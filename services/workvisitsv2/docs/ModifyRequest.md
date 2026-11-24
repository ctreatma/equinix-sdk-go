# ModifyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | Pointer to [**[]ContactRequestRegisteredUserUpdate**](ContactRequestRegisteredUserUpdate.md) |  | [optional] 
**Details** | Pointer to [**WorkvisitsAdditionalInfo**](WorkvisitsAdditionalInfo.md) |  | [optional] 

## Methods

### NewModifyRequest

`func NewModifyRequest() *ModifyRequest`

NewModifyRequest instantiates a new ModifyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModifyRequestWithDefaults

`func NewModifyRequestWithDefaults() *ModifyRequest`

NewModifyRequestWithDefaults instantiates a new ModifyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ModifyRequest) GetContacts() []ContactRequestRegisteredUserUpdate`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ModifyRequest) GetContactsOk() (*[]ContactRequestRegisteredUserUpdate, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ModifyRequest) SetContacts(v []ContactRequestRegisteredUserUpdate)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *ModifyRequest) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetDetails

`func (o *ModifyRequest) GetDetails() WorkvisitsAdditionalInfo`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ModifyRequest) GetDetailsOk() (*WorkvisitsAdditionalInfo, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ModifyRequest) SetDetails(v WorkvisitsAdditionalInfo)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ModifyRequest) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


