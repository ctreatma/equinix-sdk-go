# AssetForAssetAPI

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | Pointer to [**AssetForAssetAPIAssetId**](AssetForAssetAPIAssetId.md) |  | [optional] 
**Ibx** | Pointer to [**AssetForAssetAPIIbx**](AssetForAssetAPIIbx.md) |  | [optional] 
**AlarmStatus** | Pointer to [**AssetForAssetAPIAlarmStatus**](AssetForAssetAPIAlarmStatus.md) |  | [optional] 
**ResiliencyStatus** | Pointer to [**AssetForAssetAPIResiliencyStatus**](AssetForAssetAPIResiliencyStatus.md) |  | [optional] 
**AlarmLastTriggeredTime** | Pointer to **string** | datetime when the latest alarm on the asset was triggered | [optional] 
**AlarmLastClearedTime** | Pointer to **string** | datetime when the latest alarm on the asset was cleared | [optional] 
**PrimaryParentAsset** | Pointer to [**AssetForAssetAPIPrimaryParentAsset**](AssetForAssetAPIPrimaryParentAsset.md) |  | [optional] 
**AlternateParentAsset** | Pointer to [**AssetForAssetAPIAlternateParentAsset**](AssetForAssetAPIAlternateParentAsset.md) |  | [optional] 

## Methods

### NewAssetForAssetAPI

`func NewAssetForAssetAPI() *AssetForAssetAPI`

NewAssetForAssetAPI instantiates a new AssetForAssetAPI object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetForAssetAPIWithDefaults

`func NewAssetForAssetAPIWithDefaults() *AssetForAssetAPI`

NewAssetForAssetAPIWithDefaults instantiates a new AssetForAssetAPI object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetForAssetAPI) GetAssetId() AssetForAssetAPIAssetId`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetForAssetAPI) GetAssetIdOk() (*AssetForAssetAPIAssetId, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetForAssetAPI) SetAssetId(v AssetForAssetAPIAssetId)`

SetAssetId sets AssetId field to given value.

### HasAssetId

`func (o *AssetForAssetAPI) HasAssetId() bool`

HasAssetId returns a boolean if a field has been set.

### GetIbx

`func (o *AssetForAssetAPI) GetIbx() AssetForAssetAPIIbx`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *AssetForAssetAPI) GetIbxOk() (*AssetForAssetAPIIbx, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *AssetForAssetAPI) SetIbx(v AssetForAssetAPIIbx)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *AssetForAssetAPI) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetAlarmStatus

`func (o *AssetForAssetAPI) GetAlarmStatus() AssetForAssetAPIAlarmStatus`

GetAlarmStatus returns the AlarmStatus field if non-nil, zero value otherwise.

### GetAlarmStatusOk

`func (o *AssetForAssetAPI) GetAlarmStatusOk() (*AssetForAssetAPIAlarmStatus, bool)`

GetAlarmStatusOk returns a tuple with the AlarmStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmStatus

`func (o *AssetForAssetAPI) SetAlarmStatus(v AssetForAssetAPIAlarmStatus)`

SetAlarmStatus sets AlarmStatus field to given value.

### HasAlarmStatus

`func (o *AssetForAssetAPI) HasAlarmStatus() bool`

HasAlarmStatus returns a boolean if a field has been set.

### GetResiliencyStatus

`func (o *AssetForAssetAPI) GetResiliencyStatus() AssetForAssetAPIResiliencyStatus`

GetResiliencyStatus returns the ResiliencyStatus field if non-nil, zero value otherwise.

### GetResiliencyStatusOk

`func (o *AssetForAssetAPI) GetResiliencyStatusOk() (*AssetForAssetAPIResiliencyStatus, bool)`

GetResiliencyStatusOk returns a tuple with the ResiliencyStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResiliencyStatus

`func (o *AssetForAssetAPI) SetResiliencyStatus(v AssetForAssetAPIResiliencyStatus)`

