# LoaCriterion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Property** | Pointer to [**LoaCriterionProperty**](LoaCriterionProperty.md) |  | [optional] 
**Operator** | Pointer to [**LoaCriterionOperator**](LoaCriterionOperator.md) |  | [optional] 
**Values** | Pointer to **[]string** | Criterion values | [optional] 

## Methods

### NewLoaCriterion

`func NewLoaCriterion() *LoaCriterion`

NewLoaCriterion instantiates a new LoaCriterion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoaCriterionWithDefaults

`func NewLoaCriterionWithDefaults() *LoaCriterion`

NewLoaCriterionWithDefaults instantiates a new LoaCriterion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProperty

`func (o *LoaCriterion) GetProperty() LoaCriterionProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *LoaCriterion) GetPropertyOk() (*LoaCriterionProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *LoaCriterion) SetProperty(v LoaCriterionProperty)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *LoaCriterion) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetOperator

`func (o *LoaCriterion) GetOperator() LoaCriterionOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *LoaCriterion) GetOperatorOk() (*LoaCriterionOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *LoaCriterion) SetOperator(v LoaCriterionOperator)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *LoaCriterion) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetValues

`func (o *LoaCriterion) GetValues() []string`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *LoaCriterion) GetValuesOk() (*[]string, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *LoaCriterion) SetValues(v []string)`

SetValues sets Values field to given value.

### HasValues

`func (o *LoaCriterion) HasValues() bool`

HasValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


