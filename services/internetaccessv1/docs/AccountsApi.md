# \AccountsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountAgreements**](AccountsApi.md#AccountAgreements) | **Get** /internetAccess/v1/accounts/{accountNumber}/agreements | Lists account agreement statuses
[**ListAccounts**](AccountsApi.md#ListAccounts) | **Get** /internetAccess/v1/accounts | Lists accounts available for user within IBX
[**SingleAccount**](AccountsApi.md#SingleAccount) | **Get** /internetAccess/v1/accounts/{accountNumber} | Returns a single account



## AccountAgreements

> AccountAgreementsPage AccountAgreements(ctx, accountNumber).Ibx(ibx).Offset(offset).Limit(limit).Execute()

Lists account agreement statuses



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
	accountNumber := "100013200" // string | Number of account to search by
	ibx := "WA1" // string | Agreement IBX
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsApi.AccountAgreements(context.Background(), accountNumber).Ibx(ibx).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsApi.AccountAgreements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountAgreements`: AccountAgreementsPage
	fmt.Fprintf(os.Stdout, "Response from `AccountsApi.AccountAgreements`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountNumber** | **string** | Number of account to search by | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountAgreementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ibx** | **string** | Agreement IBX | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**AccountAgreementsPage**](AccountAgreementsPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAccounts

> AccountPage ListAccounts(ctx).OperationalUnitsIbxsIbx(operationalUnitsIbxsIbx).ProjectProjectId(projectProjectId).Offset(offset).Limit(limit).Execute()

Lists accounts available for user within IBX



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
	operationalUnitsIbxsIbx := "SG1" // string | Operational Unit IBX code
	projectProjectId := "7348" // string | Customer Resource Hierarchy Project identifier, for future use, not applicable in EIA on dedicated port scenario (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsApi.ListAccounts(context.Background()).OperationalUnitsIbxsIbx(operationalUnitsIbxsIbx).ProjectProjectId(projectProjectId).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsApi.ListAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAccounts`: AccountPage
	fmt.Fprintf(os.Stdout, "Response from `AccountsApi.ListAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **operationalUnitsIbxsIbx** | **string** | Operational Unit IBX code | 
 **projectProjectId** | **string** | Customer Resource Hierarchy Project identifier, for future use, not applicable in EIA on dedicated port scenario | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**AccountPage**](AccountPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SingleAccount

> AccountDetails SingleAccount(ctx, accountNumber).Execute()

Returns a single account



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
	accountNumber := "100013200" // string | Number of account to search by

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountsApi.SingleAccount(context.Background(), accountNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountsApi.SingleAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SingleAccount`: AccountDetails
	fmt.Fprintf(os.Stdout, "Response from `AccountsApi.SingleAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**accountNumber** | **string** | Number of account to search by | 

### Other Parameters

Other parameters are passed through a pointer to a apiSingleAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountDetails**](AccountDetails.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

