# RoutingProtocolCustomerRouteIpv6PA

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPolicy** | **string** |  | [default to "PA"]
**IpBlock** | [**IpBlockReadModelIpv6**](IpBlockReadModelIpv6.md) |  | 

## Methods

### NewRoutingProtocolCustomerRouteIpv6PA

`func NewRoutingProtocolCustomerRouteIpv6PA(importPolicy string, ipBlock IpBlockReadModelIpv6, ) *RoutingProtocolCustomerRouteIpv6PA`

NewRoutingProtocolCustomerRouteIpv6PA instantiates a new RoutingProtocolCustomerRouteIpv6PA object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolCustomerRouteIpv6PAWithDefaults

`func NewRoutingProtocolCustomerRouteIpv6PAWithDefaults() *RoutingProtocolCustomerRouteIpv6PA`

NewRoutingProtocolCustomerRouteIpv6PAWithDefaults instantiates a new RoutingProtocolCustomerRouteIpv6PA object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv6PA) GetImportPolicy() string`

GetImportPolicy returns the ImportPolicy field if non-nil, zero value otherwise.

### GetImportPolicyOk

`func (o *RoutingProtocolCustomerRouteIpv6PA) GetImportPolicyOk() (*string, bool)`

GetImportPolicyOk returns a tuple with the ImportPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv6PA) SetImportPolicy(v string)`

SetImportPolicy sets ImportPolicy field to given value.


### GetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv6PA) GetIpBlock() IpBlockReadModelIpv6`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *RoutingProtocolCustomerRouteIpv6PA) GetIpBlockOk() (*IpBlockReadModelIpv6, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv6PA) SetIpBlock(v IpBlockReadModelIpv6)`

SetIpBlock sets IpBlock field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


