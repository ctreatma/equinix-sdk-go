# OutboundShipmentsBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierTrackingNumbers** | Pointer to **[]string** | Shipment tracking number. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 
**CarrierName** | Pointer to **string** | This field should be used to specify carrier name when &#x60;carrier&#x60; is of &#x60;OTHER&#x60;. | [optional] 
**NumberOfBoxes** | Pointer to **float32** | Number of boxes to be sent. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60;  | [optional] 
**DeclaredValue** | Pointer to **float32** | Declared value of outbound shipment in dollars. This field is optional when carrier is of &#x60;CUSTOMER_CARRIER&#x60; | [optional] 

## Methods

### NewOutboundShipmentsBase

`func NewOutboundShipmentsBase() *OutboundShipmentsBase`

NewOutboundShipmentsBase instantiates a new OutboundShipmentsBase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundShipmentsBaseWithDefaults

`func NewOutboundShipmentsBaseWithDefaults() *OutboundShipmentsBase`

NewOutboundShipmentsBaseWithDefaults instantiates a new OutboundShipmentsBase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierTrackingNumbers

`func (o *OutboundShipmentsBase) GetCarrierTrackingNumbers() []string`

GetCarrierTrackingNumbers returns the CarrierTrackingNumbers field if non-nil, zero value otherwise.

### GetCarrierTrackingNumbersOk

`func (o *OutboundShipmentsBase) GetCarrierTrackingNumbersOk() (*[]string, bool)`

GetCarrierTrackingNumbersOk returns a tuple with the CarrierTrackingNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierTrackingNumbers

`func (o *OutboundShipmentsBase) SetCarrierTrackingNumbers(v []string)`

SetCarrierTrackingNumbers sets CarrierTrackingNumbers field to given value.

### HasCarrierTrackingNumbers

`func (o *OutboundShipmentsBase) HasCarrierTrackingNumbers() bool`

HasCarrierTrackingNumbers returns a boolean if a field has been set.

### GetCarrierName

`func (o *OutboundShipmentsBase) GetCarrierName() string`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *OutboundShipmentsBase) GetCarrierNameOk() (*string, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *OutboundShipmentsBase) SetCarrierName(v string)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *OutboundShipmentsBase) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetNumberOfBoxes

`func (o *OutboundShipmentsBase) GetNumberOfBoxes() float32`

GetNumberOfBoxes returns the NumberOfBoxes field if non-nil, zero value otherwise.

### GetNumberOfBoxesOk

`func (o *OutboundShipmentsBase) GetNumberOfBoxesOk() (*float32, bool)`

GetNumberOfBoxesOk returns a tuple with the NumberOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumberOfBoxes

`func (o *OutboundShipmentsBase) SetNumberOfBoxes(v float32)`

SetNumberOfBoxes sets NumberOfBoxes field to given value.

### HasNumberOfBoxes

`func (o *OutboundShipmentsBase) HasNumberOfBoxes() bool`

HasNumberOfBoxes returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *OutboundShipmentsBase) GetDeclaredValue() float32`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *OutboundShipmentsBase) GetDeclaredValueOk() (*float32, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *OutboundShipmentsBase) SetDeclaredValue(v float32)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *OutboundShipmentsBase) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


