# ProductInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to [**ProductType**](ProductType.md) |  | [optional] 
**Code** | Pointer to **string** | Equinix-assigned product code. | [optional] 
**Name** | Pointer to **string** | Full product name. | [optional] 
**Description** | Pointer to **string** | Product description. | [optional] 

## Methods

### NewProductInfo

`func NewProductInfo() *ProductInfo`

NewProductInfo instantiates a new ProductInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductInfoWithDefaults

`func NewProductInfoWithDefaults() *ProductInfo`

NewProductInfoWithDefaults instantiates a new ProductInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ProductInfo) GetType() ProductType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ProductInfo) GetTypeOk() (*ProductType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ProductInfo) SetType(v ProductType)`

SetType sets Type field to given value.

### HasType

`func (o *ProductInfo) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCode

`func (o *ProductInfo) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ProductInfo) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ProductInfo) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ProductInfo) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *ProductInfo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductInfo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductInfo) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductInfo) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ProductInfo) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductInfo) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductInfo) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductInfo) HasDescription() bool`

HasDescription returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


