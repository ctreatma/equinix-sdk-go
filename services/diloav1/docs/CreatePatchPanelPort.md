# CreatePatchPanelPort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectorType** | **string** | Patch panel connector type. | 
**CircuitId** | Pointer to **string** | Optional, customer-defined Cross Connect instance identifier. | [optional] 
**PatchPanelId** | **string** | Patch panel identifier. | 
**PortA** | **int32** | Port A | 
**PortB** | Pointer to **int32** | Port B | [optional] 

## Methods

### NewCreatePatchPanelPort

`func NewCreatePatchPanelPort(connectorType string, patchPanelId string, portA int32, ) *CreatePatchPanelPort`

NewCreatePatchPanelPort instantiates a new CreatePatchPanelPort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePatchPanelPortWithDefaults

`func NewCreatePatchPanelPortWithDefaults() *CreatePatchPanelPort`

NewCreatePatchPanelPortWithDefaults instantiates a new CreatePatchPanelPort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectorType

`func (o *CreatePatchPanelPort) GetConnectorType() string`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *CreatePatchPanelPort) GetConnectorTypeOk() (*string, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *CreatePatchPanelPort) SetConnectorType(v string)`

SetConnectorType sets ConnectorType field to given value.


### GetCircuitId

`func (o *CreatePatchPanelPort) GetCircuitId() string`

GetCircuitId returns the CircuitId field if non-nil, zero value otherwise.

### GetCircuitIdOk

`func (o *CreatePatchPanelPort) GetCircuitIdOk() (*string, bool)`

GetCircuitIdOk returns a tuple with the CircuitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitId

`func (o *CreatePatchPanelPort) SetCircuitId(v string)`

SetCircuitId sets CircuitId field to given value.

### HasCircuitId

`func (o *CreatePatchPanelPort) HasCircuitId() bool`

HasCircuitId returns a boolean if a field has been set.

### GetPatchPanelId

`func (o *CreatePatchPanelPort) GetPatchPanelId() string`

GetPatchPanelId returns the PatchPanelId field if non-nil, zero value otherwise.

### GetPatchPanelIdOk

`func (o *CreatePatchPanelPort) GetPatchPanelIdOk() (*string, bool)`

GetPatchPanelIdOk returns a tuple with the PatchPanelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanelId

`func (o *CreatePatchPanelPort) SetPatchPanelId(v string)`

SetPatchPanelId sets PatchPanelId field to given value.


### GetPortA

`func (o *CreatePatchPanelPort) GetPortA() int32`

GetPortA returns the PortA field if non-nil, zero value otherwise.

### GetPortAOk

`func (o *CreatePatchPanelPort) GetPortAOk() (*int32, bool)`

GetPortAOk returns a tuple with the PortA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortA

`func (o *CreatePatchPanelPort) SetPortA(v int32)`

SetPortA sets PortA field to given value.


### GetPortB

`func (o *CreatePatchPanelPort) GetPortB() int32`

GetPortB returns the PortB field if non-nil, zero value otherwise.

### GetPortBOk

`func (o *CreatePatchPanelPort) GetPortBOk() (*int32, bool)`

GetPortBOk returns a tuple with the PortB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortB

`func (o *CreatePatchPanelPort) SetPortB(v int32)`

SetPortB sets PortB field to given value.

### HasPortB

`func (o *CreatePatchPanelPort) HasPortB() bool`

HasPortB returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


