# \ACLTemplateApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeviceACLTemplate**](ACLTemplateApi.md#CreateDeviceACLTemplate) | **Post** /ne/v1/aclTemplates | Create ACL Template
[**CreateDeviceTemplatesbyUuid**](ACLTemplateApi.md#CreateDeviceTemplatesbyUuid) | **Post** /ne/v1/devices/{virtualDeviceUuid}/acl | Add ACL to Virtual Device
[**DeleteDeviceACLByUuid**](ACLTemplateApi.md#DeleteDeviceACLByUuid) | **Delete** /ne/v1/aclTemplates/{uuid} | Delete ACL template By Uuid
[**GetDeviceACLTemplate**](ACLTemplateApi.md#GetDeviceACLTemplate) | **Get** /ne/v1/aclTemplates | Get ACL Templates
[**GetDeviceTemplateByUuid**](ACLTemplateApi.md#GetDeviceTemplateByUuid) | **Get** /ne/v1/aclTemplates/{uuid} | Get ACL Template By Uuid
[**GetDeviceTemplatesByUuid**](ACLTemplateApi.md#GetDeviceTemplatesByUuid) | **Get** /ne/v1/devices/{virtualDeviceUuid}/acl | Get ACL of Virtual Device
[**UpdateDeviceACLTemplateByUuid**](ACLTemplateApi.md#UpdateDeviceACLTemplateByUuid) | **Put** /ne/v1/aclTemplates/{uuid} | Update ACL Template By Uuid
[**UpdateDeviceTemplatesbyUuid**](ACLTemplateApi.md#UpdateDeviceTemplatesbyUuid) | **Patch** /ne/v1/devices/{virtualDeviceUuid}/acl | Update ACL of Virtual Device



## CreateDeviceACLTemplate

> VirtualDeviceCreateResponse CreateDeviceACLTemplate(ctx).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()

Create ACL Template



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	aclTemplateRequest := *openapiclient.NewDeviceACLTemplateRequest("Test Template", "Test Template Description", []openapiclient.InboundRules{*openapiclient.NewInboundRules()}) // DeviceACLTemplateRequest | Creates an ACL template.
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | A reseller creating an ACL template for a customer can pass the accountUcmId of the customer. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ACLTemplateApi.CreateDeviceACLTemplate(context.Background()).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.CreateDeviceACLTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeviceACLTemplate`: VirtualDeviceCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `ACLTemplateApi.CreateDeviceACLTemplate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceACLTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aclTemplateRequest** | [**DeviceACLTemplateRequest**](DeviceACLTemplateRequest.md) | Creates an ACL template. | 
 **accountUcmId** | **string** | A reseller creating an ACL template for a customer can pass the accountUcmId of the customer. | 

### Return type

[**VirtualDeviceCreateResponse**](VirtualDeviceCreateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDeviceTemplatesbyUuid

> CreateDeviceTemplatesbyUuid(ctx, virtualDeviceUuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()

Add ACL to Virtual Device



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device.
	aclTemplateRequest := *openapiclient.NewUpdateDeviceACLTemplateRequest([]openapiclient.ACLDetails{*openapiclient.NewACLDetails()}) // UpdateDeviceACLTemplateRequest | Update the ACL of a device.
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | A reseller updating a device ACL template for a customer can pass the accountUcmId of the customer. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ACLTemplateApi.CreateDeviceTemplatesbyUuid(context.Background(), virtualDeviceUuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.CreateDeviceTemplatesbyUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique Id of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeviceTemplatesbyUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **aclTemplateRequest** | [**UpdateDeviceACLTemplateRequest**](UpdateDeviceACLTemplateRequest.md) | Update the ACL of a device. | 
 **accountUcmId** | **string** | A reseller updating a device ACL template for a customer can pass the accountUcmId of the customer. | 

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


## DeleteDeviceACLByUuid

> DeleteDeviceACLByUuid(ctx, uuid).AccountUcmId(accountUcmId).Execute()

Delete ACL template By Uuid



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	uuid := "be7ef79e-31e7-4769-be5b-e192496f48aa" // string | Unique ID of an ACL template
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | A reseller deleting an ACL template for a customer must pass the accountUcmId of the customer. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ACLTemplateApi.DeleteDeviceACLByUuid(context.Background(), uuid).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.DeleteDeviceACLByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of an ACL template | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDeviceACLByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountUcmId** | **string** | A reseller deleting an ACL template for a customer must pass the accountUcmId of the customer. | 

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


## GetDeviceACLTemplate

> GetACLTemplateResponse GetDeviceACLTemplate(ctx).Offset(offset).Limit(limit).AccountUcmId(accountUcmId).ProjectIds(projectIds).Execute()

Get ACL Templates



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | Unique ID of the account. A reseller querying for the ACLs of a customer should input the accountUcmId of the customer. (optional)
	projectIds := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectIds are different from default projectIds, must pass a projectIds parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ACLTemplateApi.GetDeviceACLTemplate(context.Background()).Offset(offset).Limit(limit).AccountUcmId(accountUcmId).ProjectIds(projectIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.GetDeviceACLTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceACLTemplate`: GetACLTemplateResponse
	fmt.Fprintf(os.Stdout, "Response from `ACLTemplateApi.GetDeviceACLTemplate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceACLTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]
 **accountUcmId** | **string** | Unique ID of the account. A reseller querying for the ACLs of a customer should input the accountUcmId of the customer. | 
 **projectIds** | **string** | If projectIds are different from default projectIds, must pass a projectIds parameter | 

### Return type

[**GetACLTemplateResponse**](GetACLTemplateResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceTemplateByUuid

> ACLTemplateDetailsResponse GetDeviceTemplateByUuid(ctx, uuid).Execute()

Get ACL Template By Uuid



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	uuid := "be7ef79e-31e7-4769-be5b-e192496f48aa" // string | Unique Id of an ACL template

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ACLTemplateApi.GetDeviceTemplateByUuid(context.Background(), uuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.GetDeviceTemplateByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceTemplateByUuid`: ACLTemplateDetailsResponse
	fmt.Fprintf(os.Stdout, "Response from `ACLTemplateApi.GetDeviceTemplateByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of an ACL template | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceTemplateByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ACLTemplateDetailsResponse**](ACLTemplateDetailsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeviceTemplatesByUuid

> InitialDeviceACLResponse GetDeviceTemplatesByUuid(ctx, virtualDeviceUuid).Execute()

Get ACL of Virtual Device



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ACLTemplateApi.GetDeviceTemplatesByUuid(context.Background(), virtualDeviceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.GetDeviceTemplatesByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeviceTemplatesByUuid`: InitialDeviceACLResponse
	fmt.Fprintf(os.Stdout, "Response from `ACLTemplateApi.GetDeviceTemplatesByUuid`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique Id of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeviceTemplatesByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**InitialDeviceACLResponse**](InitialDeviceACLResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeviceACLTemplateByUuid

> UpdateDeviceACLTemplateByUuid(ctx, uuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()

Update ACL Template By Uuid



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	uuid := "be7ef79e-31e7-4769-be5b-e192496f48aa" // string | Unique ID of an ACL template
	aclTemplateRequest := *openapiclient.NewDeviceACLTemplateRequest("Test Template", "Test Template Description", []openapiclient.InboundRules{*openapiclient.NewInboundRules()}) // DeviceACLTemplateRequest | Update an ACL template.
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | A reseller updating an ACL template for a customer must pass the accountUcmId of the customer. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ACLTemplateApi.UpdateDeviceACLTemplateByUuid(context.Background(), uuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.UpdateDeviceACLTemplateByUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique ID of an ACL template | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceACLTemplateByUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **aclTemplateRequest** | [**DeviceACLTemplateRequest**](DeviceACLTemplateRequest.md) | Update an ACL template. | 
 **accountUcmId** | **string** | A reseller updating an ACL template for a customer must pass the accountUcmId of the customer. | 

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


## UpdateDeviceTemplatesbyUuid

> UpdateDeviceTemplatesbyUuid(ctx, virtualDeviceUuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()

Update ACL of Virtual Device



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/networkedgev1"
)

func main() {
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device.
	aclTemplateRequest := *openapiclient.NewUpdateDeviceACLTemplateRequest([]openapiclient.ACLDetails{*openapiclient.NewACLDetails()}) // UpdateDeviceACLTemplateRequest | Update the ACL of a device.
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | A reseller updating a device ACL template for a customer can pass the accountUcmId of the customer. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ACLTemplateApi.UpdateDeviceTemplatesbyUuid(context.Background(), virtualDeviceUuid).AclTemplateRequest(aclTemplateRequest).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ACLTemplateApi.UpdateDeviceTemplatesbyUuid``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**virtualDeviceUuid** | **string** | Unique Id of a virtual device. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeviceTemplatesbyUuidRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **aclTemplateRequest** | [**UpdateDeviceACLTemplateRequest**](UpdateDeviceACLTemplateRequest.md) | Update the ACL of a device. | 
 **accountUcmId** | **string** | A reseller updating a device ACL template for a customer can pass the accountUcmId of the customer. | 

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

