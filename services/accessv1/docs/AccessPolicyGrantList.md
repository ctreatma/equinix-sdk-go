# AccessPolicyGrantList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | [**[]AccessPolicyGrant**](AccessPolicyGrant.md) |  | 
**NextPageToken** | Pointer to **string** | When paging through results, the NextPageToken indicates what page to read next. It is obtained from the previous   call. | [optional] 

## Methods

### NewAccessPolicyGrantList

`func NewAccessPolicyGrantList(list []AccessPolicyGrant, ) *AccessPolicyGrantList`

NewAccessPolicyGrantList instantiates a new AccessPolicyGrantList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPolicyGrantListWithDefaults

`func NewAccessPolicyGrantListWithDefaults() *AccessPolicyGrantList`

NewAccessPolicyGrantListWithDefaults instantiates a new AccessPolicyGrantList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *AccessPolicyGrantList) GetList() []AccessPolicyGrant`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *AccessPolicyGrantList) GetListOk() (*[]AccessPolicyGrant, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *AccessPolicyGrantList) SetList(v []AccessPolicyGrant)`

SetList sets List field to given value.


### GetNextPageToken

`func (o *AccessPolicyGrantList) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *AccessPolicyGrantList) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *AccessPolicyGrantList) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *AccessPolicyGrantList) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