SetResiliencyStatus sets ResiliencyStatus field to given value.

### HasResiliencyStatus

`func (o *AssetForAssetAPI) HasResiliencyStatus() bool`

HasResiliencyStatus returns a boolean if a field has been set.

### GetAlarmLastTriggeredTime

`func (o *AssetForAssetAPI) GetAlarmLastTriggeredTime() string`

GetAlarmLastTriggeredTime returns the AlarmLastTriggeredTime field if non-nil, zero value otherwise.

### GetAlarmLastTriggeredTimeOk

`func (o *AssetForAssetAPI) GetAlarmLastTriggeredTimeOk() (*string, bool)`

GetAlarmLastTriggeredTimeOk returns a tuple with the AlarmLastTriggeredTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmLastTriggeredTime

`func (o *AssetForAssetAPI) SetAlarmLastTriggeredTime(v string)`

SetAlarmLastTriggeredTime sets AlarmLastTriggeredTime field to given value.

### HasAlarmLastTriggeredTime

`func (o *AssetForAssetAPI) HasAlarmLastTriggeredTime() bool`

HasAlarmLastTriggeredTime returns a boolean if a field has been set.

### GetAlarmLastClearedTime

`func (o *AssetForAssetAPI) GetAlarmLastClearedTime() string`

GetAlarmLastClearedTime returns the AlarmLastClearedTime field if non-nil, zero value otherwise.

### GetAlarmLastClearedTimeOk

`func (o *AssetForAssetAPI) GetAlarmLastClearedTimeOk() (*string, bool)`

GetAlarmLastClearedTimeOk returns a tuple with the AlarmLastClearedTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlarmLastClearedTime

`func (o *AssetForAssetAPI) SetAlarmLastClearedTime(v string)`

SetAlarmLastClearedTime sets AlarmLastClearedTime field to given value.

### HasAlarmLastClearedTime

`func (o *AssetForAssetAPI) HasAlarmLastClearedTime() bool`

HasAlarmLastClearedTime returns a boolean if a field has been set.

### GetPrimaryParentAsset

`func (o *AssetForAssetAPI) GetPrimaryParentAsset() AssetForAssetAPIPrimaryParentAsset`

GetPrimaryParentAsset returns the PrimaryParentAsset field if non-nil, zero value otherwise.

### GetPrimaryParentAssetOk

`func (o *AssetForAssetAPI) GetPrimaryParentAssetOk() (*AssetForAssetAPIPrimaryParentAsset, bool)`

GetPrimaryParentAssetOk returns a tuple with the PrimaryParentAsset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryParentAsset

`func (o *AssetForAssetAPI) SetPrimaryParentAsset(v AssetForAssetAPIPrimaryParentAsset)`

SetPrimaryParentAsset sets PrimaryParentAsset field to given value.

### HasPrimaryParentAsset

`func (o *AssetForAssetAPI) HasPrimaryParentAsset() bool`

HasPrimaryParentAsset returns a boolean if a field has been set.

### GetAlternateParentAsset

`func (o *AssetForAssetAPI) GetAlternateParentAsset() AssetForAssetAPIAlternateParentAsset`

GetAlternateParentAsset returns the AlternateParentAsset field if non-nil, zero value otherwise.

### GetAlternateParentAssetOk

`func (o *AssetForAssetAPI) GetAlternateParentAssetOk() (*AssetForAssetAPIAlternateParentAsset, bool)`

GetAlternateParentAssetOk returns a tuple with the AlternateParentAsset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternateParentAsset

`func (o *AssetForAssetAPI) SetAlternateParentAsset(v AssetForAssetAPIAlternateParentAsset)`

SetAlternateParentAsset sets AlternateParentAsset field to given value.

### HasAlternateParentAsset

`func (o *AssetForAssetAPI) HasAlternateParentAsset() bool`

HasAlternateParentAsset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


