# ContactResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** | Given name of the person Equinix should contact regarding the case. | [optional] 
**LastName** | Pointer to **string** | Last name of the person Equinix should contact regarding the case. | [optional] 
**Type** | Pointer to [**TypeOfTheContact**](TypeOfTheContact.md) |  | [optional] 
**Details** | Pointer to [**[]ContactResponseDetailsInner**](ContactResponseDetailsInner.md) | Contact details of the person, such as email, mobile or phone. | [optional] 

## Methods

### NewContactResponse

`func NewContactResponse() *ContactResponse`

NewContactResponse instantiates a new ContactResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactResponseWithDefaults

`func NewContactResponseWithDefaults() *ContactResponse`

NewContactResponseWithDefaults instantiates a new ContactResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *ContactResponse) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ContactResponse) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ContactResponse) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ContactResponse) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ContactResponse) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ContactResponse) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ContactResponse) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ContactResponse) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetType

`func (o *ContactResponse) GetType() TypeOfTheContact`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactResponse) GetTypeOk() (*TypeOfTheContact, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactResponse) SetType(v TypeOfTheContact)`

SetType sets Type field to given value.

### HasType

`func (o *ContactResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDetails

`func (o *ContactResponse) GetDetails() []ContactResponseDetailsInner`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ContactResponse) GetDetailsOk() (*[]ContactResponseDetailsInner, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ContactResponse) SetDetails(v []ContactResponseDetailsInner)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ContactResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


