# Price

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | **string** | An absolute URL that returns specified pricing data | 
**Type** | [**ProductType**](ProductType.md) |  | 
**Code** | **string** | Equinix-assigned product code | 
**Name** | **string** | Full product name | 
**Description** | Pointer to **string** | Product description | [optional] 
**Account** | Pointer to [**CustomerAccount**](CustomerAccount.md) |  | [optional] 
**Currency** | [**CurrencyCode**](CurrencyCode.md) |  | 
**Category** | [**PriceCategory**](PriceCategory.md) |  | 
**Charges** | [**[]ProductPriceCharge**](ProductPriceCharge.md) |  | 
**Summary** | [**PriceSummary**](PriceSummary.md) |  | 
**Service** | Pointer to [**ServicePrice**](ServicePrice.md) |  | [optional] 
**IpBlock** | Pointer to [**IpBlockProductPrice**](IpBlockProductPrice.md) |  | [optional] 

## Methods

### NewPrice

`func NewPrice(href string, type_ ProductType, code string, name string, currency CurrencyCode, category PriceCategory, charges []ProductPriceCharge, summary PriceSummary, ) *Price`

NewPrice instantiates a new Price object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceWithDefaults

`func NewPriceWithDefaults() *Price`

NewPriceWithDefaults instantiates a new Price object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *Price) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *Price) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *Price) SetHref(v string)`

SetHref sets Href field to given value.


### GetType

`func (o *Price) GetType() ProductType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Price) GetTypeOk() (*ProductType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Price) SetType(v ProductType)`

SetType sets Type field to given value.


### GetCode

`func (o *Price) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Price) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Price) SetCode(v string)`

SetCode sets Code field to given value.


### GetName

`func (o *Price) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Price) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Price) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *Price) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Price) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Price) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Price) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAccount

`func (o *Price) GetAccount() CustomerAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *Price) GetAccountOk() (*CustomerAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *Price) SetAccount(v CustomerAccount)`

SetAccount sets Account field to given value.

### HasAccount

`func (o *Price) HasAccount() bool`

HasAccount returns a boolean if a field has been set.

### GetCurrency

`func (o *Price) GetCurrency() CurrencyCode`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Price) GetCurrencyOk() (*CurrencyCode, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Price) SetCurrency(v CurrencyCode)`

SetCurrency sets Currency field to given value.


### GetCategory

`func (o *Price) GetCategory() PriceCategory`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Price) GetCategoryOk() (*PriceCategory, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Price) SetCategory(v PriceCategory)`

SetCategory sets Category field to given value.


### GetCharges

`func (o *Price) GetCharges() []ProductPriceCharge`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *Price) GetChargesOk() (*[]ProductPriceCharge, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *Price) SetCharges(v []ProductPriceCharge)`

SetCharges sets Charges field to given value.


### GetSummary

`func (o *Price) GetSummary() PriceSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *Price) GetSummaryOk() (*PriceSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *Price) SetSummary(v PriceSummary)`

SetSummary sets Summary field to given value.


### GetService

`func (o *Price) GetService() ServicePrice`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *Price) GetServiceOk() (*ServicePrice, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *Price) SetService(v ServicePrice)`

SetService sets Service field to given value.

### HasService

`func (o *Price) HasService() bool`

HasService returns a boolean if a field has been set.

### GetIpBlock

`func (o *Price) GetIpBlock() IpBlockProductPrice`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *Price) GetIpBlockOk() (*IpBlockProductPrice, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *Price) SetIpBlock(v IpBlockProductPrice)`

SetIpBlock sets IpBlock field to given value.

### HasIpBlock

`func (o *Price) HasIpBlock() bool`

HasIpBlock returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


