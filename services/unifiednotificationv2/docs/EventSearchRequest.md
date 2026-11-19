# EventSearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filter** | Pointer to [**Filter**](Filter.md) |  | [optional] 
**Sort** | Pointer to [**[]SortCriteria**](SortCriteria.md) |  | [optional] 
**Pagination** | Pointer to [**PaginationRequest**](PaginationRequest.md) |  | [optional] 

## Methods

### NewEventSearchRequest

`func NewEventSearchRequest() *EventSearchRequest`

NewEventSearchRequest instantiates a new EventSearchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventSearchRequestWithDefaults

`func NewEventSearchRequestWithDefaults() *EventSearchRequest`

NewEventSearchRequestWithDefaults instantiates a new EventSearchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilter

`func (o *EventSearchRequest) GetFilter() Filter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *EventSearchRequest) GetFilterOk() (*Filter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *EventSearchRequest) SetFilter(v Filter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *EventSearchRequest) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### GetSort

`func (o *EventSearchRequest) GetSort() []SortCriteria`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *EventSearchRequest) GetSortOk() (*[]SortCriteria, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *EventSearchRequest) SetSort(v []SortCriteria)`

SetSort sets Sort field to given value.

### HasSort

`func (o *EventSearchRequest) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetPagination

`func (o *EventSearchRequest) GetPagination() PaginationRequest`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *EventSearchRequest) GetPaginationOk() (*PaginationRequest, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *EventSearchRequest) SetPagination(v PaginationRequest)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *EventSearchRequest) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


