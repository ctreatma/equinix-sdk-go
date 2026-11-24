# Contact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**ContactType**](ContactType.md) |  | 
**RegisteredUser** | Pointer to **string** | Registered user identified by contactId, userId, or userKey. If a registered user is specified, you don&#39;t have to provide first name and last name information. | [optional] 
**FirstName** | Pointer to **string** | Contact person&#39;s first name. Required if registeredUser isn&#39;t provided. | [optional] 
**LastName** | Pointer to **string** | Contact person&#39;s last name. Required if registeredUser isn&#39;t provided. | [optional] 
**Timezone** | Pointer to **string** | Contact Timezone | [optional] 
**Availability** | Pointer to [**ContactAvailability**](ContactAvailability.md) |  | [optional] 
**Details** | [**[]ContactDetails**](ContactDetails.md) | Means of contact. | 

## Methods

### NewContact

`func NewContact(type_ ContactType, details []ContactDetails, ) *Contact`

NewContact instantiates a new Contact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactWithDefaults

`func NewContactWithDefaults() *Contact`

NewContactWithDefaults instantiates a new Contact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Contact) GetType() ContactType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Contact) GetTypeOk() (*ContactType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Contact) SetType(v ContactType)`

SetType sets Type field to given value.


### GetRegisteredUser

`func (o *Contact) GetRegisteredUser() string`

GetRegisteredUser returns the RegisteredUser field if non-nil, zero value otherwise.

### GetRegisteredUserOk

`func (o *Contact) GetRegisteredUserOk() (*string, bool)`

GetRegisteredUserOk returns a tuple with the RegisteredUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUser

`func (o *Contact) SetRegisteredUser(v string)`

SetRegisteredUser sets RegisteredUser field to given value.

### HasRegisteredUser

`func (o *Contact) HasRegisteredUser() bool`

HasRegisteredUser returns a boolean if a field has been set.

### GetFirstName

`func (o *Contact) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *Contact) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *Contact) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *Contact) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *Contact) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *Contact) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *Contact) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *Contact) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetTimezone

`func (o *Contact) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *Contact) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *Contact) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *Contact) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetAvailability

`func (o *Contact) GetAvailability() ContactAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *Contact) GetAvailabilityOk() (*ContactAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *Contact) SetAvailability(v ContactAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *Contact) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetDetails

`func (o *Contact) GetDetails() []ContactDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Contact) GetDetailsOk() (*[]ContactDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Contact) SetDetails(v []ContactDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


