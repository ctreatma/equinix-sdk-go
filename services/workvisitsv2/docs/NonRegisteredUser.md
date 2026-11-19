# NonRegisteredUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | **string** | First name of the contact. | 
**LastName** | **string** | Last name of the contact. | 
**Details** | Pointer to [**[]ContactsRequestDetails**](ContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | [optional] 

## Methods

### NewNonRegisteredUser

`func NewNonRegisteredUser(firstName string, lastName string, ) *NonRegisteredUser`

NewNonRegisteredUser instantiates a new NonRegisteredUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNonRegisteredUserWithDefaults

`func NewNonRegisteredUserWithDefaults() *NonRegisteredUser`

NewNonRegisteredUserWithDefaults instantiates a new NonRegisteredUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *NonRegisteredUser) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *NonRegisteredUser) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *NonRegisteredUser) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *NonRegisteredUser) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *NonRegisteredUser) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *NonRegisteredUser) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetDetails

`func (o *NonRegisteredUser) GetDetails() []ContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *NonRegisteredUser) GetDetailsOk() (*[]ContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *NonRegisteredUser) SetDetails(v []ContactsRequestDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *NonRegisteredUser) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


