# ChangeApproved

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Uniquely identifies a change | 
**Type** | [**ChangeType**](ChangeType.md) |  | 
**Status** | **string** |  | [default to "APPROVED"]
**CreatedDateTime** | **time.Time** | Set when change flow starts | 
**UpdatedDateTime** | Pointer to **time.Time** | Set when change object is updated | [optional] 
**Information** | Pointer to **string** | Additional information | [optional] 
**Data** | [**ChangeData**](ChangeData.md) |  | 

## Methods

### NewChangeApproved

`func NewChangeApproved(uuid string, type_ ChangeType, status string, createdDateTime time.Time, data ChangeData, ) *ChangeApproved`

NewChangeApproved instantiates a new ChangeApproved object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeApprovedWithDefaults

`func NewChangeApprovedWithDefaults() *ChangeApproved`

NewChangeApprovedWithDefaults instantiates a new ChangeApproved object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ChangeApproved) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ChangeApproved) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ChangeApproved) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *ChangeApproved) GetType() ChangeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ChangeApproved) GetTypeOk() (*ChangeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ChangeApproved) SetType(v ChangeType)`

SetType sets Type field to given value.


### GetStatus

`func (o *ChangeApproved) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ChangeApproved) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ChangeApproved) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedDateTime

`func (o *ChangeApproved) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *ChangeApproved) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *ChangeApproved) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.


### GetUpdatedDateTime

`func (o *ChangeApproved) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *ChangeApproved) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *ChangeApproved) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *ChangeApproved) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetInformation

`func (o *ChangeApproved) GetInformation() string`

GetInformation returns the Information field if non-nil, zero value otherwise.

### GetInformationOk

`func (o *ChangeApproved) GetInformationOk() (*string, bool)`

GetInformationOk returns a tuple with the Information field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformation

`func (o *ChangeApproved) SetInformation(v string)`

SetInformation sets Information field to given value.

### HasInformation

`func (o *ChangeApproved) HasInformation() bool`

HasInformation returns a boolean if a field has been set.

### GetData

`func (o *ChangeApproved) GetData() ChangeData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ChangeApproved) GetDataOk() (*ChangeData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ChangeApproved) SetData(v ChangeData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


