# PageResponseMetroAccountResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountCreateUrl** | Pointer to **string** | The URL to create a new account | [optional] 
**Data** | Pointer to [**[]MetroAccountResponse**](MetroAccountResponse.md) | List of metro accounts | [optional] 
**ErrorMessage** | Pointer to **string** | Error message | [optional] 
**ErrorCode** | Pointer to **string** | Error code | [optional] 
**Pagination** | Pointer to [**PaginationResponse**](PaginationResponse.md) |  | [optional] 

## Methods

### NewPageResponseMetroAccountResponse

`func NewPageResponseMetroAccountResponse() *PageResponseMetroAccountResponse`

NewPageResponseMetroAccountResponse instantiates a new PageResponseMetroAccountResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPageResponseMetroAccountResponseWithDefaults

`func NewPageResponseMetroAccountResponseWithDefaults() *PageResponseMetroAccountResponse`

NewPageResponseMetroAccountResponseWithDefaults instantiates a new PageResponseMetroAccountResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountCreateUrl

`func (o *PageResponseMetroAccountResponse) GetAccountCreateUrl() string`

GetAccountCreateUrl returns the AccountCreateUrl field if non-nil, zero value otherwise.

### GetAccountCreateUrlOk

`func (o *PageResponseMetroAccountResponse) GetAccountCreateUrlOk() (*string, bool)`

GetAccountCreateUrlOk returns a tuple with the AccountCreateUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountCreateUrl

`func (o *PageResponseMetroAccountResponse) SetAccountCreateUrl(v string)`

SetAccountCreateUrl sets AccountCreateUrl field to given value.

### HasAccountCreateUrl

`func (o *PageResponseMetroAccountResponse) HasAccountCreateUrl() bool`

HasAccountCreateUrl returns a boolean if a field has been set.

### GetData

`func (o *PageResponseMetroAccountResponse) GetData() []MetroAccountResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PageResponseMetroAccountResponse) GetDataOk() (*[]MetroAccountResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PageResponseMetroAccountResponse) SetData(v []MetroAccountResponse)`

SetData sets Data field to given value.

### HasData

`func (o *PageResponseMetroAccountResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetErrorMessage

`func (o *PageResponseMetroAccountResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *PageResponseMetroAccountResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *PageResponseMetroAccountResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *PageResponseMetroAccountResponse) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### GetErrorCode

`func (o *PageResponseMetroAccountResponse) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *PageResponseMetroAccountResponse) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *PageResponseMetroAccountResponse) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.

### HasErrorCode

`func (o *PageResponseMetroAccountResponse) HasErrorCode() bool`

HasErrorCode returns a boolean if a field has been set.

### GetPagination

`func (o *PageResponseMetroAccountResponse) GetPagination() PaginationResponse`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *PageResponseMetroAccountResponse) GetPaginationOk() (*PaginationResponse, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *PageResponseMetroAccountResponse) SetPagination(v PaginationResponse)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *PageResponseMetroAccountResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


