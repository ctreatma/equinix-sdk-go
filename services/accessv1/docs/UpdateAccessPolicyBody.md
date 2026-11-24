# UpdateAccessPolicyBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**Permissions** | [**[]UserRectSetInner**](UserRectSetInner.md) | A set of permissions, each of which may be an inline permission, a permission set reference,   or a foreign access policy reference. | 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**AllowBadRefs** | Pointer to [**UpdateAccessPolicyBodyAllowBadRefs**](UpdateAccessPolicyBodyAllowBadRefs.md) |  | [optional] 
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewUpdateAccessPolicyBody

`func NewUpdateAccessPolicyBody(tags map[string]string, permissions []UserRectSetInner, lastRev string, ) *UpdateAccessPolicyBody`

NewUpdateAccessPolicyBody instantiates a new UpdateAccessPolicyBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAccessPolicyBodyWithDefaults

`func NewUpdateAccessPolicyBodyWithDefaults() *UpdateAccessPolicyBody`

NewUpdateAccessPolicyBodyWithDefaults instantiates a new UpdateAccessPolicyBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *UpdateAccessPolicyBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdateAccessPolicyBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdateAccessPolicyBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *UpdateAccessPolicyBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAccessPolicyBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAccessPolicyBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAccessPolicyBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPermissions

`func (o *UpdateAccessPolicyBody) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *UpdateAccessPolicyBody) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *UpdateAccessPolicyBody) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetIntersect

`func (o *UpdateAccessPolicyBody) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *UpdateAccessPolicyBody) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *UpdateAccessPolicyBody) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *UpdateAccessPolicyBody) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *UpdateAccessPolicyBody) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *UpdateAccessPolicyBody) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *UpdateAccessPolicyBody) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *UpdateAccessPolicyBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetAllowBadRefs

`func (o *UpdateAccessPolicyBody) GetAllowBadRefs() UpdateAccessPolicyBodyAllowBadRefs`

GetAllowBadRefs returns the AllowBadRefs field if non-nil, zero value otherwise.

### GetAllowBadRefsOk

`func (o *UpdateAccessPolicyBody) GetAllowBadRefsOk() (*UpdateAccessPolicyBodyAllowBadRefs, bool)`

GetAllowBadRefsOk returns a tuple with the AllowBadRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBadRefs

`func (o *UpdateAccessPolicyBody) SetAllowBadRefs(v UpdateAccessPolicyBodyAllowBadRefs)`

SetAllowBadRefs sets AllowBadRefs field to given value.

### HasAllowBadRefs

`func (o *UpdateAccessPolicyBody) HasAllowBadRefs() bool`

HasAllowBadRefs returns a boolean if a field has been set.

### GetLastRev

`func (o *UpdateAccessPolicyBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *UpdateAccessPolicyBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *UpdateAccessPolicyBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


