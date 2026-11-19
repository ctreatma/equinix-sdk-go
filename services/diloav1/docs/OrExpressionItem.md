# OrExpressionItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Or** | Pointer to [**[]LoaCriterion**](LoaCriterion.md) | Search criterion item displaying a record if any of the conditions separated by &#39;or&#39; is true | [optional] 
**Property** | Pointer to [**LoaCriterionProperty**](LoaCriterionProperty.md) |  | [optional] 
**Operator** | Pointer to [**LoaCriterionOperator**](LoaCriterionOperator.md) |  | [optional] 
**Values** | Pointer to **[]string** | Criterion values | [optional] 

## Methods

### NewOrExpressionItem

`func NewOrExpressionItem() *OrExpressionItem`

NewOrExpressionItem instantiates a new OrExpressionItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrExpressionItemWithDefaults

`func NewOrExpressionItemWithDefaults() *OrExpressionItem`

NewOrExpressionItemWithDefaults instantiates a new OrExpressionItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOr

`func (o *OrExpressionItem) GetOr() []LoaCriterion`

GetOr returns the Or field if non-nil, zero value otherwise.

### GetOrOk

`func (o *OrExpressionItem) GetOrOk() (*[]LoaCriterion, bool)`

GetOrOk returns a tuple with the Or field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOr

`func (o *OrExpressionItem) SetOr(v []LoaCriterion)`

SetOr sets Or field to given value.

### HasOr

`func (o *OrExpressionItem) HasOr() bool`

HasOr returns a boolean if a field has been set.

### GetProperty

`func (o *OrExpressionItem) GetProperty() LoaCriterionProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *OrExpressionItem) GetPropertyOk() (*LoaCriterionProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *OrExpressionItem) SetProperty(v LoaCriterionProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *OrExpressionItem) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetOperator

`func (o *OrExpressionItem) GetOperator() LoaCriterionOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *OrExpressionItem) GetOperatorOk() (*LoaCriterionOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *OrExpressionItem) SetOperator(v LoaCriterionOperator)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *OrExpressionItem) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetValues

`func (o *OrExpressionItem) GetValues() []string`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *OrExpressionItem) GetValuesOk() (*[]string, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *OrExpressionItem) SetValues(v []string)`

SetValues sets Values field to given value.

### HasValues

`func (o *OrExpressionItem) HasValues() bool`

HasValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


