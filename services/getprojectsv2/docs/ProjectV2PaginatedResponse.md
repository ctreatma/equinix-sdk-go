# ProjectV2PaginatedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | Pointer to [**ProjectV2PaginatedResponsePagination**](ProjectV2PaginatedResponsePagination.md) |  | [optional] 
**Data** | Pointer to [**[]ProjectV2Response**](ProjectV2Response.md) |  | [optional] 

## Methods

### NewProjectV2PaginatedResponse

`func NewProjectV2PaginatedResponse() *ProjectV2PaginatedResponse`

NewProjectV2PaginatedResponse instantiates a new ProjectV2PaginatedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectV2PaginatedResponseWithDefaults

`func NewProjectV2PaginatedResponseWithDefaults() *ProjectV2PaginatedResponse`

NewProjectV2PaginatedResponseWithDefaults instantiates a new ProjectV2PaginatedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *ProjectV2PaginatedResponse) GetPagination() ProjectV2PaginatedResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *ProjectV2PaginatedResponse) GetPaginationOk() (*ProjectV2PaginatedResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *ProjectV2PaginatedResponse) SetPagination(v ProjectV2PaginatedResponsePagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *ProjectV2PaginatedResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.

### GetData

`func (o *ProjectV2PaginatedResponse) GetData() []ProjectV2Response`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ProjectV2PaginatedResponse) GetDataOk() (*[]ProjectV2Response, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ProjectV2PaginatedResponse) SetData(v []ProjectV2Response)`

SetData sets Data field to given value.

### HasData

`func (o *ProjectV2PaginatedResponse) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


