# VirtualConnectionDefaultConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) |  | 
**UseCase** | [**ProductCatalogUseCase**](ProductCatalogUseCase.md) |  | 
**Billing** | [**ProductCatalogBillingType**](ProductCatalogBillingType.md) |  | 
**Bandwidth** | **int32** | in Mbps | 
**MinBandwidthCommit** | Pointer to **int32** | in Mbps | [optional] 
**Connection** | [**VirtualConnectionDefaultConfigurationConnection**](VirtualConnectionDefaultConfigurationConnection.md) |  | 
**RoutingProtocol** | [**VirtualConnectionDefaultConfigurationRoutingProtocol**](VirtualConnectionDefaultConfigurationRoutingProtocol.md) |  | 

## Methods

### NewVirtualConnectionDefaultConfiguration

`func NewVirtualConnectionDefaultConfiguration(type_ ProductCatalogRedundancy, useCase ProductCatalogUseCase, billing ProductCatalogBillingType, bandwidth int32, connection VirtualConnectionDefaultConfigurationConnection, routingProtocol VirtualConnectionDefaultConfigurationRoutingProtocol, ) *VirtualConnectionDefaultConfiguration`

NewVirtualConnectionDefaultConfiguration instantiates a new VirtualConnectionDefaultConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVirtualConnectionDefaultConfigurationWithDefaults

`func NewVirtualConnectionDefaultConfigurationWithDefaults() *VirtualConnectionDefaultConfiguration`

NewVirtualConnectionDefaultConfigurationWithDefaults instantiates a new VirtualConnectionDefaultConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *VirtualConnectionDefaultConfiguration) GetType() ProductCatalogRedundancy`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VirtualConnectionDefaultConfiguration) GetTypeOk() (*ProductCatalogRedundancy, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VirtualConnectionDefaultConfiguration) SetType(v ProductCatalogRedundancy)`

SetType sets Type field to given value.


### GetUseCase

`func (o *VirtualConnectionDefaultConfiguration) GetUseCase() ProductCatalogUseCase`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *VirtualConnectionDefaultConfiguration) GetUseCaseOk() (*ProductCatalogUseCase, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *VirtualConnectionDefaultConfiguration) SetUseCase(v ProductCatalogUseCase)`

SetUseCase sets UseCase field to given value.


### GetBilling

`func (o *VirtualConnectionDefaultConfiguration) GetBilling() ProductCatalogBillingType`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *VirtualConnectionDefaultConfiguration) GetBillingOk() (*ProductCatalogBillingType, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *VirtualConnectionDefaultConfiguration) SetBilling(v ProductCatalogBillingType)`

SetBilling sets Billing field to given value.


### GetBandwidth

`func (o *VirtualConnectionDefaultConfiguration) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *VirtualConnectionDefaultConfiguration) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *VirtualConnectionDefaultConfiguration) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.


### GetMinBandwidthCommit

`func (o *VirtualConnectionDefaultConfiguration) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *VirtualConnectionDefaultConfiguration) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *VirtualConnectionDefaultConfiguration) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *VirtualConnectionDefaultConfiguration) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.

### GetConnection

`func (o *VirtualConnectionDefaultConfiguration) GetConnection() VirtualConnectionDefaultConfigurationConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *VirtualConnectionDefaultConfiguration) GetConnectionOk() (*VirtualConnectionDefaultConfigurationConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *VirtualConnectionDefaultConfiguration) SetConnection(v VirtualConnectionDefaultConfigurationConnection)`

SetConnection sets Connection field to given value.


### GetRoutingProtocol

`func (o *VirtualConnectionDefaultConfiguration) GetRoutingProtocol() VirtualConnectionDefaultConfigurationRoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *VirtualConnectionDefaultConfiguration) GetRoutingProtocolOk() (*VirtualConnectionDefaultConfigurationRoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *VirtualConnectionDefaultConfiguration) SetRoutingProtocol(v VirtualConnectionDefaultConfigurationRoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


