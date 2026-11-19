# \TroubleTicketCaseApi

All URIs are relative to *https://app.swaggerhub.com/apis-docs/equinix-api/case-management/1.6.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelTicket**](TroubleTicketCaseApi.md#CancelTicket) | **Post** /support/v2/tickets/{id}/cancel | Cancel a trouble ticket by case / order number
[**CreateTicketsV2**](TroubleTicketCaseApi.md#CreateTicketsV2) | **Post** /support/v2/tickets | Create a trouble ticket / case
[**GetTicketDetails**](TroubleTicketCaseApi.md#GetTicketDetails) | **Get** /support/v2/tickets/{id} | Get a trouble ticket by case / order number
[**ModifyTicketDetailsByCaseNumber**](TroubleTicketCaseApi.md#ModifyTicketDetailsByCaseNumber) | **Post** /support/v1/tickets/{caseNumber}/notes | Modify a case by case number
[**ModifyTicketDetailsById**](TroubleTicketCaseApi.md#ModifyTicketDetailsById) | **Post** /support/v2/tickets/{id}/notes | Modify a ticket by ID



## CancelTicket

> CancelCaseResponse CancelTicket(ctx, id).CancelCase(cancelCase).Execute()

Cancel a trouble ticket by case / order number



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
	id := "id_example" // string | Case or Order Number.
	cancelCase := *openapiclient.NewCancelCase("This is a reason!") // CancelCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleTicketCaseApi.CancelTicket(context.Background(), id).CancelCase(cancelCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleTicketCaseApi.CancelTicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelTicket`: CancelCaseResponse
	fmt.Fprintf(os.Stdout, "Response from `TroubleTicketCaseApi.CancelTicket`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelTicketRequest struct via the builder pattern


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


## CreateTicketsV2

> TicketResponse CreateTicketsV2(ctx).TroubleTicketOrCase(troubleTicketOrCase).Execute()

Create a trouble ticket / case



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
	troubleTicketOrCase := *openapiclient.NewTroubleTicketOrCase(openapiclient.TroubleTicketOrCase_code("0000-0000"), "The device is overheating and causing performance issues.") // TroubleTicketOrCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleTicketCaseApi.CreateTicketsV2(context.Background()).TroubleTicketOrCase(troubleTicketOrCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleTicketCaseApi.CreateTicketsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTicketsV2`: TicketResponse
	fmt.Fprintf(os.Stdout, "Response from `TroubleTicketCaseApi.CreateTicketsV2`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTicketsV2Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **troubleTicketOrCase** | [**TroubleTicketOrCase**](TroubleTicketOrCase.md) |  | 

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


## GetTicketDetails

> SingleCaseResponseV2 GetTicketDetails(ctx, id).Execute()

Get a trouble ticket by case / order number



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
	id := "id_example" // string | Case or Order Number.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleTicketCaseApi.GetTicketDetails(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleTicketCaseApi.GetTicketDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTicketDetails`: SingleCaseResponseV2
	fmt.Fprintf(os.Stdout, "Response from `TroubleTicketCaseApi.GetTicketDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTicketDetailsRequest struct via the builder pattern


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
	resp, r, err := apiClient.TroubleTicketCaseApi.ModifyTicketDetailsByCaseNumber(context.Background(), caseNumber).ModifyCase(modifyCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleTicketCaseApi.ModifyTicketDetailsByCaseNumber``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ModifyTicketDetailsByCaseNumber`: ModifyCaseResponse
	fmt.Fprintf(os.Stdout, "Response from `TroubleTicketCaseApi.ModifyTicketDetailsByCaseNumber`: %v\n", resp)
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


## ModifyTicketDetailsById

> ModifyTicketResponse ModifyTicketDetailsById(ctx, id).ModifyCase(modifyCase).Execute()

Modify a ticket by ID



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
	id := "id_example" // string | Case or Order Number.
	modifyCase := *openapiclient.NewModifyCase("This is a notes!") // ModifyCase |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleTicketCaseApi.ModifyTicketDetailsById(context.Background(), id).ModifyCase(modifyCase).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleTicketCaseApi.ModifyTicketDetailsById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ModifyTicketDetailsById`: ModifyTicketResponse
	fmt.Fprintf(os.Stdout, "Response from `TroubleTicketCaseApi.ModifyTicketDetailsById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Case or Order Number. | 

### Other Parameters

Other parameters are passed through a pointer to a apiModifyTicketDetailsByIdRequest struct via the builder pattern


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

