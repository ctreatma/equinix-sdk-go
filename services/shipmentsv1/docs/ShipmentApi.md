# \ShipmentApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLocation**](ShipmentApi.md#GetLocation) | **Get** /v1/orders/shipment/locations | Get Locations(ibx, cage) Details for Shipment  Based on Place Shipment Permission for User
[**OutboundShipmentSubmit**](ShipmentApi.md#OutboundShipmentSubmit) | **Post** /v1/orders/shipment/outbound | Created Outbound Shipment.
[**ShipmentInbound**](ShipmentApi.md#ShipmentInbound) | **Post** /v1/orders/shipment/inbound | Inbound Shipment Order
[**ShipmentPending**](ShipmentApi.md#ShipmentPending) | **Post** /v1/orders/shipment/pendingStorage | Pending Storage Order



## GetLocation

> GetLocation200Response GetLocation(ctx).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()

Get Locations(ibx, cage) Details for Shipment  Based on Place Shipment Permission for User



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	detail := true // bool | When enable this flag returns detailed permission with Cage & Cabinets. Default value is false (optional)
	ibxs := "ibxs_example" // string |  (optional)
	cages := "cages_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentApi.GetLocation(context.Background()).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentApi.GetLocation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocation`: GetLocation200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentApi.GetLocation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLocationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **detail** | **bool** | When enable this flag returns detailed permission with Cage &amp; Cabinets. Default value is false | 
 **ibxs** | **string** |  | 
 **cages** | **string** |  | 

### Return type

[**GetLocation200Response**](GetLocation200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OutboundShipmentSubmit

> ShipmentOrderResponse OutboundShipmentSubmit(ctx).Authorization(authorization).Body(body).Execute()

Created Outbound Shipment.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	body := *openapiclient.NewOutboundShipmentRequest([]openapiclient.ContactInfo{*openapiclient.NewContactInfo(openapiclient.contactInfo_contactType("TECHNICAL"))}, *openapiclient.NewIbxLocation("Ibx_example", []openapiclient.IbxLocationCagesInner{*openapiclient.NewIbxLocationCagesInner("Cage_example", "AccountNumber_example")}), *openapiclient.NewOutboundServiceDetail(time.Now(), *openapiclient.NewOutboundServiceDetailShipmentDetails(openapiclient.outboundServiceDetail_shipmentDetails_outboundType("CARRIER")))) // OutboundShipmentRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentApi.OutboundShipmentSubmit(context.Background()).Authorization(authorization).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentApi.OutboundShipmentSubmit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OutboundShipmentSubmit`: ShipmentOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentApi.OutboundShipmentSubmit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOutboundShipmentSubmitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **body** | [**OutboundShipmentRequest**](OutboundShipmentRequest.md) |  | 

### Return type

[**ShipmentOrderResponse**](ShipmentOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ShipmentInbound

> ShipmentOrderResponse ShipmentInbound(ctx).Authorization(authorization).Body(body).Execute()

Inbound Shipment Order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	body := *openapiclient.NewInboundShipmentRequest([]openapiclient.ContactInfo{*openapiclient.NewContactInfo(openapiclient.contactInfo_contactType("TECHNICAL"))}, *openapiclient.NewIbxLocation("Ibx_example", []openapiclient.IbxLocationCagesInner{*openapiclient.NewIbxLocationCagesInner("Cage_example", "AccountNumber_example")}), *openapiclient.NewInboundServiceDetail(*openapiclient.NewInboundServiceDetailShipmentDetails(int32(123), openapiclient.inboundServiceDetail_shipmentDetails_inboundType("CARRIER")), time.Now())) // InboundShipmentRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentApi.ShipmentInbound(context.Background()).Authorization(authorization).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentApi.ShipmentInbound``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShipmentInbound`: ShipmentOrderResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentApi.ShipmentInbound`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShipmentInboundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **body** | [**InboundShipmentRequest**](InboundShipmentRequest.md) |  | 

### Return type

[**ShipmentOrderResponse**](ShipmentOrderResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ShipmentPending

> []PendingStorageOrderResponseInner ShipmentPending(ctx).Authorization(authorization).Body(body).Execute()

Pending Storage Order



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/shipmentsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	body := *openapiclient.NewPendingStorageRequest([]openapiclient.PendingStorageRequestShipmentDetailsInner{*openapiclient.NewPendingStorageRequestShipmentDetailsInner("StorageId_example", "Cage_example", "AccountNumber_example", false)}, []openapiclient.ContactInfo{*openapiclient.NewContactInfo(openapiclient.contactInfo_contactType("TECHNICAL"))}) // PendingStorageRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentApi.ShipmentPending(context.Background()).Authorization(authorization).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentApi.ShipmentPending``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ShipmentPending`: []PendingStorageOrderResponseInner
	fmt.Fprintf(os.Stdout, "Response from `ShipmentApi.ShipmentPending`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiShipmentPendingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **body** | [**PendingStorageRequest**](PendingStorageRequest.md) |  | 

### Return type

[**[]PendingStorageOrderResponseInner**](PendingStorageOrderResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

