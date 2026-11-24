# IpBlockReadModelIpv6

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | Pointer to **string** | Ip block URI | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 
**Type** | [**IpBlockReadModelType**](IpBlockReadModelType.md) |  | 
**Prefix** | Pointer to **string** | Subnet prefix | [optional] 
**PrefixLength** | Pointer to **int32** | Determines the size of ip subnet | [optional] 

## Methods

### NewIpBlockReadModelIpv6

`func NewIpBlockReadModelIpv6(type_ IpBlockReadModelType, ) *IpBlockReadModelIpv6`

NewIpBlockReadModelIpv6 instantiates a new IpBlockReadModelIpv6 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpBlockReadModelIpv6WithDefaults

`func NewIpBlockReadModelIpv6WithDefaults() *IpBlockReadModelIpv6`

NewIpBlockReadModelIpv6WithDefaults instantiates a new IpBlockReadModelIpv6 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *IpBlockReadModelIpv6) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *IpBlockReadModelIpv6) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *IpBlockReadModelIpv6) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *IpBlockReadModelIpv6) HasHref() bool`

HasHref returns a boolean if a field has been set.

### GetUuid

`func (o *IpBlockReadModelIpv6) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *IpBlockReadModelIpv6) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *IpBlockReadModelIpv6) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *IpBlockReadModelIpv6) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *IpBlockReadModelIpv6) GetType() IpBlockReadModelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *IpBlockReadModelIpv6) GetTypeOk() (*IpBlockReadModelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *IpBlockReadModelIpv6) SetType(v IpBlockReadModelType)`

SetType sets Type field to given value.


### GetPrefix

`func (o *IpBlockReadModelIpv6) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *IpBlockReadModelIpv6) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *IpBlockReadModelIpv6) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *IpBlockReadModelIpv6) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.

### GetPrefixLength

`func (o *IpBlockReadModelIpv6) GetPrefixLength() int32`

GetPrefixLength returns the PrefixLength field if non-nil, zero value otherwise.

### GetPrefixLengthOk

`func (o *IpBlockReadModelIpv6) GetPrefixLengthOk() (*int32, bool)`

GetPrefixLengthOk returns a tuple with the PrefixLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixLength

`func (o *IpBlockReadModelIpv6) SetPrefixLength(v int32)`

SetPrefixLength sets PrefixLength field to given value.

### HasPrefixLength

`func (o *IpBlockReadModelIpv6) HasPrefixLength() bool`

HasPrefixLength returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


