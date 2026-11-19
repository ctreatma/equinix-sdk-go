# DedicatedPortDefaultConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) |  | [optional] 
**UseCase** | Pointer to [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | [optional] 
**Billing** | [**VirtualBandwidthConfigurationBilling**](VirtualBandwidthConfigurationBilling.md) |  | 
**Bandwidth** | Pointer to **int32** | in Mbps | [optional] 
**MinBandwidthCommit** | Pointer to **int32** | in Mbps | [optional] 
**Connection** | [**DedicatedPortDefaultConfigurationConnection**](DedicatedPortDefaultConfigurationConnection.md) |  | 
**RoutingProtocol** | Pointer to [**DedicatedPortDefaultConfigurationRoutingProtocol**](DedicatedPortDefaultConfigurationRoutingProtocol.md) |  | [optional] 

## Methods

### NewDedicatedPortDefaultConfiguration

`func NewDedicatedPortDefaultConfiguration(billing VirtualBandwidthConfigurationBilling, connection DedicatedPortDefaultConfigurationConnection, ) *DedicatedPortDefaultConfiguration`

NewDedicatedPortDefaultConfiguration instantiates a new DedicatedPortDefaultConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDedicatedPortDefaultConfigurationWithDefaults

`func NewDedicatedPortDefaultConfigurationWithDefaults() *DedicatedPortDefaultConfiguration`

NewDedicatedPortDefaultConfigurationWithDefaults instantiates a new DedicatedPortDefaultConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *DedicatedPortDefaultConfiguration) GetType() ProductCatalogRedundancy`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DedicatedPortDefaultConfiguration) GetTypeOk() (*ProductCatalogRedundancy, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DedicatedPortDefaultConfiguration) SetType(v ProductCatalogRedundancy)`

SetType sets Type field to given value.

### HasType

`func (o *DedicatedPortDefaultConfiguration) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUseCase

`func (o *DedicatedPortDefaultConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *DedicatedPortDefaultConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *DedicatedPortDefaultConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.

### HasUseCase

`func (o *DedicatedPortDefaultConfiguration) HasUseCase() bool`

HasUseCase returns a boolean if a field has been set.

### GetBilling

`func (o *DedicatedPortDefaultConfiguration) GetBilling() VirtualBandwidthConfigurationBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *DedicatedPortDefaultConfiguration) GetBillingOk() (*VirtualBandwidthConfigurationBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *DedicatedPortDefaultConfiguration) SetBilling(v VirtualBandwidthConfigurationBilling)`

SetBilling sets Billing field to given value.


### GetBandwidth

`func (o *DedicatedPortDefaultConfiguration) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *DedicatedPortDefaultConfiguration) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *DedicatedPortDefaultConfiguration) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.

### HasBandwidth

`func (o *DedicatedPortDefaultConfiguration) HasBandwidth() bool`

HasBandwidth returns a boolean if a field has been set.

### GetMinBandwidthCommit

`func (o *DedicatedPortDefaultConfiguration) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *DedicatedPortDefaultConfiguration) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *DedicatedPortDefaultConfiguration) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *DedicatedPortDefaultConfiguration) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.

### GetConnection

`func (o *DedicatedPortDefaultConfiguration) GetConnection() DedicatedPortDefaultConfigurationConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *DedicatedPortDefaultConfiguration) GetConnectionOk() (*DedicatedPortDefaultConfigurationConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *DedicatedPortDefaultConfiguration) SetConnection(v DedicatedPortDefaultConfigurationConnection)`

SetConnection sets Connection field to given value.


### GetRoutingProtocol

`func (o *DedicatedPortDefaultConfiguration) GetRoutingProtocol() DedicatedPortDefaultConfigurationRoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *DedicatedPortDefaultConfiguration) GetRoutingProtocolOk() (*DedicatedPortDefaultConfigurationRoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *DedicatedPortDefaultConfiguration) SetRoutingProtocol(v DedicatedPortDefaultConfigurationRoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.

### HasRoutingProtocol

`func (o *DedicatedPortDefaultConfiguration) HasRoutingProtocol() bool`

HasRoutingProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


