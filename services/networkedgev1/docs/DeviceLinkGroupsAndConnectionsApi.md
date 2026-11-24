# \DeviceLinkGroupsAndConnectionsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeviceLinkGroup**](DeviceLinkGroupsAndConnectionsApi.md#CreateDeviceLinkGroup) | **Post** /ne/v1/links | Create Device Link
[**DeleteDeviceLinkGroupByUuid**](DeviceLinkGroupsAndConnectionsApi.md#DeleteDeviceLinkGroupByUuid) | **Delete** /ne/v1/links/{uuid} | Delete Device Link By Uuid
[**GetDeviceLinkGroupByUUID**](DeviceLinkGroupsAndConnectionsApi.md#GetDeviceLinkGroupByUUID) | **Get** /ne/v1/links/{uuid} | Get Device Link By Uuid
[**GetDeviceLinkGroups**](DeviceLinkGroupsAndConnectionsApi.md#GetDeviceLinkGroups) | **Get** /ne/v1/links | Get Device Links
[**UpdateDeviceLinkGroupByUuid**](DeviceLinkGroupsAndConnectionsApi.md#UpdateDeviceLinkGroupByUuid) | **Patch** /ne/v1/links/{uuid} | Update Device Link By Uuid



## CreateDeviceLinkGroup

> DeviceLinkGroupResponse CreateDeviceLinkGroup(ctx).DeviceLinkGroup(deviceLinkGroup).Execute()

Create Device Link



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
	deviceLinkGroup := *openapiclient.NewDeviceLinkRequest("linkGroup", "192.164.0.0/29") // DeviceLinkRequest | New Device Link Group

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceLinkGroupsAndConnectionsApi.CreateDeviceLinkGroup(context.Background()).DeviceLinkGroup(deviceLinkGroup).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceLinkGroupsAndConnectionsApi.CreateDeviceLinkGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeviceLinkGroup`: DeviceLinkGroupResponse
	fmt.Fprintf(os.Stdout, "Response from `DeviceLinkGroupsAndConnectionsApi.CreateDeviceLinkGroup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceLinkGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deviceLinkGroup** | [**DeviceLinkRequest**](DeviceLinkRequest.md) | New Device Link Group | 

### Return type

[**DeviceLinkGroupResponse**](DeviceLinkGroupResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeviceLinkGroupByUuid

> DeleteDeviceLinkGroupByUuid(ctx, uuid).Execute()

Delete Device Link By Uuid



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
	uuid := "6ea5a0e4-2bf7-45c2-9aa7-e846a8cd5567" // string | Unique Id of a device link group.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceLinkGroupsAndConnectionsApi.DeleteDeviceLinkGroupByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceLinkGroupsAndConnectionsApi.DeleteDeviceLinkGroupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a device link group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeviceLinkGroupByUuidRequest struct via the builder pattern


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


## GetDeviceLinkGroupByUUID

> DeviceLinkGroup GetDeviceLinkGroupByUUID(ctx, uuid).Execute()

Get Device Link By Uuid



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
	uuid := "6ea5a0e4-2bf7-45c2-9aa7-e846a8cd5567" // string | Unique Id of a device link group.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroupByUUID(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroupByUUID``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceLinkGroupByUUID`: DeviceLinkGroup
	fmt.Fprintf(os.Stdout, "Response from `DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroupByUUID`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a device link group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceLinkGroupByUUIDRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeviceLinkGroup**](DeviceLinkGroup.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceLinkGroups

> GetLinksResponse GetDeviceLinkGroups(ctx).ProjectIds(projectIds).Metro(metro).VirtualDeviceUuid(virtualDeviceUuid).AccountUcmId(accountUcmId).GroupUuid(groupUuid).GroupName(groupName).Offset(offset).Limit(limit).Execute()

Get Device Links



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
	projectIds := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectIds are different from default projectIds, must pass a projectIds parameter (optional)
	metro := "SV" // string | Metro Code (optional)
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device. (optional)
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | Unique Id of the account. A reseller querying for a customer's link groups can pass the accountUcmId of the customer's account. (optional)
	groupUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a link group (optional)
	groupName := "linkGroup" // string | The name of a link group (optional)
	offset := int32(0) // int32 | Specifies where to start a page. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroups(context.Background()).ProjectIds(projectIds).Metro(metro).VirtualDeviceUuid(virtualDeviceUuid).AccountUcmId(accountUcmId).GroupUuid(groupUuid).GroupName(groupName).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceLinkGroups`: GetLinksResponse
	fmt.Fprintf(os.Stdout, "Response from `DeviceLinkGroupsAndConnectionsApi.GetDeviceLinkGroups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceLinkGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectIds** | **string** | If projectIds are different from default projectIds, must pass a projectIds parameter | 
 **metro** | **string** | Metro Code | 
 **virtualDeviceUuid** | **string** | Unique Id of a virtual device. | 
 **accountUcmId** | **string** | Unique Id of the account. A reseller querying for a customer&#39;s link groups can pass the accountUcmId of the customer&#39;s account. | 
 **groupUuid** | **string** | Unique Id of a link group | 
 **groupName** | **string** | The name of a link group | 
 **offset** | **int32** | Specifies where to start a page. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]

### Return type

[**GetLinksResponse**](GetLinksResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeviceLinkGroupByUuid

> UpdateDeviceLinkGroupByUuid(ctx, uuid).DeviceLinkGroup(deviceLinkGroup).Execute()

Update Device Link By Uuid



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
	uuid := "6ea5a0e4-2bf7-45c2-9aa7-e846a8cd5567" // string | Unique Id of a device link group.
	deviceLinkGroup := *openapiclient.NewDeviceLinkRequest("linkGroup", "192.164.0.0/29") // DeviceLinkRequest | Device Link Group

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceLinkGroupsAndConnectionsApi.UpdateDeviceLinkGroupByUuid(context.Background(), uuid).DeviceLinkGroup(deviceLinkGroup).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceLinkGroupsAndConnectionsApi.UpdateDeviceLinkGroupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a device link group. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceLinkGroupByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deviceLinkGroup** | [**DeviceLinkRequest**](DeviceLinkRequest.md) | Device Link Group | 

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

