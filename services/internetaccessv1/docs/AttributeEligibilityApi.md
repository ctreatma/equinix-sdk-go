# \AttributeEligibilityApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCustomerRouteConfigurations**](AttributeEligibilityApi.md#GetCustomerRouteConfigurations) | **Get** /internetAccess/v1/customerRouteConfigurations | Customer Route Configuration API Endpoint
[**GetDedicatedBandwidthConfigurations**](AttributeEligibilityApi.md#GetDedicatedBandwidthConfigurations) | **Get** /internetAccess/v1/dedicatedBandwidthConfigurations | Dedicated Bandwidth Attribute Eligibility API Endpoint
[**GetDedicatedPortDefaultConfigurationsPage**](AttributeEligibilityApi.md#GetDedicatedPortDefaultConfigurationsPage) | **Get** /internetAccess/v1/dedicatedPortDefaultConfigurations | Dedicated port default configurations API Endpoint
[**GetPortConfigurations**](AttributeEligibilityApi.md#GetPortConfigurations) | **Get** /internetAccess/v1/portConfigurations | Dedicated Port Attribute Eligibility API Endpoint
[**GetRoutingConfigurations**](AttributeEligibilityApi.md#GetRoutingConfigurations) | **Get** /internetAccess/v1/routingProtocolConfigurations | Routing Protocol Attribute Eligibility API Endpoint
[**GetVirtualBandwidthConfigurations**](AttributeEligibilityApi.md#GetVirtualBandwidthConfigurations) | **Get** /internetAccess/v1/virtualBandwidthConfigurations | Virtual Bandwidth Attribute Eligibility API Endpoint
[**GetVirtualConnectionDefaultConfigurations**](AttributeEligibilityApi.md#GetVirtualConnectionDefaultConfigurations) | **Get** /internetAccess/v1/virtualConnectionDefaultConfigurations | Virtual Connection Default Configuration Attribute Eligibility API Endpoint



## GetCustomerRouteConfigurations

> CustomerRouteConfigurationPage GetCustomerRouteConfigurations(ctx).UseCase(useCase).Offset(offset).Limit(limit).Type_(type_).RoutingProtocolType(routingProtocolType).Execute()

Customer Route Configuration API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	useCase := openapiclient.getRoutingConfigurations_useCase_parameter("MAIN") // GetRoutingConfigurationsUseCaseParameter | Use case
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)
	type_ := openapiclient.ProductCatalogRedundancy("SINGLE_PORT") // ProductCatalogRedundancy | Type of Equinix Internet Access Service (optional)
	routingProtocolType := openapiclient.getCustomerRouteConfigurations_routingProtocol_type_parameter("BGP") // GetCustomerRouteConfigurationsRoutingProtocolTypeParameter | Type of Routing Protocol (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetCustomerRouteConfigurations(context.Background()).UseCase(useCase).Offset(offset).Limit(limit).Type_(type_).RoutingProtocolType(routingProtocolType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetCustomerRouteConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCustomerRouteConfigurations`: CustomerRouteConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetCustomerRouteConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCustomerRouteConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **useCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) | Use case | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]
 **type_** | [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) | Type of Equinix Internet Access Service | 
 **routingProtocolType** | [**GetCustomerRouteConfigurationsRoutingProtocolTypeParameter**](GetCustomerRouteConfigurationsRoutingProtocolTypeParameter.md) | Type of Routing Protocol | 

### Return type

[**CustomerRouteConfigurationPage**](CustomerRouteConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDedicatedBandwidthConfigurations

> DedicatedBandwidthConfigurationPage GetDedicatedBandwidthConfigurations(ctx).UseCase(useCase).ConnectionAsideAccessPointPortPhysicalPortSpeed(connectionAsideAccessPointPortPhysicalPortSpeed).Billing(billing).Offset(offset).Limit(limit).Execute()

Dedicated Bandwidth Attribute Eligibility API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	useCase := openapiclient.getRoutingConfigurations_useCase_parameter("MAIN") // GetRoutingConfigurationsUseCaseParameter | Use case
	connectionAsideAccessPointPortPhysicalPortSpeed := int32(56) // int32 | ASide access point physical port speed (Mbps), i.e. 1000, 10000, 100000 (optional)
	billing := openapiclient.getDedicatedBandwidthConfigurations_billing_parameter("FIXED") // GetDedicatedBandwidthConfigurationsBillingParameter | Billing type (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetDedicatedBandwidthConfigurations(context.Background()).UseCase(useCase).ConnectionAsideAccessPointPortPhysicalPortSpeed(connectionAsideAccessPointPortPhysicalPortSpeed).Billing(billing).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetDedicatedBandwidthConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDedicatedBandwidthConfigurations`: DedicatedBandwidthConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetDedicatedBandwidthConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDedicatedBandwidthConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **useCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) | Use case | 
 **connectionAsideAccessPointPortPhysicalPortSpeed** | **int32** | ASide access point physical port speed (Mbps), i.e. 1000, 10000, 100000 | 
 **billing** | [**GetDedicatedBandwidthConfigurationsBillingParameter**](GetDedicatedBandwidthConfigurationsBillingParameter.md) | Billing type | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**DedicatedBandwidthConfigurationPage**](DedicatedBandwidthConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDedicatedPortDefaultConfigurationsPage

> DedicatedPortDefaultConfigurationsPage GetDedicatedPortDefaultConfigurationsPage(ctx).ConnectionAsideAccessPointLocationIbx(connectionAsideAccessPointLocationIbx).Offset(offset).Limit(limit).Execute()

Dedicated port default configurations API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	connectionAsideAccessPointLocationIbx := "WA1" // string | ASide access point location IBX
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetDedicatedPortDefaultConfigurationsPage(context.Background()).ConnectionAsideAccessPointLocationIbx(connectionAsideAccessPointLocationIbx).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetDedicatedPortDefaultConfigurationsPage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDedicatedPortDefaultConfigurationsPage`: DedicatedPortDefaultConfigurationsPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetDedicatedPortDefaultConfigurationsPage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDedicatedPortDefaultConfigurationsPageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionAsideAccessPointLocationIbx** | **string** | ASide access point location IBX | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**DedicatedPortDefaultConfigurationsPage**](DedicatedPortDefaultConfigurationsPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPortConfigurations

> PortConfigurationPage GetPortConfigurations(ctx).ConnectionAsideAccessPointPortLocationIbx(connectionAsideAccessPointPortLocationIbx).UseCase(useCase).Offset(offset).Limit(limit).Execute()

Dedicated Port Attribute Eligibility API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	connectionAsideAccessPointPortLocationIbx := "WA1" // string | ASide access point port location IBX
	useCase := openapiclient.getRoutingConfigurations_useCase_parameter("MAIN") // GetRoutingConfigurationsUseCaseParameter | Use case
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetPortConfigurations(context.Background()).ConnectionAsideAccessPointPortLocationIbx(connectionAsideAccessPointPortLocationIbx).UseCase(useCase).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetPortConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPortConfigurations`: PortConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetPortConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPortConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionAsideAccessPointPortLocationIbx** | **string** | ASide access point port location IBX | 
 **useCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) | Use case | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**PortConfigurationPage**](PortConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRoutingConfigurations

> RoutingProtocolConfigurationPage GetRoutingConfigurations(ctx).UseCase(useCase).Type_(type_).Offset(offset).Limit(limit).Execute()

Routing Protocol Attribute Eligibility API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	useCase := openapiclient.getRoutingConfigurations_useCase_parameter("MAIN") // GetRoutingConfigurationsUseCaseParameter | Use case
	type_ := openapiclient.ProductCatalogRedundancy("SINGLE_PORT") // ProductCatalogRedundancy | Port type (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetRoutingConfigurations(context.Background()).UseCase(useCase).Type_(type_).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetRoutingConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRoutingConfigurations`: RoutingProtocolConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetRoutingConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRoutingConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **useCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) | Use case | 
 **type_** | [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) | Port type | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**RoutingProtocolConfigurationPage**](RoutingProtocolConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualBandwidthConfigurations

> VirtualBandwidthConfigurationPage GetVirtualBandwidthConfigurations(ctx).UseCase(useCase).Billing(billing).Offset(offset).Limit(limit).Execute()

Virtual Bandwidth Attribute Eligibility API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	useCase := openapiclient.getRoutingConfigurations_useCase_parameter("MAIN") // GetRoutingConfigurationsUseCaseParameter | Use case
	billing := openapiclient.getDedicatedBandwidthConfigurations_billing_parameter("FIXED") // GetDedicatedBandwidthConfigurationsBillingParameter | Billing type (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetVirtualBandwidthConfigurations(context.Background()).UseCase(useCase).Billing(billing).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetVirtualBandwidthConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualBandwidthConfigurations`: VirtualBandwidthConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetVirtualBandwidthConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualBandwidthConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **useCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) | Use case | 
 **billing** | [**GetDedicatedBandwidthConfigurationsBillingParameter**](GetDedicatedBandwidthConfigurationsBillingParameter.md) | Billing type | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**VirtualBandwidthConfigurationPage**](VirtualBandwidthConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualConnectionDefaultConfigurations

> VirtualConnectionDefaultConfigurationPage GetVirtualConnectionDefaultConfigurations(ctx).ConnectionAsideAccessPointLocationIbx(connectionAsideAccessPointLocationIbx).ConnectionAsideAccessPointLocationMetroCode(connectionAsideAccessPointLocationMetroCode).Offset(offset).Limit(limit).Execute()

Virtual Connection Default Configuration Attribute Eligibility API Endpoint



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/internetaccessv1"
)

func main() {
	connectionAsideAccessPointLocationIbx := "WA1" // string | Access point IBX code
	connectionAsideAccessPointLocationMetroCode := "connectionAsideAccessPointLocationMetroCode_example" // string | Access point Metro code (optional)
	offset := int32(0) // int32 | Pagination offset (optional) (default to 0)
	limit := int32(50) // int32 | Max number of returned results (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttributeEligibilityApi.GetVirtualConnectionDefaultConfigurations(context.Background()).ConnectionAsideAccessPointLocationIbx(connectionAsideAccessPointLocationIbx).ConnectionAsideAccessPointLocationMetroCode(connectionAsideAccessPointLocationMetroCode).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttributeEligibilityApi.GetVirtualConnectionDefaultConfigurations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualConnectionDefaultConfigurations`: VirtualConnectionDefaultConfigurationPage
	fmt.Fprintf(os.Stdout, "Response from `AttributeEligibilityApi.GetVirtualConnectionDefaultConfigurations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualConnectionDefaultConfigurationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectionAsideAccessPointLocationIbx** | **string** | Access point IBX code | 
 **connectionAsideAccessPointLocationMetroCode** | **string** | Access point Metro code | 
 **offset** | **int32** | Pagination offset | [default to 0]
 **limit** | **int32** | Max number of returned results | [default to 50]

### Return type

[**VirtualConnectionDefaultConfigurationPage**](VirtualConnectionDefaultConfigurationPage.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

