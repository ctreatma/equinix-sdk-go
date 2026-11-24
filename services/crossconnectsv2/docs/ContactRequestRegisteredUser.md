# ContactRequestRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Availability** | Pointer to [**ContactRequestRegisteredUserAvailability**](ContactRequestRegisteredUserAvailability.md) |  | [optional] [default to CONTACTREQUESTREGISTEREDUSERAVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 
**Type** | [**ContactRequestRegisteredUserType**](ContactRequestRegisteredUserType.md) |  | [default to CONTACTREQUESTREGISTEREDUSERTYPE_NOTIFICATION]

## Methods

### NewContactRequestRegisteredUser

`func NewContactRequestRegisteredUser(registeredUsers []string, type_ ContactRequestRegisteredUserType, ) *ContactRequestRegisteredUser`

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


### GetAvailability

`func (o *ContactRequestRegisteredUser) GetAvailability() ContactRequestRegisteredUserAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ContactRequestRegisteredUser) GetAvailabilityOk() (*ContactRequestRegisteredUserAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ContactRequestRegisteredUser) SetAvailability(v ContactRequestRegisteredUserAvailability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ContactRequestRegisteredUser) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *ContactRequestRegisteredUser) GetTimezone() TIMEZONELIST`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ContactRequestRegisteredUser) GetTimezoneOk() (*TIMEZONELIST, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ContactRequestRegisteredUser) SetTimezone(v TIMEZONELIST)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *ContactRequestRegisteredUser) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetType

`func (o *ContactRequestRegisteredUser) GetType() ContactRequestRegisteredUserType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestRegisteredUser) GetTypeOk() (*ContactRequestRegisteredUserType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestRegisteredUser) SetType(v ContactRequestRegisteredUserType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


