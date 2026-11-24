# UserRectSetInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resources** | [**InlinePermissionResources**](InlinePermissionResources.md) |  | 
**ServiceActions** | [**InlinePermissionServiceActions**](InlinePermissionServiceActions.md) |  | 
**Condition** | Pointer to **string** |  | [optional] 
**IbxLocationCondition** | Pointer to [**IbxLocationCondition**](IbxLocationCondition.md) |  | [optional] 
**ForeignAccessPolicy** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**PermissionSet** | [**GeneralPermissionSetRefPermissionSet**](GeneralPermissionSetRefPermissionSet.md) |  | 

## Methods

### NewUserRectSetInner

`func NewUserRectSetInner(resources InlinePermissionResources, serviceActions InlinePermissionServiceActions, foreignAccessPolicy string, permissionSet GeneralPermissionSetRefPermissionSet, ) *UserRectSetInner`

NewUserRectSetInner instantiates a new UserRectSetInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserRectSetInnerWithDefaults

`func NewUserRectSetInnerWithDefaults() *UserRectSetInner`

NewUserRectSetInnerWithDefaults instantiates a new UserRectSetInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResources

`func (o *UserRectSetInner) GetResources() InlinePermissionResources`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *UserRectSetInner) GetResourcesOk() (*InlinePermissionResources, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *UserRectSetInner) SetResources(v InlinePermissionResources)`

SetResources sets Resources field to given value.


### GetServiceActions

`func (o *UserRectSetInner) GetServiceActions() InlinePermissionServiceActions`

GetServiceActions returns the ServiceActions field if non-nil, zero value otherwise.

### GetServiceActionsOk

`func (o *UserRectSetInner) GetServiceActionsOk() (*InlinePermissionServiceActions, bool)`

GetServiceActionsOk returns a tuple with the ServiceActions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceActions

`func (o *UserRectSetInner) SetServiceActions(v InlinePermissionServiceActions)`

SetServiceActions sets ServiceActions field to given value.


### GetCondition

`func (o *UserRectSetInner) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *UserRectSetInner) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *UserRectSetInner) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *UserRectSetInner) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetIbxLocationCondition

`func (o *UserRectSetInner) GetIbxLocationCondition() IbxLocationCondition`

GetIbxLocationCondition returns the IbxLocationCondition field if non-nil, zero value otherwise.

### GetIbxLocationConditionOk

`func (o *UserRectSetInner) GetIbxLocationConditionOk() (*IbxLocationCondition, bool)`

GetIbxLocationConditionOk returns a tuple with the IbxLocationCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocationCondition

`func (o *UserRectSetInner) SetIbxLocationCondition(v IbxLocationCondition)`

SetIbxLocationCondition sets IbxLocationCondition field to given value.

### HasIbxLocationCondition

`func (o *UserRectSetInner) HasIbxLocationCondition() bool`

HasIbxLocationCondition returns a boolean if a field has been set.

### GetForeignAccessPolicy

`func (o *UserRectSetInner) GetForeignAccessPolicy() string`

GetForeignAccessPolicy returns the ForeignAccessPolicy field if non-nil, zero value otherwise.

### GetForeignAccessPolicyOk

`func (o *UserRectSetInner) GetForeignAccessPolicyOk() (*string, bool)`

GetForeignAccessPolicyOk returns a tuple with the ForeignAccessPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignAccessPolicy

`func (o *UserRectSetInner) SetForeignAccessPolicy(v string)`

SetForeignAccessPolicy sets ForeignAccessPolicy field to given value.


### GetPermissionSet

`func (o *UserRectSetInner) GetPermissionSet() GeneralPermissionSetRefPermissionSet`

GetPermissionSet returns the PermissionSet field if non-nil, zero value otherwise.

### GetPermissionSetOk

`func (o *UserRectSetInner) GetPermissionSetOk() (*GeneralPermissionSetRefPermissionSet, bool)`

GetPermissionSetOk returns a tuple with the PermissionSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionSet

`func (o *UserRectSetInner) SetPermissionSet(v GeneralPermissionSetRefPermissionSet)`

SetPermissionSet sets PermissionSet field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


