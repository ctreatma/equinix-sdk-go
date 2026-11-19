# UpdateAlertConfigurationCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlertConfigurationUid** | **string** | Unique identifier of the power alert configuration to update | 
**State** | Pointer to [**UpdateAlertConfigurationCommandState**](UpdateAlertConfigurationCommandState.md) |  | [optional] 
**Condition** | Pointer to [**PowerAlertCondition**](PowerAlertCondition.md) |  | [optional] 
**Recipients** | Pointer to [**[]PowerAlertRecipient**](PowerAlertRecipient.md) | Updated list of recipients | [optional] 
**Assets** | Pointer to [**UpdateAlertConfigurationCommandAssets**](UpdateAlertConfigurationCommandAssets.md) |  | [optional] 

## Methods

### NewUpdateAlertConfigurationCommand

`func NewUpdateAlertConfigurationCommand(alertConfigurationUid string, ) *UpdateAlertConfigurationCommand`

NewUpdateAlertConfigurationCommand instantiates a new UpdateAlertConfigurationCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAlertConfigurationCommandWithDefaults

`func NewUpdateAlertConfigurationCommandWithDefaults() *UpdateAlertConfigurationCommand`

NewUpdateAlertConfigurationCommandWithDefaults instantiates a new UpdateAlertConfigurationCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlertConfigurationUid

`func (o *UpdateAlertConfigurationCommand) GetAlertConfigurationUid() string`

GetAlertConfigurationUid returns the AlertConfigurationUid field if non-nil, zero value otherwise.

### GetAlertConfigurationUidOk

`func (o *UpdateAlertConfigurationCommand) GetAlertConfigurationUidOk() (*string, bool)`

GetAlertConfigurationUidOk returns a tuple with the AlertConfigurationUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertConfigurationUid

`func (o *UpdateAlertConfigurationCommand) SetAlertConfigurationUid(v string)`

SetAlertConfigurationUid sets AlertConfigurationUid field to given value.


### GetState

`func (o *UpdateAlertConfigurationCommand) GetState() UpdateAlertConfigurationCommandState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *UpdateAlertConfigurationCommand) GetStateOk() (*UpdateAlertConfigurationCommandState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *UpdateAlertConfigurationCommand) SetState(v UpdateAlertConfigurationCommandState)`

SetState sets State field to given value.

### HasState

`func (o *UpdateAlertConfigurationCommand) HasState() bool`

HasState returns a boolean if a field has been set.

### GetCondition

`func (o *UpdateAlertConfigurationCommand) GetCondition() PowerAlertCondition`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *UpdateAlertConfigurationCommand) GetConditionOk() (*PowerAlertCondition, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *UpdateAlertConfigurationCommand) SetCondition(v PowerAlertCondition)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *UpdateAlertConfigurationCommand) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetRecipients

`func (o *UpdateAlertConfigurationCommand) GetRecipients() []PowerAlertRecipient`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *UpdateAlertConfigurationCommand) GetRecipientsOk() (*[]PowerAlertRecipient, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *UpdateAlertConfigurationCommand) SetRecipients(v []PowerAlertRecipient)`

SetRecipients sets Recipients field to given value.

### HasRecipients

`func (o *UpdateAlertConfigurationCommand) HasRecipients() bool`

HasRecipients returns a boolean if a field has been set.

### GetAssets

`func (o *UpdateAlertConfigurationCommand) GetAssets() UpdateAlertConfigurationCommandAssets`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *UpdateAlertConfigurationCommand) GetAssetsOk() (*UpdateAlertConfigurationCommandAssets, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *UpdateAlertConfigurationCommand) SetAssets(v UpdateAlertConfigurationCommandAssets)`

SetAssets sets Assets field to given value.

### HasAssets

`func (o *UpdateAlertConfigurationCommand) HasAssets() bool`

HasAssets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


