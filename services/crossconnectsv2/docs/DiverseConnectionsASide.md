# DiverseConnectionsASide

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PatchPanel** | Pointer to [**PatchPanel**](PatchPanel.md) |  | [optional] 
**ConnectorType** | Pointer to [**ConnectorTypes**](ConnectorTypes.md) |  | [optional] 
**MediaConverterRequired** | Pointer to **bool** | ASide media Converter Required | [optional] [default to false]
**IfcCircuitCount** | Pointer to **int32** | Use this field to request an intra-facility cable IFC with this order. Note that there might be a delay in fulfilment of Cross Connect as it is pending intra facility cabling | [optional] 
**PatchEquipment** | Pointer to [**PatchEquipment**](PatchEquipment.md) |  | [optional] 

## Methods

### NewDiverseConnectionsASide

`func NewDiverseConnectionsASide() *DiverseConnectionsASide`

NewDiverseConnectionsASide instantiates a new DiverseConnectionsASide object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiverseConnectionsASideWithDefaults

`func NewDiverseConnectionsASideWithDefaults() *DiverseConnectionsASide`

NewDiverseConnectionsASideWithDefaults instantiates a new DiverseConnectionsASide object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPatchPanel

`func (o *DiverseConnectionsASide) GetPatchPanel() PatchPanel`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *DiverseConnectionsASide) GetPatchPanelOk() (*PatchPanel, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *DiverseConnectionsASide) SetPatchPanel(v PatchPanel)`

SetPatchPanel sets PatchPanel field to given value.

### HasPatchPanel

`func (o *DiverseConnectionsASide) HasPatchPanel() bool`

HasPatchPanel returns a boolean if a field has been set.

### GetConnectorType

`func (o *DiverseConnectionsASide) GetConnectorType() ConnectorTypes`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *DiverseConnectionsASide) GetConnectorTypeOk() (*ConnectorTypes, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *DiverseConnectionsASide) SetConnectorType(v ConnectorTypes)`

SetConnectorType sets ConnectorType field to given value.

### HasConnectorType

`func (o *DiverseConnectionsASide) HasConnectorType() bool`

HasConnectorType returns a boolean if a field has been set.

### GetMediaConverterRequired

`func (o *DiverseConnectionsASide) GetMediaConverterRequired() bool`

GetMediaConverterRequired returns the MediaConverterRequired field if non-nil, zero value otherwise.

### GetMediaConverterRequiredOk

`func (o *DiverseConnectionsASide) GetMediaConverterRequiredOk() (*bool, bool)`

GetMediaConverterRequiredOk returns a tuple with the MediaConverterRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaConverterRequired

`func (o *DiverseConnectionsASide) SetMediaConverterRequired(v bool)`

SetMediaConverterRequired sets MediaConverterRequired field to given value.

### HasMediaConverterRequired

`func (o *DiverseConnectionsASide) HasMediaConverterRequired() bool`

HasMediaConverterRequired returns a boolean if a field has been set.

### GetIfcCircuitCount

`func (o *DiverseConnectionsASide) GetIfcCircuitCount() int32`

GetIfcCircuitCount returns the IfcCircuitCount field if non-nil, zero value otherwise.

### GetIfcCircuitCountOk

`func (o *DiverseConnectionsASide) GetIfcCircuitCountOk() (*int32, bool)`

GetIfcCircuitCountOk returns a tuple with the IfcCircuitCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIfcCircuitCount

`func (o *DiverseConnectionsASide) SetIfcCircuitCount(v int32)`

SetIfcCircuitCount sets IfcCircuitCount field to given value.

### HasIfcCircuitCount

`func (o *DiverseConnectionsASide) HasIfcCircuitCount() bool`

HasIfcCircuitCount returns a boolean if a field has been set.

### GetPatchEquipment

`func (o *DiverseConnectionsASide) GetPatchEquipment() PatchEquipment`

GetPatchEquipment returns the PatchEquipment field if non-nil, zero value otherwise.

### GetPatchEquipmentOk

`func (o *DiverseConnectionsASide) GetPatchEquipmentOk() (*PatchEquipment, bool)`

GetPatchEquipmentOk returns a tuple with the PatchEquipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchEquipment

`func (o *DiverseConnectionsASide) SetPatchEquipment(v PatchEquipment)`

SetPatchEquipment sets PatchEquipment field to given value.

### HasPatchEquipment

`func (o *DiverseConnectionsASide) HasPatchEquipment() bool`

HasPatchEquipment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


