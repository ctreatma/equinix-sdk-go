# \ProductAvailabilityApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetIbx**](ProductAvailabilityApi.md#GetIbx) | **Get** /internetAccess/v1/ibxs/{ibx} | Returns requested IBX where EIA is available
[**GetIbxs**](ProductAvailabilityApi.md#GetIbxs) | **Get** /internetAccess/v1/ibxs | Returns IBXs where EIA is available



## GetIbx

> Ibx GetIbx(ctx, ibx).ServiceConnectionType(serviceConnectionType).ConnectionAsideAccessPointType(connectionAsideAccessPointType).Execute()

Returns requested IBX where EIA is available



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
	ibx := "WA1" // string | Ibx code
	serviceConnectionType := openapiclient.getIbx_service_connection_type_parameter("IA_C") // GetIbxServiceConnectionTypeParameter | Service connection type (physical, virtual) (optional)
	connectionAsideAccessPointType := openapiclient.getIbx_connection_aside_accessPoint_type_parameter("COLO") // GetIbxConnectionAsideAccessPointTypeParameter | Service connection access point type. When not provided, COLO type is used by default. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAvailabilityApi.GetIbx(context.Background(), ibx).ServiceConnectionType(serviceConnectionType).ConnectionAsideAccessPointType(connectionAsideAccessPointType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAvailabilityApi.GetIbx``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIbx`: Ibx
	fmt.Fprintf(os.Stdout, "Response from `ProductAvailabilityApi.GetIbx`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ibx** | **string** | Ibx code | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIbxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceConnectionType** | [**GetIbxServiceConnectionTypeParameter**](GetIbxServiceConnectionTypeParameter.md) | Service connection type (physical, virtual) | 
 **connectionAsideAccessPointType** | [**GetIbxConnectionAsideAccessPointTypeParameter**](GetIbxConnectionAsideAccessPointTypeParameter.md) | Service connection access point type. When not provided, COLO type is used by default. | 

### Return type

[**Ibx**](Ibx.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIbxs

> IbxPage GetIbxs(ctx).ServiceConnectionType(serviceConnectionType).Offset(offset).Limit(limit).ConnectionAsideAccessPointType(connectionAsideAccessPointType).Execute()

Returns IBXs where EIA is available



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
	serviceConnectionType := openapiclient.getIbxs_service_connection_type_parameter("IA_C") // GetIbxsServiceConnectionTypeParameter | Service connection type (physical, virtual)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)
	connectionAsideAccessPointType := openapiclient.getIbx_connection_aside_accessPoint_type_parameter("COLO") // GetIbxConnectionAsideAccessPointTypeParameter | Service connection access point type. When not provided, COLO type is used by default. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProductAvailabilityApi.GetIbxs(context.Background()).ServiceConnectionType(serviceConnectionType).Offset(offset).Limit(limit).ConnectionAsideAccessPointType(connectionAsideAccessPointType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProductAvailabilityApi.GetIbxs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIbxs`: IbxPage
	fmt.Fprintf(os.Stdout, "Response from `ProductAvailabilityApi.GetIbxs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetIbxsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **serviceConnectionType** | [**GetIbxsServiceConnectionTypeParameter**](GetIbxsServiceConnectionTypeParameter.md) | Service connection type (physical, virtual) | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]
 **connectionAsideAccessPointType** | [**GetIbxConnectionAsideAccessPointTypeParameter**](GetIbxConnectionAsideAccessPointTypeParameter.md) | Service connection access point type. When not provided, COLO type is used by default. | 

### Return type

[**IbxPage**](IbxPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

