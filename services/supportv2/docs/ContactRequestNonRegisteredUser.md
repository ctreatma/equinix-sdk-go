# ContactRequestNonRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** | First name of the contact. | [optional] 
**LastName** | Pointer to **string** | Last name of the contact. | [optional] 
**Type** | [**TypeOfTheContact**](TypeOfTheContact.md) |  | 
**Details** | [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference. | 

## Methods

### NewContactRequestNonRegisteredUser

`func NewContactRequestNonRegisteredUser(type_ TypeOfTheContact, details []ContactsRequestDetails, ) *ContactRequestNonRegisteredUser`

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

### HasFirstName

`func (o *ContactRequestNonRegisteredUser) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

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

### HasLastName

`func (o *ContactRequestNonRegisteredUser) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetType

`func (o *ContactRequestNonRegisteredUser) GetType() TypeOfTheContact`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactRequestNonRegisteredUser) GetTypeOk() (*TypeOfTheContact, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactRequestNonRegisteredUser) SetType(v TypeOfTheContact)`

SetType sets Type field to given value.


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


