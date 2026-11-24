# Layer1Create

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerReferenceId** | Pointer to **string** | Customer Reference Identifier / External Reference Identifier | [optional] 
**Attachments** | Pointer to [**[]AttachmentRequest**](AttachmentRequest.md) | File(s) attached to the Cross Connect | [optional] 
**Description** | Pointer to **string** | Description of Cross Connect | [optional] 
**ExpediteDateTime** | Pointer to **time.Time** | Expedite orders are delivered within the next 2 - 24 hours. Value must be in ISO-8601 UTC timezone format. | [optional] 
**Details** | [**[]Layer1Details**](Layer1Details.md) | Cross connections details | 
**PurchaseOrder** | Pointer to [**PurchaseOrder**](PurchaseOrder.md) |  | [optional] 
**Contacts** | Pointer to [**[]Layer1CreateContactsInner**](Layer1CreateContactsInner.md) |  | [optional] 

## Methods

### NewLayer1Create

`func NewLayer1Create(details []Layer1Details, ) *Layer1Create`

NewLayer1Create instantiates a new Layer1Create object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayer1CreateWithDefaults

`func NewLayer1CreateWithDefaults() *Layer1Create`

NewLayer1CreateWithDefaults instantiates a new Layer1Create object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerReferenceId

`func (o *Layer1Create) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *Layer1Create) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *Layer1Create) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *Layer1Create) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAttachments

`func (o *Layer1Create) GetAttachments() []AttachmentRequest`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *Layer1Create) GetAttachmentsOk() (*[]AttachmentRequest, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *Layer1Create) SetAttachments(v []AttachmentRequest)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *Layer1Create) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDescription

`func (o *Layer1Create) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Layer1Create) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Layer1Create) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Layer1Create) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetExpediteDateTime

`func (o *Layer1Create) GetExpediteDateTime() time.Time`

GetExpediteDateTime returns the ExpediteDateTime field if non-nil, zero value otherwise.

### GetExpediteDateTimeOk

`func (o *Layer1Create) GetExpediteDateTimeOk() (*time.Time, bool)`

GetExpediteDateTimeOk returns a tuple with the ExpediteDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpediteDateTime

`func (o *Layer1Create) SetExpediteDateTime(v time.Time)`

SetExpediteDateTime sets ExpediteDateTime field to given value.

### HasExpediteDateTime

`func (o *Layer1Create) HasExpediteDateTime() bool`

HasExpediteDateTime returns a boolean if a field has been set.

### GetDetails

`func (o *Layer1Create) GetDetails() []Layer1Details`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Layer1Create) GetDetailsOk() (*[]Layer1Details, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Layer1Create) SetDetails(v []Layer1Details)`

SetDetails sets Details field to given value.


### GetPurchaseOrder

`func (o *Layer1Create) GetPurchaseOrder() PurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *Layer1Create) GetPurchaseOrderOk() (*PurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *Layer1Create) SetPurchaseOrder(v PurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *Layer1Create) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetContacts

`func (o *Layer1Create) GetContacts() []Layer1CreateContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *Layer1Create) GetContactsOk() (*[]Layer1CreateContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *Layer1Create) SetContacts(v []Layer1CreateContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *Layer1Create) HasContacts() bool`

HasContacts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


