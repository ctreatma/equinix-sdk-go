# \PowerEventsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePowerAlertConfiguration**](PowerEventsApi.md#CreatePowerAlertConfiguration) | **Post** /dcim/v3/powerEvents/configurations | Create a power alert configuration
[**DeleteAlertConfiguration**](PowerEventsApi.md#DeleteAlertConfiguration) | **Delete** /dcim/v3/powerEvents/configurations/{alertConfigurationUid} | Delete a power alert configuration
[**GetPowerEvents**](PowerEventsApi.md#GetPowerEvents) | **Get** /dcim/v3/powerEvents/search | Search power events
[**PauseAlertConfiguration**](PowerEventsApi.md#PauseAlertConfiguration) | **Put** /dcim/v3/powerEvents/configurations/{alertConfigurationUid}/pause | Pause a power alert configuration
[**ResumeAlertConfiguration**](PowerEventsApi.md#ResumeAlertConfiguration) | **Put** /dcim/v3/powerEvents/configurations/{alertConfigurationUid}/resume | Resume a power alert configuration
[**SearchAlertConfigurations**](PowerEventsApi.md#SearchAlertConfigurations) | **Get** /dcim/v3/powerEvents/configurations/search | Search power alert configurations
[**UpdatePowerAlertConfiguration**](PowerEventsApi.md#UpdatePowerAlertConfiguration) | **Put** /dcim/v3/powerEvents/configurations | Update a power alert configuration



## CreatePowerAlertConfiguration

> CreateAlertConfigurationCommandResponse CreatePowerAlertConfiguration(ctx).CreateAlertConfigurationCommand(createAlertConfigurationCommand).Execute()

Create a power alert configuration



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
	createAlertConfigurationCommand := *openapiclient.NewCreateAlertConfigurationCommand("123456", "SV5", "POWER", *openapiclient.NewPowerAlertCondition(), []openapiclient.PowerAlertRecipient{*openapiclient.NewPowerAlertRecipient()}) // CreateAlertConfigurationCommand | Request body for creating a power alert configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PowerEventsApi.CreatePowerAlertConfiguration(context.Background()).CreateAlertConfigurationCommand(createAlertConfigurationCommand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.CreatePowerAlertConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePowerAlertConfiguration`: CreateAlertConfigurationCommandResponse
	fmt.Fprintf(os.Stdout, "Response from `PowerEventsApi.CreatePowerAlertConfiguration`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePowerAlertConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAlertConfigurationCommand** | [**CreateAlertConfigurationCommand**](CreateAlertConfigurationCommand.md) | Request body for creating a power alert configuration | 

### Return type

[**CreateAlertConfigurationCommandResponse**](CreateAlertConfigurationCommandResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAlertConfiguration

> DeleteAlertConfiguration(ctx, alertConfigurationUid).Execute()

Delete a power alert configuration



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
	alertConfigurationUid := "9756a585-c3c1-4648-b2e1-7d8804912098" // string | Unique identifier (UUID) of the power alert configuration to delete

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PowerEventsApi.DeleteAlertConfiguration(context.Background(), alertConfigurationUid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.DeleteAlertConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertConfigurationUid** | **string** | Unique identifier (UUID) of the power alert configuration to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAlertConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPowerEvents

> PowerEventsPaginatedResponse GetPowerEvents(ctx).Limit(limit).Offset(offset).Ibx(ibx).Status(status).EdgeCollectedOn(edgeCollectedOn).Execute()

Search power events



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
	limit := int32(100) // int32 | Number of records to retrieve per request
	offset := int32(0) // int32 | Record number to start retrieval from (0..N)
	ibx := []string{"Inner_example"} // []string | List of IBX codes to filter power events (comma-separated) (optional)
	status := []openapiclient.GetPowerEventsStatusParameterInner{openapiclient.getPowerEvents_status_parameter_inner("ACTIVE")} // []GetPowerEventsStatusParameterInner | List of statuses to filter power events (comma-separated). Possible values - ACTIVE, INACTIVE (optional)
	edgeCollectedOn := "2024-01-01T00:00:00.000Z" // string | Date filter to retrieve power events collected after a specific date (ISO 8601 format) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PowerEventsApi.GetPowerEvents(context.Background()).Limit(limit).Offset(offset).Ibx(ibx).Status(status).EdgeCollectedOn(edgeCollectedOn).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.GetPowerEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPowerEvents`: PowerEventsPaginatedResponse
	fmt.Fprintf(os.Stdout, "Response from `PowerEventsApi.GetPowerEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPowerEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Number of records to retrieve per request | 
 **offset** | **int32** | Record number to start retrieval from (0..N) | 
 **ibx** | **[]string** | List of IBX codes to filter power events (comma-separated) | 
 **status** | [**[]GetPowerEventsStatusParameterInner**](GetPowerEventsStatusParameterInner.md) | List of statuses to filter power events (comma-separated). Possible values - ACTIVE, INACTIVE | 
 **edgeCollectedOn** | **string** | Date filter to retrieve power events collected after a specific date (ISO 8601 format) | 

### Return type

[**PowerEventsPaginatedResponse**](PowerEventsPaginatedResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PauseAlertConfiguration

> PauseAlertConfiguration(ctx, alertConfigurationUid).Execute()

Pause a power alert configuration



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
	alertConfigurationUid := "9756a585-c3c1-4648-b2e1-7d8804912098" // string | Unique identifier (UUID) of the power alert configuration to pause

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PowerEventsApi.PauseAlertConfiguration(context.Background(), alertConfigurationUid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.PauseAlertConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertConfigurationUid** | **string** | Unique identifier (UUID) of the power alert configuration to pause | 

### Other Parameters

Other parameters are passed through a pointer to a apiPauseAlertConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResumeAlertConfiguration

> ResumeAlertConfiguration(ctx, alertConfigurationUid).Execute()

Resume a power alert configuration



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
	alertConfigurationUid := "9756a585-c3c1-4648-b2e1-7d8804912098" // string | Unique identifier (UUID) of the power alert configuration to resume

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PowerEventsApi.ResumeAlertConfiguration(context.Background(), alertConfigurationUid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.ResumeAlertConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertConfigurationUid** | **string** | Unique identifier (UUID) of the power alert configuration to resume | 

### Other Parameters

Other parameters are passed through a pointer to a apiResumeAlertConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchAlertConfigurations

> AlertPaginatedResponse SearchAlertConfigurations(ctx).Limit(limit).Offset(offset).Ibx(ibx).State(state).Execute()

Search power alert configurations



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
	limit := int32(100) // int32 | Number of records to retrieve per request
	offset := int32(0) // int32 | Record number to start retrieval from (0..N)
	ibx := []string{"Inner_example"} // []string | List of IBX codes to filter configurations (comma-separated) (optional)
	state := []openapiclient.SearchAlertConfigurationsStateParameterInner{openapiclient.searchAlertConfigurations_state_parameter_inner("ACTIVE")} // []SearchAlertConfigurationsStateParameterInner | List of states to filter configurations (comma-separated). Possible values - ACTIVE, PAUSED, DELETED (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PowerEventsApi.SearchAlertConfigurations(context.Background()).Limit(limit).Offset(offset).Ibx(ibx).State(state).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.SearchAlertConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAlertConfigurations`: AlertPaginatedResponse
	fmt.Fprintf(os.Stdout, "Response from `PowerEventsApi.SearchAlertConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAlertConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Number of records to retrieve per request | 
 **offset** | **int32** | Record number to start retrieval from (0..N) | 
 **ibx** | **[]string** | List of IBX codes to filter configurations (comma-separated) | 
 **state** | [**[]SearchAlertConfigurationsStateParameterInner**](SearchAlertConfigurationsStateParameterInner.md) | List of states to filter configurations (comma-separated). Possible values - ACTIVE, PAUSED, DELETED | 

### Return type

[**AlertPaginatedResponse**](AlertPaginatedResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePowerAlertConfiguration

> UpdatePowerAlertConfiguration(ctx).UpdateAlertConfigurationCommand(updateAlertConfigurationCommand).Execute()

Update a power alert configuration



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
	updateAlertConfigurationCommand := *openapiclient.NewUpdateAlertConfigurationCommand("9756a585-c3c1-4648-b2e1-7d8804912098") // UpdateAlertConfigurationCommand | Request body for updating a power alert configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PowerEventsApi.UpdatePowerAlertConfiguration(context.Background()).UpdateAlertConfigurationCommand(updateAlertConfigurationCommand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PowerEventsApi.UpdatePowerAlertConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePowerAlertConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateAlertConfigurationCommand** | [**UpdateAlertConfigurationCommand**](UpdateAlertConfigurationCommand.md) | Request body for updating a power alert configuration | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

