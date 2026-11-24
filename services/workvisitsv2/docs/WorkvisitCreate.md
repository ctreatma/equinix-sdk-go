# WorkvisitCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** | Description of the Work Visit | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Number / External Reference Number | [optional] 
**PurchaseOrder** | Pointer to [**PurchaseOrder**](PurchaseOrder.md) |  | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | File(s) attached to the Work visit. To learn about including attachments in your request, see POST Attachments API. | [optional] 
**Contacts** | Pointer to [**[]WorkvisitCreateContactsInner**](WorkvisitCreateContactsInner.md) | The ordering user is the default Technical and Notification contacts. If you would like to provide a different Technical contact and/or additional Notification contacts, specify the Technical contact and Notification contact(s) details. There can only be 1 Technical contact (registered user or not), but there can be more than 1 Notification contacts (registered users). | [optional] 
**Details** | [**WorkvisitCreateDetails**](WorkvisitCreateDetails.md) |  | 

## Methods

### NewWorkvisitCreate

`func NewWorkvisitCreate(details WorkvisitCreateDetails, ) *WorkvisitCreate`

NewWorkvisitCreate instantiates a new WorkvisitCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitCreateWithDefaults

`func NewWorkvisitCreateWithDefaults() *WorkvisitCreate`

NewWorkvisitCreateWithDefaults instantiates a new WorkvisitCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *WorkvisitCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkvisitCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkvisitCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *WorkvisitCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *WorkvisitCreate) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *WorkvisitCreate) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *WorkvisitCreate) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *WorkvisitCreate) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *WorkvisitCreate) GetPurchaseOrder() PurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *WorkvisitCreate) GetPurchaseOrderOk() (*PurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *WorkvisitCreate) SetPurchaseOrder(v PurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *WorkvisitCreate) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetAttachments

`func (o *WorkvisitCreate) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *WorkvisitCreate) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *WorkvisitCreate) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *WorkvisitCreate) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *WorkvisitCreate) GetContacts() []WorkvisitCreateContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *WorkvisitCreate) GetContactsOk() (*[]WorkvisitCreateContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *WorkvisitCreate) SetContacts(v []WorkvisitCreateContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *WorkvisitCreate) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetDetails

`func (o *WorkvisitCreate) GetDetails() WorkvisitCreateDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *WorkvisitCreate) GetDetailsOk() (*WorkvisitCreateDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *WorkvisitCreate) SetDetails(v WorkvisitCreateDetails)`

SetDetails sets Details field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


