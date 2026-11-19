# SearchPagination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Offset** | **int64** | Starting index of an item. First item is offset 0. Default value for offset is 0. | 
**Limit** | **int32** | The maximum number of items to return starting from the index denotes by the offset item. Default value for limit is 20. Upper limit is 1000 | 

## Methods

### NewSearchPagination

`func NewSearchPagination(offset int64, limit int32, ) *SearchPagination`

NewSearchPagination instantiates a new SearchPagination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchPaginationWithDefaults

`func NewSearchPaginationWithDefaults() *SearchPagination`

NewSearchPaginationWithDefaults instantiates a new SearchPagination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOffset

`func (o *SearchPagination) GetOffset() int64`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *SearchPagination) GetOffsetOk() (*int64, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *SearchPagination) SetOffset(v int64)`

SetOffset sets Offset field to given value.


### GetLimit

`func (o *SearchPagination) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SearchPagination) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SearchPagination) SetLimit(v int32)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


