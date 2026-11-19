# CreateProduct

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**CreateProductType**](CreateProductType.md) |  | 
**CrossConnect** | [**CreateCrossConnect**](CreateCrossConnect.md) |  | 

## Methods

### NewCreateProduct

`func NewCreateProduct(type_ CreateProductType, crossConnect CreateCrossConnect, ) *CreateProduct`

NewCreateProduct instantiates a new CreateProduct object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProductWithDefaults

`func NewCreateProductWithDefaults() *CreateProduct`

NewCreateProductWithDefaults instantiates a new CreateProduct object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateProduct) GetType() CreateProductType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateProduct) GetTypeOk() (*CreateProductType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateProduct) SetType(v CreateProductType)`

SetType sets Type field to given value.


### GetCrossConnect

`func (o *CreateProduct) GetCrossConnect() CreateCrossConnect`

GetCrossConnect returns the CrossConnect field if non-nil, zero value otherwise.

### GetCrossConnectOk

`func (o *CreateProduct) GetCrossConnectOk() (*CreateCrossConnect, bool)`

GetCrossConnectOk returns a tuple with the CrossConnect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrossConnect

`func (o *CreateProduct) SetCrossConnect(v CreateCrossConnect)`

SetCrossConnect sets CrossConnect field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


