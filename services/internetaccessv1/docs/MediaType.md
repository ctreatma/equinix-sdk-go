# MediaType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**ConnectorTypes** | Pointer to [**[]ConnectorType**](ConnectorType.md) |  | [optional] 

## Methods

### NewMediaType

`func NewMediaType(name string, ) *MediaType`

NewMediaType instantiates a new MediaType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaTypeWithDefaults

`func NewMediaTypeWithDefaults() *MediaType`

NewMediaTypeWithDefaults instantiates a new MediaType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *MediaType) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MediaType) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MediaType) SetName(v string)`

SetName sets Name field to given value.


### GetConnectorTypes

`func (o *MediaType) GetConnectorTypes() []ConnectorType`

GetConnectorTypes returns the ConnectorTypes field if non-nil, zero value otherwise.

### GetConnectorTypesOk

`func (o *MediaType) GetConnectorTypesOk() (*[]ConnectorType, bool)`

GetConnectorTypesOk returns a tuple with the ConnectorTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorTypes

`func (o *MediaType) SetConnectorTypes(v []ConnectorType)`

SetConnectorTypes sets ConnectorTypes field to given value.

### HasConnectorTypes

`func (o *MediaType) HasConnectorTypes() bool`

HasConnectorTypes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


