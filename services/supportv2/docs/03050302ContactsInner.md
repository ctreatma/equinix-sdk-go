# 03050302ContactsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**Model03050302ContactsInnerType**](03050302ContactsInnerType.md) |  | 
**FirstName** | **string** | First name of the contact person. | 
**LastName** | **string** | Last name of the contact person. | 
**LocalName** | Pointer to **string** | Full name of contact person in local language. | [optional] 
**Details** | [**[]Model03050302ContactsInnerDetailsInner**](Model03050302ContactsInnerDetailsInner.md) |  | 

## Methods

### New03050302ContactsInner

`func New03050302ContactsInner(type_ Model03050302ContactsInnerType, firstName string, lastName string, details []Model03050302ContactsInnerDetailsInner, ) *03050302ContactsInner`

New03050302ContactsInner instantiates a new 03050302ContactsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### New03050302ContactsInnerWithDefaults

`func New03050302ContactsInnerWithDefaults() *03050302ContactsInner`

New03050302ContactsInnerWithDefaults instantiates a new 03050302ContactsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *03050302ContactsInner) GetType() Model03050302ContactsInnerType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *03050302ContactsInner) GetTypeOk() (*Model03050302ContactsInnerType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *03050302ContactsInner) SetType(v Model03050302ContactsInnerType)`

SetType sets Type field to given value.


### GetFirstName

`func (o *03050302ContactsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *03050302ContactsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *03050302ContactsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *03050302ContactsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *03050302ContactsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *03050302ContactsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetLocalName

`func (o *03050302ContactsInner) GetLocalName() string`

GetLocalName returns the LocalName field if non-nil, zero value otherwise.

### GetLocalNameOk

`func (o *03050302ContactsInner) GetLocalNameOk() (*string, bool)`

GetLocalNameOk returns a tuple with the LocalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalName

`func (o *03050302ContactsInner) SetLocalName(v string)`

SetLocalName sets LocalName field to given value.

### HasLocalName

`func (o *03050302ContactsInner) HasLocalName() bool`

HasLocalName returns a boolean if a field has been set.

### GetDetails

`func (o *03050302ContactsInner) GetDetails() []Model03050302ContactsInnerDetailsInner`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *03050302ContactsInner) GetDetailsOk() (*[]Model03050302ContactsInnerDetailsInner, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *03050302ContactsInner) SetDetails(v []Model03050302ContactsInnerDetailsInner)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


