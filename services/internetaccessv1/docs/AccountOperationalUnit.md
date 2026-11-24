# AccountOperationalUnit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ibxs** | [**[]OperationalUnitIbxs**](OperationalUnitIbxs.md) |  | 
**Metros** | Pointer to [**[]OperationalUnitMetros**](OperationalUnitMetros.md) |  | [optional] 

## Methods

### NewAccountOperationalUnit

`func NewAccountOperationalUnit(ibxs []OperationalUnitIbxs, ) *AccountOperationalUnit`

NewAccountOperationalUnit instantiates a new AccountOperationalUnit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountOperationalUnitWithDefaults

`func NewAccountOperationalUnitWithDefaults() *AccountOperationalUnit`

NewAccountOperationalUnitWithDefaults instantiates a new AccountOperationalUnit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbxs

`func (o *AccountOperationalUnit) GetIbxs() []OperationalUnitIbxs`

GetIbxs returns the Ibxs field if non-nil, zero value otherwise.

### GetIbxsOk

`func (o *AccountOperationalUnit) GetIbxsOk() (*[]OperationalUnitIbxs, bool)`

GetIbxsOk returns a tuple with the Ibxs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxs

`func (o *AccountOperationalUnit) SetIbxs(v []OperationalUnitIbxs)`

SetIbxs sets Ibxs field to given value.


### GetMetros

`func (o *AccountOperationalUnit) GetMetros() []OperationalUnitMetros`

GetMetros returns the Metros field if non-nil, zero value otherwise.

### GetMetrosOk

`func (o *AccountOperationalUnit) GetMetrosOk() (*[]OperationalUnitMetros, bool)`

GetMetrosOk returns a tuple with the Metros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetros

`func (o *AccountOperationalUnit) SetMetros(v []OperationalUnitMetros)`

SetMetros sets Metros field to given value.

### HasMetros

`func (o *AccountOperationalUnit) HasMetros() bool`

HasMetros returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


