# ShipmentCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**ShipmentCreateType**](ShipmentCreateType.md) |  | 
**RequestedDateTime** | **time.Time** | Date and time of shipment schedule  in UTC timezone in ISO 8601 format. | 
**CageId** | **string** | ID of cage where shipment is to be delivered to or retrieve from. | 
**Details** | [**ShipmentCreateDetails**](ShipmentCreateDetails.md) |  | 
**AccountNumber** | Pointer to **string** | Customer account number. This is required if cage is shared. | [optional] 
**Description** | Pointer to **string** | Any additional information that the technician may need to complete your request | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Number / External Reference Number | [optional] 
**PurchaseOrder** | Pointer to [**PurchaseOrder**](PurchaseOrder.md) |  | [optional] 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | Additional attachments that is required to facilitate scheduled shipments such as instruction manual or photos. To learn about including attachments in your request, see POST Attachment API.  | [optional] 
**Contacts** | Pointer to [**[]ShipmentCreateContactsInner**](ShipmentCreateContactsInner.md) | The ordering user is the default Technical and Notification contacts. If you would like to provide a different Technical contact and/or additional Notification contacts, provide the Techical contact and Notificition contact(s) details. There can only be 1 Technical contact (registered user or not), but there can be more than 1 Notification contacts (registered users). | [optional] 

## Methods

### NewShipmentCreate

`func NewShipmentCreate(type_ ShipmentCreateType, requestedDateTime time.Time, cageId string, details ShipmentCreateDetails, ) *ShipmentCreate`

NewShipmentCreate instantiates a new ShipmentCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentCreateWithDefaults

`func NewShipmentCreateWithDefaults() *ShipmentCreate`

NewShipmentCreateWithDefaults instantiates a new ShipmentCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ShipmentCreate) GetType() ShipmentCreateType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ShipmentCreate) GetTypeOk() (*ShipmentCreateType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ShipmentCreate) SetType(v ShipmentCreateType)`

SetType sets Type field to given value.


### GetRequestedDateTime

`func (o *ShipmentCreate) GetRequestedDateTime() time.Time`

GetRequestedDateTime returns the RequestedDateTime field if non-nil, zero value otherwise.

### GetRequestedDateTimeOk

`func (o *ShipmentCreate) GetRequestedDateTimeOk() (*time.Time, bool)`

GetRequestedDateTimeOk returns a tuple with the RequestedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDateTime

`func (o *ShipmentCreate) SetRequestedDateTime(v time.Time)`

SetRequestedDateTime sets RequestedDateTime field to given value.


### GetCageId

`func (o *ShipmentCreate) GetCageId() string`

GetCageId returns the CageId field if non-nil, zero value otherwise.

### GetCageIdOk

`func (o *ShipmentCreate) GetCageIdOk() (*string, bool)`

GetCageIdOk returns a tuple with the CageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageId

`func (o *ShipmentCreate) SetCageId(v string)`

SetCageId sets CageId field to given value.


### GetDetails

`func (o *ShipmentCreate) GetDetails() ShipmentCreateDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ShipmentCreate) GetDetailsOk() (*ShipmentCreateDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ShipmentCreate) SetDetails(v ShipmentCreateDetails)`

SetDetails sets Details field to given value.


### GetAccountNumber

`func (o *ShipmentCreate) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *ShipmentCreate) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *ShipmentCreate) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *ShipmentCreate) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetDescription

`func (o *ShipmentCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ShipmentCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ShipmentCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ShipmentCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *ShipmentCreate) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *ShipmentCreate) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *ShipmentCreate) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *ShipmentCreate) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *ShipmentCreate) GetPurchaseOrder() PurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *ShipmentCreate) GetPurchaseOrderOk() (*PurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *ShipmentCreate) SetPurchaseOrder(v PurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *ShipmentCreate) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetAttachments

`func (o *ShipmentCreate) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ShipmentCreate) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ShipmentCreate) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ShipmentCreate) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContacts

`func (o *ShipmentCreate) GetContacts() []ShipmentCreateContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ShipmentCreate) GetContactsOk() (*[]ShipmentCreateContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ShipmentCreate) SetContacts(v []ShipmentCreateContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *ShipmentCreate) HasContacts() bool`

HasContacts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


