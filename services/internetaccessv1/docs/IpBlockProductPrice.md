# IpBlockProductPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | Unique identifier assigned to the IP block. | [optional] 
**Type** | [**IpBlockType**](IpBlockType.md) |  | 
**Location** | [**AssetLocation**](AssetLocation.md) |  | 
**Ipv4** | Pointer to [**CustomerIpBlock**](CustomerIpBlock.md) |  | [optional] 
**Ipv6** | Pointer to [**CustomerIpBlock**](CustomerIpBlock.md) |  | [optional] 

## Methods

### NewIpBlockProductPrice

`func NewIpBlockProductPrice(type_ IpBlockType, location AssetLocation, ) *IpBlockProductPrice`

NewIpBlockProductPrice instantiates a new IpBlockProductPrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpBlockProductPriceWithDefaults

`func NewIpBlockProductPriceWithDefaults() *IpBlockProductPrice`

NewIpBlockProductPriceWithDefaults instantiates a new IpBlockProductPrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *IpBlockProductPrice) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *IpBlockProductPrice) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *IpBlockProductPrice) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *IpBlockProductPrice) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *IpBlockProductPrice) GetType() IpBlockType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *IpBlockProductPrice) GetTypeOk() (*IpBlockType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *IpBlockProductPrice) SetType(v IpBlockType)`

SetType sets Type field to given value.


### GetLocation

`func (o *IpBlockProductPrice) GetLocation() AssetLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *IpBlockProductPrice) GetLocationOk() (*AssetLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *IpBlockProductPrice) SetLocation(v AssetLocation)`

SetLocation sets Location field to given value.


### GetIpv4

`func (o *IpBlockProductPrice) GetIpv4() CustomerIpBlock`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *IpBlockProductPrice) GetIpv4Ok() (*CustomerIpBlock, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *IpBlockProductPrice) SetIpv4(v CustomerIpBlock)`

SetIpv4 sets Ipv4 field to given value.

### HasIpv4

`func (o *IpBlockProductPrice) HasIpv4() bool`

HasIpv4 returns a boolean if a field has been set.

### GetIpv6

`func (o *IpBlockProductPrice) GetIpv6() CustomerIpBlock`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *IpBlockProductPrice) GetIpv6Ok() (*CustomerIpBlock, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *IpBlockProductPrice) SetIpv6(v CustomerIpBlock)`

SetIpv6 sets Ipv6 field to given value.

### HasIpv6

`func (o *IpBlockProductPrice) HasIpv6() bool`

HasIpv6 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


