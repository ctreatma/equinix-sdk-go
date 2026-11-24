# \PrivateBetaAccessApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePrivateBetaAccessRequest**](PrivateBetaAccessApi.md#CreatePrivateBetaAccessRequest) | **Post** /diloa/v1/privateBetaAccess | Create private beta access request
[**IsPrivateBetaAllowed**](PrivateBetaAccessApi.md#IsPrivateBetaAllowed) | **Get** /diloa/v1/privateBetaAccess | Check private beta permission



## CreatePrivateBetaAccessRequest

> CreatePrivateBetaAccessRequest(ctx).PrivateBetaAccessRequest(privateBetaAccessRequest).Execute()

Create private beta access request



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
	privateBetaAccessRequest := *openapiclient.NewPrivateBetaAccessRequest("kyle@mail.com", "XYZ Inc.") // PrivateBetaAccessRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PrivateBetaAccessApi.CreatePrivateBetaAccessRequest(context.Background()).PrivateBetaAccessRequest(privateBetaAccessRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PrivateBetaAccessApi.CreatePrivateBetaAccessRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePrivateBetaAccessRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **privateBetaAccessRequest** | [**PrivateBetaAccessRequest**](PrivateBetaAccessRequest.md) |  | 

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


## IsPrivateBetaAllowed

> PrivateBetaPermission IsPrivateBetaAllowed(ctx).Execute()

Check private beta permission



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PrivateBetaAccessApi.IsPrivateBetaAllowed(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PrivateBetaAccessApi.IsPrivateBetaAllowed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IsPrivateBetaAllowed`: PrivateBetaPermission
	fmt.Fprintf(os.Stdout, "Response from `PrivateBetaAccessApi.IsPrivateBetaAllowed`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiIsPrivateBetaAllowedRequest struct via the builder pattern


### Return type

[**PrivateBetaPermission**](PrivateBetaPermission.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

