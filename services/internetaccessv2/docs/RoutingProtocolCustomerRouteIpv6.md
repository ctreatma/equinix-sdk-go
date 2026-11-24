# RoutingProtocolCustomerRouteIpv6

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPolicy** | **string** |  | [default to "PI"]
**IpBlock** | [**IpBlockReadModelIpv6**](IpBlockReadModelIpv6.md) |  | 
**Prefix** | **string** | Subnet prefix | 

## Methods

### NewRoutingProtocolCustomerRouteIpv6

`func NewRoutingProtocolCustomerRouteIpv6(importPolicy string, ipBlock IpBlockReadModelIpv6, prefix string, ) *RoutingProtocolCustomerRouteIpv6`

NewRoutingProtocolCustomerRouteIpv6 instantiates a new RoutingProtocolCustomerRouteIpv6 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolCustomerRouteIpv6WithDefaults

`func NewRoutingProtocolCustomerRouteIpv6WithDefaults() *RoutingProtocolCustomerRouteIpv6`

NewRoutingProtocolCustomerRouteIpv6WithDefaults instantiates a new RoutingProtocolCustomerRouteIpv6 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv6) GetImportPolicy() string`

GetImportPolicy returns the ImportPolicy field if non-nil, zero value otherwise.

### GetImportPolicyOk

`func (o *RoutingProtocolCustomerRouteIpv6) GetImportPolicyOk() (*string, bool)`

GetImportPolicyOk returns a tuple with the ImportPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv6) SetImportPolicy(v string)`

SetImportPolicy sets ImportPolicy field to given value.


### GetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv6) GetIpBlock() IpBlockReadModelIpv6`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *RoutingProtocolCustomerRouteIpv6) GetIpBlockOk() (*IpBlockReadModelIpv6, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv6) SetIpBlock(v IpBlockReadModelIpv6)`

SetIpBlock sets IpBlock field to given value.


### GetPrefix

`func (o *RoutingProtocolCustomerRouteIpv6) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *RoutingProtocolCustomerRouteIpv6) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *RoutingProtocolCustomerRouteIpv6) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


