# ContactDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Notes** | Pointer to **string** | Additional note applicable to the given contact option. | [optional] 
**Value** | **string** | Value specific to the given contact type. | 
**Type** | [**ContactDetailsType**](ContactDetailsType.md) |  | 

## Methods

### NewContactDetails

`func NewContactDetails(value string, type_ ContactDetailsType, ) *ContactDetails`

NewContactDetails instantiates a new ContactDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactDetailsWithDefaults

`func NewContactDetailsWithDefaults() *ContactDetails`

NewContactDetailsWithDefaults instantiates a new ContactDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotes

`func (o *ContactDetails) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ContactDetails) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ContactDetails) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ContactDetails) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetValue

`func (o *ContactDetails) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ContactDetails) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ContactDetails) SetValue(v string)`

SetValue sets Value field to given value.


### GetType

`func (o *ContactDetails) GetType() ContactDetailsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactDetails) GetTypeOk() (*ContactDetailsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactDetails) SetType(v ContactDetailsType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


