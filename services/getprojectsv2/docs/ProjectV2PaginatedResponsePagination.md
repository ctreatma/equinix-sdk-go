# ProjectV2PaginatedResponsePagination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Offset** | Pointer to **int32** | the data items would be fetched from the user input offset point | [optional] 
**Limit** | Pointer to **int32** | max number of data items that can be fetched in current request | [optional] [default to 20]
**Total** | Pointer to **int32** | total number of data items available | [optional] 
**Previous** | Pointer to **interface{}** |  | [optional] 
**Next** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewProjectV2PaginatedResponsePagination

`func NewProjectV2PaginatedResponsePagination() *ProjectV2PaginatedResponsePagination`

NewProjectV2PaginatedResponsePagination instantiates a new ProjectV2PaginatedResponsePagination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectV2PaginatedResponsePaginationWithDefaults

`func NewProjectV2PaginatedResponsePaginationWithDefaults() *ProjectV2PaginatedResponsePagination`

NewProjectV2PaginatedResponsePaginationWithDefaults instantiates a new ProjectV2PaginatedResponsePagination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOffset

`func (o *ProjectV2PaginatedResponsePagination) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ProjectV2PaginatedResponsePagination) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ProjectV2PaginatedResponsePagination) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *ProjectV2PaginatedResponsePagination) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetLimit

`func (o *ProjectV2PaginatedResponsePagination) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ProjectV2PaginatedResponsePagination) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ProjectV2PaginatedResponsePagination) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ProjectV2PaginatedResponsePagination) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetTotal

`func (o *ProjectV2PaginatedResponsePagination) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ProjectV2PaginatedResponsePagination) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ProjectV2PaginatedResponsePagination) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ProjectV2PaginatedResponsePagination) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetPrevious

`func (o *ProjectV2PaginatedResponsePagination) GetPrevious() interface{}`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *ProjectV2PaginatedResponsePagination) GetPreviousOk() (*interface{}, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *ProjectV2PaginatedResponsePagination) SetPrevious(v interface{})`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *ProjectV2PaginatedResponsePagination) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### SetPreviousNil

`func (o *ProjectV2PaginatedResponsePagination) SetPreviousNil(b bool)`

 SetPreviousNil sets the value for Previous to be an explicit nil

### UnsetPrevious
`func (o *ProjectV2PaginatedResponsePagination) UnsetPrevious()`

UnsetPrevious ensures that no value is present for Previous, not even an explicit nil
### GetNext

`func (o *ProjectV2PaginatedResponsePagination) GetNext() interface{}`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *ProjectV2PaginatedResponsePagination) GetNextOk() (*interface{}, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *ProjectV2PaginatedResponsePagination) SetNext(v interface{})`

SetNext sets Next field to given value.

### HasNext

`func (o *ProjectV2PaginatedResponsePagination) HasNext() bool`

HasNext returns a boolean if a field has been set.

### SetNextNil

`func (o *ProjectV2PaginatedResponsePagination) SetNextNil(b bool)`

 SetNextNil sets the value for Next to be an explicit nil

### UnsetNext
`func (o *ProjectV2PaginatedResponsePagination) UnsetNext()`

UnsetNext ensures that no value is present for Next, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


