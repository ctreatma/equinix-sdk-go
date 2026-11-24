# \DCIMSystemAlertApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAlerts**](DCIMSystemAlertApi.md#GetAlerts) | **Post** /smartview/v2/systemAlerts/search | System alerts search
[**PostAlerts**](DCIMSystemAlertApi.md#PostAlerts) | **Get** /smartview/v2/systemAlerts/search | System alerts search



## GetAlerts

> PaginatedResponseAlertReadModel GetAlerts(ctx).SearchRequest(searchRequest).Execute()

System alerts search



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
	searchRequest := *openapiclient.NewSearchRequest() // SearchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DCIMSystemAlertApi.GetAlerts(context.Background()).SearchRequest(searchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DCIMSystemAlertApi.GetAlerts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlerts`: PaginatedResponseAlertReadModel
	fmt.Fprintf(os.Stdout, "Response from `DCIMSystemAlertApi.GetAlerts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAlertsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **searchRequest** | [**SearchRequest**](SearchRequest.md) |  | 

### Return type

[**PaginatedResponseAlertReadModel**](PaginatedResponseAlertReadModel.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostAlerts

> PaginatedResponseAlertReadModel PostAlerts(ctx).Limit(limit).Offset(offset).Status(status).AssetClassification(assetClassification).EdgeCollectedOn(edgeCollectedOn).Execute()

System alerts search



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
	limit := int32(100) // int32 | Number of records to retrieve per request.
	offset := int32(0) // int32 | Record Number you want start to retrieve from (0..N)
	status := "ACTIVE" // string | Alert status - ACTIVE or INACTIVE (optional)
	assetClassification := "Mechanical" // string | The class of assets this asset belongs to - Mechanical/Electrical/Environmental (optional)
	edgeCollectedOn := "2023-11-30T05:08:39.345Z" // string | Returns the alarms after the passed time (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DCIMSystemAlertApi.PostAlerts(context.Background()).Limit(limit).Offset(offset).Status(status).AssetClassification(assetClassification).EdgeCollectedOn(edgeCollectedOn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DCIMSystemAlertApi.PostAlerts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostAlerts`: PaginatedResponseAlertReadModel
	fmt.Fprintf(os.Stdout, "Response from `DCIMSystemAlertApi.PostAlerts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostAlertsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Number of records to retrieve per request. | 
 **offset** | **int32** | Record Number you want start to retrieve from (0..N) | 
 **status** | **string** | Alert status - ACTIVE or INACTIVE | 
 **assetClassification** | **string** | The class of assets this asset belongs to - Mechanical/Electrical/Environmental | 
 **edgeCollectedOn** | **string** | Returns the alarms after the passed time | 

### Return type

[**PaginatedResponseAlertReadModel**](PaginatedResponseAlertReadModel.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

