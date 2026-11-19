# \SignaturePoliciesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSignaturePolicies**](SignaturePoliciesApi.md#GetSignaturePolicies) | **Get** /internetAccess/v1/signaturePolicies | List signature policies



## GetSignaturePolicies

> SignaturePoliciesPage GetSignaturePolicies(ctx).Offset(offset).Limit(limit).LocationCountryCode(locationCountryCode).Execute()

List signature policies



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)
	locationCountryCode := "US" // string | Country code (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SignaturePoliciesApi.GetSignaturePolicies(context.Background()).Offset(offset).Limit(limit).LocationCountryCode(locationCountryCode).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SignaturePoliciesApi.GetSignaturePolicies``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSignaturePolicies`: SignaturePoliciesPage
	fmt.Fprintf(os.Stdout, "Response from `SignaturePoliciesApi.GetSignaturePolicies`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSignaturePoliciesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]
 **locationCountryCode** | **string** | Country code | 

### Return type

[**SignaturePoliciesPage**](SignaturePoliciesPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

