# ColoAccessPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Port** | [**Port**](Port.md) |  | 
**LinkProtocol** | Pointer to [**PortLinkProtocol**](PortLinkProtocol.md) |  | [optional] 

## Methods

### NewColoAccessPoint

`func NewColoAccessPoint(port Port, ) *ColoAccessPoint`

NewColoAccessPoint instantiates a new ColoAccessPoint object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewColoAccessPointWithDefaults

`func NewColoAccessPointWithDefaults() *ColoAccessPoint`

NewColoAccessPointWithDefaults instantiates a new ColoAccessPoint object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPort

`func (o *ColoAccessPoint) GetPort() Port`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *ColoAccessPoint) GetPortOk() (*Port, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *ColoAccessPoint) SetPort(v Port)`

SetPort sets Port field to given value.


### GetLinkProtocol

`func (o *ColoAccessPoint) GetLinkProtocol() PortLinkProtocol`

GetLinkProtocol returns the LinkProtocol field if non-nil, zero value otherwise.

### GetLinkProtocolOk

`func (o *ColoAccessPoint) GetLinkProtocolOk() (*PortLinkProtocol, bool)`

GetLinkProtocolOk returns a tuple with the LinkProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkProtocol

`func (o *ColoAccessPoint) SetLinkProtocol(v PortLinkProtocol)`

SetLinkProtocol sets LinkProtocol field to given value.

### HasLinkProtocol

`func (o *ColoAccessPoint) HasLinkProtocol() bool`

HasLinkProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


