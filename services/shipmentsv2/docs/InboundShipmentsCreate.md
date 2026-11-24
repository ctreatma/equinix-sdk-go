# InboundShipmentsCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Carrier** | [**InboundShipmentsAllOfCarrier**](InboundShipmentsAllOfCarrier.md) |  | 
**CarrierTrackingNumbers** | **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60; | [optional] 
**NumberOfBoxes** | **float32** | Number of boxes to be received. | 
**CageDelivery** | Pointer to **bool** | When set to &#x60;true&#x60;, shipment will be delivered to cage. | [optional] [default to false]

## Methods

### NewInboundShipmentsCreate

`func NewInboundShipmentsCreate(carrier InboundShipmentsAllOfCarrier, carrierTrackingNumbers []string, numberOfBoxes float32, ) *InboundShipmentsCreate`

NewInboundShipmentsCreate instantiates a new InboundShipmentsCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundShipmentsCreateWithDefaults

`func NewInboundShipmentsCreateWithDefaults() *InboundShipmentsCreate`

NewInboundShipmentsCreateWithDefaults instantiates a new InboundShipmentsCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrier

`func (o *InboundShipmentsCreate) GetCarrier() InboundShipmentsAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *InboundShipmentsCreate) GetCarrierOk() (*InboundShipmentsAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *InboundShipmentsCreate) SetCarrier(v InboundShipmentsAllOfCarrier)`

SetCarrier sets Carrier field to given value.


### GetCarrierTrackingNumbers

`func (o *InboundShipmentsCreate) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *InboundShipmentsCreate) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *InboundShipmentsCreate) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.


### GetCarrierName

`func (o *InboundShipmentsCreate) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *InboundShipmentsCreate) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *InboundShipmentsCreate) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *InboundShipmentsCreate) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *InboundShipmentsCreate) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *InboundShipmentsCreate) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *InboundShipmentsCreate) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.


### GetCageDelivery

`func (o *InboundShipmentsCreate) GetCageDelivery() bool`

GetCageDelivery returns the CageDelivery field if non-nil, zero value otherwise.

### GetCageDeliveryOk

`func (o *InboundShipmentsCreate) GetCageDeliveryOk() (*bool, bool)`

GetCageDeliveryOk returns a tuple with the CageDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageDelivery

`func (o *InboundShipmentsCreate) SetCageDelivery(v bool)`

SetCageDelivery sets CageDelivery field to given value.

### HasCageDelivery

`func (o *InboundShipmentsCreate) HasCageDelivery() bool`

HasCageDelivery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


