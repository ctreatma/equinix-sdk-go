# \ShipmentsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ScheduleInboundOrOutboundShipment**](ShipmentsApi.md#ScheduleInboundOrOutboundShipment) | **Post** /colocations/v2/orders/shipments | Schedule inbound or outbound shipment
[**UpdateInboundOrOutboundShipment**](ShipmentsApi.md#UpdateInboundOrOutboundShipment) | **Patch** /colocations/v2/orders/shipments/{orderId} | Update inbound or outbound shipment



## ScheduleInboundOrOutboundShipment

> ScheduleInboundOrOutboundShipment(ctx).ShipmentCreate(shipmentCreate).Execute()

Schedule inbound or outbound shipment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv2"
)

func main() {
	shipmentCreate := *openapiclient.NewShipmentCreate(openapiclient.Shipment_Create_type("INBOUND"), time.Now(), "DC2:01:001030", openapiclient.Shipment_Create_details{InboundShipmentsCreate: openapiclient.NewInboundShipmentsCreate(openapiclient.InboundShipments_allOf_carrier("DHL"), []string{"123466ABCXYZ"}, float32(10))}) // ShipmentCreate |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ShipmentsApi.ScheduleInboundOrOutboundShipment(context.Background()).ShipmentCreate(shipmentCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsApi.ScheduleInboundOrOutboundShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiScheduleInboundOrOutboundShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **shipmentCreate** | [**ShipmentCreate**](ShipmentCreate.md) |  | 

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


## UpdateInboundOrOutboundShipment

> UpdateInboundOrOutboundShipment(ctx, orderId).ShipmentModifyRequest(shipmentModifyRequest).Execute()

Update inbound or outbound shipment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv2"
)

func main() {
	orderId := "orderId_example" // string | Identifier of the shipments order
	shipmentModifyRequest := *openapiclient.NewShipmentModifyRequest() // ShipmentModifyRequest | The Shipment to be updated

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ShipmentsApi.UpdateInboundOrOutboundShipment(context.Background(), orderId).ShipmentModifyRequest(shipmentModifyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsApi.UpdateInboundOrOutboundShipment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** | Identifier of the shipments order | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInboundOrOutboundShipmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **shipmentModifyRequest** | [**ShipmentModifyRequest**](ShipmentModifyRequest.md) | The Shipment to be updated | 

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

