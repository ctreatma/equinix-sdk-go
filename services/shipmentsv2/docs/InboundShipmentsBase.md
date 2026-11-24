# InboundShipmentsBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60; | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be received. | [optional] 

## Methods

### NewInboundShipmentsBase

`func NewInboundShipmentsBase() *InboundShipmentsBase`

NewInboundShipmentsBase instantiates a new InboundShipmentsBase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundShipmentsBaseWithDefaults

`func NewInboundShipmentsBaseWithDefaults() *InboundShipmentsBase`

NewInboundShipmentsBaseWithDefaults instantiates a new InboundShipmentsBase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierName

`func (o *InboundShipmentsBase) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *InboundShipmentsBase) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *InboundShipmentsBase) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *InboundShipmentsBase) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *InboundShipmentsBase) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *InboundShipmentsBase) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *InboundShipmentsBase) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *InboundShipmentsBase) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


