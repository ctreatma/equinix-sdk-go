# \LoaChangesApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FindChangeByUuid**](LoaChangesApi.md#FindChangeByUuid) | **Get** /diloa/v1/digitalLoas/{uuid}/changes/{changeUuid} | Get specified Digital LOA change
[**FindChangesByLoaUuid**](LoaChangesApi.md#FindChangesByLoaUuid) | **Get** /diloa/v1/digitalLoas/{uuid}/changes | Get specified Digital LOA changes



## FindChangeByUuid

> LoaChange FindChangeByUuid(ctx, uuid, changeUuid).Execute()

Get specified Digital LOA change



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/diloav1"
)

func main() {
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA unique identifier.
	changeUuid := "4c7d67e2-bbf2-4407-bcff-05a385ed0d4e" // string | Digital LOA change unique identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaChangesApi.FindChangeByUuid(context.Background(), uuid, changeUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaChangesApi.FindChangeByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindChangeByUuid`: LoaChange
	fmt.Fprintf(os.Stdout, "Response from `LoaChangesApi.FindChangeByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA unique identifier. | 
**changeUuid** | **string** | Digital LOA change unique identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiFindChangeByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**LoaChange**](LoaChange.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FindChangesByLoaUuid

> []LoaChange FindChangesByLoaUuid(ctx, uuid).Execute()

Get specified Digital LOA changes



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/diloav1"
)

func main() {
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA unique identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaChangesApi.FindChangesByLoaUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaChangesApi.FindChangesByLoaUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindChangesByLoaUuid`: []LoaChange
	fmt.Fprintf(os.Stdout, "Response from `LoaChangesApi.FindChangesByLoaUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA unique identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiFindChangesByLoaUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]LoaChange**](LoaChange.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

