# ConfigurationReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ThresholdValue** | Pointer to **string** | threshold value | [optional] 
**ThresholdValueDisplayName** | Pointer to **string** | threshold display value | [optional] 
**UnitOfMeasurement** | Pointer to **string** | unit of measurement | [optional] 
**ThresholdType** | Pointer to [**ConfigurationReadModelThresholdType**](ConfigurationReadModelThresholdType.md) |  | [optional] 
**ConditionName** | Pointer to [**ConfigurationReadModelConditionName**](ConfigurationReadModelConditionName.md) |  | [optional] 
**CustomerVisible** | Pointer to **bool** | asset is customer visible | [optional] 
**ConfigurationVersion** | Pointer to **string** | alert configuration version | [optional] 

## Methods

### NewConfigurationReadModel

`func NewConfigurationReadModel() *ConfigurationReadModel`

NewConfigurationReadModel instantiates a new ConfigurationReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigurationReadModelWithDefaults

`func NewConfigurationReadModelWithDefaults() *ConfigurationReadModel`

NewConfigurationReadModelWithDefaults instantiates a new ConfigurationReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetThresholdValue

`func (o *ConfigurationReadModel) GetThresholdValue() string`

GetThresholdValue returns the ThresholdValue field if non-nil, zero value otherwise.

### GetThresholdValueOk

`func (o *ConfigurationReadModel) GetThresholdValueOk() (*string, bool)`

GetThresholdValueOk returns a tuple with the ThresholdValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholdValue

`func (o *ConfigurationReadModel) SetThresholdValue(v string)`

SetThresholdValue sets ThresholdValue field to given value.

### HasThresholdValue

`func (o *ConfigurationReadModel) HasThresholdValue() bool`

HasThresholdValue returns a boolean if a field has been set.

### GetThresholdValueDisplayName

`func (o *ConfigurationReadModel) GetThresholdValueDisplayName() string`

GetThresholdValueDisplayName returns the ThresholdValueDisplayName field if non-nil, zero value otherwise.

### GetThresholdValueDisplayNameOk

`func (o *ConfigurationReadModel) GetThresholdValueDisplayNameOk() (*string, bool)`

GetThresholdValueDisplayNameOk returns a tuple with the ThresholdValueDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholdValueDisplayName

`func (o *ConfigurationReadModel) SetThresholdValueDisplayName(v string)`

SetThresholdValueDisplayName sets ThresholdValueDisplayName field to given value.

### HasThresholdValueDisplayName

`func (o *ConfigurationReadModel) HasThresholdValueDisplayName() bool`

HasThresholdValueDisplayName returns a boolean if a field has been set.

### GetUnitOfMeasurement

`func (o *ConfigurationReadModel) GetUnitOfMeasurement() string`

GetUnitOfMeasurement returns the UnitOfMeasurement field if non-nil, zero value otherwise.

### GetUnitOfMeasurementOk

`func (o *ConfigurationReadModel) GetUnitOfMeasurementOk() (*string, bool)`

GetUnitOfMeasurementOk returns a tuple with the UnitOfMeasurement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitOfMeasurement

`func (o *ConfigurationReadModel) SetUnitOfMeasurement(v string)`

SetUnitOfMeasurement sets UnitOfMeasurement field to given value.

### HasUnitOfMeasurement

`func (o *ConfigurationReadModel) HasUnitOfMeasurement() bool`

HasUnitOfMeasurement returns a boolean if a field has been set.

### GetThresholdType

`func (o *ConfigurationReadModel) GetThresholdType() ConfigurationReadModelThresholdType`

GetThresholdType returns the ThresholdType field if non-nil, zero value otherwise.

### GetThresholdTypeOk

`func (o *ConfigurationReadModel) GetThresholdTypeOk() (*ConfigurationReadModelThresholdType, bool)`

GetThresholdTypeOk returns a tuple with the ThresholdType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThresholdType

`func (o *ConfigurationReadModel) SetThresholdType(v ConfigurationReadModelThresholdType)`

SetThresholdType sets ThresholdType field to given value.

### HasThresholdType

`func (o *ConfigurationReadModel) HasThresholdType() bool`

HasThresholdType returns a boolean if a field has been set.

### GetConditionName

`func (o *ConfigurationReadModel) GetConditionName() ConfigurationReadModelConditionName`

GetConditionName returns the ConditionName field if non-nil, zero value otherwise.

### GetConditionNameOk

`func (o *ConfigurationReadModel) GetConditionNameOk() (*ConfigurationReadModelConditionName, bool)`

GetConditionNameOk returns a tuple with the ConditionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionName

`func (o *ConfigurationReadModel) SetConditionName(v ConfigurationReadModelConditionName)`

SetConditionName sets ConditionName field to given value.

### HasConditionName

`func (o *ConfigurationReadModel) HasConditionName() bool`

HasConditionName returns a boolean if a field has been set.

### GetCustomerVisible

`func (o *ConfigurationReadModel) GetCustomerVisible() bool`

GetCustomerVisible returns the CustomerVisible field if non-nil, zero value otherwise.

### GetCustomerVisibleOk

`func (o *ConfigurationReadModel) GetCustomerVisibleOk() (*bool, bool)`

GetCustomerVisibleOk returns a tuple with the CustomerVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerVisible

`func (o *ConfigurationReadModel) SetCustomerVisible(v bool)`

SetCustomerVisible sets CustomerVisible field to given value.

### HasCustomerVisible

`func (o *ConfigurationReadModel) HasCustomerVisible() bool`

HasCustomerVisible returns a boolean if a field has been set.

### GetConfigurationVersion

`func (o *ConfigurationReadModel) GetConfigurationVersion() string`

GetConfigurationVersion returns the ConfigurationVersion field if non-nil, zero value otherwise.

### GetConfigurationVersionOk

`func (o *ConfigurationReadModel) GetConfigurationVersionOk() (*string, bool)`

GetConfigurationVersionOk returns a tuple with the ConfigurationVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigurationVersion

`func (o *ConfigurationReadModel) SetConfigurationVersion(v string)`

SetConfigurationVersion sets ConfigurationVersion field to given value.

### HasConfigurationVersion

`func (o *ConfigurationReadModel) HasConfigurationVersion() bool`

HasConfigurationVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


