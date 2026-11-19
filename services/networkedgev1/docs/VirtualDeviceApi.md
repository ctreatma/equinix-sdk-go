# \VirtualDeviceApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeviceReloadByUuid**](VirtualDeviceApi.md#CreateDeviceReloadByUuid) | **Post** /ne/v1/devices/{virtualDeviceUUID}/softReboot | Trigger Virtual Device Soft Reboot
[**CreateVirtualDevice**](VirtualDeviceApi.md#CreateVirtualDevice) | **Post** /ne/v1/devices | Create Virtual Device
[**CreateVirtualDeviceByUuid**](VirtualDeviceApi.md#CreateVirtualDeviceByUuid) | **Put** /ne/v1/devices/{uuid} | Update Device Draft
[**DeleteVirtualDeviceByUuid**](VirtualDeviceApi.md#DeleteVirtualDeviceByUuid) | **Delete** /ne/v1/devices/{uuid} | Delete Virtual Device By Uuid
[**GetDeviceReloadByUuid**](VirtualDeviceApi.md#GetDeviceReloadByUuid) | **Get** /ne/v1/devices/{virtualDeviceUUID}/softReboot | List Device Reload History By Uuid
[**GetDeviceUpgradeByUuid**](VirtualDeviceApi.md#GetDeviceUpgradeByUuid) | **Get** /ne/v1/devices/{virtualDeviceUuid}/resourceUpgrade | Get Device Upgrade History
[**GetInterfaceStatisticsByUuid**](VirtualDeviceApi.md#GetInterfaceStatisticsByUuid) | **Get** /ne/v1/devices/{virtualDeviceUuid}/interfaces/{interfaceId}/stats | Get Interface Statistics
[**GetVirtualDeviceByUuid**](VirtualDeviceApi.md#GetVirtualDeviceByUuid) | **Get** /ne/v1/devices/{uuid} | Get Virtual Device By Uuid
[**GetVirtualDeviceInterfacesByUuid**](VirtualDeviceApi.md#GetVirtualDeviceInterfacesByUuid) | **Get** /ne/v1/devices/{uuid}/interfaces | Get Device Interfaces
[**GetVirtualDevices**](VirtualDeviceApi.md#GetVirtualDevices) | **Get** /ne/v1/devices | Get Virtual Devices
[**PingDeviceByUuid**](VirtualDeviceApi.md#PingDeviceByUuid) | **Get** /ne/v1/devices/{uuid}/ping | Ping Virtual Device
[**UpdateAdditionalBandwidthByUuid**](VirtualDeviceApi.md#UpdateAdditionalBandwidthByUuid) | **Put** /ne/v1/devices/{uuid}/additionalBandwidths | Update Additional Bandwidth of Virtual Device
[**UpdateVirtualDeviceByUuid**](VirtualDeviceApi.md#UpdateVirtualDeviceByUuid) | **Patch** /ne/v1/devices/{uuid} | Update Virtual Device By Uuid



## CreateDeviceReloadByUuid

> CreateDeviceReloadByUuid(ctx, virtualDeviceUUID).Execute()

Trigger Virtual Device Soft Reboot



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
	virtualDeviceUUID := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a virtual device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VirtualDeviceApi.CreateDeviceReloadByUuid(context.Background(), virtualDeviceUUID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.CreateDeviceReloadByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUUID** | **string** | Unique ID of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceReloadByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateVirtualDevice

> VirtualDeviceCreateResponse CreateVirtualDevice(ctx).VirtualDevice(virtualDevice).Draft(draft).DraftUuid(draftUuid).Execute()

Create Virtual Device



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
	virtualDevice := *openapiclient.NewVirtualDeviceRequest("16.09.03", openapiclient.DeviceTypeCode("C8000V"), true, openapiclient.VirtualDeviceRequest_licenseMode("SUB"), "SV", "Router1-c8000v", []string{"Notifications_example"}, openapiclient.VirtualDeviceRequest_deviceManagementType("SELF-CONFIGURED"), int32(4)) // VirtualDeviceRequest | Create a virtual device (e.g., a router or a firewall)
	draft := false // bool | Whether to save this as a draft. (optional) (default to false)
	draftUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | The unique ID of the draft to be promoted to a device. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.CreateVirtualDevice(context.Background()).VirtualDevice(virtualDevice).Draft(draft).DraftUuid(draftUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.CreateVirtualDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateVirtualDevice`: VirtualDeviceCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.CreateVirtualDevice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateVirtualDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **virtualDevice** | [**VirtualDeviceRequest**](VirtualDeviceRequest.md) | Create a virtual device (e.g., a router or a firewall) | 
 **draft** | **bool** | Whether to save this as a draft. | [default to false]
 **draftUuid** | **string** | The unique ID of the draft to be promoted to a device. | 

### Return type

[**VirtualDeviceCreateResponse**](VirtualDeviceCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateVirtualDeviceByUuid

> CreateVirtualDeviceByUuid(ctx, uuid).Draft(draft).VirtualDevice(virtualDevice).Execute()

Update Device Draft



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a Virtual Device
	draft := true // bool | draft
	virtualDevice := *openapiclient.NewVirtualDeviceRequest("16.09.03", openapiclient.DeviceTypeCode("C8000V"), true, openapiclient.VirtualDeviceRequest_licenseMode("SUB"), "SV", "Router1-c8000v", []string{"Notifications_example"}, openapiclient.VirtualDeviceRequest_deviceManagementType("SELF-CONFIGURED"), int32(4)) // VirtualDeviceRequest | Update virtual device details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VirtualDeviceApi.CreateVirtualDeviceByUuid(context.Background(), uuid).Draft(draft).VirtualDevice(virtualDevice).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.CreateVirtualDeviceByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a Virtual Device | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateVirtualDeviceByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **draft** | **bool** | draft | 
 **virtualDevice** | [**VirtualDeviceRequest**](VirtualDeviceRequest.md) | Update virtual device details | 

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


## DeleteVirtualDeviceByUuid

> DeleteVirtualDeviceByUuid(ctx, uuid).DeleteRedundantDevice(deleteRedundantDevice).DeletionInfo(deletionInfo).Execute()

Delete Virtual Device By Uuid



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a Virtual Device
	deleteRedundantDevice := false // bool | Optional parameter in case you have a secondary device. As both the primary and secondary devices are deleted simultaneously, this field must be marked True so we delete both the devices simultaneously. (optional) (default to false)
	deletionInfo := *openapiclient.NewVirtualDeviceDeleteRequest() // VirtualDeviceDeleteRequest | deletionInfo (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VirtualDeviceApi.DeleteVirtualDeviceByUuid(context.Background(), uuid).DeleteRedundantDevice(deleteRedundantDevice).DeletionInfo(deletionInfo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.DeleteVirtualDeviceByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a Virtual Device | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteVirtualDeviceByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deleteRedundantDevice** | **bool** | Optional parameter in case you have a secondary device. As both the primary and secondary devices are deleted simultaneously, this field must be marked True so we delete both the devices simultaneously. | [default to false]
 **deletionInfo** | [**VirtualDeviceDeleteRequest**](VirtualDeviceDeleteRequest.md) | deletionInfo | 

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


## GetDeviceReloadByUuid

> GetDeviceReloadResponse GetDeviceReloadByUuid(ctx, virtualDeviceUUID).Offset(offset).Limit(limit).Execute()

List Device Reload History By Uuid



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
	virtualDeviceUUID := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a virtual device.
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetDeviceReloadByUuid(context.Background(), virtualDeviceUUID).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetDeviceReloadByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceReloadByUuid`: GetDeviceReloadResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetDeviceReloadByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUUID** | **string** | Unique ID of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceReloadByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]

### Return type

[**GetDeviceReloadResponse**](GetDeviceReloadResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceUpgradeByUuid

> GetDeviceUpgradeResponse GetDeviceUpgradeByUuid(ctx, virtualDeviceUuid).Offset(offset).Limit(limit).Execute()

Get Device Upgrade History



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
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a virtual device.
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetDeviceUpgradeByUuid(context.Background(), virtualDeviceUuid).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetDeviceUpgradeByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceUpgradeByUuid`: GetDeviceUpgradeResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetDeviceUpgradeByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique ID of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceUpgradeByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]

### Return type

[**GetDeviceUpgradeResponse**](GetDeviceUpgradeResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetInterfaceStatisticsByUuid

> InterfaceStatsObject GetInterfaceStatisticsByUuid(ctx, virtualDeviceUuid, interfaceId).StartDateTime(startDateTime).EndDateTime(endDateTime).Execute()

Get Interface Statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a device
	interfaceId := "1" // string | Interface Id
	startDateTime := time.Now() // time.Time | Start time of the duration for which you want stats. (YYYY-MM-DDThh:mm:ssZ) (optional)
	endDateTime := time.Now() // time.Time | End time of the duration for which you want stats. (YYYY-MM-DDThh:mm:ssZ) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetInterfaceStatisticsByUuid(context.Background(), virtualDeviceUuid, interfaceId).StartDateTime(startDateTime).EndDateTime(endDateTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetInterfaceStatisticsByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInterfaceStatisticsByUuid`: InterfaceStatsObject
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetInterfaceStatisticsByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique Id of a device | 
**interfaceId** | **string** | Interface Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInterfaceStatisticsByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **startDateTime** | **time.Time** | Start time of the duration for which you want stats. (YYYY-MM-DDThh:mm:ssZ) | 
 **endDateTime** | **time.Time** | End time of the duration for which you want stats. (YYYY-MM-DDThh:mm:ssZ) | 

### Return type

[**InterfaceStatsObject**](InterfaceStatsObject.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualDeviceByUuid

> VirtualDeviceDetailsResponse GetVirtualDeviceByUuid(ctx, uuid).Execute()

Get Virtual Device By Uuid



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetVirtualDeviceByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetVirtualDeviceByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualDeviceByUuid`: VirtualDeviceDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetVirtualDeviceByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualDeviceByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VirtualDeviceDetailsResponse**](VirtualDeviceDetailsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualDeviceInterfacesByUuid

> []InterfaceBasicInfoResponse GetVirtualDeviceInterfacesByUuid(ctx, uuid).Execute()

Get Device Interfaces



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | uuid

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetVirtualDeviceInterfacesByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetVirtualDeviceInterfacesByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualDeviceInterfacesByUuid`: []InterfaceBasicInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetVirtualDeviceInterfacesByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | uuid | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualDeviceInterfacesByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]InterfaceBasicInfoResponse**](InterfaceBasicInfoResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualDevices

> GetDevicesResponse GetVirtualDevices(ctx).Offset(offset).Limit(limit).MetroCode(metroCode).Status(status).ShowOnlySubCustomerDevices(showOnlySubCustomerDevices).AccountUcmId(accountUcmId).SearchText(searchText).Sort(sort).ProjectIds(projectIds).Execute()

Get Virtual Devices



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
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)
	metroCode := "SV" // string | Two-letter metro code. (optional)
	status := openapiclient.getVirtualDevices_status_parameter("PROVISIONED") // GetVirtualDevicesStatusParameter | The status of the device. (optional)
	showOnlySubCustomerDevices := false // bool | Resellers may mark this Yes to see sub customer devices. (optional)
	accountUcmId := "123456" // string | Unique ID of the account. (optional)
	searchText := "My-Device" // string | Enter text to fetch only matching device names (optional)
	sort := []string{"Inner_example"} // []string | Sorts the output based on field names. (optional)
	projectIds := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectIds are different from default projectIds, must pass a projectIds parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.GetVirtualDevices(context.Background()).Offset(offset).Limit(limit).MetroCode(metroCode).Status(status).ShowOnlySubCustomerDevices(showOnlySubCustomerDevices).AccountUcmId(accountUcmId).SearchText(searchText).Sort(sort).ProjectIds(projectIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.GetVirtualDevices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualDevices`: GetDevicesResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.GetVirtualDevices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualDevicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]
 **metroCode** | **string** | Two-letter metro code. | 
 **status** | [**GetVirtualDevicesStatusParameter**](GetVirtualDevicesStatusParameter.md) | The status of the device. | 
 **showOnlySubCustomerDevices** | **bool** | Resellers may mark this Yes to see sub customer devices. | 
 **accountUcmId** | **string** | Unique ID of the account. | 
 **searchText** | **string** | Enter text to fetch only matching device names | 
 **sort** | **[]string** | Sorts the output based on field names. | 
 **projectIds** | **string** | If projectIds are different from default projectIds, must pass a projectIds parameter | 

### Return type

[**GetDevicesResponse**](GetDevicesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PingDeviceByUuid

> PingResponse PingDeviceByUuid(ctx, uuid).Execute()

Ping Virtual Device



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Virtual Device unique Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VirtualDeviceApi.PingDeviceByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.PingDeviceByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PingDeviceByUuid`: PingResponse
	fmt.Fprintf(os.Stdout, "Response from `VirtualDeviceApi.PingDeviceByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Virtual Device unique Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPingDeviceByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PingResponse**](PingResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAdditionalBandwidthByUuid

> UpdateAdditionalBandwidthByUuid(ctx, uuid).Request(request).Execute()

Update Additional Bandwidth of Virtual Device



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | The unique Id of a virtual device
	request := *openapiclient.NewAdditionalBandwidthRequest() // AdditionalBandwidthRequest | Additional Bandwidth

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VirtualDeviceApi.UpdateAdditionalBandwidthByUuid(context.Background(), uuid).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.UpdateAdditionalBandwidthByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | The unique Id of a virtual device | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAdditionalBandwidthByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **request** | [**AdditionalBandwidthRequest**](AdditionalBandwidthRequest.md) | Additional Bandwidth | 

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


## UpdateVirtualDeviceByUuid

> UpdateVirtualDeviceByUuid(ctx, uuid).VirtualDeviceUpdateRequestDto(virtualDeviceUpdateRequestDto).Execute()

Update Virtual Device By Uuid



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a Virtual Device
	virtualDeviceUpdateRequestDto := *openapiclient.NewVirtualDeviceInternalPatchRequest() // VirtualDeviceInternalPatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.VirtualDeviceApi.UpdateVirtualDeviceByUuid(context.Background(), uuid).VirtualDeviceUpdateRequestDto(virtualDeviceUpdateRequestDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VirtualDeviceApi.UpdateVirtualDeviceByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a Virtual Device | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateVirtualDeviceByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **virtualDeviceUpdateRequestDto** | [**VirtualDeviceInternalPatchRequest**](VirtualDeviceInternalPatchRequest.md) |  | 

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

