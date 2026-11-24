# ContactRequestRegisteredUserUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username for the registered user party | 
**Type** | [**ContactRequestRegisteredUserUpdateType**](ContactRequestRegisteredUserUpdateType.md) |  | 

## Methods

### NewContactRequestRegisteredUserUpdate

`func NewContactRequestRegisteredUserUpdate(registeredUsers []string, type_ ContactRequestRegisteredUserUpdateType, ) *ContactRequestRegisteredUserUpdate`

NewContactRequestRegisteredUserUpdate instantiates a new ContactRequestRegisteredUserUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactRequestRegisteredUserUpdateWithDefaults

`func NewContactRequestRegisteredUserUpdateWithDefaults() *ContactRequestRegisteredUserUpdate`

NewContactRequestRegisteredUserUpdateWithDefaults instantiates a new ContactRequestRegisteredUserUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *ContactRequestRegisteredUserUpdate) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *ContactRequestRegisteredUserUpdate) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *ContactRequestRegisteredUserUpdate) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *ContactRequestRegisteredUserUpdate) GetType() ContactRequestRegisteredUserUpdateType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestRegisteredUserUpdate) GetTypeOk() (*ContactRequestRegisteredUserUpdateType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestRegisteredUserUpdate) SetType(v ContactRequestRegisteredUserUpdateType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


