# ConnectionPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | Unique identifier assigned to the connection. Either the uuid or the remaining attributes must be supplied. | [optional] 
**Type** | [**ConnectionType**](ConnectionType.md) |  | 
**ASide** | [**ASidePrice**](ASidePrice.md) |  | 

## Methods

### NewConnectionPrice

`func NewConnectionPrice(type_ ConnectionType, aSide ASidePrice, ) *ConnectionPrice`

NewConnectionPrice instantiates a new ConnectionPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionPriceWithDefaults

`func NewConnectionPriceWithDefaults() *ConnectionPrice`

NewConnectionPriceWithDefaults instantiates a new ConnectionPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ConnectionPrice) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ConnectionPrice) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ConnectionPrice) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *ConnectionPrice) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *ConnectionPrice) GetType() ConnectionType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ConnectionPrice) GetTypeOk() (*ConnectionType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ConnectionPrice) SetType(v ConnectionType)`

SetType sets Type field to given value.


### GetASide

`func (o *ConnectionPrice) GetASide() ASidePrice`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *ConnectionPrice) GetASideOk() (*ASidePrice, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *ConnectionPrice) SetASide(v ASidePrice)`

SetASide sets ASide field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


