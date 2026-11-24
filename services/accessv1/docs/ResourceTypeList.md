# ResourceTypeList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | [**[]ResourceType**](ResourceType.md) |  | 
**NextPageToken** | Pointer to **string** | When paging through results, the NextPageToken indicates what page to read next. It is obtained from the previous   call. | [optional] 

## Methods

### NewResourceTypeList

`func NewResourceTypeList(list []ResourceType, ) *ResourceTypeList`

NewResourceTypeList instantiates a new ResourceTypeList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceTypeListWithDefaults

`func NewResourceTypeListWithDefaults() *ResourceTypeList`

NewResourceTypeListWithDefaults instantiates a new ResourceTypeList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *ResourceTypeList) GetList() []ResourceType`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *ResourceTypeList) GetListOk() (*[]ResourceType, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *ResourceTypeList) SetList(v []ResourceType)`

SetList sets List field to given value.


### GetNextPageToken

`func (o *ResourceTypeList) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *ResourceTypeList) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *ResourceTypeList) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *ResourceTypeList) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


