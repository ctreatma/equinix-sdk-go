# CreatePolicyMaskBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedPolicies** | Pointer to [**CreatePolicyMaskBodyManagedPolicies**](CreatePolicyMaskBodyManagedPolicies.md) |  | [optional] 
**ManagedPermissionSets** | Pointer to [**CreatePolicyMaskBodyManagedPermissionSets**](CreatePolicyMaskBodyManagedPermissionSets.md) |  | [optional] 
**Subtract** | Pointer to [**CreatePolicyMaskBodySubtract**](CreatePolicyMaskBodySubtract.md) |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**PolicyMaskId** | **string** | Uniquely identifies a policy mask globally or within a governing project. | 

## Methods

### NewCreatePolicyMaskBody

`func NewCreatePolicyMaskBody(tags map[string]string, policyMaskId string, ) *CreatePolicyMaskBody`

NewCreatePolicyMaskBody instantiates a new CreatePolicyMaskBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePolicyMaskBodyWithDefaults

`func NewCreatePolicyMaskBodyWithDefaults() *CreatePolicyMaskBody`

NewCreatePolicyMaskBodyWithDefaults instantiates a new CreatePolicyMaskBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedPolicies

`func (o *CreatePolicyMaskBody) GetManagedPolicies() CreatePolicyMaskBodyManagedPolicies`

GetManagedPolicies returns the ManagedPolicies field if non-nil, zero value otherwise.

### GetManagedPoliciesOk

`func (o *CreatePolicyMaskBody) GetManagedPoliciesOk() (*CreatePolicyMaskBodyManagedPolicies, bool)`

GetManagedPoliciesOk returns a tuple with the ManagedPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPolicies

`func (o *CreatePolicyMaskBody) SetManagedPolicies(v CreatePolicyMaskBodyManagedPolicies)`

SetManagedPolicies sets ManagedPolicies field to given value.

### HasManagedPolicies

`func (o *CreatePolicyMaskBody) HasManagedPolicies() bool`

HasManagedPolicies returns a boolean if a field has been set.

### GetManagedPermissionSets

`func (o *CreatePolicyMaskBody) GetManagedPermissionSets() CreatePolicyMaskBodyManagedPermissionSets`

GetManagedPermissionSets returns the ManagedPermissionSets field if non-nil, zero value otherwise.

### GetManagedPermissionSetsOk

`func (o *CreatePolicyMaskBody) GetManagedPermissionSetsOk() (*CreatePolicyMaskBodyManagedPermissionSets, bool)`

GetManagedPermissionSetsOk returns a tuple with the ManagedPermissionSets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPermissionSets

`func (o *CreatePolicyMaskBody) SetManagedPermissionSets(v CreatePolicyMaskBodyManagedPermissionSets)`

SetManagedPermissionSets sets ManagedPermissionSets field to given value.

### HasManagedPermissionSets

`func (o *CreatePolicyMaskBody) HasManagedPermissionSets() bool`

HasManagedPermissionSets returns a boolean if a field has been set.

### GetSubtract

`func (o *CreatePolicyMaskBody) GetSubtract() CreatePolicyMaskBodySubtract`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *CreatePolicyMaskBody) GetSubtractOk() (*CreatePolicyMaskBodySubtract, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *CreatePolicyMaskBody) SetSubtract(v CreatePolicyMaskBodySubtract)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *CreatePolicyMaskBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetTags

`func (o *CreatePolicyMaskBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreatePolicyMaskBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreatePolicyMaskBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *CreatePolicyMaskBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreatePolicyMaskBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreatePolicyMaskBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreatePolicyMaskBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPolicyMaskId

`func (o *CreatePolicyMaskBody) GetPolicyMaskId() string`

GetPolicyMaskId returns the PolicyMaskId field if non-nil, zero value otherwise.

### GetPolicyMaskIdOk

`func (o *CreatePolicyMaskBody) GetPolicyMaskIdOk() (*string, bool)`

GetPolicyMaskIdOk returns a tuple with the PolicyMaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyMaskId

`func (o *CreatePolicyMaskBody) SetPolicyMaskId(v string)`

SetPolicyMaskId sets PolicyMaskId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


