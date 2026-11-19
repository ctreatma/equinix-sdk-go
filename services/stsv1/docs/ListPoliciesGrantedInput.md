# ListPoliciesGrantedInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **string** | Globally unique identifier of a project. | 
**SubjectToken** | **string** | An ID or access token indicating the subject to list granted access policies for | 
**SubjectTokenType** | [**ListPoliciesGrantedInputSubjectTokenType**](ListPoliciesGrantedInputSubjectTokenType.md) |  | 
**PageSize** | Pointer to **int32** | When paging through results, this is an integer indicating the maximum number of results to return. Note, it is   possible for fewer results to be returned even when the end of the result set has not been reached. | [optional] 
**PageToken** | Pointer to **string** | When paging through results, the PageToken is an opaque indicator that identifies a page. | [optional] 

## Methods

### NewListPoliciesGrantedInput

`func NewListPoliciesGrantedInput(projectId string, subjectToken string, subjectTokenType ListPoliciesGrantedInputSubjectTokenType, ) *ListPoliciesGrantedInput`

NewListPoliciesGrantedInput instantiates a new ListPoliciesGrantedInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListPoliciesGrantedInputWithDefaults

`func NewListPoliciesGrantedInputWithDefaults() *ListPoliciesGrantedInput`

NewListPoliciesGrantedInputWithDefaults instantiates a new ListPoliciesGrantedInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ListPoliciesGrantedInput) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ListPoliciesGrantedInput) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ListPoliciesGrantedInput) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetSubjectToken

`func (o *ListPoliciesGrantedInput) GetSubjectToken() string`

GetSubjectToken returns the SubjectToken field if non-nil, zero value otherwise.

### GetSubjectTokenOk

`func (o *ListPoliciesGrantedInput) GetSubjectTokenOk() (*string, bool)`

GetSubjectTokenOk returns a tuple with the SubjectToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectToken

`func (o *ListPoliciesGrantedInput) SetSubjectToken(v string)`

SetSubjectToken sets SubjectToken field to given value.


### GetSubjectTokenType

`func (o *ListPoliciesGrantedInput) GetSubjectTokenType() ListPoliciesGrantedInputSubjectTokenType`

GetSubjectTokenType returns the SubjectTokenType field if non-nil, zero value otherwise.

### GetSubjectTokenTypeOk

`func (o *ListPoliciesGrantedInput) GetSubjectTokenTypeOk() (*ListPoliciesGrantedInputSubjectTokenType, bool)`

GetSubjectTokenTypeOk returns a tuple with the SubjectTokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectTokenType

`func (o *ListPoliciesGrantedInput) SetSubjectTokenType(v ListPoliciesGrantedInputSubjectTokenType)`

SetSubjectTokenType sets SubjectTokenType field to given value.


### GetPageSize

`func (o *ListPoliciesGrantedInput) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *ListPoliciesGrantedInput) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *ListPoliciesGrantedInput) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.

### HasPageSize

`func (o *ListPoliciesGrantedInput) HasPageSize() bool`

HasPageSize returns a boolean if a field has been set.

### GetPageToken

`func (o *ListPoliciesGrantedInput) GetPageToken() string`

GetPageToken returns the PageToken field if non-nil, zero value otherwise.

### GetPageTokenOk

`func (o *ListPoliciesGrantedInput) GetPageTokenOk() (*string, bool)`

GetPageTokenOk returns a tuple with the PageToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageToken

`func (o *ListPoliciesGrantedInput) SetPageToken(v string)`

SetPageToken sets PageToken field to given value.

### HasPageToken

`func (o *ListPoliciesGrantedInput) HasPageToken() bool`

HasPageToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


