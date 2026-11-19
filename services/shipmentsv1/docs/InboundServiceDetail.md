# InboundServiceDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShipmentDetails** | [**InboundServiceDetailShipmentDetails**](InboundServiceDetailShipmentDetails.md) |  | 
**DeliverToCage** | Pointer to **bool** | Deliver To cage | [optional] 
**InboundRequestDescription** | Pointer to **string** | Scope of work | [optional] 
**StorageId** | Pointer to **string** | Storage ID | [optional] 
**EstimatedDateTime** | **time.Time** | estimatedDateTime of Shipment (ISO Date)&lt;br&gt; Cannot in Past.  | 

## Methods

### NewInboundServiceDetail

`func NewInboundServiceDetail(shipmentDetails InboundServiceDetailShipmentDetails, estimatedDateTime time.Time, ) *InboundServiceDetail`

NewInboundServiceDetail instantiates a new InboundServiceDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboundServiceDetailWithDefaults

`func NewInboundServiceDetailWithDefaults() *InboundServiceDetail`

NewInboundServiceDetailWithDefaults instantiates a new InboundServiceDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShipmentDetails

`func (o *InboundServiceDetail) GetShipmentDetails() InboundServiceDetailShipmentDetails`

GetShipmentDetails returns the ShipmentDetails field if non-nil, zero value otherwise.

### GetShipmentDetailsOk

`func (o *InboundServiceDetail) GetShipmentDetailsOk() (*InboundServiceDetailShipmentDetails, bool)`

GetShipmentDetailsOk returns a tuple with the ShipmentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentDetails

`func (o *InboundServiceDetail) SetShipmentDetails(v InboundServiceDetailShipmentDetails)`

SetShipmentDetails sets ShipmentDetails field to given value.


### GetDeliverToCage

`func (o *InboundServiceDetail) GetDeliverToCage() bool`

GetDeliverToCage returns the DeliverToCage field if non-nil, zero value otherwise.

### GetDeliverToCageOk

`func (o *InboundServiceDetail) GetDeliverToCageOk() (*bool, bool)`

GetDeliverToCageOk returns a tuple with the DeliverToCage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverToCage

`func (o *InboundServiceDetail) SetDeliverToCage(v bool)`

SetDeliverToCage sets DeliverToCage field to given value.

### HasDeliverToCage

`func (o *InboundServiceDetail) HasDeliverToCage() bool`

HasDeliverToCage returns a boolean if a field has been set.

### GetInboundRequestDescription

`func (o *InboundServiceDetail) GetInboundRequestDescription() string`

GetInboundRequestDescription returns the InboundRequestDescription field if non-nil, zero value otherwise.

### GetInboundRequestDescriptionOk

`func (o *InboundServiceDetail) GetInboundRequestDescriptionOk() (*string, bool)`

GetInboundRequestDescriptionOk returns a tuple with the InboundRequestDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboundRequestDescription

`func (o *InboundServiceDetail) SetInboundRequestDescription(v string)`

SetInboundRequestDescription sets InboundRequestDescription field to given value.

### HasInboundRequestDescription

`func (o *InboundServiceDetail) HasInboundRequestDescription() bool`

HasInboundRequestDescription returns a boolean if a field has been set.

### GetStorageId

`func (o *InboundServiceDetail) GetStorageId() string`

GetStorageId returns the StorageId field if non-nil, zero value otherwise.

### GetStorageIdOk

`func (o *InboundServiceDetail) GetStorageIdOk() (*string, bool)`

GetStorageIdOk returns a tuple with the StorageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageId

`func (o *InboundServiceDetail) SetStorageId(v string)`

SetStorageId sets StorageId field to given value.

### HasStorageId

`func (o *InboundServiceDetail) HasStorageId() bool`

HasStorageId returns a boolean if a field has been set.

### GetEstimatedDateTime

`func (o *InboundServiceDetail) GetEstimatedDateTime() time.Time`

GetEstimatedDateTime returns the EstimatedDateTime field if non-nil, zero value otherwise.

### GetEstimatedDateTimeOk

`func (o *InboundServiceDetail) GetEstimatedDateTimeOk() (*time.Time, bool)`

GetEstimatedDateTimeOk returns a tuple with the EstimatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedDateTime

`func (o *InboundServiceDetail) SetEstimatedDateTime(v time.Time)`

SetEstimatedDateTime sets EstimatedDateTime field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


