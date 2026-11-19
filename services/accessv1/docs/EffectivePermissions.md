# EffectivePermissions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PrincipalId** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. | 
**ProjectId** | **string** | Globally unique identifier of a project. | 
**ServiceId** | **string** | Fully qualified, universally unique id of a service. Starts with the NamespaceId. Formatted like   \&quot;service:&amp;lt;namespace&amp;gt;/&amp;lt;service&amp;gt;\&quot;. | 
**AccessPolicyIds** | Pointer to [**[]ListGrantsAccessPolicyIdParameterOneOf**](ListGrantsAccessPolicyIdParameterOneOf.md) |  | [optional] 
**Permissions** | [**[]EffectivePermissionsPermissionsInner**](EffectivePermissionsPermissionsInner.md) |  | 

## Methods

### NewEffectivePermissions

`func NewEffectivePermissions(principalId string, projectId string, serviceId string, permissions []EffectivePermissionsPermissionsInner, ) *EffectivePermissions`

NewEffectivePermissions instantiates a new EffectivePermissions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEffectivePermissionsWithDefaults

`func NewEffectivePermissionsWithDefaults() *EffectivePermissions`

NewEffectivePermissionsWithDefaults instantiates a new EffectivePermissions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrincipalId

`func (o *EffectivePermissions) GetPrincipalId() string`

GetPrincipalId returns the PrincipalId field if non-nil, zero value otherwise.

### GetPrincipalIdOk

`func (o *EffectivePermissions) GetPrincipalIdOk() (*string, bool)`

GetPrincipalIdOk returns a tuple with the PrincipalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrincipalId

`func (o *EffectivePermissions) SetPrincipalId(v string)`

SetPrincipalId sets PrincipalId field to given value.


### GetProjectId

`func (o *EffectivePermissions) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *EffectivePermissions) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *EffectivePermissions) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetServiceId

`func (o *EffectivePermissions) GetServiceId() string`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *EffectivePermissions) GetServiceIdOk() (*string, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *EffectivePermissions) SetServiceId(v string)`

SetServiceId sets ServiceId field to given value.


### GetAccessPolicyIds

`func (o *EffectivePermissions) GetAccessPolicyIds() []ListGrantsAccessPolicyIdParameterOneOf`

GetAccessPolicyIds returns the AccessPolicyIds field if non-nil, zero value otherwise.

### GetAccessPolicyIdsOk

`func (o *EffectivePermissions) GetAccessPolicyIdsOk() (*[]ListGrantsAccessPolicyIdParameterOneOf, bool)`

GetAccessPolicyIdsOk returns a tuple with the AccessPolicyIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessPolicyIds

`func (o *EffectivePermissions) SetAccessPolicyIds(v []ListGrantsAccessPolicyIdParameterOneOf)`

SetAccessPolicyIds sets AccessPolicyIds field to given value.

### HasAccessPolicyIds

`func (o *EffectivePermissions) HasAccessPolicyIds() bool`

HasAccessPolicyIds returns a boolean if a field has been set.

### GetPermissions

`func (o *EffectivePermissions) GetPermissions() []EffectivePermissionsPermissionsInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *EffectivePermissions) GetPermissionsOk() (*[]EffectivePermissionsPermissionsInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *EffectivePermissions) SetPermissions(v []EffectivePermissionsPermissionsInner)`

SetPermissions sets Permissions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


