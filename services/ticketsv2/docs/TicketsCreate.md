# TicketsCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | [**TicketsCreateCode**](TicketsCreateCode.md) |  | 
**Description** | **string** | Description of the trouble or issue. | 
**PrimaryId** | **string** | Primary reference identifier. | 
**OccurredDateTime** | **time.Time** | Date and time the issue occurred. | 
**SecondaryId** | Pointer to **string** | Secondary reference identifier | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Number / External Reference Number. | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | File(s) attached to the ticket. e.g. picture of broken device, scanned copy of bill or charge. To learn about including attachments in your request, see POST Attachments API. | [optional] 
**Contacts** | Pointer to [**[]TicketsCreateContactsInner**](TicketsCreateContactsInner.md) | List of persons who will be contacted for this ticket. | [optional] 
**Details** | Pointer to [**TicketsDetails**](TicketsDetails.md) |  | [optional] 

## Methods

### NewTicketsCreate

`func NewTicketsCreate(code TicketsCreateCode, description string, primaryId string, occurredDateTime time.Time, ) *TicketsCreate`

NewTicketsCreate instantiates a new TicketsCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsCreateWithDefaults

`func NewTicketsCreateWithDefaults() *TicketsCreate`

NewTicketsCreateWithDefaults instantiates a new TicketsCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TicketsCreate) GetCode() TicketsCreateCode`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TicketsCreate) GetCodeOk() (*TicketsCreateCode, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TicketsCreate) SetCode(v TicketsCreateCode)`

SetCode sets Code field to given value.


### GetDescription

`func (o *TicketsCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TicketsCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TicketsCreate) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetPrimaryId

`func (o *TicketsCreate) GetPrimaryId() string`

GetPrimaryId returns the PrimaryId field if non-nil, zero value otherwise.

### GetPrimaryIdOk

`func (o *TicketsCreate) GetPrimaryIdOk() (*string, bool)`

GetPrimaryIdOk returns a tuple with the PrimaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryId

`func (o *TicketsCreate) SetPrimaryId(v string)`

SetPrimaryId sets PrimaryId field to given value.


### GetOccurredDateTime

`func (o *TicketsCreate) GetOccurredDateTime() time.Time`

GetOccurredDateTime returns the OccurredDateTime field if non-nil, zero value otherwise.

### GetOccurredDateTimeOk

`func (o *TicketsCreate) GetOccurredDateTimeOk() (*time.Time, bool)`

GetOccurredDateTimeOk returns a tuple with the OccurredDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredDateTime

`func (o *TicketsCreate) SetOccurredDateTime(v time.Time)`

SetOccurredDateTime sets OccurredDateTime field to given value.


### GetSecondaryId

`func (o *TicketsCreate) GetSecondaryId() string`

GetSecondaryId returns the SecondaryId field if non-nil, zero value otherwise.

### GetSecondaryIdOk

`func (o *TicketsCreate) GetSecondaryIdOk() (*string, bool)`

GetSecondaryIdOk returns a tuple with the SecondaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryId

`func (o *TicketsCreate) SetSecondaryId(v string)`

SetSecondaryId sets SecondaryId field to given value.

### HasSecondaryId

`func (o *TicketsCreate) HasSecondaryId() bool`

HasSecondaryId returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *TicketsCreate) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *TicketsCreate) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *TicketsCreate) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *TicketsCreate) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAttachments

`func (o *TicketsCreate) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *TicketsCreate) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *TicketsCreate) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *TicketsCreate) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *TicketsCreate) GetContacts() []TicketsCreateContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *TicketsCreate) GetContactsOk() (*[]TicketsCreateContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *TicketsCreate) SetContacts(v []TicketsCreateContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *TicketsCreate) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetDetails

`func (o *TicketsCreate) GetDetails() TicketsDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *TicketsCreate) GetDetailsOk() (*TicketsDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *TicketsCreate) SetDetails(v TicketsDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *TicketsCreate) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


