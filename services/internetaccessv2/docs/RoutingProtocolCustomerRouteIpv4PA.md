# RoutingProtocolCustomerRouteIpv4PA

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPolicy** | **string** |  | [default to "PA"]
**IpBlock** | [**IpBlockReadModelIpv4**](IpBlockReadModelIpv4.md) |  | 

## Methods

### NewRoutingProtocolCustomerRouteIpv4PA

`func NewRoutingProtocolCustomerRouteIpv4PA(importPolicy string, ipBlock IpBlockReadModelIpv4, ) *RoutingProtocolCustomerRouteIpv4PA`

NewRoutingProtocolCustomerRouteIpv4PA instantiates a new RoutingProtocolCustomerRouteIpv4PA object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolCustomerRouteIpv4PAWithDefaults

`func NewRoutingProtocolCustomerRouteIpv4PAWithDefaults() *RoutingProtocolCustomerRouteIpv4PA`

NewRoutingProtocolCustomerRouteIpv4PAWithDefaults instantiates a new RoutingProtocolCustomerRouteIpv4PA object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv4PA) GetImportPolicy() string`

GetImportPolicy returns the ImportPolicy field if non-nil, zero value otherwise.

### GetImportPolicyOk

`func (o *RoutingProtocolCustomerRouteIpv4PA) GetImportPolicyOk() (*string, bool)`

GetImportPolicyOk returns a tuple with the ImportPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpv4PA) SetImportPolicy(v string)`

SetImportPolicy sets ImportPolicy field to given value.


### GetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv4PA) GetIpBlock() IpBlockReadModelIpv4`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *RoutingProtocolCustomerRouteIpv4PA) GetIpBlockOk() (*IpBlockReadModelIpv4, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *RoutingProtocolCustomerRouteIpv4PA) SetIpBlock(v IpBlockReadModelIpv4)`

SetIpBlock sets IpBlock field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


