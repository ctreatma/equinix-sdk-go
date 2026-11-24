# PatchPanelPort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CircuitId** | Pointer to **string** | Optional, customer-defined Cross Connect instance identifier. | [optional] 
**ConnectorType** | **string** | Patch panel connector type. | 
**PatchPanel** | [**PatchPanel**](PatchPanel.md) |  | 
**PortA** | **int32** | Port A | 
**PortB** | Pointer to **int32** | Port B | [optional] 

## Methods

### NewPatchPanelPort

`func NewPatchPanelPort(connectorType string, patchPanel PatchPanel, portA int32, ) *PatchPanelPort`

NewPatchPanelPort instantiates a new PatchPanelPort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchPanelPortWithDefaults

`func NewPatchPanelPortWithDefaults() *PatchPanelPort`

NewPatchPanelPortWithDefaults instantiates a new PatchPanelPort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCircuitId

`func (o *PatchPanelPort) GetCircuitId() string`

GetCircuitId returns the CircuitId field if non-nil, zero value otherwise.

### GetCircuitIdOk

`func (o *PatchPanelPort) GetCircuitIdOk() (*string, bool)`

GetCircuitIdOk returns a tuple with the CircuitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitId

`func (o *PatchPanelPort) SetCircuitId(v string)`

SetCircuitId sets CircuitId field to given value.

### HasCircuitId

`func (o *PatchPanelPort) HasCircuitId() bool`

HasCircuitId returns a boolean if a field has been set.

### GetConnectorType

`func (o *PatchPanelPort) GetConnectorType() string`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *PatchPanelPort) GetConnectorTypeOk() (*string, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *PatchPanelPort) SetConnectorType(v string)`

SetConnectorType sets ConnectorType field to given value.


### GetPatchPanel

`func (o *PatchPanelPort) GetPatchPanel() PatchPanel`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *PatchPanelPort) GetPatchPanelOk() (*PatchPanel, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *PatchPanelPort) SetPatchPanel(v PatchPanel)`

SetPatchPanel sets PatchPanel field to given value.


### GetPortA

`func (o *PatchPanelPort) GetPortA() int32`

GetPortA returns the PortA field if non-nil, zero value otherwise.

### GetPortAOk

`func (o *PatchPanelPort) GetPortAOk() (*int32, bool)`

GetPortAOk returns a tuple with the PortA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortA

`func (o *PatchPanelPort) SetPortA(v int32)`

SetPortA sets PortA field to given value.


### GetPortB

`func (o *PatchPanelPort) GetPortB() int32`

GetPortB returns the PortB field if non-nil, zero value otherwise.

### GetPortBOk

`func (o *PatchPanelPort) GetPortBOk() (*int32, bool)`

GetPortBOk returns a tuple with the PortB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortB

`func (o *PatchPanelPort) SetPortB(v int32)`

SetPortB sets PortB field to given value.

### HasPortB

`func (o *PatchPanelPort) HasPortB() bool`

HasPortB returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


