# PreviousBackups

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | The unique Id of a backup. | [optional] 
**Status** | Pointer to [**DeviceBackupInfoVerboseStatus**](DeviceBackupInfoVerboseStatus.md) |  | [optional] 
**CreatedBy** | Pointer to **string** | Created by. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Created date. | [optional] 
**LastUpdatedDateTime** | Pointer to **time.Time** | Last updated date. | [optional] 

## Methods

### NewPreviousBackups

`func NewPreviousBackups() *PreviousBackups`

NewPreviousBackups instantiates a new PreviousBackups object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPreviousBackupsWithDefaults

`func NewPreviousBackupsWithDefaults() *PreviousBackups`

NewPreviousBackupsWithDefaults instantiates a new PreviousBackups object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *PreviousBackups) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PreviousBackups) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PreviousBackups) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *PreviousBackups) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetStatus

`func (o *PreviousBackups) GetStatus() DeviceBackupInfoVerboseStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PreviousBackups) GetStatusOk() (*DeviceBackupInfoVerboseStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PreviousBackups) SetStatus(v DeviceBackupInfoVerboseStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PreviousBackups) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedBy

`func (o *PreviousBackups) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *PreviousBackups) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *PreviousBackups) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *PreviousBackups) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *PreviousBackups) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *PreviousBackups) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *PreviousBackups) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *PreviousBackups) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetLastUpdatedDateTime

`func (o *PreviousBackups) GetLastUpdatedDateTime() time.Time`

GetLastUpdatedDateTime returns the LastUpdatedDateTime field if non-nil, zero value otherwise.

### GetLastUpdatedDateTimeOk

`func (o *PreviousBackups) GetLastUpdatedDateTimeOk() (*time.Time, bool)`

GetLastUpdatedDateTimeOk returns a tuple with the LastUpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedDateTime

`func (o *PreviousBackups) SetLastUpdatedDateTime(v time.Time)`

SetLastUpdatedDateTime sets LastUpdatedDateTime field to given value.

### HasLastUpdatedDateTime

`func (o *PreviousBackups) HasLastUpdatedDateTime() bool`

HasLastUpdatedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


