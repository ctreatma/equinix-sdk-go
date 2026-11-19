# \CaseApi

All URIs are relative to *https://app.swaggerhub.com/apis-docs/equinix-api/case-management/1.6.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DownloadAttachment**](CaseApi.md#DownloadAttachment) | **Get** /support/v2/tickets/attachment/download/{caseId}/{attachmentId} | Download an attachment by case ID and attachment ID
[**GetEmailDetailsByCaseNumber**](CaseApi.md#GetEmailDetailsByCaseNumber) | **Get** /support/v1/tickets/emailDetails/{emailId}/caseNumber/{caseNumber} | Get email details by email ID and case number



## DownloadAttachment

> *os.File DownloadAttachment(ctx, caseId, attachmentId).Execute()

Download an attachment by case ID and attachment ID



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/supportv2"
)

func main() {
	caseId := "caseId_example" // string | Case Number.
	attachmentId := "attachmentId_example" // string | Attachment ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.DownloadAttachment(context.Background(), caseId, attachmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.DownloadAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadAttachment`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.DownloadAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**caseId** | **string** | Case Number. | 
**attachmentId** | **string** | Attachment ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[***os.File**](*os.File.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEmailDetailsByCaseNumber

> EmailDetailsResponse GetEmailDetailsByCaseNumber(ctx, caseNumber, emailId).Execute()

Get email details by email ID and case number



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/supportv2"
)

func main() {
	caseNumber := "caseNumber_example" // string | Case Number.
	emailId := "emailId_example" // string | Email ID.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.GetEmailDetailsByCaseNumber(context.Background(), caseNumber, emailId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.GetEmailDetailsByCaseNumber``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEmailDetailsByCaseNumber`: EmailDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.GetEmailDetailsByCaseNumber`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**caseNumber** | **string** | Case Number. | 
**emailId** | **string** | Email ID. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEmailDetailsByCaseNumberRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**EmailDetailsResponse**](EmailDetailsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

