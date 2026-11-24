# PatchDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Op** | [**PatchDocumentOp**](PatchDocumentOp.md) |  | 
**Path** | [**PatchDocumentPath**](PatchDocumentPath.md) |  | 
**Value** | Pointer to **map[string]interface{}** | The value to be used within the operations. | [optional] 
**From** | Pointer to **string** | A string containing a JSON Pointer value. | [optional] 

## Methods

### NewPatchDocument

`func NewPatchDocument(op PatchDocumentOp, path PatchDocumentPath, ) *PatchDocument`

NewPatchDocument instantiates a new PatchDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchDocumentWithDefaults

`func NewPatchDocumentWithDefaults() *PatchDocument`

NewPatchDocumentWithDefaults instantiates a new PatchDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOp

`func (o *PatchDocument) GetOp() PatchDocumentOp`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *PatchDocument) GetOpOk() (*PatchDocumentOp, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *PatchDocument) SetOp(v PatchDocumentOp)`

SetOp sets Op field to given value.


### GetPath

`func (o *PatchDocument) GetPath() PatchDocumentPath`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *PatchDocument) GetPathOk() (*PatchDocumentPath, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *PatchDocument) SetPath(v PatchDocumentPath)`

SetPath sets Path field to given value.


### GetValue

`func (o *PatchDocument) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PatchDocument) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PatchDocument) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.

### HasValue

`func (o *PatchDocument) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetFrom

`func (o *PatchDocument) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *PatchDocument) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *PatchDocument) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *PatchDocument) HasFrom() bool`

HasFrom returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


