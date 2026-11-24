# TicketsCreateContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Type** | [**ContactRequestNonRegisteredUserType**](ContactRequestNonRegisteredUserType.md) |  | [default to CONTACTREQUESTNONREGISTEREDUSERTYPE_TECHNICAL]
**FirstName** | Pointer to **string** | First name of the contact. | [optional] 
**LastName** | Pointer to **string** | Last name of the contact. | [optional] 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Communications Details. | 

## Methods

### NewTicketsCreateContactsInner

`func NewTicketsCreateContactsInner(registeredUsers []string, type_ ContactRequestNonRegisteredUserType, details []ContactsRequestDetails, ) *TicketsCreateContactsInner`

NewTicketsCreateContactsInner instantiates a new TicketsCreateContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsCreateContactsInnerWithDefaults

`func NewTicketsCreateContactsInnerWithDefaults() *TicketsCreateContactsInner`

NewTicketsCreateContactsInnerWithDefaults instantiates a new TicketsCreateContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *TicketsCreateContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *TicketsCreateContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *TicketsCreateContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *TicketsCreateContactsInner) GetType() ContactRequestNonRegisteredUserType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TicketsCreateContactsInner) GetTypeOk() (*ContactRequestNonRegisteredUserType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TicketsCreateContactsInner) SetType(v ContactRequestNonRegisteredUserType)`

SetType sets Type field to given value.


### GetFirstName

`func (o *TicketsCreateContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *TicketsCreateContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *TicketsCreateContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *TicketsCreateContactsInner) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *TicketsCreateContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *TicketsCreateContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *TicketsCreateContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *TicketsCreateContactsInner) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetDetails

`func (o *TicketsCreateContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *TicketsCreateContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *TicketsCreateContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


