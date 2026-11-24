# PaymentInstructions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Electronic** | Pointer to [**PaymentInstructionsElectronic**](PaymentInstructionsElectronic.md) |  | [optional] 
**Check** | Pointer to [**PaymentInstructionsCheck**](PaymentInstructionsCheck.md) |  | [optional] 
**EmailRemittance** | Pointer to **string** | Email address to send remittance advice. | [optional] 

## Methods

### NewPaymentInstructions

`func NewPaymentInstructions() *PaymentInstructions`

NewPaymentInstructions instantiates a new PaymentInstructions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentInstructionsWithDefaults

`func NewPaymentInstructionsWithDefaults() *PaymentInstructions`

NewPaymentInstructionsWithDefaults instantiates a new PaymentInstructions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetElectronic

`func (o *PaymentInstructions) GetElectronic() PaymentInstructionsElectronic`

GetElectronic returns the Electronic field if non-nil, zero value otherwise.

### GetElectronicOk

`func (o *PaymentInstructions) GetElectronicOk() (*PaymentInstructionsElectronic, bool)`

GetElectronicOk returns a tuple with the Electronic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElectronic

`func (o *PaymentInstructions) SetElectronic(v PaymentInstructionsElectronic)`

SetElectronic sets Electronic field to given value.

### HasElectronic

`func (o *PaymentInstructions) HasElectronic() bool`

HasElectronic returns a boolean if a field has been set.

### GetCheck

`func (o *PaymentInstructions) GetCheck() PaymentInstructionsCheck`

GetCheck returns the Check field if non-nil, zero value otherwise.

### GetCheckOk

`func (o *PaymentInstructions) GetCheckOk() (*PaymentInstructionsCheck, bool)`

GetCheckOk returns a tuple with the Check field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheck

`func (o *PaymentInstructions) SetCheck(v PaymentInstructionsCheck)`

SetCheck sets Check field to given value.

### HasCheck

`func (o *PaymentInstructions) HasCheck() bool`

HasCheck returns a boolean if a field has been set.

### GetEmailRemittance

`func (o *PaymentInstructions) GetEmailRemittance() string`

GetEmailRemittance returns the EmailRemittance field if non-nil, zero value otherwise.

### GetEmailRemittanceOk

`func (o *PaymentInstructions) GetEmailRemittanceOk() (*string, bool)`

GetEmailRemittanceOk returns a tuple with the EmailRemittance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailRemittance

`func (o *PaymentInstructions) SetEmailRemittance(v string)`

SetEmailRemittance sets EmailRemittance field to given value.

### HasEmailRemittance

`func (o *PaymentInstructions) HasEmailRemittance() bool`

HasEmailRemittance returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


