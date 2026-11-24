# PartyContacts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | [**[]Contact**](Contact.md) | Organization contact information. | 

## Methods

### NewPartyContacts

`func NewPartyContacts(contacts []Contact, ) *PartyContacts`

NewPartyContacts instantiates a new PartyContacts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartyContactsWithDefaults

`func NewPartyContactsWithDefaults() *PartyContacts`

NewPartyContactsWithDefaults instantiates a new PartyContacts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *PartyContacts) GetContacts() []Contact`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *PartyContacts) GetContactsOk() (*[]Contact, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *PartyContacts) SetContacts(v []Contact)`

SetContacts sets Contacts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


