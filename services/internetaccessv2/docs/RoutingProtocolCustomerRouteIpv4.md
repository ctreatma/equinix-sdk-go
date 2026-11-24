# RoutingProtocolCustomerRouteIpv4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPolicy** | **string** | Provider Assigned (PA) means that Equinix will assign ip address space.  Provider Independent (PI) means that the API caller must supply ip address space. Allowed values: PA, PI  | 
**IpBlock** | [**IpBlockReadModelIpv4**](IpBlockReadModelIpv4.md) |  | 
**Prefix** | **string** | Subnet prefix | 

## Methods

### NewRoutingProtocolCustomerRouteIpv4

`func NewRoutingProtocolCustomerRouteIpv4(importPolicy string, ipBlock IpBlockReadModelIpv4, prefix string, ) *RoutingProtocolCustomerRouteIpv4`

NewRoutingProtocolCustomerRouteIpv4 instantiates a new RoutingProtocolCustomerRouteIpv4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolCustomerRouteIpv4WithDefaults

`func NewRoutingProtocolCustomerRouteIpv4WithDefaults() *RoutingProtocolCustomerRouteIpv4`

NewRoutingProtocolCustomerRouteIpv4WithDefaults instantiates a new RoutingProtocolCustomerRouteIpv4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv4) GetImportPolicy() string`

GetImportPolicy returns the ImportPolicy field if non-nil, zero value otherwise.

### GetImportPolicyOk

`func (o *RoutingProtocolCustomerRouteIpv4) GetImportPolicyOk() (*string, bool)`

GetImportPolicyOk returns a tuple with the ImportPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv4) SetImportPolicy(v string)`

SetImportPolicy sets ImportPolicy field to given value.


### GetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv4) GetIpBlock() IpBlockReadModelIpv4`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *RoutingProtocolCustomerRouteIpv4) GetIpBlockOk() (*IpBlockReadModelIpv4, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv4) SetIpBlock(v IpBlockReadModelIpv4)`

SetIpBlock sets IpBlock field to given value.


### GetPrefix

`func (o *RoutingProtocolCustomerRouteIpv4) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *RoutingProtocolCustomerRouteIpv4) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *RoutingProtocolCustomerRouteIpv4) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


