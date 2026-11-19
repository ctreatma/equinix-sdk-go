# \LoaApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelByUuid**](LoaApi.md#CancelByUuid) | **Delete** /diloa/v1/digitalLoas/{uuid} | Delete Digital LOA document
[**Create**](LoaApi.md#Create) | **Post** /diloa/v1/digitalLoas | Create Digital LOA document
[**FindByUuid**](LoaApi.md#FindByUuid) | **Get** /diloa/v1/digitalLoas/{uuid} | Get specified Digital LOA document.
[**PatchByUuid**](LoaApi.md#PatchByUuid) | **Patch** /diloa/v1/digitalLoas/{uuid} | Modify a Digital LOA document
[**PerformAction**](LoaApi.md#PerformAction) | **Post** /diloa/v1/digitalLoas/{uuid}/actions | Perform action on Digital LOA document.
[**Search**](LoaApi.md#Search) | **Post** /diloa/v1/digitalLoas/search | Retrieve Digital LOA Documents



## CancelByUuid

> CancelByUuid(ctx, uuid).Execute()

Delete Digital LOA document



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
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA document identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.LoaApi.CancelByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.CancelByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA document identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelByUuidRequest struct via the builder pattern


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


## Create

> LoaBasic Create(ctx).CreateLoa(createLoa).Execute()

Create Digital LOA document



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
	createLoa := *openapiclient.NewCreateLoa([]openapiclient.CreateProduct{*openapiclient.NewCreateProduct(openapiclient.CreateProduct_type("CROSS_CONNECT"), *openapiclient.NewCreateCrossConnect("MULTI_MODE_FIBER", "50_MICRON_MULTI_MODE_FIBER_OM3", "100_GIG_ETHERNET", *openapiclient.NewCreatePatchPanelPort("ST", "CP:0218:0102:13008148", int32(12))))}, *openapiclient.NewParty(openapiclient.Party_type("NEW_RELATIONSHIP")), *openapiclient.NewPartyContacts([]openapiclient.Contact{*openapiclient.NewContact(openapiclient.Contact_type("NOTIFICATION"), []openapiclient.ContactDetails{*openapiclient.NewContactDetails("kyle@mail.com", openapiclient.ContactDetails_type("EMAIL"))})})) // CreateLoa | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaApi.Create(context.Background()).CreateLoa(createLoa).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.Create``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Create`: LoaBasic
	fmt.Fprintf(os.Stdout, "Response from `LoaApi.Create`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLoa** | [**CreateLoa**](CreateLoa.md) |  | 

### Return type

[**LoaBasic**](LoaBasic.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FindByUuid

> Loa FindByUuid(ctx, uuid).Execute()

Get specified Digital LOA document.



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
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA document identifier.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaApi.FindByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.FindByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindByUuid`: Loa
	fmt.Fprintf(os.Stdout, "Response from `LoaApi.FindByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA document identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiFindByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Loa**](Loa.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchByUuid

> Loa PatchByUuid(ctx, uuid).PatchDocument(patchDocument).Execute()

Modify a Digital LOA document



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
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA document identifier.
	patchDocument := []openapiclient.PatchDocument{*openapiclient.NewPatchDocument(openapiclient.PatchDocument_op("add"), openapiclient.PatchDocument_path("/state"))} // []PatchDocument | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaApi.PatchByUuid(context.Background(), uuid).PatchDocument(patchDocument).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.PatchByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchByUuid`: Loa
	fmt.Fprintf(os.Stdout, "Response from `LoaApi.PatchByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA document identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchDocument** | [**[]PatchDocument**](PatchDocument.md) |  | 

### Return type

[**Loa**](Loa.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PerformAction

> Loa PerformAction(ctx, uuid).UserAction(userAction).Execute()

Perform action on Digital LOA document.



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
	uuid := "079dc798-05e8-11ed-b939-0242ac120002" // string | Digital LOA document identifier.
	userAction := *openapiclient.NewUserAction(openapiclient.UserAction_type("ACCEPT")) // UserAction | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaApi.PerformAction(context.Background(), uuid).UserAction(userAction).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.PerformAction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PerformAction`: Loa
	fmt.Fprintf(os.Stdout, "Response from `LoaApi.PerformAction`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Digital LOA document identifier. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPerformActionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userAction** | [**UserAction**](UserAction.md) |  | 

### Return type

[**Loa**](Loa.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Search

> PageableAndSortableLoa Search(ctx).LoaSearch(loaSearch).Offset(offset).Limit(limit).Sort(sort).Execute()

Retrieve Digital LOA Documents



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
	loaSearch := *openapiclient.NewLoaSearch(*openapiclient.NewLoaSearchItem([]openapiclient.OrExpressionItem{openapiclient.OrExpressionItem{Expression: openapiclient.NewExpression()}})) // LoaSearch | 
	offset := int32(0) // int32 | Index of the first item returned in the response. (optional) (default to 0)
	limit := int32(20) // int32 | Maximum number of items returned per page. (optional) (default to 20)
	sort := []openapiclient.SearchSortParameterInner{openapiclient.search_sort_parameter_inner("/changeLog/createdDateTime")} // []SearchSortParameterInner | Search results sorting settings:   * `/` - Ascending, i.e. '/expiryDateTime'   * `-/` - Descending, i.e. '-/expiryDateTime'  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LoaApi.Search(context.Background()).LoaSearch(loaSearch).Offset(offset).Limit(limit).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LoaApi.Search``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Search`: PageableAndSortableLoa
	fmt.Fprintf(os.Stdout, "Response from `LoaApi.Search`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loaSearch** | [**LoaSearch**](LoaSearch.md) |  | 
 **offset** | **int32** | Index of the first item returned in the response. | [default to 0]
 **limit** | **int32** | Maximum number of items returned per page. | [default to 20]
 **sort** | [**[]SearchSortParameterInner**](SearchSortParameterInner.md) | Search results sorting settings:   * &#x60;/&#x60; - Ascending, i.e. &#39;/expiryDateTime&#39;   * &#x60;-/&#x60; - Descending, i.e. &#39;-/expiryDateTime&#39;  | 

### Return type

[**PageableAndSortableLoa**](PageableAndSortableLoa.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

