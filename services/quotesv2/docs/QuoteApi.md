# \QuoteApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RetrieveAQuote**](QuoteApi.md#RetrieveAQuote) | **Get** /v2/quotes/{quoteId} | Retrieve a quote



## RetrieveAQuote

> QuoteResponse RetrieveAQuote(ctx, quoteId).Ibxs(ibxs).Execute()

Retrieve a quote



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/quotesv2"
)

func main() {
	quoteId := "quoteId_example" // string | Identifier of the quote
	ibxs := []string{"Inner_example"} // []string | List of IBXs to be filtered (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuoteApi.RetrieveAQuote(context.Background(), quoteId).Ibxs(ibxs).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuoteApi.RetrieveAQuote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveAQuote`: QuoteResponse
	fmt.Fprintf(os.Stdout, "Response from `QuoteApi.RetrieveAQuote`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**quoteId** | **string** | Identifier of the quote | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveAQuoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ibxs** | **[]string** | List of IBXs to be filtered | 

### Return type

[**QuoteResponse**](QuoteResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

