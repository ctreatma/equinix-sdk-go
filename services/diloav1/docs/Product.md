# Product

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | Product identifier. | 
**Type** | [**ProductType**](ProductType.md) |  | 
**CrossConnect** | [**CrossConnect**](CrossConnect.md) |  | 

## Methods

### NewProduct

`func NewProduct(uuid string, type_ ProductType, crossConnect CrossConnect, ) *Product`

NewProduct instantiates a new Product object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductWithDefaults

`func NewProductWithDefaults() *Product`

NewProductWithDefaults instantiates a new Product object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Product) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Product) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Product) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *Product) GetType() ProductType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Product) GetTypeOk() (*ProductType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Product) SetType(v ProductType)`

SetType sets Type field to given value.


### GetCrossConnect

`func (o *Product) GetCrossConnect() CrossConnect`

GetCrossConnect returns the CrossConnect field if non-nil, zero value otherwise.

### GetCrossConnectOk

`func (o *Product) GetCrossConnectOk() (*CrossConnect, bool)`

GetCrossConnectOk returns a tuple with the CrossConnect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrossConnect

`func (o *Product) SetCrossConnect(v CrossConnect)`

SetCrossConnect sets CrossConnect field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


