# DemarcationPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionService** | **string** | Connection Service  | 
**MediaType** | **string** | Media Type   | 
**ConnectorType** | **string** | Type of the connector  | 
**CrossConnectId** | Pointer to **string** |  | [optional] 
**CageSpaceId** | **string** |  | 
**CabinetSpaceId** | **string** |  | 
**PatchPanel** | **string** | Port patch panel | 
**PatchPanelPortA** | **int32** | Port patch panel port A | 
**PatchPanelPortB** | Pointer to **int32** | Port patch panel port B | [optional] 

## Methods

### NewDemarcationPoint

`func NewDemarcationPoint(connectionService string, mediaType string, connectorType string, cageSpaceId string, cabinetSpaceId string, patchPanel string, patchPanelPortA int32, ) *DemarcationPoint`

NewDemarcationPoint instantiates a new DemarcationPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDemarcationPointWithDefaults

`func NewDemarcationPointWithDefaults() *DemarcationPoint`

NewDemarcationPointWithDefaults instantiates a new DemarcationPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionService

`func (o *DemarcationPoint) GetConnectionService() string`

GetConnectionService returns the ConnectionService field if non-nil, zero value otherwise.

### GetConnectionServiceOk

`func (o *DemarcationPoint) GetConnectionServiceOk() (*string, bool)`

GetConnectionServiceOk returns a tuple with the ConnectionService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionService

`func (o *DemarcationPoint) SetConnectionService(v string)`

SetConnectionService sets ConnectionService field to given value.


### GetMediaType

`func (o *DemarcationPoint) GetMediaType() string`

GetMediaType returns the MediaType field if non-nil, zero value otherwise.

### GetMediaTypeOk

`func (o *DemarcationPoint) GetMediaTypeOk() (*string, bool)`

GetMediaTypeOk returns a tuple with the MediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaType

`func (o *DemarcationPoint) SetMediaType(v string)`

SetMediaType sets MediaType field to given value.


### GetConnectorType

`func (o *DemarcationPoint) GetConnectorType() string`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *DemarcationPoint) GetConnectorTypeOk() (*string, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *DemarcationPoint) SetConnectorType(v string)`

SetConnectorType sets ConnectorType field to given value.


### GetCrossConnectId

`func (o *DemarcationPoint) GetCrossConnectId() string`

GetCrossConnectId returns the CrossConnectId field if non-nil, zero value otherwise.

### GetCrossConnectIdOk

`func (o *DemarcationPoint) GetCrossConnectIdOk() (*string, bool)`

GetCrossConnectIdOk returns a tuple with the CrossConnectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrossConnectId

`func (o *DemarcationPoint) SetCrossConnectId(v string)`

SetCrossConnectId sets CrossConnectId field to given value.

### HasCrossConnectId

`func (o *DemarcationPoint) HasCrossConnectId() bool`

HasCrossConnectId returns a boolean if a field has been set.

### GetCageSpaceId

`func (o *DemarcationPoint) GetCageSpaceId() string`

GetCageSpaceId returns the CageSpaceId field if non-nil, zero value otherwise.

### GetCageSpaceIdOk

`func (o *DemarcationPoint) GetCageSpaceIdOk() (*string, bool)`

GetCageSpaceIdOk returns a tuple with the CageSpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageSpaceId

`func (o *DemarcationPoint) SetCageSpaceId(v string)`

SetCageSpaceId sets CageSpaceId field to given value.


### GetCabinetSpaceId

`func (o *DemarcationPoint) GetCabinetSpaceId() string`

GetCabinetSpaceId returns the CabinetSpaceId field if non-nil, zero value otherwise.

### GetCabinetSpaceIdOk

`func (o *DemarcationPoint) GetCabinetSpaceIdOk() (*string, bool)`

GetCabinetSpaceIdOk returns a tuple with the CabinetSpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinetSpaceId

`func (o *DemarcationPoint) SetCabinetSpaceId(v string)`

SetCabinetSpaceId sets CabinetSpaceId field to given value.


### GetPatchPanel

`func (o *DemarcationPoint) GetPatchPanel() string`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *DemarcationPoint) GetPatchPanelOk() (*string, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *DemarcationPoint) SetPatchPanel(v string)`

SetPatchPanel sets PatchPanel field to given value.


### GetPatchPanelPortA

`func (o *DemarcationPoint) GetPatchPanelPortA() int32`

GetPatchPanelPortA returns the PatchPanelPortA field if non-nil, zero value otherwise.

### GetPatchPanelPortAOk

`func (o *DemarcationPoint) GetPatchPanelPortAOk() (*int32, bool)`

GetPatchPanelPortAOk returns a tuple with the PatchPanelPortA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanelPortA

`func (o *DemarcationPoint) SetPatchPanelPortA(v int32)`

SetPatchPanelPortA sets PatchPanelPortA field to given value.


### GetPatchPanelPortB

`func (o *DemarcationPoint) GetPatchPanelPortB() int32`

GetPatchPanelPortB returns the PatchPanelPortB field if non-nil, zero value otherwise.

### GetPatchPanelPortBOk

`func (o *DemarcationPoint) GetPatchPanelPortBOk() (*int32, bool)`

GetPatchPanelPortBOk returns a tuple with the PatchPanelPortB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanelPortB

`func (o *DemarcationPoint) SetPatchPanelPortB(v int32)`

SetPatchPanelPortB sets PatchPanelPortB field to given value.

### HasPatchPanelPortB

`func (o *DemarcationPoint) HasPatchPanelPortB() bool`

HasPatchPanelPortB returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


