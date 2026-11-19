# BillingAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** | Billing account ID. | [optional] 
**AccountNumber** | Pointer to **string** | Billing account number. | [optional] 
**AccountName** | Pointer to **string** | Billing account name. | [optional] 
**Currency** | Pointer to **string** | Billing account currency. | [optional] 
**BillingCountry** | Pointer to **string** | Billing account country. | [optional] 
**AccountStatus** | Pointer to [**AccountStatus**](AccountStatus.md) |  | [optional] 
**IsGlobal** | Pointer to **bool** | Indicator for billing account type. true &#x3D; Global billing account, false &#x3D; Local billing account | [optional] 
**IsPoRequired** | Pointer to **bool** | Indicator for pucharse order required. | [optional] 
**IsSignatureRequired** | Pointer to **bool** | Indicator for signature required. | [optional] 
**IsReseller** | Pointer to **bool** | Indicator for reseller. | [optional] 
**IsSubCustomer** | Pointer to **bool** | Indicator for sub customer. | [optional] 
**CreatedDatetime** | Pointer to **time.Time** | Billing Account created datetime | [optional] 
**LastModifiedDatetime** | Pointer to **time.Time** | Billing account last modified datetime | [optional] 

## Methods

### NewBillingAccount

`func NewBillingAccount() *BillingAccount`

NewBillingAccount instantiates a new BillingAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBillingAccountWithDefaults

`func NewBillingAccountWithDefaults() *BillingAccount`

NewBillingAccountWithDefaults instantiates a new BillingAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *BillingAccount) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *BillingAccount) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *BillingAccount) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *BillingAccount) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *BillingAccount) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *BillingAccount) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *BillingAccount) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *BillingAccount) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountName

`func (o *BillingAccount) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *BillingAccount) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *BillingAccount) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *BillingAccount) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetCurrency

`func (o *BillingAccount) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *BillingAccount) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *BillingAccount) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *BillingAccount) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetBillingCountry

`func (o *BillingAccount) GetBillingCountry() string`

GetBillingCountry returns the BillingCountry field if non-nil, zero value otherwise.

### GetBillingCountryOk

`func (o *BillingAccount) GetBillingCountryOk() (*string, bool)`

GetBillingCountryOk returns a tuple with the BillingCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCountry

`func (o *BillingAccount) SetBillingCountry(v string)`

SetBillingCountry sets BillingCountry field to given value.

### HasBillingCountry

`func (o *BillingAccount) HasBillingCountry() bool`

HasBillingCountry returns a boolean if a field has been set.

### GetAccountStatus

`func (o *BillingAccount) GetAccountStatus() AccountStatus`

GetAccountStatus returns the AccountStatus field if non-nil, zero value otherwise.

### GetAccountStatusOk

`func (o *BillingAccount) GetAccountStatusOk() (*AccountStatus, bool)`

GetAccountStatusOk returns a tuple with the AccountStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountStatus

`func (o *BillingAccount) SetAccountStatus(v AccountStatus)`

SetAccountStatus sets AccountStatus field to given value.

### HasAccountStatus

`func (o *BillingAccount) HasAccountStatus() bool`

HasAccountStatus returns a boolean if a field has been set.

### GetIsGlobal

`func (o *BillingAccount) GetIsGlobal() bool`

GetIsGlobal returns the IsGlobal field if non-nil, zero value otherwise.

### GetIsGlobalOk

`func (o *BillingAccount) GetIsGlobalOk() (*bool, bool)`

GetIsGlobalOk returns a tuple with the IsGlobal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGlobal

`func (o *BillingAccount) SetIsGlobal(v bool)`

SetIsGlobal sets IsGlobal field to given value.

### HasIsGlobal

`func (o *BillingAccount) HasIsGlobal() bool`

HasIsGlobal returns a boolean if a field has been set.

### GetIsPoRequired

`func (o *BillingAccount) GetIsPoRequired() bool`

GetIsPoRequired returns the IsPoRequired field if non-nil, zero value otherwise.

