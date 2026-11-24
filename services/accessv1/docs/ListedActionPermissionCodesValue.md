# ListedActionPermissionCodesValue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequiresAll** | Pointer to **bool** | True indicates that the action is only allowed when the user has been unconditionally granted the permission code at the top-level of the asset hierarchy | [optional] 

## Methods

### NewListedActionPermissionCodesValue

`func NewListedActionPermissionCodesValue() *ListedActionPermissionCodesValue`

NewListedActionPermissionCodesValue instantiates a new ListedActionPermissionCodesValue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListedActionPermissionCodesValueWithDefaults

`func NewListedActionPermissionCodesValueWithDefaults() *ListedActionPermissionCodesValue`

NewListedActionPermissionCodesValueWithDefaults instantiates a new ListedActionPermissionCodesValue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequiresAll

`func (o *ListedActionPermissionCodesValue) GetRequiresAll() bool`

GetRequiresAll returns the RequiresAll field if non-nil, zero value otherwise.

### GetRequiresAllOk

`func (o *ListedActionPermissionCodesValue) GetRequiresAllOk() (*bool, bool)`

GetRequiresAllOk returns a tuple with the RequiresAll field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresAll

`func (o *ListedActionPermissionCodesValue) SetRequiresAll(v bool)`

SetRequiresAll sets RequiresAll field to given value.

### HasRequiresAll

`func (o *ListedActionPermissionCodesValue) HasRequiresAll() bool`

HasRequiresAll returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


