# RoutingProtocolCustomerRouteIpBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPolicy** | **string** | Provider Assigned (PA) means that Equinix will assign ip address space.  Provider Independent (PI) means that the API caller must supply ip address space. Allowed values: PA, PI  | 

## Methods

### NewRoutingProtocolCustomerRouteIpBase

`func NewRoutingProtocolCustomerRouteIpBase(importPolicy string, ) *RoutingProtocolCustomerRouteIpBase`

NewRoutingProtocolCustomerRouteIpBase instantiates a new RoutingProtocolCustomerRouteIpBase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolCustomerRouteIpBaseWithDefaults

`func NewRoutingProtocolCustomerRouteIpBaseWithDefaults() *RoutingProtocolCustomerRouteIpBase`

NewRoutingProtocolCustomerRouteIpBaseWithDefaults instantiates a new RoutingProtocolCustomerRouteIpBase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpBase) GetImportPolicy() string`

GetImportPolicy returns the ImportPolicy field if non-nil, zero value otherwise.

### GetImportPolicyOk

`func (o *RoutingProtocolCustomerRouteIpBase) GetImportPolicyOk() (*string, bool)`

GetImportPolicyOk returns a tuple with the ImportPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPolicy

`func (o *RoutingProtocolCustomerRouteIpBase) SetImportPolicy(v string)`

SetImportPolicy sets ImportPolicy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


