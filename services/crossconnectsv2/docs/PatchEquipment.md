# PatchEquipment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CabinetId** | **string** | Device Cabinet Id. The cabinet for patching must belong to the specific cage defined in the A-side details. | 
**ConnectorType** | **string** | Device Connector Type to facilitate cross connection.  | 
**Details** | **string** | Provide additional information to facilitate patch equipment connection | 
**Port** | **float32** | Device port number to be connected | 

## Methods

### NewPatchEquipment

`func NewPatchEquipment(cabinetId string, connectorType string, details string, port float32, ) *PatchEquipment`

NewPatchEquipment instantiates a new PatchEquipment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchEquipmentWithDefaults

`func NewPatchEquipmentWithDefaults() *PatchEquipment`

NewPatchEquipmentWithDefaults instantiates a new PatchEquipment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCabinetId

`func (o *PatchEquipment) GetCabinetId() string`

GetCabinetId returns the CabinetId field if non-nil, zero value otherwise.

### GetCabinetIdOk

`func (o *PatchEquipment) GetCabinetIdOk() (*string, bool)`

GetCabinetIdOk returns a tuple with the CabinetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinetId

`func (o *PatchEquipment) SetCabinetId(v string)`

SetCabinetId sets CabinetId field to given value.


### GetConnectorType

`func (o *PatchEquipment) GetConnectorType() string`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *PatchEquipment) GetConnectorTypeOk() (*string, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *PatchEquipment) SetConnectorType(v string)`

SetConnectorType sets ConnectorType field to given value.


### GetDetails

`func (o *PatchEquipment) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PatchEquipment) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PatchEquipment) SetDetails(v string)`

SetDetails sets Details field to given value.


### GetPort

`func (o *PatchEquipment) GetPort() float32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *PatchEquipment) GetPortOk() (*float32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *PatchEquipment) SetPort(v float32)`

SetPort sets Port field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


