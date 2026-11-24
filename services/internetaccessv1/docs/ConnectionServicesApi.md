# \ConnectionServicesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetConnectionServices**](ConnectionServicesApi.md#GetConnectionServices) | **Get** /internetAccess/v1/connectionServices | Get list of available connection services



## GetConnectionServices

> ConnectionServicesPage GetConnectionServices(ctx).MediaTypesConnectorTypesLocationsIbx(mediaTypesConnectorTypesLocationsIbx).Offset(offset).Limit(limit).Execute()

Get list of available connection services



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
	mediaTypesConnectorTypesLocationsIbx := "SG1" // string | IBX Code
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ConnectionServicesApi.GetConnectionServices(context.Background()).MediaTypesConnectorTypesLocationsIbx(mediaTypesConnectorTypesLocationsIbx).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ConnectionServicesApi.GetConnectionServices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConnectionServices`: ConnectionServicesPage
	fmt.Fprintf(os.Stdout, "Response from `ConnectionServicesApi.GetConnectionServices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetConnectionServicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mediaTypesConnectorTypesLocationsIbx** | **string** | IBX Code | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**ConnectionServicesPage**](ConnectionServicesPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

