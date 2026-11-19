# OutboundServiceDetailShipmentDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OutboundType** | [**OutboundServiceDetailShipmentDetailsOutboundType**](OutboundServiceDetailShipmentDetailsOutboundType.md) |  | 
**CarrierName** | Pointer to [**OutboundServiceDetailShipmentDetailsCarrierName**](OutboundServiceDetailShipmentDetailsCarrierName.md) |  | [optional] 
**TrackingNumber** | Pointer to **string** |  | [optional] 
**NoOfBoxes** | Pointer to **int32** |  | [optional] 
**DeclaredValue** | Pointer to **string** |  | [optional] 
**LabelExists** | Pointer to **bool** |  | [optional] 
**ShipToAddress** | Pointer to [**OutboundServiceDetailShipmentDetailsShipToAddress**](OutboundServiceDetailShipmentDetailsShipToAddress.md) |  | [optional] 
**OtherCarrierName** | Pointer to **string** |  | [optional] 
**UploadedLabel** | Pointer to [**Attachment**](Attachment.md) |  | [optional] 
**InsureShipment** | Pointer to **bool** |  | [optional] 
**PickUpFromCageSuite** | Pointer to **bool** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 

## Methods

### NewOutboundServiceDetailShipmentDetails

`func NewOutboundServiceDetailShipmentDetails(outboundType OutboundServiceDetailShipmentDetailsOutboundType, ) *OutboundServiceDetailShipmentDetails`

NewOutboundServiceDetailShipmentDetails instantiates a new OutboundServiceDetailShipmentDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOutboundServiceDetailShipmentDetailsWithDefaults

`func NewOutboundServiceDetailShipmentDetailsWithDefaults() *OutboundServiceDetailShipmentDetails`

NewOutboundServiceDetailShipmentDetailsWithDefaults instantiates a new OutboundServiceDetailShipmentDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutboundType

`func (o *OutboundServiceDetailShipmentDetails) GetOutboundType() OutboundServiceDetailShipmentDetailsOutboundType`

GetOutboundType returns the OutboundType field if non-nil, zero value otherwise.

### GetOutboundTypeOk

`func (o *OutboundServiceDetailShipmentDetails) GetOutboundTypeOk() (*OutboundServiceDetailShipmentDetailsOutboundType, bool)`

GetOutboundTypeOk returns a tuple with the OutboundType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutboundType

`func (o *OutboundServiceDetailShipmentDetails) SetOutboundType(v OutboundServiceDetailShipmentDetailsOutboundType)`

SetOutboundType sets OutboundType field to given value.


### GetCarrierName

`func (o *OutboundServiceDetailShipmentDetails) GetCarrierName() OutboundServiceDetailShipmentDetailsCarrierName`

GetCarrierName returns the CarrierName field if non-nil, zero value otherwise.

### GetCarrierNameOk

`func (o *OutboundServiceDetailShipmentDetails) GetCarrierNameOk() (*OutboundServiceDetailShipmentDetailsCarrierName, bool)`

GetCarrierNameOk returns a tuple with the CarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierName

`func (o *OutboundServiceDetailShipmentDetails) SetCarrierName(v OutboundServiceDetailShipmentDetailsCarrierName)`

SetCarrierName sets CarrierName field to given value.

### HasCarrierName

`func (o *OutboundServiceDetailShipmentDetails) HasCarrierName() bool`

HasCarrierName returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *OutboundServiceDetailShipmentDetails) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *OutboundServiceDetailShipmentDetails) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *OutboundServiceDetailShipmentDetails) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *OutboundServiceDetailShipmentDetails) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetNoOfBoxes

`func (o *OutboundServiceDetailShipmentDetails) GetNoOfBoxes() int32`

GetNoOfBoxes returns the NoOfBoxes field if non-nil, zero value otherwise.

### GetNoOfBoxesOk

`func (o *OutboundServiceDetailShipmentDetails) GetNoOfBoxesOk() (*int32, bool)`

GetNoOfBoxesOk returns a tuple with the NoOfBoxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoOfBoxes

`func (o *OutboundServiceDetailShipmentDetails) SetNoOfBoxes(v int32)`

SetNoOfBoxes sets NoOfBoxes field to given value.

### HasNoOfBoxes

`func (o *OutboundServiceDetailShipmentDetails) HasNoOfBoxes() bool`

HasNoOfBoxes returns a boolean if a field has been set.

### GetDeclaredValue

`func (o *OutboundServiceDetailShipmentDetails) GetDeclaredValue() string`

GetDeclaredValue returns the DeclaredValue field if non-nil, zero value otherwise.

### GetDeclaredValueOk

`func (o *OutboundServiceDetailShipmentDetails) GetDeclaredValueOk() (*string, bool)`

GetDeclaredValueOk returns a tuple with the DeclaredValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclaredValue

`func (o *OutboundServiceDetailShipmentDetails) SetDeclaredValue(v string)`

SetDeclaredValue sets DeclaredValue field to given value.

### HasDeclaredValue

`func (o *OutboundServiceDetailShipmentDetails) HasDeclaredValue() bool`

HasDeclaredValue returns a boolean if a field has been set.

