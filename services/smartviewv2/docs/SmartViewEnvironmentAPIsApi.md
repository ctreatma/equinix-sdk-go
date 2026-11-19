# \SmartViewEnvironmentAPIsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCurrentEnvironmentData**](SmartViewEnvironmentAPIsApi.md#GetCurrentEnvironmentData) | **Get** /environment/v1/current | Retrieve current environmental data
[**GetSensorReadings**](SmartViewEnvironmentAPIsApi.md#GetSensorReadings) | **Get** /smartview/v2/environmental/ibxs/{ibx}/sensors/readings | Retrieve IBX sensors current readings
[**GetSingleSensorReadings**](SmartViewEnvironmentAPIsApi.md#GetSingleSensorReadings) | **Get** /smartview/v2/environmental/ibxs/{ibx}/sensors/{sensorId}/readings | Retrieve Single sensor current value(s)
[**GetTrendingEnvironmentData**](SmartViewEnvironmentAPIsApi.md#GetTrendingEnvironmentData) | **Get** /environment/v1/trending | Retrieve trending environmental data
[**ListCurrentEnvironmentData**](SmartViewEnvironmentAPIsApi.md#ListCurrentEnvironmentData) | **Get** /environment/v1/listCurrent | Retrieve a list of environmental data



## GetCurrentEnvironmentData

> EnvironmentData GetCurrentEnvironmentData(ctx).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Execute()

Retrieve current environmental data



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
	levelType := openapiclient.getCurrentEnvironmentData_levelType_parameter("IBX") // GetCurrentEnvironmentDataLevelTypeParameter | Level Type
	levelValue := "CH2:1:06:ColoArea:1" // string | Identifies the location to query, depending on levelType. For IBX, the IBX code, for example CH2. For ZONE, the zone unique space ID, a colon-separated string in the format `<ibxCode>:<phase>:<floor>:<room>:<zone>`, for example CH2:1:06:ColoArea:1. The zone segment is optional; when there is no zone it is left empty and the trailing colon is kept, for example AM3:1:R1:RoofTop:.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewEnvironmentAPIsApi.GetCurrentEnvironmentData(context.Background()).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).LevelValue(levelValue).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewEnvironmentAPIsApi.GetCurrentEnvironmentData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentEnvironmentData`: EnvironmentData
	fmt.Fprintf(os.Stdout, "Response from `SmartViewEnvironmentAPIsApi.GetCurrentEnvironmentData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentEnvironmentDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **levelType** | [**GetCurrentEnvironmentDataLevelTypeParameter**](GetCurrentEnvironmentDataLevelTypeParameter.md) | Level Type | 
 **levelValue** | **string** | Identifies the location to query, depending on levelType. For IBX, the IBX code, for example CH2. For ZONE, the zone unique space ID, a colon-separated string in the format &#x60;&lt;ibxCode&gt;:&lt;phase&gt;:&lt;floor&gt;:&lt;room&gt;:&lt;zone&gt;&#x60;, for example CH2:1:06:ColoArea:1. The zone segment is optional; when there is no zone it is left empty and the trailing colon is kept, for example AM3:1:R1:RoofTop:. | 

### Return type

[**EnvironmentData**](EnvironmentData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSensorReadings

> SensorReadingsResponse GetSensorReadings(ctx, ibx).Type_(type_).Zone(zone).Offset(offset).Limit(limit).Execute()

Retrieve IBX sensors current readings



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
	ibx := "CH2" // string | IBX where the sensor is located.
	type_ := "HUMIDITY" // string | Type of sensor data to display, e.g. specifying 'HUMIDITY' means only sensor readings with HUMIDITY value will be included (optional)
	zone := "CH2:1:06:ColoArea:1" // string | Zone name. Adding this parameter limits the query to sensors in the specified zone (optional)
	offset := int32(56) // int32 | Results offset you want to retrieve (0..N) (optional) (default to 0)
	limit := int32(56) // int32 | Number of records to retrieve per request. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewEnvironmentAPIsApi.GetSensorReadings(context.Background(), ibx).Type_(type_).Zone(zone).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewEnvironmentAPIsApi.GetSensorReadings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSensorReadings`: SensorReadingsResponse
	fmt.Fprintf(os.Stdout, "Response from `SmartViewEnvironmentAPIsApi.GetSensorReadings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ibx** | **string** | IBX where the sensor is located. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSensorReadingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **string** | Type of sensor data to display, e.g. specifying &#39;HUMIDITY&#39; means only sensor readings with HUMIDITY value will be included | 
 **zone** | **string** | Zone name. Adding this parameter limits the query to sensors in the specified zone | 
 **offset** | **int32** | Results offset you want to retrieve (0..N) | [default to 0]
 **limit** | **int32** | Number of records to retrieve per request. | [default to 20]

### Return type

[**SensorReadingsResponse**](SensorReadingsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSingleSensorReadings

> SensorReading GetSingleSensorReadings(ctx, ibx, sensorId).Execute()

Retrieve Single sensor current value(s)



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
	ibx := "SV2" // string | IBX where the sensor is located.
	sensorId := "CH2.Environmental.MbusColo3Mod5.MOD35.C3TS03" // string | Id of sensor to read.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewEnvironmentAPIsApi.GetSingleSensorReadings(context.Background(), ibx, sensorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewEnvironmentAPIsApi.GetSingleSensorReadings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSingleSensorReadings`: SensorReading
	fmt.Fprintf(os.Stdout, "Response from `SmartViewEnvironmentAPIsApi.GetSingleSensorReadings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ibx** | **string** | IBX where the sensor is located. | 
**sensorId** | **string** | Id of sensor to read. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSingleSensorReadingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**SensorReading**](SensorReading.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTrendingEnvironmentData

> TrendingEnvironmentData GetTrendingEnvironmentData(ctx).AccountNo(accountNo).Ibx(ibx).DataPoint(dataPoint).LevelType(levelType).LevelValue(levelValue).Interval(interval).FromDate(fromDate).ToDate(toDate).Execute()

Retrieve trending environmental data



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/smartviewv2"
)

func main() {
	accountNo := "accountNo_example" // string | Customer Account Number
	ibx := "ibx_example" // string | IBX Code
	dataPoint := openapiclient.getTrendingEnvironmentData_dataPoint_parameter("temperature") // GetTrendingEnvironmentDataDataPointParameter | Data point
	levelType := openapiclient.getCurrentEnvironmentData_levelType_parameter("IBX") // GetCurrentEnvironmentDataLevelTypeParameter | Level Type
	levelValue := "CH2:1:06:ColoArea:1" // string | Identifies the location to query, depending on levelType. For IBX, the IBX code, for example CH2. For ZONE, the zone unique space ID, a colon-separated string in the format `<ibxCode>:<phase>:<floor>:<room>:<zone>`, for example CH2:1:06:ColoArea:1. The zone segment is optional; when there is no zone it is left empty and the trailing colon is kept, for example AM3:1:R1:RoofTop:.
	interval := openapiclient.getTrendingEnvironmentData_interval_parameter("reading") // GetTrendingEnvironmentDataIntervalParameter | Interval
	fromDate := time.Now() // time.Time | Date in long
	toDate := time.Now() // time.Time | Date in long

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewEnvironmentAPIsApi.GetTrendingEnvironmentData(context.Background()).AccountNo(accountNo).Ibx(ibx).DataPoint(dataPoint).LevelType(levelType).LevelValue(levelValue).Interval(interval).FromDate(fromDate).ToDate(toDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewEnvironmentAPIsApi.GetTrendingEnvironmentData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTrendingEnvironmentData`: TrendingEnvironmentData
	fmt.Fprintf(os.Stdout, "Response from `SmartViewEnvironmentAPIsApi.GetTrendingEnvironmentData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTrendingEnvironmentDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **dataPoint** | [**GetTrendingEnvironmentDataDataPointParameter**](GetTrendingEnvironmentDataDataPointParameter.md) | Data point | 
 **levelType** | [**GetCurrentEnvironmentDataLevelTypeParameter**](GetCurrentEnvironmentDataLevelTypeParameter.md) | Level Type | 
 **levelValue** | **string** | Identifies the location to query, depending on levelType. For IBX, the IBX code, for example CH2. For ZONE, the zone unique space ID, a colon-separated string in the format &#x60;&lt;ibxCode&gt;:&lt;phase&gt;:&lt;floor&gt;:&lt;room&gt;:&lt;zone&gt;&#x60;, for example CH2:1:06:ColoArea:1. The zone segment is optional; when there is no zone it is left empty and the trailing colon is kept, for example AM3:1:R1:RoofTop:. | 
 **interval** | [**GetTrendingEnvironmentDataIntervalParameter**](GetTrendingEnvironmentDataIntervalParameter.md) | Interval | 
 **fromDate** | **time.Time** | Date in long | 
 **toDate** | **time.Time** | Date in long | 

### Return type

[**TrendingEnvironmentData**](TrendingEnvironmentData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCurrentEnvironmentData

> EnvironmentDataResponse ListCurrentEnvironmentData(ctx).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).Execute()

Retrieve a list of environmental data



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
	levelType := openapiclient.getCurrentEnvironmentData_levelType_parameter("IBX") // GetCurrentEnvironmentDataLevelTypeParameter | Level Type

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartViewEnvironmentAPIsApi.ListCurrentEnvironmentData(context.Background()).AccountNo(accountNo).Ibx(ibx).LevelType(levelType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartViewEnvironmentAPIsApi.ListCurrentEnvironmentData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCurrentEnvironmentData`: EnvironmentDataResponse
	fmt.Fprintf(os.Stdout, "Response from `SmartViewEnvironmentAPIsApi.ListCurrentEnvironmentData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListCurrentEnvironmentDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNo** | **string** | Customer Account Number | 
 **ibx** | **string** | IBX Code | 
 **levelType** | [**GetCurrentEnvironmentDataLevelTypeParameter**](GetCurrentEnvironmentDataLevelTypeParameter.md) | Level Type | 

### Return type

[**EnvironmentDataResponse**](EnvironmentDataResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

