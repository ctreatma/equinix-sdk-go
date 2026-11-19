# DiverseConnections

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to [**DiverseConnectionsType**](DiverseConnectionsType.md) |  | [optional] [default to DIVERSECONNECTIONSTYPE_EXISTING]
**SerialNumber** | Pointer to **string** | The serial number of Cross Connect is expecting when Diversified connection required from a previously provisioned connection | [optional] 
**ASide** | Pointer to [**DiverseConnectionsASide**](DiverseConnectionsASide.md) |  | [optional] 
**ZSide** | Pointer to [**DiverseConnectionsZSide**](DiverseConnectionsZSide.md) |  | [optional] 

## Methods

### NewDiverseConnections

`func NewDiverseConnections() *DiverseConnections`

NewDiverseConnections instantiates a new DiverseConnections object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiverseConnectionsWithDefaults

`func NewDiverseConnectionsWithDefaults() *DiverseConnections`

NewDiverseConnectionsWithDefaults instantiates a new DiverseConnections object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *DiverseConnections) GetType() DiverseConnectionsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DiverseConnections) GetTypeOk() (*DiverseConnectionsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DiverseConnections) SetType(v DiverseConnectionsType)`

SetType sets Type field to given value.

### HasType

`func (o *DiverseConnections) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSerialNumber

`func (o *DiverseConnections) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *DiverseConnections) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *DiverseConnections) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *DiverseConnections) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetASide

`func (o *DiverseConnections) GetASide() DiverseConnectionsASide`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *DiverseConnections) GetASideOk() (*DiverseConnectionsASide, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *DiverseConnections) SetASide(v DiverseConnectionsASide)`

SetASide sets ASide field to given value.

### HasASide

`func (o *DiverseConnections) HasASide() bool`

HasASide returns a boolean if a field has been set.

### GetZSide

`func (o *DiverseConnections) GetZSide() DiverseConnectionsZSide`

GetZSide returns the ZSide field if non-nil, zero value otherwise.

### GetZSideOk

`func (o *DiverseConnections) GetZSideOk() (*DiverseConnectionsZSide, bool)`

GetZSideOk returns a tuple with the ZSide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZSide

`func (o *DiverseConnections) SetZSide(v DiverseConnectionsZSide)`

SetZSide sets ZSide field to given value.

### HasZSide

`func (o *DiverseConnections) HasZSide() bool`

HasZSide returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


