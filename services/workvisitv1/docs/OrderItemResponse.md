# OrderItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Successes** | Pointer to [**[]OrderItemResponseSuccessesInner**](OrderItemResponseSuccessesInner.md) |  | [optional] 

## Methods

### NewOrderItemResponse

`func NewOrderItemResponse() *OrderItemResponse`

NewOrderItemResponse instantiates a new OrderItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderItemResponseWithDefaults

`func NewOrderItemResponseWithDefaults() *OrderItemResponse`

NewOrderItemResponseWithDefaults instantiates a new OrderItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccesses

`func (o *OrderItemResponse) GetSuccesses() []OrderItemResponseSuccessesInner`

GetSuccesses returns the Successes field if non-nil, zero value otherwise.

### GetSuccessesOk

`func (o *OrderItemResponse) GetSuccessesOk() (*[]OrderItemResponseSuccessesInner, bool)`

GetSuccessesOk returns a tuple with the Successes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccesses

`func (o *OrderItemResponse) SetSuccesses(v []OrderItemResponseSuccessesInner)`

SetSuccesses sets Successes field to given value.

### HasSuccesses

`func (o *OrderItemResponse) HasSuccesses() bool`

HasSuccesses returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


