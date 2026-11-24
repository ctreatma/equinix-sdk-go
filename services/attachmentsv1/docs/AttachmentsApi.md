# \AttachmentsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAttachment**](AttachmentsApi.md#CreateAttachment) | **Post** /v1/attachments/file | Upload a Multipart File
[**DeleteAttachment**](AttachmentsApi.md#DeleteAttachment) | **Delete** /v1/attachments/{attachmentId} | Delete Attachment by Id
[**GetAttachedFile**](AttachmentsApi.md#GetAttachedFile) | **Get** /v1/attachments/{attachmentId}/file | Download Attachment File
[**GetAttachment**](AttachmentsApi.md#GetAttachment) | **Get** /v1/attachments/{attachmentId} | Get Attachment by Id
[**GetAttachments**](AttachmentsApi.md#GetAttachments) | **Get** /v1/attachments | Get List of Attachments



## CreateAttachment

> Attachment CreateAttachment(ctx).Authorization(authorization).UploadFile(uploadFile).Purpose(purpose).Execute()

Upload a Multipart File



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/attachmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.
	uploadFile := os.NewFile(1234, "some_file") // *os.File | The file to be uploaded
	purpose := openapiclient.createAttachment_purpose_parameter("LOA") // CreateAttachmentPurposeParameter | Purpose of the file is uploaded. [ ex. LOA is for Cross connect, PO is for Purchar order ] (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentsApi.CreateAttachment(context.Background()).Authorization(authorization).UploadFile(uploadFile).Purpose(purpose).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentsApi.CreateAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAttachment`: Attachment
	fmt.Fprintf(os.Stdout, "Response from `AttachmentsApi.CreateAttachment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 
 **uploadFile** | ***os.File** | The file to be uploaded | 
 **purpose** | [**CreateAttachmentPurposeParameter**](CreateAttachmentPurposeParameter.md) | Purpose of the file is uploaded. [ ex. LOA is for Cross connect, PO is for Purchar order ] | 

### Return type

[**Attachment**](Attachment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAttachment

> Status DeleteAttachment(ctx, attachmentId).Authorization(authorization).Execute()

Delete Attachment by Id



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/attachmentsv1"
)

func main() {
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The id of the attachment.
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentsApi.DeleteAttachment(context.Background(), attachmentId).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentsApi.DeleteAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAttachment`: Status
	fmt.Fprintf(os.Stdout, "Response from `AttachmentsApi.DeleteAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** | The id of the attachment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 

### Return type

[**Status**](Status.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAttachedFile

> GetAttachedFile(ctx, attachmentId).Authorization(authorization).Execute()

Download Attachment File



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/attachmentsv1"
)

func main() {
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The id of the attachment record you want to get binary data from.
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AttachmentsApi.GetAttachedFile(context.Background(), attachmentId).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentsApi.GetAttachedFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** | The id of the attachment record you want to get binary data from. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAttachedFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAttachment

> Attachment GetAttachment(ctx, attachmentId).Authorization(authorization).Execute()

Get Attachment by Id



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/attachmentsv1"
)

func main() {
	attachmentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The id of the attachment.
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentsApi.GetAttachment(context.Background(), attachmentId).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentsApi.GetAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAttachment`: Attachment
	fmt.Fprintf(os.Stdout, "Response from `AttachmentsApi.GetAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **string** | The id of the attachment. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 

### Return type

[**Attachment**](Attachment.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAttachments

> Records GetAttachments(ctx).Authorization(authorization).Offset(offset).Limit(limit).AttachmentIds(attachmentIds).Execute()

Get List of Attachments



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/attachmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.
	offset := int32(56) // int32 | Page number to skip the results (optional) (default to 0)
	limit := int32(56) // int32 | Number of expected records in the response (optional) (default to 20)
	attachmentIds := []string{"Inner_example"} // []string | Comma separated attachment ids to search (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttachmentsApi.GetAttachments(context.Background()).Authorization(authorization).Offset(offset).Limit(limit).AttachmentIds(attachmentIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttachmentsApi.GetAttachments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAttachments`: Records
	fmt.Fprintf(os.Stdout, "Response from `AttachmentsApi.GetAttachments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAttachmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 
 **offset** | **int32** | Page number to skip the results | [default to 0]
 **limit** | **int32** | Number of expected records in the response | [default to 20]
 **attachmentIds** | **[]string** | Comma separated attachment ids to search | 

### Return type

[**Records**](Records.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

