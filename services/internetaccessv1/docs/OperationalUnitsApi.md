# \OperationalUnitsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetOperationalUnits**](OperationalUnitsApi.md#GetOperationalUnits) | **Get** /internetAccess/v1/operationalUnits | List operational units



## GetOperationalUnits

> OperationalUnitPage GetOperationalUnits(ctx).LocationIbx(locationIbx).Offset(offset).Limit(limit).Execute()

List operational units



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
	locationIbx := "SG1" // string | Operational Unit IBX code
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OperationalUnitsApi.GetOperationalUnits(context.Background()).LocationIbx(locationIbx).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OperationalUnitsApi.GetOperationalUnits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOperationalUnits`: OperationalUnitPage
	fmt.Fprintf(os.Stdout, "Response from `OperationalUnitsApi.GetOperationalUnits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOperationalUnitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationIbx** | **string** | Operational Unit IBX code | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**OperationalUnitPage**](OperationalUnitPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

