# RoleAssignmentAssignmentScopeParent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Id the project that owns this port | 
**Type** | [**CreateRoleAssignmentInputAssignmentScopeParentType**](CreateRoleAssignmentInputAssignmentScopeParentType.md) |  | 
**Name** | Pointer to **string** | Name of object refered to by assignmentScope id | [optional] 

## Methods

### NewRoleAssignmentAssignmentScopeParent

`func NewRoleAssignmentAssignmentScopeParent(id string, type_ CreateRoleAssignmentInputAssignmentScopeParentType, ) *RoleAssignmentAssignmentScopeParent`

NewRoleAssignmentAssignmentScopeParent instantiates a new RoleAssignmentAssignmentScopeParent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoleAssignmentAssignmentScopeParentWithDefaults

`func NewRoleAssignmentAssignmentScopeParentWithDefaults() *RoleAssignmentAssignmentScopeParent`

NewRoleAssignmentAssignmentScopeParentWithDefaults instantiates a new RoleAssignmentAssignmentScopeParent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RoleAssignmentAssignmentScopeParent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RoleAssignmentAssignmentScopeParent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RoleAssignmentAssignmentScopeParent) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *RoleAssignmentAssignmentScopeParent) GetType() CreateRoleAssignmentInputAssignmentScopeParentType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoleAssignmentAssignmentScopeParent) GetTypeOk() (*CreateRoleAssignmentInputAssignmentScopeParentType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoleAssignmentAssignmentScopeParent) SetType(v CreateRoleAssignmentInputAssignmentScopeParentType)`

SetType sets Type field to given value.


### GetName

`func (o *RoleAssignmentAssignmentScopeParent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RoleAssignmentAssignmentScopeParent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RoleAssignmentAssignmentScopeParent) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RoleAssignmentAssignmentScopeParent) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


