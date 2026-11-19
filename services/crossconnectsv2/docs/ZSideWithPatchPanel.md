# ZSideWithPatchPanel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectorType** | [**ConnectorTypes**](ConnectorTypes.md) |  | 
**PatchPanel** | [**PatchPanel**](PatchPanel.md) |  | 
**CircuitId** | Pointer to **string** | Customer or carrier circuit ID cable reference number for verification purposes. | [optional] 

## Methods

### NewZSideWithPatchPanel

`func NewZSideWithPatchPanel(connectorType ConnectorTypes, patchPanel PatchPanel, ) *ZSideWithPatchPanel`

NewZSideWithPatchPanel instantiates a new ZSideWithPatchPanel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewZSideWithPatchPanelWithDefaults

`func NewZSideWithPatchPanelWithDefaults() *ZSideWithPatchPanel`

NewZSideWithPatchPanelWithDefaults instantiates a new ZSideWithPatchPanel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectorType

`func (o *ZSideWithPatchPanel) GetConnectorType() ConnectorTypes`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *ZSideWithPatchPanel) GetConnectorTypeOk() (*ConnectorTypes, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *ZSideWithPatchPanel) SetConnectorType(v ConnectorTypes)`

SetConnectorType sets ConnectorType field to given value.


### GetPatchPanel

`func (o *ZSideWithPatchPanel) GetPatchPanel() PatchPanel`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *ZSideWithPatchPanel) GetPatchPanelOk() (*PatchPanel, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *ZSideWithPatchPanel) SetPatchPanel(v PatchPanel)`

SetPatchPanel sets PatchPanel field to given value.


### GetCircuitId

`func (o *ZSideWithPatchPanel) GetCircuitId() string`

GetCircuitId returns the CircuitId field if non-nil, zero value otherwise.

### GetCircuitIdOk

`func (o *ZSideWithPatchPanel) GetCircuitIdOk() (*string, bool)`

GetCircuitIdOk returns a tuple with the CircuitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitId

`func (o *ZSideWithPatchPanel) SetCircuitId(v string)`

SetCircuitId sets CircuitId field to given value.

### HasCircuitId

`func (o *ZSideWithPatchPanel) HasCircuitId() bool`

HasCircuitId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


