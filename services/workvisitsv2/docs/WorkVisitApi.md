# \WorkVisitApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ScheduleWorkVisitServices**](WorkVisitApi.md#ScheduleWorkVisitServices) | **Post** /colocations/v2/orders/workVisits | Schedule Work Visit Services
[**UpdateAWorkVisitOrder**](WorkVisitApi.md#UpdateAWorkVisitOrder) | **Patch** /colocations/v2/orders/workVisits/{orderId} | Update a work visit order



## ScheduleWorkVisitServices

> ScheduleWorkVisitServices(ctx).WorkvisitCreate(workvisitCreate).Execute()

Schedule Work Visit Services



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/workvisitsv2"
)

func main() {
	workvisitCreate := *openapiclient.NewWorkvisitCreate(*openapiclient.NewWorkvisitCreateDetails(time.Now(), time.Now(), []openapiclient.WorkvisitAdditionalDetailsVisitorsInner{*openapiclient.NewWorkvisitAdditionalDetailsVisitorsInner([]string{"john_doe1"}, "John", "Doe", "Acme Corporation")}, []openapiclient.CagesDetails{*openapiclient.NewCagesDetails("DC2:01:123456")})) // WorkvisitCreate |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WorkVisitApi.ScheduleWorkVisitServices(context.Background()).WorkvisitCreate(workvisitCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkVisitApi.ScheduleWorkVisitServices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiScheduleWorkVisitServicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workvisitCreate** | [**WorkvisitCreate**](WorkvisitCreate.md) |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAWorkVisitOrder

> UpdateAWorkVisitOrder(ctx, orderId).ModifyRequest(modifyRequest).Execute()

Update a work visit order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/workvisitsv2"
)

func main() {
	orderId := "orderId_example" // string | Identifier of the work visit orders
	modifyRequest := *openapiclient.NewModifyRequest() // ModifyRequest | The work visit order to be updated

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.WorkVisitApi.UpdateAWorkVisitOrder(context.Background(), orderId).ModifyRequest(modifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkVisitApi.UpdateAWorkVisitOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** | Identifier of the work visit orders | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAWorkVisitOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **modifyRequest** | [**ModifyRequest**](ModifyRequest.md) | The work visit order to be updated | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

