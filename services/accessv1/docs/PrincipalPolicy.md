# PrincipalPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**UpdatedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**UserPrincipal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. | 
**Permissions** | [**[]ManagedPermissionSetRef**](ManagedPermissionSetRef.md) |  | 
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 
**ApprovedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**DisabledPolicy** | Pointer to [**AccessPolicyDisabledPolicy**](AccessPolicyDisabledPolicy.md) |  | [optional] 
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**ApprovedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to approve the resource. | [optional] 

## Methods

### NewPrincipalPolicy

`func NewPrincipalPolicy(tags map[string]string, userPrincipal string, permissions []ManagedPermissionSetRef, rev string, ) *PrincipalPolicy`

NewPrincipalPolicy instantiates a new PrincipalPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPrincipalPolicyWithDefaults

`func NewPrincipalPolicyWithDefaults() *PrincipalPolicy`

NewPrincipalPolicyWithDefaults instantiates a new PrincipalPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PrincipalPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PrincipalPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PrincipalPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PrincipalPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTags

`func (o *PrincipalPolicy) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PrincipalPolicy) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PrincipalPolicy) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetUpdatedAt

`func (o *PrincipalPolicy) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PrincipalPolicy) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PrincipalPolicy) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PrincipalPolicy) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetUserPrincipal

`func (o *PrincipalPolicy) GetUserPrincipal() string`

GetUserPrincipal returns the UserPrincipal field if non-nil, zero value otherwise.

### GetUserPrincipalOk

`func (o *PrincipalPolicy) GetUserPrincipalOk() (*string, bool)`

GetUserPrincipalOk returns a tuple with the UserPrincipal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserPrincipal

`func (o *PrincipalPolicy) SetUserPrincipal(v string)`

SetUserPrincipal sets UserPrincipal field to given value.


### GetPermissions

`func (o *PrincipalPolicy) GetPermissions() []ManagedPermissionSetRef`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *PrincipalPolicy) GetPermissionsOk() (*[]ManagedPermissionSetRef, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *PrincipalPolicy) SetPermissions(v []ManagedPermissionSetRef)`

SetPermissions sets Permissions field to given value.


### GetCreatedBy

`func (o *PrincipalPolicy) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *PrincipalPolicy) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *PrincipalPolicy) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *PrincipalPolicy) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PrincipalPolicy) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PrincipalPolicy) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PrincipalPolicy) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PrincipalPolicy) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRev

`func (o *PrincipalPolicy) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *PrincipalPolicy) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *PrincipalPolicy) SetRev(v string)`

SetRev sets Rev field to given value.


### GetApprovedAt

`func (o *PrincipalPolicy) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *PrincipalPolicy) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *PrincipalPolicy) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *PrincipalPolicy) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetDisabledPolicy

`func (o *PrincipalPolicy) GetDisabledPolicy() AccessPolicyDisabledPolicy`

GetDisabledPolicy returns the DisabledPolicy field if non-nil, zero value otherwise.

### GetDisabledPolicyOk

`func (o *PrincipalPolicy) GetDisabledPolicyOk() (*AccessPolicyDisabledPolicy, bool)`

GetDisabledPolicyOk returns a tuple with the DisabledPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabledPolicy

`func (o *PrincipalPolicy) SetDisabledPolicy(v AccessPolicyDisabledPolicy)`

SetDisabledPolicy sets DisabledPolicy field to given value.

### HasDisabledPolicy

`func (o *PrincipalPolicy) HasDisabledPolicy() bool`

HasDisabledPolicy returns a boolean if a field has been set.

### GetUpdatedBy

`func (o *PrincipalPolicy) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *PrincipalPolicy) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *PrincipalPolicy) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *PrincipalPolicy) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetApprovedBy

`func (o *PrincipalPolicy) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *PrincipalPolicy) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *PrincipalPolicy) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *PrincipalPolicy) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


