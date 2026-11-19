# \SmartViewAssetsAPIsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAffectedAsset**](SmartViewAssetsAPIsApi.md#GetAffectedAsset) | **Get** /smartview/v1/asset/tagpoint/affected-assets | Retrieve affected customers assets hierarchy
[**GetAsset**](SmartViewAssetsAPIsApi.md#GetAsset) | **Get** /smartview/v1/asset/list | Retrieve assets list information
[**GetAssetDetails**](SmartViewAssetsAPIsApi.md#GetAssetDetails) | **Get** /smartview/v1/asset/details | Retrieve details for an asset
[**GetCurrentTagPoint**](SmartViewAssetsAPIsApi.md#GetCurrentTagPoint) | **Get** /smartview/v1/asset/tagpoint/current | Retrieve latest tag point data
[**PostAssetDetails**](SmartViewAssetsAPIsApi.md#PostAssetDetails) | **Post** /smartview/v1/asset/details | Retrieve asset details
[**PostCurrentTagPoint**](SmartViewAssetsAPIsApi.md#PostCurrentTagPoint) | **Post** /smartview/v1/asset/tagpoint/current | Retrieve current tag points data
[**SearchAsset**](SmartViewAssetsAPIsApi.md#SearchAsset) | **Get** /smartview/v1/asset/search | Search for Assets matching the identifiers



## GetAffectedAsset

> HierarchyNodeForAssetAPI GetAffectedAsset(ctx).AccountNo(accountNo).Ibx(ibx).AssetId(assetId).Classification(classification).Execute()

Retrieve affected customers assets hierarchy



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
	accountNo := "accountNo_example" // string | customer account number
	ibx := "ibx_example" // string | ibx code
	assetId := "assetId_example" // string | asset id
	classification := openapiclient.getAsset_classification_parameter("Electrical") // GetAssetClassificationParameter | asset classification(Electrical, Mechanical)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.GetAffectedAsset(context.Background()).AccountNo(accountNo).Ibx(ibx).AssetId(assetId).Classification(classification).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.GetAffectedAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAffectedAsset`: HierarchyNodeForAssetAPI
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.GetAffectedAsset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAffectedAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | customer account number | 
 **ibx** | **string** | ibx code | 
 **assetId** | **string** | asset id | 
 **classification** | [**GetAssetClassificationParameter**](GetAssetClassificationParameter.md) | asset classification(Electrical, Mechanical) | 

### Return type

[**HierarchyNodeForAssetAPI**](HierarchyNodeForAssetAPI.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAsset

> AssetsList GetAsset(ctx).AccountNo(accountNo).Ibx(ibx).Classification(classification).Cages(cages).Execute()

Retrieve assets list information



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
	accountNo := "accountNo_example" // string | customer account number
	ibx := "ibx_example" // string | ibx code
	classification := openapiclient.getAsset_classification_parameter("Electrical") // GetAssetClassificationParameter | asset classification (Electrical, Mechanical)
	cages := []string{"Inner_example"} // []string | cage unique space id to be used to filter the assets list assumed to be all cage unique space id if no value is sent. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.GetAsset(context.Background()).AccountNo(accountNo).Ibx(ibx).Classification(classification).Cages(cages).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.GetAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAsset`: AssetsList
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.GetAsset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | customer account number | 
 **ibx** | **string** | ibx code | 
 **classification** | [**GetAssetClassificationParameter**](GetAssetClassificationParameter.md) | asset classification (Electrical, Mechanical) | 
 **cages** | **[]string** | cage unique space id to be used to filter the assets list assumed to be all cage unique space id if no value is sent. | 

### Return type

[**AssetsList**](AssetsList.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssetDetails

> AssetDetailsGetResponse GetAssetDetails(ctx).AccountNo(accountNo).Ibx(ibx).Classification(classification).AssetId(assetId).Execute()

Retrieve details for an asset



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
	accountNo := "accountNo_example" // string | customer account number
	ibx := "ibx_example" // string | ibx code
	classification := "classification_example" // string | asset classification (Electrical, Mechanical)
	assetId := "assetId_example" // string | asset id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.GetAssetDetails(context.Background()).AccountNo(accountNo).Ibx(ibx).Classification(classification).AssetId(assetId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.GetAssetDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetDetails`: AssetDetailsGetResponse
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.GetAssetDetails`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | customer account number | 
 **ibx** | **string** | ibx code | 
 **classification** | **string** | asset classification (Electrical, Mechanical) | 
 **assetId** | **string** | asset id | 

### Return type

[**AssetDetailsGetResponse**](AssetDetailsGetResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCurrentTagPoint

> TagPointData GetCurrentTagPoint(ctx).AccountNo(accountNo).Ibx(ibx).Tagid(tagid).Execute()

Retrieve latest tag point data



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
	accountNo := "accountNo_example" // string | customer account number
	ibx := "ibx_example" // string | ibx code
	tagid := "tagid_example" // string | tag id is the unique identifier for the tag point

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.GetCurrentTagPoint(context.Background()).AccountNo(accountNo).Ibx(ibx).Tagid(tagid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.GetCurrentTagPoint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentTagPoint`: TagPointData
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.GetCurrentTagPoint`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentTagPointRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | customer account number | 
 **ibx** | **string** | ibx code | 
 **tagid** | **string** | tag id is the unique identifier for the tag point | 

### Return type

[**TagPointData**](TagPointData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostAssetDetails

> AssetDetailsResponse PostAssetDetails(ctx).AssetDetailsRequest(assetDetailsRequest).Execute()

Retrieve asset details



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
	assetDetailsRequest := *openapiclient.NewAssetDetailsRequest() // AssetDetailsRequest | request schema

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.PostAssetDetails(context.Background()).AssetDetailsRequest(assetDetailsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.PostAssetDetails``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostAssetDetails`: AssetDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.PostAssetDetails`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostAssetDetailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetDetailsRequest** | [**AssetDetailsRequest**](AssetDetailsRequest.md) | request schema | 

### Return type

[**AssetDetailsResponse**](AssetDetailsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostCurrentTagPoint

> TagPointData PostCurrentTagPoint(ctx).CurrentTagPointRequest(currentTagPointRequest).Execute()

Retrieve current tag points data



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
	currentTagPointRequest := *openapiclient.NewCurrentTagPointRequest() // CurrentTagPointRequest | request schema

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.PostCurrentTagPoint(context.Background()).CurrentTagPointRequest(currentTagPointRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.PostCurrentTagPoint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostCurrentTagPoint`: TagPointData
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.PostCurrentTagPoint`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostCurrentTagPointRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **currentTagPointRequest** | [**CurrentTagPointRequest**](CurrentTagPointRequest.md) | request schema | 

### Return type

[**TagPointData**](TagPointData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchAsset

> Assets SearchAsset(ctx).AccountNo(accountNo).Ibx(ibx).SearchString(searchString).Execute()

Search for Assets matching the identifiers



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
	ibx := "ibx_example" // string | IBX Code
	searchString := "searchString_example" // string | Search String

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewAssetsAPIsApi.SearchAsset(context.Background()).AccountNo(accountNo).Ibx(ibx).SearchString(searchString).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewAssetsAPIsApi.SearchAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAsset`: Assets
	fmt.Fprintf(os.Stdout, "Response from `SmartViewAssetsAPIsApi.SearchAsset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **searchString** | **string** | Search String | 

### Return type

[**Assets**](Assets.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

