# \PricesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchPrices**](PricesApi.md#SearchPrices) | **Post** /internetAccess/v1/prices/search | Search EIA prices



## SearchPrices

> PriceSearchResponse SearchPrices(ctx).FilterBody(filterBody).Offset(offset).Limit(limit).Execute()

Search EIA prices



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
	filterBody := *openapiclient.NewFilterBody(*openapiclient.NewSearchFilter([]openapiclient.SimpleExpression{*openapiclient.NewSimpleExpression("Property_example", openapiclient.SimpleExpression_operator("="), []string{"Values_example"})})) // FilterBody | 
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PricesApi.SearchPrices(context.Background()).FilterBody(filterBody).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PricesApi.SearchPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchPrices`: PriceSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `PricesApi.SearchPrices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchPricesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filterBody** | [**FilterBody**](FilterBody.md) |  | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**PriceSearchResponse**](PriceSearchResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

