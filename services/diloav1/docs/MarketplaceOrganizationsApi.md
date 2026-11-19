# \MarketplaceOrganizationsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FindOrganizations**](MarketplaceOrganizationsApi.md#FindOrganizations) | **Get** /diloa/v1/organizations | Marketplace organizations selection



## FindOrganizations

> []CustomerOrganization FindOrganizations(ctx).LocationIbx(locationIbx).ProductType(productType).Execute()

Marketplace organizations selection



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
	locationIbx := "AM11" // string | IBX data center identifier.
	productType := []openapiclient.FindOrganizationsProductTypeParameterInner{openapiclient.findOrganizations_product_type_parameter_inner("CROSS_CONNECT")} // []FindOrganizationsProductTypeParameterInner | Product types. (optional) (default to ["CROSS_CONNECT"])

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MarketplaceOrganizationsApi.FindOrganizations(context.Background()).LocationIbx(locationIbx).ProductType(productType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MarketplaceOrganizationsApi.FindOrganizations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindOrganizations`: []CustomerOrganization
	fmt.Fprintf(os.Stdout, "Response from `MarketplaceOrganizationsApi.FindOrganizations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFindOrganizationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationIbx** | **string** | IBX data center identifier. | 
 **productType** | [**[]FindOrganizationsProductTypeParameterInner**](FindOrganizationsProductTypeParameterInner.md) | Product types. | [default to [&quot;CROSS_CONNECT&quot;]]

### Return type

[**[]CustomerOrganization**](CustomerOrganization.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

