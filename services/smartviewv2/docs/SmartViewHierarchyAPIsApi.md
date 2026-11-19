# \SmartViewHierarchyAPIsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetLocationHierarchy**](SmartViewHierarchyAPIsApi.md#GetLocationHierarchy) | **Get** /smartview/v1/hierarchy/location | Retrieve the Location Hierarchy
[**GetPowerHierarchy**](SmartViewHierarchyAPIsApi.md#GetPowerHierarchy) | **Get** /smartview/v1/hierarchy/power | Retrieve the Power Hierarchy



## GetLocationHierarchy

> []HierarchyNode GetLocationHierarchy(ctx).AccountNo(accountNo).Ibx(ibx).Execute()

Retrieve the Location Hierarchy



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/smartviewv2"
)

func main() {
	accountNo := "accountNo_example" // string | Customer Account Number
	ibx := "ibx_example" // string | IBX Code (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewHierarchyAPIsApi.GetLocationHierarchy(context.Background()).AccountNo(accountNo).Ibx(ibx).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewHierarchyAPIsApi.GetLocationHierarchy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLocationHierarchy`: []HierarchyNode
	fmt.Fprintf(os.Stdout, "Response from `SmartViewHierarchyAPIsApi.GetLocationHierarchy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLocationHierarchyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 

### Return type

[**[]HierarchyNode**](HierarchyNode.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPowerHierarchy

> []PowerHierarchyNode GetPowerHierarchy(ctx).AccountNo(accountNo).Ibx(ibx).Execute()

Retrieve the Power Hierarchy



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/smartviewv2"
)

func main() {
	accountNo := "accountNo_example" // string | Customer Account Number
	ibx := "ibx_example" // string | IBX Code (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewHierarchyAPIsApi.GetPowerHierarchy(context.Background()).AccountNo(accountNo).Ibx(ibx).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewHierarchyAPIsApi.GetPowerHierarchy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPowerHierarchy`: []PowerHierarchyNode
	fmt.Fprintf(os.Stdout, "Response from `SmartViewHierarchyAPIsApi.GetPowerHierarchy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPowerHierarchyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 

### Return type

[**[]PowerHierarchyNode**](PowerHierarchyNode.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

