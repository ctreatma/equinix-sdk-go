# RoleDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RoleId** | **string** | Uniquely identifies an access policy within a project. | 
**Name** | **string** |  | 
**Description** | **NullableString** |  | 
**AssignmentScopeTypes** | **[]string** | This Role may be assigned to a scope of any of these types. | 
**Permissions** | [**[]RoleDetailsPermissionsInner**](RoleDetailsPermissionsInner.md) | List of permissions assigned to this role | 

## Methods

### NewRoleDetails

`func NewRoleDetails(roleId string, name string, description NullableString, assignmentScopeTypes []string, permissions []RoleDetailsPermissionsInner, ) *RoleDetails`

NewRoleDetails instantiates a new RoleDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleDetailsWithDefaults

`func NewRoleDetailsWithDefaults() *RoleDetails`

NewRoleDetailsWithDefaults instantiates a new RoleDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRoleId

`func (o *RoleDetails) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *RoleDetails) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *RoleDetails) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.


### GetName

`func (o *RoleDetails) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleDetails) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleDetails) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *RoleDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *RoleDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *RoleDetails) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *RoleDetails) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *RoleDetails) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAssignmentScopeTypes

`func (o *RoleDetails) GetAssignmentScopeTypes() []string`

GetAssignmentScopeTypes returns the AssignmentScopeTypes field if non-nil, zero value otherwise.

### GetAssignmentScopeTypesOk

`func (o *RoleDetails) GetAssignmentScopeTypesOk() (*[]string, bool)`

GetAssignmentScopeTypesOk returns a tuple with the AssignmentScopeTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentScopeTypes

`func (o *RoleDetails) SetAssignmentScopeTypes(v []string)`

SetAssignmentScopeTypes sets AssignmentScopeTypes field to given value.


### GetPermissions

`func (o *RoleDetails) GetPermissions() []RoleDetailsPermissionsInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *RoleDetails) GetPermissionsOk() (*[]RoleDetailsPermissionsInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *RoleDetails) SetPermissions(v []RoleDetailsPermissionsInner)`

SetPermissions sets Permissions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


