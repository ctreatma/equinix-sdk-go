# \StreamingSubscriptionAPIApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateSubscription**](StreamingSubscriptionAPIApi.md#CreateSubscription) | **Post** /smartview/v2/streaming/subscriptions | Create subscription endpoint
[**DeleteSubscriptionById**](StreamingSubscriptionAPIApi.md#DeleteSubscriptionById) | **Delete** /smartview/v2/streaming/subscriptions/{id} | Delete subscription
[**GetAllSubscriptions**](StreamingSubscriptionAPIApi.md#GetAllSubscriptions) | **Get** /smartview/v2/streaming/subscriptions | Retrieve all subscriptions
[**GetCertificate**](StreamingSubscriptionAPIApi.md#GetCertificate) | **Get** /smartview/v2/streaming/subscriptions/certificate | Get subscription certificate endpoint
[**GetSubscriptionById**](StreamingSubscriptionAPIApi.md#GetSubscriptionById) | **Get** /smartview/v2/streaming/subscriptions/{id} | Retrieve subscription by ID
[**GetSubscriptionData**](StreamingSubscriptionAPIApi.md#GetSubscriptionData) | **Get** /smartview/v2/streaming/subscriptionData/{subscriptionId} | Retrieve subscription data via REST
[**UpdateSubscription**](StreamingSubscriptionAPIApi.md#UpdateSubscription) | **Put** /smartview/v2/streaming/subscriptions/{id} | Update subscription



## CreateSubscription

> CreateSubscription(ctx).SubscriptionRequest(subscriptionRequest).Execute()

Create subscription endpoint



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
	subscriptionRequest := *openapiclient.NewSubscriptionRequest() // SubscriptionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.StreamingSubscriptionAPIApi.CreateSubscription(context.Background()).SubscriptionRequest(subscriptionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.CreateSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateSubscriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subscriptionRequest** | [**SubscriptionRequest**](SubscriptionRequest.md) |  | 

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


## DeleteSubscriptionById

> DeleteSubscriptionById(ctx, id).Execute()

Delete subscription



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
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.StreamingSubscriptionAPIApi.DeleteSubscriptionById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.DeleteSubscriptionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteSubscriptionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllSubscriptions

> []SubscriptionResponse GetAllSubscriptions(ctx).Execute()

Retrieve all subscriptions



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StreamingSubscriptionAPIApi.GetAllSubscriptions(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.GetAllSubscriptions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllSubscriptions`: []SubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `StreamingSubscriptionAPIApi.GetAllSubscriptions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAllSubscriptionsRequest struct via the builder pattern


### Return type

[**[]SubscriptionResponse**](SubscriptionResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCertificate

> SubscriptionCertificateResponse GetCertificate(ctx).ChannelType(channelType).Execute()

Get subscription certificate endpoint



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
	channelType := openapiclient.getCertificate_channelType_parameter("AWS_IOT_CORE") // GetCertificateChannelTypeParameter | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StreamingSubscriptionAPIApi.GetCertificate(context.Background()).ChannelType(channelType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.GetCertificate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCertificate`: SubscriptionCertificateResponse
	fmt.Fprintf(os.Stdout, "Response from `StreamingSubscriptionAPIApi.GetCertificate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCertificateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **channelType** | [**GetCertificateChannelTypeParameter**](GetCertificateChannelTypeParameter.md) |  | 

### Return type

[**SubscriptionCertificateResponse**](SubscriptionCertificateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSubscriptionById

> SubscriptionResponse GetSubscriptionById(ctx, id).Execute()

Retrieve subscription by ID



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
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StreamingSubscriptionAPIApi.GetSubscriptionById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.GetSubscriptionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionById`: SubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `StreamingSubscriptionAPIApi.GetSubscriptionById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SubscriptionResponse**](SubscriptionResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSubscriptionData

> SubscriptionData GetSubscriptionData(ctx, subscriptionId).Ibxs(ibxs).MessageTypes(messageTypes).StreamIds(streamIds).Offset(offset).Limit(limit).Execute()

Retrieve subscription data via REST



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
	subscriptionId := "subscriptionId_example" // string | Subscription ID
	ibxs := []string{"Inner_example"} // []string | Filter, set of IBXs (optional)
	messageTypes := []openapiclient.GetSubscriptionDataMessageTypesParameterInner{openapiclient.getSubscriptionData_messageTypes_parameter_inner("ALARM")} // []GetSubscriptionDataMessageTypesParameterInner | Filter, set of message types (optional)
	streamIds := []string{"Inner_example"} // []string | Filter, set of stream IDs (optional)
	offset := int32(56) // int32 | Pagination, offset of the first item (optional) (default to 0)
	limit := int32(56) // int32 | Pagination, limit of items returned (optional) (default to 250)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StreamingSubscriptionAPIApi.GetSubscriptionData(context.Background(), subscriptionId).Ibxs(ibxs).MessageTypes(messageTypes).StreamIds(streamIds).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.GetSubscriptionData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionData`: SubscriptionData
	fmt.Fprintf(os.Stdout, "Response from `StreamingSubscriptionAPIApi.GetSubscriptionData`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**subscriptionId** | **string** | Subscription ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ibxs** | **[]string** | Filter, set of IBXs | 
 **messageTypes** | [**[]GetSubscriptionDataMessageTypesParameterInner**](GetSubscriptionDataMessageTypesParameterInner.md) | Filter, set of message types | 
 **streamIds** | **[]string** | Filter, set of stream IDs | 
 **offset** | **int32** | Pagination, offset of the first item | [default to 0]
 **limit** | **int32** | Pagination, limit of items returned | [default to 250]

### Return type

[**SubscriptionData**](SubscriptionData.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateSubscription

> UpdateSubscription(ctx, id).SubscriptionRequest(subscriptionRequest).Execute()

Update subscription



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
	id := "id_example" // string | 
	subscriptionRequest := *openapiclient.NewSubscriptionRequest() // SubscriptionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.StreamingSubscriptionAPIApi.UpdateSubscription(context.Background(), id).SubscriptionRequest(subscriptionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StreamingSubscriptionAPIApi.UpdateSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateSubscriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **subscriptionRequest** | [**SubscriptionRequest**](SubscriptionRequest.md) |  | 

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

