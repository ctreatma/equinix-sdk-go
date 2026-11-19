# LoaSearchItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**And** | [**[]OrExpressionItem**](OrExpressionItem.md) | Search criterion list | 

## Methods

### NewLoaSearchItem

`func NewLoaSearchItem(and []OrExpressionItem, ) *LoaSearchItem`

NewLoaSearchItem instantiates a new LoaSearchItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoaSearchItemWithDefaults

`func NewLoaSearchItemWithDefaults() *LoaSearchItem`

NewLoaSearchItemWithDefaults instantiates a new LoaSearchItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnd

`func (o *LoaSearchItem) GetAnd() []OrExpressionItem`

GetAnd returns the And field if non-nil, zero value otherwise.

### GetAndOk

`func (o *LoaSearchItem) GetAndOk() (*[]OrExpressionItem, bool)`

GetAndOk returns a tuple with the And field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnd

`func (o *LoaSearchItem) SetAnd(v []OrExpressionItem)`

SetAnd sets And field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


