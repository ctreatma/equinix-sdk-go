# Port

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | Pointer to **[]string** |  | [optional] 
**Type** | [**PortType**](PortType.md) |  | 
**Uuid** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** | Name of the port provided by the client  | [optional] 
**Description** | Pointer to **string** | Description of the port provided by the client  | [optional] 
**Bandwidth** | Pointer to **int32** | Entity bandwidth in Mbps  | [optional] 
**Encapsulation** | Pointer to [**PortEncapsulation**](PortEncapsulation.md) |  | [optional] 
**Location** | Pointer to [**PortLocation**](PortLocation.md) |  | [optional] 
**Lag** | Pointer to [**PortLag**](PortLag.md) |  | [optional] 
**ConnectivitySource** | Pointer to [**PortConnectivitySource**](PortConnectivitySource.md) |  | [optional] 
**PhysicalPorts** | Pointer to [**[]PhysicalPort**](PhysicalPort.md) | Collection of the Physical Ports  | [optional] 

## Methods

### NewPort

`func NewPort(type_ PortType, ) *Port`

NewPort instantiates a new Port object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortWithDefaults

`func NewPortWithDefaults() *Port`

NewPortWithDefaults instantiates a new Port object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *Port) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Port) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Port) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *Port) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetType

`func (o *Port) GetType() PortType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Port) GetTypeOk() (*PortType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Port) SetType(v PortType)`

SetType sets Type field to given value.


### GetUuid

`func (o *Port) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Port) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Port) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *Port) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetName

`func (o *Port) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Port) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Port) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Port) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *Port) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Port) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Port) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Port) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBandwidth

`func (o *Port) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *Port) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *Port) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.

### HasBandwidth

`func (o *Port) HasBandwidth() bool`

HasBandwidth returns a boolean if a field has been set.

### GetEncapsulation

`func (o *Port) GetEncapsulation() PortEncapsulation`

GetEncapsulation returns the Encapsulation field if non-nil, zero value otherwise.

### GetEncapsulationOk

`func (o *Port) GetEncapsulationOk() (*PortEncapsulation, bool)`

GetEncapsulationOk returns a tuple with the Encapsulation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncapsulation

`func (o *Port) SetEncapsulation(v PortEncapsulation)`

SetEncapsulation sets Encapsulation field to given value.

### HasEncapsulation

`func (o *Port) HasEncapsulation() bool`

HasEncapsulation returns a boolean if a field has been set.

### GetLocation

`func (o *Port) GetLocation() PortLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *Port) GetLocationOk() (*PortLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *Port) SetLocation(v PortLocation)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *Port) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetLag

`func (o *Port) GetLag() PortLag`

GetLag returns the Lag field if non-nil, zero value otherwise.

### GetLagOk

`func (o *Port) GetLagOk() (*PortLag, bool)`

GetLagOk returns a tuple with the Lag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLag

`func (o *Port) SetLag(v PortLag)`

SetLag sets Lag field to given value.

### HasLag

`func (o *Port) HasLag() bool`

HasLag returns a boolean if a field has been set.

### GetConnectivitySource

`func (o *Port) GetConnectivitySource() PortConnectivitySource`

GetConnectivitySource returns the ConnectivitySource field if non-nil, zero value otherwise.

### GetConnectivitySourceOk

`func (o *Port) GetConnectivitySourceOk() (*PortConnectivitySource, bool)`

GetConnectivitySourceOk returns a tuple with the ConnectivitySource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectivitySource

`func (o *Port) SetConnectivitySource(v PortConnectivitySource)`

SetConnectivitySource sets ConnectivitySource field to given value.

### HasConnectivitySource

`func (o *Port) HasConnectivitySource() bool`

HasConnectivitySource returns a boolean if a field has been set.

### GetPhysicalPorts

`func (o *Port) GetPhysicalPorts() []PhysicalPort`

GetPhysicalPorts returns the PhysicalPorts field if non-nil, zero value otherwise.

### GetPhysicalPortsOk

`func (o *Port) GetPhysicalPortsOk() (*[]PhysicalPort, bool)`

GetPhysicalPortsOk returns a tuple with the PhysicalPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalPorts

`func (o *Port) SetPhysicalPorts(v []PhysicalPort)`

SetPhysicalPorts sets PhysicalPorts field to given value.

### HasPhysicalPorts

`func (o *Port) HasPhysicalPorts() bool`

HasPhysicalPorts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


