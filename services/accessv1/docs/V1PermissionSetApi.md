# \V1PermissionSetApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePermissionSet**](V1PermissionSetApi.md#CreatePermissionSet) | **Post** /v1/projects/{projectId}/permissionSets | Create Permission Set
[**DeletePermissionSet**](V1PermissionSetApi.md#DeletePermissionSet) | **Delete** /v1/projects/{projectId}/permissionSets/{permissionSetId} | Delete Permission Set
[**GetPermissionSet**](V1PermissionSetApi.md#GetPermissionSet) | **Get** /v1/projects/{projectId}/permissionSets/{permissionSetId} | Get Permission Set
[**ListPermissionSets**](V1PermissionSetApi.md#ListPermissionSets) | **Get** /v1/projects/{projectId}/permissionSets | List Permission Sets
[**UpdatePermissionSet**](V1PermissionSetApi.md#UpdatePermissionSet) | **Patch** /v1/projects/{projectId}/permissionSets/{permissionSetId} | Update Permission Set



## CreatePermissionSet

> PermissionSet CreatePermissionSet(ctx, projectId).CreatePermissionSetBody(createPermissionSetBody).Execute()

Create Permission Set



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
	createPermissionSetBody := *openapiclient.NewCreatePermissionSetBody(map[string]string{"key": "my tag value"}, []openapiclient.UserRectSetInner{openapiclient.UserRectSet_inner{ForeignAccessPolicyRef: openapiclient.NewForeignAccessPolicyRef("ern:eqix:equinix/sts:global:abc-123:SomeType:res-id")}}, "permissionset:my-set") // CreatePermissionSetBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PermissionSetApi.CreatePermissionSet(context.Background(), projectId).CreatePermissionSetBody(createPermissionSetBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PermissionSetApi.CreatePermissionSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePermissionSet`: PermissionSet
	fmt.Fprintf(os.Stdout, "Response from `V1PermissionSetApi.CreatePermissionSet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePermissionSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createPermissionSetBody** | [**CreatePermissionSetBody**](CreatePermissionSetBody.md) |  | 

### Return type

[**PermissionSet**](PermissionSet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePermissionSet

> DeletePermissionSet(ctx, projectId, permissionSetId).LastRevBody(lastRevBody).Execute()

Delete Permission Set



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that permissionSetId is an ERN.
	permissionSetId := openapiclient.deletePermissionSet_permissionSetId_parameter{String: new(string)} // DeletePermissionSetPermissionSetIdParameter | Uniquely identifies a PermissionSet within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1PermissionSetApi.DeletePermissionSet(context.Background(), projectId, permissionSetId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PermissionSetApi.DeletePermissionSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that permissionSetId is an ERN. | 
**permissionSetId** | [**DeletePermissionSetPermissionSetIdParameter**](.md) | Uniquely identifies a PermissionSet within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePermissionSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPermissionSet

> PermissionSet GetPermissionSet(ctx, projectId, permissionSetId).Execute()

Get Permission Set



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that permissionSetId is an ERN.
	permissionSetId := openapiclient.getPermissionSet_permissionSetId_parameter{GetPermissionSetPermissionSetIdParameterOneOf: openapiclient.getPermissionSet_permissionSetId_parameter_oneOf{String: new(string)}} // GetPermissionSetPermissionSetIdParameter |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PermissionSetApi.GetPermissionSet(context.Background(), projectId, permissionSetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PermissionSetApi.GetPermissionSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPermissionSet`: PermissionSet
	fmt.Fprintf(os.Stdout, "Response from `V1PermissionSetApi.GetPermissionSet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that permissionSetId is an ERN. | 
**permissionSetId** | [**GetPermissionSetPermissionSetIdParameter**](.md) |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPermissionSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PermissionSet**](PermissionSet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPermissionSets

> PermissionSetList ListPermissionSets(ctx, projectId).Execute()

List Permission Sets



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PermissionSetApi.ListPermissionSets(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PermissionSetApi.ListPermissionSets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPermissionSets`: PermissionSetList
	fmt.Fprintf(os.Stdout, "Response from `V1PermissionSetApi.ListPermissionSets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPermissionSetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PermissionSetList**](PermissionSetList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePermissionSet

> PermissionSet UpdatePermissionSet(ctx, projectId, permissionSetId).UpdatePermissionSetBody(updatePermissionSetBody).Execute()

Update Permission Set



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that permissionSetId is an ERN.
	permissionSetId := openapiclient.deletePermissionSet_permissionSetId_parameter{String: new(string)} // DeletePermissionSetPermissionSetIdParameter | Uniquely identifies a PermissionSet within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	updatePermissionSetBody := *openapiclient.NewUpdatePermissionSetBody(map[string]string{"key": "my tag value"}, []openapiclient.UserRectSetInner{openapiclient.UserRectSet_inner{ForeignAccessPolicyRef: openapiclient.NewForeignAccessPolicyRef("ern:eqix:equinix/sts:global:abc-123:SomeType:res-id")}}, "abc123") // UpdatePermissionSetBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PermissionSetApi.UpdatePermissionSet(context.Background(), projectId, permissionSetId).UpdatePermissionSetBody(updatePermissionSetBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PermissionSetApi.UpdatePermissionSet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePermissionSet`: PermissionSet
	fmt.Fprintf(os.Stdout, "Response from `V1PermissionSetApi.UpdatePermissionSet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that permissionSetId is an ERN. | 
**permissionSetId** | [**DeletePermissionSetPermissionSetIdParameter**](.md) | Uniquely identifies a PermissionSet within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePermissionSetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePermissionSetBody** | [**UpdatePermissionSetBody**](UpdatePermissionSetBody.md) |  | 

### Return type

[**PermissionSet**](PermissionSet.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

