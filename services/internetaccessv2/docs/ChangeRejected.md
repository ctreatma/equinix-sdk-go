# ChangeRejected

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Uniquely identifies a change | 
**Type** | [**ChangeType**](ChangeType.md) |  | 
**Status** | **string** |  | [default to "REJECTED"]
**CreatedDateTime** | **time.Time** | Set when change flow starts | 
**UpdatedDateTime** | Pointer to **time.Time** | Set when change object is updated | [optional] 
**Information** | Pointer to **string** | Additional information | [optional] 
**Data** | [**ChangeRejectedData**](ChangeRejectedData.md) |  | 

## Methods

### NewChangeRejected

`func NewChangeRejected(uuid string, type_ ChangeType, status string, createdDateTime time.Time, data ChangeRejectedData, ) *ChangeRejected`

NewChangeRejected instantiates a new ChangeRejected object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeRejectedWithDefaults

`func NewChangeRejectedWithDefaults() *ChangeRejected`

NewChangeRejectedWithDefaults instantiates a new ChangeRejected object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ChangeRejected) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ChangeRejected) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ChangeRejected) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *ChangeRejected) GetType() ChangeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ChangeRejected) GetTypeOk() (*ChangeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ChangeRejected) SetType(v ChangeType)`

SetType sets Type field to given value.


### GetStatus

`func (o *ChangeRejected) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ChangeRejected) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ChangeRejected) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedDateTime

`func (o *ChangeRejected) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *ChangeRejected) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *ChangeRejected) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.


### GetUpdatedDateTime

`func (o *ChangeRejected) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *ChangeRejected) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *ChangeRejected) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *ChangeRejected) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetInformation

`func (o *ChangeRejected) GetInformation() string`

GetInformation returns the Information field if non-nil, zero value otherwise.

### GetInformationOk

`func (o *ChangeRejected) GetInformationOk() (*string, bool)`

GetInformationOk returns a tuple with the Information field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformation

`func (o *ChangeRejected) SetInformation(v string)`

SetInformation sets Information field to given value.

### HasInformation

`func (o *ChangeRejected) HasInformation() bool`

HasInformation returns a boolean if a field has been set.

### GetData

`func (o *ChangeRejected) GetData() ChangeRejectedData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ChangeRejected) GetDataOk() (*ChangeRejectedData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ChangeRejected) SetData(v ChangeRejectedData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


