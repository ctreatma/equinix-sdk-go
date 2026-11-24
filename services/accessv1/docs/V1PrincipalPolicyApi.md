# \V1PrincipalPolicyApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DisablePrincipalPolicy**](V1PrincipalPolicyApi.md#DisablePrincipalPolicy) | **Post** /v1/projects/{projectId}/principalPolicies/{userPrincipal}/disable | Disable Principal Policy
[**EnablePrincipalPolicy**](V1PrincipalPolicyApi.md#EnablePrincipalPolicy) | **Post** /v1/projects/{projectId}/principalPolicies/{userPrincipal}/enable | Enable Principal Policy
[**GetPrincipalPolicy**](V1PrincipalPolicyApi.md#GetPrincipalPolicy) | **Get** /v1/projects/{projectId}/principalPolicies/{userPrincipal} | Get Principal Policy
[**ListPrincipalPolicies**](V1PrincipalPolicyApi.md#ListPrincipalPolicies) | **Get** /v1/projects/{projectId}/principalPolicies | List Principal Policies
[**UpdatePrincipalPolicy**](V1PrincipalPolicyApi.md#UpdatePrincipalPolicy) | **Patch** /v1/projects/{projectId}/principalPolicies/{userPrincipal} | Update Principal Policy



## DisablePrincipalPolicy

> PrincipalPolicy DisablePrincipalPolicy(ctx, projectId, userPrincipal).LastRevBody(lastRevBody).Execute()

Disable Principal Policy



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
	userPrincipal := "userPrincipal_example" // string | Globally unique string identifier for a principal formatted like \"principal:...\". Callers may URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PrincipalPolicyApi.DisablePrincipalPolicy(context.Background(), projectId, userPrincipal).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PrincipalPolicyApi.DisablePrincipalPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisablePrincipalPolicy`: PrincipalPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1PrincipalPolicyApi.DisablePrincipalPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**userPrincipal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisablePrincipalPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**PrincipalPolicy**](PrincipalPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnablePrincipalPolicy

> PrincipalPolicy EnablePrincipalPolicy(ctx, projectId, userPrincipal).LastRevBody(lastRevBody).Execute()

Enable Principal Policy



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
	userPrincipal := "userPrincipal_example" // string | Globally unique string identifier for a principal formatted like \"principal:...\". Callers may URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PrincipalPolicyApi.EnablePrincipalPolicy(context.Background(), projectId, userPrincipal).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PrincipalPolicyApi.EnablePrincipalPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnablePrincipalPolicy`: PrincipalPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1PrincipalPolicyApi.EnablePrincipalPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**userPrincipal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEnablePrincipalPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**PrincipalPolicy**](PrincipalPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPrincipalPolicy

> PrincipalPolicy GetPrincipalPolicy(ctx, projectId, userPrincipal).Execute()

Get Principal Policy



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
	userPrincipal := "userPrincipal_example" // string | Globally unique string identifier for a principal formatted like \"principal:...\". Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PrincipalPolicyApi.GetPrincipalPolicy(context.Background(), projectId, userPrincipal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PrincipalPolicyApi.GetPrincipalPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPrincipalPolicy`: PrincipalPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1PrincipalPolicyApi.GetPrincipalPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**userPrincipal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPrincipalPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PrincipalPolicy**](PrincipalPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPrincipalPolicies

> PrincipalPolicyList ListPrincipalPolicies(ctx, projectId).PageToken(pageToken).PageSize(pageSize).Execute()

List Principal Policies



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PrincipalPolicyApi.ListPrincipalPolicies(context.Background(), projectId).PageToken(pageToken).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PrincipalPolicyApi.ListPrincipalPolicies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPrincipalPolicies`: PrincipalPolicyList
	fmt.Fprintf(os.Stdout, "Response from `V1PrincipalPolicyApi.ListPrincipalPolicies`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPrincipalPoliciesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 

### Return type

[**PrincipalPolicyList**](PrincipalPolicyList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePrincipalPolicy

> PrincipalPolicy UpdatePrincipalPolicy(ctx, projectId, userPrincipal).UpdatePrincipalPolicyBody(updatePrincipalPolicyBody).Execute()

Update Principal Policy



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
	userPrincipal := "userPrincipal_example" // string | Globally unique string identifier for a principal formatted like \"principal:...\". Callers may URL encode this value.
	updatePrincipalPolicyBody := *openapiclient.NewUpdatePrincipalPolicyBody([]openapiclient.ManagedPermissionSetRef{*openapiclient.NewManagedPermissionSetRef("managedset:my-set")}, map[string]string{"key": "my tag value"}, "abc123") // UpdatePrincipalPolicyBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PrincipalPolicyApi.UpdatePrincipalPolicy(context.Background(), projectId, userPrincipal).UpdatePrincipalPolicyBody(updatePrincipalPolicyBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PrincipalPolicyApi.UpdatePrincipalPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePrincipalPolicy`: PrincipalPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1PrincipalPolicyApi.UpdatePrincipalPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**userPrincipal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePrincipalPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePrincipalPolicyBody** | [**UpdatePrincipalPolicyBody**](UpdatePrincipalPolicyBody.md) |  | 

### Return type

[**PrincipalPolicy**](PrincipalPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

