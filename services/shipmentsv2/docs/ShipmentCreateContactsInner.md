# ShipmentCreateContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Availability** | Pointer to [**ContactRequestNonRegisteredUserAvailability**](ContactRequestNonRegisteredUserAvailability.md) |  | [optional] [default to CONTACTREQUESTNONREGISTEREDUSERAVAILABILITY_WORK_HOURS]
**Timezone** | Pointer to [**Timezone**](Timezone.md) |  | [optional] 
**Type** | [**ContactRequestNonRegisteredUserType**](ContactRequestNonRegisteredUserType.md) |  | [default to CONTACTREQUESTNONREGISTEREDUSERTYPE_TECHNICAL]
**FirstName** | **string** | First name of the contact. | 
**LastName** | **string** | Last name of the contact. | 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | 

## Methods

### NewShipmentCreateContactsInner

`func NewShipmentCreateContactsInner(registeredUsers []string, type_ ContactRequestNonRegisteredUserType, firstName string, lastName string, details []ContactsRequestDetails, ) *ShipmentCreateContactsInner`

NewShipmentCreateContactsInner instantiates a new ShipmentCreateContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentCreateContactsInnerWithDefaults

`func NewShipmentCreateContactsInnerWithDefaults() *ShipmentCreateContactsInner`

NewShipmentCreateContactsInnerWithDefaults instantiates a new ShipmentCreateContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *ShipmentCreateContactsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *ShipmentCreateContactsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *ShipmentCreateContactsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetAvailability

`func (o *ShipmentCreateContactsInner) GetAvailability() ContactRequestNonRegisteredUserAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ShipmentCreateContactsInner) GetAvailabilityOk() (*ContactRequestNonRegisteredUserAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ShipmentCreateContactsInner) SetAvailability(v ContactRequestNonRegisteredUserAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ShipmentCreateContactsInner) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *ShipmentCreateContactsInner) GetTimezone() Timezone`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ShipmentCreateContactsInner) GetTimezoneOk() (*Timezone, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ShipmentCreateContactsInner) SetTimezone(v Timezone)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *ShipmentCreateContactsInner) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetType

`func (o *ShipmentCreateContactsInner) GetType() ContactRequestNonRegisteredUserType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ShipmentCreateContactsInner) GetTypeOk() (*ContactRequestNonRegisteredUserType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ShipmentCreateContactsInner) SetType(v ContactRequestNonRegisteredUserType)`

SetType sets Type field to given value.


### GetFirstName

`func (o *ShipmentCreateContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ShipmentCreateContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ShipmentCreateContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *ShipmentCreateContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ShipmentCreateContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ShipmentCreateContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetDetails

`func (o *ShipmentCreateContactsInner) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ShipmentCreateContactsInner) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ShipmentCreateContactsInner) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


