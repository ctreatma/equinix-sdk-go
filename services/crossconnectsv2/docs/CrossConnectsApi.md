# \CrossConnectsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrderCrossConnects**](CrossConnectsApi.md#OrderCrossConnects) | **Post** /colocations/v2/orders/crossConnects | Order cross connects
[**PlaceCrossConnectDeinstallationOrder**](CrossConnectsApi.md#PlaceCrossConnectDeinstallationOrder) | **Post** /colocations/v2/orders/crossConnects/deinstall | Place cross connect deinstallation order
[**UpdateACrossConnectOrder**](CrossConnectsApi.md#UpdateACrossConnectOrder) | **Patch** /colocations/v2/orders/crossConnects/{orderId} | Update a cross connects order



## OrderCrossConnects

> OrderCrossConnects(ctx).Layer1Create(layer1Create).Execute()

Order cross connects



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/crossconnectsv2"
)

func main() {
	layer1Create := *openapiclient.NewLayer1Create([]openapiclient.Layer1Details{*openapiclient.NewLayer1Details(*openapiclient.NewASide(*openapiclient.NewPatchPanel("Id_example"), openapiclient.Connection_services("COAX"), openapiclient.media_types("COAX"), openapiclient.protocol_types("ANTENNA"), openapiclient.connector_types("BNC")), openapiclient.zSide{ZSideWithLOA: openapiclient.NewZSideWithLOA("8d0bef9c-cca9-11ea-87d0-0242ac130003", "Ibx_example", "Carigan Communications  ")})}) // Layer1Create |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CrossConnectsApi.OrderCrossConnects(context.Background()).Layer1Create(layer1Create).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrossConnectsApi.OrderCrossConnects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrderCrossConnectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **layer1Create** | [**Layer1Create**](Layer1Create.md) |  | 

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


## PlaceCrossConnectDeinstallationOrder

> PlaceCrossConnectDeinstallationOrder(ctx).Layer1DeinstallRequest(layer1DeinstallRequest).Execute()

Place cross connect deinstallation order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/crossconnectsv2"
)

func main() {
	layer1DeinstallRequest := *openapiclient.NewLayer1DeinstallRequest([]openapiclient.Layer1DeinstallDetails{*openapiclient.NewLayer1DeinstallDetails("4-1234567890")}, time.Now()) // Layer1DeinstallRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CrossConnectsApi.PlaceCrossConnectDeinstallationOrder(context.Background()).Layer1DeinstallRequest(layer1DeinstallRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrossConnectsApi.PlaceCrossConnectDeinstallationOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlaceCrossConnectDeinstallationOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **layer1DeinstallRequest** | [**Layer1DeinstallRequest**](Layer1DeinstallRequest.md) |  | 

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


## UpdateACrossConnectOrder

> UpdateACrossConnectOrder(ctx, orderId).ModifyRequest(modifyRequest).Execute()

Update a cross connects order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/crossconnectsv2"
)

func main() {
	orderId := "orderId_example" // string | Identifier of the cross connect order
	modifyRequest := *openapiclient.NewModifyRequest() // ModifyRequest | The cross connect to be updated

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CrossConnectsApi.UpdateACrossConnectOrder(context.Background(), orderId).ModifyRequest(modifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrossConnectsApi.UpdateACrossConnectOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** | Identifier of the cross connect order | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateACrossConnectOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **modifyRequest** | [**ModifyRequest**](ModifyRequest.md) | The cross connect to be updated | 

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

