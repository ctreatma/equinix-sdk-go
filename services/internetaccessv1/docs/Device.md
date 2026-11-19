# Device

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**Alias** | Pointer to **string** |  | [optional] 
**Vendor** | Pointer to **string** |  | [optional] 
**ConfigModel** | [**DeviceConfigModel**](DeviceConfigModel.md) |  | 
**Redundancy** | Pointer to [**DeviceRedundancy**](DeviceRedundancy.md) |  | [optional] 

## Methods

### NewDevice

`func NewDevice(name string, configModel DeviceConfigModel, ) *Device`

NewDevice instantiates a new Device object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceWithDefaults

`func NewDeviceWithDefaults() *Device`

NewDeviceWithDefaults instantiates a new Device object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Device) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Device) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Device) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *Device) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Device) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Device) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Device) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAlias

`func (o *Device) GetAlias() string`

GetAlias returns the Alias field if non-nil, zero value otherwise.

### GetAliasOk

`func (o *Device) GetAliasOk() (*string, bool)`

GetAliasOk returns a tuple with the Alias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlias

`func (o *Device) SetAlias(v string)`

SetAlias sets Alias field to given value.

### HasAlias

`func (o *Device) HasAlias() bool`

HasAlias returns a boolean if a field has been set.

### GetVendor

`func (o *Device) GetVendor() string`

GetVendor returns the Vendor field if non-nil, zero value otherwise.

### GetVendorOk

`func (o *Device) GetVendorOk() (*string, bool)`

GetVendorOk returns a tuple with the Vendor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendor

`func (o *Device) SetVendor(v string)`

SetVendor sets Vendor field to given value.

### HasVendor

`func (o *Device) HasVendor() bool`

HasVendor returns a boolean if a field has been set.

### GetConfigModel

`func (o *Device) GetConfigModel() DeviceConfigModel`

GetConfigModel returns the ConfigModel field if non-nil, zero value otherwise.

### GetConfigModelOk

`func (o *Device) GetConfigModelOk() (*DeviceConfigModel, bool)`

GetConfigModelOk returns a tuple with the ConfigModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigModel

`func (o *Device) SetConfigModel(v DeviceConfigModel)`

SetConfigModel sets ConfigModel field to given value.


### GetRedundancy

`func (o *Device) GetRedundancy() DeviceRedundancy`

GetRedundancy returns the Redundancy field if non-nil, zero value otherwise.

### GetRedundancyOk

`func (o *Device) GetRedundancyOk() (*DeviceRedundancy, bool)`

GetRedundancyOk returns a tuple with the Redundancy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedundancy

`func (o *Device) SetRedundancy(v DeviceRedundancy)`

SetRedundancy sets Redundancy field to given value.

### HasRedundancy

`func (o *Device) HasRedundancy() bool`

HasRedundancy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


