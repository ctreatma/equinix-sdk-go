# NetworkInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**IfIndex** | Pointer to **int32** |  | [optional] 
**Device** | Pointer to [**Device**](Device.md) |  | [optional] 

## Methods

### NewNetworkInterface

`func NewNetworkInterface(id string, ) *NetworkInterface`

NewNetworkInterface instantiates a new NetworkInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkInterfaceWithDefaults

`func NewNetworkInterfaceWithDefaults() *NetworkInterface`

NewNetworkInterfaceWithDefaults instantiates a new NetworkInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *NetworkInterface) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NetworkInterface) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NetworkInterface) SetId(v string)`

SetId sets Id field to given value.


### GetIfIndex

`func (o *NetworkInterface) GetIfIndex() int32`

GetIfIndex returns the IfIndex field if non-nil, zero value otherwise.

### GetIfIndexOk

`func (o *NetworkInterface) GetIfIndexOk() (*int32, bool)`

GetIfIndexOk returns a tuple with the IfIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIfIndex

`func (o *NetworkInterface) SetIfIndex(v int32)`

SetIfIndex sets IfIndex field to given value.

### HasIfIndex

`func (o *NetworkInterface) HasIfIndex() bool`

HasIfIndex returns a boolean if a field has been set.

### GetDevice

`func (o *NetworkInterface) GetDevice() Device`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *NetworkInterface) GetDeviceOk() (*Device, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *NetworkInterface) SetDevice(v Device)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *NetworkInterface) HasDevice() bool`

HasDevice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


