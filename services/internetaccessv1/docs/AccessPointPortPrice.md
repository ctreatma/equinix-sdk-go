# AccessPointPortPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** |  | [optional] 
**PhysicalPort** | Pointer to [**AccessPointPhysicalPortPrice**](AccessPointPhysicalPortPrice.md) |  | [optional] 
**PhysicalPortQuantity** | **int32** |  | 

## Methods

### NewAccessPointPortPrice

`func NewAccessPointPortPrice(physicalPortQuantity int32, ) *AccessPointPortPrice`

NewAccessPointPortPrice instantiates a new AccessPointPortPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPointPortPriceWithDefaults

`func NewAccessPointPortPriceWithDefaults() *AccessPointPortPrice`

NewAccessPointPortPriceWithDefaults instantiates a new AccessPointPortPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *AccessPointPortPrice) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AccessPointPortPrice) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AccessPointPortPrice) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *AccessPointPortPrice) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetPhysicalPort

`func (o *AccessPointPortPrice) GetPhysicalPort() AccessPointPhysicalPortPrice`

GetPhysicalPort returns the PhysicalPort field if non-nil, zero value otherwise.

### GetPhysicalPortOk

`func (o *AccessPointPortPrice) GetPhysicalPortOk() (*AccessPointPhysicalPortPrice, bool)`

GetPhysicalPortOk returns a tuple with the PhysicalPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalPort

`func (o *AccessPointPortPrice) SetPhysicalPort(v AccessPointPhysicalPortPrice)`

SetPhysicalPort sets PhysicalPort field to given value.

### HasPhysicalPort

`func (o *AccessPointPortPrice) HasPhysicalPort() bool`

HasPhysicalPort returns a boolean if a field has been set.

### GetPhysicalPortQuantity

`func (o *AccessPointPortPrice) GetPhysicalPortQuantity() int32`

GetPhysicalPortQuantity returns the PhysicalPortQuantity field if non-nil, zero value otherwise.

### GetPhysicalPortQuantityOk

`func (o *AccessPointPortPrice) GetPhysicalPortQuantityOk() (*int32, bool)`

GetPhysicalPortQuantityOk returns a tuple with the PhysicalPortQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalPortQuantity

`func (o *AccessPointPortPrice) SetPhysicalPortQuantity(v int32)`

SetPhysicalPortQuantity sets PhysicalPortQuantity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


