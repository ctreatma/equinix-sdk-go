# InboundShipments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60; | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be received. | [optional] 
**Carrier** | Pointer to [**InboundShipmentsAllOfCarrier**](InboundShipmentsAllOfCarrier.md) |  | [optional] 
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**CageDelivery** | Pointer to **bool** | When set to &#x60;true&#x60;, shipment will be delivered to cage. | [optional] [default to false]

## Methods

### NewInboundShipments

`func NewInboundShipments() *InboundShipments`

NewInboundShipments instantiates a new InboundShipments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundShipmentsWithDefaults

`func NewInboundShipmentsWithDefaults() *InboundShipments`

NewInboundShipmentsWithDefaults instantiates a new InboundShipments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierName

`func (o *InboundShipments) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *InboundShipments) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *InboundShipments) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *InboundShipments) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *InboundShipments) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *InboundShipments) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *InboundShipments) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *InboundShipments) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetCarrier

`func (o *InboundShipments) GetCarrier() InboundShipmentsAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *InboundShipments) GetCarrierOk() (*InboundShipmentsAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *InboundShipments) SetCarrier(v InboundShipmentsAllOfCarrier)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *InboundShipments) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCarrierTrackingNumbers

`func (o *InboundShipments) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *InboundShipments) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *InboundShipments) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *InboundShipments) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCageDelivery

`func (o *InboundShipments) GetCageDelivery() bool`

GetCageDelivery returns the CageDelivery field if non-nil, zero value otherwise.

### GetCageDeliveryOk

`func (o *InboundShipments) GetCageDeliveryOk() (*bool, bool)`

GetCageDeliveryOk returns a tuple with the CageDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageDelivery

`func (o *InboundShipments) SetCageDelivery(v bool)`

SetCageDelivery sets CageDelivery field to given value.

### HasCageDelivery

`func (o *InboundShipments) HasCageDelivery() bool`

HasCageDelivery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


