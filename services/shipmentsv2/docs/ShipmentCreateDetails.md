# ShipmentCreateDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | [**InboundShipmentsAllOfCarrier**](InboundShipmentsAllOfCarrier.md) |  | 
**CarrierTrackingNumbers** | **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | **float32** | Number of boxes to be sent. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60;  | 
**CageDelivery** | Pointer to **bool** | When set to &#x60;true&#x60;, shipment will be delivered to cage. | [optional] [default to false]
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**DeclaredValueCurrency** | Pointer to [**DeclaredValueCurrency**](DeclaredValueCurrency.md) |  | [optional] 
**RequirePickup** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will pick up shipment from your cage. Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**InsureShipment** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will insure outbound shipment .Note that this will incur additional Smarthands fees based on contract rate. | [optional] [default to false]
**ShipmentLabelRequired** | Pointer to **bool** | When set to &#x60;true&#x60;, Equinix will print shipment label for your package. Address information for shipment label can be uploaded as an label attachment or as address fields. | [optional] [default to true]
**ShipmentAttachmentId** | Pointer to **string** | Attachment ID of uploaded shipment label. Refer to Attachment API on how to upload documents via API | [optional] 
**ShipmentAddress** | Pointer to [**ShipmentAddress**](ShipmentAddress.md) |  | [optional] 

## Methods

### NewShipmentCreateDetails

`func NewShipmentCreateDetails(carrier InboundShipmentsAllOfCarrier, carrierTrackingNumbers []string, numberOfBoxes float32, ) *ShipmentCreateDetails`

NewShipmentCreateDetails instantiates a new ShipmentCreateDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentCreateDetailsWithDefaults

`func NewShipmentCreateDetailsWithDefaults() *ShipmentCreateDetails`

NewShipmentCreateDetailsWithDefaults instantiates a new ShipmentCreateDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *ShipmentCreateDetails) GetCarrier() InboundShipmentsAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *ShipmentCreateDetails) GetCarrierOk() (*InboundShipmentsAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *ShipmentCreateDetails) SetCarrier(v InboundShipmentsAllOfCarrier)`

SetCarrier sets Carrier field to given value.


### GetCarrierTrackingNumbers

`func (o *ShipmentCreateDetails) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *ShipmentCreateDetails) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *ShipmentCreateDetails) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.


### GetCarrierName

`func (o *ShipmentCreateDetails) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *ShipmentCreateDetails) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *ShipmentCreateDetails) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *ShipmentCreateDetails) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *ShipmentCreateDetails) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *ShipmentCreateDetails) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *ShipmentCreateDetails) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.


### GetCageDelivery

`func (o *ShipmentCreateDetails) GetCageDelivery() bool`

GetCageDelivery returns the CageDelivery field if non-nil, zero value otherwise.

### GetCageDeliveryOk

`func (o *ShipmentCreateDetails) GetCageDeliveryOk() (*bool, bool)`

GetCageDeliveryOk returns a tuple with the CageDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageDelivery

`func (o *ShipmentCreateDetails) SetCageDelivery(v bool)`

SetCageDelivery sets CageDelivery field to given value.

### HasCageDelivery

`func (o *ShipmentCreateDetails) HasCageDelivery() bool`

HasCageDelivery returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *ShipmentCreateDetails) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *ShipmentCreateDetails) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *ShipmentCreateDetails) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *ShipmentCreateDetails) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetDeclaredValueCurrency

`func (o *ShipmentCreateDetails) GetDeclaredValueCurrency() DeclaredValueCurrency`

GetDeclaredValueCurrency returns the DeclaredValueCurrency field if non-nil, zero value otherwise.

### GetDeclaredValueCurrencyOk

`func (o *ShipmentCreateDetails) GetDeclaredValueCurrencyOk() (*DeclaredValueCurrency, bool)`

GetDeclaredValueCurrencyOk returns a tuple with the DeclaredValueCurrency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValueCurrency

`func (o *ShipmentCreateDetails) SetDeclaredValueCurrency(v DeclaredValueCurrency)`

SetDeclaredValueCurrency sets DeclaredValueCurrency field to given value.

### HasDeclaredValueCurrency

`func (o *ShipmentCreateDetails) HasDeclaredValueCurrency() bool`

HasDeclaredValueCurrency returns a boolean if a field has been set.

### GetRequirePickup

`func (o *ShipmentCreateDetails) GetRequirePickup() bool`

GetRequirePickup returns the RequirePickup field if non-nil, zero value otherwise.

### GetRequirePickupOk

`func (o *ShipmentCreateDetails) GetRequirePickupOk() (*bool, bool)`

GetRequirePickupOk returns a tuple with the RequirePickup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirePickup

`func (o *ShipmentCreateDetails) SetRequirePickup(v bool)`

SetRequirePickup sets RequirePickup field to given value.

### HasRequirePickup

`func (o *ShipmentCreateDetails) HasRequirePickup() bool`

HasRequirePickup returns a boolean if a field has been set.

### GetInsureShipment

`func (o *ShipmentCreateDetails) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *ShipmentCreateDetails) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *ShipmentCreateDetails) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *ShipmentCreateDetails) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetShipmentLabelRequired

`func (o *ShipmentCreateDetails) GetShipmentLabelRequired() bool`

GetShipmentLabelRequired returns the ShipmentLabelRequired field if non-nil, zero value otherwise.

### GetShipmentLabelRequiredOk

`func (o *ShipmentCreateDetails) GetShipmentLabelRequiredOk() (*bool, bool)`

GetShipmentLabelRequiredOk returns a tuple with the ShipmentLabelRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentLabelRequired

`func (o *ShipmentCreateDetails) SetShipmentLabelRequired(v bool)`

SetShipmentLabelRequired sets ShipmentLabelRequired field to given value.

### HasShipmentLabelRequired

`func (o *ShipmentCreateDetails) HasShipmentLabelRequired() bool`

HasShipmentLabelRequired returns a boolean if a field has been set.

### GetShipmentAttachmentId

`func (o *ShipmentCreateDetails) GetShipmentAttachmentId() string`

GetShipmentAttachmentId returns the ShipmentAttachmentId field if non-nil, zero value otherwise.

### GetShipmentAttachmentIdOk

`func (o *ShipmentCreateDetails) GetShipmentAttachmentIdOk() (*string, bool)`

GetShipmentAttachmentIdOk returns a tuple with the ShipmentAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAttachmentId

`func (o *ShipmentCreateDetails) SetShipmentAttachmentId(v string)`

SetShipmentAttachmentId sets ShipmentAttachmentId field to given value.

### HasShipmentAttachmentId

`func (o *ShipmentCreateDetails) HasShipmentAttachmentId() bool`

HasShipmentAttachmentId returns a boolean if a field has been set.

### GetShipmentAddress

`func (o *ShipmentCreateDetails) GetShipmentAddress() ShipmentAddress`

GetShipmentAddress returns the ShipmentAddress field if non-nil, zero value otherwise.

### GetShipmentAddressOk

`func (o *ShipmentCreateDetails) GetShipmentAddressOk() (*ShipmentAddress, bool)`

GetShipmentAddressOk returns a tuple with the ShipmentAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentAddress

`func (o *ShipmentCreateDetails) SetShipmentAddress(v ShipmentAddress)`

SetShipmentAddress sets ShipmentAddress field to given value.

### HasShipmentAddress

`func (o *ShipmentCreateDetails) HasShipmentAddress() bool`

HasShipmentAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


