# InvoiceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]InvoiceItems**](InvoiceItems.md) |  | [optional] 
**Pagination** | Pointer to [**Pagination**](Pagination.md) |  | [optional] 

## Methods

### NewInvoiceResponse

`func NewInvoiceResponse() *InvoiceResponse`

NewInvoiceResponse instantiates a new InvoiceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceResponseWithDefaults

`func NewInvoiceResponseWithDefaults() *InvoiceResponse`

NewInvoiceResponseWithDefaults instantiates a new InvoiceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *InvoiceResponse) GetData() []InvoiceItems`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *InvoiceResponse) GetDataOk() (*[]InvoiceItems, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *InvoiceResponse) SetData(v []InvoiceItems)`

SetData sets Data field to given value.

### HasData

`func (o *InvoiceResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPagination

`func (o *InvoiceResponse) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *InvoiceResponse) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *InvoiceResponse) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *InvoiceResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


