# RoutingProtocolConfigurationIp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerRoute** | Pointer to [**RoutingProtocolConfigurationIpCustomerRoute**](RoutingProtocolConfigurationIpCustomerRoute.md) |  | [optional] 
**Peering** | Pointer to [**RoutingProtocolConfigurationIpPeering**](RoutingProtocolConfigurationIpPeering.md) |  | [optional] 

## Methods

### NewRoutingProtocolConfigurationIp

`func NewRoutingProtocolConfigurationIp() *RoutingProtocolConfigurationIp`

NewRoutingProtocolConfigurationIp instantiates a new RoutingProtocolConfigurationIp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolConfigurationIpWithDefaults

`func NewRoutingProtocolConfigurationIpWithDefaults() *RoutingProtocolConfigurationIp`

NewRoutingProtocolConfigurationIpWithDefaults instantiates a new RoutingProtocolConfigurationIp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerRoute

`func (o *RoutingProtocolConfigurationIp) GetCustomerRoute() RoutingProtocolConfigurationIpCustomerRoute`

GetCustomerRoute returns the CustomerRoute field if non-nil, zero value otherwise.

### GetCustomerRouteOk

`func (o *RoutingProtocolConfigurationIp) GetCustomerRouteOk() (*RoutingProtocolConfigurationIpCustomerRoute, bool)`

GetCustomerRouteOk returns a tuple with the CustomerRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerRoute

`func (o *RoutingProtocolConfigurationIp) SetCustomerRoute(v RoutingProtocolConfigurationIpCustomerRoute)`

SetCustomerRoute sets CustomerRoute field to given value.

### HasCustomerRoute

`func (o *RoutingProtocolConfigurationIp) HasCustomerRoute() bool`

HasCustomerRoute returns a boolean if a field has been set.

### GetPeering

`func (o *RoutingProtocolConfigurationIp) GetPeering() RoutingProtocolConfigurationIpPeering`

GetPeering returns the Peering field if non-nil, zero value otherwise.

### GetPeeringOk

`func (o *RoutingProtocolConfigurationIp) GetPeeringOk() (*RoutingProtocolConfigurationIpPeering, bool)`

GetPeeringOk returns a tuple with the Peering field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeering

`func (o *RoutingProtocolConfigurationIp) SetPeering(v RoutingProtocolConfigurationIpPeering)`

SetPeering sets Peering field to given value.

### HasPeering

`func (o *RoutingProtocolConfigurationIp) HasPeering() bool`

HasPeering returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


