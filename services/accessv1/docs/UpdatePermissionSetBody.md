# UpdatePermissionSetBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**Permissions** | [**[]UserRectSetInner**](UserRectSetInner.md) | A set of permissions, each of which may be an inline permission, a permission set reference,   or a foreign access policy reference. | 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**AllowBadRefs** | Pointer to [**UpdatePermissionSetBodyAllowBadRefs**](UpdatePermissionSetBodyAllowBadRefs.md) |  | [optional] 
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewUpdatePermissionSetBody

`func NewUpdatePermissionSetBody(tags map[string]string, permissions []UserRectSetInner, lastRev string, ) *UpdatePermissionSetBody`

NewUpdatePermissionSetBody instantiates a new UpdatePermissionSetBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePermissionSetBodyWithDefaults

`func NewUpdatePermissionSetBodyWithDefaults() *UpdatePermissionSetBody`

NewUpdatePermissionSetBodyWithDefaults instantiates a new UpdatePermissionSetBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *UpdatePermissionSetBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdatePermissionSetBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdatePermissionSetBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *UpdatePermissionSetBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdatePermissionSetBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdatePermissionSetBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdatePermissionSetBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPermissions

`func (o *UpdatePermissionSetBody) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *UpdatePermissionSetBody) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *UpdatePermissionSetBody) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetIntersect

`func (o *UpdatePermissionSetBody) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *UpdatePermissionSetBody) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *UpdatePermissionSetBody) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *UpdatePermissionSetBody) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *UpdatePermissionSetBody) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *UpdatePermissionSetBody) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *UpdatePermissionSetBody) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *UpdatePermissionSetBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetAllowBadRefs

`func (o *UpdatePermissionSetBody) GetAllowBadRefs() UpdatePermissionSetBodyAllowBadRefs`

GetAllowBadRefs returns the AllowBadRefs field if non-nil, zero value otherwise.

### GetAllowBadRefsOk

`func (o *UpdatePermissionSetBody) GetAllowBadRefsOk() (*UpdatePermissionSetBodyAllowBadRefs, bool)`

GetAllowBadRefsOk returns a tuple with the AllowBadRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBadRefs

`func (o *UpdatePermissionSetBody) SetAllowBadRefs(v UpdatePermissionSetBodyAllowBadRefs)`

SetAllowBadRefs sets AllowBadRefs field to given value.

### HasAllowBadRefs

`func (o *UpdatePermissionSetBody) HasAllowBadRefs() bool`

HasAllowBadRefs returns a boolean if a field has been set.

### GetLastRev

`func (o *UpdatePermissionSetBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *UpdatePermissionSetBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *UpdatePermissionSetBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


