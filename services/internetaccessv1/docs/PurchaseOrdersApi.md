# \PurchaseOrdersApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPurchaseOrder**](PurchaseOrdersApi.md#GetPurchaseOrder) | **Get** /internetAccess/v1/accounts/{accountNumber}/purchaseOrders/{number} | Get specified purchase order
[**GetPurchaseOrders**](PurchaseOrdersApi.md#GetPurchaseOrders) | **Get** /internetAccess/v1/accounts/{accountNumber}/purchaseOrders | List purchase orders



## GetPurchaseOrder

> PurchaseOrder GetPurchaseOrder(ctx, accountNumber, number).Execute()

Get specified purchase order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	accountNumber := "100013200" // string | Number of account to search by
	number := "PO-1234567" // string | purchase order number

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersApi.GetPurchaseOrder(context.Background(), accountNumber, number).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersApi.GetPurchaseOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPurchaseOrder`: PurchaseOrder
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersApi.GetPurchaseOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountNumber** | **string** | Number of account to search by | 
**number** | **string** | purchase order number | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPurchaseOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PurchaseOrder**](PurchaseOrder.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPurchaseOrders

> PurchaseOrdersPage GetPurchaseOrders(ctx, accountNumber).LocationsIbx(locationsIbx).Category(category).Offset(offset).Limit(limit).Execute()

List purchase orders



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	accountNumber := "100013200" // string | Number of account to search by
	locationsIbx := "WA1" // string | IBX code (optional)
	category := openapiclient.getPurchaseOrders_category_parameter("ALL_SERVICES") // GetPurchaseOrdersCategoryParameter | product category (optional) (default to "INTERCONNECTION")
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PurchaseOrdersApi.GetPurchaseOrders(context.Background(), accountNumber).LocationsIbx(locationsIbx).Category(category).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PurchaseOrdersApi.GetPurchaseOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPurchaseOrders`: PurchaseOrdersPage
	fmt.Fprintf(os.Stdout, "Response from `PurchaseOrdersApi.GetPurchaseOrders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountNumber** | **string** | Number of account to search by | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPurchaseOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **locationsIbx** | **string** | IBX code | 
 **category** | [**GetPurchaseOrdersCategoryParameter**](GetPurchaseOrdersCategoryParameter.md) | product category | [default to &quot;INTERCONNECTION&quot;]
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**PurchaseOrdersPage**](PurchaseOrdersPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

