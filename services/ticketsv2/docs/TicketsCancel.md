# TicketsCancel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reason** | **string** | Description of the trouble or issue. | 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | File(s) attached to the ticket. e.g. picture of broken device, scanned copy of bill or charge. To learn about including attachments in your request, see POST Attachments API. | [optional] 

## Methods

### NewTicketsCancel

`func NewTicketsCancel(reason string, ) *TicketsCancel`

NewTicketsCancel instantiates a new TicketsCancel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsCancelWithDefaults

`func NewTicketsCancelWithDefaults() *TicketsCancel`

NewTicketsCancelWithDefaults instantiates a new TicketsCancel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReason

`func (o *TicketsCancel) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *TicketsCancel) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *TicketsCancel) SetReason(v string)`

SetReason sets Reason field to given value.


### GetAttachments

`func (o *TicketsCancel) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *TicketsCancel) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *TicketsCancel) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *TicketsCancel) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


