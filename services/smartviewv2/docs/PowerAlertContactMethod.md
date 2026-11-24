# PowerAlertContactMethod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **string** | The contact value (phone number for SMS, email address for email) | [optional] 
**Enabled** | Pointer to **bool** | Whether this contact method is enabled for notifications | [optional] 

## Methods

### NewPowerAlertContactMethod

`func NewPowerAlertContactMethod() *PowerAlertContactMethod`

NewPowerAlertContactMethod instantiates a new PowerAlertContactMethod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerAlertContactMethodWithDefaults

`func NewPowerAlertContactMethodWithDefaults() *PowerAlertContactMethod`

NewPowerAlertContactMethodWithDefaults instantiates a new PowerAlertContactMethod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *PowerAlertContactMethod) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PowerAlertContactMethod) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PowerAlertContactMethod) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *PowerAlertContactMethod) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetEnabled

`func (o *PowerAlertContactMethod) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PowerAlertContactMethod) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PowerAlertContactMethod) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *PowerAlertContactMethod) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