### GetIsPoRequiredOk

`func (o *BillingAccount) GetIsPoRequiredOk() (*bool, bool)`

GetIsPoRequiredOk returns a tuple with the IsPoRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPoRequired

`func (o *BillingAccount) SetIsPoRequired(v bool)`

SetIsPoRequired sets IsPoRequired field to given value.

### HasIsPoRequired

`func (o *BillingAccount) HasIsPoRequired() bool`

HasIsPoRequired returns a boolean if a field has been set.

### GetIsSignatureRequired

`func (o *BillingAccount) GetIsSignatureRequired() bool`

GetIsSignatureRequired returns the IsSignatureRequired field if non-nil, zero value otherwise.

### GetIsSignatureRequiredOk

`func (o *BillingAccount) GetIsSignatureRequiredOk() (*bool, bool)`

GetIsSignatureRequiredOk returns a tuple with the IsSignatureRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSignatureRequired

`func (o *BillingAccount) SetIsSignatureRequired(v bool)`

SetIsSignatureRequired sets IsSignatureRequired field to given value.

### HasIsSignatureRequired

`func (o *BillingAccount) HasIsSignatureRequired() bool`

HasIsSignatureRequired returns a boolean if a field has been set.

### GetIsReseller

`func (o *BillingAccount) GetIsReseller() bool`

GetIsReseller returns the IsReseller field if non-nil, zero value otherwise.

### GetIsResellerOk

`func (o *BillingAccount) GetIsResellerOk() (*bool, bool)`

GetIsResellerOk returns a tuple with the IsReseller field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsReseller

`func (o *BillingAccount) SetIsReseller(v bool)`

SetIsReseller sets IsReseller field to given value.

### HasIsReseller

`func (o *BillingAccount) HasIsReseller() bool`

HasIsReseller returns a boolean if a field has been set.

### GetIsSubCustomer

`func (o *BillingAccount) GetIsSubCustomer() bool`

GetIsSubCustomer returns the IsSubCustomer field if non-nil, zero value otherwise.

### GetIsSubCustomerOk

`func (o *BillingAccount) GetIsSubCustomerOk() (*bool, bool)`

GetIsSubCustomerOk returns a tuple with the IsSubCustomer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSubCustomer

`func (o *BillingAccount) SetIsSubCustomer(v bool)`

SetIsSubCustomer sets IsSubCustomer field to given value.

### HasIsSubCustomer

`func (o *BillingAccount) HasIsSubCustomer() bool`

HasIsSubCustomer returns a boolean if a field has been set.

### GetCreatedDatetime

`func (o *BillingAccount) GetCreatedDatetime() time.Time`

GetCreatedDatetime returns the CreatedDatetime field if non-nil, zero value otherwise.

### GetCreatedDatetimeOk

`func (o *BillingAccount) GetCreatedDatetimeOk() (*time.Time, bool)`

GetCreatedDatetimeOk returns a tuple with the CreatedDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDatetime

`func (o *BillingAccount) SetCreatedDatetime(v time.Time)`

SetCreatedDatetime sets CreatedDatetime field to given value.

### HasCreatedDatetime

`func (o *BillingAccount) HasCreatedDatetime() bool`

HasCreatedDatetime returns a boolean if a field has been set.

### GetLastModifiedDatetime

`func (o *BillingAccount) GetLastModifiedDatetime() time.Time`

GetLastModifiedDatetime returns the LastModifiedDatetime field if non-nil, zero value otherwise.

### GetLastModifiedDatetimeOk

`func (o *BillingAccount) GetLastModifiedDatetimeOk() (*time.Time, bool)`

GetLastModifiedDatetimeOk returns a tuple with the LastModifiedDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifiedDatetime

`func (o *BillingAccount) SetLastModifiedDatetime(v time.Time)`

SetLastModifiedDatetime sets LastModifiedDatetime field to given value.

### HasLastModifiedDatetime

`func (o *BillingAccount) HasLastModifiedDatetime() bool`

HasLastModifiedDatetime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


