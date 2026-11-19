# Layer1CreateContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Availability** | Pointer to [**ContactRequestRegisteredUserAvailability**](ContactRequestRegisteredUserAvailability.md) |  | [optional] [default to CONTACTREQUESTREGISTEREDUSERAVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 
**Type** | [**ContactRequestNonRegisteredUserType**](ContactRequestNonRegisteredUserType.md) |  | [default to CONTACTREQUESTNONREGISTEREDUSERTYPE_TECHNICAL]
**FirstName** | **string** | First name of the contact. | 
**LastName** | **string** | Last name of the contact. | 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | 

## Methods

### NewLayer1CreateContactsInner

`func NewLayer1CreateContactsInner(registeredUsers []string, type_ ContactRequestNonRegisteredUserType, firstName string, lastName string, details []ContactsRequestDetails, ) *Layer1CreateContactsInner`

NewLayer1CreateContactsInner instantiates a new Layer1CreateContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayer1CreateContactsInnerWithDefaults

`func NewLayer1CreateContactsInnerWithDefaults() *Layer1CreateContactsInner`

NewLayer1CreateContactsInnerWithDefaults instantiates a new Layer1CreateContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *Layer1CreateContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *Layer1CreateContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *Layer1CreateContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetAvailability

`func (o *Layer1CreateContactsInner) GetAvailability() ContactRequestRegisteredUserAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *Layer1CreateContactsInner) GetAvailabilityOk() (*ContactRequestRegisteredUserAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *Layer1CreateContactsInner) SetAvailability(v ContactRequestRegisteredUserAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *Layer1CreateContactsInner) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *Layer1CreateContactsInner) GetTimezone() TIMEZONELIST`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *Layer1CreateContactsInner) GetTimezoneOk() (*TIMEZONELIST, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *Layer1CreateContactsInner) SetTimezone(v TIMEZONELIST)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *Layer1CreateContactsInner) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetType

`func (o *Layer1CreateContactsInner) GetType() ContactRequestNonRegisteredUserType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Layer1CreateContactsInner) GetTypeOk() (*ContactRequestNonRegisteredUserType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Layer1CreateContactsInner) SetType(v ContactRequestNonRegisteredUserType)`

SetType sets Type field to given value.


### GetFirstName

`func (o *Layer1CreateContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *Layer1CreateContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *Layer1CreateContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *Layer1CreateContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *Layer1CreateContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *Layer1CreateContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetDetails

`func (o *Layer1CreateContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Layer1CreateContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Layer1CreateContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


