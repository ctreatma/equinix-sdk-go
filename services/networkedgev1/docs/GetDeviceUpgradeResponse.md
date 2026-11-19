# GetDeviceUpgradeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**PaginationResponse**](PaginationResponse.md) |  | 
**Data** | [**[]DeviceUpgradeDetailsResponse**](DeviceUpgradeDetailsResponse.md) | Array of available upgrade history | 

## Methods

### NewGetDeviceUpgradeResponse

`func NewGetDeviceUpgradeResponse(pagination PaginationResponse, data []DeviceUpgradeDetailsResponse, ) *GetDeviceUpgradeResponse`

NewGetDeviceUpgradeResponse instantiates a new GetDeviceUpgradeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceUpgradeResponseWithDefaults

`func NewGetDeviceUpgradeResponseWithDefaults() *GetDeviceUpgradeResponse`

NewGetDeviceUpgradeResponseWithDefaults instantiates a new GetDeviceUpgradeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *GetDeviceUpgradeResponse) GetPagination() PaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *GetDeviceUpgradeResponse) GetPaginationOk() (*PaginationResponse, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *GetDeviceUpgradeResponse) SetPagination(v PaginationResponse)`

SetPagination sets Pagination field to given value.


### GetData

`func (o *GetDeviceUpgradeResponse) GetData() []DeviceUpgradeDetailsResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDeviceUpgradeResponse) GetDataOk() (*[]DeviceUpgradeDetailsResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDeviceUpgradeResponse) SetData(v []DeviceUpgradeDetailsResponse)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


