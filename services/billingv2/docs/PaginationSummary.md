# PaginationSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Offset** | Pointer to **int32** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 
**Next** | Pointer to **string** |  | [optional] 
**Previous** | Pointer to **string** |  | [optional] 

## Methods

### NewPaginationSummary

`func NewPaginationSummary() *PaginationSummary`

NewPaginationSummary instantiates a new PaginationSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginationSummaryWithDefaults

`func NewPaginationSummaryWithDefaults() *PaginationSummary`

NewPaginationSummaryWithDefaults instantiates a new PaginationSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOffset

`func (o *PaginationSummary) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PaginationSummary) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PaginationSummary) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *PaginationSummary) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetLimit

`func (o *PaginationSummary) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PaginationSummary) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PaginationSummary) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *PaginationSummary) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetTotal

`func (o *PaginationSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PaginationSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PaginationSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *PaginationSummary) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetNext

`func (o *PaginationSummary) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginationSummary) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginationSummary) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginationSummary) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *PaginationSummary) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginationSummary) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginationSummary) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginationSummary) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


