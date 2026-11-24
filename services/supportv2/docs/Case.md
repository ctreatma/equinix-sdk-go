# Case

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Ticket code. See GET /support/v2/tickets/codes for the list of valid ticket codes, and GET /support/v2/tickets/codes/{code}/schema for the required fields for a given ticket code. | 
**Description** | **string** | Description of the issue. | 
**PrimaryId** | Pointer to **string** | Primary reference identifier. | [optional] 
**SecondaryId** | Pointer to **string** | Secondary reference identifier. | [optional] 
**OccurredDateTime** | Pointer to **time.Time** | Date and time the issue occurred. | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer or external reference number. | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | Supporting files to attach in the case, such as a picture of a broken device. | [optional] 
**Contacts** | Pointer to [**[]CaseContactsInner**](CaseContactsInner.md) | List of persons who will be contacted for this case. | [optional] 
**Details** | Pointer to **map[string]interface{}** | Additional details or requirements for case resolution. The shape depends on the ticket code — see GET /support/v2/tickets/codes/{code}/schema for the fields applicable to a given code. | [optional] 

## Methods

### NewCase

`func NewCase(code string, description string, ) *Case`

NewCase instantiates a new Case object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCaseWithDefaults

`func NewCaseWithDefaults() *Case`

NewCaseWithDefaults instantiates a new Case object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *Case) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Case) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Case) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *Case) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Case) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Case) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetPrimaryId

`func (o *Case) GetPrimaryId() string`

GetPrimaryId returns the PrimaryId field if non-nil, zero value otherwise.

### GetPrimaryIdOk

`func (o *Case) GetPrimaryIdOk() (*string, bool)`

GetPrimaryIdOk returns a tuple with the PrimaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryId

`func (o *Case) SetPrimaryId(v string)`

SetPrimaryId sets PrimaryId field to given value.

### HasPrimaryId

`func (o *Case) HasPrimaryId() bool`

HasPrimaryId returns a boolean if a field has been set.

### GetSecondaryId

`func (o *Case) GetSecondaryId() string`

GetSecondaryId returns the SecondaryId field if non-nil, zero value otherwise.

### GetSecondaryIdOk

`func (o *Case) GetSecondaryIdOk() (*string, bool)`

GetSecondaryIdOk returns a tuple with the SecondaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryId

`func (o *Case) SetSecondaryId(v string)`

SetSecondaryId sets SecondaryId field to given value.

### HasSecondaryId

`func (o *Case) HasSecondaryId() bool`

HasSecondaryId returns a boolean if a field has been set.

### GetOccurredDateTime

`func (o *Case) GetOccurredDateTime() time.Time`

GetOccurredDateTime returns the OccurredDateTime field if non-nil, zero value otherwise.

### GetOccurredDateTimeOk

`func (o *Case) GetOccurredDateTimeOk() (*time.Time, bool)`

GetOccurredDateTimeOk returns a tuple with the OccurredDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredDateTime

`func (o *Case) SetOccurredDateTime(v time.Time)`

SetOccurredDateTime sets OccurredDateTime field to given value.

### HasOccurredDateTime

`func (o *Case) HasOccurredDateTime() bool`

HasOccurredDateTime returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *Case) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *Case) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *Case) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *Case) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAttachments

`func (o *Case) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *Case) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *Case) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *Case) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *Case) GetContacts() []CaseContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *Case) GetContactsOk() (*[]CaseContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *Case) SetContacts(v []CaseContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *Case) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetDetails

`func (o *Case) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Case) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Case) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Case) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


