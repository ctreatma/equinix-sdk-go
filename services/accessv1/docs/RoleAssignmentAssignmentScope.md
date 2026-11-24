# RoleAssignmentAssignmentScope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Type** | **string** | Type of object that defines the scope of a role assignment (e.g. PROJECT, ORGANIZATION). | 
**Name** | Pointer to **string** | Name of object refered to by assignmentScope id | [optional] 
**Parent** | Pointer to [**RoleAssignmentAssignmentScopeParent**](RoleAssignmentAssignmentScopeParent.md) |  | [optional] 

## Methods

### NewRoleAssignmentAssignmentScope

`func NewRoleAssignmentAssignmentScope(id string, type_ string, ) *RoleAssignmentAssignmentScope`

NewRoleAssignmentAssignmentScope instantiates a new RoleAssignmentAssignmentScope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleAssignmentAssignmentScopeWithDefaults

`func NewRoleAssignmentAssignmentScopeWithDefaults() *RoleAssignmentAssignmentScope`

NewRoleAssignmentAssignmentScopeWithDefaults instantiates a new RoleAssignmentAssignmentScope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RoleAssignmentAssignmentScope) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RoleAssignmentAssignmentScope) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RoleAssignmentAssignmentScope) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *RoleAssignmentAssignmentScope) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoleAssignmentAssignmentScope) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoleAssignmentAssignmentScope) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *RoleAssignmentAssignmentScope) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleAssignmentAssignmentScope) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleAssignmentAssignmentScope) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoleAssignmentAssignmentScope) HasName() bool`

HasName returns a boolean if a field has been set.

### GetParent

`func (o *RoleAssignmentAssignmentScope) GetParent() RoleAssignmentAssignmentScopeParent`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *RoleAssignmentAssignmentScope) GetParentOk() (*RoleAssignmentAssignmentScopeParent, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *RoleAssignmentAssignmentScope) SetParent(v RoleAssignmentAssignmentScopeParent)`

SetParent sets Parent field to given value.

### HasParent

`func (o *RoleAssignmentAssignmentScope) HasParent() bool`

HasParent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


