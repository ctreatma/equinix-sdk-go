# ContactRequestNonRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | **string** | First name of the contact. | 
**LastName** | **string** | Last name of the contact. | 
**Type** | [**ContactRequestNonRegisteredUserType**](ContactRequestNonRegisteredUserType.md) |  | [default to CONTACTREQUESTNONREGISTEREDUSERTYPE_TECHNICAL]
**Availability** | Pointer to [**ContactRequestNonRegisteredUserAvailability**](ContactRequestNonRegisteredUserAvailability.md) |  | [optional] [default to CONTACTREQUESTNONREGISTEREDUSERAVAILABILITY_WORK_HOURS]
**Timezone** | Pointer to [**Timezone**](Timezone.md) |  | [optional] 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | 

## Methods

### NewContactRequestNonRegisteredUser

`func NewContactRequestNonRegisteredUser(firstName string, lastName string, type_ ContactRequestNonRegisteredUserType, details []ContactsRequestDetails, ) *ContactRequestNonRegisteredUser`

NewContactRequestNonRegisteredUser instantiates a new ContactRequestNonRegisteredUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactRequestNonRegisteredUserWithDefaults

`func NewContactRequestNonRegisteredUserWithDefaults() *ContactRequestNonRegisteredUser`

NewContactRequestNonRegisteredUserWithDefaults instantiates a new ContactRequestNonRegisteredUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *ContactRequestNonRegisteredUser) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactRequestNonRegisteredUser) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactRequestNonRegisteredUser) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *ContactRequestNonRegisteredUser) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactRequestNonRegisteredUser) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactRequestNonRegisteredUser) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetType

`func (o *ContactRequestNonRegisteredUser) GetType() ContactRequestNonRegisteredUserType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestNonRegisteredUser) GetTypeOk() (*ContactRequestNonRegisteredUserType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestNonRegisteredUser) SetType(v ContactRequestNonRegisteredUserType)`

SetType sets Type field to given value.


### GetAvailability

`func (o *ContactRequestNonRegisteredUser) GetAvailability() ContactRequestNonRegisteredUserAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ContactRequestNonRegisteredUser) GetAvailabilityOk() (*ContactRequestNonRegisteredUserAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ContactRequestNonRegisteredUser) SetAvailability(v ContactRequestNonRegisteredUserAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ContactRequestNonRegisteredUser) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *ContactRequestNonRegisteredUser) GetTimezone() Timezone`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ContactRequestNonRegisteredUser) GetTimezoneOk() (*Timezone, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ContactRequestNonRegisteredUser) SetTimezone(v Timezone)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *ContactRequestNonRegisteredUser) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetDetails

`func (o *ContactRequestNonRegisteredUser) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ContactRequestNonRegisteredUser) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ContactRequestNonRegisteredUser) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


