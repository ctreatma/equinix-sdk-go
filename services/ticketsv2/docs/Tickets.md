# Tickets

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | Pointer to **string** | Tickets Category. | [optional] 
**SubCategory** | Pointer to **string** | Tickets Sub Category. | [optional] 
**Description** | Pointer to **string** | Description of the trouble or issue. | [optional] 
**PrimaryId** | Pointer to **string** | Primary reference identifier associated with the troubled asset, such as cage identifier. | [optional] 
**OccurredDateTime** | Pointer to **time.Time** | Date and time the issue occurred. | [optional] 
**Id** | Pointer to **string** | Unique identifier of the ticket. | [optional] 
**SecondaryId** | Pointer to **string** | Secondary reference identifier associated with the troubled asset. | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Number / External Reference Number. | [optional] 
**ResolutionDateTime** | Pointer to **time.Time** | The resolution date and time | [optional] 
**Resolutions** | Pointer to [**[]Resolutions**](Resolutions.md) | Resolution Details. | [optional] 
**Status** | Pointer to [**TicketsStatus**](TicketsStatus.md) |  | [optional] 
**Details** | Pointer to [**TicketsDetails**](TicketsDetails.md) |  | [optional] 
**Notes** | Pointer to [**[]Note**](Note.md) | The note(s) that are associated to the ticket. | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | File(s) attached to the ticket | [optional] 
**Contacts** | Pointer to [**[]Contacts**](Contacts.md) | List of persons who will be contacted for this ticket. | [optional] 

## Methods

### NewTickets

`func NewTickets() *Tickets`

NewTickets instantiates a new Tickets object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsWithDefaults

`func NewTicketsWithDefaults() *Tickets`

NewTicketsWithDefaults instantiates a new Tickets object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *Tickets) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Tickets) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Tickets) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *Tickets) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetSubCategory

`func (o *Tickets) GetSubCategory() string`

GetSubCategory returns the SubCategory field if non-nil, zero value otherwise.

### GetSubCategoryOk

`func (o *Tickets) GetSubCategoryOk() (*string, bool)`

GetSubCategoryOk returns a tuple with the SubCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubCategory

`func (o *Tickets) SetSubCategory(v string)`

SetSubCategory sets SubCategory field to given value.

### HasSubCategory

`func (o *Tickets) HasSubCategory() bool`

HasSubCategory returns a boolean if a field has been set.

### GetDescription

`func (o *Tickets) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Tickets) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Tickets) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Tickets) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPrimaryId

`func (o *Tickets) GetPrimaryId() string`

GetPrimaryId returns the PrimaryId field if non-nil, zero value otherwise.

### GetPrimaryIdOk

`func (o *Tickets) GetPrimaryIdOk() (*string, bool)`

GetPrimaryIdOk returns a tuple with the PrimaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryId

`func (o *Tickets) SetPrimaryId(v string)`

SetPrimaryId sets PrimaryId field to given value.

### HasPrimaryId

`func (o *Tickets) HasPrimaryId() bool`

HasPrimaryId returns a boolean if a field has been set.

### GetOccurredDateTime

`func (o *Tickets) GetOccurredDateTime() time.Time`

GetOccurredDateTime returns the OccurredDateTime field if non-nil, zero value otherwise.

### GetOccurredDateTimeOk

`func (o *Tickets) GetOccurredDateTimeOk() (*time.Time, bool)`

GetOccurredDateTimeOk returns a tuple with the OccurredDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredDateTime

`func (o *Tickets) SetOccurredDateTime(v time.Time)`

SetOccurredDateTime sets OccurredDateTime field to given value.

### HasOccurredDateTime

`func (o *Tickets) HasOccurredDateTime() bool`

HasOccurredDateTime returns a boolean if a field has been set.

### GetId

`func (o *Tickets) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Tickets) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Tickets) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Tickets) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSecondaryId

`func (o *Tickets) GetSecondaryId() string`

GetSecondaryId returns the SecondaryId field if non-nil, zero value otherwise.

### GetSecondaryIdOk

`func (o *Tickets) GetSecondaryIdOk() (*string, bool)`

GetSecondaryIdOk returns a tuple with the SecondaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryId

`func (o *Tickets) SetSecondaryId(v string)`

SetSecondaryId sets SecondaryId field to given value.

### HasSecondaryId

`func (o *Tickets) HasSecondaryId() bool`

HasSecondaryId returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *Tickets) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *Tickets) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *Tickets) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *Tickets) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetResolutionDateTime

`func (o *Tickets) GetResolutionDateTime() time.Time`

GetResolutionDateTime returns the ResolutionDateTime field if non-nil, zero value otherwise.

### GetResolutionDateTimeOk

`func (o *Tickets) GetResolutionDateTimeOk() (*time.Time, bool)`

GetResolutionDateTimeOk returns a tuple with the ResolutionDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolutionDateTime

`func (o *Tickets) SetResolutionDateTime(v time.Time)`

SetResolutionDateTime sets ResolutionDateTime field to given value.

### HasResolutionDateTime

`func (o *Tickets) HasResolutionDateTime() bool`

HasResolutionDateTime returns a boolean if a field has been set.

### GetResolutions

`func (o *Tickets) GetResolutions() []Resolutions`

GetResolutions returns the Resolutions field if non-nil, zero value otherwise.

### GetResolutionsOk

`func (o *Tickets) GetResolutionsOk() (*[]Resolutions, bool)`

GetResolutionsOk returns a tuple with the Resolutions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolutions

`func (o *Tickets) SetResolutions(v []Resolutions)`

SetResolutions sets Resolutions field to given value.

### HasResolutions

`func (o *Tickets) HasResolutions() bool`

HasResolutions returns a boolean if a field has been set.

### GetStatus

`func (o *Tickets) GetStatus() TicketsStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Tickets) GetStatusOk() (*TicketsStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Tickets) SetStatus(v TicketsStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Tickets) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDetails

`func (o *Tickets) GetDetails() TicketsDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Tickets) GetDetailsOk() (*TicketsDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Tickets) SetDetails(v TicketsDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Tickets) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetNotes

`func (o *Tickets) GetNotes() []Note`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Tickets) GetNotesOk() (*[]Note, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Tickets) SetNotes(v []Note)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Tickets) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetAttachments

`func (o *Tickets) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *Tickets) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *Tickets) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *Tickets) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *Tickets) GetContacts() []Contacts`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *Tickets) GetContactsOk() (*[]Contacts, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *Tickets) SetContacts(v []Contacts)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *Tickets) HasContacts() bool`

HasContacts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


