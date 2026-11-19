# PricingDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **float32** | To be used with &#x60;valueType&#x60; and &#x60;type&#x60;. Can be used to denote price or discount for an order or service | [optional] 
**ValueType** | Pointer to [**PricingDetailsValueType**](PricingDetailsValueType.md) |  | [optional] 
**Type** | Pointer to [**PricingDetailsType**](PricingDetailsType.md) |  | [optional] 

## Methods

### NewPricingDetails

`func NewPricingDetails() *PricingDetails`

NewPricingDetails instantiates a new PricingDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPricingDetailsWithDefaults

`func NewPricingDetailsWithDefaults() *PricingDetails`

NewPricingDetailsWithDefaults instantiates a new PricingDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *PricingDetails) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PricingDetails) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PricingDetails) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *PricingDetails) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetValueType

`func (o *PricingDetails) GetValueType() PricingDetailsValueType`

GetValueType returns the ValueType field if non-nil, zero value otherwise.

### GetValueTypeOk

`func (o *PricingDetails) GetValueTypeOk() (*PricingDetailsValueType, bool)`

GetValueTypeOk returns a tuple with the ValueType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueType

`func (o *PricingDetails) SetValueType(v PricingDetailsValueType)`

SetValueType sets ValueType field to given value.

### HasValueType

`func (o *PricingDetails) HasValueType() bool`

HasValueType returns a boolean if a field has been set.

### GetType

`func (o *PricingDetails) GetType() PricingDetailsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PricingDetails) GetTypeOk() (*PricingDetailsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PricingDetails) SetType(v PricingDetailsType)`

SetType sets Type field to given value.

### HasType

`func (o *PricingDetails) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


