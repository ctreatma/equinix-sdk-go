# OutboundShipmentsUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | Pointer to [**InboundShipmentsUpdateAllOfCarrier**](InboundShipmentsUpdateAllOfCarrier.md) |  | [optional] 
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. | [optional] 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be sent.  | [optional] 
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars.  | [optional] 
**DeclaredValueCurrency** | Pointer to [**DeclaredValueCurrency**](DeclaredValueCurrency.md) |  | [optional] 
**RequirePickup** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will pick up shipment from your cage. Note that this will incur additional Smarthands fees based on contract rate. | [optional] 
**InsureShipment** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will insure outbound shipment .Note that this will incur additional Smarthands fees based on contract rate. | [optional] 
**ShipmentAttachmentId** | Pointer to **string** | Attachment ID of uploaded shipment label. Refer to Attachment API on how to upload documents via API | [optional] 
**ShipmentAddress** | Pointer to [**ShipmentAddress**](ShipmentAddress.md) |  | [optional] 

## Methods

### NewOutboundShipmentsUpdate

`func NewOutboundShipmentsUpdate() *OutboundShipmentsUpdate`

NewOutboundShipmentsUpdate instantiates a new OutboundShipmentsUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundShipmentsUpdateWithDefaults

`func NewOutboundShipmentsUpdateWithDefaults() *OutboundShipmentsUpdate`

NewOutboundShipmentsUpdateWithDefaults instantiates a new OutboundShipmentsUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *OutboundShipmentsUpdate) GetCarrier() InboundShipmentsUpdateAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *OutboundShipmentsUpdate) GetCarrierOk() (*InboundShipmentsUpdateAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *OutboundShipmentsUpdate) SetCarrier(v InboundShipmentsUpdateAllOfCarrier)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *OutboundShipmentsUpdate) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCarrierTrackingNumbers

`func (o *OutboundShipmentsUpdate) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *OutboundShipmentsUpdate) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *OutboundShipmentsUpdate) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *OutboundShipmentsUpdate) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCarrierName

`func (o *OutboundShipmentsUpdate) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *OutboundShipmentsUpdate) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *OutboundShipmentsUpdate) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *OutboundShipmentsUpdate) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *OutboundShipmentsUpdate) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *OutboundShipmentsUpdate) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *OutboundShipmentsUpdate) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *OutboundShipmentsUpdate) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *OutboundShipmentsUpdate) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *OutboundShipmentsUpdate) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *OutboundShipmentsUpdate) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *OutboundShipmentsUpdate) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetDeclaredValueCurrency

`func (o *OutboundShipmentsUpdate) GetDeclaredValueCurrency() DeclaredValueCurrency`

GetDeclaredValueCurrency returns the DeclaredValueCurrency field if non-nil, zero value otherwise.

### GetDeclaredValueCurrencyOk

`func (o *OutboundShipmentsUpdate) GetDeclaredValueCurrencyOk() (*DeclaredValueCurrency, bool)`

GetDeclaredValueCurrencyOk returns a tuple with the DeclaredValueCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValueCurrency

`func (o *OutboundShipmentsUpdate) SetDeclaredValueCurrency(v DeclaredValueCurrency)`

SetDeclaredValueCurrency sets DeclaredValueCurrency field to given value.

### HasDeclaredValueCurrency

`func (o *OutboundShipmentsUpdate) HasDeclaredValueCurrency() bool`

HasDeclaredValueCurrency returns a boolean if a field has been set.

### GetRequirePickup

`func (o *OutboundShipmentsUpdate) GetRequirePickup() bool`

GetRequirePickup returns the RequirePickup field if non-nil, zero value otherwise.

### GetRequirePickupOk

`func (o *OutboundShipmentsUpdate) GetRequirePickupOk() (*bool, bool)`

GetRequirePickupOk returns a tuple with the RequirePickup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirePickup

`func (o *OutboundShipmentsUpdate) SetRequirePickup(v bool)`

SetRequirePickup sets RequirePickup field to given value.

### HasRequirePickup

`func (o *OutboundShipmentsUpdate) HasRequirePickup() bool`

HasRequirePickup returns a boolean if a field has been set.

### GetInsureShipment

`func (o *OutboundShipmentsUpdate) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *OutboundShipmentsUpdate) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *OutboundShipmentsUpdate) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *OutboundShipmentsUpdate) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetShipmentAttachmentId

`func (o *OutboundShipmentsUpdate) GetShipmentAttachmentId() string`

GetShipmentAttachmentId returns the ShipmentAttachmentId field if non-nil, zero value otherwise.

### GetShipmentAttachmentIdOk

`func (o *OutboundShipmentsUpdate) GetShipmentAttachmentIdOk() (*string, bool)`

GetShipmentAttachmentIdOk returns a tuple with the ShipmentAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAttachmentId

`func (o *OutboundShipmentsUpdate) SetShipmentAttachmentId(v string)`

SetShipmentAttachmentId sets ShipmentAttachmentId field to given value.

### HasShipmentAttachmentId

`func (o *OutboundShipmentsUpdate) HasShipmentAttachmentId() bool`

HasShipmentAttachmentId returns a boolean if a field has been set.

### GetShipmentAddress

`func (o *OutboundShipmentsUpdate) GetShipmentAddress() ShipmentAddress`

GetShipmentAddress returns the ShipmentAddress field if non-nil, zero value otherwise.

### GetShipmentAddressOk

`func (o *OutboundShipmentsUpdate) GetShipmentAddressOk() (*ShipmentAddress, bool)`

GetShipmentAddressOk returns a tuple with the ShipmentAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAddress

`func (o *OutboundShipmentsUpdate) SetShipmentAddress(v ShipmentAddress)`

SetShipmentAddress sets ShipmentAddress field to given value.

### HasShipmentAddress

`func (o *OutboundShipmentsUpdate) HasShipmentAddress() bool`

HasShipmentAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


