# Layer1DeinstallRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerReferenceId** | Pointer to **string** | Customer Reference Identifier / External Reference Identifier | [optional] 
**PurchaseOrder** | Pointer to [**PurchaseOrder**](PurchaseOrder.md) |  | [optional] 
**Contacts** | Pointer to [**[]Layer1CreateContactsInner**](Layer1CreateContactsInner.md) |  | [optional] 
**Attachments** | Pointer to [**[]AttachmentRequest**](AttachmentRequest.md) | File(s) attached to the layer #1 connections | [optional] 
**Description** | Pointer to **string** | Description of deinstallation | [optional] 
**Details** | [**[]Layer1DeinstallDetails**](Layer1DeinstallDetails.md) |  layer #1 connections details | 
**RemovalDate** | **string** | Equinix will aim to terminate this Cross Connect at this date subjected to operation availability. | 

## Methods

### NewLayer1DeinstallRequest

`func NewLayer1DeinstallRequest(details []Layer1DeinstallDetails, removalDate string, ) *Layer1DeinstallRequest`

NewLayer1DeinstallRequest instantiates a new Layer1DeinstallRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayer1DeinstallRequestWithDefaults

`func NewLayer1DeinstallRequestWithDefaults() *Layer1DeinstallRequest`

NewLayer1DeinstallRequestWithDefaults instantiates a new Layer1DeinstallRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerReferenceId

`func (o *Layer1DeinstallRequest) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *Layer1DeinstallRequest) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *Layer1DeinstallRequest) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *Layer1DeinstallRequest) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *Layer1DeinstallRequest) GetPurchaseOrder() PurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *Layer1DeinstallRequest) GetPurchaseOrderOk() (*PurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *Layer1DeinstallRequest) SetPurchaseOrder(v PurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *Layer1DeinstallRequest) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetContacts

`func (o *Layer1DeinstallRequest) GetContacts() []Layer1CreateContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *Layer1DeinstallRequest) GetContactsOk() (*[]Layer1CreateContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *Layer1DeinstallRequest) SetContacts(v []Layer1CreateContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *Layer1DeinstallRequest) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetAttachments

`func (o *Layer1DeinstallRequest) GetAttachments() []AttachmentRequest`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *Layer1DeinstallRequest) GetAttachmentsOk() (*[]AttachmentRequest, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *Layer1DeinstallRequest) SetAttachments(v []AttachmentRequest)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *Layer1DeinstallRequest) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDescription

`func (o *Layer1DeinstallRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Layer1DeinstallRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Layer1DeinstallRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Layer1DeinstallRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDetails

`func (o *Layer1DeinstallRequest) GetDetails() []Layer1DeinstallDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Layer1DeinstallRequest) GetDetailsOk() (*[]Layer1DeinstallDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Layer1DeinstallRequest) SetDetails(v []Layer1DeinstallDetails)`

SetDetails sets Details field to given value.


### GetRemovalDate

`func (o *Layer1DeinstallRequest) GetRemovalDate() string`

GetRemovalDate returns the RemovalDate field if non-nil, zero value otherwise.

### GetRemovalDateOk

`func (o *Layer1DeinstallRequest) GetRemovalDateOk() (*string, bool)`

GetRemovalDateOk returns a tuple with the RemovalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovalDate

`func (o *Layer1DeinstallRequest) SetRemovalDate(v string)`

SetRemovalDate sets RemovalDate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


