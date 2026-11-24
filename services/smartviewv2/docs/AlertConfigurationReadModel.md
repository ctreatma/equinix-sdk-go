# AlertConfigurationReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlertConfigurationUid** | Pointer to **string** | Unique identifier of the alert configuration | [optional] 
**Ibx** | Pointer to **string** | IBX code associated with the alert configuration | [optional] 
**State** | Pointer to [**AlertConfigurationReadModelState**](AlertConfigurationReadModelState.md) |  | [optional] 
**Section** | Pointer to **string** | Section type of the alert configuration | [optional] 
**Source** | Pointer to **string** | Source system that created the configuration | [optional] 
**Condition** | Pointer to [**PowerAlertCondition**](PowerAlertCondition.md) |  | [optional] 
**Recipients** | Pointer to [**[]PowerAlertRecipient**](PowerAlertRecipient.md) | List of configured notification recipients | [optional] 
**Creator** | Pointer to [**AlertConfigurationReadModelCreator**](AlertConfigurationReadModelCreator.md) |  | [optional] 
**CreatedOn** | Pointer to **time.Time** | Timestamp when the configuration was created | [optional] 
**UpdatedOn** | Pointer to **NullableTime** | Timestamp when the configuration was last updated | [optional] 
**Assets** | Pointer to [**map[string][]PowerAlertConfigurationAsset**](array.md) | Assets being monitored, keyed by level type (CAGE, CABINET, CIRCUIT) | [optional] 

## Methods

### NewAlertConfigurationReadModel

`func NewAlertConfigurationReadModel() *AlertConfigurationReadModel`

NewAlertConfigurationReadModel instantiates a new AlertConfigurationReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertConfigurationReadModelWithDefaults

`func NewAlertConfigurationReadModelWithDefaults() *AlertConfigurationReadModel`

NewAlertConfigurationReadModelWithDefaults instantiates a new AlertConfigurationReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlertConfigurationUid

`func (o *AlertConfigurationReadModel) GetAlertConfigurationUid() string`

GetAlertConfigurationUid returns the AlertConfigurationUid field if non-nil, zero value otherwise.

### GetAlertConfigurationUidOk

`func (o *AlertConfigurationReadModel) GetAlertConfigurationUidOk() (*string, bool)`

GetAlertConfigurationUidOk returns a tuple with the AlertConfigurationUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertConfigurationUid

`func (o *AlertConfigurationReadModel) SetAlertConfigurationUid(v string)`

SetAlertConfigurationUid sets AlertConfigurationUid field to given value.

### HasAlertConfigurationUid

`func (o *AlertConfigurationReadModel) HasAlertConfigurationUid() bool`

HasAlertConfigurationUid returns a boolean if a field has been set.

### GetIbx

`func (o *AlertConfigurationReadModel) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *AlertConfigurationReadModel) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *AlertConfigurationReadModel) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *AlertConfigurationReadModel) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetState

`func (o *AlertConfigurationReadModel) GetState() AlertConfigurationReadModelState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AlertConfigurationReadModel) GetStateOk() (*AlertConfigurationReadModelState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AlertConfigurationReadModel) SetState(v AlertConfigurationReadModelState)`

SetState sets State field to given value.

### HasState

`func (o *AlertConfigurationReadModel) HasState() bool`

HasState returns a boolean if a field has been set.

### GetSection

`func (o *AlertConfigurationReadModel) GetSection() string`

GetSection returns the Section field if non-nil, zero value otherwise.

### GetSectionOk

`func (o *AlertConfigurationReadModel) GetSectionOk() (*string, bool)`

GetSectionOk returns a tuple with the Section field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSection

`func (o *AlertConfigurationReadModel) SetSection(v string)`

SetSection sets Section field to given value.

### HasSection

`func (o *AlertConfigurationReadModel) HasSection() bool`

HasSection returns a boolean if a field has been set.

### GetSource

`func (o *AlertConfigurationReadModel) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AlertConfigurationReadModel) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AlertConfigurationReadModel) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *AlertConfigurationReadModel) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetCondition

`func (o *AlertConfigurationReadModel) GetCondition() PowerAlertCondition`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *AlertConfigurationReadModel) GetConditionOk() (*PowerAlertCondition, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *AlertConfigurationReadModel) SetCondition(v PowerAlertCondition)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *AlertConfigurationReadModel) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetRecipients

`func (o *AlertConfigurationReadModel) GetRecipients() []PowerAlertRecipient`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *AlertConfigurationReadModel) GetRecipientsOk() (*[]PowerAlertRecipient, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *AlertConfigurationReadModel) SetRecipients(v []PowerAlertRecipient)`

SetRecipients sets Recipients field to given value.

### HasRecipients

`func (o *AlertConfigurationReadModel) HasRecipients() bool`

HasRecipients returns a boolean if a field has been set.

### GetCreator

`func (o *AlertConfigurationReadModel) GetCreator() AlertConfigurationReadModelCreator`

GetCreator returns the Creator field if non-nil, zero value otherwise.

### GetCreatorOk

`func (o *AlertConfigurationReadModel) GetCreatorOk() (*AlertConfigurationReadModelCreator, bool)`

GetCreatorOk returns a tuple with the Creator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreator

`func (o *AlertConfigurationReadModel) SetCreator(v AlertConfigurationReadModelCreator)`

SetCreator sets Creator field to given value.

### HasCreator

`func (o *AlertConfigurationReadModel) HasCreator() bool`

HasCreator returns a boolean if a field has been set.

### GetCreatedOn

`func (o *AlertConfigurationReadModel) GetCreatedOn() time.Time`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *AlertConfigurationReadModel) GetCreatedOnOk() (*time.Time, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *AlertConfigurationReadModel) SetCreatedOn(v time.Time)`

SetCreatedOn sets CreatedOn field to given value.

### HasCreatedOn

`func (o *AlertConfigurationReadModel) HasCreatedOn() bool`

HasCreatedOn returns a boolean if a field has been set.

### GetUpdatedOn

`func (o *AlertConfigurationReadModel) GetUpdatedOn() time.Time`

GetUpdatedOn returns the UpdatedOn field if non-nil, zero value otherwise.

### GetUpdatedOnOk

`func (o *AlertConfigurationReadModel) GetUpdatedOnOk() (*time.Time, bool)`

GetUpdatedOnOk returns a tuple with the UpdatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedOn

`func (o *AlertConfigurationReadModel) SetUpdatedOn(v time.Time)`

SetUpdatedOn sets UpdatedOn field to given value.

### HasUpdatedOn

`func (o *AlertConfigurationReadModel) HasUpdatedOn() bool`

HasUpdatedOn returns a boolean if a field has been set.

### SetUpdatedOnNil

`func (o *AlertConfigurationReadModel) SetUpdatedOnNil(b bool)`

 SetUpdatedOnNil sets the value for UpdatedOn to be an explicit nil

### UnsetUpdatedOn
`func (o *AlertConfigurationReadModel) UnsetUpdatedOn()`

UnsetUpdatedOn ensures that no value is present for UpdatedOn, not even an explicit nil
### GetAssets

`func (o *AlertConfigurationReadModel) GetAssets() map[string][]PowerAlertConfigurationAsset`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *AlertConfigurationReadModel) GetAssetsOk() (*map[string][]PowerAlertConfigurationAsset, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *AlertConfigurationReadModel) SetAssets(v map[string][]PowerAlertConfigurationAsset)`

SetAssets sets Assets field to given value.

### HasAssets

`func (o *AlertConfigurationReadModel) HasAssets() bool`

HasAssets returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


