# PowerEventsPaginatedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | Pointer to [**[]PowerEventReadModel**](PowerEventReadModel.md) | Array of power events | [optional] 
**Limit** | Pointer to **int32** | Number of records returned per request | [optional] 
**Offset** | Pointer to **int32** | Starting record index for this page | [optional] 
**TotalCount** | Pointer to **int32** | Total number of records matching the query | [optional] 

## Methods

### NewPowerEventsPaginatedResponse

`func NewPowerEventsPaginatedResponse() *PowerEventsPaginatedResponse`

NewPowerEventsPaginatedResponse instantiates a new PowerEventsPaginatedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerEventsPaginatedResponseWithDefaults

`func NewPowerEventsPaginatedResponseWithDefaults() *PowerEventsPaginatedResponse`

NewPowerEventsPaginatedResponseWithDefaults instantiates a new PowerEventsPaginatedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PowerEventsPaginatedResponse) GetItems() []PowerEventReadModel`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PowerEventsPaginatedResponse) GetItemsOk() (*[]PowerEventReadModel, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PowerEventsPaginatedResponse) SetItems(v []PowerEventReadModel)`

SetItems sets Items field to given value.

### HasItems

`func (o *PowerEventsPaginatedResponse) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetLimit

`func (o *PowerEventsPaginatedResponse) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PowerEventsPaginatedResponse) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PowerEventsPaginatedResponse) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *PowerEventsPaginatedResponse) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *PowerEventsPaginatedResponse) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PowerEventsPaginatedResponse) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PowerEventsPaginatedResponse) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *PowerEventsPaginatedResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetTotalCount

`func (o *PowerEventsPaginatedResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *PowerEventsPaginatedResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *PowerEventsPaginatedResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *PowerEventsPaginatedResponse) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


