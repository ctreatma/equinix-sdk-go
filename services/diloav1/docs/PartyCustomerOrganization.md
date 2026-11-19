# PartyCustomerOrganization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrgIds** | **[]string** | Customer organization identifiers. | 
**Name** | **string** | Customer organization name. | 
**Contacts** | [**[]Contact**](Contact.md) | Organization contact information. | 

## Methods

### NewPartyCustomerOrganization

`func NewPartyCustomerOrganization(orgIds []string, name string, contacts []Contact, ) *PartyCustomerOrganization`

NewPartyCustomerOrganization instantiates a new PartyCustomerOrganization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartyCustomerOrganizationWithDefaults

`func NewPartyCustomerOrganizationWithDefaults() *PartyCustomerOrganization`

NewPartyCustomerOrganizationWithDefaults instantiates a new PartyCustomerOrganization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrgIds

`func (o *PartyCustomerOrganization) GetOrgIds() []string`

GetOrgIds returns the OrgIds field if non-nil, zero value otherwise.

### GetOrgIdsOk

`func (o *PartyCustomerOrganization) GetOrgIdsOk() (*[]string, bool)`

GetOrgIdsOk returns a tuple with the OrgIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgIds

`func (o *PartyCustomerOrganization) SetOrgIds(v []string)`

SetOrgIds sets OrgIds field to given value.


### GetName

`func (o *PartyCustomerOrganization) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartyCustomerOrganization) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartyCustomerOrganization) SetName(v string)`

SetName sets Name field to given value.


### GetContacts

`func (o *PartyCustomerOrganization) GetContacts() []Contact`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *PartyCustomerOrganization) GetContactsOk() (*[]Contact, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *PartyCustomerOrganization) SetContacts(v []Contact)`

SetContacts sets Contacts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


