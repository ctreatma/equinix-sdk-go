# \V1AccessPolicyApi

All URIs are relative to *https://access.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddGrant**](V1AccessPolicyApi.md#AddGrant) | **Post** /v1/projects/{projectId}/accessPolicies/{accessPolicyId}/grants | Add Grant
[**CreateAccessPolicy**](V1AccessPolicyApi.md#CreateAccessPolicy) | **Post** /v1/projects/{projectId}/accessPolicies | Create Access Policy
[**DeleteAccessPolicy**](V1AccessPolicyApi.md#DeleteAccessPolicy) | **Delete** /v1/projects/{projectId}/accessPolicies/{accessPolicyId} | Delete Access Policy
[**DisableAccessPolicy**](V1AccessPolicyApi.md#DisableAccessPolicy) | **Post** /v1/projects/{projectId}/accessPolicies/{accessPolicyId}/disable | Disable Access Policy
[**EnableAccessPolicy**](V1AccessPolicyApi.md#EnableAccessPolicy) | **Post** /v1/projects/{projectId}/accessPolicies/{accessPolicyId}/enable | Enable Access Policy
[**GetAccessPolicy**](V1AccessPolicyApi.md#GetAccessPolicy) | **Get** /v1/projects/{projectId}/accessPolicies/{accessPolicyId} | Get Access Policy
[**ListAccessPolicies**](V1AccessPolicyApi.md#ListAccessPolicies) | **Get** /v1/projects/{projectId}/accessPolicies | List Access Policies
[**ListGrants**](V1AccessPolicyApi.md#ListGrants) | **Get** /v1/projects/{projectId}/accessPolicies/{accessPolicyId}/grants | List Grants
[**RemoveGrant**](V1AccessPolicyApi.md#RemoveGrant) | **Delete** /v1/projects/{projectId}/accessPolicies/{accessPolicyId}/grants/{grantId} | Remove Grant
[**UpdateAccessPolicy**](V1AccessPolicyApi.md#UpdateAccessPolicy) | **Patch** /v1/projects/{projectId}/accessPolicies/{accessPolicyId} | Update Access Policy



## AddGrant

> AccessPolicyGrant AddGrant(ctx, projectId, accessPolicyId).AddGrantBody(addGrantBody).Execute()

Add Grant



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.listGrants_accessPolicyId_parameter{ListGrantsAccessPolicyIdParameterOneOf: openapiclient.listGrants_accessPolicyId_parameter_oneOf{String: new(string)}} // ListGrantsAccessPolicyIdParameter |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	addGrantBody := *openapiclient.NewAddGrantBody(*openapiclient.NewGrantee()) // AddGrantBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.AddGrant(context.Background(), projectId, accessPolicyId).AddGrantBody(addGrantBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.AddGrant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddGrant`: AccessPolicyGrant
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.AddGrant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**ListGrantsAccessPolicyIdParameter**](.md) |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddGrantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **addGrantBody** | [**AddGrantBody**](AddGrantBody.md) |  | 

### Return type

[**AccessPolicyGrant**](AccessPolicyGrant.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAccessPolicy

> AccessPolicy CreateAccessPolicy(ctx, projectId).CreateAccessPolicyBody(createAccessPolicyBody).Execute()

Create Access Policy



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
	createAccessPolicyBody := *openapiclient.NewCreateAccessPolicyBody(map[string]string{"key": "my tag value"}, []openapiclient.UserRectSetInner{openapiclient.UserRectSet_inner{ForeignAccessPolicyRef: openapiclient.NewForeignAccessPolicyRef("ern:eqix:equinix/sts:global:abc-123:SomeType:res-id")}}, "accesspolicy:my-policy") // CreateAccessPolicyBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.CreateAccessPolicy(context.Background(), projectId).CreateAccessPolicyBody(createAccessPolicyBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.CreateAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAccessPolicy`: AccessPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.CreateAccessPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAccessPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createAccessPolicyBody** | [**CreateAccessPolicyBody**](CreateAccessPolicyBody.md) |  | 

### Return type

[**AccessPolicy**](AccessPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAccessPolicy

> DeleteAccessPolicy(ctx, projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()

Delete Access Policy



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.deleteAccessPolicy_accessPolicyId_parameter{String: new(string)} // DeleteAccessPolicyAccessPolicyIdParameter | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1AccessPolicyApi.DeleteAccessPolicy(context.Background(), projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.DeleteAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**DeleteAccessPolicyAccessPolicyIdParameter**](.md) | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAccessPolicyRequest struct via the builder pattern


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


## DisableAccessPolicy

> AccessPolicy DisableAccessPolicy(ctx, projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()

Disable Access Policy



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.deleteAccessPolicy_accessPolicyId_parameter{String: new(string)} // DeleteAccessPolicyAccessPolicyIdParameter | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.DisableAccessPolicy(context.Background(), projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.DisableAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisableAccessPolicy`: AccessPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.DisableAccessPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**DeleteAccessPolicyAccessPolicyIdParameter**](.md) | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisableAccessPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**AccessPolicy**](AccessPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnableAccessPolicy

> AccessPolicy EnableAccessPolicy(ctx, projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()

Enable Access Policy



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.deleteAccessPolicy_accessPolicyId_parameter{String: new(string)} // DeleteAccessPolicyAccessPolicyIdParameter | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	lastRevBody := *openapiclient.NewLastRevBody("abc123") // LastRevBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.EnableAccessPolicy(context.Background(), projectId, accessPolicyId).LastRevBody(lastRevBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.EnableAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnableAccessPolicy`: AccessPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.EnableAccessPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**DeleteAccessPolicyAccessPolicyIdParameter**](.md) | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiEnableAccessPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **lastRevBody** | [**LastRevBody**](LastRevBody.md) |  | 

### Return type

[**AccessPolicy**](AccessPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAccessPolicy

> AccessPolicy GetAccessPolicy(ctx, projectId, accessPolicyId).Execute()

Get Access Policy



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.listGrants_accessPolicyId_parameter{ListGrantsAccessPolicyIdParameterOneOf: openapiclient.listGrants_accessPolicyId_parameter_oneOf{String: new(string)}} // ListGrantsAccessPolicyIdParameter |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.GetAccessPolicy(context.Background(), projectId, accessPolicyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.GetAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAccessPolicy`: AccessPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.GetAccessPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**ListGrantsAccessPolicyIdParameter**](.md) |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAccessPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**AccessPolicy**](AccessPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAccessPolicies

> AccessPolicyList ListAccessPolicies(ctx, projectId).Execute()

List Access Policies



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
	resp, r, err := apiClient.V1AccessPolicyApi.ListAccessPolicies(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.ListAccessPolicies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAccessPolicies`: AccessPolicyList
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.ListAccessPolicies`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAccessPoliciesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccessPolicyList**](AccessPolicyList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrants

> AccessPolicyGrantList ListGrants(ctx, projectId, accessPolicyId).PageToken(pageToken).PageSize(pageSize).Execute()

List Grants



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.listGrants_accessPolicyId_parameter{ListGrantsAccessPolicyIdParameterOneOf: openapiclient.listGrants_accessPolicyId_parameter_oneOf{String: new(string)}} // ListGrantsAccessPolicyIdParameter |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.ListGrants(context.Background(), projectId, accessPolicyId).PageToken(pageToken).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.ListGrants``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrants`: AccessPolicyGrantList
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.ListGrants`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**ListGrantsAccessPolicyIdParameter**](.md) |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGrantsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 

### Return type

[**AccessPolicyGrantList**](AccessPolicyGrantList.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveGrant

> RemoveGrant(ctx, grantId, projectId, accessPolicyId).Execute()

Remove Grant



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
	grantId := "grantId_example" // string | Uniquely identifies an access policy grant. Callers may URL encode this value.
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.listGrants_accessPolicyId_parameter{ListGrantsAccessPolicyIdParameterOneOf: openapiclient.listGrants_accessPolicyId_parameter_oneOf{String: new(string)}} // ListGrantsAccessPolicyIdParameter |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1AccessPolicyApi.RemoveGrant(context.Background(), grantId, projectId, accessPolicyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.RemoveGrant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**grantId** | **string** | Uniquely identifies an access policy grant. Callers may URL encode this value. | 
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**ListGrantsAccessPolicyIdParameter**](.md) |  Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveGrantRequest struct via the builder pattern


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


## UpdateAccessPolicy

> AccessPolicy UpdateAccessPolicy(ctx, projectId, accessPolicyId).UpdateAccessPolicyBody(updateAccessPolicyBody).Execute()

Update Access Policy



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
	projectId := openapiclient.listGrants_projectId_parameter{ListGrantsProjectIdParameterOneOf: openapiclient.listGrants_projectId_parameter_oneOf("*")} // ListGrantsProjectIdParameter | Globally unique identifier of a project. Callers may URL encode this value. Use `*` here to indicate that accessPolicyId is an ERN.
	accessPolicyId := openapiclient.deleteAccessPolicy_accessPolicyId_parameter{String: new(string)} // DeleteAccessPolicyAccessPolicyIdParameter | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value.
	updateAccessPolicyBody := *openapiclient.NewUpdateAccessPolicyBody(map[string]string{"key": "my tag value"}, []openapiclient.UserRectSetInner{openapiclient.UserRectSet_inner{ForeignAccessPolicyRef: openapiclient.NewForeignAccessPolicyRef("ern:eqix:equinix/sts:global:abc-123:SomeType:res-id")}}, "abc123") // UpdateAccessPolicyBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1AccessPolicyApi.UpdateAccessPolicy(context.Background(), projectId, accessPolicyId).UpdateAccessPolicyBody(updateAccessPolicyBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1AccessPolicyApi.UpdateAccessPolicy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAccessPolicy`: AccessPolicy
	fmt.Fprintf(os.Stdout, "Response from `V1AccessPolicyApi.UpdateAccessPolicy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | [**ListGrantsProjectIdParameter**](.md) | Globally unique identifier of a project. Callers may URL encode this value. Use &#x60;*&#x60; here to indicate that accessPolicyId is an ERN. | 
**accessPolicyId** | [**DeleteAccessPolicyAccessPolicyIdParameter**](.md) | Uniquely identifies an access policy within a project. Callers may URL encode this value. When passing an ERN, callers *must* URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAccessPolicyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateAccessPolicyBody** | [**UpdateAccessPolicyBody**](UpdateAccessPolicyBody.md) |  | 

### Return type

[**AccessPolicy**](AccessPolicy.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

