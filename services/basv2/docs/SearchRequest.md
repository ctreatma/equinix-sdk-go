# SearchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IbxCode** | Pointer to **string** | IBX where billing account can place order. | [optional] 
**MetroCode** | Pointer to **string** | Metro where billing account can place order. | [optional] 
**AccountStatus** | Pointer to [**[]AccountStatus**](AccountStatus.md) | List of account status to search. | [optional] 
**ProjectId** | Pointer to **string** | Project id where billing account associated with. | [optional] 
**Limit** | Pointer to **int32** | Specifies the page size. | [optional] [default to 100]
**Offset** | Pointer to **int32** | Specifies where to start a page. It is the starting point of the collection returned from the server. | [optional] [default to 0]

## Methods

### NewSearchRequest

`func NewSearchRequest() *SearchRequest`

NewSearchRequest instantiates a new SearchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchRequestWithDefaults

`func NewSearchRequestWithDefaults() *SearchRequest`

NewSearchRequestWithDefaults instantiates a new SearchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbxCode

`func (o *SearchRequest) GetIbxCode() string`

GetIbxCode returns the IbxCode field if non-nil, zero value otherwise.

### GetIbxCodeOk

`func (o *SearchRequest) GetIbxCodeOk() (*string, bool)`

GetIbxCodeOk returns a tuple with the IbxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxCode

`func (o *SearchRequest) SetIbxCode(v string)`

SetIbxCode sets IbxCode field to given value.

### HasIbxCode

`func (o *SearchRequest) HasIbxCode() bool`

HasIbxCode returns a boolean if a field has been set.

### GetMetroCode

`func (o *SearchRequest) GetMetroCode() string`

GetMetroCode returns the MetroCode field if non-nil, zero value otherwise.

### GetMetroCodeOk

`func (o *SearchRequest) GetMetroCodeOk() (*string, bool)`

GetMetroCodeOk returns a tuple with the MetroCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroCode

`func (o *SearchRequest) SetMetroCode(v string)`

SetMetroCode sets MetroCode field to given value.

### HasMetroCode

`func (o *SearchRequest) HasMetroCode() bool`

HasMetroCode returns a boolean if a field has been set.

### GetAccountStatus

`func (o *SearchRequest) GetAccountStatus() []AccountStatus`

GetAccountStatus returns the AccountStatus field if non-nil, zero value otherwise.

### GetAccountStatusOk

`func (o *SearchRequest) GetAccountStatusOk() (*[]AccountStatus, bool)`

GetAccountStatusOk returns a tuple with the AccountStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountStatus

`func (o *SearchRequest) SetAccountStatus(v []AccountStatus)`

SetAccountStatus sets AccountStatus field to given value.

### HasAccountStatus

`func (o *SearchRequest) HasAccountStatus() bool`

HasAccountStatus returns a boolean if a field has been set.

### GetProjectId

`func (o *SearchRequest) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SearchRequest) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SearchRequest) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SearchRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetLimit

`func (o *SearchRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SearchRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SearchRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *SearchRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *SearchRequest) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *SearchRequest) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *SearchRequest) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *SearchRequest) HasOffset() bool`

HasOffset returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


