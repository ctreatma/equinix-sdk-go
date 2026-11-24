# SingleCaseResponseV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier used to retrieve a case, provided as either the case number or the order number. | [optional] 
**AccountNumber** | Pointer to **string** | User account number. | [optional] 
**AccountName** | Pointer to **string** | User account name. | [optional] 
**CustomerReferenceId** | Pointer to **string** | Additional information for customer to reference. | [optional] 
**Channel** | Pointer to [**SingleCaseResponseV2Channel**](SingleCaseResponseV2Channel.md) |  | [optional] 
**OrderId** | Pointer to **string** | Unique identifier assigned to an order, used to retrieve or reference the case associated with it. | [optional] 
**Location** | Pointer to [**SingleCaseResponseV2Location**](SingleCaseResponseV2Location.md) |  | [optional] 
**Status** | Pointer to [**StatusResponse**](StatusResponse.md) |  | [optional] 
**Contacts** | Pointer to [**[]ContactResponse**](ContactResponse.md) | List of individuals associated with the case who are contacted regarding it. | [optional] 
**Notes** | Pointer to [**[]SingleCaseResponseV2NotesInner**](SingleCaseResponseV2NotesInner.md) | Notes added to the case. | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | File(s) attached to the case. e.g. picture of broken device, scanning of a bill or charge, etc... | [optional] 
**Email** | Pointer to [**[]Email**](Email.md) | Email conversation(s) attached to the case. e.g. email conversation with a technician, email conversation with a customer, etc... | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | A datetime string with format YYYY-MM-DDTHH:mm:ss.sssZ. | [optional] 
**OtherDetails** | Pointer to [**SingleCaseResponseV2OtherDetails**](SingleCaseResponseV2OtherDetails.md) |  | [optional] 

## Methods

### NewSingleCaseResponseV2

`func NewSingleCaseResponseV2() *SingleCaseResponseV2`

NewSingleCaseResponseV2 instantiates a new SingleCaseResponseV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSingleCaseResponseV2WithDefaults

`func NewSingleCaseResponseV2WithDefaults() *SingleCaseResponseV2`

NewSingleCaseResponseV2WithDefaults instantiates a new SingleCaseResponseV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SingleCaseResponseV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SingleCaseResponseV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SingleCaseResponseV2) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SingleCaseResponseV2) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *SingleCaseResponseV2) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *SingleCaseResponseV2) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *SingleCaseResponseV2) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *SingleCaseResponseV2) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountName

`func (o *SingleCaseResponseV2) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *SingleCaseResponseV2) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *SingleCaseResponseV2) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *SingleCaseResponseV2) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *SingleCaseResponseV2) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *SingleCaseResponseV2) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *SingleCaseResponseV2) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *SingleCaseResponseV2) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetChannel

`func (o *SingleCaseResponseV2) GetChannel() SingleCaseResponseV2Channel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *SingleCaseResponseV2) GetChannelOk() (*SingleCaseResponseV2Channel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *SingleCaseResponseV2) SetChannel(v SingleCaseResponseV2Channel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *SingleCaseResponseV2) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetOrderId

`func (o *SingleCaseResponseV2) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *SingleCaseResponseV2) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *SingleCaseResponseV2) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *SingleCaseResponseV2) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetLocation

`func (o *SingleCaseResponseV2) GetLocation() SingleCaseResponseV2Location`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *SingleCaseResponseV2) GetLocationOk() (*SingleCaseResponseV2Location, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *SingleCaseResponseV2) SetLocation(v SingleCaseResponseV2Location)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *SingleCaseResponseV2) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetStatus

`func (o *SingleCaseResponseV2) GetStatus() StatusResponse`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SingleCaseResponseV2) GetStatusOk() (*StatusResponse, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SingleCaseResponseV2) SetStatus(v StatusResponse)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SingleCaseResponseV2) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetContacts

`func (o *SingleCaseResponseV2) GetContacts() []ContactResponse`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *SingleCaseResponseV2) GetContactsOk() (*[]ContactResponse, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *SingleCaseResponseV2) SetContacts(v []ContactResponse)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *SingleCaseResponseV2) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetNotes

`func (o *SingleCaseResponseV2) GetNotes() []SingleCaseResponseV2NotesInner`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SingleCaseResponseV2) GetNotesOk() (*[]SingleCaseResponseV2NotesInner, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SingleCaseResponseV2) SetNotes(v []SingleCaseResponseV2NotesInner)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SingleCaseResponseV2) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetAttachments

`func (o *SingleCaseResponseV2) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *SingleCaseResponseV2) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *SingleCaseResponseV2) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *SingleCaseResponseV2) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetEmail

`func (o *SingleCaseResponseV2) GetEmail() []Email`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SingleCaseResponseV2) GetEmailOk() (*[]Email, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SingleCaseResponseV2) SetEmail(v []Email)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SingleCaseResponseV2) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *SingleCaseResponseV2) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *SingleCaseResponseV2) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *SingleCaseResponseV2) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *SingleCaseResponseV2) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetOtherDetails

`func (o *SingleCaseResponseV2) GetOtherDetails() SingleCaseResponseV2OtherDetails`

GetOtherDetails returns the OtherDetails field if non-nil, zero value otherwise.

### GetOtherDetailsOk

`func (o *SingleCaseResponseV2) GetOtherDetailsOk() (*SingleCaseResponseV2OtherDetails, bool)`

GetOtherDetailsOk returns a tuple with the OtherDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherDetails

`func (o *SingleCaseResponseV2) SetOtherDetails(v SingleCaseResponseV2OtherDetails)`

SetOtherDetails sets OtherDetails field to given value.

### HasOtherDetails

`func (o *SingleCaseResponseV2) HasOtherDetails() bool`

HasOtherDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


