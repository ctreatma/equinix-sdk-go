# ListedAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceAspect** | [**ServiceAspect**](ServiceAspect.md) |  | 
**RbacPermission** | Pointer to [**RBACPermission**](RBACPermission.md) |  | [optional] 
**PermissionCodes** | Pointer to [**map[string]ListedActionPermissionCodesValue**](ListedActionPermissionCodesValue.md) |  | [optional] 
**Attributes** | Pointer to [**AttributeSet**](AttributeSet.md) | Identify the attributes which are included on this action. | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**ActionId** | **string** | Id of an action, unique across all aspects of its service | 

## Methods

### NewListedAction

`func NewListedAction(serviceAspect ServiceAspect, tags map[string]string, actionId string, ) *ListedAction`

NewListedAction instantiates a new ListedAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListedActionWithDefaults

`func NewListedActionWithDefaults() *ListedAction`

NewListedActionWithDefaults instantiates a new ListedAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceAspect

`func (o *ListedAction) GetServiceAspect() ServiceAspect`

GetServiceAspect returns the ServiceAspect field if non-nil, zero value otherwise.

### GetServiceAspectOk

`func (o *ListedAction) GetServiceAspectOk() (*ServiceAspect, bool)`

GetServiceAspectOk returns a tuple with the ServiceAspect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceAspect

`func (o *ListedAction) SetServiceAspect(v ServiceAspect)`

SetServiceAspect sets ServiceAspect field to given value.


### GetRbacPermission

`func (o *ListedAction) GetRbacPermission() RBACPermission`

GetRbacPermission returns the RbacPermission field if non-nil, zero value otherwise.

### GetRbacPermissionOk

`func (o *ListedAction) GetRbacPermissionOk() (*RBACPermission, bool)`

GetRbacPermissionOk returns a tuple with the RbacPermission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRbacPermission

`func (o *ListedAction) SetRbacPermission(v RBACPermission)`

SetRbacPermission sets RbacPermission field to given value.

### HasRbacPermission

`func (o *ListedAction) HasRbacPermission() bool`

HasRbacPermission returns a boolean if a field has been set.

### GetPermissionCodes

`func (o *ListedAction) GetPermissionCodes() map[string]ListedActionPermissionCodesValue`

GetPermissionCodes returns the PermissionCodes field if non-nil, zero value otherwise.

### GetPermissionCodesOk

`func (o *ListedAction) GetPermissionCodesOk() (*map[string]ListedActionPermissionCodesValue, bool)`

GetPermissionCodesOk returns a tuple with the PermissionCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionCodes

`func (o *ListedAction) SetPermissionCodes(v map[string]ListedActionPermissionCodesValue)`

SetPermissionCodes sets PermissionCodes field to given value.

### HasPermissionCodes

`func (o *ListedAction) HasPermissionCodes() bool`

HasPermissionCodes returns a boolean if a field has been set.

### GetAttributes

`func (o *ListedAction) GetAttributes() AttributeSet`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *ListedAction) GetAttributesOk() (*AttributeSet, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *ListedAction) SetAttributes(v AttributeSet)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *ListedAction) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.

### GetTags

`func (o *ListedAction) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ListedAction) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ListedAction) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetActionId

`func (o *ListedAction) GetActionId() string`

GetActionId returns the ActionId field if non-nil, zero value otherwise.

### GetActionIdOk

`func (o *ListedAction) GetActionIdOk() (*string, bool)`

GetActionIdOk returns a tuple with the ActionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionId

`func (o *ListedAction) SetActionId(v string)`

SetActionId sets ActionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


