# \ProjectApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAllProjects**](ProjectApi.md#GetAllProjects) | **Get** /resourceManager/v2/projects | To retrieve projects of a root organization



## GetAllProjects

> ProjectV2PaginatedResponse GetAllProjects(ctx).IncludePermissions(includePermissions).IncludeInbox(includeInbox).Limit(limit).Offset(offset).Execute()

To retrieve projects of a root organization



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/getprojectsv2"
)

func main() {
	includePermissions := false // bool | whether to include the user permissions on the project resource (optional) (default to false)
	includeInbox := false // bool | Whether to include the projects with inbox classification or not (optional) (default to false)
	limit := int32(50) // int32 | Limits the number of returned results (optional) (default to 20)
	offset := int32(0) // int32 | Offset from which start returned results (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectApi.GetAllProjects(context.Background()).IncludePermissions(includePermissions).IncludeInbox(includeInbox).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectApi.GetAllProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllProjects`: ProjectV2PaginatedResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectApi.GetAllProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includePermissions** | **bool** | whether to include the user permissions on the project resource | [default to false]
 **includeInbox** | **bool** | Whether to include the projects with inbox classification or not | [default to false]
 **limit** | **int32** | Limits the number of returned results | [default to 20]
 **offset** | **int32** | Offset from which start returned results | [default to 0]

### Return type

[**ProjectV2PaginatedResponse**](ProjectV2PaginatedResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

