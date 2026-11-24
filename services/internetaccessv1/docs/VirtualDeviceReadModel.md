# VirtualDeviceReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Virtual device identifier | 
**Type** | Pointer to [**VirtualDeviceReadModelType**](VirtualDeviceReadModelType.md) |  | [optional] 
**Href** | Pointer to **string** | Virtual device URI | [optional] 

## Methods

### NewVirtualDeviceReadModel

`func NewVirtualDeviceReadModel(uuid string, ) *VirtualDeviceReadModel`

NewVirtualDeviceReadModel instantiates a new VirtualDeviceReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVirtualDeviceReadModelWithDefaults

`func NewVirtualDeviceReadModelWithDefaults() *VirtualDeviceReadModel`

NewVirtualDeviceReadModelWithDefaults instantiates a new VirtualDeviceReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *VirtualDeviceReadModel) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *VirtualDeviceReadModel) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *VirtualDeviceReadModel) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *VirtualDeviceReadModel) GetType() VirtualDeviceReadModelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VirtualDeviceReadModel) GetTypeOk() (*VirtualDeviceReadModelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VirtualDeviceReadModel) SetType(v VirtualDeviceReadModelType)`

SetType sets Type field to given value.

### HasType

`func (o *VirtualDeviceReadModel) HasType() bool`

HasType returns a boolean if a field has been set.

### GetHref

`func (o *VirtualDeviceReadModel) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *VirtualDeviceReadModel) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *VirtualDeviceReadModel) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *VirtualDeviceReadModel) HasHref() bool`

HasHref returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


