# RequestSchemaResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Ticket code, e.g. \&quot;0000-0000\&quot;. | 
**Schema** | [**map[string]FieldDefinition**](FieldDefinition.md) | Provides the request payload schema for the ticket code, including available fields, required flags, and any applicable constraints. The fields and their requirements vary by ticket code. The returned value is the source of truth. | 
**Example** | **map[string]interface{}** | Illustrative sample request payload for the ticket code. The fields and values vary by ticket code and are provided as a guide only. | 

## Methods

### NewRequestSchemaResponse

`func NewRequestSchemaResponse(code string, schema map[string]FieldDefinition, example map[string]interface{}, ) *RequestSchemaResponse`

NewRequestSchemaResponse instantiates a new RequestSchemaResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRequestSchemaResponseWithDefaults

`func NewRequestSchemaResponseWithDefaults() *RequestSchemaResponse`

NewRequestSchemaResponseWithDefaults instantiates a new RequestSchemaResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *RequestSchemaResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *RequestSchemaResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *RequestSchemaResponse) SetCode(v string)`

SetCode sets Code field to given value.


### GetSchema

`func (o *RequestSchemaResponse) GetSchema() map[string]FieldDefinition`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *RequestSchemaResponse) GetSchemaOk() (*map[string]FieldDefinition, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *RequestSchemaResponse) SetSchema(v map[string]FieldDefinition)`

SetSchema sets Schema field to given value.


### GetExample

`func (o *RequestSchemaResponse) GetExample() map[string]interface{}`

GetExample returns the Example field if non-nil, zero value otherwise.

### GetExampleOk

`func (o *RequestSchemaResponse) GetExampleOk() (*map[string]interface{}, bool)`

GetExampleOk returns a tuple with the Example field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExample

`func (o *RequestSchemaResponse) SetExample(v map[string]interface{})`

SetExample sets Example field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


