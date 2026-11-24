# FieldDefinition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DataType** | [**FieldDefinitionDataType**](FieldDefinitionDataType.md) |  | 
**FieldDescription** | **string** | Explains the expected input for the field. | 
**Required** | **bool** | Indicates whether this field is required in the request payload. | 
**Format** | Pointer to **string** | Specifies the expected format or validation rule for the field. | [optional] 
**MinLength** | Pointer to **int32** | Minimum number of characters allowed for a string field. | [optional] 
**MaxLength** | Pointer to **int32** | Maximum number of characters allowed for a string field. | [optional] 
**AllowedValues** | Pointer to **[]string** | List of values accepted for the field, when the field is restricted to a predefined set of values. | [optional] 
**Constraints** | Pointer to **map[string]interface{}** | Additional validation rules for the field. The applicable constraints depend on the field and may include rules such as minItems, maxItems, maxItemsBy, oneOf, or contains. | [optional] 
**Items** | Pointer to [**FieldDefinition**](FieldDefinition.md) |  | [optional] 
**Fields** | Pointer to [**map[string]FieldDefinition**](FieldDefinition.md) | Defines the nested fields of an object. Each property name represents a field in the object and its value contains the corresponding field definition. | [optional] 

## Methods

### NewFieldDefinition

`func NewFieldDefinition(dataType FieldDefinitionDataType, fieldDescription string, required bool, ) *FieldDefinition`

NewFieldDefinition instantiates a new FieldDefinition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldDefinitionWithDefaults

`func NewFieldDefinitionWithDefaults() *FieldDefinition`

NewFieldDefinitionWithDefaults instantiates a new FieldDefinition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDataType

`func (o *FieldDefinition) GetDataType() FieldDefinitionDataType`

GetDataType returns the DataType field if non-nil, zero value otherwise.

### GetDataTypeOk

`func (o *FieldDefinition) GetDataTypeOk() (*FieldDefinitionDataType, bool)`

GetDataTypeOk returns a tuple with the DataType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataType

`func (o *FieldDefinition) SetDataType(v FieldDefinitionDataType)`

SetDataType sets DataType field to given value.


### GetFieldDescription

`func (o *FieldDefinition) GetFieldDescription() string`

GetFieldDescription returns the FieldDescription field if non-nil, zero value otherwise.

### GetFieldDescriptionOk

`func (o *FieldDefinition) GetFieldDescriptionOk() (*string, bool)`

GetFieldDescriptionOk returns a tuple with the FieldDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldDescription

`func (o *FieldDefinition) SetFieldDescription(v string)`

SetFieldDescription sets FieldDescription field to given value.


### GetRequired

`func (o *FieldDefinition) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *FieldDefinition) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *FieldDefinition) SetRequired(v bool)`

SetRequired sets Required field to given value.


### GetFormat

`func (o *FieldDefinition) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FieldDefinition) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FieldDefinition) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FieldDefinition) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetMinLength

`func (o *FieldDefinition) GetMinLength() int32`

GetMinLength returns the MinLength field if non-nil, zero value otherwise.

### GetMinLengthOk

`func (o *FieldDefinition) GetMinLengthOk() (*int32, bool)`

GetMinLengthOk returns a tuple with the MinLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLength

`func (o *FieldDefinition) SetMinLength(v int32)`

SetMinLength sets MinLength field to given value.

### HasMinLength

`func (o *FieldDefinition) HasMinLength() bool`

HasMinLength returns a boolean if a field has been set.

### GetMaxLength

`func (o *FieldDefinition) GetMaxLength() int32`

GetMaxLength returns the MaxLength field if non-nil, zero value otherwise.

### GetMaxLengthOk

`func (o *FieldDefinition) GetMaxLengthOk() (*int32, bool)`

GetMaxLengthOk returns a tuple with the MaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLength

`func (o *FieldDefinition) SetMaxLength(v int32)`

SetMaxLength sets MaxLength field to given value.

### HasMaxLength

`func (o *FieldDefinition) HasMaxLength() bool`

HasMaxLength returns a boolean if a field has been set.

### GetAllowedValues

`func (o *FieldDefinition) GetAllowedValues() []string`

GetAllowedValues returns the AllowedValues field if non-nil, zero value otherwise.

### GetAllowedValuesOk

`func (o *FieldDefinition) GetAllowedValuesOk() (*[]string, bool)`

GetAllowedValuesOk returns a tuple with the AllowedValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedValues

`func (o *FieldDefinition) SetAllowedValues(v []string)`

SetAllowedValues sets AllowedValues field to given value.

### HasAllowedValues

`func (o *FieldDefinition) HasAllowedValues() bool`

HasAllowedValues returns a boolean if a field has been set.

### GetConstraints

`func (o *FieldDefinition) GetConstraints() map[string]interface{}`

GetConstraints returns the Constraints field if non-nil, zero value otherwise.

### GetConstraintsOk

`func (o *FieldDefinition) GetConstraintsOk() (*map[string]interface{}, bool)`

GetConstraintsOk returns a tuple with the Constraints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraints

`func (o *FieldDefinition) SetConstraints(v map[string]interface{})`

SetConstraints sets Constraints field to given value.

### HasConstraints

`func (o *FieldDefinition) HasConstraints() bool`

HasConstraints returns a boolean if a field has been set.

### GetItems

`func (o *FieldDefinition) GetItems() FieldDefinition`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *FieldDefinition) GetItemsOk() (*FieldDefinition, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *FieldDefinition) SetItems(v FieldDefinition)`

SetItems sets Items field to given value.

### HasItems

`func (o *FieldDefinition) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetFields

`func (o *FieldDefinition) GetFields() map[string]FieldDefinition`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *FieldDefinition) GetFieldsOk() (*map[string]FieldDefinition, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *FieldDefinition) SetFields(v map[string]FieldDefinition)`

SetFields sets Fields field to given value.

### HasFields

`func (o *FieldDefinition) HasFields() bool`

HasFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


