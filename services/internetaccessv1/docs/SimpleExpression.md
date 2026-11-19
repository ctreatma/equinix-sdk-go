# SimpleExpression

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Property** | **string** |  | 
**Operator** | [**SimpleExpressionOperator**](SimpleExpressionOperator.md) |  | 
**Values** | **[]string** |  | 

## Methods

### NewSimpleExpression

`func NewSimpleExpression(property string, operator SimpleExpressionOperator, values []string, ) *SimpleExpression`

NewSimpleExpression instantiates a new SimpleExpression object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSimpleExpressionWithDefaults

`func NewSimpleExpressionWithDefaults() *SimpleExpression`

NewSimpleExpressionWithDefaults instantiates a new SimpleExpression object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProperty

`func (o *SimpleExpression) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SimpleExpression) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SimpleExpression) SetProperty(v string)`

SetProperty sets Property field to given value.


### GetOperator

`func (o *SimpleExpression) GetOperator() SimpleExpressionOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *SimpleExpression) GetOperatorOk() (*SimpleExpressionOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *SimpleExpression) SetOperator(v SimpleExpressionOperator)`

SetOperator sets Operator field to given value.


### GetValues

`func (o *SimpleExpression) GetValues() []string`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *SimpleExpression) GetValuesOk() (*[]string, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *SimpleExpression) SetValues(v []string)`

SetValues sets Values field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


