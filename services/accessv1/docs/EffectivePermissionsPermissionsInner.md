# EffectivePermissionsPermissionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | **[]string** | A set of actions the caller is permitted to perform. | 
**Resources** | Pointer to [**EffectivePermissionsPermissionsInnerResources**](EffectivePermissionsPermissionsInnerResources.md) |  | [optional] 
**MetroCodes** | Pointer to [**EffectivePermissionsPermissionsInnerMetroCodes**](EffectivePermissionsPermissionsInnerMetroCodes.md) |  | [optional] 
**IbxIds** | Pointer to [**EffectivePermissionsPermissionsInnerIbxIds**](EffectivePermissionsPermissionsInnerIbxIds.md) |  | [optional] 
**CageIds** | Pointer to [**EffectivePermissionsPermissionsInnerCageIds**](EffectivePermissionsPermissionsInnerCageIds.md) |  | [optional] 
**Condition** | Pointer to **string** | A Cedar policy language expression that must be true for the actions to be performed. | [optional] 

## Methods

### NewEffectivePermissionsPermissionsInner

`func NewEffectivePermissionsPermissionsInner(actions []string, ) *EffectivePermissionsPermissionsInner`

NewEffectivePermissionsPermissionsInner instantiates a new EffectivePermissionsPermissionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEffectivePermissionsPermissionsInnerWithDefaults

`func NewEffectivePermissionsPermissionsInnerWithDefaults() *EffectivePermissionsPermissionsInner`

NewEffectivePermissionsPermissionsInnerWithDefaults instantiates a new EffectivePermissionsPermissionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *EffectivePermissionsPermissionsInner) GetActions() []string`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *EffectivePermissionsPermissionsInner) GetActionsOk() (*[]string, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *EffectivePermissionsPermissionsInner) SetActions(v []string)`

SetActions sets Actions field to given value.


### GetResources

`func (o *EffectivePermissionsPermissionsInner) GetResources() EffectivePermissionsPermissionsInnerResources`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *EffectivePermissionsPermissionsInner) GetResourcesOk() (*EffectivePermissionsPermissionsInnerResources, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *EffectivePermissionsPermissionsInner) SetResources(v EffectivePermissionsPermissionsInnerResources)`

SetResources sets Resources field to given value.

### HasResources

`func (o *EffectivePermissionsPermissionsInner) HasResources() bool`

HasResources returns a boolean if a field has been set.

### GetMetroCodes

`func (o *EffectivePermissionsPermissionsInner) GetMetroCodes() EffectivePermissionsPermissionsInnerMetroCodes`

GetMetroCodes returns the MetroCodes field if non-nil, zero value otherwise.

### GetMetroCodesOk

`func (o *EffectivePermissionsPermissionsInner) GetMetroCodesOk() (*EffectivePermissionsPermissionsInnerMetroCodes, bool)`

GetMetroCodesOk returns a tuple with the MetroCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroCodes

`func (o *EffectivePermissionsPermissionsInner) SetMetroCodes(v EffectivePermissionsPermissionsInnerMetroCodes)`

SetMetroCodes sets MetroCodes field to given value.

### HasMetroCodes

`func (o *EffectivePermissionsPermissionsInner) HasMetroCodes() bool`

HasMetroCodes returns a boolean if a field has been set.

### GetIbxIds

`func (o *EffectivePermissionsPermissionsInner) GetIbxIds() EffectivePermissionsPermissionsInnerIbxIds`

GetIbxIds returns the IbxIds field if non-nil, zero value otherwise.

### GetIbxIdsOk

`func (o *EffectivePermissionsPermissionsInner) GetIbxIdsOk() (*EffectivePermissionsPermissionsInnerIbxIds, bool)`

GetIbxIdsOk returns a tuple with the IbxIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxIds

`func (o *EffectivePermissionsPermissionsInner) SetIbxIds(v EffectivePermissionsPermissionsInnerIbxIds)`

SetIbxIds sets IbxIds field to given value.

### HasIbxIds

`func (o *EffectivePermissionsPermissionsInner) HasIbxIds() bool`

HasIbxIds returns a boolean if a field has been set.

### GetCageIds

`func (o *EffectivePermissionsPermissionsInner) GetCageIds() EffectivePermissionsPermissionsInnerCageIds`

GetCageIds returns the CageIds field if non-nil, zero value otherwise.

### GetCageIdsOk

`func (o *EffectivePermissionsPermissionsInner) GetCageIdsOk() (*EffectivePermissionsPermissionsInnerCageIds, bool)`

GetCageIdsOk returns a tuple with the CageIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageIds

`func (o *EffectivePermissionsPermissionsInner) SetCageIds(v EffectivePermissionsPermissionsInnerCageIds)`

SetCageIds sets CageIds field to given value.

### HasCageIds

`func (o *EffectivePermissionsPermissionsInner) HasCageIds() bool`

HasCageIds returns a boolean if a field has been set.

### GetCondition

`func (o *EffectivePermissionsPermissionsInner) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *EffectivePermissionsPermissionsInner) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *EffectivePermissionsPermissionsInner) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *EffectivePermissionsPermissionsInner) HasCondition() bool`

HasCondition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


