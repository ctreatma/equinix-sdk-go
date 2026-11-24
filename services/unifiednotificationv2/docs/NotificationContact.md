# NotificationContact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to [**NotificationContactType**](NotificationContactType.md) |  | [optional] 
**FirstName** | **string** | First name. | 
**LastName** | **string** | Last name. | 
**Details** | Pointer to [**[]ContactDetails**](ContactDetails.md) |  | [optional] 

## Methods

### NewNotificationContact

`func NewNotificationContact(firstName string, lastName string, ) *NotificationContact`

NewNotificationContact instantiates a new NotificationContact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNotificationContactWithDefaults

`func NewNotificationContactWithDefaults() *NotificationContact`

NewNotificationContactWithDefaults instantiates a new NotificationContact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *NotificationContact) GetType() NotificationContactType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *NotificationContact) GetTypeOk() (*NotificationContactType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *NotificationContact) SetType(v NotificationContactType)`

SetType sets Type field to given value.

### HasType

`func (o *NotificationContact) HasType() bool`

HasType returns a boolean if a field has been set.

### GetFirstName

`func (o *NotificationContact) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *NotificationContact) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *NotificationContact) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *NotificationContact) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *NotificationContact) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *NotificationContact) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetDetails

`func (o *NotificationContact) GetDetails() []ContactDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *NotificationContact) GetDetailsOk() (*[]ContactDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *NotificationContact) SetDetails(v []ContactDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *NotificationContact) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


