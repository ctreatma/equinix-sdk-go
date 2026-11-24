# SingleCaseResponseV2NotesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Identifier of the note. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | A datetime string with format YYYY-MM-DDTHH:mm:ss.sssZ. | [optional] 
**Text** | Pointer to **string** | The content of the note. | [optional] 
**Type** | Pointer to [**SingleCaseResponseV2NotesInnerType**](SingleCaseResponseV2NotesInnerType.md) |  | [optional] 

## Methods

### NewSingleCaseResponseV2NotesInner

`func NewSingleCaseResponseV2NotesInner() *SingleCaseResponseV2NotesInner`

NewSingleCaseResponseV2NotesInner instantiates a new SingleCaseResponseV2NotesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSingleCaseResponseV2NotesInnerWithDefaults

`func NewSingleCaseResponseV2NotesInnerWithDefaults() *SingleCaseResponseV2NotesInner`

NewSingleCaseResponseV2NotesInnerWithDefaults instantiates a new SingleCaseResponseV2NotesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SingleCaseResponseV2NotesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SingleCaseResponseV2NotesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SingleCaseResponseV2NotesInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SingleCaseResponseV2NotesInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *SingleCaseResponseV2NotesInner) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *SingleCaseResponseV2NotesInner) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *SingleCaseResponseV2NotesInner) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *SingleCaseResponseV2NotesInner) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetText

`func (o *SingleCaseResponseV2NotesInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SingleCaseResponseV2NotesInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SingleCaseResponseV2NotesInner) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *SingleCaseResponseV2NotesInner) HasText() bool`

HasText returns a boolean if a field has been set.

### GetType

`func (o *SingleCaseResponseV2NotesInner) GetType() SingleCaseResponseV2NotesInnerType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SingleCaseResponseV2NotesInner) GetTypeOk() (*SingleCaseResponseV2NotesInnerType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SingleCaseResponseV2NotesInner) SetType(v SingleCaseResponseV2NotesInnerType)`

SetType sets Type field to given value.

### HasType

`func (o *SingleCaseResponseV2NotesInner) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


