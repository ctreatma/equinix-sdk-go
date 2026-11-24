# PaymentInstructionsCheck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BankName** | Pointer to **string** | Name of Bank for check payment. | [optional] 
**BankAddress** | Pointer to [**BankAddressDetails**](BankAddressDetails.md) |  | [optional] 

## Methods

### NewPaymentInstructionsCheck

`func NewPaymentInstructionsCheck() *PaymentInstructionsCheck`

NewPaymentInstructionsCheck instantiates a new PaymentInstructionsCheck object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentInstructionsCheckWithDefaults

`func NewPaymentInstructionsCheckWithDefaults() *PaymentInstructionsCheck`

NewPaymentInstructionsCheckWithDefaults instantiates a new PaymentInstructionsCheck object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBankName

`func (o *PaymentInstructionsCheck) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *PaymentInstructionsCheck) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *PaymentInstructionsCheck) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *PaymentInstructionsCheck) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### GetBankAddress

`func (o *PaymentInstructionsCheck) GetBankAddress() BankAddressDetails`

GetBankAddress returns the BankAddress field if non-nil, zero value otherwise.

### GetBankAddressOk

`func (o *PaymentInstructionsCheck) GetBankAddressOk() (*BankAddressDetails, bool)`

GetBankAddressOk returns a tuple with the BankAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankAddress

`func (o *PaymentInstructionsCheck) SetBankAddress(v BankAddressDetails)`

SetBankAddress sets BankAddress field to given value.

### HasBankAddress

`func (o *PaymentInstructionsCheck) HasBankAddress() bool`

HasBankAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


