# UpdatePolicyMaskBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedPolicies** | Pointer to [**PolicyMaskAllOfManagedPolicies**](PolicyMaskAllOfManagedPolicies.md) |  | [optional] 
**ManagedPermissionSets** | Pointer to [**PolicyMaskAllOfManagedPermissionSets**](PolicyMaskAllOfManagedPermissionSets.md) |  | [optional] 
**Subtract** | Pointer to [**PolicyMaskAllOfSubtract**](PolicyMaskAllOfSubtract.md) |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewUpdatePolicyMaskBody

`func NewUpdatePolicyMaskBody(tags map[string]string, lastRev string, ) *UpdatePolicyMaskBody`

NewUpdatePolicyMaskBody instantiates a new UpdatePolicyMaskBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePolicyMaskBodyWithDefaults

`func NewUpdatePolicyMaskBodyWithDefaults() *UpdatePolicyMaskBody`

NewUpdatePolicyMaskBodyWithDefaults instantiates a new UpdatePolicyMaskBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedPolicies

`func (o *UpdatePolicyMaskBody) GetManagedPolicies() PolicyMaskAllOfManagedPolicies`

GetManagedPolicies returns the ManagedPolicies field if non-nil, zero value otherwise.

### GetManagedPoliciesOk

`func (o *UpdatePolicyMaskBody) GetManagedPoliciesOk() (*PolicyMaskAllOfManagedPolicies, bool)`

GetManagedPoliciesOk returns a tuple with the ManagedPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPolicies

`func (o *UpdatePolicyMaskBody) SetManagedPolicies(v PolicyMaskAllOfManagedPolicies)`

SetManagedPolicies sets ManagedPolicies field to given value.

### HasManagedPolicies

`func (o *UpdatePolicyMaskBody) HasManagedPolicies() bool`

HasManagedPolicies returns a boolean if a field has been set.

### GetManagedPermissionSets

`func (o *UpdatePolicyMaskBody) GetManagedPermissionSets() PolicyMaskAllOfManagedPermissionSets`

GetManagedPermissionSets returns the ManagedPermissionSets field if non-nil, zero value otherwise.

### GetManagedPermissionSetsOk

`func (o *UpdatePolicyMaskBody) GetManagedPermissionSetsOk() (*PolicyMaskAllOfManagedPermissionSets, bool)`

GetManagedPermissionSetsOk returns a tuple with the ManagedPermissionSets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPermissionSets

`func (o *UpdatePolicyMaskBody) SetManagedPermissionSets(v PolicyMaskAllOfManagedPermissionSets)`

SetManagedPermissionSets sets ManagedPermissionSets field to given value.

### HasManagedPermissionSets

`func (o *UpdatePolicyMaskBody) HasManagedPermissionSets() bool`

HasManagedPermissionSets returns a boolean if a field has been set.

### GetSubtract

`func (o *UpdatePolicyMaskBody) GetSubtract() PolicyMaskAllOfSubtract`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *UpdatePolicyMaskBody) GetSubtractOk() (*PolicyMaskAllOfSubtract, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *UpdatePolicyMaskBody) SetSubtract(v PolicyMaskAllOfSubtract)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *UpdatePolicyMaskBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetTags

`func (o *UpdatePolicyMaskBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdatePolicyMaskBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdatePolicyMaskBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *UpdatePolicyMaskBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdatePolicyMaskBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdatePolicyMaskBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdatePolicyMaskBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetLastRev

`func (o *UpdatePolicyMaskBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *UpdatePolicyMaskBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *UpdatePolicyMaskBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


