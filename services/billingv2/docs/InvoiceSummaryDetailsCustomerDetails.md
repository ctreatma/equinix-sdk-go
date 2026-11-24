# InvoiceSummaryDetailsCustomerDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountName** | Pointer to **string** | Customer account name | [optional] 
**AccountNumber** | Pointer to **string** | Customer account number | [optional] 
**Region** | Pointer to [**CustomerDetailsRegion**](CustomerDetailsRegion.md) |  | [optional] 
**AccountContact** | Pointer to **string** | Customer contact name. | [optional] 
**Address** | Pointer to [**AddressDetails**](AddressDetails.md) |  | [optional] 

## Methods

### NewInvoiceSummaryDetailsCustomerDetails

`func NewInvoiceSummaryDetailsCustomerDetails() *InvoiceSummaryDetailsCustomerDetails`

NewInvoiceSummaryDetailsCustomerDetails instantiates a new InvoiceSummaryDetailsCustomerDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceSummaryDetailsCustomerDetailsWithDefaults

`func NewInvoiceSummaryDetailsCustomerDetailsWithDefaults() *InvoiceSummaryDetailsCustomerDetails`

NewInvoiceSummaryDetailsCustomerDetailsWithDefaults instantiates a new InvoiceSummaryDetailsCustomerDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountName

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *InvoiceSummaryDetailsCustomerDetails) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *InvoiceSummaryDetailsCustomerDetails) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *InvoiceSummaryDetailsCustomerDetails) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *InvoiceSummaryDetailsCustomerDetails) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetRegion

`func (o *InvoiceSummaryDetailsCustomerDetails) GetRegion() CustomerDetailsRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *InvoiceSummaryDetailsCustomerDetails) GetRegionOk() (*CustomerDetailsRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *InvoiceSummaryDetailsCustomerDetails) SetRegion(v CustomerDetailsRegion)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *InvoiceSummaryDetailsCustomerDetails) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetAccountContact

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountContact() string`

GetAccountContact returns the AccountContact field if non-nil, zero value otherwise.

### GetAccountContactOk

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAccountContactOk() (*string, bool)`

GetAccountContactOk returns a tuple with the AccountContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountContact

`func (o *InvoiceSummaryDetailsCustomerDetails) SetAccountContact(v string)`

SetAccountContact sets AccountContact field to given value.

### HasAccountContact

`func (o *InvoiceSummaryDetailsCustomerDetails) HasAccountContact() bool`

HasAccountContact returns a boolean if a field has been set.

### GetAddress

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAddress() AddressDetails`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *InvoiceSummaryDetailsCustomerDetails) GetAddressOk() (*AddressDetails, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *InvoiceSummaryDetailsCustomerDetails) SetAddress(v AddressDetails)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *InvoiceSummaryDetailsCustomerDetails) HasAddress() bool`

HasAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


