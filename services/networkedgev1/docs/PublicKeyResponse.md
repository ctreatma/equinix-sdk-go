# PublicKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | The unique Id of the keyName and keyValue combination | [optional] 
**KeyName** | Pointer to **string** | Key name | [optional] 
**KeyValue** | Pointer to **string** | Key value | [optional] 
**KeyType** | Pointer to [**PublicKeyResponseKeyType**](PublicKeyResponseKeyType.md) |  | [optional] 

## Methods

### NewPublicKeyResponse

`func NewPublicKeyResponse() *PublicKeyResponse`

NewPublicKeyResponse instantiates a new PublicKeyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicKeyResponseWithDefaults

`func NewPublicKeyResponseWithDefaults() *PublicKeyResponse`

NewPublicKeyResponseWithDefaults instantiates a new PublicKeyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *PublicKeyResponse) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PublicKeyResponse) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PublicKeyResponse) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *PublicKeyResponse) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetKeyName

`func (o *PublicKeyResponse) GetKeyName() string`

GetKeyName returns the KeyName field if non-nil, zero value otherwise.

### GetKeyNameOk

`func (o *PublicKeyResponse) GetKeyNameOk() (*string, bool)`

GetKeyNameOk returns a tuple with the KeyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyName

`func (o *PublicKeyResponse) SetKeyName(v string)`

SetKeyName sets KeyName field to given value.

### HasKeyName

`func (o *PublicKeyResponse) HasKeyName() bool`

HasKeyName returns a boolean if a field has been set.

### GetKeyValue

`func (o *PublicKeyResponse) GetKeyValue() string`

GetKeyValue returns the KeyValue field if non-nil, zero value otherwise.

### GetKeyValueOk

`func (o *PublicKeyResponse) GetKeyValueOk() (*string, bool)`

GetKeyValueOk returns a tuple with the KeyValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyValue

`func (o *PublicKeyResponse) SetKeyValue(v string)`

SetKeyValue sets KeyValue field to given value.

### HasKeyValue

`func (o *PublicKeyResponse) HasKeyValue() bool`

HasKeyValue returns a boolean if a field has been set.

### GetKeyType

`func (o *PublicKeyResponse) GetKeyType() PublicKeyResponseKeyType`

GetKeyType returns the KeyType field if non-nil, zero value otherwise.

### GetKeyTypeOk

`func (o *PublicKeyResponse) GetKeyTypeOk() (*PublicKeyResponseKeyType, bool)`

GetKeyTypeOk returns a tuple with the KeyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyType

`func (o *PublicKeyResponse) SetKeyType(v PublicKeyResponseKeyType)`

SetKeyType sets KeyType field to given value.

### HasKeyType

`func (o *PublicKeyResponse) HasKeyType() bool`

HasKeyType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


