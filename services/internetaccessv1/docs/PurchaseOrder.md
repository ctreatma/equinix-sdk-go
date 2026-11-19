# PurchaseOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PurchaseOrderType**](PurchaseOrderType.md) |  | 
**Number** | **string** | Purchase order number | 
**Account** | [**PurchaseOrderAccount**](PurchaseOrderAccount.md) |  | 
**Categories** | [**[]PurchaseOrderCategoriesInner**](PurchaseOrderCategoriesInner.md) |  | 
**Locations** | [**[]PurchaseOrderLocations**](PurchaseOrderLocations.md) |  | 
**Amount** | **float64** | Amount | 
**StartDate** | Pointer to **string** | Start date in YYYY-MM-DD format | [optional] 
**EndDate** | Pointer to **string** | End date in YYYY-MM-DD format | [optional] 
**Description** | Pointer to **string** | Purchase order description | [optional] 
**Draft** | **bool** | Is draft | 
**Status** | Pointer to [**PurchaseOrderStatus**](PurchaseOrderStatus.md) |  | [optional] 
**Currency** | [**CurrencyCode**](CurrencyCode.md) |  | 

## Methods

### NewPurchaseOrder

`func NewPurchaseOrder(type_ PurchaseOrderType, number string, account PurchaseOrderAccount, categories []PurchaseOrderCategoriesInner, locations []PurchaseOrderLocations, amount float64, draft bool, currency CurrencyCode, ) *PurchaseOrder`

NewPurchaseOrder instantiates a new PurchaseOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderWithDefaults

`func NewPurchaseOrderWithDefaults() *PurchaseOrder`

NewPurchaseOrderWithDefaults instantiates a new PurchaseOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PurchaseOrder) GetType() PurchaseOrderType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrder) GetTypeOk() (*PurchaseOrderType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrder) SetType(v PurchaseOrderType)`

SetType sets Type field to given value.


### GetNumber

`func (o *PurchaseOrder) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PurchaseOrder) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PurchaseOrder) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetAccount

`func (o *PurchaseOrder) GetAccount() PurchaseOrderAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *PurchaseOrder) GetAccountOk() (*PurchaseOrderAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *PurchaseOrder) SetAccount(v PurchaseOrderAccount)`

SetAccount sets Account field to given value.


### GetCategories

`func (o *PurchaseOrder) GetCategories() []PurchaseOrderCategoriesInner`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *PurchaseOrder) GetCategoriesOk() (*[]PurchaseOrderCategoriesInner, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *PurchaseOrder) SetCategories(v []PurchaseOrderCategoriesInner)`

SetCategories sets Categories field to given value.


### GetLocations

`func (o *PurchaseOrder) GetLocations() []PurchaseOrderLocations`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *PurchaseOrder) GetLocationsOk() (*[]PurchaseOrderLocations, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *PurchaseOrder) SetLocations(v []PurchaseOrderLocations)`

SetLocations sets Locations field to given value.


### GetAmount

`func (o *PurchaseOrder) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PurchaseOrder) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PurchaseOrder) SetAmount(v float64)`

SetAmount sets Amount field to given value.


### GetStartDate

`func (o *PurchaseOrder) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *PurchaseOrder) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *PurchaseOrder) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *PurchaseOrder) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetEndDate

`func (o *PurchaseOrder) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *PurchaseOrder) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *PurchaseOrder) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *PurchaseOrder) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetDescription

`func (o *PurchaseOrder) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PurchaseOrder) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PurchaseOrder) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PurchaseOrder) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDraft

`func (o *PurchaseOrder) GetDraft() bool`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *PurchaseOrder) GetDraftOk() (*bool, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *PurchaseOrder) SetDraft(v bool)`

SetDraft sets Draft field to given value.


### GetStatus

`func (o *PurchaseOrder) GetStatus() PurchaseOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PurchaseOrder) GetStatusOk() (*PurchaseOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PurchaseOrder) SetStatus(v PurchaseOrderStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PurchaseOrder) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCurrency

`func (o *PurchaseOrder) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PurchaseOrder) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PurchaseOrder) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


