# \UserProfileApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBetaTermsAgreement**](UserProfileApi.md#GetBetaTermsAgreement) | **Get** /diloa/v1/betaTermsAgreement | Get beta terms agreement
[**UpdateBetaTermsAgreement**](UserProfileApi.md#UpdateBetaTermsAgreement) | **Put** /diloa/v1/betaTermsAgreement | Update beta terms agreement



## GetBetaTermsAgreement

> BetaTermsAgreement GetBetaTermsAgreement(ctx).Execute()

Get beta terms agreement



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/diloav1"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserProfileApi.GetBetaTermsAgreement(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileApi.GetBetaTermsAgreement``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBetaTermsAgreement`: BetaTermsAgreement
	fmt.Fprintf(os.Stdout, "Response from `UserProfileApi.GetBetaTermsAgreement`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBetaTermsAgreementRequest struct via the builder pattern


### Return type

[**BetaTermsAgreement**](BetaTermsAgreement.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateBetaTermsAgreement

> BetaTermsAgreement UpdateBetaTermsAgreement(ctx).BetaTermsAgreement(betaTermsAgreement).Execute()

Update beta terms agreement



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/diloav1"
)

func main() {
	betaTermsAgreement := *openapiclient.NewBetaTermsAgreement() // BetaTermsAgreement |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserProfileApi.UpdateBetaTermsAgreement(context.Background()).BetaTermsAgreement(betaTermsAgreement).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserProfileApi.UpdateBetaTermsAgreement``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateBetaTermsAgreement`: BetaTermsAgreement
	fmt.Fprintf(os.Stdout, "Response from `UserProfileApi.UpdateBetaTermsAgreement`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateBetaTermsAgreementRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **betaTermsAgreement** | [**BetaTermsAgreement**](BetaTermsAgreement.md) |  | 

### Return type

[**BetaTermsAgreement**](BetaTermsAgreement.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

