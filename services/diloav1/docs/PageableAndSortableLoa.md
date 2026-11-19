# PageableAndSortableLoa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**Pagination**](Pagination.md) |  | 
**Sort** | [**[]Sort**](Sort.md) | Search results sorting settings. | 
**Data** | [**[]Loa**](Loa.md) | Data set containing Digital LOA documents. | 

## Methods

### NewPageableAndSortableLoa

`func NewPageableAndSortableLoa(pagination Pagination, sort []Sort, data []Loa, ) *PageableAndSortableLoa`

NewPageableAndSortableLoa instantiates a new PageableAndSortableLoa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPageableAndSortableLoaWithDefaults

`func NewPageableAndSortableLoaWithDefaults() *PageableAndSortableLoa`

NewPageableAndSortableLoaWithDefaults instantiates a new PageableAndSortableLoa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *PageableAndSortableLoa) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *PageableAndSortableLoa) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *PageableAndSortableLoa) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.


### GetSort

`func (o *PageableAndSortableLoa) GetSort() []Sort`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *PageableAndSortableLoa) GetSortOk() (*[]Sort, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *PageableAndSortableLoa) SetSort(v []Sort)`

SetSort sets Sort field to given value.


### GetData

`func (o *PageableAndSortableLoa) GetData() []Loa`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PageableAndSortableLoa) GetDataOk() (*[]Loa, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PageableAndSortableLoa) SetData(v []Loa)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


