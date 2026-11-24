# \DownloadImageApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetDownloadImageByDeviceType**](DownloadImageApi.md#GetDownloadImageByDeviceType) | **Post** /ne/v1/devices/{deviceType}/repositories/{version}/download | Download an Image
[**GetDownloadableImagesByDeviceType**](DownloadImageApi.md#GetDownloadableImagesByDeviceType) | **Get** /ne/v1/devices/{deviceType}/repositories | Get Downloadable Images



## GetDownloadImageByDeviceType

> PostDownloadImageResponse GetDownloadImageByDeviceType(ctx, deviceType, version).Execute()

Download an Image



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	deviceType := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | Device type
	version := "17.06.01" // string | Version

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DownloadImageApi.GetDownloadImageByDeviceType(context.Background(), deviceType, version).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DownloadImageApi.GetDownloadImageByDeviceType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDownloadImageByDeviceType`: PostDownloadImageResponse
	fmt.Fprintf(os.Stdout, "Response from `DownloadImageApi.GetDownloadImageByDeviceType`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceType** | [**DeviceTypeCode**](.md) | Device type | 
**version** | **string** | Version | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDownloadImageByDeviceTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PostDownloadImageResponse**](PostDownloadImageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDownloadableImagesByDeviceType

> []ListOfDownloadableImages GetDownloadableImagesByDeviceType(ctx, deviceType).Execute()

Get Downloadable Images



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	deviceType := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | Device type

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DownloadImageApi.GetDownloadableImagesByDeviceType(context.Background(), deviceType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DownloadImageApi.GetDownloadableImagesByDeviceType``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDownloadableImagesByDeviceType`: []ListOfDownloadableImages
	fmt.Fprintf(os.Stdout, "Response from `DownloadImageApi.GetDownloadableImagesByDeviceType`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceType** | [**DeviceTypeCode**](.md) | Device type | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDownloadableImagesByDeviceTypeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]ListOfDownloadableImages**](ListOfDownloadableImages.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

