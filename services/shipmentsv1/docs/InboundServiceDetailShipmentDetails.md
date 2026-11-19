# InboundServiceDetailShipmentDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NoOfBoxes** | **int32** | No of boxes | 
**IsOverSized** | Pointer to **bool** | if Box is oversized | [optional] 
**Description** | Pointer to **string** | description of inbound shipment | [optional] 
**TrackingNumber** | Pointer to **[]string** | Tracking number | [optional] 
**InboundType** | [**InboundServiceDetailShipmentDetailsInboundType**](InboundServiceDetailShipmentDetailsInboundType.md) |  | 
**CarrierName** | Pointer to [**InboundServiceDetailShipmentDetailsCarrierName**](InboundServiceDetailShipmentDetailsCarrierName.md) |  | [optional] 
**OtherCarrierName** | Pointer to **string** | Other Carrier Name | [optional] 

## Methods

### NewInboundServiceDetailShipmentDetails

`func NewInboundServiceDetailShipmentDetails(noOfBoxes int32, inboundType InboundServiceDetailShipmentDetailsInboundType, ) *InboundServiceDetailShipmentDetails`

NewInboundServiceDetailShipmentDetails instantiates a new InboundServiceDetailShipmentDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundServiceDetailShipmentDetailsWithDefaults

`func NewInboundServiceDetailShipmentDetailsWithDefaults() *InboundServiceDetailShipmentDetails`

NewInboundServiceDetailShipmentDetailsWithDefaults instantiates a new InboundServiceDetailShipmentDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNoOfBoxes

`func (o *InboundServiceDetailShipmentDetails) GetNoOfBoxes() int32`

GetNoOfBoxes returns the NoOfBoxes field if non-nil, zero value otherwise.

### GetNoOfBoxesOk

`func (o *InboundServiceDetailShipmentDetails) GetNoOfBoxesOk() (*int32, bool)`

GetNoOfBoxesOk returns a tuple with the NoOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoOfBoxes

`func (o *InboundServiceDetailShipmentDetails) SetNoOfBoxes(v int32)`

SetNoOfBoxes sets NoOfBoxes field to given value.


### GetIsOverSized

`func (o *InboundServiceDetailShipmentDetails) GetIsOverSized() bool`

GetIsOverSized returns the IsOverSized field if non-nil, zero value otherwise.

### GetIsOverSizedOk

`func (o *InboundServiceDetailShipmentDetails) GetIsOverSizedOk() (*bool, bool)`

GetIsOverSizedOk returns a tuple with the IsOverSized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOverSized

`func (o *InboundServiceDetailShipmentDetails) SetIsOverSized(v bool)`

SetIsOverSized sets IsOverSized field to given value.

### HasIsOverSized

`func (o *InboundServiceDetailShipmentDetails) HasIsOverSized() bool`

HasIsOverSized returns a boolean if a field has been set.

### GetDescription

`func (o *InboundServiceDetailShipmentDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InboundServiceDetailShipmentDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InboundServiceDetailShipmentDetails) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *InboundServiceDetailShipmentDetails) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *InboundServiceDetailShipmentDetails) GetTrackingNumber() []string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *InboundServiceDetailShipmentDetails) GetTrackingNumberOk() (*[]string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *InboundServiceDetailShipmentDetails) SetTrackingNumber(v []string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *InboundServiceDetailShipmentDetails) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetInboundType

`func (o *InboundServiceDetailShipmentDetails) GetInboundType() InboundServiceDetailShipmentDetailsInboundType`

GetInboundType returns the InboundType field if non-nil, zero value otherwise.

### GetInboundTypeOk

`func (o *InboundServiceDetailShipmentDetails) GetInboundTypeOk() (*InboundServiceDetailShipmentDetailsInboundType, bool)`

GetInboundTypeOk returns a tuple with the InboundType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundType

`func (o *InboundServiceDetailShipmentDetails) SetInboundType(v InboundServiceDetailShipmentDetailsInboundType)`

SetInboundType sets InboundType field to given value.


### GetCarrierName

`func (o *InboundServiceDetailShipmentDetails) GetCarrierName() InboundServiceDetailShipmentDetailsCarrierName`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *InboundServiceDetailShipmentDetails) GetCarrierNameOk() (*InboundServiceDetailShipmentDetailsCarrierName, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *InboundServiceDetailShipmentDetails) SetCarrierName(v InboundServiceDetailShipmentDetailsCarrierName)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *InboundServiceDetailShipmentDetails) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetOtherCarrierName

`func (o *InboundServiceDetailShipmentDetails) GetOtherCarrierName() string`

GetOtherCarrierName returns the OtherCarrierName field if non-nil, zero value otherwise.

### GetOtherCarrierNameOk

`func (o *InboundServiceDetailShipmentDetails) GetOtherCarrierNameOk() (*string, bool)`

GetOtherCarrierNameOk returns a tuple with the OtherCarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherCarrierName

`func (o *InboundServiceDetailShipmentDetails) SetOtherCarrierName(v string)`

SetOtherCarrierName sets OtherCarrierName field to given value.

### HasOtherCarrierName

`func (o *InboundServiceDetailShipmentDetails) HasOtherCarrierName() bool`

HasOtherCarrierName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


