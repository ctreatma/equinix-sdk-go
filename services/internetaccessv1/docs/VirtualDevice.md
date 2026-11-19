# VirtualDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Type** | Pointer to [**VirtualDeviceType**](VirtualDeviceType.md) |  | [optional] 

## Methods

### NewVirtualDevice

`func NewVirtualDevice(uuid string, ) *VirtualDevice`

NewVirtualDevice instantiates a new VirtualDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVirtualDeviceWithDefaults

`func NewVirtualDeviceWithDefaults() *VirtualDevice`

NewVirtualDeviceWithDefaults instantiates a new VirtualDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *VirtualDevice) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *VirtualDevice) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *VirtualDevice) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *VirtualDevice) GetType() VirtualDeviceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VirtualDevice) GetTypeOk() (*VirtualDeviceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VirtualDevice) SetType(v VirtualDeviceType)`

SetType sets Type field to given value.

### HasType

`func (o *VirtualDevice) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


