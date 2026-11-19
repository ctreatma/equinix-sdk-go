# InvoiceItemsCustomerDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountName** | Pointer to **string** | Customer account name | [optional] 
**AccountNumber** | Pointer to **string** | Customer account number | [optional] 
**Region** | Pointer to [**CustomerDetailsRegion**](CustomerDetailsRegion.md) |  | [optional] 
**LegalEntity** | Pointer to **string** | Name of customer legal entity | [optional] 
**CountryCode** | Pointer to [**CountryCode**](CountryCode.md) |  | [optional] 

## Methods

### NewInvoiceItemsCustomerDetails

`func NewInvoiceItemsCustomerDetails() *InvoiceItemsCustomerDetails`

NewInvoiceItemsCustomerDetails instantiates a new InvoiceItemsCustomerDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceItemsCustomerDetailsWithDefaults

`func NewInvoiceItemsCustomerDetailsWithDefaults() *InvoiceItemsCustomerDetails`

NewInvoiceItemsCustomerDetailsWithDefaults instantiates a new InvoiceItemsCustomerDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountName

`func (o *InvoiceItemsCustomerDetails) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *InvoiceItemsCustomerDetails) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *InvoiceItemsCustomerDetails) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *InvoiceItemsCustomerDetails) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *InvoiceItemsCustomerDetails) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *InvoiceItemsCustomerDetails) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *InvoiceItemsCustomerDetails) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *InvoiceItemsCustomerDetails) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetRegion

`func (o *InvoiceItemsCustomerDetails) GetRegion() CustomerDetailsRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *InvoiceItemsCustomerDetails) GetRegionOk() (*CustomerDetailsRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *InvoiceItemsCustomerDetails) SetRegion(v CustomerDetailsRegion)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *InvoiceItemsCustomerDetails) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetLegalEntity

`func (o *InvoiceItemsCustomerDetails) GetLegalEntity() string`

GetLegalEntity returns the LegalEntity field if non-nil, zero value otherwise.

### GetLegalEntityOk

`func (o *InvoiceItemsCustomerDetails) GetLegalEntityOk() (*string, bool)`

GetLegalEntityOk returns a tuple with the LegalEntity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalEntity

`func (o *InvoiceItemsCustomerDetails) SetLegalEntity(v string)`

SetLegalEntity sets LegalEntity field to given value.

### HasLegalEntity

`func (o *InvoiceItemsCustomerDetails) HasLegalEntity() bool`

HasLegalEntity returns a boolean if a field has been set.

### GetCountryCode

`func (o *InvoiceItemsCustomerDetails) GetCountryCode() CountryCode`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *InvoiceItemsCustomerDetails) GetCountryCodeOk() (*CountryCode, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *InvoiceItemsCustomerDetails) SetCountryCode(v CountryCode)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *InvoiceItemsCustomerDetails) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


