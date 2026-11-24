# \V1PolicyMaskApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePolicyMask**](V1PolicyMaskApi.md#CreatePolicyMask) | **Post** /v1/projects/{projectId}/policyMasks | Create Policy Mask
[**DeletePolicyMask**](V1PolicyMaskApi.md#DeletePolicyMask) | **Delete** /v1/projects/{projectId}/policyMasks/{policyMaskId} | Delete Policy Mask
[**DisablePolicyMask**](V1PolicyMaskApi.md#DisablePolicyMask) | **Post** /v1/projects/{projectId}/policyMasks/{policyMaskId}/disable | Disable Policy Mask
[**EnablePolicyMask**](V1PolicyMaskApi.md#EnablePolicyMask) | **Post** /v1/projects/{projectId}/policyMasks/{policyMaskId}/enable | Enable Policy Mask
[**GetPolicyMask**](V1PolicyMaskApi.md#GetPolicyMask) | **Get** /v1/projects/{projectId}/policyMasks/{policyMaskId} | Get Policy Mask
[**ListPolicyMasks**](V1PolicyMaskApi.md#ListPolicyMasks) | **Get** /v1/projects/{projectId}/policyMasks | List Policy Masks
[**UpdatePolicyMask**](V1PolicyMaskApi.md#UpdatePolicyMask) | **Patch** /v1/projects/{projectId}/policyMasks/{policyMaskId} | Update Policy Mask



## CreatePolicyMask

> PolicyMask CreatePolicyMask(ctx, projectId).CreatePolicyMaskBody(createPolicyMaskBody).Execute()

Create Policy Mask



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
	createPolicyMaskBody := *openapiclient.NewCreatePolicyMaskBody(map[string]string{"key": "my tag value"}, "policymask:my-mask") // CreatePolicyMaskBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PolicyMaskApi.CreatePolicyMask(context.Background(), projectId).CreatePolicyMaskBody(createPolicyMaskBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.CreatePolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePolicyMask`: PolicyMask
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.CreatePolicyMask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePolicyMaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createPolicyMaskBody** | [**CreatePolicyMaskBody**](CreatePolicyMaskBody.md) |  | 

### Return type

[**PolicyMask**](PolicyMask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePolicyMask

> DeletePolicyMask(ctx, projectId, policyMaskId).LastRevBody(lastRevBody).Execute()

Delete Policy Mask



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that policyMaskId is an ERN.
	policyMaskId := openapiclient.disablePolicyMask_policyMaskId_parameter{String: new(string)} // DisablePolicyMaskPolicyMaskIdParameter | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1PolicyMaskApi.DeletePolicyMask(context.Background(), projectId, policyMaskId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.DeletePolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that policyMaskId is an ERN. | 
**policyMaskId** | [**DisablePolicyMaskPolicyMaskIdParameter**](.md) | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePolicyMaskRequest struct via the builder pattern


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


## DisablePolicyMask

> PolicyMask DisablePolicyMask(ctx, projectId, policyMaskId).LastRevBody(lastRevBody).Execute()

Disable Policy Mask



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that policyMaskId is an ERN.
	policyMaskId := openapiclient.disablePolicyMask_policyMaskId_parameter{String: new(string)} // DisablePolicyMaskPolicyMaskIdParameter | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PolicyMaskApi.DisablePolicyMask(context.Background(), projectId, policyMaskId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.DisablePolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisablePolicyMask`: PolicyMask
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.DisablePolicyMask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that policyMaskId is an ERN. | 
**policyMaskId** | [**DisablePolicyMaskPolicyMaskIdParameter**](.md) | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisablePolicyMaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**PolicyMask**](PolicyMask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnablePolicyMask

> PolicyMask EnablePolicyMask(ctx, projectId, policyMaskId).LastRevBody(lastRevBody).Execute()

Enable Policy Mask



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that policyMaskId is an ERN.
	policyMaskId := openapiclient.disablePolicyMask_policyMaskId_parameter{String: new(string)} // DisablePolicyMaskPolicyMaskIdParameter | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PolicyMaskApi.EnablePolicyMask(context.Background(), projectId, policyMaskId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.EnablePolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnablePolicyMask`: PolicyMask
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.EnablePolicyMask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that policyMaskId is an ERN. | 
**policyMaskId** | [**DisablePolicyMaskPolicyMaskIdParameter**](.md) | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEnablePolicyMaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**PolicyMask**](PolicyMask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPolicyMask

> PolicyMask GetPolicyMask(ctx, projectId, policyMaskId).Execute()

Get Policy Mask



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that policyMaskId is an ERN.
	policyMaskId := openapiclient.disablePolicyMask_policyMaskId_parameter{String: new(string)} // DisablePolicyMaskPolicyMaskIdParameter | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PolicyMaskApi.GetPolicyMask(context.Background(), projectId, policyMaskId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.GetPolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPolicyMask`: PolicyMask
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.GetPolicyMask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that policyMaskId is an ERN. | 
**policyMaskId** | [**DisablePolicyMaskPolicyMaskIdParameter**](.md) | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPolicyMaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PolicyMask**](PolicyMask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPolicyMasks

> PolicyMaskList ListPolicyMasks(ctx, projectId).PageToken(pageToken).PageSize(pageSize).Execute()

List Policy Masks



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
	resp, r, err := apiClient.V1PolicyMaskApi.ListPolicyMasks(context.Background(), projectId).PageToken(pageToken).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.ListPolicyMasks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPolicyMasks`: PolicyMaskList
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.ListPolicyMasks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPolicyMasksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 

### Return type

[**PolicyMaskList**](PolicyMaskList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePolicyMask

> PolicyMask UpdatePolicyMask(ctx, projectId, policyMaskId).UpdatePolicyMaskBody(updatePolicyMaskBody).Execute()

Update Policy Mask



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that policyMaskId is an ERN.
	policyMaskId := openapiclient.disablePolicyMask_policyMaskId_parameter{String: new(string)} // DisablePolicyMaskPolicyMaskIdParameter | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	updatePolicyMaskBody := *openapiclient.NewUpdatePolicyMaskBody(map[string]string{"key": "my tag value"}, "abc123") // UpdatePolicyMaskBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PolicyMaskApi.UpdatePolicyMask(context.Background(), projectId, policyMaskId).UpdatePolicyMaskBody(updatePolicyMaskBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PolicyMaskApi.UpdatePolicyMask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePolicyMask`: PolicyMask
	fmt.Fprintf(os.Stdout, "Response from `V1PolicyMaskApi.UpdatePolicyMask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that policyMaskId is an ERN. | 
**policyMaskId** | [**DisablePolicyMaskPolicyMaskIdParameter**](.md) | Uniquely identifies a policy mask globally or within a governing project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePolicyMaskRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updatePolicyMaskBody** | [**UpdatePolicyMaskBody**](UpdatePolicyMaskBody.md) |  | 

### Return type

[**PolicyMask**](PolicyMask.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

