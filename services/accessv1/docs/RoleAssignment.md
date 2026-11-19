# RoleAssignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RoleAssignmentId** | **string** | Uniquely identifies an access policy within a project. | 
**ProjectId** | **string** | Globally unique identifier of a project. | 
**Principal** | [**RoleAssignmentPrincipal**](RoleAssignmentPrincipal.md) |  | 
**RoleId** | **string** | Uniquely identifies an access policy within a project. | 
**RoleName** | **string** | Name of the Role assigned to the principal | 
**AssignmentScope** | [**RoleAssignmentAssignmentScope**](RoleAssignmentAssignmentScope.md) |  | 

## Methods

### NewRoleAssignment

`func NewRoleAssignment(roleAssignmentId string, projectId string, principal RoleAssignmentPrincipal, roleId string, roleName string, assignmentScope RoleAssignmentAssignmentScope, ) *RoleAssignment`

NewRoleAssignment instantiates a new RoleAssignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleAssignmentWithDefaults

`func NewRoleAssignmentWithDefaults() *RoleAssignment`

NewRoleAssignmentWithDefaults instantiates a new RoleAssignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRoleAssignmentId

`func (o *RoleAssignment) GetRoleAssignmentId() string`

GetRoleAssignmentId returns the RoleAssignmentId field if non-nil, zero value otherwise.

### GetRoleAssignmentIdOk

`func (o *RoleAssignment) GetRoleAssignmentIdOk() (*string, bool)`

GetRoleAssignmentIdOk returns a tuple with the RoleAssignmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleAssignmentId

`func (o *RoleAssignment) SetRoleAssignmentId(v string)`

SetRoleAssignmentId sets RoleAssignmentId field to given value.


### GetProjectId

`func (o *RoleAssignment) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *RoleAssignment) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *RoleAssignment) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetPrincipal

`func (o *RoleAssignment) GetPrincipal() RoleAssignmentPrincipal`

GetPrincipal returns the Principal field if non-nil, zero value otherwise.

### GetPrincipalOk

`func (o *RoleAssignment) GetPrincipalOk() (*RoleAssignmentPrincipal, bool)`

GetPrincipalOk returns a tuple with the Principal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrincipal

`func (o *RoleAssignment) SetPrincipal(v RoleAssignmentPrincipal)`

SetPrincipal sets Principal field to given value.


### GetRoleId

`func (o *RoleAssignment) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *RoleAssignment) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *RoleAssignment) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.


### GetRoleName

`func (o *RoleAssignment) GetRoleName() string`

GetRoleName returns the RoleName field if non-nil, zero value otherwise.

### GetRoleNameOk

`func (o *RoleAssignment) GetRoleNameOk() (*string, bool)`

GetRoleNameOk returns a tuple with the RoleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleName

`func (o *RoleAssignment) SetRoleName(v string)`

SetRoleName sets RoleName field to given value.


### GetAssignmentScope

`func (o *RoleAssignment) GetAssignmentScope() RoleAssignmentAssignmentScope`

GetAssignmentScope returns the AssignmentScope field if non-nil, zero value otherwise.

### GetAssignmentScopeOk

`func (o *RoleAssignment) GetAssignmentScopeOk() (*RoleAssignmentAssignmentScope, bool)`

GetAssignmentScopeOk returns a tuple with the AssignmentScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentScope

`func (o *RoleAssignment) SetAssignmentScope(v RoleAssignmentAssignmentScope)`

SetAssignmentScope sets AssignmentScope field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


