# TicketCodePagination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** | Total number of ticket codes matching the request across all pages. | 
**Offset** | **int32** | Zero-based index of the first item on the current page. | 
**Limit** | **int32** | Maximum number of items returned per page. | 
**Next** | Pointer to **string** | Relative URL of the next page. Omitted from the response when the current page is the last page. | [optional] 
**Previous** | Pointer to **string** | Relative URL of the previous page. Omitted from the response when the current page is the first page. | [optional] 

## Methods

### NewTicketCodePagination

`func NewTicketCodePagination(total int32, offset int32, limit int32, ) *TicketCodePagination`

NewTicketCodePagination instantiates a new TicketCodePagination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketCodePaginationWithDefaults

`func NewTicketCodePaginationWithDefaults() *TicketCodePagination`

NewTicketCodePaginationWithDefaults instantiates a new TicketCodePagination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *TicketCodePagination) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *TicketCodePagination) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *TicketCodePagination) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetOffset

`func (o *TicketCodePagination) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *TicketCodePagination) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *TicketCodePagination) SetOffset(v int32)`

SetOffset sets Offset field to given value.


### GetLimit

`func (o *TicketCodePagination) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *TicketCodePagination) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *TicketCodePagination) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetNext

`func (o *TicketCodePagination) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *TicketCodePagination) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *TicketCodePagination) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *TicketCodePagination) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *TicketCodePagination) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *TicketCodePagination) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *TicketCodePagination) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *TicketCodePagination) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


