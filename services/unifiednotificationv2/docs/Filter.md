# Filter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | Pointer to [**[]Category**](Category.md) |  | [optional] 
**Type** | Pointer to [**[]Type**](Type.md) |  | [optional] 
**NotificationNumber** | Pointer to **[]string** |  | [optional] 
**AccountNumber** | Pointer to **[]string** |  | [optional] 
**CreatedDateTime** | Pointer to **[]string** |  | [optional] 

## Methods

### NewFilter

`func NewFilter() *Filter`

NewFilter instantiates a new Filter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFilterWithDefaults

`func NewFilterWithDefaults() *Filter`

NewFilterWithDefaults instantiates a new Filter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *Filter) GetCategory() []Category`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Filter) GetCategoryOk() (*[]Category, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Filter) SetCategory(v []Category)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *Filter) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetType

`func (o *Filter) GetType() []Type`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Filter) GetTypeOk() (*[]Type, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Filter) SetType(v []Type)`

SetType sets Type field to given value.

### HasType

`func (o *Filter) HasType() bool`

HasType returns a boolean if a field has been set.

### GetNotificationNumber

`func (o *Filter) GetNotificationNumber() []string`

GetNotificationNumber returns the NotificationNumber field if non-nil, zero value otherwise.

### GetNotificationNumberOk

`func (o *Filter) GetNotificationNumberOk() (*[]string, bool)`

GetNotificationNumberOk returns a tuple with the NotificationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationNumber

`func (o *Filter) SetNotificationNumber(v []string)`

SetNotificationNumber sets NotificationNumber field to given value.

### HasNotificationNumber

`func (o *Filter) HasNotificationNumber() bool`

HasNotificationNumber returns a boolean if a field has been set.

### GetAccountNumber

`func (o *Filter) GetAccountNumber() []string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *Filter) GetAccountNumberOk() (*[]string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *Filter) SetAccountNumber(v []string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *Filter) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *Filter) GetCreatedDateTime() []string`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *Filter) GetCreatedDateTimeOk() (*[]string, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *Filter) SetCreatedDateTime(v []string)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *Filter) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


