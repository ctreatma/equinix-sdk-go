# PowerAlertCondition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConditionType** | Pointer to **string** | The type of condition that triggers the alert (e.g., EXCEEDS, FALLS_BELOW) | [optional] 
**EventType** | Pointer to **string** | The power metric being monitored (e.g., CAGE_DRAW, CABINET_DRAW_TO_USABLE_KVA) | [optional] 
**Threshold** | Pointer to [**PowerAlertThreshold**](PowerAlertThreshold.md) |  | [optional] 

## Methods

### NewPowerAlertCondition

`func NewPowerAlertCondition() *PowerAlertCondition`

NewPowerAlertCondition instantiates a new PowerAlertCondition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerAlertConditionWithDefaults

`func NewPowerAlertConditionWithDefaults() *PowerAlertCondition`

NewPowerAlertConditionWithDefaults instantiates a new PowerAlertCondition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConditionType

`func (o *PowerAlertCondition) GetConditionType() string`

GetConditionType returns the ConditionType field if non-nil, zero value otherwise.

### GetConditionTypeOk

`func (o *PowerAlertCondition) GetConditionTypeOk() (*string, bool)`

GetConditionTypeOk returns a tuple with the ConditionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionType

`func (o *PowerAlertCondition) SetConditionType(v string)`

SetConditionType sets ConditionType field to given value.

### HasConditionType

`func (o *PowerAlertCondition) HasConditionType() bool`

HasConditionType returns a boolean if a field has been set.

### GetEventType

`func (o *PowerAlertCondition) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PowerAlertCondition) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PowerAlertCondition) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *PowerAlertCondition) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetThreshold

`func (o *PowerAlertCondition) GetThreshold() PowerAlertThreshold`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *PowerAlertCondition) GetThresholdOk() (*PowerAlertThreshold, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *PowerAlertCondition) SetThreshold(v PowerAlertThreshold)`

SetThreshold sets Threshold field to given value.

### HasThreshold

`func (o *PowerAlertCondition) HasThreshold() bool`

HasThreshold returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


