# PriceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingCommencementDateTime** | Pointer to **time.Time** | Billing commencement date. | [optional] 
**BillingEnabled** | Pointer to **bool** | Whether billing is enabled. | [optional] 
**Charges** | Pointer to [**[]Charges**](Charges.md) | An array of the monthly recurring charges. | [optional] 
**Currency** | Pointer to **string** | Currency. | [optional] 

## Methods

### NewPriceResponse

`func NewPriceResponse() *PriceResponse`

NewPriceResponse instantiates a new PriceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceResponseWithDefaults

`func NewPriceResponseWithDefaults() *PriceResponse`

NewPriceResponseWithDefaults instantiates a new PriceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillingCommencementDateTime

`func (o *PriceResponse) GetBillingCommencementDateTime() time.Time`

GetBillingCommencementDateTime returns the BillingCommencementDateTime field if non-nil, zero value otherwise.

### GetBillingCommencementDateTimeOk

`func (o *PriceResponse) GetBillingCommencementDateTimeOk() (*time.Time, bool)`

GetBillingCommencementDateTimeOk returns a tuple with the BillingCommencementDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCommencementDateTime

`func (o *PriceResponse) SetBillingCommencementDateTime(v time.Time)`

SetBillingCommencementDateTime sets BillingCommencementDateTime field to given value.

### HasBillingCommencementDateTime

`func (o *PriceResponse) HasBillingCommencementDateTime() bool`

HasBillingCommencementDateTime returns a boolean if a field has been set.

### GetBillingEnabled

`func (o *PriceResponse) GetBillingEnabled() bool`

GetBillingEnabled returns the BillingEnabled field if non-nil, zero value otherwise.

### GetBillingEnabledOk

`func (o *PriceResponse) GetBillingEnabledOk() (*bool, bool)`

GetBillingEnabledOk returns a tuple with the BillingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingEnabled

`func (o *PriceResponse) SetBillingEnabled(v bool)`

SetBillingEnabled sets BillingEnabled field to given value.

### HasBillingEnabled

`func (o *PriceResponse) HasBillingEnabled() bool`

HasBillingEnabled returns a boolean if a field has been set.

### GetCharges

`func (o *PriceResponse) GetCharges() []Charges`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *PriceResponse) GetChargesOk() (*[]Charges, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *PriceResponse) SetCharges(v []Charges)`

SetCharges sets Charges field to given value.

### HasCharges

`func (o *PriceResponse) HasCharges() bool`

HasCharges returns a boolean if a field has been set.

### GetCurrency

`func (o *PriceResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PriceResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PriceResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *PriceResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


