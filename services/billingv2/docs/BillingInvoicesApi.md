# \BillingInvoicesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RetrieveBillingDetails**](BillingInvoicesApi.md#RetrieveBillingDetails) | **Get** /v2/invoices/details | Retrieve billing details
[**RetrieveBillingSummary**](BillingInvoicesApi.md#RetrieveBillingSummary) | **Get** /v2/invoices | Retrieve billing summary



## RetrieveBillingDetails

> InvoiceResponse RetrieveBillingDetails(ctx).StartDate(startDate).EndDate(endDate).AccountNumbers(accountNumbers).TransactionIds(transactionIds).Offset(offset).Limit(limit).Execute()

Retrieve billing details



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/billingv2"
)

func main() {
	startDate := time.Now() // string | Start date of invoice in `YYYY-MM-DD` format (optional)
	endDate := time.Now() // string | End date of invoice in `YYYY-MM-DD` format (optional)
	accountNumbers := []string{"Inner_example"} // []string | List of accounts to be filtered (optional)
	transactionIds := []string{"Inner_example"} // []string | List of transactions to be filtered (optional)
	offset := int32(56) // int32 | Use offset to control the number of records to be skipped in the response. (optional) (default to 0)
	limit := int32(56) // int32 | Use limit to restrict the number of records in the response. (optional) (default to 10)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingInvoicesApi.RetrieveBillingDetails(context.Background()).StartDate(startDate).EndDate(endDate).AccountNumbers(accountNumbers).TransactionIds(transactionIds).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingInvoicesApi.RetrieveBillingDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveBillingDetails`: InvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingInvoicesApi.RetrieveBillingDetails`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveBillingDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDate** | **string** | Start date of invoice in &#x60;YYYY-MM-DD&#x60; format | 
 **endDate** | **string** | End date of invoice in &#x60;YYYY-MM-DD&#x60; format | 
 **accountNumbers** | **[]string** | List of accounts to be filtered | 
 **transactionIds** | **[]string** | List of transactions to be filtered | 
 **offset** | **int32** | Use offset to control the number of records to be skipped in the response. | [default to 0]
 **limit** | **int32** | Use limit to restrict the number of records in the response. | [default to 10]

### Return type

[**InvoiceResponse**](InvoiceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrieveBillingSummary

> InvoiceSummaryResponse RetrieveBillingSummary(ctx).StartDate(startDate).EndDate(endDate).AccountNumbers(accountNumbers).TransactionIds(transactionIds).Offset(offset).Limit(limit).Execute()

Retrieve billing summary



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/billingv2"
)

func main() {
	startDate := time.Now() // string | Start date of invoice in `YYYY-MM-DD` format (optional)
	endDate := time.Now() // string | End date of invoice in `YYYY-MM-DD` format (optional)
	accountNumbers := []string{"Inner_example"} // []string | List of accounts to be filtered (optional)
	transactionIds := []string{"Inner_example"} // []string | List of transactions to be filtered (optional)
	offset := int32(56) // int32 | Use offset to control the number of records to be skipped in the response. (optional) (default to 0)
	limit := int32(56) // int32 | Use limit to restrict the number of records in the response. (optional) (default to 10)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingInvoicesApi.RetrieveBillingSummary(context.Background()).StartDate(startDate).EndDate(endDate).AccountNumbers(accountNumbers).TransactionIds(transactionIds).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingInvoicesApi.RetrieveBillingSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveBillingSummary`: InvoiceSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingInvoicesApi.RetrieveBillingSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveBillingSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDate** | **string** | Start date of invoice in &#x60;YYYY-MM-DD&#x60; format | 
 **endDate** | **string** | End date of invoice in &#x60;YYYY-MM-DD&#x60; format | 
 **accountNumbers** | **[]string** | List of accounts to be filtered | 
 **transactionIds** | **[]string** | List of transactions to be filtered | 
 **offset** | **int32** | Use offset to control the number of records to be skipped in the response. | [default to 0]
 **limit** | **int32** | Use limit to restrict the number of records in the response. | [default to 10]

### Return type

[**InvoiceSummaryResponse**](InvoiceSummaryResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

