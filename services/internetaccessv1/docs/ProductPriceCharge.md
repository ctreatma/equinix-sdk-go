# ProductPriceCharge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PriceChargeType**](PriceChargeType.md) |  | 
**Price** | **float32** | Offering price | 
**Unit** | [**PriceChargeUnit**](PriceChargeUnit.md) |  | 
**Product** | Pointer to [**ProductInfo**](ProductInfo.md) |  | [optional] 

## Methods

### NewProductPriceCharge

`func NewProductPriceCharge(type_ PriceChargeType, price float32, unit PriceChargeUnit, ) *ProductPriceCharge`

NewProductPriceCharge instantiates a new ProductPriceCharge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductPriceChargeWithDefaults

`func NewProductPriceChargeWithDefaults() *ProductPriceCharge`

NewProductPriceChargeWithDefaults instantiates a new ProductPriceCharge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ProductPriceCharge) GetType() PriceChargeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProductPriceCharge) GetTypeOk() (*PriceChargeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProductPriceCharge) SetType(v PriceChargeType)`

SetType sets Type field to given value.


### GetPrice

`func (o *ProductPriceCharge) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ProductPriceCharge) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ProductPriceCharge) SetPrice(v float32)`

SetPrice sets Price field to given value.


### GetUnit

`func (o *ProductPriceCharge) GetUnit() PriceChargeUnit`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductPriceCharge) GetUnitOk() (*PriceChargeUnit, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductPriceCharge) SetUnit(v PriceChargeUnit)`

SetUnit sets Unit field to given value.


### GetProduct

`func (o *ProductPriceCharge) GetProduct() ProductInfo`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *ProductPriceCharge) GetProductOk() (*ProductInfo, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *ProductPriceCharge) SetProduct(v ProductInfo)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *ProductPriceCharge) HasProduct() bool`

HasProduct returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


