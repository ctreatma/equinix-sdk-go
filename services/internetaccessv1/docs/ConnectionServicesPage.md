# ConnectionServicesPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**Pagination**](Pagination.md) |  | 
**Data** | [**[]ConnectionService**](ConnectionService.md) |  | 

## Methods

### NewConnectionServicesPage

`func NewConnectionServicesPage(pagination Pagination, data []ConnectionService, ) *ConnectionServicesPage`

NewConnectionServicesPage instantiates a new ConnectionServicesPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionServicesPageWithDefaults

`func NewConnectionServicesPageWithDefaults() *ConnectionServicesPage`

NewConnectionServicesPageWithDefaults instantiates a new ConnectionServicesPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *ConnectionServicesPage) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *ConnectionServicesPage) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *ConnectionServicesPage) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.


### GetData

`func (o *ConnectionServicesPage) GetData() []ConnectionService`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ConnectionServicesPage) GetDataOk() (*[]ConnectionService, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ConnectionServicesPage) SetData(v []ConnectionService)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


