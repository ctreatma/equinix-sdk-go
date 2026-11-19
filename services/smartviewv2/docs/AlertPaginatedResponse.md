# AlertPaginatedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AlertConfigurationReadModel**](AlertConfigurationReadModel.md) | Array of power alert configurations | [optional] 
**Pagination** | Pointer to [**AlertPaginatedResponsePagination**](AlertPaginatedResponsePagination.md) |  | [optional] 

## Methods

### NewAlertPaginatedResponse

`func NewAlertPaginatedResponse() *AlertPaginatedResponse`

NewAlertPaginatedResponse instantiates a new AlertPaginatedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertPaginatedResponseWithDefaults

`func NewAlertPaginatedResponseWithDefaults() *AlertPaginatedResponse`

NewAlertPaginatedResponseWithDefaults instantiates a new AlertPaginatedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AlertPaginatedResponse) GetData() []AlertConfigurationReadModel`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AlertPaginatedResponse) GetDataOk() (*[]AlertConfigurationReadModel, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AlertPaginatedResponse) SetData(v []AlertConfigurationReadModel)`

SetData sets Data field to given value.

### HasData

`func (o *AlertPaginatedResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPagination

`func (o *AlertPaginatedResponse) GetPagination() AlertPaginatedResponsePagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *AlertPaginatedResponse) GetPaginationOk() (*AlertPaginatedResponsePagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *AlertPaginatedResponse) SetPagination(v AlertPaginatedResponsePagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *AlertPaginatedResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


