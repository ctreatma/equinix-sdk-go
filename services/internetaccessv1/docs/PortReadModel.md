# PortReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | **string** | Port URI | 
**Type** | [**PortReadModelType**](PortReadModelType.md) |  | 
**Uuid** | **string** | Port identifier | 

## Methods

### NewPortReadModel

`func NewPortReadModel(href string, type_ PortReadModelType, uuid string, ) *PortReadModel`

NewPortReadModel instantiates a new PortReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortReadModelWithDefaults

`func NewPortReadModelWithDefaults() *PortReadModel`

NewPortReadModelWithDefaults instantiates a new PortReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *PortReadModel) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *PortReadModel) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *PortReadModel) SetHref(v string)`

SetHref sets Href field to given value.


### GetType

`func (o *PortReadModel) GetType() PortReadModelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PortReadModel) GetTypeOk() (*PortReadModelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PortReadModel) SetType(v PortReadModelType)`

SetType sets Type field to given value.


### GetUuid

`func (o *PortReadModel) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PortReadModel) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PortReadModel) SetUuid(v string)`

SetUuid sets Uuid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


