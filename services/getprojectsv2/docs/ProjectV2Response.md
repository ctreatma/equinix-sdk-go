# ProjectV2Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | Pointer to **string** | Project id | [optional] 
**ProjectName** | Pointer to **string** | Project name | [optional] 
**InboxResource** | Pointer to **bool** | Inbox project or not | [optional] 
**ParentOrganizationId** | Pointer to **string** | Parent organization id | [optional] 
**Labels** | Pointer to **map[string]string** | Resource Labels as JSON key, value pairs | [optional] 
**SilentProject** | Pointer to **bool** | Whether the returned project is a SILENT project or not | [optional] 
**Permissions** | Pointer to [**[]ProjectV2ResponsePermissionsInner**](ProjectV2ResponsePermissionsInner.md) | Available user permissions on the project resource, if requested by query param | [optional] 

## Methods

### NewProjectV2Response

`func NewProjectV2Response() *ProjectV2Response`

NewProjectV2Response instantiates a new ProjectV2Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectV2ResponseWithDefaults

`func NewProjectV2ResponseWithDefaults() *ProjectV2Response`

NewProjectV2ResponseWithDefaults instantiates a new ProjectV2Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjectId

`func (o *ProjectV2Response) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectV2Response) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectV2Response) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ProjectV2Response) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProjectName

`func (o *ProjectV2Response) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *ProjectV2Response) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *ProjectV2Response) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.

### HasProjectName

`func (o *ProjectV2Response) HasProjectName() bool`

HasProjectName returns a boolean if a field has been set.

### GetInboxResource

`func (o *ProjectV2Response) GetInboxResource() bool`

GetInboxResource returns the InboxResource field if non-nil, zero value otherwise.

### GetInboxResourceOk

`func (o *ProjectV2Response) GetInboxResourceOk() (*bool, bool)`

GetInboxResourceOk returns a tuple with the InboxResource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInboxResource

`func (o *ProjectV2Response) SetInboxResource(v bool)`

SetInboxResource sets InboxResource field to given value.

### HasInboxResource

`func (o *ProjectV2Response) HasInboxResource() bool`

HasInboxResource returns a boolean if a field has been set.

### GetParentOrganizationId

`func (o *ProjectV2Response) GetParentOrganizationId() string`

GetParentOrganizationId returns the ParentOrganizationId field if non-nil, zero value otherwise.

### GetParentOrganizationIdOk

`func (o *ProjectV2Response) GetParentOrganizationIdOk() (*string, bool)`

GetParentOrganizationIdOk returns a tuple with the ParentOrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentOrganizationId

`func (o *ProjectV2Response) SetParentOrganizationId(v string)`

SetParentOrganizationId sets ParentOrganizationId field to given value.

### HasParentOrganizationId

`func (o *ProjectV2Response) HasParentOrganizationId() bool`

HasParentOrganizationId returns a boolean if a field has been set.

### GetLabels

`func (o *ProjectV2Response) GetLabels() map[string]string`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *ProjectV2Response) GetLabelsOk() (*map[string]string, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *ProjectV2Response) SetLabels(v map[string]string)`

SetLabels sets Labels field to given value.

### HasLabels

`func (o *ProjectV2Response) HasLabels() bool`

HasLabels returns a boolean if a field has been set.

### GetSilentProject

`func (o *ProjectV2Response) GetSilentProject() bool`

GetSilentProject returns the SilentProject field if non-nil, zero value otherwise.

### GetSilentProjectOk

`func (o *ProjectV2Response) GetSilentProjectOk() (*bool, bool)`

GetSilentProjectOk returns a tuple with the SilentProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSilentProject

`func (o *ProjectV2Response) SetSilentProject(v bool)`

SetSilentProject sets SilentProject field to given value.

### HasSilentProject

`func (o *ProjectV2Response) HasSilentProject() bool`

HasSilentProject returns a boolean if a field has been set.

### GetPermissions

`func (o *ProjectV2Response) GetPermissions() []ProjectV2ResponsePermissionsInner`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *ProjectV2Response) GetPermissionsOk() (*[]ProjectV2ResponsePermissionsInner, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *ProjectV2Response) SetPermissions(v []ProjectV2ResponsePermissionsInner)`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *ProjectV2Response) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


