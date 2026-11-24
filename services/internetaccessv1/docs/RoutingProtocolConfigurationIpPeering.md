# RoutingProtocolConfigurationIpPeering

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VrrpEnabled** | Pointer to **bool** |  | [optional] 
**PeerSubnet** | Pointer to [**RoutingProtocolConfigurationIpPeeringPeerSubnet**](RoutingProtocolConfigurationIpPeeringPeerSubnet.md) |  | [optional] 

## Methods

### NewRoutingProtocolConfigurationIpPeering

`func NewRoutingProtocolConfigurationIpPeering() *RoutingProtocolConfigurationIpPeering`

NewRoutingProtocolConfigurationIpPeering instantiates a new RoutingProtocolConfigurationIpPeering object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolConfigurationIpPeeringWithDefaults

`func NewRoutingProtocolConfigurationIpPeeringWithDefaults() *RoutingProtocolConfigurationIpPeering`

NewRoutingProtocolConfigurationIpPeeringWithDefaults instantiates a new RoutingProtocolConfigurationIpPeering object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVrrpEnabled

`func (o *RoutingProtocolConfigurationIpPeering) GetVrrpEnabled() bool`

GetVrrpEnabled returns the VrrpEnabled field if non-nil, zero value otherwise.

### GetVrrpEnabledOk

`func (o *RoutingProtocolConfigurationIpPeering) GetVrrpEnabledOk() (*bool, bool)`

GetVrrpEnabledOk returns a tuple with the VrrpEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVrrpEnabled

`func (o *RoutingProtocolConfigurationIpPeering) SetVrrpEnabled(v bool)`

SetVrrpEnabled sets VrrpEnabled field to given value.

### HasVrrpEnabled

`func (o *RoutingProtocolConfigurationIpPeering) HasVrrpEnabled() bool`

HasVrrpEnabled returns a boolean if a field has been set.

### GetPeerSubnet

`func (o *RoutingProtocolConfigurationIpPeering) GetPeerSubnet() RoutingProtocolConfigurationIpPeeringPeerSubnet`

GetPeerSubnet returns the PeerSubnet field if non-nil, zero value otherwise.

### GetPeerSubnetOk

`func (o *RoutingProtocolConfigurationIpPeering) GetPeerSubnetOk() (*RoutingProtocolConfigurationIpPeeringPeerSubnet, bool)`

GetPeerSubnetOk returns a tuple with the PeerSubnet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeerSubnet

`func (o *RoutingProtocolConfigurationIpPeering) SetPeerSubnet(v RoutingProtocolConfigurationIpPeeringPeerSubnet)`

SetPeerSubnet sets PeerSubnet field to given value.

### HasPeerSubnet

`func (o *RoutingProtocolConfigurationIpPeering) HasPeerSubnet() bool`

HasPeerSubnet returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


