# ContactRequestRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**Type** | [**ContactRequestRegisteredUserAllOfType**](ContactRequestRegisteredUserAllOfType.md) |  | [default to CONTACTREQUESTREGISTEREDUSERALLOFTYPE_NOTIFICATION]
**Availability** | Pointer to [**ContactRequestRegisteredUserAllOfAvailability**](ContactRequestRegisteredUserAllOfAvailability.md) |  | [optional] [default to CONTACTREQUESTREGISTEREDUSERALLOFAVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 

## Methods

### NewContactRequestRegisteredUser

`func NewContactRequestRegisteredUser(registeredUsers []string, type_ ContactRequestRegisteredUserAllOfType, ) *ContactRequestRegisteredUser`

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

`func (o *ContactRequestRegisteredUser) GetType() ContactRequestRegisteredUserAllOfType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestRegisteredUser) GetTypeOk() (*ContactRequestRegisteredUserAllOfType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestRegisteredUser) SetType(v ContactRequestRegisteredUserAllOfType)`

SetType sets Type field to given value.


### GetAvailability

`func (o *ContactRequestRegisteredUser) GetAvailability() ContactRequestRegisteredUserAllOfAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ContactRequestRegisteredUser) GetAvailabilityOk() (*ContactRequestRegisteredUserAllOfAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ContactRequestRegisteredUser) SetAvailability(v ContactRequestRegisteredUserAllOfAvailability)`

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


