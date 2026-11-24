# Account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Number** | **string** | Account Number | 
**Name** | **string** | Name of Account | 
**PricingEnabled** | Pointer to **bool** | Pricing enabled for account | [optional] 
**PricingEnforced** | Pointer to **bool** | Pricing enforced for account | [optional] 
**PoTracking** | Pointer to **bool** | PO Tracking Account | [optional] 
**Cabinets** | Pointer to [**[]Cabinets**](Cabinets.md) | List of Cabinets | [optional] 

## Methods

### NewAccount

`func NewAccount(number string, name string, ) *Account`

NewAccount instantiates a new Account object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountWithDefaults

`func NewAccountWithDefaults() *Account`

NewAccountWithDefaults instantiates a new Account object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumber

`func (o *Account) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *Account) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *Account) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetName

`func (o *Account) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Account) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Account) SetName(v string)`

SetName sets Name field to given value.


### GetPricingEnabled

`func (o *Account) GetPricingEnabled() bool`

GetPricingEnabled returns the PricingEnabled field if non-nil, zero value otherwise.

### GetPricingEnabledOk

`func (o *Account) GetPricingEnabledOk() (*bool, bool)`

GetPricingEnabledOk returns a tuple with the PricingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingEnabled

`func (o *Account) SetPricingEnabled(v bool)`

SetPricingEnabled sets PricingEnabled field to given value.

### HasPricingEnabled

`func (o *Account) HasPricingEnabled() bool`

HasPricingEnabled returns a boolean if a field has been set.

### GetPricingEnforced

`func (o *Account) GetPricingEnforced() bool`

GetPricingEnforced returns the PricingEnforced field if non-nil, zero value otherwise.

### GetPricingEnforcedOk

`func (o *Account) GetPricingEnforcedOk() (*bool, bool)`

GetPricingEnforcedOk returns a tuple with the PricingEnforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingEnforced

`func (o *Account) SetPricingEnforced(v bool)`

SetPricingEnforced sets PricingEnforced field to given value.

### HasPricingEnforced

`func (o *Account) HasPricingEnforced() bool`

HasPricingEnforced returns a boolean if a field has been set.

### GetPoTracking

`func (o *Account) GetPoTracking() bool`

GetPoTracking returns the PoTracking field if non-nil, zero value otherwise.

### GetPoTrackingOk

`func (o *Account) GetPoTrackingOk() (*bool, bool)`

GetPoTrackingOk returns a tuple with the PoTracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoTracking

`func (o *Account) SetPoTracking(v bool)`

SetPoTracking sets PoTracking field to given value.

### HasPoTracking

`func (o *Account) HasPoTracking() bool`

HasPoTracking returns a boolean if a field has been set.

### GetCabinets

`func (o *Account) GetCabinets() []Cabinets`

GetCabinets returns the Cabinets field if non-nil, zero value otherwise.

### GetCabinetsOk

`func (o *Account) GetCabinetsOk() (*[]Cabinets, bool)`

GetCabinetsOk returns a tuple with the Cabinets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinets

`func (o *Account) SetCabinets(v []Cabinets)`

SetCabinets sets Cabinets field to given value.

### HasCabinets

`func (o *Account) HasCabinets() bool`

HasCabinets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


