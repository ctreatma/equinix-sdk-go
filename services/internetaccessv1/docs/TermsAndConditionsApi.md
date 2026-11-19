# \TermsAndConditionsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetTermsAndConditions**](TermsAndConditionsApi.md#GetTermsAndConditions) | **Get** /internetAccess/v1/terms | Retrieve terms and conditions



## GetTermsAndConditions

> TermsAndConditionsPage GetTermsAndConditions(ctx).AccountAccountNumber(accountAccountNumber).LocationIbx(locationIbx).ConnectivitySourceType(connectivitySourceType).Product(product).Offset(offset).Limit(limit).Type_(type_).Language(language).Execute()

Retrieve terms and conditions



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
	accountAccountNumber := "123111232" // string | Account number
	locationIbx := "CH2" // string | IBX code for given location
	connectivitySourceType := openapiclient.getTermsAndConditions_connectivitySource_type_parameter("COLO") // GetTermsAndConditionsConnectivitySourceTypeParameter | Connectivity source type
	product := openapiclient.getTermsAndConditions_product_parameter("IA_C") // GetTermsAndConditionsProductParameter | Product
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)
	type_ := openapiclient.getTermsAndConditions_type_parameter("TERMS_AND_CONDITIONS") // GetTermsAndConditionsTypeParameter | Agreement type (optional)
	language := "en" // string | 2 letter ISO 639-1 language code (optional) (default to "en")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TermsAndConditionsApi.GetTermsAndConditions(context.Background()).AccountAccountNumber(accountAccountNumber).LocationIbx(locationIbx).ConnectivitySourceType(connectivitySourceType).Product(product).Offset(offset).Limit(limit).Type_(type_).Language(language).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TermsAndConditionsApi.GetTermsAndConditions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTermsAndConditions`: TermsAndConditionsPage
	fmt.Fprintf(os.Stdout, "Response from `TermsAndConditionsApi.GetTermsAndConditions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTermsAndConditionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountAccountNumber** | **string** | Account number | 
 **locationIbx** | **string** | IBX code for given location | 
 **connectivitySourceType** | [**GetTermsAndConditionsConnectivitySourceTypeParameter**](GetTermsAndConditionsConnectivitySourceTypeParameter.md) | Connectivity source type | 
 **product** | [**GetTermsAndConditionsProductParameter**](GetTermsAndConditionsProductParameter.md) | Product | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]
 **type_** | [**GetTermsAndConditionsTypeParameter**](GetTermsAndConditionsTypeParameter.md) | Agreement type | 
 **language** | **string** | 2 letter ISO 639-1 language code | [default to &quot;en&quot;]

### Return type

[**TermsAndConditionsPage**](TermsAndConditionsPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

