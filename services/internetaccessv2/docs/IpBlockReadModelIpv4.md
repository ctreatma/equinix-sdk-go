# IpBlockReadModelIpv4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | Pointer to **string** | Ip block URI | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 
**Type** | [**IpBlockReadModelType**](IpBlockReadModelType.md) |  | 
**Prefix** | Pointer to **string** | Subnet prefix | [optional] 
**PrefixLength** | Pointer to **int32** | Determines the size of ip subnet | [optional] 
**AddressingPlans** | Pointer to [**[]IpBlockAddressingPlans**](IpBlockAddressingPlans.md) | Collection of addressing plans | [optional] 
**Questions** | Pointer to [**[]IpBlockQuestions**](IpBlockQuestions.md) | Connection of questions | [optional] 

## Methods

### NewIpBlockReadModelIpv4

`func NewIpBlockReadModelIpv4(type_ IpBlockReadModelType, ) *IpBlockReadModelIpv4`

NewIpBlockReadModelIpv4 instantiates a new IpBlockReadModelIpv4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIpBlockReadModelIpv4WithDefaults

`func NewIpBlockReadModelIpv4WithDefaults() *IpBlockReadModelIpv4`

NewIpBlockReadModelIpv4WithDefaults instantiates a new IpBlockReadModelIpv4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *IpBlockReadModelIpv4) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *IpBlockReadModelIpv4) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *IpBlockReadModelIpv4) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *IpBlockReadModelIpv4) HasHref() bool`

HasHref returns a boolean if a field has been set.

### GetUuid

`func (o *IpBlockReadModelIpv4) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *IpBlockReadModelIpv4) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *IpBlockReadModelIpv4) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *IpBlockReadModelIpv4) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *IpBlockReadModelIpv4) GetType() IpBlockReadModelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *IpBlockReadModelIpv4) GetTypeOk() (*IpBlockReadModelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *IpBlockReadModelIpv4) SetType(v IpBlockReadModelType)`

SetType sets Type field to given value.


### GetPrefix

`func (o *IpBlockReadModelIpv4) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *IpBlockReadModelIpv4) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *IpBlockReadModelIpv4) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *IpBlockReadModelIpv4) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.

### GetPrefixLength

`func (o *IpBlockReadModelIpv4) GetPrefixLength() int32`

GetPrefixLength returns the PrefixLength field if non-nil, zero value otherwise.

### GetPrefixLengthOk

`func (o *IpBlockReadModelIpv4) GetPrefixLengthOk() (*int32, bool)`

GetPrefixLengthOk returns a tuple with the PrefixLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefixLength

`func (o *IpBlockReadModelIpv4) SetPrefixLength(v int32)`

SetPrefixLength sets PrefixLength field to given value.

### HasPrefixLength

`func (o *IpBlockReadModelIpv4) HasPrefixLength() bool`

HasPrefixLength returns a boolean if a field has been set.

### GetAddressingPlans

`func (o *IpBlockReadModelIpv4) GetAddressingPlans() []IpBlockAddressingPlans`

GetAddressingPlans returns the AddressingPlans field if non-nil, zero value otherwise.

### GetAddressingPlansOk

`func (o *IpBlockReadModelIpv4) GetAddressingPlansOk() (*[]IpBlockAddressingPlans, bool)`

GetAddressingPlansOk returns a tuple with the AddressingPlans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressingPlans

`func (o *IpBlockReadModelIpv4) SetAddressingPlans(v []IpBlockAddressingPlans)`

SetAddressingPlans sets AddressingPlans field to given value.

### HasAddressingPlans

`func (o *IpBlockReadModelIpv4) HasAddressingPlans() bool`

HasAddressingPlans returns a boolean if a field has been set.

### GetQuestions

`func (o *IpBlockReadModelIpv4) GetQuestions() []IpBlockQuestions`

GetQuestions returns the Questions field if non-nil, zero value otherwise.

### GetQuestionsOk

`func (o *IpBlockReadModelIpv4) GetQuestionsOk() (*[]IpBlockQuestions, bool)`

GetQuestionsOk returns a tuple with the Questions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestions

`func (o *IpBlockReadModelIpv4) SetQuestions(v []IpBlockQuestions)`

SetQuestions sets Questions field to given value.

### HasQuestions

`func (o *IpBlockReadModelIpv4) HasQuestions() bool`

HasQuestions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


