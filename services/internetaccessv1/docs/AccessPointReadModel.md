# AccessPointReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**AccessPointReadModelType**](AccessPointReadModelType.md) |  | 
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Location** | Pointer to [**LocationReadModel**](LocationReadModel.md) |  | [optional] 
**Port** | Pointer to [**PortReadModel**](PortReadModel.md) |  | [optional] 
**LinkProtocol** | Pointer to [**LinkProtocol**](LinkProtocol.md) |  | [optional] 
**VirtualDevice** | Pointer to [**VirtualDeviceReadModel**](VirtualDeviceReadModel.md) |  | [optional] 

## Methods

### NewAccessPointReadModel

`func NewAccessPointReadModel(type_ AccessPointReadModelType, ) *AccessPointReadModel`

NewAccessPointReadModel instantiates a new AccessPointReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPointReadModelWithDefaults

`func NewAccessPointReadModelWithDefaults() *AccessPointReadModel`

NewAccessPointReadModelWithDefaults instantiates a new AccessPointReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AccessPointReadModel) GetType() AccessPointReadModelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccessPointReadModel) GetTypeOk() (*AccessPointReadModelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccessPointReadModel) SetType(v AccessPointReadModelType)`

SetType sets Type field to given value.


### GetName

`func (o *AccessPointReadModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AccessPointReadModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AccessPointReadModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AccessPointReadModel) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *AccessPointReadModel) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccessPointReadModel) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccessPointReadModel) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccessPointReadModel) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLocation

`func (o *AccessPointReadModel) GetLocation() LocationReadModel`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *AccessPointReadModel) GetLocationOk() (*LocationReadModel, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *AccessPointReadModel) SetLocation(v LocationReadModel)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *AccessPointReadModel) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetPort

`func (o *AccessPointReadModel) GetPort() PortReadModel`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *AccessPointReadModel) GetPortOk() (*PortReadModel, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *AccessPointReadModel) SetPort(v PortReadModel)`

SetPort sets Port field to given value.

### HasPort

`func (o *AccessPointReadModel) HasPort() bool`

HasPort returns a boolean if a field has been set.

### GetLinkProtocol

`func (o *AccessPointReadModel) GetLinkProtocol() LinkProtocol`

GetLinkProtocol returns the LinkProtocol field if non-nil, zero value otherwise.

### GetLinkProtocolOk

`func (o *AccessPointReadModel) GetLinkProtocolOk() (*LinkProtocol, bool)`

GetLinkProtocolOk returns a tuple with the LinkProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkProtocol

`func (o *AccessPointReadModel) SetLinkProtocol(v LinkProtocol)`

SetLinkProtocol sets LinkProtocol field to given value.

### HasLinkProtocol

`func (o *AccessPointReadModel) HasLinkProtocol() bool`

HasLinkProtocol returns a boolean if a field has been set.

### GetVirtualDevice

`func (o *AccessPointReadModel) GetVirtualDevice() VirtualDeviceReadModel`

GetVirtualDevice returns the VirtualDevice field if non-nil, zero value otherwise.

### GetVirtualDeviceOk

`func (o *AccessPointReadModel) GetVirtualDeviceOk() (*VirtualDeviceReadModel, bool)`

GetVirtualDeviceOk returns a tuple with the VirtualDevice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualDevice

`func (o *AccessPointReadModel) SetVirtualDevice(v VirtualDeviceReadModel)`

SetVirtualDevice sets VirtualDevice field to given value.

### HasVirtualDevice

`func (o *AccessPointReadModel) HasVirtualDevice() bool`

HasVirtualDevice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


