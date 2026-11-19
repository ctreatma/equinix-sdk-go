# CreateAlertConfigurationCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNo** | **string** | Customer account number | 
**Ibx** | **string** | IBX code where the alert should be monitored | 
**Section** | **string** | Section type for the alert. Use POWER for power-related alerts. | 
**Condition** | [**PowerAlertCondition**](PowerAlertCondition.md) |  | 
**Recipients** | [**[]PowerAlertRecipient**](PowerAlertRecipient.md) | List of recipients to be notified when the alert condition is met | 
**Assets** | Pointer to [**CreateAlertConfigurationCommandAssets**](CreateAlertConfigurationCommandAssets.md) |  | [optional] 

## Methods

### NewCreateAlertConfigurationCommand

`func NewCreateAlertConfigurationCommand(accountNo string, ibx string, section string, condition PowerAlertCondition, recipients []PowerAlertRecipient, ) *CreateAlertConfigurationCommand`

NewCreateAlertConfigurationCommand instantiates a new CreateAlertConfigurationCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlertConfigurationCommandWithDefaults

`func NewCreateAlertConfigurationCommandWithDefaults() *CreateAlertConfigurationCommand`

NewCreateAlertConfigurationCommandWithDefaults instantiates a new CreateAlertConfigurationCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNo

`func (o *CreateAlertConfigurationCommand) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *CreateAlertConfigurationCommand) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *CreateAlertConfigurationCommand) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.


### GetIbx

`func (o *CreateAlertConfigurationCommand) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *CreateAlertConfigurationCommand) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *CreateAlertConfigurationCommand) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetSection

`func (o *CreateAlertConfigurationCommand) GetSection() string`

GetSection returns the Section field if non-nil, zero value otherwise.

### GetSectionOk

`func (o *CreateAlertConfigurationCommand) GetSectionOk() (*string, bool)`

GetSectionOk returns a tuple with the Section field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSection

`func (o *CreateAlertConfigurationCommand) SetSection(v string)`

SetSection sets Section field to given value.


### GetCondition

`func (o *CreateAlertConfigurationCommand) GetCondition() PowerAlertCondition`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *CreateAlertConfigurationCommand) GetConditionOk() (*PowerAlertCondition, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *CreateAlertConfigurationCommand) SetCondition(v PowerAlertCondition)`

SetCondition sets Condition field to given value.


### GetRecipients

`func (o *CreateAlertConfigurationCommand) GetRecipients() []PowerAlertRecipient`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *CreateAlertConfigurationCommand) GetRecipientsOk() (*[]PowerAlertRecipient, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *CreateAlertConfigurationCommand) SetRecipients(v []PowerAlertRecipient)`

SetRecipients sets Recipients field to given value.


### GetAssets

`func (o *CreateAlertConfigurationCommand) GetAssets() CreateAlertConfigurationCommandAssets`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *CreateAlertConfigurationCommand) GetAssetsOk() (*CreateAlertConfigurationCommandAssets, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *CreateAlertConfigurationCommand) SetAssets(v CreateAlertConfigurationCommandAssets)`

SetAssets sets Assets field to given value.

### HasAssets

`func (o *CreateAlertConfigurationCommand) HasAssets() bool`

HasAssets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


