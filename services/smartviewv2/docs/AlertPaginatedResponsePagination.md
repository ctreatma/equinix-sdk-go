# AlertPaginatedResponsePagination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Offset** | Pointer to **int32** | Starting record index for this page | [optional] 
**Limit** | Pointer to **int32** | Number of records returned per request | [optional] 
**Total** | Pointer to **int32** | Total number of records matching the query | [optional] 

## Methods

### NewAlertPaginatedResponsePagination

`func NewAlertPaginatedResponsePagination() *AlertPaginatedResponsePagination`

NewAlertPaginatedResponsePagination instantiates a new AlertPaginatedResponsePagination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertPaginatedResponsePaginationWithDefaults

`func NewAlertPaginatedResponsePaginationWithDefaults() *AlertPaginatedResponsePagination`

NewAlertPaginatedResponsePaginationWithDefaults instantiates a new AlertPaginatedResponsePagination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOffset

`func (o *AlertPaginatedResponsePagination) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *AlertPaginatedResponsePagination) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *AlertPaginatedResponsePagination) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *AlertPaginatedResponsePagination) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetLimit

`func (o *AlertPaginatedResponsePagination) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AlertPaginatedResponsePagination) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AlertPaginatedResponsePagination) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *AlertPaginatedResponsePagination) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetTotal

`func (o *AlertPaginatedResponsePagination) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AlertPaginatedResponsePagination) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AlertPaginatedResponsePagination) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *AlertPaginatedResponsePagination) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


