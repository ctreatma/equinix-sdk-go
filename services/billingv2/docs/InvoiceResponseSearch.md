# InvoiceResponseSearch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]InvoiceItems**](InvoiceItems.md) |  | [optional] 
**Pagination** | Pointer to [**PaginationSearch**](PaginationSearch.md) |  | [optional] 

## Methods

### NewInvoiceResponseSearch

`func NewInvoiceResponseSearch() *InvoiceResponseSearch`

NewInvoiceResponseSearch instantiates a new InvoiceResponseSearch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceResponseSearchWithDefaults

`func NewInvoiceResponseSearchWithDefaults() *InvoiceResponseSearch`

NewInvoiceResponseSearchWithDefaults instantiates a new InvoiceResponseSearch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *InvoiceResponseSearch) GetData() []InvoiceItems`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *InvoiceResponseSearch) GetDataOk() (*[]InvoiceItems, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *InvoiceResponseSearch) SetData(v []InvoiceItems)`

SetData sets Data field to given value.

### HasData

`func (o *InvoiceResponseSearch) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPagination

`func (o *InvoiceResponseSearch) GetPagination() PaginationSearch`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *InvoiceResponseSearch) GetPaginationOk() (*PaginationSearch, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *InvoiceResponseSearch) SetPagination(v PaginationSearch)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *InvoiceResponseSearch) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


