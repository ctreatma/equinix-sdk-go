# OutboundShipmentsCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | [**InboundShipmentsAllOfCarrier**](InboundShipmentsAllOfCarrier.md) |  | 
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be sent. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60;  | [optional] 
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**DeclaredValueCurrency** | Pointer to [**DeclaredValueCurrency**](DeclaredValueCurrency.md) |  | [optional] 
**RequirePickup** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will pick up shipment from your cage. Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**InsureShipment** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will insure outbound shipment .Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**ShipmentLabelRequired** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will print shipment label for your package. Address information for shipment label can be uploaded as an label attachment or as address fields. | [optional] [default to true]
**ShipmentAttachmentId** | Pointer to **string** | Attachment ID of uploaded shipment label. Refer to Attachment API on how to upload documents via API | [optional] 
**ShipmentAddress** | Pointer to [**ShipmentAddress**](ShipmentAddress.md) |  | [optional] 

## Methods

### NewOutboundShipmentsCreate

`func NewOutboundShipmentsCreate(carrier InboundShipmentsAllOfCarrier, ) *OutboundShipmentsCreate`

NewOutboundShipmentsCreate instantiates a new OutboundShipmentsCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundShipmentsCreateWithDefaults

`func NewOutboundShipmentsCreateWithDefaults() *OutboundShipmentsCreate`

NewOutboundShipmentsCreateWithDefaults instantiates a new OutboundShipmentsCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *OutboundShipmentsCreate) GetCarrier() InboundShipmentsAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *OutboundShipmentsCreate) GetCarrierOk() (*InboundShipmentsAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *OutboundShipmentsCreate) SetCarrier(v InboundShipmentsAllOfCarrier)`

SetCarrier sets Carrier field to given value.


### GetCarrierTrackingNumbers

`func (o *OutboundShipmentsCreate) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *OutboundShipmentsCreate) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *OutboundShipmentsCreate) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *OutboundShipmentsCreate) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCarrierName

`func (o *OutboundShipmentsCreate) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *OutboundShipmentsCreate) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *OutboundShipmentsCreate) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *OutboundShipmentsCreate) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *OutboundShipmentsCreate) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *OutboundShipmentsCreate) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *OutboundShipmentsCreate) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *OutboundShipmentsCreate) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *OutboundShipmentsCreate) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *OutboundShipmentsCreate) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *OutboundShipmentsCreate) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *OutboundShipmentsCreate) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetDeclaredValueCurrency

`func (o *OutboundShipmentsCreate) GetDeclaredValueCurrency() DeclaredValueCurrency`

GetDeclaredValueCurrency returns the DeclaredValueCurrency field if non-nil, zero value otherwise.

### GetDeclaredValueCurrencyOk

`func (o *OutboundShipmentsCreate) GetDeclaredValueCurrencyOk() (*DeclaredValueCurrency, bool)`

GetDeclaredValueCurrencyOk returns a tuple with the DeclaredValueCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValueCurrency

`func (o *OutboundShipmentsCreate) SetDeclaredValueCurrency(v DeclaredValueCurrency)`

SetDeclaredValueCurrency sets DeclaredValueCurrency field to given value.

### HasDeclaredValueCurrency

`func (o *OutboundShipmentsCreate) HasDeclaredValueCurrency() bool`

HasDeclaredValueCurrency returns a boolean if a field has been set.

### GetRequirePickup

`func (o *OutboundShipmentsCreate) GetRequirePickup() bool`

GetRequirePickup returns the RequirePickup field if non-nil, zero value otherwise.

### GetRequirePickupOk

`func (o *OutboundShipmentsCreate) GetRequirePickupOk() (*bool, bool)`

GetRequirePickupOk returns a tuple with the RequirePickup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirePickup

`func (o *OutboundShipmentsCreate) SetRequirePickup(v bool)`

SetRequirePickup sets RequirePickup field to given value.

### HasRequirePickup

`func (o *OutboundShipmentsCreate) HasRequirePickup() bool`

HasRequirePickup returns a boolean if a field has been set.

### GetInsureShipment

`func (o *OutboundShipmentsCreate) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *OutboundShipmentsCreate) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *OutboundShipmentsCreate) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *OutboundShipmentsCreate) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetShipmentLabelRequired

`func (o *OutboundShipmentsCreate) GetShipmentLabelRequired() bool`

GetShipmentLabelRequired returns the ShipmentLabelRequired field if non-nil, zero value otherwise.

### GetShipmentLabelRequiredOk

`func (o *OutboundShipmentsCreate) GetShipmentLabelRequiredOk() (*bool, bool)`

GetShipmentLabelRequiredOk returns a tuple with the ShipmentLabelRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentLabelRequired

`func (o *OutboundShipmentsCreate) SetShipmentLabelRequired(v bool)`

SetShipmentLabelRequired sets ShipmentLabelRequired field to given value.

### HasShipmentLabelRequired

`func (o *OutboundShipmentsCreate) HasShipmentLabelRequired() bool`

HasShipmentLabelRequired returns a boolean if a field has been set.

### GetShipmentAttachmentId

`func (o *OutboundShipmentsCreate) GetShipmentAttachmentId() string`

GetShipmentAttachmentId returns the ShipmentAttachmentId field if non-nil, zero value otherwise.

### GetShipmentAttachmentIdOk

`func (o *OutboundShipmentsCreate) GetShipmentAttachmentIdOk() (*string, bool)`

GetShipmentAttachmentIdOk returns a tuple with the ShipmentAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAttachmentId

`func (o *OutboundShipmentsCreate) SetShipmentAttachmentId(v string)`

SetShipmentAttachmentId sets ShipmentAttachmentId field to given value.

### HasShipmentAttachmentId

`func (o *OutboundShipmentsCreate) HasShipmentAttachmentId() bool`

HasShipmentAttachmentId returns a boolean if a field has been set.

### GetShipmentAddress

`func (o *OutboundShipmentsCreate) GetShipmentAddress() ShipmentAddress`

GetShipmentAddress returns the ShipmentAddress field if non-nil, zero value otherwise.

### GetShipmentAddressOk

`func (o *OutboundShipmentsCreate) GetShipmentAddressOk() (*ShipmentAddress, bool)`

GetShipmentAddressOk returns a tuple with the ShipmentAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAddress

`func (o *OutboundShipmentsCreate) SetShipmentAddress(v ShipmentAddress)`

SetShipmentAddress sets ShipmentAddress field to given value.

### HasShipmentAddress

`func (o *OutboundShipmentsCreate) HasShipmentAddress() bool`

HasShipmentAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


