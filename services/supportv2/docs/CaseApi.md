# \CaseApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelCaseById**](CaseApi.md#CancelCaseById) | **Post** /support/v2/tickets/{id}/cancel | Cancel Case
[**DownloadAttachment**](CaseApi.md#DownloadAttachment) | **Get** /support/v2/tickets/attachment/download/{caseId}/{attachmentId} | Download an attachment by case ID and attachment ID
[**GetCaseDetailsById**](CaseApi.md#GetCaseDetailsById) | **Get** /support/v2/tickets/{id} | Get Case Details
[**GetEmailDetailsByCaseNumber**](CaseApi.md#GetEmailDetailsByCaseNumber) | **Get** /support/v1/tickets/emailDetails/{emailId}/caseNumber/{caseNumber} | Get email details by email ID and case number
[**GetTicketCodeRequestSchema**](CaseApi.md#GetTicketCodeRequestSchema) | **Get** /support/v2/tickets/codes/{code}/schema | Get Request Schema And Example By Ticket Code
[**ListTicketCodes**](CaseApi.md#ListTicketCodes) | **Get** /support/v2/tickets/codes | Get Ticket Codes
[**ModifyCaseById**](CaseApi.md#ModifyCaseById) | **Post** /support/v2/tickets/{id}/notes | Modify Case
[**ModifyTicketDetailsByCaseNumber**](CaseApi.md#ModifyTicketDetailsByCaseNumber) | **Post** /support/v1/tickets/{caseNumber}/notes | Modify a case by case number
[**SubmitCase**](CaseApi.md#SubmitCase) | **Post** /support/v2/tickets | Create case



## CancelCaseById

> CancelCaseResponse CancelCaseById(ctx, id).CancelCase(cancelCase).Execute()

Cancel Case



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
	id := "11150929" // string | Case or Order Number.
	cancelCase := *openapiclient.NewCancelCase("This is a reason!") // CancelCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.CancelCaseById(context.Background(), id).CancelCase(cancelCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.CancelCaseById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelCaseById`: CancelCaseResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.CancelCaseById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelCaseByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cancelCase** | [**CancelCase**](CancelCase.md) |  | 

### Return type

[**CancelCaseResponse**](CancelCaseResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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
	attachmentId := "c77c5f58-a7ea-4e88-9fc4-1a2900027425" // string | Attachment ID.

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
- **Accept**: application/octet-stream, Content-Disposition, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCaseDetailsById

> SingleCaseResponseV2 GetCaseDetailsById(ctx, id).Execute()

Get Case Details



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
	id := "11150929" // string | Case or Order Number.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.GetCaseDetailsById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.GetCaseDetailsById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCaseDetailsById`: SingleCaseResponseV2
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.GetCaseDetailsById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCaseDetailsByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SingleCaseResponseV2**](SingleCaseResponseV2.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

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


## GetTicketCodeRequestSchema

> RequestSchemaResponse GetTicketCodeRequestSchema(ctx, code).Execute()

Get Request Schema And Example By Ticket Code



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
	code := "0000-0000" // string | The ticket code to retrieve the request payload schema and sample request payload. See GET /support/v2/tickets/codes for the list of available ticket codes.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.GetTicketCodeRequestSchema(context.Background(), code).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.GetTicketCodeRequestSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTicketCodeRequestSchema`: RequestSchemaResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.GetTicketCodeRequestSchema`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**code** | **string** | The ticket code to retrieve the request payload schema and sample request payload. See GET /support/v2/tickets/codes for the list of available ticket codes. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTicketCodeRequestSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RequestSchemaResponse**](RequestSchemaResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTicketCodes

> TicketCodeList ListTicketCodes(ctx).Limit(limit).Offset(offset).Categories(categories).Execute()

Get Ticket Codes



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
	limit := int32(10) // int32 | Maximum number of ticket codes to return per page. (optional)
	offset := int32(0) // int32 | Zero-based index of the first ticket code to return. (optional)
	categories := []openapiclient.ListTicketCodesCategoriesParameterInner{openapiclient.listTicketCodes_categories_parameter_inner("IBX_DATA_CENTERS")} // []ListTicketCodesCategoriesParameterInner | Filter results to the specified product categories. Accepts a comma-separated list (e.g. `?categories=FABRIC,NETWORK_EDGE`). Omit to return all categories permitted for the caller.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.ListTicketCodes(context.Background()).Limit(limit).Offset(offset).Categories(categories).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.ListTicketCodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTicketCodes`: TicketCodeList
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.ListTicketCodes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTicketCodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Maximum number of ticket codes to return per page. | 
 **offset** | **int32** | Zero-based index of the first ticket code to return. | 
 **categories** | [**[]ListTicketCodesCategoriesParameterInner**](ListTicketCodesCategoriesParameterInner.md) | Filter results to the specified product categories. Accepts a comma-separated list (e.g. &#x60;?categories&#x3D;FABRIC,NETWORK_EDGE&#x60;). Omit to return all categories permitted for the caller.  | 

### Return type

[**TicketCodeList**](TicketCodeList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ModifyCaseById

> ModifyTicketResponse ModifyCaseById(ctx, id).ModifyCase(modifyCase).Execute()

Modify Case



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
	id := "11150929" // string | Case or Order Number.
	modifyCase := *openapiclient.NewModifyCase("This is a notes!") // ModifyCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.ModifyCaseById(context.Background(), id).ModifyCase(modifyCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.ModifyCaseById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ModifyCaseById`: ModifyTicketResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.ModifyCaseById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiModifyCaseByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **modifyCase** | [**ModifyCase**](ModifyCase.md) |  | 

### Return type

[**ModifyTicketResponse**](ModifyTicketResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ModifyTicketDetailsByCaseNumber

> ModifyCaseResponse ModifyTicketDetailsByCaseNumber(ctx, caseNumber).ModifyCase(modifyCase).Execute()

Modify a case by case number



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
	caseNumber := "caseNumber_example" // string | Case number.
	modifyCase := *openapiclient.NewModifyCase("This is a notes!") // ModifyCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.ModifyTicketDetailsByCaseNumber(context.Background(), caseNumber).ModifyCase(modifyCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.ModifyTicketDetailsByCaseNumber``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ModifyTicketDetailsByCaseNumber`: ModifyCaseResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.ModifyTicketDetailsByCaseNumber`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**caseNumber** | **string** | Case number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiModifyTicketDetailsByCaseNumberRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **modifyCase** | [**ModifyCase**](ModifyCase.md) |  | 

### Return type

[**ModifyCaseResponse**](ModifyCaseResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitCase

> TicketResponse SubmitCase(ctx).Case_(case_).Execute()

Create case



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
	case_ := *openapiclient.NewCase("0200-0000", "The device is overheating and causing performance issues.") // Case |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CaseApi.SubmitCase(context.Background()).Case_(case_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CaseApi.SubmitCase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitCase`: TicketResponse
	fmt.Fprintf(os.Stdout, "Response from `CaseApi.SubmitCase`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubmitCaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **case_** | [**Case**](Case.md) |  | 

### Return type

[**TicketResponse**](TicketResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

