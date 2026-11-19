# \V1MiscApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetEffectivePermissions**](V1MiscApi.md#GetEffectivePermissions) | **Get** /v1/projects/{projectId}/effectivePermissions | Get Effective Permissions
[**GetServicePolicySchema**](V1MiscApi.md#GetServicePolicySchema) | **Get** /v1/projects/{projectId}/servicePolicySchemas | Get Service Policy Schema
[**ListActionSets**](V1MiscApi.md#ListActionSets) | **Get** /v1/projects/{projectId}/actionSets | List Action Sets
[**ListActions**](V1MiscApi.md#ListActions) | **Get** /v1/projects/{projectId}/actions | List Actions
[**ListResourceTypes**](V1MiscApi.md#ListResourceTypes) | **Get** /v1/projects/{projectId}/resourceTypes | List Resource Types
[**PageResourceTypeActions**](V1MiscApi.md#PageResourceTypeActions) | **Get** /v1/projects/{projectId}/resourceTypeActions | Page Resource Type Actions



## GetEffectivePermissions

> EffectivePermissions GetEffectivePermissions(ctx, projectId).ServiceId(serviceId).ProjectErn(projectErn).Execute()

Get Effective Permissions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of a service.
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.GetEffectivePermissions(context.Background(), projectId).ServiceId(serviceId).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.GetEffectivePermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEffectivePermissions`: EffectivePermissions
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.GetEffectivePermissions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEffectivePermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of a service. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**EffectivePermissions**](EffectivePermissions.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetServicePolicySchema

> ServicePolicySchema GetServicePolicySchema(ctx, projectId).ServiceId(serviceId).Execute()

Get Service Policy Schema



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of a service.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.GetServicePolicySchema(context.Background(), projectId).ServiceId(serviceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.GetServicePolicySchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetServicePolicySchema`: ServicePolicySchema
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.GetServicePolicySchema`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetServicePolicySchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of a service. | 

### Return type

[**ServicePolicySchema**](ServicePolicySchema.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListActionSets

> ServiceActionSetNoErnList ListActionSets(ctx, projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()

List Action Sets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of a service.
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.ListActionSets(context.Background(), projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.ListActionSets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListActionSets`: ServiceActionSetNoErnList
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.ListActionSets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListActionSetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of a service. | 
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**ServiceActionSetNoErnList**](ServiceActionSetNoErnList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListActions

> ActionList ListActions(ctx, projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()

List Actions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of a service.
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.ListActions(context.Background(), projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.ListActions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListActions`: ActionList
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.ListActions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListActionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of a service. | 
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**ActionList**](ActionList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListResourceTypes

> ResourceTypeList ListResourceTypes(ctx, projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()

List Resource Types



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of a service.
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.ListResourceTypes(context.Background(), projectId).ServiceId(serviceId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.ListResourceTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListResourceTypes`: ResourceTypeList
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.ListResourceTypes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListResourceTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of a service. | 
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**ResourceTypeList**](ResourceTypeList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PageResourceTypeActions

> ResourceTypeActionPage PageResourceTypeActions(ctx, projectId).ServiceId(serviceId).ResourceType(resourceType).ResourceTypeServiceId(resourceTypeServiceId).LastAction(lastAction).PageSize(pageSize).ProjectErn(projectErn).Execute()

Page Resource Type Actions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/accessv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	serviceId := "serviceId_example" // string | Fully qualified, universally unique id of the service owning the resource type.
	resourceType := "resourceType_example" // string | Identifies the resource type within the service.
	resourceTypeServiceId := "resourceTypeServiceId_example" // string | Service id of the resource type, if different from serviceId. (optional)
	lastAction := "lastAction_example" // string | Id of the last action received; used for cursor-based pagination. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1MiscApi.PageResourceTypeActions(context.Background(), projectId).ServiceId(serviceId).ResourceType(resourceType).ResourceTypeServiceId(resourceTypeServiceId).LastAction(lastAction).PageSize(pageSize).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1MiscApi.PageResourceTypeActions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PageResourceTypeActions`: ResourceTypeActionPage
	fmt.Fprintf(os.Stdout, "Response from `V1MiscApi.PageResourceTypeActions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPageResourceTypeActionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **serviceId** | **string** | Fully qualified, universally unique id of the service owning the resource type. | 
 **resourceType** | **string** | Identifies the resource type within the service. | 
 **resourceTypeServiceId** | **string** | Service id of the resource type, if different from serviceId. | 
 **lastAction** | **string** | Id of the last action received; used for cursor-based pagination. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**ResourceTypeActionPage**](ResourceTypeActionPage.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

