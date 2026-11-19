# ASide

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PatchPanel** | [**PatchPanel**](PatchPanel.md) |  | 
**ConnectionService** | [**ConnectionServices**](ConnectionServices.md) |  | 
**MediaType** | [**MediaTypes**](MediaTypes.md) |  | 
**ProtocolType** | [**ProtocolTypes**](ProtocolTypes.md) |  | 
**ConnectorType** | [**ConnectorTypes**](ConnectorTypes.md) |  | 
**MediaConverterRequired** | Pointer to **bool** | When &#x60;false&#x60;, Equinix will not proceed with cross connect installation that requires media conversion | [optional] 
**IfcCircuitCount** | Pointer to **int32** | Use this field to request an intra-facility cable IFC with this order. Note that there might be a delay in fulfilment of Cross Connect as it is pending intra facility cabling | [optional] 
**PatchEquipment** | Pointer to [**PatchEquipment**](PatchEquipment.md) |  | [optional] 

## Methods

### NewASide

`func NewASide(patchPanel PatchPanel, connectionService ConnectionServices, mediaType MediaTypes, protocolType ProtocolTypes, connectorType ConnectorTypes, ) *ASide`

NewASide instantiates a new ASide object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewASideWithDefaults

`func NewASideWithDefaults() *ASide`

NewASideWithDefaults instantiates a new ASide object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPatchPanel

`func (o *ASide) GetPatchPanel() PatchPanel`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *ASide) GetPatchPanelOk() (*PatchPanel, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *ASide) SetPatchPanel(v PatchPanel)`

SetPatchPanel sets PatchPanel field to given value.


### GetConnectionService

`func (o *ASide) GetConnectionService() ConnectionServices`

GetConnectionService returns the ConnectionService field if non-nil, zero value otherwise.

### GetConnectionServiceOk

`func (o *ASide) GetConnectionServiceOk() (*ConnectionServices, bool)`

GetConnectionServiceOk returns a tuple with the ConnectionService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionService

`func (o *ASide) SetConnectionService(v ConnectionServices)`

SetConnectionService sets ConnectionService field to given value.


### GetMediaType

`func (o *ASide) GetMediaType() MediaTypes`

GetMediaType returns the MediaType field if non-nil, zero value otherwise.

### GetMediaTypeOk

`func (o *ASide) GetMediaTypeOk() (*MediaTypes, bool)`

GetMediaTypeOk returns a tuple with the MediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaType

`func (o *ASide) SetMediaType(v MediaTypes)`

SetMediaType sets MediaType field to given value.


### GetProtocolType

`func (o *ASide) GetProtocolType() ProtocolTypes`

GetProtocolType returns the ProtocolType field if non-nil, zero value otherwise.

### GetProtocolTypeOk

`func (o *ASide) GetProtocolTypeOk() (*ProtocolTypes, bool)`

GetProtocolTypeOk returns a tuple with the ProtocolType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocolType

`func (o *ASide) SetProtocolType(v ProtocolTypes)`

SetProtocolType sets ProtocolType field to given value.


### GetConnectorType

`func (o *ASide) GetConnectorType() ConnectorTypes`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *ASide) GetConnectorTypeOk() (*ConnectorTypes, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *ASide) SetConnectorType(v ConnectorTypes)`

SetConnectorType sets ConnectorType field to given value.


### GetMediaConverterRequired

`func (o *ASide) GetMediaConverterRequired() bool`

GetMediaConverterRequired returns the MediaConverterRequired field if non-nil, zero value otherwise.

### GetMediaConverterRequiredOk

`func (o *ASide) GetMediaConverterRequiredOk() (*bool, bool)`

GetMediaConverterRequiredOk returns a tuple with the MediaConverterRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaConverterRequired

`func (o *ASide) SetMediaConverterRequired(v bool)`

SetMediaConverterRequired sets MediaConverterRequired field to given value.

### HasMediaConverterRequired

`func (o *ASide) HasMediaConverterRequired() bool`

HasMediaConverterRequired returns a boolean if a field has been set.

### GetIfcCircuitCount

`func (o *ASide) GetIfcCircuitCount() int32`

GetIfcCircuitCount returns the IfcCircuitCount field if non-nil, zero value otherwise.

### GetIfcCircuitCountOk

`func (o *ASide) GetIfcCircuitCountOk() (*int32, bool)`

GetIfcCircuitCountOk returns a tuple with the IfcCircuitCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIfcCircuitCount

`func (o *ASide) SetIfcCircuitCount(v int32)`

SetIfcCircuitCount sets IfcCircuitCount field to given value.

### HasIfcCircuitCount

`func (o *ASide) HasIfcCircuitCount() bool`

HasIfcCircuitCount returns a boolean if a field has been set.

### GetPatchEquipment

`func (o *ASide) GetPatchEquipment() PatchEquipment`

GetPatchEquipment returns the PatchEquipment field if non-nil, zero value otherwise.

### GetPatchEquipmentOk

`func (o *ASide) GetPatchEquipmentOk() (*PatchEquipment, bool)`

GetPatchEquipmentOk returns a tuple with the PatchEquipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchEquipment

`func (o *ASide) SetPatchEquipment(v PatchEquipment)`

SetPatchEquipment sets PatchEquipment field to given value.

### HasPatchEquipment

`func (o *ASide) HasPatchEquipment() bool`

HasPatchEquipment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


