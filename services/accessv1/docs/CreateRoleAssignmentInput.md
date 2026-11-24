# CreateRoleAssignmentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Principal** | **string** | Globally unique string identifier for a principal formatted like \&quot;principal:...\&quot;. | 
**RoleId** | **string** | Uniquely identifies an access policy within a project. | 
**AssignmentScope** | [**CreateRoleAssignmentInputAssignmentScope**](CreateRoleAssignmentInputAssignmentScope.md) |  | 

## Methods

### NewCreateRoleAssignmentInput

`func NewCreateRoleAssignmentInput(principal string, roleId string, assignmentScope CreateRoleAssignmentInputAssignmentScope, ) *CreateRoleAssignmentInput`

NewCreateRoleAssignmentInput instantiates a new CreateRoleAssignmentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateRoleAssignmentInputWithDefaults

`func NewCreateRoleAssignmentInputWithDefaults() *CreateRoleAssignmentInput`

NewCreateRoleAssignmentInputWithDefaults instantiates a new CreateRoleAssignmentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrincipal

`func (o *CreateRoleAssignmentInput) GetPrincipal() string`

GetPrincipal returns the Principal field if non-nil, zero value otherwise.

### GetPrincipalOk

`func (o *CreateRoleAssignmentInput) GetPrincipalOk() (*string, bool)`

GetPrincipalOk returns a tuple with the Principal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrincipal

`func (o *CreateRoleAssignmentInput) SetPrincipal(v string)`

SetPrincipal sets Principal field to given value.


### GetRoleId

`func (o *CreateRoleAssignmentInput) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *CreateRoleAssignmentInput) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *CreateRoleAssignmentInput) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.


### GetAssignmentScope

`func (o *CreateRoleAssignmentInput) GetAssignmentScope() CreateRoleAssignmentInputAssignmentScope`

GetAssignmentScope returns the AssignmentScope field if non-nil, zero value otherwise.

### GetAssignmentScopeOk

`func (o *CreateRoleAssignmentInput) GetAssignmentScopeOk() (*CreateRoleAssignmentInputAssignmentScope, bool)`

GetAssignmentScopeOk returns a tuple with the AssignmentScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignmentScope

`func (o *CreateRoleAssignmentInput) SetAssignmentScope(v CreateRoleAssignmentInputAssignmentScope)`

SetAssignmentScope sets AssignmentScope field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


