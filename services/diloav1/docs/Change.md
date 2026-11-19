# Change

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | Digital LOA document identifier. | [optional] 
**Href** | Pointer to **string** | Digital LOA document URI. | [optional] 
**Type** | Pointer to [**ChangeType**](ChangeType.md) |  | [optional] 

## Methods

### NewChange

`func NewChange() *Change`

NewChange instantiates a new Change object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeWithDefaults

`func NewChangeWithDefaults() *Change`

NewChangeWithDefaults instantiates a new Change object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Change) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Change) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Change) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *Change) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetHref

`func (o *Change) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *Change) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *Change) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *Change) HasHref() bool`

HasHref returns a boolean if a field has been set.

### GetType

`func (o *Change) GetType() ChangeType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Change) GetTypeOk() (*ChangeType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Change) SetType(v ChangeType)`

SetType sets Type field to given value.

### HasType

`func (o *Change) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


