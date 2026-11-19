# \DeviceBackupAndRestoreApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckRestoreAnalysisOfBackupByUuid**](DeviceBackupAndRestoreApi.md#CheckRestoreAnalysisOfBackupByUuid) | **Get** /ne/v1/devices/{uuid}/restoreAnalysis | Checks Feasibility of Restore
[**CreateDeviceBackup**](DeviceBackupAndRestoreApi.md#CreateDeviceBackup) | **Post** /ne/v1/deviceBackups | Creates Device Backup
[**DeleteDeviceBackupByUuid**](DeviceBackupAndRestoreApi.md#DeleteDeviceBackupByUuid) | **Delete** /ne/v1/deviceBackups/{uuid} | Delete Backup of Device
[**DownloadDeviceBackupByUuid**](DeviceBackupAndRestoreApi.md#DownloadDeviceBackupByUuid) | **Get** /ne/v1/deviceBackups/{uuid}/download | Download a Backup
[**GetDetailsOfBackupsByUuid**](DeviceBackupAndRestoreApi.md#GetDetailsOfBackupsByUuid) | **Get** /ne/v1/deviceBackups/{uuid} | Get Backups of Device By Uuid
[**GetDeviceBackups**](DeviceBackupAndRestoreApi.md#GetDeviceBackups) | **Get** /ne/v1/deviceBackups | Get Backups of Device
[**RestoreDeviceBackupByUuid**](DeviceBackupAndRestoreApi.md#RestoreDeviceBackupByUuid) | **Patch** /ne/v1/devices/{uuid}/restore | Restores a backup
[**UpdateDeviceBackupByUuid**](DeviceBackupAndRestoreApi.md#UpdateDeviceBackupByUuid) | **Patch** /ne/v1/deviceBackups/{uuid} | Update Device Backup



## CheckRestoreAnalysisOfBackupByUuid

> RestoreBackupInfoVerbose CheckRestoreAnalysisOfBackupByUuid(ctx, uuid).BackupUuid(backupUuid).Execute()

Checks Feasibility of Restore



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a device
	backupUuid := "4cfb5675-5c3f-4275-adba-0c9e3c26c96b" // string | Unique ID of a backup (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceBackupAndRestoreApi.CheckRestoreAnalysisOfBackupByUuid(context.Background(), uuid).BackupUuid(backupUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.CheckRestoreAnalysisOfBackupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckRestoreAnalysisOfBackupByUuid`: RestoreBackupInfoVerbose
	fmt.Fprintf(os.Stdout, "Response from `DeviceBackupAndRestoreApi.CheckRestoreAnalysisOfBackupByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of a device | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckRestoreAnalysisOfBackupByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **backupUuid** | **string** | Unique ID of a backup | 

### Return type

[**RestoreBackupInfoVerbose**](RestoreBackupInfoVerbose.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDeviceBackup

> SshUserCreateResponse CreateDeviceBackup(ctx).Request(request).Execute()

Creates Device Backup



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
	request := *openapiclient.NewDeviceBackupCreateRequest("3da0a663-20d9-4b8f-8c5d-d5cf706840c8", "My New Backup") // DeviceBackupCreateRequest | Device backup info

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceBackupAndRestoreApi.CreateDeviceBackup(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.CreateDeviceBackup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeviceBackup`: SshUserCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `DeviceBackupAndRestoreApi.CreateDeviceBackup`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DeviceBackupCreateRequest**](DeviceBackupCreateRequest.md) | Device backup info | 

### Return type

[**SshUserCreateResponse**](SshUserCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeviceBackupByUuid

> DeleteDeviceBackupByUuid(ctx, uuid).Execute()

Delete Backup of Device



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
	uuid := "4cfb5675-5c3f-4275-adba-0c9e3c26c96b" // string | Unique Id a backup

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceBackupAndRestoreApi.DeleteDeviceBackupByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.DeleteDeviceBackupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id a backup | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeviceBackupByUuidRequest struct via the builder pattern


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


## DownloadDeviceBackupByUuid

> string DownloadDeviceBackupByUuid(ctx, uuid).Execute()

Download a Backup



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
	uuid := "4cfb5675-5c3f-4275-adba-0c9e3c26c96b" // string | Unique ID of a backup

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceBackupAndRestoreApi.DownloadDeviceBackupByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.DownloadDeviceBackupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadDeviceBackupByUuid`: string
	fmt.Fprintf(os.Stdout, "Response from `DeviceBackupAndRestoreApi.DownloadDeviceBackupByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of a backup | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadDeviceBackupByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDetailsOfBackupsByUuid

> DeviceBackupInfoVerbose GetDetailsOfBackupsByUuid(ctx, uuid).Execute()

Get Backups of Device By Uuid



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a backup

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceBackupAndRestoreApi.GetDetailsOfBackupsByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.GetDetailsOfBackupsByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDetailsOfBackupsByUuid`: DeviceBackupInfoVerbose
	fmt.Fprintf(os.Stdout, "Response from `DeviceBackupAndRestoreApi.GetDetailsOfBackupsByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of a backup | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDetailsOfBackupsByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeviceBackupInfoVerbose**](DeviceBackupInfoVerbose.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceBackups

> GetDeviceBackupsResponse GetDeviceBackups(ctx).ProjectIds(projectIds).VirtualDeviceUuid(virtualDeviceUuid).Status(status).Offset(offset).Limit(limit).Execute()

Get Backups of Device



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
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique ID of a virtual device (optional)
	status := openapiclient.getDeviceBackups_status_parameter("COMPLETED") // GetDeviceBackupsStatusParameter | An array of status values (optional)
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeviceBackupAndRestoreApi.GetDeviceBackups(context.Background()).ProjectIds(projectIds).VirtualDeviceUuid(virtualDeviceUuid).Status(status).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.GetDeviceBackups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceBackups`: GetDeviceBackupsResponse
	fmt.Fprintf(os.Stdout, "Response from `DeviceBackupAndRestoreApi.GetDeviceBackups`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceBackupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectIds** | **string** | If projectIds are different from default projectIds, must pass a projectIds parameter | 
 **virtualDeviceUuid** | **string** | Unique ID of a virtual device | 
 **status** | [**GetDeviceBackupsStatusParameter**](GetDeviceBackupsStatusParameter.md) | An array of status values | 
 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]

### Return type

[**GetDeviceBackupsResponse**](GetDeviceBackupsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreDeviceBackupByUuid

> RestoreDeviceBackupByUuid(ctx, uuid).Request(request).Execute()

Restores a backup



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
	uuid := "4cfb5675-5c3f-4275-adba-0c9e3c26c96b" // string | Unique ID of a backup
	request := *openapiclient.NewDeviceBackupUpdateRequest("My New Backup") // DeviceBackupUpdateRequest | Update device backup

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceBackupAndRestoreApi.RestoreDeviceBackupByUuid(context.Background(), uuid).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.RestoreDeviceBackupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of a backup | 

### Other Parameters

Other parameters are passed through a pointer to a apiRestoreDeviceBackupByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **request** | [**DeviceBackupUpdateRequest**](DeviceBackupUpdateRequest.md) | Update device backup | 

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


## UpdateDeviceBackupByUuid

> UpdateDeviceBackupByUuid(ctx, uuid).Request(request).Execute()

Update Device Backup



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
	uuid := "4cfb5675-5c3f-4275-adba-0c9e3c26c96b" // string | Unique ID of a backup
	request := *openapiclient.NewDeviceBackupUpdateRequest("My New Backup") // DeviceBackupUpdateRequest | Update device backup

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DeviceBackupAndRestoreApi.UpdateDeviceBackupByUuid(context.Background(), uuid).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeviceBackupAndRestoreApi.UpdateDeviceBackupByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of a backup | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceBackupByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **request** | [**DeviceBackupUpdateRequest**](DeviceBackupUpdateRequest.md) | Update device backup | 

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

