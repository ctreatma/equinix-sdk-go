# UpdatePrincipalPolicyBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Permissions** | [**[]ManagedPermissionSetRef**](ManagedPermissionSetRef.md) |  | 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**Description** | Pointer to **string** |  | [optional] 
**AllowBadRefs** | Pointer to [**UpdatePrincipalPolicyBodyAllowBadRefs**](UpdatePrincipalPolicyBodyAllowBadRefs.md) |  | [optional] 
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewUpdatePrincipalPolicyBody

`func NewUpdatePrincipalPolicyBody(permissions []ManagedPermissionSetRef, tags map[string]string, lastRev string, ) *UpdatePrincipalPolicyBody`

NewUpdatePrincipalPolicyBody instantiates a new UpdatePrincipalPolicyBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePrincipalPolicyBodyWithDefaults

`func NewUpdatePrincipalPolicyBodyWithDefaults() *UpdatePrincipalPolicyBody`

NewUpdatePrincipalPolicyBodyWithDefaults instantiates a new UpdatePrincipalPolicyBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissions

`func (o *UpdatePrincipalPolicyBody) GetPermissions() []ManagedPermissionSetRef`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *UpdatePrincipalPolicyBody) GetPermissionsOk() (*[]ManagedPermissionSetRef, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *UpdatePrincipalPolicyBody) SetPermissions(v []ManagedPermissionSetRef)`

SetPermissions sets Permissions field to given value.


### GetTags

`func (o *UpdatePrincipalPolicyBody) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdatePrincipalPolicyBody) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdatePrincipalPolicyBody) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetDescription

`func (o *UpdatePrincipalPolicyBody) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdatePrincipalPolicyBody) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdatePrincipalPolicyBody) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdatePrincipalPolicyBody) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetAllowBadRefs

`func (o *UpdatePrincipalPolicyBody) GetAllowBadRefs() UpdatePrincipalPolicyBodyAllowBadRefs`

GetAllowBadRefs returns the AllowBadRefs field if non-nil, zero value otherwise.

### GetAllowBadRefsOk

`func (o *UpdatePrincipalPolicyBody) GetAllowBadRefsOk() (*UpdatePrincipalPolicyBodyAllowBadRefs, bool)`

GetAllowBadRefsOk returns a tuple with the AllowBadRefs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowBadRefs

`func (o *UpdatePrincipalPolicyBody) SetAllowBadRefs(v UpdatePrincipalPolicyBodyAllowBadRefs)`

SetAllowBadRefs sets AllowBadRefs field to given value.

### HasAllowBadRefs

`func (o *UpdatePrincipalPolicyBody) HasAllowBadRefs() bool`

HasAllowBadRefs returns a boolean if a field has been set.

### GetLastRev

`func (o *UpdatePrincipalPolicyBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *UpdatePrincipalPolicyBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *UpdatePrincipalPolicyBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


