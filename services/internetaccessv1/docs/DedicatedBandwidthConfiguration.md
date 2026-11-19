# DedicatedBandwidthConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | 
**Bandwidth** | **int32** | in Mbps | 
**MinBandwidthCommit** | Pointer to **int32** | in Mbps | [optional] 
**Billing** | Pointer to [**GetDedicatedBandwidthConfigurationsBillingParameter**](GetDedicatedBandwidthConfigurationsBillingParameter.md) |  | [optional] 
**Connection** | [**DedicatedBandwidthConfigurationConnection**](DedicatedBandwidthConfigurationConnection.md) |  | 

## Methods

### NewDedicatedBandwidthConfiguration

`func NewDedicatedBandwidthConfiguration(useCase GetRoutingConfigurationsUseCaseParameter, bandwidth int32, connection DedicatedBandwidthConfigurationConnection, ) *DedicatedBandwidthConfiguration`

NewDedicatedBandwidthConfiguration instantiates a new DedicatedBandwidthConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDedicatedBandwidthConfigurationWithDefaults

`func NewDedicatedBandwidthConfigurationWithDefaults() *DedicatedBandwidthConfiguration`

NewDedicatedBandwidthConfigurationWithDefaults instantiates a new DedicatedBandwidthConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseCase

`func (o *DedicatedBandwidthConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *DedicatedBandwidthConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *DedicatedBandwidthConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.


### GetBandwidth

`func (o *DedicatedBandwidthConfiguration) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *DedicatedBandwidthConfiguration) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *DedicatedBandwidthConfiguration) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.


### GetMinBandwidthCommit

`func (o *DedicatedBandwidthConfiguration) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *DedicatedBandwidthConfiguration) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *DedicatedBandwidthConfiguration) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *DedicatedBandwidthConfiguration) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.

### GetBilling

`func (o *DedicatedBandwidthConfiguration) GetBilling() GetDedicatedBandwidthConfigurationsBillingParameter`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *DedicatedBandwidthConfiguration) GetBillingOk() (*GetDedicatedBandwidthConfigurationsBillingParameter, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *DedicatedBandwidthConfiguration) SetBilling(v GetDedicatedBandwidthConfigurationsBillingParameter)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *DedicatedBandwidthConfiguration) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetConnection

`func (o *DedicatedBandwidthConfiguration) GetConnection() DedicatedBandwidthConfigurationConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *DedicatedBandwidthConfiguration) GetConnectionOk() (*DedicatedBandwidthConfigurationConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *DedicatedBandwidthConfiguration) SetConnection(v DedicatedBandwidthConfigurationConnection)`

SetConnection sets Connection field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


