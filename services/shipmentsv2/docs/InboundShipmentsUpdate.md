# InboundShipmentsUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60; | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be received. | [optional] 
**Carrier** | Pointer to [**InboundShipmentsUpdateAllOfCarrier**](InboundShipmentsUpdateAllOfCarrier.md) |  | [optional] 
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. | [optional] 
**CageDelivery** | Pointer to **bool** | When set to &#x60;true&#x60;, shipment will be delivered to cage. | [optional] 

## Methods

### NewInboundShipmentsUpdate

`func NewInboundShipmentsUpdate() *InboundShipmentsUpdate`

NewInboundShipmentsUpdate instantiates a new InboundShipmentsUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundShipmentsUpdateWithDefaults

`func NewInboundShipmentsUpdateWithDefaults() *InboundShipmentsUpdate`

NewInboundShipmentsUpdateWithDefaults instantiates a new InboundShipmentsUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierName

`func (o *InboundShipmentsUpdate) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *InboundShipmentsUpdate) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *InboundShipmentsUpdate) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *InboundShipmentsUpdate) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *InboundShipmentsUpdate) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *InboundShipmentsUpdate) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *InboundShipmentsUpdate) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *InboundShipmentsUpdate) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetCarrier

`func (o *InboundShipmentsUpdate) GetCarrier() InboundShipmentsUpdateAllOfCarrier`

GetCarrier returns the Carrier field if non-nil, zero value otherwise.

### GetCarrierOk

`func (o *InboundShipmentsUpdate) GetCarrierOk() (*InboundShipmentsUpdateAllOfCarrier, bool)`

GetCarrierOk returns a tuple with the Carrier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrier

`func (o *InboundShipmentsUpdate) SetCarrier(v InboundShipmentsUpdateAllOfCarrier)`

SetCarrier sets Carrier field to given value.

### HasCarrier

`func (o *InboundShipmentsUpdate) HasCarrier() bool`

HasCarrier returns a boolean if a field has been set.

### GetCarrierTrackingNumbers

`func (o *InboundShipmentsUpdate) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *InboundShipmentsUpdate) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *InboundShipmentsUpdate) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *InboundShipmentsUpdate) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCageDelivery

`func (o *InboundShipmentsUpdate) GetCageDelivery() bool`

GetCageDelivery returns the CageDelivery field if non-nil, zero value otherwise.

### GetCageDeliveryOk

`func (o *InboundShipmentsUpdate) GetCageDeliveryOk() (*bool, bool)`

GetCageDeliveryOk returns a tuple with the CageDelivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageDelivery

`func (o *InboundShipmentsUpdate) SetCageDelivery(v bool)`

SetCageDelivery sets CageDelivery field to given value.

### HasCageDelivery

`func (o *InboundShipmentsUpdate) HasCageDelivery() bool`

HasCageDelivery returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


