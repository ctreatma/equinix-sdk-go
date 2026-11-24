# TicketCodeList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]TicketCode**](TicketCode.md) | Ticket codes on the current page. | 
**Pagination** | [**TicketCodePagination**](TicketCodePagination.md) |  | 

## Methods

### NewTicketCodeList

`func NewTicketCodeList(data []TicketCode, pagination TicketCodePagination, ) *TicketCodeList`

NewTicketCodeList instantiates a new TicketCodeList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketCodeListWithDefaults

`func NewTicketCodeListWithDefaults() *TicketCodeList`

NewTicketCodeListWithDefaults instantiates a new TicketCodeList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TicketCodeList) GetData() []TicketCode`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TicketCodeList) GetDataOk() (*[]TicketCode, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TicketCodeList) SetData(v []TicketCode)`

SetData sets Data field to given value.


### GetPagination

`func (o *TicketCodeList) GetPagination() TicketCodePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *TicketCodeList) GetPaginationOk() (*TicketCodePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *TicketCodeList) SetPagination(v TicketCodePagination)`

SetPagination sets Pagination field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