### GetLabelExists

`func (o *OutboundServiceDetailShipmentDetails) GetLabelExists() bool`

GetLabelExists returns the LabelExists field if non-nil, zero value otherwise.

### GetLabelExistsOk

`func (o *OutboundServiceDetailShipmentDetails) GetLabelExistsOk() (*bool, bool)`

GetLabelExistsOk returns a tuple with the LabelExists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelExists

`func (o *OutboundServiceDetailShipmentDetails) SetLabelExists(v bool)`

SetLabelExists sets LabelExists field to given value.

### HasLabelExists

`func (o *OutboundServiceDetailShipmentDetails) HasLabelExists() bool`

HasLabelExists returns a boolean if a field has been set.

### GetShipToAddress

`func (o *OutboundServiceDetailShipmentDetails) GetShipToAddress() OutboundServiceDetailShipmentDetailsShipToAddress`

GetShipToAddress returns the ShipToAddress field if non-nil, zero value otherwise.

### GetShipToAddressOk

`func (o *OutboundServiceDetailShipmentDetails) GetShipToAddressOk() (*OutboundServiceDetailShipmentDetailsShipToAddress, bool)`

GetShipToAddressOk returns a tuple with the ShipToAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToAddress

`func (o *OutboundServiceDetailShipmentDetails) SetShipToAddress(v OutboundServiceDetailShipmentDetailsShipToAddress)`

SetShipToAddress sets ShipToAddress field to given value.

### HasShipToAddress

`func (o *OutboundServiceDetailShipmentDetails) HasShipToAddress() bool`

HasShipToAddress returns a boolean if a field has been set.

### GetOtherCarrierName

`func (o *OutboundServiceDetailShipmentDetails) GetOtherCarrierName() string`

GetOtherCarrierName returns the OtherCarrierName field if non-nil, zero value otherwise.

### GetOtherCarrierNameOk

`func (o *OutboundServiceDetailShipmentDetails) GetOtherCarrierNameOk() (*string, bool)`

GetOtherCarrierNameOk returns a tuple with the OtherCarrierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherCarrierName

`func (o *OutboundServiceDetailShipmentDetails) SetOtherCarrierName(v string)`

SetOtherCarrierName sets OtherCarrierName field to given value.

### HasOtherCarrierName

`func (o *OutboundServiceDetailShipmentDetails) HasOtherCarrierName() bool`

HasOtherCarrierName returns a boolean if a field has been set.

### GetUploadedLabel

`func (o *OutboundServiceDetailShipmentDetails) GetUploadedLabel() Attachment`

GetUploadedLabel returns the UploadedLabel field if non-nil, zero value otherwise.

### GetUploadedLabelOk

`func (o *OutboundServiceDetailShipmentDetails) GetUploadedLabelOk() (*Attachment, bool)`

GetUploadedLabelOk returns a tuple with the UploadedLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadedLabel

`func (o *OutboundServiceDetailShipmentDetails) SetUploadedLabel(v Attachment)`

SetUploadedLabel sets UploadedLabel field to given value.

### HasUploadedLabel

`func (o *OutboundServiceDetailShipmentDetails) HasUploadedLabel() bool`

HasUploadedLabel returns a boolean if a field has been set.

### GetInsureShipment

`func (o *OutboundServiceDetailShipmentDetails) GetInsureShipment() bool`

GetInsureShipment returns the InsureShipment field if non-nil, zero value otherwise.

### GetInsureShipmentOk

`func (o *OutboundServiceDetailShipmentDetails) GetInsureShipmentOk() (*bool, bool)`

GetInsureShipmentOk returns a tuple with the InsureShipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInsureShipment

`func (o *OutboundServiceDetailShipmentDetails) SetInsureShipment(v bool)`

SetInsureShipment sets InsureShipment field to given value.

### HasInsureShipment

`func (o *OutboundServiceDetailShipmentDetails) HasInsureShipment() bool`

HasInsureShipment returns a boolean if a field has been set.

### GetPickUpFromCageSuite

`func (o *OutboundServiceDetailShipmentDetails) GetPickUpFromCageSuite() bool`

GetPickUpFromCageSuite returns the PickUpFromCageSuite field if non-nil, zero value otherwise.

### GetPickUpFromCageSuiteOk

`func (o *OutboundServiceDetailShipmentDetails) GetPickUpFromCageSuiteOk() (*bool, bool)`

GetPickUpFromCageSuiteOk returns a tuple with the PickUpFromCageSuite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickUpFromCageSuite

`func (o *OutboundServiceDetailShipmentDetails) SetPickUpFromCageSuite(v bool)`

SetPickUpFromCageSuite sets PickUpFromCageSuite field to given value.

### HasPickUpFromCageSuite

`func (o *OutboundServiceDetailShipmentDetails) HasPickUpFromCageSuite() bool`

HasPickUpFromCageSuite returns a boolean if a field has been set.

### GetDescription

`func (o *OutboundServiceDetailShipmentDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OutboundServiceDetailShipmentDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OutboundServiceDetailShipmentDetails) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OutboundServiceDetailShipmentDetails) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


