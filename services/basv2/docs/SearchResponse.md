# SearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | Pointer to [**SearchResponsePagination**](SearchResponsePagination.md) |  | [optional] 
**Data** | Pointer to [**[]BillingAccount**](BillingAccount.md) | Search result | [optional] 

## Methods

### NewSearchResponse

`func NewSearchResponse() *SearchResponse`

NewSearchResponse instantiates a new SearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchResponseWithDefaults

`func NewSearchResponseWithDefaults() *SearchResponse`

NewSearchResponseWithDefaults instantiates a new SearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *SearchResponse) GetPagination() SearchResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *SearchResponse) GetPaginationOk() (*SearchResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *SearchResponse) SetPagination(v SearchResponsePagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *SearchResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.

### GetData

`func (o *SearchResponse) GetData() []BillingAccount`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SearchResponse) GetDataOk() (*[]BillingAccount, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SearchResponse) SetData(v []BillingAccount)`

SetData sets Data field to given value.

### HasData

`func (o *SearchResponse) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


