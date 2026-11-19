# CreateRoleAssignmentInputAssignmentScope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Type** | **string** | Type of object that defines the scope of a role assignment (e.g. PROJECT, ORGANIZATION). | 
**Parent** | Pointer to [**CreateRoleAssignmentInputAssignmentScopeParent**](CreateRoleAssignmentInputAssignmentScopeParent.md) |  | [optional] 

## Methods

### NewCreateRoleAssignmentInputAssignmentScope

`func NewCreateRoleAssignmentInputAssignmentScope(id string, type_ string, ) *CreateRoleAssignmentInputAssignmentScope`

NewCreateRoleAssignmentInputAssignmentScope instantiates a new CreateRoleAssignmentInputAssignmentScope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateRoleAssignmentInputAssignmentScopeWithDefaults

`func NewCreateRoleAssignmentInputAssignmentScopeWithDefaults() *CreateRoleAssignmentInputAssignmentScope`

NewCreateRoleAssignmentInputAssignmentScopeWithDefaults instantiates a new CreateRoleAssignmentInputAssignmentScope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateRoleAssignmentInputAssignmentScope) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateRoleAssignmentInputAssignmentScope) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateRoleAssignmentInputAssignmentScope) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *CreateRoleAssignmentInputAssignmentScope) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateRoleAssignmentInputAssignmentScope) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateRoleAssignmentInputAssignmentScope) SetType(v string)`

SetType sets Type field to given value.


### GetParent

`func (o *CreateRoleAssignmentInputAssignmentScope) GetParent() CreateRoleAssignmentInputAssignmentScopeParent`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *CreateRoleAssignmentInputAssignmentScope) GetParentOk() (*CreateRoleAssignmentInputAssignmentScopeParent, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *CreateRoleAssignmentInputAssignmentScope) SetParent(v CreateRoleAssignmentInputAssignmentScopeParent)`

SetParent sets Parent field to given value.

### HasParent

`func (o *CreateRoleAssignmentInputAssignmentScope) HasParent() bool`

HasParent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


