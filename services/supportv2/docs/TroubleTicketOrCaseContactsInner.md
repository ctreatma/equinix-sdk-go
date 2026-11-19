# TroubleTicketOrCaseContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Type** | [**TypeOfTheContact**](TypeOfTheContact.md) |  | 
**FirstName** | Pointer to **string** | First name of the contact. | [optional] 
**LastName** | Pointer to **string** | Last name of the contact. | [optional] 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference. | 

## Methods

### NewTroubleTicketOrCaseContactsInner

`func NewTroubleTicketOrCaseContactsInner(registeredUsers []string, type_ TypeOfTheContact, details []ContactsRequestDetails, ) *TroubleTicketOrCaseContactsInner`

NewTroubleTicketOrCaseContactsInner instantiates a new TroubleTicketOrCaseContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketOrCaseContactsInnerWithDefaults

`func NewTroubleTicketOrCaseContactsInnerWithDefaults() *TroubleTicketOrCaseContactsInner`

NewTroubleTicketOrCaseContactsInnerWithDefaults instantiates a new TroubleTicketOrCaseContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *TroubleTicketOrCaseContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *TroubleTicketOrCaseContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *TroubleTicketOrCaseContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *TroubleTicketOrCaseContactsInner) GetType() TypeOfTheContact`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TroubleTicketOrCaseContactsInner) GetTypeOk() (*TypeOfTheContact, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TroubleTicketOrCaseContactsInner) SetType(v TypeOfTheContact)`

SetType sets Type field to given value.


### GetFirstName

`func (o *TroubleTicketOrCaseContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *TroubleTicketOrCaseContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *TroubleTicketOrCaseContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *TroubleTicketOrCaseContactsInner) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *TroubleTicketOrCaseContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *TroubleTicketOrCaseContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *TroubleTicketOrCaseContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *TroubleTicketOrCaseContactsInner) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetDetails

`func (o *TroubleTicketOrCaseContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *TroubleTicketOrCaseContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *TroubleTicketOrCaseContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


