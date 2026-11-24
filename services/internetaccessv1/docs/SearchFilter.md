# SearchFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**And** | [**[]SimpleExpression**](SimpleExpression.md) |  | 

## Methods

### NewSearchFilter

`func NewSearchFilter(and []SimpleExpression, ) *SearchFilter`

NewSearchFilter instantiates a new SearchFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchFilterWithDefaults

`func NewSearchFilterWithDefaults() *SearchFilter`

NewSearchFilterWithDefaults instantiates a new SearchFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnd

`func (o *SearchFilter) GetAnd() []SimpleExpression`

GetAnd returns the And field if non-nil, zero value otherwise.

### GetAndOk

`func (o *SearchFilter) GetAndOk() (*[]SimpleExpression, bool)`

GetAndOk returns a tuple with the And field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnd

`func (o *SearchFilter) SetAnd(v []SimpleExpression)`

SetAnd sets And field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


