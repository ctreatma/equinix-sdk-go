# \AssetsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAssetById**](AssetsApi.md#GetAssetById) | **Get** /v1/assets/{assetId} | Get details of an asset
[**SearchAssets**](AssetsApi.md#SearchAssets) | **Post** /v1/assets/search | Search permissible assets



## GetAssetById

> Asset GetAssetById(ctx, assetId).Authorization(authorization).Execute()

Get details of an asset



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/assetsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.
	assetId := "assetId_example" // string | {assetId} identification number

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsApi.GetAssetById(context.Background(), assetId).Authorization(authorization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsApi.GetAssetById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetById`: Asset
	fmt.Fprintf(os.Stdout, "Response from `AssetsApi.GetAssetById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** | {assetId} identification number | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 


### Return type

[**Asset**](Asset.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchAssets

> AssetsSearchResponse SearchAssets(ctx).Authorization(authorization).Sorts(sorts).Source(source).Q(q).ExactMatch(exactMatch).Offset(offset).Limit(limit).Body(body).Execute()

Search permissible assets



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/assetsv1"
)

func main() {
	authorization := "authorization_example" // string | Specify the Access token with prefix 'Bearer '.
	sorts := []openapiclient.SearchAssetsSortsParameterInner{openapiclient.searchAssets_sorts_parameter_inner("SERIAL_NUMBER")} // []SearchAssetsSortsParameterInner | Sort fields  (optional)
	source := []openapiclient.SearchAssetsSourceParameterInner{openapiclient.searchAssets_source_parameter_inner("LEGACY_CAGE")} // []SearchAssetsSourceParameterInner | \"q\" parameter will be searched in these fields, by default search will performed on all fields (optional)
	q := "q_example" // string | To support add a keyword, free text search on source fields. Min 3 character for efficient search results. (optional)
	exactMatch := true // bool | flag determines the q should be Exact match or partial match, By default flag is false (optional)
	offset := int32(56) // int32 | The start index from which the list is created. (optional)
	limit := int32(56) // int32 | Number of entries in response. (optional)
	body := *openapiclient.NewAssetsSearchRequest() // AssetsSearchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AssetsApi.SearchAssets(context.Background()).Authorization(authorization).Sorts(sorts).Source(source).Q(q).ExactMatch(exactMatch).Offset(offset).Limit(limit).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AssetsApi.SearchAssets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAssets`: AssetsSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `AssetsApi.SearchAssets`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAssetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string** | Specify the Access token with prefix &#39;Bearer &#39;. | 
 **sorts** | [**[]SearchAssetsSortsParameterInner**](SearchAssetsSortsParameterInner.md) | Sort fields  | 
 **source** | [**[]SearchAssetsSourceParameterInner**](SearchAssetsSourceParameterInner.md) | \&quot;q\&quot; parameter will be searched in these fields, by default search will performed on all fields | 
 **q** | **string** | To support add a keyword, free text search on source fields. Min 3 character for efficient search results. | 
 **exactMatch** | **bool** | flag determines the q should be Exact match or partial match, By default flag is false | 
 **offset** | **int32** | The start index from which the list is created. | 
 **limit** | **int32** | Number of entries in response. | 
 **body** | [**AssetsSearchRequest**](AssetsSearchRequest.md) |  | 

### Return type

[**AssetsSearchResponse**](AssetsSearchResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

