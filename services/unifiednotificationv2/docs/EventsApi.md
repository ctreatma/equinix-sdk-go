# \EventsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetNotifications**](EventsApi.md#GetNotifications) | **Post** /notifications/v2/events/findAll | Search notification



## GetNotifications

> EventSearchResponse GetNotifications(ctx).EventSearchRequest(eventSearchRequest).Execute()

Search notification



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/unifiednotificationv2"
)

func main() {
	eventSearchRequest := *openapiclient.NewEventSearchRequest() // EventSearchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventsApi.GetNotifications(context.Background()).EventSearchRequest(eventSearchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventsApi.GetNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNotifications`: EventSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `EventsApi.GetNotifications`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **eventSearchRequest** | [**EventSearchRequest**](EventSearchRequest.md) |  | 

### Return type

[**EventSearchResponse**](EventSearchResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

