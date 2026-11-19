# Layer1Details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ASide** | [**ASide**](ASide.md) |  | 
**ZSide** | [**ZSide**](ZSide.md) |  | 
**DiverseConnections** | Pointer to [**DiverseConnections**](DiverseConnections.md) |  | [optional] 
**VerifyLink** | Pointer to **bool** | When &#x60;true&#x60;, light link verification is carried out. This may incur fixed fee based on your contract pricing. | [optional] 
**CircuitDeliveryDate** | Pointer to **string** | Carrier Circuit Delivery Date | [optional] 
**SubmarineEngineerRequired** | Pointer to **bool** | Set to &#x60;true&#x60; if submarine cable station engineer is required. | [optional] [default to false]

## Methods

### NewLayer1Details

`func NewLayer1Details(aSide ASide, zSide ZSide, ) *Layer1Details`

NewLayer1Details instantiates a new Layer1Details object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayer1DetailsWithDefaults

`func NewLayer1DetailsWithDefaults() *Layer1Details`

NewLayer1DetailsWithDefaults instantiates a new Layer1Details object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetASide

`func (o *Layer1Details) GetASide() ASide`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *Layer1Details) GetASideOk() (*ASide, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *Layer1Details) SetASide(v ASide)`

SetASide sets ASide field to given value.


### GetZSide

`func (o *Layer1Details) GetZSide() ZSide`

GetZSide returns the ZSide field if non-nil, zero value otherwise.

### GetZSideOk

`func (o *Layer1Details) GetZSideOk() (*ZSide, bool)`

GetZSideOk returns a tuple with the ZSide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZSide

`func (o *Layer1Details) SetZSide(v ZSide)`

SetZSide sets ZSide field to given value.


### GetDiverseConnections

`func (o *Layer1Details) GetDiverseConnections() DiverseConnections`

GetDiverseConnections returns the DiverseConnections field if non-nil, zero value otherwise.

### GetDiverseConnectionsOk

`func (o *Layer1Details) GetDiverseConnectionsOk() (*DiverseConnections, bool)`

GetDiverseConnectionsOk returns a tuple with the DiverseConnections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiverseConnections

`func (o *Layer1Details) SetDiverseConnections(v DiverseConnections)`

SetDiverseConnections sets DiverseConnections field to given value.

### HasDiverseConnections

`func (o *Layer1Details) HasDiverseConnections() bool`

HasDiverseConnections returns a boolean if a field has been set.

### GetVerifyLink

`func (o *Layer1Details) GetVerifyLink() bool`

GetVerifyLink returns the VerifyLink field if non-nil, zero value otherwise.

### GetVerifyLinkOk

`func (o *Layer1Details) GetVerifyLinkOk() (*bool, bool)`

GetVerifyLinkOk returns a tuple with the VerifyLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyLink

`func (o *Layer1Details) SetVerifyLink(v bool)`

SetVerifyLink sets VerifyLink field to given value.

### HasVerifyLink

`func (o *Layer1Details) HasVerifyLink() bool`

HasVerifyLink returns a boolean if a field has been set.

### GetCircuitDeliveryDate

`func (o *Layer1Details) GetCircuitDeliveryDate() string`

GetCircuitDeliveryDate returns the CircuitDeliveryDate field if non-nil, zero value otherwise.

### GetCircuitDeliveryDateOk

`func (o *Layer1Details) GetCircuitDeliveryDateOk() (*string, bool)`

GetCircuitDeliveryDateOk returns a tuple with the CircuitDeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitDeliveryDate

`func (o *Layer1Details) SetCircuitDeliveryDate(v string)`

SetCircuitDeliveryDate sets CircuitDeliveryDate field to given value.

### HasCircuitDeliveryDate

`func (o *Layer1Details) HasCircuitDeliveryDate() bool`

HasCircuitDeliveryDate returns a boolean if a field has been set.

### GetSubmarineEngineerRequired

`func (o *Layer1Details) GetSubmarineEngineerRequired() bool`

GetSubmarineEngineerRequired returns the SubmarineEngineerRequired field if non-nil, zero value otherwise.

### GetSubmarineEngineerRequiredOk

`func (o *Layer1Details) GetSubmarineEngineerRequiredOk() (*bool, bool)`

GetSubmarineEngineerRequiredOk returns a tuple with the SubmarineEngineerRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmarineEngineerRequired

`func (o *Layer1Details) SetSubmarineEngineerRequired(v bool)`

SetSubmarineEngineerRequired sets SubmarineEngineerRequired field to given value.

### HasSubmarineEngineerRequired

`func (o *Layer1Details) HasSubmarineEngineerRequired() bool`

HasSubmarineEngineerRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


