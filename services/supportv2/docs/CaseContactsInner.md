# CaseContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Usernames of the registered users. A username may or may not be an email address. | 
**Type** | [**TypeOfTheContact**](TypeOfTheContact.md) |  | 
**FirstName** | Pointer to **string** | Given name of the person Equinix should contact regarding the case. | [optional] 
**LastName** | Pointer to **string** | Last name of the person Equinix should contact regarding the case. | [optional] 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference. | 

## Methods

### NewCaseContactsInner

`func NewCaseContactsInner(registeredUsers []string, type_ TypeOfTheContact, details []ContactsRequestDetails, ) *CaseContactsInner`

NewCaseContactsInner instantiates a new CaseContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCaseContactsInnerWithDefaults

`func NewCaseContactsInnerWithDefaults() *CaseContactsInner`

NewCaseContactsInnerWithDefaults instantiates a new CaseContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *CaseContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *CaseContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *CaseContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *CaseContactsInner) GetType() TypeOfTheContact`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CaseContactsInner) GetTypeOk() (*TypeOfTheContact, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CaseContactsInner) SetType(v TypeOfTheContact)`

SetType sets Type field to given value.


### GetFirstName

`func (o *CaseContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *CaseContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *CaseContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *CaseContactsInner) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *CaseContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *CaseContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *CaseContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *CaseContactsInner) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetDetails

`func (o *CaseContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *CaseContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *CaseContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


