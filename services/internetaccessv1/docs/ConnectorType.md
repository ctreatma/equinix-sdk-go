# ConnectorType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**RequiredPorts** | **int32** |  | 
**OptionalPorts** | **int32** |  | 
**Locations** | Pointer to [**[]ConnectorTypeLocation**](ConnectorTypeLocation.md) |  | [optional] 

## Methods

### NewConnectorType

`func NewConnectorType(name string, requiredPorts int32, optionalPorts int32, ) *ConnectorType`

NewConnectorType instantiates a new ConnectorType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectorTypeWithDefaults

`func NewConnectorTypeWithDefaults() *ConnectorType`

NewConnectorTypeWithDefaults instantiates a new ConnectorType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ConnectorType) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectorType) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectorType) SetName(v string)`

SetName sets Name field to given value.


### GetRequiredPorts

`func (o *ConnectorType) GetRequiredPorts() int32`

GetRequiredPorts returns the RequiredPorts field if non-nil, zero value otherwise.

### GetRequiredPortsOk

`func (o *ConnectorType) GetRequiredPortsOk() (*int32, bool)`

GetRequiredPortsOk returns a tuple with the RequiredPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredPorts

`func (o *ConnectorType) SetRequiredPorts(v int32)`

SetRequiredPorts sets RequiredPorts field to given value.


### GetOptionalPorts

`func (o *ConnectorType) GetOptionalPorts() int32`

GetOptionalPorts returns the OptionalPorts field if non-nil, zero value otherwise.

### GetOptionalPortsOk

`func (o *ConnectorType) GetOptionalPortsOk() (*int32, bool)`

GetOptionalPortsOk returns a tuple with the OptionalPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionalPorts

`func (o *ConnectorType) SetOptionalPorts(v int32)`

SetOptionalPorts sets OptionalPorts field to given value.


### GetLocations

`func (o *ConnectorType) GetLocations() []ConnectorTypeLocation`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *ConnectorType) GetLocationsOk() (*[]ConnectorTypeLocation, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *ConnectorType) SetLocations(v []ConnectorTypeLocation)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *ConnectorType) HasLocations() bool`

HasLocations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


