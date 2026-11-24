# SubscriptionCertificateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChannelType** | Pointer to [**GetCertificateChannelTypeParameter**](GetCertificateChannelTypeParameter.md) |  | [optional] 
**CertificateBase64** | Pointer to **string** | Base64-encoded certificate | [optional] 
**ExpiryDate** | Pointer to **time.Time** | The date and time when the certificate expires. | [optional] 

## Methods

### NewSubscriptionCertificateResponse

`func NewSubscriptionCertificateResponse() *SubscriptionCertificateResponse`

NewSubscriptionCertificateResponse instantiates a new SubscriptionCertificateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionCertificateResponseWithDefaults

`func NewSubscriptionCertificateResponseWithDefaults() *SubscriptionCertificateResponse`

NewSubscriptionCertificateResponseWithDefaults instantiates a new SubscriptionCertificateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannelType

`func (o *SubscriptionCertificateResponse) GetChannelType() GetCertificateChannelTypeParameter`

GetChannelType returns the ChannelType field if non-nil, zero value otherwise.

### GetChannelTypeOk

`func (o *SubscriptionCertificateResponse) GetChannelTypeOk() (*GetCertificateChannelTypeParameter, bool)`

GetChannelTypeOk returns a tuple with the ChannelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelType

`func (o *SubscriptionCertificateResponse) SetChannelType(v GetCertificateChannelTypeParameter)`

SetChannelType sets ChannelType field to given value.

### HasChannelType

`func (o *SubscriptionCertificateResponse) HasChannelType() bool`

HasChannelType returns a boolean if a field has been set.

### GetCertificateBase64

`func (o *SubscriptionCertificateResponse) GetCertificateBase64() string`

GetCertificateBase64 returns the CertificateBase64 field if non-nil, zero value otherwise.

### GetCertificateBase64Ok

`func (o *SubscriptionCertificateResponse) GetCertificateBase64Ok() (*string, bool)`

GetCertificateBase64Ok returns a tuple with the CertificateBase64 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateBase64

`func (o *SubscriptionCertificateResponse) SetCertificateBase64(v string)`

SetCertificateBase64 sets CertificateBase64 field to given value.

### HasCertificateBase64

`func (o *SubscriptionCertificateResponse) HasCertificateBase64() bool`

HasCertificateBase64 returns a boolean if a field has been set.

### GetExpiryDate

`func (o *SubscriptionCertificateResponse) GetExpiryDate() time.Time`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *SubscriptionCertificateResponse) GetExpiryDateOk() (*time.Time, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *SubscriptionCertificateResponse) SetExpiryDate(v time.Time)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *SubscriptionCertificateResponse) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


