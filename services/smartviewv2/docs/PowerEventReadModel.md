# PowerEventReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | Database ID of the power event | [optional] 
**AlertUid** | Pointer to **string** | Unique identifier of the power event | [optional] 
**TraceUid** | Pointer to **string** | Trace unique ID related to the power event status change | [optional] 
**Status** | Pointer to [**PowerEventReadModelStatus**](PowerEventReadModelStatus.md) |  | [optional] 
**Asset** | Pointer to [**PowerEventAssetReadModel**](PowerEventAssetReadModel.md) |  | [optional] 
**ActiveProcessing** | Pointer to [**PowerEventProcessingTimeReadModel**](PowerEventProcessingTimeReadModel.md) |  | [optional] 
**Category** | Pointer to **string** | Category of the power event | [optional] 
**EventType** | Pointer to **string** | Type of power event (e.g., CAGE_DRAW, CABINET_DRAW_TO_USABLE_KVA) | [optional] 
**ConditionType** | Pointer to **string** | Condition type that triggered the event (e.g., EXCEEDS, FALLS_BELOW) | [optional] 
**TriggerValue** | Pointer to **string** | The threshold value that was configured to trigger the event | [optional] 
**CurrentValue** | Pointer to **string** | The actual value at the time the event was triggered | [optional] 
**AccountNo** | Pointer to **string** | Customer account number associated with the event | [optional] 

## Methods

### NewPowerEventReadModel

`func NewPowerEventReadModel() *PowerEventReadModel`

NewPowerEventReadModel instantiates a new PowerEventReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerEventReadModelWithDefaults

`func NewPowerEventReadModelWithDefaults() *PowerEventReadModel`

NewPowerEventReadModelWithDefaults instantiates a new PowerEventReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PowerEventReadModel) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PowerEventReadModel) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PowerEventReadModel) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *PowerEventReadModel) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAlertUid

`func (o *PowerEventReadModel) GetAlertUid() string`

GetAlertUid returns the AlertUid field if non-nil, zero value otherwise.

### GetAlertUidOk

`func (o *PowerEventReadModel) GetAlertUidOk() (*string, bool)`

GetAlertUidOk returns a tuple with the AlertUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertUid

`func (o *PowerEventReadModel) SetAlertUid(v string)`

SetAlertUid sets AlertUid field to given value.

### HasAlertUid

`func (o *PowerEventReadModel) HasAlertUid() bool`

HasAlertUid returns a boolean if a field has been set.

### GetTraceUid

`func (o *PowerEventReadModel) GetTraceUid() string`

GetTraceUid returns the TraceUid field if non-nil, zero value otherwise.

### GetTraceUidOk

`func (o *PowerEventReadModel) GetTraceUidOk() (*string, bool)`

GetTraceUidOk returns a tuple with the TraceUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceUid

`func (o *PowerEventReadModel) SetTraceUid(v string)`

SetTraceUid sets TraceUid field to given value.

### HasTraceUid

`func (o *PowerEventReadModel) HasTraceUid() bool`

HasTraceUid returns a boolean if a field has been set.

### GetStatus

`func (o *PowerEventReadModel) GetStatus() PowerEventReadModelStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PowerEventReadModel) GetStatusOk() (*PowerEventReadModelStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PowerEventReadModel) SetStatus(v PowerEventReadModelStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PowerEventReadModel) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAsset

`func (o *PowerEventReadModel) GetAsset() PowerEventAssetReadModel`

GetAsset returns the Asset field if non-nil, zero value otherwise.

### GetAssetOk

`func (o *PowerEventReadModel) GetAssetOk() (*PowerEventAssetReadModel, bool)`

GetAssetOk returns a tuple with the Asset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset

`func (o *PowerEventReadModel) SetAsset(v PowerEventAssetReadModel)`

SetAsset sets Asset field to given value.

### HasAsset

`func (o *PowerEventReadModel) HasAsset() bool`

HasAsset returns a boolean if a field has been set.

### GetActiveProcessing

`func (o *PowerEventReadModel) GetActiveProcessing() PowerEventProcessingTimeReadModel`

GetActiveProcessing returns the ActiveProcessing field if non-nil, zero value otherwise.

### GetActiveProcessingOk

`func (o *PowerEventReadModel) GetActiveProcessingOk() (*PowerEventProcessingTimeReadModel, bool)`

GetActiveProcessingOk returns a tuple with the ActiveProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveProcessing

`func (o *PowerEventReadModel) SetActiveProcessing(v PowerEventProcessingTimeReadModel)`

SetActiveProcessing sets ActiveProcessing field to given value.

### HasActiveProcessing

`func (o *PowerEventReadModel) HasActiveProcessing() bool`

HasActiveProcessing returns a boolean if a field has been set.

### GetCategory

`func (o *PowerEventReadModel) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *PowerEventReadModel) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *PowerEventReadModel) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *PowerEventReadModel) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetEventType

`func (o *PowerEventReadModel) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PowerEventReadModel) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PowerEventReadModel) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *PowerEventReadModel) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### GetConditionType

`func (o *PowerEventReadModel) GetConditionType() string`

GetConditionType returns the ConditionType field if non-nil, zero value otherwise.

### GetConditionTypeOk

`func (o *PowerEventReadModel) GetConditionTypeOk() (*string, bool)`

GetConditionTypeOk returns a tuple with the ConditionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditionType

`func (o *PowerEventReadModel) SetConditionType(v string)`

SetConditionType sets ConditionType field to given value.

### HasConditionType

`func (o *PowerEventReadModel) HasConditionType() bool`

HasConditionType returns a boolean if a field has been set.

### GetTriggerValue

`func (o *PowerEventReadModel) GetTriggerValue() string`

GetTriggerValue returns the TriggerValue field if non-nil, zero value otherwise.

### GetTriggerValueOk

`func (o *PowerEventReadModel) GetTriggerValueOk() (*string, bool)`

GetTriggerValueOk returns a tuple with the TriggerValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerValue

`func (o *PowerEventReadModel) SetTriggerValue(v string)`

SetTriggerValue sets TriggerValue field to given value.

### HasTriggerValue

`func (o *PowerEventReadModel) HasTriggerValue() bool`

HasTriggerValue returns a boolean if a field has been set.

### GetCurrentValue

`func (o *PowerEventReadModel) GetCurrentValue() string`

GetCurrentValue returns the CurrentValue field if non-nil, zero value otherwise.

### GetCurrentValueOk

`func (o *PowerEventReadModel) GetCurrentValueOk() (*string, bool)`

GetCurrentValueOk returns a tuple with the CurrentValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentValue

`func (o *PowerEventReadModel) SetCurrentValue(v string)`

SetCurrentValue sets CurrentValue field to given value.

### HasCurrentValue

`func (o *PowerEventReadModel) HasCurrentValue() bool`

HasCurrentValue returns a boolean if a field has been set.

### GetAccountNo

`func (o *PowerEventReadModel) GetAccountNo() string`

GetAccountNo returns the AccountNo field if non-nil, zero value otherwise.

### GetAccountNoOk

`func (o *PowerEventReadModel) GetAccountNoOk() (*string, bool)`

GetAccountNoOk returns a tuple with the AccountNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNo

`func (o *PowerEventReadModel) SetAccountNo(v string)`

SetAccountNo sets AccountNo field to given value.

### HasAccountNo

`func (o *PowerEventReadModel) HasAccountNo() bool`

HasAccountNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


