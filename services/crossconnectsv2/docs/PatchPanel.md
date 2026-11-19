# PatchPanel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Patch Panel ID | 
**PortA** | Pointer to **float32** | Specify the desired port number for port A. When ports are not selected, next available ports will be used | [optional] 
**PortB** | Pointer to **float32** | Specify the desired port number for port B. When ports are not selected, next available ports will be used. If no selection is required, use value of &#x60;-1&#x60; | [optional] 

## Methods

### NewPatchPanel

`func NewPatchPanel(id string, ) *PatchPanel`

NewPatchPanel instantiates a new PatchPanel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchPanelWithDefaults

`func NewPatchPanelWithDefaults() *PatchPanel`

NewPatchPanelWithDefaults instantiates a new PatchPanel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PatchPanel) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PatchPanel) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PatchPanel) SetId(v string)`

SetId sets Id field to given value.


### GetPortA

`func (o *PatchPanel) GetPortA() float32`

GetPortA returns the PortA field if non-nil, zero value otherwise.

### GetPortAOk

`func (o *PatchPanel) GetPortAOk() (*float32, bool)`

GetPortAOk returns a tuple with the PortA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortA

`func (o *PatchPanel) SetPortA(v float32)`

SetPortA sets PortA field to given value.

### HasPortA

`func (o *PatchPanel) HasPortA() bool`

HasPortA returns a boolean if a field has been set.

### GetPortB

`func (o *PatchPanel) GetPortB() float32`

GetPortB returns the PortB field if non-nil, zero value otherwise.

### GetPortBOk

`func (o *PatchPanel) GetPortBOk() (*float32, bool)`

GetPortBOk returns a tuple with the PortB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortB

`func (o *PatchPanel) SetPortB(v float32)`

SetPortB sets PortB field to given value.

### HasPortB

`func (o *PatchPanel) HasPortB() bool`

HasPortB returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


