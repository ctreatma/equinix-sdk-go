# \EIAServiceApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateEquinixInternetAccess**](EIAServiceApi.md#CreateEquinixInternetAccess) | **Post** /internetAccess/v1/services | Creates Equinix Internet Access Service
[**DeleteEquinixInternetAccess**](EIAServiceApi.md#DeleteEquinixInternetAccess) | **Delete** /internetAccess/v1/services/{serviceId} | Deletes Equinix Internet Access Service
[**GetEquinixInternetAccessServiceDetails**](EIAServiceApi.md#GetEquinixInternetAccessServiceDetails) | **Get** /internetAccess/v1/services/{serviceUuid} | Get Equinix Internet Access Service details
[**GetEquinixInternetAccessServices**](EIAServiceApi.md#GetEquinixInternetAccessServices) | **Post** /internetAccess/v1/services/search | Get Equinix Internet Access Services



## CreateEquinixInternetAccess

> Service CreateEquinixInternetAccess(ctx).ServiceRequest(serviceRequest).Execute()

Creates Equinix Internet Access Service



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
	serviceRequest := *openapiclient.NewServiceRequest(openapiclient.ServiceType("SINGLE_PORT"), openapiclient.UseCaseType("MAIN"), "WebServers", int32(10000), []openapiclient.Connection{*openapiclient.NewConnection(openapiclient.ConnectionType("IA_C"), *openapiclient.NewConnectionASide(*openapiclient.NewAccessPoint(openapiclient.AccessPointType("COLO"))))}, []openapiclient.RoutingProtocolRequest{*openapiclient.NewRoutingProtocolRequest(openapiclient.RoutingProtocolType("DIRECT"))}, *openapiclient.NewCustomerBillingAccount("2-57689234")) // ServiceRequest | Options for creating Equinix Internet Access Service product 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EIAServiceApi.CreateEquinixInternetAccess(context.Background()).ServiceRequest(serviceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EIAServiceApi.CreateEquinixInternetAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateEquinixInternetAccess`: Service
	fmt.Fprintf(os.Stdout, "Response from `EIAServiceApi.CreateEquinixInternetAccess`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateEquinixInternetAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **serviceRequest** | [**ServiceRequest**](ServiceRequest.md) | Options for creating Equinix Internet Access Service product  | 

### Return type

[**Service**](Service.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteEquinixInternetAccess

> Service DeleteEquinixInternetAccess(ctx, serviceId).DryRun(dryRun).Execute()

Deletes Equinix Internet Access Service



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
	serviceId := "919ac898-a4b9-4f9d-b684-aa09ddc65b1b" // string | Service identifier
	dryRun := true // bool | Setting this parameter to true will perform only request validation without actually deleting the service (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EIAServiceApi.DeleteEquinixInternetAccess(context.Background(), serviceId).DryRun(dryRun).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EIAServiceApi.DeleteEquinixInternetAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteEquinixInternetAccess`: Service
	fmt.Fprintf(os.Stdout, "Response from `EIAServiceApi.DeleteEquinixInternetAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serviceId** | **string** | Service identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteEquinixInternetAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **dryRun** | **bool** | Setting this parameter to true will perform only request validation without actually deleting the service | 

### Return type

[**Service**](Service.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEquinixInternetAccessServiceDetails

> ServiceDetailsResponse GetEquinixInternetAccessServiceDetails(ctx, serviceUuid).Execute()

Get Equinix Internet Access Service details



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
	serviceUuid := "919ac898-a4b9-4f9d-b684-aa09ddc65b1b" // string | Service identifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EIAServiceApi.GetEquinixInternetAccessServiceDetails(context.Background(), serviceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EIAServiceApi.GetEquinixInternetAccessServiceDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEquinixInternetAccessServiceDetails`: ServiceDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `EIAServiceApi.GetEquinixInternetAccessServiceDetails`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**serviceUuid** | **string** | Service identifier | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEquinixInternetAccessServiceDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ServiceDetailsResponse**](ServiceDetailsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEquinixInternetAccessServices

> SearchResponse GetEquinixInternetAccessServices(ctx).Offset(offset).Limit(limit).Sort(sort).SearchRequest(searchRequest).Execute()

Get Equinix Internet Access Services



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
	offset := float32(20) // float32 | Search result offset (optional)
	limit := float32(35) // float32 | Search result limit (optional)
	sort := "/name,-/type" // string | Search result sorting (optional)
	searchRequest := *openapiclient.NewSearchRequest() // SearchRequest | Search filters (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EIAServiceApi.GetEquinixInternetAccessServices(context.Background()).Offset(offset).Limit(limit).Sort(sort).SearchRequest(searchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EIAServiceApi.GetEquinixInternetAccessServices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEquinixInternetAccessServices`: SearchResponse
	fmt.Fprintf(os.Stdout, "Response from `EIAServiceApi.GetEquinixInternetAccessServices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetEquinixInternetAccessServicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **float32** | Search result offset | 
 **limit** | **float32** | Search result limit | 
 **sort** | **string** | Search result sorting | 
 **searchRequest** | [**SearchRequest**](SearchRequest.md) | Search filters | 

### Return type

[**SearchResponse**](SearchResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

