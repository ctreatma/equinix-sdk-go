# PaginationSearch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Offset** | Pointer to **int32** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Next** | Pointer to **string** |  | [optional] 
**Previous** | Pointer to **string** |  | [optional] 

## Methods

### NewPaginationSearch

`func NewPaginationSearch() *PaginationSearch`

NewPaginationSearch instantiates a new PaginationSearch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginationSearchWithDefaults

`func NewPaginationSearchWithDefaults() *PaginationSearch`

NewPaginationSearchWithDefaults instantiates a new PaginationSearch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOffset

`func (o *PaginationSearch) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PaginationSearch) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PaginationSearch) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *PaginationSearch) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetLimit

`func (o *PaginationSearch) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PaginationSearch) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PaginationSearch) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *PaginationSearch) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetTotal

`func (o *PaginationSearch) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PaginationSearch) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PaginationSearch) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *PaginationSearch) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetNext

`func (o *PaginationSearch) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginationSearch) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginationSearch) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginationSearch) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *PaginationSearch) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginationSearch) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginationSearch) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginationSearch) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


