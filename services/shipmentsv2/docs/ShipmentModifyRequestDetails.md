# ShipmentModifyRequestDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | Pointer to [**InboundShipmentsUpdateAllOfCarrier**](InboundShipmentsUpdateAllOfCarrier.md) |  | [optional] 
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. | [optional] 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be sent.  | [optional] 
**CageDelivery** | Pointer to **bool** | When set to &#x60;true&#x60;, shipment will be delivered to cage. | [optional] 
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars.  | [optional] 
**DeclaredValueCurrency** | Pointer to [**DeclaredValueCurrency**](DeclaredValueCurrency.md) |  | [optional] 
**RequirePickup** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will pick up shipment from your cage. Note that this will incur additional Smarthands fees based on contract rate. | [optional] 
**InsureShipment** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will insure outbound shipment .Note that this will incur additional Smarthands fees based on contract rate. | [optional] 
**ShipmentAttachmentId** | Pointer to **string** | Attachment ID of uploaded shipment label. Refer to Attachment API on how to upload documents via API | [optional] 
**ShipmentAddress** | Pointer to [**ShipmentAddress**](ShipmentAddress.md) |  | [optional] 

## Methods

### NewShipmentModifyRequestDetails

`func NewShipmentModifyRequestDetails() *ShipmentModifyRequestDetails`

NewShipmentModifyRequestDetails instantiates a new ShipmentModifyRequestDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentModifyRequestDetailsWithDefaults

`func NewShipmentModifyRequestDetailsWithDefaults() *ShipmentModifyRequestDetails`

NewShipmentModifyRequestDetailsWithDefaults instantiates a new ShipmentModifyRequestDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *ShipmentModifyRequestDetails) GetCarrier() InboundShipmentsUpdateAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShipmentModifyRequestDetails) GetCarrierOk() (*InboundShipmentsUpdateAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShipmentModifyRequestDetails) SetCarrier(v InboundShipmentsUpdateAllOfCarrier)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *ShipmentModifyRequestDetails) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCarrierTrackingNumbers

`func (o *ShipmentModifyRequestDetails) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *ShipmentModifyRequestDetails) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *ShipmentModifyRequestDetails) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *ShipmentModifyRequestDetails) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCarrierName

`func (o *ShipmentModifyRequestDetails) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *ShipmentModifyRequestDetails) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *ShipmentModifyRequestDetails) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *ShipmentModifyRequestDetails) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *ShipmentModifyRequestDetails) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *ShipmentModifyRequestDetails) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *ShipmentModifyRequestDetails) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *ShipmentModifyRequestDetails) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetCageDelivery

`func (o *ShipmentModifyRequestDetails) GetCageDelivery() bool`

GetCageDelivery returns the CageDelivery field if non-nil, zero value otherwise.

### GetCageDeliveryOk

`func (o *ShipmentModifyRequestDetails) GetCageDeliveryOk() (*bool, bool)`

GetCageDeliveryOk returns a tuple with the CageDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageDelivery

`func (o *ShipmentModifyRequestDetails) SetCageDelivery(v bool)`

SetCageDelivery sets CageDelivery field to given value.

### HasCageDelivery

`func (o *ShipmentModifyRequestDetails) HasCageDelivery() bool`

HasCageDelivery returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *ShipmentModifyRequestDetails) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *ShipmentModifyRequestDetails) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *ShipmentModifyRequestDetails) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *ShipmentModifyRequestDetails) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetDeclaredValueCurrency

`func (o *ShipmentModifyRequestDetails) GetDeclaredValueCurrency() DeclaredValueCurrency`

GetDeclaredValueCurrency returns the DeclaredValueCurrency field if non-nil, zero value otherwise.

### GetDeclaredValueCurrencyOk

`func (o *ShipmentModifyRequestDetails) GetDeclaredValueCurrencyOk() (*DeclaredValueCurrency, bool)`

GetDeclaredValueCurrencyOk returns a tuple with the DeclaredValueCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValueCurrency

`func (o *ShipmentModifyRequestDetails) SetDeclaredValueCurrency(v DeclaredValueCurrency)`

SetDeclaredValueCurrency sets DeclaredValueCurrency field to given value.

### HasDeclaredValueCurrency

`func (o *ShipmentModifyRequestDetails) HasDeclaredValueCurrency() bool`

HasDeclaredValueCurrency returns a boolean if a field has been set.

### GetRequirePickup

`func (o *ShipmentModifyRequestDetails) GetRequirePickup() bool`

GetRequirePickup returns the RequirePickup field if non-nil, zero value otherwise.

### GetRequirePickupOk

`func (o *ShipmentModifyRequestDetails) GetRequirePickupOk() (*bool, bool)`

GetRequirePickupOk returns a tuple with the RequirePickup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirePickup

`func (o *ShipmentModifyRequestDetails) SetRequirePickup(v bool)`

SetRequirePickup sets RequirePickup field to given value.

### HasRequirePickup

`func (o *ShipmentModifyRequestDetails) HasRequirePickup() bool`

HasRequirePickup returns a boolean if a field has been set.

### GetInsureShipment

`func (o *ShipmentModifyRequestDetails) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *ShipmentModifyRequestDetails) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *ShipmentModifyRequestDetails) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *ShipmentModifyRequestDetails) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetShipmentAttachmentId

`func (o *ShipmentModifyRequestDetails) GetShipmentAttachmentId() string`

GetShipmentAttachmentId returns the ShipmentAttachmentId field if non-nil, zero value otherwise.

### GetShipmentAttachmentIdOk

`func (o *ShipmentModifyRequestDetails) GetShipmentAttachmentIdOk() (*string, bool)`

GetShipmentAttachmentIdOk returns a tuple with the ShipmentAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAttachmentId

`func (o *ShipmentModifyRequestDetails) SetShipmentAttachmentId(v string)`

SetShipmentAttachmentId sets ShipmentAttachmentId field to given value.

### HasShipmentAttachmentId

`func (o *ShipmentModifyRequestDetails) HasShipmentAttachmentId() bool`

HasShipmentAttachmentId returns a boolean if a field has been set.

### GetShipmentAddress

`func (o *ShipmentModifyRequestDetails) GetShipmentAddress() ShipmentAddress`

GetShipmentAddress returns the ShipmentAddress field if non-nil, zero value otherwise.

### GetShipmentAddressOk

`func (o *ShipmentModifyRequestDetails) GetShipmentAddressOk() (*ShipmentAddress, bool)`

GetShipmentAddressOk returns a tuple with the ShipmentAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAddress

`func (o *ShipmentModifyRequestDetails) SetShipmentAddress(v ShipmentAddress)`

SetShipmentAddress sets ShipmentAddress field to given value.

### HasShipmentAddress

`func (o *ShipmentModifyRequestDetails) HasShipmentAddress() bool`

HasShipmentAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


