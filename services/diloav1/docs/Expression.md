# Expression

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Or** | Pointer to [**[]LoaCriterion**](LoaCriterion.md) | Search criterion item displaying a record if any of the conditions separated by &#39;or&#39; is true | [optional] 

## Methods

### NewExpression

`func NewExpression() *Expression`

NewExpression instantiates a new Expression object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExpressionWithDefaults

`func NewExpressionWithDefaults() *Expression`

NewExpressionWithDefaults instantiates a new Expression object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOr

`func (o *Expression) GetOr() []LoaCriterion`

GetOr returns the Or field if non-nil, zero value otherwise.

### GetOrOk

`func (o *Expression) GetOrOk() (*[]LoaCriterion, bool)`

GetOrOk returns a tuple with the Or field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOr

`func (o *Expression) SetOr(v []LoaCriterion)`

SetOr sets Or field to given value.

### HasOr

`func (o *Expression) HasOr() bool`

HasOr returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


