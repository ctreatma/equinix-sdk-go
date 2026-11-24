# \WorkvisitApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLocation**](WorkvisitApi.md#GetLocation) | **Get** /v1/orders/workvisit/locations | Get Work visit Locations
[**WorkVisitOrder**](WorkvisitApi.md#WorkVisitOrder) | **Post** /v1/orders/workvisit | Schedule Work Visit



## GetLocation

> GetLocation200Response GetLocation(ctx).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()

Get Work visit Locations



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/workvisitv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	detail := true // bool | When enable this flag returns detailed permission with Cage & Cabinets. (optional) (default to false)
	ibxs := "ibxs_example" // string | IBX Filter. Example: AM1, AM2 (optional)
	cages := "cages_example" // string | Cage Filter. Example: AM1:0G:00EQ (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkvisitApi.GetLocation(context.Background()).Authorization(authorization).Detail(detail).Ibxs(ibxs).Cages(cages).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkvisitApi.GetLocation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocation`: GetLocation200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkvisitApi.GetLocation`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLocationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **detail** | **bool** | When enable this flag returns detailed permission with Cage &amp; Cabinets. | [default to false]
 **ibxs** | **string** | IBX Filter. Example: AM1, AM2 | 
 **cages** | **string** | Cage Filter. Example: AM1:0G:00EQ | 

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


## WorkVisitOrder

> OrderItemResponse WorkVisitOrder(ctx).Authorization(authorization).Body(body).Execute()

Schedule Work Visit



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/workvisitv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer'.
	body := *openapiclient.NewWorkVisitRequest([]openapiclient.ContactInfo{*openapiclient.NewContactInfo(openapiclient.contactInfo_contactType("TECHNICAL"))}, *openapiclient.NewIbxLocation("AM1", []openapiclient.IbxLocationCagesInner{*openapiclient.NewIbxLocationCagesInner("AM1:0G:00E", "12345")}), *openapiclient.NewServiceDetail(*openapiclient.NewServiceDetailSchedule(time.Now(), time.Now()), []openapiclient.Visitor{*openapiclient.NewVisitor()})) // WorkVisitRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkvisitApi.WorkVisitOrder(context.Background()).Authorization(authorization).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkvisitApi.WorkVisitOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WorkVisitOrder`: OrderItemResponse
	fmt.Fprintf(os.Stdout, "Response from `WorkvisitApi.WorkVisitOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiWorkVisitOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer&#39;. | 
 **body** | [**WorkVisitRequest**](WorkVisitRequest.md) |  | 

### Return type

[**OrderItemResponse**](OrderItemResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

