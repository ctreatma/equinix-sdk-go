# GetLinksResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**PaginationResponse**](PaginationResponse.md) |  | 
**Data** | [**[]DeviceLinkGroup**](DeviceLinkGroup.md) | Array of available links | 

## Methods

### NewGetLinksResponse

`func NewGetLinksResponse(pagination PaginationResponse, data []DeviceLinkGroup, ) *GetLinksResponse`

NewGetLinksResponse instantiates a new GetLinksResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetLinksResponseWithDefaults

`func NewGetLinksResponseWithDefaults() *GetLinksResponse`

NewGetLinksResponseWithDefaults instantiates a new GetLinksResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *GetLinksResponse) GetPagination() PaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *GetLinksResponse) GetPaginationOk() (*PaginationResponse, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *GetLinksResponse) SetPagination(v PaginationResponse)`

SetPagination sets Pagination field to given value.


### GetData

`func (o *GetLinksResponse) GetData() []DeviceLinkGroup`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetLinksResponse) GetDataOk() (*[]DeviceLinkGroup, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetLinksResponse) SetData(v []DeviceLinkGroup)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


