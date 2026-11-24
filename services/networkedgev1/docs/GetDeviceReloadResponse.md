# GetDeviceReloadResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**PaginationResponse**](PaginationResponse.md) |  | 
**Data** | [**[]DeviceRebootResponse**](DeviceRebootResponse.md) | Array of available reload history | 

## Methods

### NewGetDeviceReloadResponse

`func NewGetDeviceReloadResponse(pagination PaginationResponse, data []DeviceRebootResponse, ) *GetDeviceReloadResponse`

NewGetDeviceReloadResponse instantiates a new GetDeviceReloadResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceReloadResponseWithDefaults

`func NewGetDeviceReloadResponseWithDefaults() *GetDeviceReloadResponse`

NewGetDeviceReloadResponseWithDefaults instantiates a new GetDeviceReloadResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *GetDeviceReloadResponse) GetPagination() PaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *GetDeviceReloadResponse) GetPaginationOk() (*PaginationResponse, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *GetDeviceReloadResponse) SetPagination(v PaginationResponse)`

SetPagination sets Pagination field to given value.


### GetData

`func (o *GetDeviceReloadResponse) GetData() []DeviceRebootResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDeviceReloadResponse) GetDataOk() (*[]DeviceRebootResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDeviceReloadResponse) SetData(v []DeviceRebootResponse)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


