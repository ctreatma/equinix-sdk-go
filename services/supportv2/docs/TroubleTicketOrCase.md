# TroubleTicketOrCase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | [**TroubleTicketOrCaseCode**](TroubleTicketOrCaseCode.md) |  | 
**Description** | **string** | Description of the trouble or issue. | 
**PrimaryId** | Pointer to **string** | Primary reference identifier. | [optional] 
**SecondaryId** | Pointer to **string** | Secondary reference identifier. | [optional] 
**OccurredDateTime** | Pointer to **time.Time** | Date and time the issue occurred. | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer or external reference number. | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | Supporting files to attach in the ticket, such as a picture of a broken device. | [optional] 
**Contacts** | Pointer to [**[]TroubleTicketOrCaseContactsInner**](TroubleTicketOrCaseContactsInner.md) | List of persons who will be contacted for this ticket. | [optional] 
**Details** | Pointer to [**TroubleTicketOrCaseDetails**](TroubleTicketOrCaseDetails.md) |  | [optional] 

## Methods

### NewTroubleTicketOrCase

`func NewTroubleTicketOrCase(code TroubleTicketOrCaseCode, description string, ) *TroubleTicketOrCase`

NewTroubleTicketOrCase instantiates a new TroubleTicketOrCase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketOrCaseWithDefaults

`func NewTroubleTicketOrCaseWithDefaults() *TroubleTicketOrCase`

NewTroubleTicketOrCaseWithDefaults instantiates a new TroubleTicketOrCase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TroubleTicketOrCase) GetCode() TroubleTicketOrCaseCode`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TroubleTicketOrCase) GetCodeOk() (*TroubleTicketOrCaseCode, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TroubleTicketOrCase) SetCode(v TroubleTicketOrCaseCode)`

SetCode sets Code field to given value.


### GetDescription

`func (o *TroubleTicketOrCase) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TroubleTicketOrCase) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TroubleTicketOrCase) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetPrimaryId

`func (o *TroubleTicketOrCase) GetPrimaryId() string`

GetPrimaryId returns the PrimaryId field if non-nil, zero value otherwise.

### GetPrimaryIdOk

`func (o *TroubleTicketOrCase) GetPrimaryIdOk() (*string, bool)`

GetPrimaryIdOk returns a tuple with the PrimaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryId

`func (o *TroubleTicketOrCase) SetPrimaryId(v string)`

SetPrimaryId sets PrimaryId field to given value.

### HasPrimaryId

`func (o *TroubleTicketOrCase) HasPrimaryId() bool`

HasPrimaryId returns a boolean if a field has been set.

### GetSecondaryId

`func (o *TroubleTicketOrCase) GetSecondaryId() string`

GetSecondaryId returns the SecondaryId field if non-nil, zero value otherwise.

### GetSecondaryIdOk

`func (o *TroubleTicketOrCase) GetSecondaryIdOk() (*string, bool)`

GetSecondaryIdOk returns a tuple with the SecondaryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryId

`func (o *TroubleTicketOrCase) SetSecondaryId(v string)`

SetSecondaryId sets SecondaryId field to given value.

### HasSecondaryId

`func (o *TroubleTicketOrCase) HasSecondaryId() bool`

HasSecondaryId returns a boolean if a field has been set.

### GetOccurredDateTime

`func (o *TroubleTicketOrCase) GetOccurredDateTime() time.Time`

GetOccurredDateTime returns the OccurredDateTime field if non-nil, zero value otherwise.

### GetOccurredDateTimeOk

`func (o *TroubleTicketOrCase) GetOccurredDateTimeOk() (*time.Time, bool)`

GetOccurredDateTimeOk returns a tuple with the OccurredDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredDateTime

`func (o *TroubleTicketOrCase) SetOccurredDateTime(v time.Time)`

SetOccurredDateTime sets OccurredDateTime field to given value.

### HasOccurredDateTime

`func (o *TroubleTicketOrCase) HasOccurredDateTime() bool`

HasOccurredDateTime returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *TroubleTicketOrCase) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *TroubleTicketOrCase) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *TroubleTicketOrCase) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *TroubleTicketOrCase) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAttachments

`func (o *TroubleTicketOrCase) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *TroubleTicketOrCase) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *TroubleTicketOrCase) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *TroubleTicketOrCase) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *TroubleTicketOrCase) GetContacts() []TroubleTicketOrCaseContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *TroubleTicketOrCase) GetContactsOk() (*[]TroubleTicketOrCaseContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *TroubleTicketOrCase) SetContacts(v []TroubleTicketOrCaseContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *TroubleTicketOrCase) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetDetails

`func (o *TroubleTicketOrCase) GetDetails() TroubleTicketOrCaseDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *TroubleTicketOrCase) GetDetailsOk() (*TroubleTicketOrCaseDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *TroubleTicketOrCase) SetDetails(v TroubleTicketOrCaseDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *TroubleTicketOrCase) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


