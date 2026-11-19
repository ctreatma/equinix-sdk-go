# OutboundShipments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be sent. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60;  | [optional] 
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**Carrier** | Pointer to [**InboundShipmentsAllOfCarrier**](InboundShipmentsAllOfCarrier.md) |  | [optional] 
**DeclaredValueCurrency** | Pointer to [**DeclaredValueCurrency**](DeclaredValueCurrency.md) |  | [optional] 
**RequirePickup** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will pick up shipment from your cage. Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**InsureShipment** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will insure outbound shipment .Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**ShipmentLabelRequired** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will print shipment label for your package. Address information for shipment label can be uploaded as an label attachment or as address fields. | [optional] [default to true]
**ShipmentAttachmentId** | Pointer to **string** | Attachment ID of uploaded shipment label. Refer to Attachment API on how to upload documents via API | [optional] 
**ShipmentAddress** | Pointer to [**ShipmentAddress**](ShipmentAddress.md) |  | [optional] 

## Methods

### NewOutboundShipments

`func NewOutboundShipments() *OutboundShipments`

NewOutboundShipments instantiates a new OutboundShipments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundShipmentsWithDefaults

`func NewOutboundShipmentsWithDefaults() *OutboundShipments`

NewOutboundShipmentsWithDefaults instantiates a new OutboundShipments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierTrackingNumbers

`func (o *OutboundShipments) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *OutboundShipments) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *OutboundShipments) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *OutboundShipments) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCarrierName

`func (o *OutboundShipments) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *OutboundShipments) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *OutboundShipments) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *OutboundShipments) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *OutboundShipments) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *OutboundShipments) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *OutboundShipments) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *OutboundShipments) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *OutboundShipments) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *OutboundShipments) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *OutboundShipments) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *OutboundShipments) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetCarrier

`func (o *OutboundShipments) GetCarrier() InboundShipmentsAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *OutboundShipments) GetCarrierOk() (*InboundShipmentsAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *OutboundShipments) SetCarrier(v InboundShipmentsAllOfCarrier)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *OutboundShipments) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetDeclaredValueCurrency

`func (o *OutboundShipments) GetDeclaredValueCurrency() DeclaredValueCurrency`

GetDeclaredValueCurrency returns the DeclaredValueCurrency field if non-nil, zero value otherwise.

### GetDeclaredValueCurrencyOk

`func (o *OutboundShipments) GetDeclaredValueCurrencyOk() (*DeclaredValueCurrency, bool)`

GetDeclaredValueCurrencyOk returns a tuple with the DeclaredValueCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValueCurrency

`func (o *OutboundShipments) SetDeclaredValueCurrency(v DeclaredValueCurrency)`

SetDeclaredValueCurrency sets DeclaredValueCurrency field to given value.

### HasDeclaredValueCurrency

`func (o *OutboundShipments) HasDeclaredValueCurrency() bool`

HasDeclaredValueCurrency returns a boolean if a field has been set.

### GetRequirePickup

`func (o *OutboundShipments) GetRequirePickup() bool`

GetRequirePickup returns the RequirePickup field if non-nil, zero value otherwise.

### GetRequirePickupOk

`func (o *OutboundShipments) GetRequirePickupOk() (*bool, bool)`

GetRequirePickupOk returns a tuple with the RequirePickup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirePickup

`func (o *OutboundShipments) SetRequirePickup(v bool)`

SetRequirePickup sets RequirePickup field to given value.

### HasRequirePickup

`func (o *OutboundShipments) HasRequirePickup() bool`

HasRequirePickup returns a boolean if a field has been set.

### GetInsureShipment

`func (o *OutboundShipments) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *OutboundShipments) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *OutboundShipments) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *OutboundShipments) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetShipmentLabelRequired

`func (o *OutboundShipments) GetShipmentLabelRequired() bool`

GetShipmentLabelRequired returns the ShipmentLabelRequired field if non-nil, zero value otherwise.

### GetShipmentLabelRequiredOk

`func (o *OutboundShipments) GetShipmentLabelRequiredOk() (*bool, bool)`

GetShipmentLabelRequiredOk returns a tuple with the ShipmentLabelRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentLabelRequired

`func (o *OutboundShipments) SetShipmentLabelRequired(v bool)`

SetShipmentLabelRequired sets ShipmentLabelRequired field to given value.

### HasShipmentLabelRequired

`func (o *OutboundShipments) HasShipmentLabelRequired() bool`

HasShipmentLabelRequired returns a boolean if a field has been set.

### GetShipmentAttachmentId

`func (o *OutboundShipments) GetShipmentAttachmentId() string`

GetShipmentAttachmentId returns the ShipmentAttachmentId field if non-nil, zero value otherwise.

### GetShipmentAttachmentIdOk

`func (o *OutboundShipments) GetShipmentAttachmentIdOk() (*string, bool)`

GetShipmentAttachmentIdOk returns a tuple with the ShipmentAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAttachmentId

`func (o *OutboundShipments) SetShipmentAttachmentId(v string)`

SetShipmentAttachmentId sets ShipmentAttachmentId field to given value.

### HasShipmentAttachmentId

`func (o *OutboundShipments) HasShipmentAttachmentId() bool`

HasShipmentAttachmentId returns a boolean if a field has been set.

### GetShipmentAddress

`func (o *OutboundShipments) GetShipmentAddress() ShipmentAddress`

GetShipmentAddress returns the ShipmentAddress field if non-nil, zero value otherwise.

### GetShipmentAddressOk

`func (o *OutboundShipments) GetShipmentAddressOk() (*ShipmentAddress, bool)`

GetShipmentAddressOk returns a tuple with the ShipmentAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAddress

`func (o *OutboundShipments) SetShipmentAddress(v ShipmentAddress)`

SetShipmentAddress sets ShipmentAddress field to given value.

### HasShipmentAddress

`func (o *OutboundShipments) HasShipmentAddress() bool`

HasShipmentAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


