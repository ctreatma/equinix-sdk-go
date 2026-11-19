# CreateAccessPolicyBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**Permissions** | [**[]UserRectSetInner**](UserRectSetInner.md) | A set of permissions, each of which may be an inline permission, a permission set reference,   or a foreign access policy reference. | 
**Intersect** | Pointer to [**[]UserRectSetInner**](UserRectSetInner.md) | Entries must appear in both the &#x60;intersect&#x60; field and the &#x60;permissions&#x60; to be in the                 results from this permission object. | [optional] 
**Subtract** | Pointer to [**[]InlinePermission**](InlinePermission.md) | Entries in the &#x60;subtract&#x60; field are not included in the results from this permission                object. | [optional] 
**AccessPolicyId** | **string** | Uniquely identifies an access policy within a project. | 
**AllowBadRefs** | Pointer to [**CreateAccessPolicyBodyAllowBadRefs**](CreateAccessPolicyBodyAllowBadRefs.md) |  | [optional] 

## Methods

### NewCreateAccessPolicyBody

`func NewCreateAccessPolicyBody(tags map[string]string, permissions []UserRectSetInner, accessPolicyId string, ) *CreateAccessPolicyBody`

NewCreateAccessPolicyBody instantiates a new CreateAccessPolicyBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAccessPolicyBodyWithDefaults

`func NewCreateAccessPolicyBodyWithDefaults() *CreateAccessPolicyBody`

NewCreateAccessPolicyBodyWithDefaults instantiates a new CreateAccessPolicyBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *CreateAccessPolicyBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreateAccessPolicyBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreateAccessPolicyBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *CreateAccessPolicyBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAccessPolicyBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAccessPolicyBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAccessPolicyBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPermissions

`func (o *CreateAccessPolicyBody) GetPermissions() []UserRectSetInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateAccessPolicyBody) GetPermissionsOk() (*[]UserRectSetInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateAccessPolicyBody) SetPermissions(v []UserRectSetInner)`

SetPermissions sets Permissions field to given value.


### GetIntersect

`func (o *CreateAccessPolicyBody) GetIntersect() []UserRectSetInner`

GetIntersect returns the Intersect field if non-nil, zero value otherwise.

### GetIntersectOk

`func (o *CreateAccessPolicyBody) GetIntersectOk() (*[]UserRectSetInner, bool)`

GetIntersectOk returns a tuple with the Intersect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntersect

`func (o *CreateAccessPolicyBody) SetIntersect(v []UserRectSetInner)`

SetIntersect sets Intersect field to given value.

### HasIntersect

`func (o *CreateAccessPolicyBody) HasIntersect() bool`

HasIntersect returns a boolean if a field has been set.

### GetSubtract

`func (o *CreateAccessPolicyBody) GetSubtract() []InlinePermission`

GetSubtract returns the Subtract field if non-nil, zero value otherwise.

### GetSubtractOk

`func (o *CreateAccessPolicyBody) GetSubtractOk() (*[]InlinePermission, bool)`

GetSubtractOk returns a tuple with the Subtract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtract

`func (o *CreateAccessPolicyBody) SetSubtract(v []InlinePermission)`

SetSubtract sets Subtract field to given value.

### HasSubtract

`func (o *CreateAccessPolicyBody) HasSubtract() bool`

HasSubtract returns a boolean if a field has been set.

### GetAccessPolicyId

`func (o *CreateAccessPolicyBody) GetAccessPolicyId() string`

GetAccessPolicyId returns the AccessPolicyId field if non-nil, zero value otherwise.

### GetAccessPolicyIdOk

`func (o *CreateAccessPolicyBody) GetAccessPolicyIdOk() (*string, bool)`

GetAccessPolicyIdOk returns a tuple with the AccessPolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessPolicyId

`func (o *CreateAccessPolicyBody) SetAccessPolicyId(v string)`

SetAccessPolicyId sets AccessPolicyId field to given value.


### GetAllowBadRefs

`func (o *CreateAccessPolicyBody) GetAllowBadRefs() CreateAccessPolicyBodyAllowBadRefs`

GetAllowBadRefs returns the AllowBadRefs field if non-nil, zero value otherwise.

### GetAllowBadRefsOk

`func (o *CreateAccessPolicyBody) GetAllowBadRefsOk() (*CreateAccessPolicyBodyAllowBadRefs, bool)`

GetAllowBadRefsOk returns a tuple with the AllowBadRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBadRefs

`func (o *CreateAccessPolicyBody) SetAllowBadRefs(v CreateAccessPolicyBodyAllowBadRefs)`

SetAllowBadRefs sets AllowBadRefs field to given value.

### HasAllowBadRefs

`func (o *CreateAccessPolicyBody) HasAllowBadRefs() bool`

HasAllowBadRefs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


