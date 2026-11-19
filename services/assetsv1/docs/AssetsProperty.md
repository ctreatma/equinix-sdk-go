# AssetsProperty

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | Key of the property. | 
**Value** | **string** | Value of the property. | 
**Tag** | Pointer to **string** | Stands for a logical grouping on where the asset belogs to for a particular product. e.g - A-SIDE for Cross Connect. | [optional] 

## Methods

### NewAssetsProperty

`func NewAssetsProperty(key string, value string, ) *AssetsProperty`

NewAssetsProperty instantiates a new AssetsProperty object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetsPropertyWithDefaults

`func NewAssetsPropertyWithDefaults() *AssetsProperty`

NewAssetsPropertyWithDefaults instantiates a new AssetsProperty object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *AssetsProperty) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AssetsProperty) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AssetsProperty) SetKey(v string)`

SetKey sets Key field to given value.


### GetValue

`func (o *AssetsProperty) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AssetsProperty) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AssetsProperty) SetValue(v string)`

SetValue sets Value field to given value.


### GetTag

`func (o *AssetsProperty) GetTag() string`

GetTag returns the Tag field if non-nil, zero value otherwise.

### GetTagOk

`func (o *AssetsProperty) GetTagOk() (*string, bool)`

GetTagOk returns a tuple with the Tag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTag

`func (o *AssetsProperty) SetTag(v string)`

SetTag sets Tag field to given value.

### HasTag

`func (o *AssetsProperty) HasTag() bool`

HasTag returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


