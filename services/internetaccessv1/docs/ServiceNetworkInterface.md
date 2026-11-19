# ServiceNetworkInterface

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**IfIndex** | Pointer to **int32** |  | [optional] 

## Methods

### NewServiceNetworkInterface

`func NewServiceNetworkInterface(id string, ) *ServiceNetworkInterface`

NewServiceNetworkInterface instantiates a new ServiceNetworkInterface object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceNetworkInterfaceWithDefaults

`func NewServiceNetworkInterfaceWithDefaults() *ServiceNetworkInterface`

NewServiceNetworkInterfaceWithDefaults instantiates a new ServiceNetworkInterface object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ServiceNetworkInterface) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ServiceNetworkInterface) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ServiceNetworkInterface) SetId(v string)`

SetId sets Id field to given value.


### GetIfIndex

`func (o *ServiceNetworkInterface) GetIfIndex() int32`

GetIfIndex returns the IfIndex field if non-nil, zero value otherwise.

### GetIfIndexOk

`func (o *ServiceNetworkInterface) GetIfIndexOk() (*int32, bool)`

GetIfIndexOk returns a tuple with the IfIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIfIndex

`func (o *ServiceNetworkInterface) SetIfIndex(v int32)`

SetIfIndex sets IfIndex field to given value.

### HasIfIndex

`func (o *ServiceNetworkInterface) HasIfIndex() bool`

HasIfIndex returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


