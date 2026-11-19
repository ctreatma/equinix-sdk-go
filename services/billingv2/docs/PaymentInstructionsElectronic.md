# PaymentInstructionsElectronic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BankName** | Pointer to **string** | Name of bank for electronic payment. | [optional] 
**BankAddress** | Pointer to [**BankAddressDetails**](BankAddressDetails.md) |  | [optional] 
**PayeeName** | Pointer to **string** | Equinix payee name for electronic payment. | [optional] 
**PayeeAccountNumber** | Pointer to **string** | Equinix bank account number. | [optional] 
**BankCode** | Pointer to **string** | Equinix international bank account number. This can be &#x60;BSB#&#x60;, &#x60;IBAN&#x60;, &#x60;CNAP&#x60;, &#x60;ABA#&#x60; depending on the region. Please refer to appendix for more information. | [optional] 
**SwiftCode** | Pointer to **string** | Equinix SWIFT code for bank transfer | [optional] 
**SortCode** | Pointer to **string** | Equinix Sort code for bank transfer | [optional] 

## Methods

### NewPaymentInstructionsElectronic

`func NewPaymentInstructionsElectronic() *PaymentInstructionsElectronic`

NewPaymentInstructionsElectronic instantiates a new PaymentInstructionsElectronic object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentInstructionsElectronicWithDefaults

`func NewPaymentInstructionsElectronicWithDefaults() *PaymentInstructionsElectronic`

NewPaymentInstructionsElectronicWithDefaults instantiates a new PaymentInstructionsElectronic object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBankName

`func (o *PaymentInstructionsElectronic) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *PaymentInstructionsElectronic) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *PaymentInstructionsElectronic) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *PaymentInstructionsElectronic) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *PaymentInstructionsElectronic) GetBankAddress() BankAddressDetails`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *PaymentInstructionsElectronic) GetBankAddressOk() (*BankAddressDetails, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *PaymentInstructionsElectronic) SetBankAddress(v BankAddressDetails)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *PaymentInstructionsElectronic) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.

### GetPayeeName

`func (o *PaymentInstructionsElectronic) GetPayeeName() string`

GetPayeeName returns the PayeeName field if non-nil, zero value otherwise.

### GetPayeeNameOk

`func (o *PaymentInstructionsElectronic) GetPayeeNameOk() (*string, bool)`

GetPayeeNameOk returns a tuple with the PayeeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayeeName

`func (o *PaymentInstructionsElectronic) SetPayeeName(v string)`

SetPayeeName sets PayeeName field to given value.

### HasPayeeName

`func (o *PaymentInstructionsElectronic) HasPayeeName() bool`

HasPayeeName returns a boolean if a field has been set.

### GetPayeeAccountNumber

`func (o *PaymentInstructionsElectronic) GetPayeeAccountNumber() string`

GetPayeeAccountNumber returns the PayeeAccountNumber field if non-nil, zero value otherwise.

### GetPayeeAccountNumberOk

`func (o *PaymentInstructionsElectronic) GetPayeeAccountNumberOk() (*string, bool)`

GetPayeeAccountNumberOk returns a tuple with the PayeeAccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayeeAccountNumber

`func (o *PaymentInstructionsElectronic) SetPayeeAccountNumber(v string)`

SetPayeeAccountNumber sets PayeeAccountNumber field to given value.

### HasPayeeAccountNumber

`func (o *PaymentInstructionsElectronic) HasPayeeAccountNumber() bool`

HasPayeeAccountNumber returns a boolean if a field has been set.

### GetBankCode

`func (o *PaymentInstructionsElectronic) GetBankCode() string`

GetBankCode returns the BankCode field if non-nil, zero value otherwise.

### GetBankCodeOk

`func (o *PaymentInstructionsElectronic) GetBankCodeOk() (*string, bool)`

GetBankCodeOk returns a tuple with the BankCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankCode

`func (o *PaymentInstructionsElectronic) SetBankCode(v string)`

SetBankCode sets BankCode field to given value.

### HasBankCode

`func (o *PaymentInstructionsElectronic) HasBankCode() bool`

HasBankCode returns a boolean if a field has been set.

### GetSwiftCode

`func (o *PaymentInstructionsElectronic) GetSwiftCode() string`

GetSwiftCode returns the SwiftCode field if non-nil, zero value otherwise.

### GetSwiftCodeOk

`func (o *PaymentInstructionsElectronic) GetSwiftCodeOk() (*string, bool)`

GetSwiftCodeOk returns a tuple with the SwiftCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwiftCode

`func (o *PaymentInstructionsElectronic) SetSwiftCode(v string)`

SetSwiftCode sets SwiftCode field to given value.

### HasSwiftCode

`func (o *PaymentInstructionsElectronic) HasSwiftCode() bool`

HasSwiftCode returns a boolean if a field has been set.

### GetSortCode

`func (o *PaymentInstructionsElectronic) GetSortCode() string`

GetSortCode returns the SortCode field if non-nil, zero value otherwise.

### GetSortCodeOk

`func (o *PaymentInstructionsElectronic) GetSortCodeOk() (*string, bool)`

GetSortCodeOk returns a tuple with the SortCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortCode

`func (o *PaymentInstructionsElectronic) SetSortCode(v string)`

SetSortCode sets SortCode field to given value.

### HasSortCode

`func (o *PaymentInstructionsElectronic) HasSortCode() bool`

HasSortCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


