# \LoaRequestsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateRequest**](LoaRequestsApi.md#CreateRequest) | **Post** /diloa/v1/digitalLoas/loaRequests | Create Digital LOA Request



## CreateRequest

> CreateRequest(ctx).CreateLoaRequest(createLoaRequest).Execute()

Create Digital LOA Request



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
	createLoaRequest := *openapiclient.NewCreateLoaRequest("CH1", int32(2), *openapiclient.NewPartyContacts([]openapiclient.Contact{*openapiclient.NewContact(openapiclient.Contact_type("NOTIFICATION"), []openapiclient.ContactDetails{*openapiclient.NewContactDetails("kyle@mail.com", openapiclient.ContactDetails_type("EMAIL"))})}), *openapiclient.NewParty(openapiclient.Party_type("NEW_RELATIONSHIP"))) // CreateLoaRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.LoaRequestsApi.CreateRequest(context.Background()).CreateLoaRequest(createLoaRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaRequestsApi.CreateRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLoaRequest** | [**CreateLoaRequest**](CreateLoaRequest.md) |  | 

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

