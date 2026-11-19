# \AvailabilityAndMetrosApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAgreement**](AvailabilityAndMetrosApi.md#CreateAgreement) | **Post** /ne/v1/agreements/accounts | Create an agreement
[**GetAccountsWithStatus**](AvailabilityAndMetrosApi.md#GetAccountsWithStatus) | **Get** /ne/v1/accounts/{metro} | List Accounts by Metro
[**GetAgreementStatus**](AvailabilityAndMetrosApi.md#GetAgreementStatus) | **Get** /ne/v1/agreements/accounts | Get Agreement Status
[**GetAllowedInterfaces**](AvailabilityAndMetrosApi.md#GetAllowedInterfaces) | **Get** /ne/v1/deviceTypes/{deviceType}/interfaces | List Allowed Interfaces
[**GetMetros**](AvailabilityAndMetrosApi.md#GetMetros) | **Get** /ne/v1/metros | List Available Metros
[**GetNotifications**](AvailabilityAndMetrosApi.md#GetNotifications) | **Get** /ne/v1/notifications | Get Downtime Notifications
[**GetOrderSummary**](AvailabilityAndMetrosApi.md#GetOrderSummary) | **Get** /ne/v1/orderSummaries | Get Order Summary
[**GetOrderTerms**](AvailabilityAndMetrosApi.md#GetOrderTerms) | **Get** /ne/v1/agreements/orders | Get Order Terms
[**GetPublicKeys**](AvailabilityAndMetrosApi.md#GetPublicKeys) | **Get** /ne/v1/publicKeys | Get Public Keys
[**GetVendorTerms**](AvailabilityAndMetrosApi.md#GetVendorTerms) | **Get** /ne/v1/agreements/vendors | Get Vendor Terms
[**GetVirtualDeviceTypes**](AvailabilityAndMetrosApi.md#GetVirtualDeviceTypes) | **Get** /ne/v1/deviceTypes | List Device Types
[**PostPublicKey**](AvailabilityAndMetrosApi.md#PostPublicKey) | **Post** /ne/v1/publicKeys | Create Public Key
[**RetrievePrice**](AvailabilityAndMetrosApi.md#RetrievePrice) | **Get** /ne/v1/prices | Calculate Price
[**UpdateLicenseToken**](AvailabilityAndMetrosApi.md#UpdateLicenseToken) | **Put** /ne/v1/devices/{uuid}/licenseTokens | Update License Token/ID/Code
[**UploadFile**](AvailabilityAndMetrosApi.md#UploadFile) | **Post** /ne/v1/files | Upload File
[**UploadLicense**](AvailabilityAndMetrosApi.md#UploadLicense) | **Post** /ne/v1/devices/licenseFiles | Upload License File
[**UploadLicenseForDevice**](AvailabilityAndMetrosApi.md#UploadLicenseForDevice) | **Post** /ne/v1/devices/licenseFiles/{uuid} | Upload License for a Virtual Device



## CreateAgreement

> AgreementAcceptResponse CreateAgreement(ctx).AgreementAcceptRequest(agreementAcceptRequest).Execute()

Create an agreement



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
	agreementAcceptRequest := *openapiclient.NewAgreementAcceptRequest() // AgreementAcceptRequest | agreementAcceptRequest

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.CreateAgreement(context.Background()).AgreementAcceptRequest(agreementAcceptRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.CreateAgreement``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAgreement`: AgreementAcceptResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.CreateAgreement`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAgreementRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **agreementAcceptRequest** | [**AgreementAcceptRequest**](AgreementAcceptRequest.md) | agreementAcceptRequest | 

### Return type

[**AgreementAcceptResponse**](AgreementAcceptResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAccountsWithStatus

> PageResponseMetroAccountResponse GetAccountsWithStatus(ctx, metro).AccountUcmId(accountUcmId).Execute()

List Accounts by Metro



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
	metro := "SV" // string | Metro region for which you want to check your account status
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | Unique ID of an account (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetAccountsWithStatus(context.Background(), metro).AccountUcmId(accountUcmId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetAccountsWithStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAccountsWithStatus`: PageResponseMetroAccountResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetAccountsWithStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**metro** | **string** | Metro region for which you want to check your account status | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAccountsWithStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountUcmId** | **string** | Unique ID of an account | 

### Return type

[**PageResponseMetroAccountResponse**](PageResponseMetroAccountResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgreementStatus

> AgreementStatusResponse GetAgreementStatus(ctx).AccountNumber(accountNumber).Execute()

Get Agreement Status



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
	accountNumber := "123456" // string | Unique identifier of the customer account. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetAgreementStatus(context.Background()).AccountNumber(accountNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetAgreementStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgreementStatus`: AgreementStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetAgreementStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAgreementStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNumber** | **string** | Unique identifier of the customer account. | 

### Return type

[**AgreementStatusResponse**](AgreementStatusResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllowedInterfaces

> AllowedInterfaceResponse GetAllowedInterfaces(ctx, deviceType).DeviceManagementType(deviceManagementType).Mode(mode).Cluster(cluster).Sdwan(sdwan).Connectivity(connectivity).Core(core).Memory(memory).Unit(unit).Flavor(flavor).Version(version).SoftwarePkg(softwarePkg).Execute()

List Allowed Interfaces



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
	deviceType := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | Device type code. PA-VM.
	deviceManagementType := openapiclient.getAllowedInterfaces_deviceManagementType_parameter("SELF-CONFIGURED") // GetAllowedInterfacesDeviceManagementTypeParameter | Device management type. SELF-CONFIGURED
	mode := openapiclient.getAllowedInterfaces_mode_parameter("Subscription") // GetAllowedInterfacesModeParameter | License mode, either Subscription or BYOL. (optional)
	cluster := false // bool | Whether you want a cluster device. (optional)
	sdwan := false // bool | Whether you want an SD-WAN device. (optional)
	connectivity := openapiclient.getAllowedInterfaces_connectivity_parameter("INTERNET-ACCESS") // GetAllowedInterfacesConnectivityParameter | Type of connectivity you want. INTERNET-ACCESS, PRIVATE, or INTERNET-ACCESS-WITH-PRVT-MGMT. PRIVATE devices do not have ACLs or bandwidth. (optional)
	core := int32(4) // int32 | The desired number of cores. (optional)
	memory := int32(4) // int32 | Desired memory. (optional)
	unit := "GB" // string | Unit of memory. GB or MB. (optional)
	flavor := "small" // string | Flavor of device. (optional)
	version := "17.06.01" // string | Version. (optional)
	softwarePkg := "SEC" // string | Software package. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetAllowedInterfaces(context.Background(), deviceType).DeviceManagementType(deviceManagementType).Mode(mode).Cluster(cluster).Sdwan(sdwan).Connectivity(connectivity).Core(core).Memory(memory).Unit(unit).Flavor(flavor).Version(version).SoftwarePkg(softwarePkg).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetAllowedInterfaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllowedInterfaces`: AllowedInterfaceResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetAllowedInterfaces`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deviceType** | [**DeviceTypeCode**](.md) | Device type code. PA-VM. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAllowedInterfacesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deviceManagementType** | [**GetAllowedInterfacesDeviceManagementTypeParameter**](GetAllowedInterfacesDeviceManagementTypeParameter.md) | Device management type. SELF-CONFIGURED | 
 **mode** | [**GetAllowedInterfacesModeParameter**](GetAllowedInterfacesModeParameter.md) | License mode, either Subscription or BYOL. | 
 **cluster** | **bool** | Whether you want a cluster device. | 
 **sdwan** | **bool** | Whether you want an SD-WAN device. | 
 **connectivity** | [**GetAllowedInterfacesConnectivityParameter**](GetAllowedInterfacesConnectivityParameter.md) | Type of connectivity you want. INTERNET-ACCESS, PRIVATE, or INTERNET-ACCESS-WITH-PRVT-MGMT. PRIVATE devices do not have ACLs or bandwidth. | 
 **core** | **int32** | The desired number of cores. | 
 **memory** | **int32** | Desired memory. | 
 **unit** | **string** | Unit of memory. GB or MB. | 
 **flavor** | **string** | Flavor of device. | 
 **version** | **string** | Version. | 
 **softwarePkg** | **string** | Software package. | 

### Return type

[**AllowedInterfaceResponse**](AllowedInterfaceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMetros

> GetMetrosResponse GetMetros(ctx).Region(region).Offset(offset).Limit(limit).Execute()

List Available Metros



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
	region := "AMER" // string | Name of the region for which you want metros (e.g., AMER) (optional)
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetMetros(context.Background()).Region(region).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetMetros``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMetros`: GetMetrosResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetMetros`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMetrosRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **region** | **string** | Name of the region for which you want metros (e.g., AMER) | 
 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]

### Return type

[**GetMetrosResponse**](GetMetrosResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNotifications

> DowntimeNotification GetNotifications(ctx).Execute()

Get Downtime Notifications



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetNotifications(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNotifications`: DowntimeNotification
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetNotifications`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetNotificationsRequest struct via the builder pattern


### Return type

[**DowntimeNotification**](DowntimeNotification.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderSummary

> PageResponse GetOrderSummary(ctx).AccountNumber(accountNumber).Metro(metro).VendorPackage(vendorPackage).LicenseType(licenseType).SoftwarePackage(softwarePackage).Throughput(throughput).ThroughputUnit(throughputUnit).TermLength(termLength).AdditionalBandwidth(additionalBandwidth).VirtualDeviceUuid(virtualDeviceUuid).DeviceManagementType(deviceManagementType).Core(core).SecondaryAccountNumber(secondaryAccountNumber).SecondaryMetro(secondaryMetro).SecondaryAdditionalBandwidth(secondaryAdditionalBandwidth).AccountUcmId(accountUcmId).OrderingContact(orderingContact).Execute()

Get Order Summary



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
	accountNumber := int32(123456) // int32 | Account number (optional)
	metro := "SV" // string | Metro (optional)
	vendorPackage := openapiclient.getVendorTerms_vendorPackage_parameter("VM02") // GetVendorTermsVendorPackageParameter | Vendor package (optional)
	licenseType := openapiclient.getAllowedInterfaces_mode_parameter("Subscription") // GetAllowedInterfacesModeParameter | License type (optional)
	softwarePackage := "AX" // string | Software package (optional)
	throughput := int32(100) // int32 | Throughput (optional)
	throughputUnit := "Mbps" // string | Throughput unit (optional)
	termLength := "12" // string | Term length (in months) (optional)
	additionalBandwidth := int32(100) // int32 | Additional bandwidth (in Mbps) (optional)
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Virtual device unique Id (only required if existing device is being modified) (optional)
	deviceManagementType := openapiclient.getAllowedInterfaces_deviceManagementType_parameter("SELF-CONFIGURED") // GetAllowedInterfacesDeviceManagementTypeParameter | The device management type (optional)
	core := int32(4) // int32 | The number of cores (optional)
	secondaryAccountNumber := int32(123457) // int32 | Secondary account number (in case you have a device pair) (optional)
	secondaryMetro := "SV" // string | Secondary metro (in case you have a device pair) (optional)
	secondaryAdditionalBandwidth := int32(100) // int32 | Secondary additional bandwidth (in Mbps) (optional)
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | Account unique ID (optional)
	orderingContact := "cust0001" // string | Reseller customer username (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetOrderSummary(context.Background()).AccountNumber(accountNumber).Metro(metro).VendorPackage(vendorPackage).LicenseType(licenseType).SoftwarePackage(softwarePackage).Throughput(throughput).ThroughputUnit(throughputUnit).TermLength(termLength).AdditionalBandwidth(additionalBandwidth).VirtualDeviceUuid(virtualDeviceUuid).DeviceManagementType(deviceManagementType).Core(core).SecondaryAccountNumber(secondaryAccountNumber).SecondaryMetro(secondaryMetro).SecondaryAdditionalBandwidth(secondaryAdditionalBandwidth).AccountUcmId(accountUcmId).OrderingContact(orderingContact).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetOrderSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderSummary`: PageResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetOrderSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNumber** | **int32** | Account number | 
 **metro** | **string** | Metro | 
 **vendorPackage** | [**GetVendorTermsVendorPackageParameter**](GetVendorTermsVendorPackageParameter.md) | Vendor package | 
 **licenseType** | [**GetAllowedInterfacesModeParameter**](GetAllowedInterfacesModeParameter.md) | License type | 
 **softwarePackage** | **string** | Software package | 
 **throughput** | **int32** | Throughput | 
 **throughputUnit** | **string** | Throughput unit | 
 **termLength** | **string** | Term length (in months) | 
 **additionalBandwidth** | **int32** | Additional bandwidth (in Mbps) | 
 **virtualDeviceUuid** | **string** | Virtual device unique Id (only required if existing device is being modified) | 
 **deviceManagementType** | [**GetAllowedInterfacesDeviceManagementTypeParameter**](GetAllowedInterfacesDeviceManagementTypeParameter.md) | The device management type | 
 **core** | **int32** | The number of cores | 
 **secondaryAccountNumber** | **int32** | Secondary account number (in case you have a device pair) | 
 **secondaryMetro** | **string** | Secondary metro (in case you have a device pair) | 
 **secondaryAdditionalBandwidth** | **int32** | Secondary additional bandwidth (in Mbps) | 
 **accountUcmId** | **string** | Account unique ID | 
 **orderingContact** | **string** | Reseller customer username | 

### Return type

[**PageResponse**](PageResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrderTerms

> OrderTermsResponse GetOrderTerms(ctx).Execute()

Get Order Terms



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetOrderTerms(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetOrderTerms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrderTerms`: OrderTermsResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetOrderTerms`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrderTermsRequest struct via the builder pattern


### Return type

[**OrderTermsResponse**](OrderTermsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicKeys

> GetPublicKeysResponse GetPublicKeys(ctx).AccountUcmId(accountUcmId).ProjectIds(projectIds).Execute()

Get Public Keys



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
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | This field is for resellers. Please pass the accountUcmId of your customer to get the public keys. (optional)
	projectIds := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8,3da0a663-20d9-4b8f-8c5d-d5cf706840c9" // string | If projectIds are different from default projectIds, must pass a projectIds parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetPublicKeys(context.Background()).AccountUcmId(accountUcmId).ProjectIds(projectIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetPublicKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicKeys`: GetPublicKeysResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetPublicKeys`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountUcmId** | **string** | This field is for resellers. Please pass the accountUcmId of your customer to get the public keys. | 
 **projectIds** | **string** | If projectIds are different from default projectIds, must pass a projectIds parameter | 

### Return type

[**GetPublicKeysResponse**](GetPublicKeysResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVendorTerms

> VendorTermsResponse GetVendorTerms(ctx).VendorPackage(vendorPackage).LicenseType(licenseType).Execute()

Get Vendor Terms



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
	vendorPackage := openapiclient.getVendorTerms_vendorPackage_parameter("VM02") // GetVendorTermsVendorPackageParameter | The vendor package code. (optional)
	licenseType := openapiclient.getAllowedInterfaces_mode_parameter("Subscription") // GetAllowedInterfacesModeParameter | The type of license (e.g., Subscription, BYOL). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetVendorTerms(context.Background()).VendorPackage(vendorPackage).LicenseType(licenseType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetVendorTerms``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVendorTerms`: VendorTermsResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetVendorTerms`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVendorTermsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **vendorPackage** | [**GetVendorTermsVendorPackageParameter**](GetVendorTermsVendorPackageParameter.md) | The vendor package code. | 
 **licenseType** | [**GetAllowedInterfacesModeParameter**](GetAllowedInterfacesModeParameter.md) | The type of license (e.g., Subscription, BYOL). | 

### Return type

[**VendorTermsResponse**](VendorTermsResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVirtualDeviceTypes

> GetDeviceTypesResponse GetVirtualDeviceTypes(ctx).DeviceTypeCode(deviceTypeCode).Category(category).Offset(offset).Limit(limit).ProjectId(projectId).Execute()

List Device Types



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
	deviceTypeCode := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | Device type code (e.g., C8000V) (optional)
	category := "ROUTER" // string | Category. One of FIREWALL, ROUTER or SD-WAN (optional)
	offset := int32(0) // int32 | Specifies where to start a page. It is the starting point of the collection returned from the server. (optional) (default to 0)
	limit := int32(20) // int32 | Specifies the page size. (optional) (default to 20)
	projectId := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectId is different from default projectId, must pass a projectId parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.GetVirtualDeviceTypes(context.Background()).DeviceTypeCode(deviceTypeCode).Category(category).Offset(offset).Limit(limit).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.GetVirtualDeviceTypes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVirtualDeviceTypes`: GetDeviceTypesResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.GetVirtualDeviceTypes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVirtualDeviceTypesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deviceTypeCode** | [**DeviceTypeCode**](DeviceTypeCode.md) | Device type code (e.g., C8000V) | 
 **category** | **string** | Category. One of FIREWALL, ROUTER or SD-WAN | 
 **offset** | **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [default to 0]
 **limit** | **int32** | Specifies the page size. | [default to 20]
 **projectId** | **string** | If projectId is different from default projectId, must pass a projectId parameter | 

### Return type

[**GetDeviceTypesResponse**](GetDeviceTypesResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostPublicKey

> PublicKeyResponse PostPublicKey(ctx).PublicKeyRequest(publicKeyRequest).Execute()

Create Public Key



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
	publicKeyRequest := *openapiclient.NewPublicKeyRequest("myKeyName", "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAAAgQC5kHcagDZ7utPan4DHWUvoJxwz/DISRFwZdpMhslhZRI+6dGOC8mJn42SlSUAUtkt8Qyl4HipPK7Xh6oGj70Iba1a9pDcURYTYcqWFBEhcdDsMnH1CICmvVdsILehFtiS3X0J1JhwmWQI/7ll3QOk8fLgWCz3idlYJqtMs8Gz/6Q== noname") // PublicKeyRequest | keyName, keyValue, and keyType

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.PostPublicKey(context.Background()).PublicKeyRequest(publicKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.PostPublicKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostPublicKey`: PublicKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.PostPublicKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostPublicKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publicKeyRequest** | [**PublicKeyRequest**](PublicKeyRequest.md) | keyName, keyValue, and keyType | 

### Return type

[**PublicKeyResponse**](PublicKeyResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrievePrice

> CompositePriceResponse RetrievePrice(ctx).AccountNumber(accountNumber).Metro(metro).VendorPackage(vendorPackage).LicenseType(licenseType).SoftwarePackage(softwarePackage).Throughput(throughput).ThroughputUnit(throughputUnit).TermLength(termLength).AdditionalBandwidth(additionalBandwidth).VirtualDeviceUuid(virtualDeviceUuid).DeviceManagementType(deviceManagementType).Core(core).SecondaryAccountNumber(secondaryAccountNumber).SecondaryMetro(secondaryMetro).SecondaryAdditionalBandwidth(secondaryAdditionalBandwidth).AccountUcmId(accountUcmId).OrderingContact(orderingContact).Execute()

Calculate Price



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
	accountNumber := int32(123456) // int32 | Account number (optional)
	metro := "SV" // string | Metro (optional)
	vendorPackage := openapiclient.getVendorTerms_vendorPackage_parameter("VM02") // GetVendorTermsVendorPackageParameter | Vendor package (optional)
	licenseType := openapiclient.getAllowedInterfaces_mode_parameter("Subscription") // GetAllowedInterfacesModeParameter | License type (optional)
	softwarePackage := "AX" // string | Software package (optional)
	throughput := int32(100) // int32 | Throughput (optional)
	throughputUnit := "Mbps" // string | Throughput unit (optional)
	termLength := "12" // string | Term length (in months) (optional)
	additionalBandwidth := int32(100) // int32 | Additional bandwidth (in Mbps) (optional)
	virtualDeviceUuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Virtual device unique Id (only required if existing device is being modified) (optional)
	deviceManagementType := openapiclient.getAllowedInterfaces_deviceManagementType_parameter("SELF-CONFIGURED") // GetAllowedInterfacesDeviceManagementTypeParameter | The device management type (optional)
	core := int32(4) // int32 | The number of cores (optional)
	secondaryAccountNumber := int32(123457) // int32 | The secondary account number (for HA) (optional)
	secondaryMetro := "SV" // string | Secondary metro (for HA) (optional)
	secondaryAdditionalBandwidth := int32(100) // int32 | Secondary additional bandwidth (in Mbps for HA) (optional)
	accountUcmId := "92D27009-EA33-4b60-B4FB-D3C4ED589649" // string | Account unique ID (optional)
	orderingContact := "cust0001" // string | Reseller customer username (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.RetrievePrice(context.Background()).AccountNumber(accountNumber).Metro(metro).VendorPackage(vendorPackage).LicenseType(licenseType).SoftwarePackage(softwarePackage).Throughput(throughput).ThroughputUnit(throughputUnit).TermLength(termLength).AdditionalBandwidth(additionalBandwidth).VirtualDeviceUuid(virtualDeviceUuid).DeviceManagementType(deviceManagementType).Core(core).SecondaryAccountNumber(secondaryAccountNumber).SecondaryMetro(secondaryMetro).SecondaryAdditionalBandwidth(secondaryAdditionalBandwidth).AccountUcmId(accountUcmId).OrderingContact(orderingContact).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.RetrievePrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrievePrice`: CompositePriceResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.RetrievePrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetrievePriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNumber** | **int32** | Account number | 
 **metro** | **string** | Metro | 
 **vendorPackage** | [**GetVendorTermsVendorPackageParameter**](GetVendorTermsVendorPackageParameter.md) | Vendor package | 
 **licenseType** | [**GetAllowedInterfacesModeParameter**](GetAllowedInterfacesModeParameter.md) | License type | 
 **softwarePackage** | **string** | Software package | 
 **throughput** | **int32** | Throughput | 
 **throughputUnit** | **string** | Throughput unit | 
 **termLength** | **string** | Term length (in months) | 
 **additionalBandwidth** | **int32** | Additional bandwidth (in Mbps) | 
 **virtualDeviceUuid** | **string** | Virtual device unique Id (only required if existing device is being modified) | 
 **deviceManagementType** | [**GetAllowedInterfacesDeviceManagementTypeParameter**](GetAllowedInterfacesDeviceManagementTypeParameter.md) | The device management type | 
 **core** | **int32** | The number of cores | 
 **secondaryAccountNumber** | **int32** | The secondary account number (for HA) | 
 **secondaryMetro** | **string** | Secondary metro (for HA) | 
 **secondaryAdditionalBandwidth** | **int32** | Secondary additional bandwidth (in Mbps for HA) | 
 **accountUcmId** | **string** | Account unique ID | 
 **orderingContact** | **string** | Reseller customer username | 

### Return type

[**CompositePriceResponse**](CompositePriceResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateLicenseToken

> LicenseUploadResponse UpdateLicenseToken(ctx, uuid).Request(request).Execute()

Update License Token/ID/Code



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device
	request := *openapiclient.NewLicenseUpdateRequest() // LicenseUpdateRequest | License token

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.UpdateLicenseToken(context.Background(), uuid).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.UpdateLicenseToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateLicenseToken`: LicenseUploadResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.UpdateLicenseToken`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a virtual device | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateLicenseTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **request** | [**LicenseUpdateRequest**](LicenseUpdateRequest.md) | License token | 

### Return type

[**LicenseUploadResponse**](LicenseUploadResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadFile

> FileUploadResponse UploadFile(ctx).File(file).MetroCode(metroCode).DeviceTypeCode(deviceTypeCode).ProcessType(processType).DeviceManagementType(deviceManagementType).LicenseType(licenseType).Execute()

Upload File



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
	file := os.NewFile(1234, "some_file") // *os.File | A license or a cloud_init file.
	metroCode := "metroCode_example" // string | Two-letter metro code.
	deviceTypeCode := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | 
	processType := openapiclient.FileUploadRequest_processType("LICENSE") // FileUploadRequestProcessType | 
	deviceManagementType := openapiclient.FileUploadRequest_deviceManagementType("SELF-CONFIGURED") // FileUploadRequestDeviceManagementType |  (optional)
	licenseType := openapiclient.FileUploadRequest_licenseType("BYOL") // FileUploadRequestLicenseType |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.UploadFile(context.Background()).File(file).MetroCode(metroCode).DeviceTypeCode(deviceTypeCode).ProcessType(processType).DeviceManagementType(deviceManagementType).LicenseType(licenseType).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.UploadFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadFile`: FileUploadResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.UploadFile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | A license or a cloud_init file. | 
 **metroCode** | **string** | Two-letter metro code. | 
 **deviceTypeCode** | [**DeviceTypeCode**](DeviceTypeCode.md) |  | 
 **processType** | [**FileUploadRequestProcessType**](FileUploadRequestProcessType.md) |  | 
 **deviceManagementType** | [**FileUploadRequestDeviceManagementType**](FileUploadRequestDeviceManagementType.md) |  | 
 **licenseType** | [**FileUploadRequestLicenseType**](FileUploadRequestLicenseType.md) |  | 

### Return type

[**FileUploadResponse**](FileUploadResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadLicense

> LicenseUploadResponse UploadLicense(ctx).MetroCode(metroCode).DeviceTypeCode(deviceTypeCode).LicenseType(licenseType).File(file).ProjectId(projectId).Execute()

Upload License File



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
	metroCode := "SV" // string | Two-letter metro code where the device will be created.
	deviceTypeCode := openapiclient.DeviceTypeCode("C8000V") // DeviceTypeCode | Device type code (e.g., C8000V).
	licenseType := openapiclient.uploadLicense_licenseType_parameter("BYOL") // UploadLicenseLicenseTypeParameter | Type of license (e.g., BYOL).
	file := os.NewFile(1234, "some_file") // *os.File | License file
	projectId := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectId is different from default projectId, must pass a projectId parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.UploadLicense(context.Background()).MetroCode(metroCode).DeviceTypeCode(deviceTypeCode).LicenseType(licenseType).File(file).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.UploadLicense``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadLicense`: LicenseUploadResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.UploadLicense`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadLicenseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **metroCode** | **string** | Two-letter metro code where the device will be created. | 
 **deviceTypeCode** | [**DeviceTypeCode**](DeviceTypeCode.md) | Device type code (e.g., C8000V). | 
 **licenseType** | [**UploadLicenseLicenseTypeParameter**](UploadLicenseLicenseTypeParameter.md) | Type of license (e.g., BYOL). | 
 **file** | ***os.File** | License file | 
 **projectId** | **string** | If projectId is different from default projectId, must pass a projectId parameter | 

### Return type

[**LicenseUploadResponse**](LicenseUploadResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadLicenseForDevice

> LicenseUploadResponse UploadLicenseForDevice(ctx, uuid).File(file).ProjectId(projectId).Execute()

Upload License for a Virtual Device



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
	uuid := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | Unique Id of a virtual device
	file := os.NewFile(1234, "some_file") // *os.File | License file
	projectId := "3da0a663-20d9-4b8f-8c5d-d5cf706840c8" // string | If projectId is different from default projectId, must pass a projectId parameter (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvailabilityAndMetrosApi.UploadLicenseForDevice(context.Background(), uuid).File(file).ProjectId(projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvailabilityAndMetrosApi.UploadLicenseForDevice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadLicenseForDevice`: LicenseUploadResponse
	fmt.Fprintf(os.Stdout, "Response from `AvailabilityAndMetrosApi.UploadLicenseForDevice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**uuid** | **string** | Unique Id of a virtual device | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadLicenseForDeviceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **file** | ***os.File** | License file | 
 **projectId** | **string** | If projectId is different from default projectId, must pass a projectId parameter | 

### Return type

[**LicenseUploadResponse**](LicenseUploadResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

