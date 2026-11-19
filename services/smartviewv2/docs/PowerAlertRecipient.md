# PowerAlertRecipient

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** | First name of the recipient | [optional] 
**LastName** | Pointer to **string** | Last name of the recipient | [optional] 
**Sms** | Pointer to [**PowerAlertContactMethod**](PowerAlertContactMethod.md) |  | [optional] 
**Email** | Pointer to [**PowerAlertContactMethod**](PowerAlertContactMethod.md) |  | [optional] 

## Methods

### NewPowerAlertRecipient

`func NewPowerAlertRecipient() *PowerAlertRecipient`

NewPowerAlertRecipient instantiates a new PowerAlertRecipient object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerAlertRecipientWithDefaults

`func NewPowerAlertRecipientWithDefaults() *PowerAlertRecipient`

NewPowerAlertRecipientWithDefaults instantiates a new PowerAlertRecipient object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *PowerAlertRecipient) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *PowerAlertRecipient) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *PowerAlertRecipient) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *PowerAlertRecipient) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *PowerAlertRecipient) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *PowerAlertRecipient) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *PowerAlertRecipient) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *PowerAlertRecipient) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetSms

`func (o *PowerAlertRecipient) GetSms() PowerAlertContactMethod`

GetSms returns the Sms field if non-nil, zero value otherwise.

### GetSmsOk

`func (o *PowerAlertRecipient) GetSmsOk() (*PowerAlertContactMethod, bool)`

GetSmsOk returns a tuple with the Sms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSms

`func (o *PowerAlertRecipient) SetSms(v PowerAlertContactMethod)`

SetSms sets Sms field to given value.

### HasSms

`func (o *PowerAlertRecipient) HasSms() bool`

HasSms returns a boolean if a field has been set.

### GetEmail

`func (o *PowerAlertRecipient) GetEmail() PowerAlertContactMethod`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PowerAlertRecipient) GetEmailOk() (*PowerAlertContactMethod, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PowerAlertRecipient) SetEmail(v PowerAlertContactMethod)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *PowerAlertRecipient) HasEmail() bool`

HasEmail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


