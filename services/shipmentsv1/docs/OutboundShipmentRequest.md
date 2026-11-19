# OutboundShipmentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | [**[]ContactInfo**](ContactInfo.md) |  | 
**CustomerReferenceNumber** | Pointer to **map[string]interface{}** | You may use numbers and text in this field to enter reference information for your records. This will also appear in your reports and details. You may use this information to search for this content on the submitted requests page. | [optional] 
**PurchaseOrder** | Pointer to [**PurchaseOrder**](PurchaseOrder.md) |  | [optional] 
**IbxLocation** | [**IbxLocation**](IbxLocation.md) |  | 
**ServiceDetails** | [**OutboundServiceDetail**](OutboundServiceDetail.md) |  | 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | Attachments | [optional] 

## Methods

### NewOutboundShipmentRequest

`func NewOutboundShipmentRequest(contacts []ContactInfo, ibxLocation IbxLocation, serviceDetails OutboundServiceDetail, ) *OutboundShipmentRequest`

NewOutboundShipmentRequest instantiates a new OutboundShipmentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundShipmentRequestWithDefaults

`func NewOutboundShipmentRequestWithDefaults() *OutboundShipmentRequest`

NewOutboundShipmentRequestWithDefaults instantiates a new OutboundShipmentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *OutboundShipmentRequest) GetContacts() []ContactInfo`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *OutboundShipmentRequest) GetContactsOk() (*[]ContactInfo, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *OutboundShipmentRequest) SetContacts(v []ContactInfo)`

SetContacts sets Contacts field to given value.


### GetCustomerReferenceNumber

`func (o *OutboundShipmentRequest) GetCustomerReferenceNumber() map[string]interface{}`

GetCustomerReferenceNumber returns the CustomerReferenceNumber field if non-nil, zero value otherwise.

### GetCustomerReferenceNumberOk

`func (o *OutboundShipmentRequest) GetCustomerReferenceNumberOk() (*map[string]interface{}, bool)`

GetCustomerReferenceNumberOk returns a tuple with the CustomerReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceNumber

`func (o *OutboundShipmentRequest) SetCustomerReferenceNumber(v map[string]interface{})`

SetCustomerReferenceNumber sets CustomerReferenceNumber field to given value.

### HasCustomerReferenceNumber

`func (o *OutboundShipmentRequest) HasCustomerReferenceNumber() bool`

HasCustomerReferenceNumber returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *OutboundShipmentRequest) GetPurchaseOrder() PurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *OutboundShipmentRequest) GetPurchaseOrderOk() (*PurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *OutboundShipmentRequest) SetPurchaseOrder(v PurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *OutboundShipmentRequest) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetIbxLocation

`func (o *OutboundShipmentRequest) GetIbxLocation() IbxLocation`

GetIbxLocation returns the IbxLocation field if non-nil, zero value otherwise.

### GetIbxLocationOk

`func (o *OutboundShipmentRequest) GetIbxLocationOk() (*IbxLocation, bool)`

GetIbxLocationOk returns a tuple with the IbxLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocation

`func (o *OutboundShipmentRequest) SetIbxLocation(v IbxLocation)`

SetIbxLocation sets IbxLocation field to given value.


### GetServiceDetails

`func (o *OutboundShipmentRequest) GetServiceDetails() OutboundServiceDetail`

GetServiceDetails returns the ServiceDetails field if non-nil, zero value otherwise.

### GetServiceDetailsOk

`func (o *OutboundShipmentRequest) GetServiceDetailsOk() (*OutboundServiceDetail, bool)`

GetServiceDetailsOk returns a tuple with the ServiceDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDetails

`func (o *OutboundShipmentRequest) SetServiceDetails(v OutboundServiceDetail)`

SetServiceDetails sets ServiceDetails field to given value.


### GetAttachments

`func (o *OutboundShipmentRequest) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *OutboundShipmentRequest) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *OutboundShipmentRequest) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *OutboundShipmentRequest) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


