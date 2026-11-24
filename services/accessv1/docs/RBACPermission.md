# RBACPermission

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Permission** | **string** |  | 
**PermissionResourceType** | **string** |  | 

## Methods

### NewRBACPermission

`func NewRBACPermission(permission string, permissionResourceType string, ) *RBACPermission`

NewRBACPermission instantiates a new RBACPermission object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRBACPermissionWithDefaults

`func NewRBACPermissionWithDefaults() *RBACPermission`

NewRBACPermissionWithDefaults instantiates a new RBACPermission object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermission

`func (o *RBACPermission) GetPermission() string`

GetPermission returns the Permission field if non-nil, zero value otherwise.

### GetPermissionOk

`func (o *RBACPermission) GetPermissionOk() (*string, bool)`

GetPermissionOk returns a tuple with the Permission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermission

`func (o *RBACPermission) SetPermission(v string)`

SetPermission sets Permission field to given value.


### GetPermissionResourceType

`func (o *RBACPermission) GetPermissionResourceType() string`

GetPermissionResourceType returns the PermissionResourceType field if non-nil, zero value otherwise.

### GetPermissionResourceTypeOk

`func (o *RBACPermission) GetPermissionResourceTypeOk() (*string, bool)`

GetPermissionResourceTypeOk returns a tuple with the PermissionResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionResourceType

`func (o *RBACPermission) SetPermissionResourceType(v string)`

SetPermissionResourceType sets PermissionResourceType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


