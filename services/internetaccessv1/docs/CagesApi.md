# \CagesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCages**](CagesApi.md#GetCages) | **Get** /internetAccess/v1/cages | Get list of available Cages



## GetCages

> CagesPage GetCages(ctx).LocationIbx(locationIbx).AccountAccountNumber(accountAccountNumber).Offset(offset).Limit(limit).Execute()

Get list of available Cages



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
	locationIbx := "CH2" // string | IBX code for given location
	accountAccountNumber := "123111232" // string | Account number
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CagesApi.GetCages(context.Background()).LocationIbx(locationIbx).AccountAccountNumber(accountAccountNumber).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CagesApi.GetCages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCages`: CagesPage
	fmt.Fprintf(os.Stdout, "Response from `CagesApi.GetCages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationIbx** | **string** | IBX code for given location | 
 **accountAccountNumber** | **string** | Account number | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**CagesPage**](CagesPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

