# \V1RoleAssignmentApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateRoleAssignment**](V1RoleAssignmentApi.md#CreateRoleAssignment) | **Post** /v1/roleAssignments | Create Role Assignment
[**DeleteRoleAssignment**](V1RoleAssignmentApi.md#DeleteRoleAssignment) | **Delete** /v1/roleAssignments/{roleAssignmentId} | Delete Role Assignment
[**GetRoleAssignment**](V1RoleAssignmentApi.md#GetRoleAssignment) | **Get** /v1/roleAssignments/{roleAssignmentId} | Get Role Assignment
[**ListRoleAssignments**](V1RoleAssignmentApi.md#ListRoleAssignments) | **Get** /v1/roleAssignments | List Role Assignments



## CreateRoleAssignment

> RoleAssignment CreateRoleAssignment(ctx).CreateRoleAssignmentInput(createRoleAssignmentInput).Execute()

Create Role Assignment



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
	createRoleAssignmentInput := *openapiclient.NewCreateRoleAssignmentInput("principal:abc-123:idp:example-user", "role:550e8400-e29b-41d4-a716-446655440000", *openapiclient.NewCreateRoleAssignmentInputAssignmentScope("07218c48-343d-43e2-9831-a2080445cd22", "PROJECT")) // CreateRoleAssignmentInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1RoleAssignmentApi.CreateRoleAssignment(context.Background()).CreateRoleAssignmentInput(createRoleAssignmentInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleAssignmentApi.CreateRoleAssignment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRoleAssignment`: RoleAssignment
	fmt.Fprintf(os.Stdout, "Response from `V1RoleAssignmentApi.CreateRoleAssignment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRoleAssignmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createRoleAssignmentInput** | [**CreateRoleAssignmentInput**](CreateRoleAssignmentInput.md) |  | 

### Return type

[**RoleAssignment**](RoleAssignment.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRoleAssignment

> DeleteRoleAssignment(ctx, roleAssignmentId).Execute()

Delete Role Assignment



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
	roleAssignmentId := "roleAssignmentId_example" // string | Uniquely identifies an access policy within a project. Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1RoleAssignmentApi.DeleteRoleAssignment(context.Background(), roleAssignmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleAssignmentApi.DeleteRoleAssignment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**roleAssignmentId** | **string** | Uniquely identifies an access policy within a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRoleAssignmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRoleAssignment

> RoleAssignment GetRoleAssignment(ctx, roleAssignmentId).Execute()

Get Role Assignment



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
	roleAssignmentId := "roleAssignmentId_example" // string | Uniquely identifies an access policy within a project. Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1RoleAssignmentApi.GetRoleAssignment(context.Background(), roleAssignmentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleAssignmentApi.GetRoleAssignment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRoleAssignment`: RoleAssignment
	fmt.Fprintf(os.Stdout, "Response from `V1RoleAssignmentApi.GetRoleAssignment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**roleAssignmentId** | **string** | Uniquely identifies an access policy within a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRoleAssignmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RoleAssignment**](RoleAssignment.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRoleAssignments

> RoleAssignmentList ListRoleAssignments(ctx).AssignmentScopeId(assignmentScopeId).AssignmentScopeType(assignmentScopeType).PageToken(pageToken).PageSize(pageSize).Execute()

List Role Assignments



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
	assignmentScopeId := "07218c48-343d-43e2-9831-a2080445cd22" // string | Id of the object this assignment scope refers to
	assignmentScopeType := "PROJECT" // string | Type of object that defines the scope of a role assignment (e.g. PROJECT, ORGANIZATION).
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1RoleAssignmentApi.ListRoleAssignments(context.Background()).AssignmentScopeId(assignmentScopeId).AssignmentScopeType(assignmentScopeType).PageToken(pageToken).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1RoleAssignmentApi.ListRoleAssignments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRoleAssignments`: RoleAssignmentList
	fmt.Fprintf(os.Stdout, "Response from `V1RoleAssignmentApi.ListRoleAssignments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListRoleAssignmentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assignmentScopeId** | **string** | Id of the object this assignment scope refers to | 
 **assignmentScopeType** | **string** | Type of object that defines the scope of a role assignment (e.g. PROJECT, ORGANIZATION). | 
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 

### Return type

[**RoleAssignmentList**](RoleAssignmentList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

