# PolicyMask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**ManagedPermissionSets** | Pointer to [**PolicyMaskAllOfManagedPermissionSets**](PolicyMaskAllOfManagedPermissionSets.md) |  | [optional] 
**UpdatedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 
**Ern** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**DisabledPolicy** | Pointer to [**AccessPolicyDisabledPolicy**](AccessPolicyDisabledPolicy.md) |  | [optional] 
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**PolicyMaskId** | **string** | Uniquely identifies a policy mask globally or within a governing project. | 
**ManagedPolicies** | Pointer to [**PolicyMaskAllOfManagedPolicies**](PolicyMaskAllOfManagedPolicies.md) |  | [optional] 
**Subtract** | Pointer to [**PolicyMaskAllOfSubtract**](PolicyMaskAllOfSubtract.md) |  | [optional] 

## Methods

### NewPolicyMask

`func NewPolicyMask(tags map[string]string, rev string, ern string, policyMaskId string, ) *PolicyMask`

NewPolicyMask instantiates a new PolicyMask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPolicyMaskWithDefaults

`func NewPolicyMaskWithDefaults() *PolicyMask`

NewPolicyMaskWithDefaults instantiates a new PolicyMask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PolicyMask) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PolicyMask) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PolicyMask) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PolicyMask) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTags

`func (o *PolicyMask) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PolicyMask) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PolicyMask) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetManagedPermissionSets

`func (o *PolicyMask) GetManagedPermissionSets() PolicyMaskAllOfManagedPermissionSets`

GetManagedPermissionSets returns the ManagedPermissionSets field if non-nil, zero value otherwise.

### GetManagedPermissionSetsOk

`func (o *PolicyMask) GetManagedPermissionSetsOk() (*PolicyMaskAllOfManagedPermissionSets, bool)`

GetManagedPermissionSetsOk returns a tuple with the ManagedPermissionSets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPermissionSets

`func (o *PolicyMask) SetManagedPermissionSets(v PolicyMaskAllOfManagedPermissionSets)`

SetManagedPermissionSets sets ManagedPermissionSets field to given value.

### HasManagedPermissionSets

`func (o *PolicyMask) HasManagedPermissionSets() bool`

HasManagedPermissionSets returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *PolicyMask) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PolicyMask) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PolicyMask) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PolicyMask) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetCreatedBy

`func (o *PolicyMask) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *PolicyMask) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *PolicyMask) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *PolicyMask) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PolicyMask) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PolicyMask) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PolicyMask) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PolicyMask) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRev

`func (o *PolicyMask) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *PolicyMask) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *PolicyMask) SetRev(v string)`

SetRev sets Rev field to given value.


### GetErn

`func (o *PolicyMask) GetErn() string`

GetErn returns the Ern field if non-nil, zero value otherwise.

### GetErnOk

`func (o *PolicyMask) GetErnOk() (*string, bool)`

GetErnOk returns a tuple with the Ern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErn

`func (o *PolicyMask) SetErn(v string)`

SetErn sets Ern field to given value.


### GetDisabledPolicy

`func (o *PolicyMask) GetDisabledPolicy() AccessPolicyDisabledPolicy`

GetDisabledPolicy returns the DisabledPolicy field if non-nil, zero value otherwise.

### GetDisabledPolicyOk

`func (o *PolicyMask) GetDisabledPolicyOk() (*AccessPolicyDisabledPolicy, bool)`

GetDisabledPolicyOk returns a tuple with the DisabledPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabledPolicy

`func (o *PolicyMask) SetDisabledPolicy(v AccessPolicyDisabledPolicy)`

SetDisabledPolicy sets DisabledPolicy field to given value.

### HasDisabledPolicy

`func (o *PolicyMask) HasDisabledPolicy() bool`

HasDisabledPolicy returns a boolean if a field has been set.

### GetUpdatedBy

`func (o *PolicyMask) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *PolicyMask) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *PolicyMask) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *PolicyMask) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetPolicyMaskId

`func (o *PolicyMask) GetPolicyMaskId() string`

GetPolicyMaskId returns the PolicyMaskId field if non-nil, zero value otherwise.

### GetPolicyMaskIdOk

`func (o *PolicyMask) GetPolicyMaskIdOk() (*string, bool)`

GetPolicyMaskIdOk returns a tuple with the PolicyMaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyMaskId

`func (o *PolicyMask) SetPolicyMaskId(v string)`

SetPolicyMaskId sets PolicyMaskId field to given value.


### GetManagedPolicies

`func (o *PolicyMask) GetManagedPolicies() PolicyMaskAllOfManagedPolicies`

GetManagedPolicies returns the ManagedPolicies field if non-nil, zero value otherwise.

### GetManagedPoliciesOk

`func (o *PolicyMask) GetManagedPoliciesOk() (*PolicyMaskAllOfManagedPolicies, bool)`

GetManagedPoliciesOk returns a tuple with the ManagedPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPolicies

`func (o *PolicyMask) SetManagedPolicies(v PolicyMaskAllOfManagedPolicies)`

SetManagedPolicies sets ManagedPolicies field to given value.

### HasManagedPolicies

`func (o *PolicyMask) HasManagedPolicies() bool`

HasManagedPolicies returns a boolean if a field has been set.

### GetSubtract

`func (o *PolicyMask) GetSubtract() PolicyMaskAllOfSubtract`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *PolicyMask) GetSubtractOk() (*PolicyMaskAllOfSubtract, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *PolicyMask) SetSubtract(v PolicyMaskAllOfSubtract)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *PolicyMask) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


