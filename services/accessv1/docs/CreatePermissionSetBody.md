# CreatePermissionSetBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**Permissions** | [**[]UserRectSetInner**](UserRectSetInner.md) | A set of permissions, each of which may be an inline permission, a permission set reference,   or a foreign access policy reference. | 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**PermissionSetId** | **string** | Uniquely identifies a PermissionSet within a project. | 
**AllowBadRefs** | Pointer to [**CreatePermissionSetBodyAllowBadRefs**](CreatePermissionSetBodyAllowBadRefs.md) |  | [optional] 

## Methods

### NewCreatePermissionSetBody

`func NewCreatePermissionSetBody(tags map[string]string, permissions []UserRectSetInner, permissionSetId string, ) *CreatePermissionSetBody`

NewCreatePermissionSetBody instantiates a new CreatePermissionSetBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePermissionSetBodyWithDefaults

`func NewCreatePermissionSetBodyWithDefaults() *CreatePermissionSetBody`

NewCreatePermissionSetBodyWithDefaults instantiates a new CreatePermissionSetBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *CreatePermissionSetBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreatePermissionSetBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreatePermissionSetBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *CreatePermissionSetBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreatePermissionSetBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreatePermissionSetBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreatePermissionSetBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPermissions

`func (o *CreatePermissionSetBody) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreatePermissionSetBody) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreatePermissionSetBody) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetIntersect

`func (o *CreatePermissionSetBody) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *CreatePermissionSetBody) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *CreatePermissionSetBody) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *CreatePermissionSetBody) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *CreatePermissionSetBody) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *CreatePermissionSetBody) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *CreatePermissionSetBody) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *CreatePermissionSetBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetPermissionSetId

`func (o *CreatePermissionSetBody) GetPermissionSetId() string`

GetPermissionSetId returns the PermissionSetId field if non-nil, zero value otherwise.

### GetPermissionSetIdOk

`func (o *CreatePermissionSetBody) GetPermissionSetIdOk() (*string, bool)`

GetPermissionSetIdOk returns a tuple with the PermissionSetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionSetId

`func (o *CreatePermissionSetBody) SetPermissionSetId(v string)`

SetPermissionSetId sets PermissionSetId field to given value.


### GetAllowBadRefs

`func (o *CreatePermissionSetBody) GetAllowBadRefs() CreatePermissionSetBodyAllowBadRefs`

GetAllowBadRefs returns the AllowBadRefs field if non-nil, zero value otherwise.

### GetAllowBadRefsOk

`func (o *CreatePermissionSetBody) GetAllowBadRefsOk() (*CreatePermissionSetBodyAllowBadRefs, bool)`

GetAllowBadRefsOk returns a tuple with the AllowBadRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBadRefs

`func (o *CreatePermissionSetBody) SetAllowBadRefs(v CreatePermissionSetBodyAllowBadRefs)`

SetAllowBadRefs sets AllowBadRefs field to given value.

### HasAllowBadRefs

`func (o *CreatePermissionSetBody) HasAllowBadRefs() bool`

HasAllowBadRefs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


