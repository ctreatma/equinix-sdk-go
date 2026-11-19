# \EIAOrderApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetOrder**](EIAOrderApi.md#GetOrder) | **Get** /internetAccess/v1/orders/{orderUUID} | Returns EIA Order details



## GetOrder

> OrderDetails GetOrder(ctx, orderUUID).Execute()

Returns EIA Order details



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
	orderUUID := "d27c0f84-f1da-498e-95c0-f3d3ae02d16d" // string | UUID of the checked order

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EIAOrderApi.GetOrder(context.Background(), orderUUID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EIAOrderApi.GetOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrder`: OrderDetails
	fmt.Fprintf(os.Stdout, "Response from `EIAOrderApi.GetOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderUUID** | **string** | UUID of the checked order | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OrderDetails**](OrderDetails.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

