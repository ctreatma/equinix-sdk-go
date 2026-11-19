# AccessPolicyList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | [**[]AccessPolicy**](AccessPolicy.md) |  | 
**NextPageToken** | Pointer to **string** | When paging through results, the NextPageToken indicates what page to read next. It is obtained from the previous   call. | [optional] 

## Methods

### NewAccessPolicyList

`func NewAccessPolicyList(list []AccessPolicy, ) *AccessPolicyList`

NewAccessPolicyList instantiates a new AccessPolicyList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPolicyListWithDefaults

`func NewAccessPolicyListWithDefaults() *AccessPolicyList`

NewAccessPolicyListWithDefaults instantiates a new AccessPolicyList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *AccessPolicyList) GetList() []AccessPolicy`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *AccessPolicyList) GetListOk() (*[]AccessPolicy, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *AccessPolicyList) SetList(v []AccessPolicy)`

SetList sets List field to given value.


### GetNextPageToken

`func (o *AccessPolicyList) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *AccessPolicyList) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *AccessPolicyList) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *AccessPolicyList) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


