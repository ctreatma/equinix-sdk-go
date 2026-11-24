# InlinePermission

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resources** | [**InlinePermissionResources**](InlinePermissionResources.md) |  | 
**ServiceActions** | [**InlinePermissionServiceActions**](InlinePermissionServiceActions.md) |  | 
**Condition** | Pointer to **string** |  | [optional] 
**IbxLocationCondition** | Pointer to [**IbxLocationCondition**](IbxLocationCondition.md) |  | [optional] 

## Methods

### NewInlinePermission

`func NewInlinePermission(resources InlinePermissionResources, serviceActions InlinePermissionServiceActions, ) *InlinePermission`

NewInlinePermission instantiates a new InlinePermission object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInlinePermissionWithDefaults

`func NewInlinePermissionWithDefaults() *InlinePermission`

NewInlinePermissionWithDefaults instantiates a new InlinePermission object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResources

`func (o *InlinePermission) GetResources() InlinePermissionResources`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *InlinePermission) GetResourcesOk() (*InlinePermissionResources, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *InlinePermission) SetResources(v InlinePermissionResources)`

SetResources sets Resources field to given value.


### GetServiceActions

`func (o *InlinePermission) GetServiceActions() InlinePermissionServiceActions`

GetServiceActions returns the ServiceActions field if non-nil, zero value otherwise.

### GetServiceActionsOk

`func (o *InlinePermission) GetServiceActionsOk() (*InlinePermissionServiceActions, bool)`

GetServiceActionsOk returns a tuple with the ServiceActions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceActions

`func (o *InlinePermission) SetServiceActions(v InlinePermissionServiceActions)`

SetServiceActions sets ServiceActions field to given value.


### GetCondition

`func (o *InlinePermission) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *InlinePermission) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *InlinePermission) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *InlinePermission) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetIbxLocationCondition

`func (o *InlinePermission) GetIbxLocationCondition() IbxLocationCondition`

GetIbxLocationCondition returns the IbxLocationCondition field if non-nil, zero value otherwise.

### GetIbxLocationConditionOk

`func (o *InlinePermission) GetIbxLocationConditionOk() (*IbxLocationCondition, bool)`

GetIbxLocationConditionOk returns a tuple with the IbxLocationCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocationCondition

`func (o *InlinePermission) SetIbxLocationCondition(v IbxLocationCondition)`

SetIbxLocationCondition sets IbxLocationCondition field to given value.

### HasIbxLocationCondition

`func (o *InlinePermission) HasIbxLocationCondition() bool`

HasIbxLocationCondition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


