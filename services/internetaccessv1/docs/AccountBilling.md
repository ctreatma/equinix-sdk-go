# AccountBilling

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SignatureRequired** | **bool** | Whether the signature is required | 
**PoExempted** | **bool** | Whether the purchase order has been exempted | 
**PoBearing** | **bool** | Whether the purchase order is required | 
**Currency** | [**CurrencyCode**](CurrencyCode.md) |  | 

## Methods

### NewAccountBilling

`func NewAccountBilling(signatureRequired bool, poExempted bool, poBearing bool, currency CurrencyCode, ) *AccountBilling`

NewAccountBilling instantiates a new AccountBilling object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountBillingWithDefaults

`func NewAccountBillingWithDefaults() *AccountBilling`

NewAccountBillingWithDefaults instantiates a new AccountBilling object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSignatureRequired

`func (o *AccountBilling) GetSignatureRequired() bool`

GetSignatureRequired returns the SignatureRequired field if non-nil, zero value otherwise.

### GetSignatureRequiredOk

`func (o *AccountBilling) GetSignatureRequiredOk() (*bool, bool)`

GetSignatureRequiredOk returns a tuple with the SignatureRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureRequired

`func (o *AccountBilling) SetSignatureRequired(v bool)`

SetSignatureRequired sets SignatureRequired field to given value.


### GetPoExempted

`func (o *AccountBilling) GetPoExempted() bool`

GetPoExempted returns the PoExempted field if non-nil, zero value otherwise.

### GetPoExemptedOk

`func (o *AccountBilling) GetPoExemptedOk() (*bool, bool)`

GetPoExemptedOk returns a tuple with the PoExempted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoExempted

`func (o *AccountBilling) SetPoExempted(v bool)`

SetPoExempted sets PoExempted field to given value.


### GetPoBearing

`func (o *AccountBilling) GetPoBearing() bool`

GetPoBearing returns the PoBearing field if non-nil, zero value otherwise.

### GetPoBearingOk

`func (o *AccountBilling) GetPoBearingOk() (*bool, bool)`

GetPoBearingOk returns a tuple with the PoBearing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoBearing

`func (o *AccountBilling) SetPoBearing(v bool)`

SetPoBearing sets PoBearing field to given value.


### GetCurrency

`func (o *AccountBilling) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *AccountBilling) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *AccountBilling) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


