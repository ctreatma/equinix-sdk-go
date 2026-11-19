# AccessPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**UpdatedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Permissions** | [**[]UserRectSetInner**](UserRectSetInner.md) | A set of permissions, each of which may be an inline permission, a permission set reference,   or a foreign access policy reference. | 
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 
**ApprovedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Ern** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**DisabledPolicy** | Pointer to [**AccessPolicyDisabledPolicy**](AccessPolicyDisabledPolicy.md) |  | [optional] 
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**Managed** | Pointer to [**AccessPolicyDisabledPolicy**](AccessPolicyDisabledPolicy.md) |  | [optional] 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**AccessPolicyId** | [**ListGrantsAccessPolicyIdParameterOneOf**](ListGrantsAccessPolicyIdParameterOneOf.md) |  | 
**ApprovedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to approve the resource. | [optional] 

## Methods

### NewAccessPolicy

`func NewAccessPolicy(tags map[string]string, permissions []UserRectSetInner, rev string, ern string, accessPolicyId ListGrantsAccessPolicyIdParameterOneOf, ) *AccessPolicy`

NewAccessPolicy instantiates a new AccessPolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPolicyWithDefaults

`func NewAccessPolicyWithDefaults() *AccessPolicy`

NewAccessPolicyWithDefaults instantiates a new AccessPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *AccessPolicy) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccessPolicy) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccessPolicy) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccessPolicy) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTags

`func (o *AccessPolicy) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *AccessPolicy) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *AccessPolicy) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetUpdatedAt

`func (o *AccessPolicy) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AccessPolicy) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AccessPolicy) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *AccessPolicy) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetPermissions

`func (o *AccessPolicy) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *AccessPolicy) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *AccessPolicy) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetCreatedBy

`func (o *AccessPolicy) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *AccessPolicy) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *AccessPolicy) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *AccessPolicy) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *AccessPolicy) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AccessPolicy) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AccessPolicy) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AccessPolicy) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRev

`func (o *AccessPolicy) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *AccessPolicy) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *AccessPolicy) SetRev(v string)`

SetRev sets Rev field to given value.


### GetApprovedAt

`func (o *AccessPolicy) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *AccessPolicy) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *AccessPolicy) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *AccessPolicy) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetErn

`func (o *AccessPolicy) GetErn() string`

GetErn returns the Ern field if non-nil, zero value otherwise.

### GetErnOk

`func (o *AccessPolicy) GetErnOk() (*string, bool)`

GetErnOk returns a tuple with the Ern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErn

`func (o *AccessPolicy) SetErn(v string)`

SetErn sets Ern field to given value.


### GetDisabledPolicy

`func (o *AccessPolicy) GetDisabledPolicy() AccessPolicyDisabledPolicy`

GetDisabledPolicy returns the DisabledPolicy field if non-nil, zero value otherwise.

### GetDisabledPolicyOk

`func (o *AccessPolicy) GetDisabledPolicyOk() (*AccessPolicyDisabledPolicy, bool)`

GetDisabledPolicyOk returns a tuple with the DisabledPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabledPolicy

`func (o *AccessPolicy) SetDisabledPolicy(v AccessPolicyDisabledPolicy)`

SetDisabledPolicy sets DisabledPolicy field to given value.

### HasDisabledPolicy

`func (o *AccessPolicy) HasDisabledPolicy() bool`

HasDisabledPolicy returns a boolean if a field has been set.

### GetUpdatedBy

`func (o *AccessPolicy) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *AccessPolicy) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *AccessPolicy) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *AccessPolicy) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetManaged

`func (o *AccessPolicy) GetManaged() AccessPolicyDisabledPolicy`

GetManaged returns the Managed field if non-nil, zero value otherwise.

### GetManagedOk

`func (o *AccessPolicy) GetManagedOk() (*AccessPolicyDisabledPolicy, bool)`

GetManagedOk returns a tuple with the Managed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManaged

`func (o *AccessPolicy) SetManaged(v AccessPolicyDisabledPolicy)`

SetManaged sets Managed field to given value.

### HasManaged

`func (o *AccessPolicy) HasManaged() bool`

HasManaged returns a boolean if a field has been set.

### GetIntersect

`func (o *AccessPolicy) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *AccessPolicy) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *AccessPolicy) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *AccessPolicy) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *AccessPolicy) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *AccessPolicy) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *AccessPolicy) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *AccessPolicy) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetAccessPolicyId

`func (o *AccessPolicy) GetAccessPolicyId() ListGrantsAccessPolicyIdParameterOneOf`

GetAccessPolicyId returns the AccessPolicyId field if non-nil, zero value otherwise.

### GetAccessPolicyIdOk

`func (o *AccessPolicy) GetAccessPolicyIdOk() (*ListGrantsAccessPolicyIdParameterOneOf, bool)`

GetAccessPolicyIdOk returns a tuple with the AccessPolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessPolicyId

`func (o *AccessPolicy) SetAccessPolicyId(v ListGrantsAccessPolicyIdParameterOneOf)`

SetAccessPolicyId sets AccessPolicyId field to given value.


### GetApprovedBy

`func (o *AccessPolicy) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *AccessPolicy) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *AccessPolicy) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *AccessPolicy) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


