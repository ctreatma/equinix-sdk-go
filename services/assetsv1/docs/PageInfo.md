# PageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **int32** | Starting count based on offset. | [optional] 
**Offset** | Pointer to **int32** | Limit count per page. | [optional] 
**Total** | Pointer to **int32** | Matching record count / total number records matched with filter. | [optional] 
**Sorts** | Pointer to [**[]PageInfoSortsInner**](PageInfoSortsInner.md) |  | [optional] 

## Methods

### NewPageInfo

`func NewPageInfo() *PageInfo`

NewPageInfo instantiates a new PageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPageInfoWithDefaults

`func NewPageInfoWithDefaults() *PageInfo`

NewPageInfoWithDefaults instantiates a new PageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *PageInfo) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PageInfo) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PageInfo) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *PageInfo) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *PageInfo) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PageInfo) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PageInfo) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *PageInfo) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetTotal

`func (o *PageInfo) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PageInfo) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PageInfo) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *PageInfo) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetSorts

`func (o *PageInfo) GetSorts() []PageInfoSortsInner`

GetSorts returns the Sorts field if non-nil, zero value otherwise.

### GetSortsOk

`func (o *PageInfo) GetSortsOk() (*[]PageInfoSortsInner, bool)`

GetSortsOk returns a tuple with the Sorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSorts

`func (o *PageInfo) SetSorts(v []PageInfoSortsInner)`

SetSorts sets Sorts field to given value.

### HasSorts

`func (o *PageInfo) HasSorts() bool`

HasSorts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


