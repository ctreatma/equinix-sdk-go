# AlertReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | database ID | [optional] 
**AlertUid** | Pointer to **string** | alert unique ID | [optional] 
**TraceUid** | Pointer to **string** | alert trace unique ID related to status change | [optional] 
**AssetTagUid** | Pointer to **string** | asset tag point unique id | [optional] 
**AssetTagDisplayName** | Pointer to **string** | asset tag point display name | [optional] 
**Status** | Pointer to [**AlertReadModelStatus**](AlertReadModelStatus.md) |  | [optional] 
**Value** | Pointer to [**ValueReadModel**](ValueReadModel.md) |  | [optional] 
**Asset** | Pointer to [**AssetReadModel**](AssetReadModel.md) |  | [optional] 
**Configuration** | Pointer to [**ConfigurationReadModel**](ConfigurationReadModel.md) |  | [optional] 
**ActiveProcessing** | Pointer to [**ProcessingTimeReadModel**](ProcessingTimeReadModel.md) |  | [optional] 
**InactiveProcessing** | Pointer to [**ProcessingTimeReadModel**](ProcessingTimeReadModel.md) |  | [optional] 

## Methods

### NewAlertReadModel

`func NewAlertReadModel() *AlertReadModel`

NewAlertReadModel instantiates a new AlertReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertReadModelWithDefaults

`func NewAlertReadModelWithDefaults() *AlertReadModel`

NewAlertReadModelWithDefaults instantiates a new AlertReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AlertReadModel) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AlertReadModel) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AlertReadModel) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *AlertReadModel) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAlertUid

`func (o *AlertReadModel) GetAlertUid() string`

GetAlertUid returns the AlertUid field if non-nil, zero value otherwise.

### GetAlertUidOk

`func (o *AlertReadModel) GetAlertUidOk() (*string, bool)`

GetAlertUidOk returns a tuple with the AlertUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertUid

`func (o *AlertReadModel) SetAlertUid(v string)`

SetAlertUid sets AlertUid field to given value.

### HasAlertUid

`func (o *AlertReadModel) HasAlertUid() bool`

HasAlertUid returns a boolean if a field has been set.

### GetTraceUid

`func (o *AlertReadModel) GetTraceUid() string`

GetTraceUid returns the TraceUid field if non-nil, zero value otherwise.

### GetTraceUidOk

`func (o *AlertReadModel) GetTraceUidOk() (*string, bool)`

GetTraceUidOk returns a tuple with the TraceUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceUid

`func (o *AlertReadModel) SetTraceUid(v string)`

SetTraceUid sets TraceUid field to given value.

### HasTraceUid

`func (o *AlertReadModel) HasTraceUid() bool`

HasTraceUid returns a boolean if a field has been set.

### GetAssetTagUid

`func (o *AlertReadModel) GetAssetTagUid() string`

GetAssetTagUid returns the AssetTagUid field if non-nil, zero value otherwise.

### GetAssetTagUidOk

`func (o *AlertReadModel) GetAssetTagUidOk() (*string, bool)`

GetAssetTagUidOk returns a tuple with the AssetTagUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetTagUid

`func (o *AlertReadModel) SetAssetTagUid(v string)`

SetAssetTagUid sets AssetTagUid field to given value.

### HasAssetTagUid

`func (o *AlertReadModel) HasAssetTagUid() bool`

HasAssetTagUid returns a boolean if a field has been set.

### GetAssetTagDisplayName

`func (o *AlertReadModel) GetAssetTagDisplayName() string`

GetAssetTagDisplayName returns the AssetTagDisplayName field if non-nil, zero value otherwise.

### GetAssetTagDisplayNameOk

`func (o *AlertReadModel) GetAssetTagDisplayNameOk() (*string, bool)`

GetAssetTagDisplayNameOk returns a tuple with the AssetTagDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetTagDisplayName

`func (o *AlertReadModel) SetAssetTagDisplayName(v string)`

SetAssetTagDisplayName sets AssetTagDisplayName field to given value.

### HasAssetTagDisplayName

`func (o *AlertReadModel) HasAssetTagDisplayName() bool`

HasAssetTagDisplayName returns a boolean if a field has been set.

### GetStatus

`func (o *AlertReadModel) GetStatus() AlertReadModelStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AlertReadModel) GetStatusOk() (*AlertReadModelStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AlertReadModel) SetStatus(v AlertReadModelStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AlertReadModel) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetValue

`func (o *AlertReadModel) GetValue() ValueReadModel`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AlertReadModel) GetValueOk() (*ValueReadModel, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AlertReadModel) SetValue(v ValueReadModel)`

SetValue sets Value field to given value.

### HasValue

`func (o *AlertReadModel) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetAsset

`func (o *AlertReadModel) GetAsset() AssetReadModel`

GetAsset returns the Asset field if non-nil, zero value otherwise.

### GetAssetOk

`func (o *AlertReadModel) GetAssetOk() (*AssetReadModel, bool)`

GetAssetOk returns a tuple with the Asset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsset

`func (o *AlertReadModel) SetAsset(v AssetReadModel)`

SetAsset sets Asset field to given value.

### HasAsset

`func (o *AlertReadModel) HasAsset() bool`

HasAsset returns a boolean if a field has been set.

### GetConfiguration

`func (o *AlertReadModel) GetConfiguration() ConfigurationReadModel`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *AlertReadModel) GetConfigurationOk() (*ConfigurationReadModel, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *AlertReadModel) SetConfiguration(v ConfigurationReadModel)`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *AlertReadModel) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### GetActiveProcessing

`func (o *AlertReadModel) GetActiveProcessing() ProcessingTimeReadModel`

GetActiveProcessing returns the ActiveProcessing field if non-nil, zero value otherwise.

### GetActiveProcessingOk

`func (o *AlertReadModel) GetActiveProcessingOk() (*ProcessingTimeReadModel, bool)`

GetActiveProcessingOk returns a tuple with the ActiveProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveProcessing

`func (o *AlertReadModel) SetActiveProcessing(v ProcessingTimeReadModel)`

SetActiveProcessing sets ActiveProcessing field to given value.

### HasActiveProcessing

`func (o *AlertReadModel) HasActiveProcessing() bool`

HasActiveProcessing returns a boolean if a field has been set.

### GetInactiveProcessing

`func (o *AlertReadModel) GetInactiveProcessing() ProcessingTimeReadModel`

GetInactiveProcessing returns the InactiveProcessing field if non-nil, zero value otherwise.

### GetInactiveProcessingOk

`func (o *AlertReadModel) GetInactiveProcessingOk() (*ProcessingTimeReadModel, bool)`

GetInactiveProcessingOk returns a tuple with the InactiveProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInactiveProcessing

`func (o *AlertReadModel) SetInactiveProcessing(v ProcessingTimeReadModel)`

SetInactiveProcessing sets InactiveProcessing field to given value.

### HasInactiveProcessing

`func (o *AlertReadModel) HasInactiveProcessing() bool`

HasInactiveProcessing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


