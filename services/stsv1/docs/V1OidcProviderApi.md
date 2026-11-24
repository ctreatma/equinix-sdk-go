# \V1OidcProviderApi

All URIs are relative to *https://sts.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateOidcProvider**](V1OidcProviderApi.md#CreateOidcProvider) | **Post** /v1/projects/{projectId}/oidcProviders | Create OIDC Provider
[**DeleteOidcProvider**](V1OidcProviderApi.md#DeleteOidcProvider) | **Delete** /v1/projects/{projectId}/oidcProviders/{idpId} | Delete OIDC Provider
[**PageOidcProviders**](V1OidcProviderApi.md#PageOidcProviders) | **Get** /v1/projects/{projectId}/oidcProviders | List OIDC Providers
[**PatchOidcProvider**](V1OidcProviderApi.md#PatchOidcProvider) | **Patch** /v1/projects/{projectId}/oidcProviders/{idpId} | Patch OIDC Provider
[**ResumeOidcProvider**](V1OidcProviderApi.md#ResumeOidcProvider) | **Post** /v1/projects/{projectId}/oidcProviders/{idpId}/resume | Resume OIDC Provider
[**SuspendOidcProvider**](V1OidcProviderApi.md#SuspendOidcProvider) | **Post** /v1/projects/{projectId}/oidcProviders/{idpId}/suspend | Suspend OIDC Provider



## CreateOidcProvider

> OIDCProvider CreateOidcProvider(ctx, projectId).CreateOidcProviderBody(createOidcProviderBody).Execute()

Create OIDC Provider



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	createOidcProviderBody := *openapiclient.NewCreateOidcProviderBody("My OIDC Provider", []string{"my-oauth-client-id"}, "https://example.com/oidc", "my-idp") // CreateOidcProviderBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1OidcProviderApi.CreateOidcProvider(context.Background(), projectId).CreateOidcProviderBody(createOidcProviderBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.CreateOidcProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOidcProvider`: OIDCProvider
	fmt.Fprintf(os.Stdout, "Response from `V1OidcProviderApi.CreateOidcProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateOidcProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOidcProviderBody** | [**CreateOidcProviderBody**](CreateOidcProviderBody.md) |  | 

### Return type

[**OIDCProvider**](OIDCProvider.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteOidcProvider

> DeleteOidcProvider(ctx, projectId, idpId).Execute()

Delete OIDC Provider



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	idpId := "idpId_example" // string | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1OidcProviderApi.DeleteOidcProvider(context.Background(), projectId, idpId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.DeleteOidcProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**idpId** | **string** | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteOidcProviderRequest struct via the builder pattern


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


## PageOidcProviders

> OIDCProviderPage PageOidcProviders(ctx, projectId).IncludeSuspended(includeSuspended).PageToken(pageToken).PageSize(pageSize).Execute()

List OIDC Providers



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	includeSuspended := false // bool | When true, include suspended OIDC providers in the results. (optional)
	pageToken := "pageToken_example" // string | Opaque token identifying the page of results to retrieve. (optional)
	pageSize := int32(56) // int32 | Maximum number of results to return per page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1OidcProviderApi.PageOidcProviders(context.Background(), projectId).IncludeSuspended(includeSuspended).PageToken(pageToken).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.PageOidcProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PageOidcProviders`: OIDCProviderPage
	fmt.Fprintf(os.Stdout, "Response from `V1OidcProviderApi.PageOidcProviders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPageOidcProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeSuspended** | **bool** | When true, include suspended OIDC providers in the results. | 
 **pageToken** | **string** | Opaque token identifying the page of results to retrieve. | 
 **pageSize** | **int32** | Maximum number of results to return per page. | 

### Return type

[**OIDCProviderPage**](OIDCProviderPage.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchOidcProvider

> OIDCProvider PatchOidcProvider(ctx, projectId, idpId).PatchOidcProviderBody(patchOidcProviderBody).Execute()

Patch OIDC Provider



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	idpId := "idpId_example" // string | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value.
	patchOidcProviderBody := *openapiclient.NewPatchOidcProviderBody("abc123") // PatchOidcProviderBody | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1OidcProviderApi.PatchOidcProvider(context.Background(), projectId, idpId).PatchOidcProviderBody(patchOidcProviderBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.PatchOidcProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchOidcProvider`: OIDCProvider
	fmt.Fprintf(os.Stdout, "Response from `V1OidcProviderApi.PatchOidcProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**idpId** | **string** | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchOidcProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **patchOidcProviderBody** | [**PatchOidcProviderBody**](PatchOidcProviderBody.md) |  | 

### Return type

[**OIDCProvider**](OIDCProvider.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResumeOidcProvider

> ResumeOidcProvider(ctx, projectId, idpId).Execute()

Resume OIDC Provider



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	idpId := "idpId_example" // string | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1OidcProviderApi.ResumeOidcProvider(context.Background(), projectId, idpId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.ResumeOidcProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**idpId** | **string** | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiResumeOidcProviderRequest struct via the builder pattern


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


## SuspendOidcProvider

> SuspendOidcProvider(ctx, projectId, idpId).Execute()

Suspend OIDC Provider



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/stsv1"
)

func main() {
	projectId := "projectId_example" // string | Globally unique identifier of a project. Callers may URL encode this value.
	idpId := "idpId_example" // string | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.V1OidcProviderApi.SuspendOidcProvider(context.Background(), projectId, idpId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1OidcProviderApi.SuspendOidcProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** | Globally unique identifier of a project. Callers may URL encode this value. | 
**idpId** | **string** | Uniquely identifies a trusted Identity Provider within a root project. Callers may URL encode this value. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuspendOidcProviderRequest struct via the builder pattern


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

