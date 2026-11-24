# WorkvisitCreateContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Type** | [**ContactRequestNonRegisteredUserAllOfType**](ContactRequestNonRegisteredUserAllOfType.md) |  | [default to CONTACTREQUESTNONREGISTEREDUSERALLOFTYPE_TECHNICAL]
**Availability** | Pointer to [**ContactRequestRegisteredUserAllOfAvailability**](ContactRequestRegisteredUserAllOfAvailability.md) |  | [optional] [default to CONTACTREQUESTREGISTEREDUSERALLOFAVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 
**FirstName** | **string** | First name of the contact. | 
**LastName** | **string** | Last name of the contact. | 
**Details** | Pointer to [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | [optional] 

## Methods

### NewWorkvisitCreateContactsInner

`func NewWorkvisitCreateContactsInner(registeredUsers []string, type_ ContactRequestNonRegisteredUserAllOfType, firstName string, lastName string, ) *WorkvisitCreateContactsInner`

NewWorkvisitCreateContactsInner instantiates a new WorkvisitCreateContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitCreateContactsInnerWithDefaults

`func NewWorkvisitCreateContactsInnerWithDefaults() *WorkvisitCreateContactsInner`

NewWorkvisitCreateContactsInnerWithDefaults instantiates a new WorkvisitCreateContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *WorkvisitCreateContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *WorkvisitCreateContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *WorkvisitCreateContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetType

`func (o *WorkvisitCreateContactsInner) GetType() ContactRequestNonRegisteredUserAllOfType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WorkvisitCreateContactsInner) GetTypeOk() (*ContactRequestNonRegisteredUserAllOfType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WorkvisitCreateContactsInner) SetType(v ContactRequestNonRegisteredUserAllOfType)`

SetType sets Type field to given value.


### GetAvailability

`func (o *WorkvisitCreateContactsInner) GetAvailability() ContactRequestRegisteredUserAllOfAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *WorkvisitCreateContactsInner) GetAvailabilityOk() (*ContactRequestRegisteredUserAllOfAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *WorkvisitCreateContactsInner) SetAvailability(v ContactRequestRegisteredUserAllOfAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *WorkvisitCreateContactsInner) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *WorkvisitCreateContactsInner) GetTimezone() TIMEZONELIST`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *WorkvisitCreateContactsInner) GetTimezoneOk() (*TIMEZONELIST, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *WorkvisitCreateContactsInner) SetTimezone(v TIMEZONELIST)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *WorkvisitCreateContactsInner) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetFirstName

`func (o *WorkvisitCreateContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *WorkvisitCreateContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *WorkvisitCreateContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *WorkvisitCreateContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *WorkvisitCreateContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *WorkvisitCreateContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetDetails

`func (o *WorkvisitCreateContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *WorkvisitCreateContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *WorkvisitCreateContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *WorkvisitCreateContactsInner) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


