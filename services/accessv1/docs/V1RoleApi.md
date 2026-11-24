# \V1RoleApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListRoles**](V1RoleApi.md#ListRoles) | **Get** /v1/roles | List Roles
[**ListRolesByProjectId**](V1RoleApi.md#ListRolesByProjectId) | **Get** /v1/projects/{projectId}/roles | list roles useable by project



## ListRoles

> RoleList ListRoles(ctx).PageToken(pageToken).PageSize(pageSize).ProjectId(projectId).ProjectErn(projectErn).Execute()

List Roles



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
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectId := "projectId_example" // string | Globally unique identifier of a project. Mutually exclusive with projectErn. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1RoleApi.ListRoles(context.Background()).PageToken(pageToken).PageSize(pageSize).ProjectId(projectId).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleApi.ListRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRoles`: RoleList
	fmt.Fprintf(os.Stdout, "Response from `V1RoleApi.ListRoles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectId** | **string** | Globally unique identifier of a project. Mutually exclusive with projectErn. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**RoleList**](RoleList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRolesByProjectId

> RoleList ListRolesByProjectId(ctx, projectId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()

list roles useable by project



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
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)
	projectErn := "projectErn_example" // string | Equinix Resource Name of a project. Mutually exclusive with projectId. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1RoleApi.ListRolesByProjectId(context.Background(), projectId).PageToken(pageToken).PageSize(pageSize).ProjectErn(projectErn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleApi.ListRolesByProjectId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRolesByProjectId`: RoleList
	fmt.Fprintf(os.Stdout, "Response from `V1RoleApi.ListRolesByProjectId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListRolesByProjectIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 
 **projectErn** | **string** | Equinix Resource Name of a project. Mutually exclusive with projectId. | 

### Return type

[**RoleList**](RoleList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

