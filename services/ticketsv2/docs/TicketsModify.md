# TicketsModify

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | [**[]ContactRequestRegisteredUserUpdate**](ContactRequestRegisteredUserUpdate.md) | List of persons who will be contacted for this ticket. | 

## Methods

### NewTicketsModify

`func NewTicketsModify(contacts []ContactRequestRegisteredUserUpdate, ) *TicketsModify`

NewTicketsModify instantiates a new TicketsModify object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsModifyWithDefaults

`func NewTicketsModifyWithDefaults() *TicketsModify`

NewTicketsModifyWithDefaults instantiates a new TicketsModify object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *TicketsModify) GetContacts() []ContactRequestRegisteredUserUpdate`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *TicketsModify) GetContactsOk() (*[]ContactRequestRegisteredUserUpdate, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *TicketsModify) SetContacts(v []ContactRequestRegisteredUserUpdate)`

SetContacts sets Contacts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


