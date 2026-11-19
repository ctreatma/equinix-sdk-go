# \DeviceRMAApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeviceRMAByUuid**](DeviceRMAApi.md#CreateDeviceRMAByUuid) | **Post** /ne/v1/devices/{virtualDeviceUuid}/rma | Trigger Device RMA



## CreateDeviceRMAByUuid

> CreateDeviceRMAByUuid(ctx, virtualDeviceUuid).Request(request).Execute()

Trigger Device RMA



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
	virtualDeviceUuid := "877a3aa2-c49a-4af1-98a6-007424e737ae" // string | Unique ID of a device
	request := *openapiclient.NewDeviceRMAPostRequest("17.09.01a") // DeviceRMAPostRequest | Post RMA request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceRMAApi.CreateDeviceRMAByUuid(context.Background(), virtualDeviceUuid).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceRMAApi.CreateDeviceRMAByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique ID of a device | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceRMAByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **request** | [**DeviceRMAPostRequest**](DeviceRMAPostRequest.md) | Post RMA request | 

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

