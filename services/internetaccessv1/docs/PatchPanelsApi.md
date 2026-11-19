# \PatchPanelsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPatchPanels**](PatchPanelsApi.md#GetPatchPanels) | **Get** /internetAccess/v1/patchPanels | Get list of available Patch Panels



## GetPatchPanels

> PatchPanelsPage GetPatchPanels(ctx).LocationIbx(locationIbx).AccountAccountNumber(accountAccountNumber).CageSpaceId(cageSpaceId).CabinetSpaceId(cabinetSpaceId).MediaTypesName(mediaTypesName).Offset(offset).Limit(limit).Execute()

Get list of available Patch Panels



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
	cageSpaceId := "CH2:03:00603" // string | Cage space ID
	cabinetSpaceId := "CH1:01:011201:0204" // string | Cabinet space ID
	mediaTypesName := "SINGLE_MODE_FIBER" // string | Media Type (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PatchPanelsApi.GetPatchPanels(context.Background()).LocationIbx(locationIbx).AccountAccountNumber(accountAccountNumber).CageSpaceId(cageSpaceId).CabinetSpaceId(cabinetSpaceId).MediaTypesName(mediaTypesName).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PatchPanelsApi.GetPatchPanels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPatchPanels`: PatchPanelsPage
	fmt.Fprintf(os.Stdout, "Response from `PatchPanelsApi.GetPatchPanels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPatchPanelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationIbx** | **string** | IBX code for given location | 
 **accountAccountNumber** | **string** | Account number | 
 **cageSpaceId** | **string** | Cage space ID | 
 **cabinetSpaceId** | **string** | Cabinet space ID | 
 **mediaTypesName** | **string** | Media Type | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**PatchPanelsPage**](PatchPanelsPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

