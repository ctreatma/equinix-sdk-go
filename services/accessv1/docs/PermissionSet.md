# PermissionSet

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
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**Managed** | Pointer to [**AccessPolicyDisabledPolicy**](AccessPolicyDisabledPolicy.md) |  | [optional] 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**PermissionSetId** | [**GetPermissionSetPermissionSetIdParameterOneOf**](GetPermissionSetPermissionSetIdParameterOneOf.md) |  | 
**ApprovedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to approve the resource. | [optional] 

## Methods

### NewPermissionSet

`func NewPermissionSet(tags map[string]string, permissions []UserRectSetInner, rev string, ern string, permissionSetId GetPermissionSetPermissionSetIdParameterOneOf, ) *PermissionSet`

NewPermissionSet instantiates a new PermissionSet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPermissionSetWithDefaults

`func NewPermissionSetWithDefaults() *PermissionSet`

NewPermissionSetWithDefaults instantiates a new PermissionSet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PermissionSet) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PermissionSet) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PermissionSet) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PermissionSet) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTags

`func (o *PermissionSet) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PermissionSet) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PermissionSet) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetUpdatedAt

`func (o *PermissionSet) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PermissionSet) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PermissionSet) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PermissionSet) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetPermissions

`func (o *PermissionSet) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *PermissionSet) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *PermissionSet) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetCreatedBy

`func (o *PermissionSet) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *PermissionSet) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *PermissionSet) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *PermissionSet) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PermissionSet) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PermissionSet) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PermissionSet) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PermissionSet) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRev

`func (o *PermissionSet) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *PermissionSet) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *PermissionSet) SetRev(v string)`

SetRev sets Rev field to given value.


### GetApprovedAt

`func (o *PermissionSet) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *PermissionSet) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *PermissionSet) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *PermissionSet) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetErn

`func (o *PermissionSet) GetErn() string`

GetErn returns the Ern field if non-nil, zero value otherwise.

### GetErnOk

`func (o *PermissionSet) GetErnOk() (*string, bool)`

GetErnOk returns a tuple with the Ern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErn

`func (o *PermissionSet) SetErn(v string)`

SetErn sets Ern field to given value.


### GetUpdatedBy

`func (o *PermissionSet) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *PermissionSet) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *PermissionSet) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *PermissionSet) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetManaged

`func (o *PermissionSet) GetManaged() AccessPolicyDisabledPolicy`

GetManaged returns the Managed field if non-nil, zero value otherwise.

### GetManagedOk

`func (o *PermissionSet) GetManagedOk() (*AccessPolicyDisabledPolicy, bool)`

GetManagedOk returns a tuple with the Managed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManaged

`func (o *PermissionSet) SetManaged(v AccessPolicyDisabledPolicy)`

SetManaged sets Managed field to given value.

### HasManaged

`func (o *PermissionSet) HasManaged() bool`

HasManaged returns a boolean if a field has been set.

### GetIntersect

`func (o *PermissionSet) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *PermissionSet) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *PermissionSet) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *PermissionSet) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *PermissionSet) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *PermissionSet) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *PermissionSet) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *PermissionSet) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetPermissionSetId

`func (o *PermissionSet) GetPermissionSetId() GetPermissionSetPermissionSetIdParameterOneOf`

GetPermissionSetId returns the PermissionSetId field if non-nil, zero value otherwise.

### GetPermissionSetIdOk

`func (o *PermissionSet) GetPermissionSetIdOk() (*GetPermissionSetPermissionSetIdParameterOneOf, bool)`

GetPermissionSetIdOk returns a tuple with the PermissionSetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionSetId

`func (o *PermissionSet) SetPermissionSetId(v GetPermissionSetPermissionSetIdParameterOneOf)`

SetPermissionSetId sets PermissionSetId field to given value.


### GetApprovedBy

`func (o *PermissionSet) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *PermissionSet) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *PermissionSet) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *PermissionSet) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


