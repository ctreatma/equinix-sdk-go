# VirtualBandwidthConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | 
**Billing** | [**VirtualBandwidthConfigurationBilling**](VirtualBandwidthConfigurationBilling.md) |  | 
**Bandwidth** | **int32** | in Mbps | 
**MinBandwidthCommit** | Pointer to **int32** | in Mbps | [optional] 

## Methods

### NewVirtualBandwidthConfiguration

`func NewVirtualBandwidthConfiguration(useCase GetRoutingConfigurationsUseCaseParameter, billing VirtualBandwidthConfigurationBilling, bandwidth int32, ) *VirtualBandwidthConfiguration`

NewVirtualBandwidthConfiguration instantiates a new VirtualBandwidthConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVirtualBandwidthConfigurationWithDefaults

`func NewVirtualBandwidthConfigurationWithDefaults() *VirtualBandwidthConfiguration`

NewVirtualBandwidthConfigurationWithDefaults instantiates a new VirtualBandwidthConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseCase

`func (o *VirtualBandwidthConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *VirtualBandwidthConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *VirtualBandwidthConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.


### GetBilling

`func (o *VirtualBandwidthConfiguration) GetBilling() VirtualBandwidthConfigurationBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *VirtualBandwidthConfiguration) GetBillingOk() (*VirtualBandwidthConfigurationBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *VirtualBandwidthConfiguration) SetBilling(v VirtualBandwidthConfigurationBilling)`

SetBilling sets Billing field to given value.


### GetBandwidth

`func (o *VirtualBandwidthConfiguration) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *VirtualBandwidthConfiguration) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *VirtualBandwidthConfiguration) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.


### GetMinBandwidthCommit

`func (o *VirtualBandwidthConfiguration) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *VirtualBandwidthConfiguration) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *VirtualBandwidthConfiguration) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *VirtualBandwidthConfiguration) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


