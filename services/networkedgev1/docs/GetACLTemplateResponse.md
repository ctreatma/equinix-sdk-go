# GetACLTemplateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pagination** | [**PaginationResponse**](PaginationResponse.md) |  | 
**Data** | [**[]DeviceACLDetailsResponse**](DeviceACLDetailsResponse.md) | Array of available ACL templates | 

## Methods

### NewGetACLTemplateResponse

`func NewGetACLTemplateResponse(pagination PaginationResponse, data []DeviceACLDetailsResponse, ) *GetACLTemplateResponse`

NewGetACLTemplateResponse instantiates a new GetACLTemplateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetACLTemplateResponseWithDefaults

`func NewGetACLTemplateResponseWithDefaults() *GetACLTemplateResponse`

NewGetACLTemplateResponseWithDefaults instantiates a new GetACLTemplateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPagination

`func (o *GetACLTemplateResponse) GetPagination() PaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *GetACLTemplateResponse) GetPaginationOk() (*PaginationResponse, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *GetACLTemplateResponse) SetPagination(v PaginationResponse)`

SetPagination sets Pagination field to given value.


### GetData

`func (o *GetACLTemplateResponse) GetData() []DeviceACLDetailsResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetACLTemplateResponse) GetDataOk() (*[]DeviceACLDetailsResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetACLTemplateResponse) SetData(v []DeviceACLDetailsResponse)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


