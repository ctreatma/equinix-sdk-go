# OutboundServiceDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OutboundRequestDescription** | Pointer to **string** |  | [optional] 
**EstimatedDateTime** | **time.Time** | Date and time of received event (ISO Date)&lt;br&gt; Cannot in Past.  | 
**ShipmentDetails** | [**OutboundServiceDetailShipmentDetails**](OutboundServiceDetailShipmentDetails.md) |  | 

## Methods

### NewOutboundServiceDetail

`func NewOutboundServiceDetail(estimatedDateTime time.Time, shipmentDetails OutboundServiceDetailShipmentDetails, ) *OutboundServiceDetail`

NewOutboundServiceDetail instantiates a new OutboundServiceDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundServiceDetailWithDefaults

`func NewOutboundServiceDetailWithDefaults() *OutboundServiceDetail`

NewOutboundServiceDetailWithDefaults instantiates a new OutboundServiceDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutboundRequestDescription

`func (o *OutboundServiceDetail) GetOutboundRequestDescription() string`

GetOutboundRequestDescription returns the OutboundRequestDescription field if non-nil, zero value otherwise.

### GetOutboundRequestDescriptionOk

`func (o *OutboundServiceDetail) GetOutboundRequestDescriptionOk() (*string, bool)`

GetOutboundRequestDescriptionOk returns a tuple with the OutboundRequestDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundRequestDescription

`func (o *OutboundServiceDetail) SetOutboundRequestDescription(v string)`

SetOutboundRequestDescription sets OutboundRequestDescription field to given value.

### HasOutboundRequestDescription

`func (o *OutboundServiceDetail) HasOutboundRequestDescription() bool`

HasOutboundRequestDescription returns a boolean if a field has been set.

### GetEstimatedDateTime

`func (o *OutboundServiceDetail) GetEstimatedDateTime() time.Time`

GetEstimatedDateTime returns the EstimatedDateTime field if non-nil, zero value otherwise.

### GetEstimatedDateTimeOk

`func (o *OutboundServiceDetail) GetEstimatedDateTimeOk() (*time.Time, bool)`

GetEstimatedDateTimeOk returns a tuple with the EstimatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDateTime

`func (o *OutboundServiceDetail) SetEstimatedDateTime(v time.Time)`

SetEstimatedDateTime sets EstimatedDateTime field to given value.


### GetShipmentDetails

`func (o *OutboundServiceDetail) GetShipmentDetails() OutboundServiceDetailShipmentDetails`

GetShipmentDetails returns the ShipmentDetails field if non-nil, zero value otherwise.

### GetShipmentDetailsOk

`func (o *OutboundServiceDetail) GetShipmentDetailsOk() (*OutboundServiceDetailShipmentDetails, bool)`

GetShipmentDetailsOk returns a tuple with the ShipmentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentDetails

`func (o *OutboundServiceDetail) SetShipmentDetails(v OutboundServiceDetailShipmentDetails)`

SetShipmentDetails sets ShipmentDetails field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


