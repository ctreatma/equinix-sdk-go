# LoaChange

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedDateTime** | Pointer to **time.Time** | Date and time of Digital LOA change creation. | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** | Date and time of Digital LOA change update. | [optional] 
**Data** | Pointer to **string** | Changes to Digital LOA according to JSON representation. | [optional] 
**Description** | Pointer to **string** | Additional Digital LOA change information. | [optional] 
**Href** | Pointer to **string** | Digital LOA document URI. | [optional] 
**Links** | Pointer to [**[]Link**](Link.md) | HATEOAS links specifying possible follow-up interactions. | [optional] 
**Type** | Pointer to [**LoaChangeType**](LoaChangeType.md) |  | [optional] 
**Uuid** | Pointer to **string** | Digital LOA change unique identifier. | [optional] 
**Status** | Pointer to [**LoaChangeStatus**](LoaChangeStatus.md) |  | [optional] 
**Result** | Pointer to [**ChangeResult**](ChangeResult.md) |  | [optional] 

## Methods

### NewLoaChange

`func NewLoaChange() *LoaChange`

NewLoaChange instantiates a new LoaChange object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoaChangeWithDefaults

`func NewLoaChangeWithDefaults() *LoaChange`

NewLoaChangeWithDefaults instantiates a new LoaChange object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedDateTime

`func (o *LoaChange) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *LoaChange) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *LoaChange) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *LoaChange) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *LoaChange) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *LoaChange) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *LoaChange) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *LoaChange) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetData

`func (o *LoaChange) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *LoaChange) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *LoaChange) SetData(v string)`

SetData sets Data field to given value.

### HasData

`func (o *LoaChange) HasData() bool`

HasData returns a boolean if a field has been set.

### GetDescription

`func (o *LoaChange) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LoaChange) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LoaChange) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LoaChange) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetHref

`func (o *LoaChange) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *LoaChange) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *LoaChange) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *LoaChange) HasHref() bool`

HasHref returns a boolean if a field has been set.

### GetLinks

`func (o *LoaChange) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *LoaChange) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *LoaChange) SetLinks(v []Link)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *LoaChange) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetType

`func (o *LoaChange) GetType() LoaChangeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *LoaChange) GetTypeOk() (*LoaChangeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *LoaChange) SetType(v LoaChangeType)`

SetType sets Type field to given value.

### HasType

`func (o *LoaChange) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUuid

`func (o *LoaChange) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *LoaChange) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *LoaChange) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *LoaChange) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetStatus

`func (o *LoaChange) GetStatus() LoaChangeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LoaChange) GetStatusOk() (*LoaChangeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LoaChange) SetStatus(v LoaChangeStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LoaChange) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetResult

`func (o *LoaChange) GetResult() ChangeResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *LoaChange) GetResultOk() (*ChangeResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *LoaChange) SetResult(v ChangeResult)`

SetResult sets Result field to given value.

### HasResult

`func (o *LoaChange) HasResult() bool`

HasResult returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


