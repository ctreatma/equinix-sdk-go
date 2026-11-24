# PriceCharge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PriceChargeType**](PriceChargeType.md) |  | 
**Price** | **float32** | Offering price | 
**Unit** | [**PriceChargeUnit**](PriceChargeUnit.md) |  | 

## Methods

### NewPriceCharge

`func NewPriceCharge(type_ PriceChargeType, price float32, unit PriceChargeUnit, ) *PriceCharge`

NewPriceCharge instantiates a new PriceCharge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceChargeWithDefaults

`func NewPriceChargeWithDefaults() *PriceCharge`

NewPriceChargeWithDefaults instantiates a new PriceCharge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PriceCharge) GetType() PriceChargeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PriceCharge) GetTypeOk() (*PriceChargeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PriceCharge) SetType(v PriceChargeType)`

SetType sets Type field to given value.


### GetPrice

`func (o *PriceCharge) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *PriceCharge) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *PriceCharge) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetUnit

`func (o *PriceCharge) GetUnit() PriceChargeUnit`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PriceCharge) GetUnitOk() (*PriceChargeUnit, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PriceCharge) SetUnit(v PriceChargeUnit)`

SetUnit sets Unit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


