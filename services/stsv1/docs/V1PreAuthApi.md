# \V1PreAuthApi

All URIs are relative to *https://sts.eqix.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GenerateStsToken**](V1PreAuthApi.md#GenerateStsToken) | **Post** /v1/token | generate sts token
[**GetJwks**](V1PreAuthApi.md#GetJwks) | **Get** /jwks | Get JSON Web Key Set
[**GetOpenIdConfiguration**](V1PreAuthApi.md#GetOpenIdConfiguration) | **Get** /.well-known/openid-configuration | Get Well-Known OpenID Configuration
[**ListAccessPoliciesGranted**](V1PreAuthApi.md#ListAccessPoliciesGranted) | **Post** /v1/accessPoliciesGranted | List Access Policies Granted



## GenerateStsToken

> TokenResponse GenerateStsToken(ctx).GrantType(grantType).Scope(scope).SubjectToken(subjectToken).SubjectTokenType(subjectTokenType).Execute()

generate sts token



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
	grantType := openapiclient.TokenRequest_grantType("client_credentials") // TokenRequestGrantType | 
	scope := "scope_example" // string | Requested scope for the access token. (optional)
	subjectToken := "subjectToken_example" // string | The ID token to exchange. (optional)
	subjectTokenType := openapiclient.TokenRequest_subjectTokenType("urn:ietf:params:oauth:token-type:id_token") // TokenRequestSubjectTokenType |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PreAuthApi.GenerateStsToken(context.Background()).GrantType(grantType).Scope(scope).SubjectToken(subjectToken).SubjectTokenType(subjectTokenType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PreAuthApi.GenerateStsToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateStsToken`: TokenResponse
	fmt.Fprintf(os.Stdout, "Response from `V1PreAuthApi.GenerateStsToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateStsTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **grantType** | [**TokenRequestGrantType**](TokenRequestGrantType.md) |  | 
 **scope** | **string** | Requested scope for the access token. | 
 **subjectToken** | **string** | The ID token to exchange. | 
 **subjectTokenType** | [**TokenRequestSubjectTokenType**](TokenRequestSubjectTokenType.md) |  | 

### Return type

[**TokenResponse**](TokenResponse.md)

### Authorization

[clientCredentials](../README.md#clientCredentials)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJwks

> JwksResponse GetJwks(ctx).Execute()

Get JSON Web Key Set



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PreAuthApi.GetJwks(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PreAuthApi.GetJwks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJwks`: JwksResponse
	fmt.Fprintf(os.Stdout, "Response from `V1PreAuthApi.GetJwks`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetJwksRequest struct via the builder pattern


### Return type

[**JwksResponse**](JwksResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOpenIdConfiguration

> OpenIdConfiguration GetOpenIdConfiguration(ctx).Execute()

Get Well-Known OpenID Configuration



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PreAuthApi.GetOpenIdConfiguration(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PreAuthApi.GetOpenIdConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOpenIdConfiguration`: OpenIdConfiguration
	fmt.Fprintf(os.Stdout, "Response from `V1PreAuthApi.GetOpenIdConfiguration`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetOpenIdConfigurationRequest struct via the builder pattern


### Return type

[**OpenIdConfiguration**](OpenIdConfiguration.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAccessPoliciesGranted

> ListAccessPoliciesGrantedOutput ListAccessPoliciesGranted(ctx).ListPoliciesGrantedInput(listPoliciesGrantedInput).Execute()

List Access Policies Granted



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
	listPoliciesGrantedInput := *openapiclient.NewListPoliciesGrantedInput("project:abc-123", "eyJhbGciOiJSUzI1NiJ9...", openapiclient.ListPoliciesGrantedInput_subjectTokenType("urn:ietf:params:oauth:token-type:id_token")) // ListPoliciesGrantedInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.V1PreAuthApi.ListAccessPoliciesGranted(context.Background()).ListPoliciesGrantedInput(listPoliciesGrantedInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `V1PreAuthApi.ListAccessPoliciesGranted``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAccessPoliciesGranted`: ListAccessPoliciesGrantedOutput
	fmt.Fprintf(os.Stdout, "Response from `V1PreAuthApi.ListAccessPoliciesGranted`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAccessPoliciesGrantedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listPoliciesGrantedInput** | [**ListPoliciesGrantedInput**](ListPoliciesGrantedInput.md) |  | 

### Return type

[**ListAccessPoliciesGrantedOutput**](ListAccessPoliciesGrantedOutput.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

