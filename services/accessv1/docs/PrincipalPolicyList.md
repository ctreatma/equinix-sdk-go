# PrincipalPolicyList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**List** | [**[]PrincipalPolicy**](PrincipalPolicy.md) |  | 
**NextPageToken** | Pointer to **string** | When paging through results, the NextPageToken indicates what page to read next. It is obtained from the previous   call. | [optional] 

## Methods

### NewPrincipalPolicyList

`func NewPrincipalPolicyList(list []PrincipalPolicy, ) *PrincipalPolicyList`

NewPrincipalPolicyList instantiates a new PrincipalPolicyList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrincipalPolicyListWithDefaults

`func NewPrincipalPolicyListWithDefaults() *PrincipalPolicyList`

NewPrincipalPolicyListWithDefaults instantiates a new PrincipalPolicyList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetList

`func (o *PrincipalPolicyList) GetList() []PrincipalPolicy`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *PrincipalPolicyList) GetListOk() (*[]PrincipalPolicy, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *PrincipalPolicyList) SetList(v []PrincipalPolicy)`

SetList sets List field to given value.


### GetNextPageToken

`func (o *PrincipalPolicyList) GetNextPageToken() string`

GetNextPageToken returns the NextPageToken field if non-nil, zero value otherwise.

### GetNextPageTokenOk

`func (o *PrincipalPolicyList) GetNextPageTokenOk() (*string, bool)`

GetNextPageTokenOk returns a tuple with the NextPageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPageToken

`func (o *PrincipalPolicyList) SetNextPageToken(v string)`

SetNextPageToken sets NextPageToken field to given value.

### HasNextPageToken

`func (o *PrincipalPolicyList) HasNextPageToken() bool`

HasNextPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


