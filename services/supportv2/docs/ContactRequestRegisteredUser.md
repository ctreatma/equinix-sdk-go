# ContactRequestRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Type** | [**TypeOfTheContact**](TypeOfTheContact.md) |  | 

## Methods

### NewContactRequestRegisteredUser

`func NewContactRequestRegisteredUser(registeredUsers []string, type_ TypeOfTheContact, ) *ContactRequestRegisteredUser`

NewContactRequestRegisteredUser instantiates a new ContactRequestRegisteredUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactRequestRegisteredUserWithDefaults

`func NewContactRequestRegisteredUserWithDefaults() *ContactRequestRegisteredUser`

NewContactRequestRegisteredUserWithDefaults instantiates a new ContactRequestRegisteredUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *ContactRequestRegisteredUser) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *ContactRequestRegisteredUser) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *ContactRequestRegisteredUser) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *ContactRequestRegisteredUser) GetType() TypeOfTheContact`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestRegisteredUser) GetTypeOk() (*TypeOfTheContact, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestRegisteredUser) SetType(v TypeOfTheContact)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


