# PolicyMaskList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | [**[]PolicyMask**](PolicyMask.md) |  | 
**NextPageToken** | Pointer to **string** | When paging through results, the NextPageToken indicates what page to read next. It is obtained from the previous   call. | [optional] 

## Methods

### NewPolicyMaskList

`func NewPolicyMaskList(list []PolicyMask, ) *PolicyMaskList`

NewPolicyMaskList instantiates a new PolicyMaskList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPolicyMaskListWithDefaults

`func NewPolicyMaskListWithDefaults() *PolicyMaskList`

NewPolicyMaskListWithDefaults instantiates a new PolicyMaskList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *PolicyMaskList) GetList() []PolicyMask`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *PolicyMaskList) GetListOk() (*[]PolicyMask, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *PolicyMaskList) SetList(v []PolicyMask)`

SetList sets List field to given value.


### GetNextPageToken

`func (o *PolicyMaskList) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *PolicyMaskList) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *PolicyMaskList) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *PolicyMaskList) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


