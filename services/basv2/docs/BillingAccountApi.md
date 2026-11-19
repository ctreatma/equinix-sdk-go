# \BillingAccountApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBillingAccountByAccountId**](BillingAccountApi.md#GetBillingAccountByAccountId) | **Get** /billing/v2/billingAccounts/{accountId} | Get Billing account detail by account id
[**GetBillingAccountByAccountNumber**](BillingAccountApi.md#GetBillingAccountByAccountNumber) | **Get** /billing/v2/billingAccounts/accountNumber/{accountNumber} | Get billing account detail by account number
[**SearchBillingAccount**](BillingAccountApi.md#SearchBillingAccount) | **Post** /billing/v2/billingAccounts/search | Get customer&#39;s billing accounts



## GetBillingAccountByAccountId

> BillingAccount GetBillingAccountByAccountId(ctx, accountId).Execute()

Get Billing account detail by account id



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/basv2"
)

func main() {
	accountId := "C-12345" // string | Billing Account Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAccountApi.GetBillingAccountByAccountId(context.Background(), accountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAccountApi.GetBillingAccountByAccountId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBillingAccountByAccountId`: BillingAccount
	fmt.Fprintf(os.Stdout, "Response from `BillingAccountApi.GetBillingAccountByAccountId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountId** | **string** | Billing Account Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBillingAccountByAccountIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BillingAccount**](BillingAccount.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBillingAccountByAccountNumber

> BillingAccount GetBillingAccountByAccountNumber(ctx, accountNumber).Execute()

Get billing account detail by account number



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/basv2"
)

func main() {
	accountNumber := "12345" // string | Billing account number

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAccountApi.GetBillingAccountByAccountNumber(context.Background(), accountNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAccountApi.GetBillingAccountByAccountNumber``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBillingAccountByAccountNumber`: BillingAccount
	fmt.Fprintf(os.Stdout, "Response from `BillingAccountApi.GetBillingAccountByAccountNumber`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountNumber** | **string** | Billing account number | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBillingAccountByAccountNumberRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BillingAccount**](BillingAccount.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchBillingAccount

> SearchResponse SearchBillingAccount(ctx).SearchRequest(searchRequest).Execute()

Get customer's billing accounts



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/basv2"
)

func main() {
	searchRequest := *openapiclient.NewSearchRequest() // SearchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAccountApi.SearchBillingAccount(context.Background()).SearchRequest(searchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAccountApi.SearchBillingAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchBillingAccount`: SearchResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAccountApi.SearchBillingAccount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchBillingAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchRequest** | [**SearchRequest**](SearchRequest.md) |  | 

### Return type

[**SearchResponse**](SearchResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

