# ChangeOperationUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Op** | **string** | Operation type. Allowed values: - replace - add - remove  | 
**Path** | **string** | Path inside document leading to updated parameter. Allowed values: - /bandwidth - /routingProtocol/ipv4/customerRoutes[*] - /routingProtocol/ipv6/customerRoutes[*]  | 
**Value** | **string** | New value for updated parameter.  Allowed value for PA is prefixLength, e.g. \&quot;30\&quot; Allowed value for PI is prefix with subnetSize. e.g. \&quot;192.168.1.0/24\&quot;  | 
**Order** | Pointer to [**ServiceOrder**](ServiceOrder.md) |  | [optional] 

## Methods

### NewChangeOperationUpdate

`func NewChangeOperationUpdate(op string, path string, value string, ) *ChangeOperationUpdate`

NewChangeOperationUpdate instantiates a new ChangeOperationUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeOperationUpdateWithDefaults

`func NewChangeOperationUpdateWithDefaults() *ChangeOperationUpdate`

NewChangeOperationUpdateWithDefaults instantiates a new ChangeOperationUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOp

`func (o *ChangeOperationUpdate) GetOp() string`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *ChangeOperationUpdate) GetOpOk() (*string, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *ChangeOperationUpdate) SetOp(v string)`

SetOp sets Op field to given value.


### GetPath

`func (o *ChangeOperationUpdate) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ChangeOperationUpdate) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ChangeOperationUpdate) SetPath(v string)`

SetPath sets Path field to given value.


### GetValue

`func (o *ChangeOperationUpdate) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ChangeOperationUpdate) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ChangeOperationUpdate) SetValue(v string)`

SetValue sets Value field to given value.


### GetOrder

`func (o *ChangeOperationUpdate) GetOrder() ServiceOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ChangeOperationUpdate) GetOrderOk() (*ServiceOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ChangeOperationUpdate) SetOrder(v ServiceOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ChangeOperationUpdate) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


