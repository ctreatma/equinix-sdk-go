# \TroubleticketApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLocation**](TroubleticketApi.md#GetLocation) | **Get** /v1/orders/troubleticket/locations | Get Locations(ibx, cage) Details for Trouble Ticket  Based on Trouble Ticket Permission for User
[**GetTroubleTicketType**](TroubleticketApi.md#GetTroubleTicketType) | **Get** /v1/orders/troubleticket/types | Get list of all Equinix Trouble Ticket Types
[**PlaceTroubleTicketOrder**](TroubleticketApi.md#PlaceTroubleTicketOrder) | **Post** /v1/orders/troubleticket | If you are experiencing an issue that is impacting your service, please enter your information and submit a trouble ticket



## GetLocation

> GetLocation200Response GetLocation(ctx).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()

Get Locations(ibx, cage) Details for Trouble Ticket  Based on Trouble Ticket Permission for User



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/troubleticketv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	detail := true // bool | When enable this flag returns detailed permission with Cage & Cabinets. (optional) (default to false)
	ibxs := "ibxs_example" // string | CH1 (optional)
	cages := "cages_example" // string | Eg: CH1:01:0101 (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleticketApi.GetLocation(context.Background()).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleticketApi.GetLocation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocation`: GetLocation200Response
	fmt.Fprintf(os.Stdout, "Response from `TroubleticketApi.GetLocation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLocationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **detail** | **bool** | When enable this flag returns detailed permission with Cage &amp; Cabinets. | [default to false]
 **ibxs** | **string** | CH1 | 
 **cages** | **string** | Eg: CH1:01:0101 | 

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


## GetTroubleTicketType

> GetTroubleTicketType200Response GetTroubleTicketType(ctx).Authorization(authorization).Category(category).Execute()

Get list of all Equinix Trouble Ticket Types



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/troubleticketv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	category := openapiclient.getTroubleTicketType_category_parameter("Cross Connect") // GetTroubleTicketTypeCategoryParameter | To get results by trouble ticket category. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleticketApi.GetTroubleTicketType(context.Background()).Authorization(authorization).Category(category).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleticketApi.GetTroubleTicketType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTroubleTicketType`: GetTroubleTicketType200Response
	fmt.Fprintf(os.Stdout, "Response from `TroubleticketApi.GetTroubleTicketType`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTroubleTicketTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **category** | [**GetTroubleTicketTypeCategoryParameter**](GetTroubleTicketTypeCategoryParameter.md) | To get results by trouble ticket category. | 

### Return type

[**GetTroubleTicketType200Response**](GetTroubleTicketType200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PlaceTroubleTicketOrder

> TroubleTicketResponse PlaceTroubleTicketOrder(ctx).Authorization(authorization).Body(body).Execute()

If you are experiencing an issue that is impacting your service, please enter your information and submit a trouble ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/troubleticketv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	body := *openapiclient.NewTroubleTicketOrderRequest(*openapiclient.NewIbxLocation("AM1", []openapiclient.IbxLocationCagesInner{*openapiclient.NewIbxLocationCagesInner("AM1:01:001MC3", "12345")}), []openapiclient.ContactInfo{*openapiclient.NewContactInfo(openapiclient.contactInfo_contactType("TECHNICAL"))}, *openapiclient.NewTroubleTicketOrderRequestServiceDetails(time.Now(), openapiclient.TroubleTicketOrderRequest_serviceDetails_problemCode("cc01"))) // TroubleTicketOrderRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TroubleticketApi.PlaceTroubleTicketOrder(context.Background()).Authorization(authorization).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TroubleticketApi.PlaceTroubleTicketOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PlaceTroubleTicketOrder`: TroubleTicketResponse
	fmt.Fprintf(os.Stdout, "Response from `TroubleticketApi.PlaceTroubleTicketOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPlaceTroubleTicketOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **body** | [**TroubleTicketOrderRequest**](TroubleTicketOrderRequest.md) |  | 

### Return type

[**TroubleTicketResponse**](TroubleTicketResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

