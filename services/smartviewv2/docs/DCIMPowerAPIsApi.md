# \DCIMPowerAPIsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCurrentPowerData**](DCIMPowerAPIsApi.md#GetCurrentPowerData) | **Get** /power/v1/current | Retrieve current power consumption data
[**GetTrendingPowerData**](DCIMPowerAPIsApi.md#GetTrendingPowerData) | **Get** /power/v1/trending | Retrieve Trending Power Data.
[**PostCurrentPowerData**](DCIMPowerAPIsApi.md#PostCurrentPowerData) | **Post** /power/v1/current | Retrieve current power consumption data



## GetCurrentPowerData

> PowerData GetCurrentPowerData(ctx).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Execute()

Retrieve current power consumption data



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
	levelType := openapiclient.getCurrentPowerData_levelType_parameter("ibx") // GetCurrentPowerDataLevelTypeParameter | level type allowed value [ibx|cage|cabinet|circuit]
	levelValue := "levelValue_example" // string | level value - ibx code, cage unique space id, cabinet unique space id, serial number for level type ibx, cage, cabinet, circuit respectively.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DCIMPowerAPIsApi.GetCurrentPowerData(context.Background()).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DCIMPowerAPIsApi.GetCurrentPowerData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentPowerData`: PowerData
	fmt.Fprintf(os.Stdout, "Response from `DCIMPowerAPIsApi.GetCurrentPowerData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentPowerDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **levelType** | [**GetCurrentPowerDataLevelTypeParameter**](GetCurrentPowerDataLevelTypeParameter.md) | level type allowed value [ibx|cage|cabinet|circuit] | 
 **levelValue** | **string** | level value - ibx code, cage unique space id, cabinet unique space id, serial number for level type ibx, cage, cabinet, circuit respectively. | 

### Return type

[**PowerData**](PowerData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrendingPowerData

> TrendingPowerData GetTrendingPowerData(ctx).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Interval(interval).FromDate(fromDate).ToDate(toDate).Execute()

Retrieve Trending Power Data.



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
	levelType := openapiclient.getCurrentPowerData_levelType_parameter("ibx") // GetCurrentPowerDataLevelTypeParameter | [ibx|cage|cabinet|circuit]
	levelValue := "levelValue_example" // string | ibx code, cage unique space id, cabinet unique space id and serial number for level type ibx, cage, cabinet and circuit respectively.
	interval := "interval_example" // string | [recording|1h|1d]
	fromDate := "fromDate_example" // string | timestamp expected to be epoch long (milliseconds).
	toDate := "toDate_example" // string | timestamp expected to be epoch long (milliseconds).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DCIMPowerAPIsApi.GetTrendingPowerData(context.Background()).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Interval(interval).FromDate(fromDate).ToDate(toDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DCIMPowerAPIsApi.GetTrendingPowerData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrendingPowerData`: TrendingPowerData
	fmt.Fprintf(os.Stdout, "Response from `DCIMPowerAPIsApi.GetTrendingPowerData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTrendingPowerDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **levelType** | [**GetCurrentPowerDataLevelTypeParameter**](GetCurrentPowerDataLevelTypeParameter.md) | [ibx|cage|cabinet|circuit] | 
 **levelValue** | **string** | ibx code, cage unique space id, cabinet unique space id and serial number for level type ibx, cage, cabinet and circuit respectively. | 
 **interval** | **string** | [recording|1h|1d] | 
 **fromDate** | **string** | timestamp expected to be epoch long (milliseconds). | 
 **toDate** | **string** | timestamp expected to be epoch long (milliseconds). | 

### Return type

[**TrendingPowerData**](TrendingPowerData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostCurrentPowerData

> PowerDataResponseIBX PostCurrentPowerData(ctx).PowerCurrentPostRequest(powerCurrentPostRequest).Execute()

Retrieve current power consumption data



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
	powerCurrentPostRequest := *openapiclient.NewPowerCurrentPostRequest() // PowerCurrentPostRequest | request payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DCIMPowerAPIsApi.PostCurrentPowerData(context.Background()).PowerCurrentPostRequest(powerCurrentPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DCIMPowerAPIsApi.PostCurrentPowerData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostCurrentPowerData`: PowerDataResponseIBX
	fmt.Fprintf(os.Stdout, "Response from `DCIMPowerAPIsApi.PostCurrentPowerData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostCurrentPowerDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **powerCurrentPostRequest** | [**PowerCurrentPostRequest**](PowerCurrentPostRequest.md) | request payload | 

### Return type

[**PowerDataResponseIBX**](PowerDataResponseIBX.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

