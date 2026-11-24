# InvoiceSummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]InvoiceSummaryDetails**](InvoiceSummaryDetails.md) |  | [optional] 
**Pagination** | Pointer to [**PaginationSummary**](PaginationSummary.md) |  | [optional] 

## Methods

### NewInvoiceSummaryResponse

`func NewInvoiceSummaryResponse() *InvoiceSummaryResponse`

NewInvoiceSummaryResponse instantiates a new InvoiceSummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceSummaryResponseWithDefaults

`func NewInvoiceSummaryResponseWithDefaults() *InvoiceSummaryResponse`

NewInvoiceSummaryResponseWithDefaults instantiates a new InvoiceSummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *InvoiceSummaryResponse) GetData() []InvoiceSummaryDetails`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *InvoiceSummaryResponse) GetDataOk() (*[]InvoiceSummaryDetails, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *InvoiceSummaryResponse) SetData(v []InvoiceSummaryDetails)`

SetData sets Data field to given value.

### HasData

`func (o *InvoiceSummaryResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPagination

`func (o *InvoiceSummaryResponse) GetPagination() PaginationSummary`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *InvoiceSummaryResponse) GetPaginationOk() (*PaginationSummary, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *InvoiceSummaryResponse) SetPagination(v PaginationSummary)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *InvoiceSummaryResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


