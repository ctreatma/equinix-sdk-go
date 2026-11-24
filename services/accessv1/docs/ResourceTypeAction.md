# ResourceTypeAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**ResourceType** | Pointer to **string** | Identifies a resource type within a service, formatted as \&quot;resourcetype:&lt;typeName&gt;\&quot;. | [optional] 
**ResourceTypeErn** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**Action** | **string** | Id of an action, unique across all aspects of its service | 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 

## Methods

### NewResourceTypeAction

`func NewResourceTypeAction(resourceTypeErn string, action string, rev string, ) *ResourceTypeAction`

NewResourceTypeAction instantiates a new ResourceTypeAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceTypeActionWithDefaults

`func NewResourceTypeActionWithDefaults() *ResourceTypeAction`

NewResourceTypeActionWithDefaults instantiates a new ResourceTypeAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedBy

`func (o *ResourceTypeAction) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ResourceTypeAction) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ResourceTypeAction) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *ResourceTypeAction) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ResourceTypeAction) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ResourceTypeAction) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ResourceTypeAction) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ResourceTypeAction) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetResourceType

`func (o *ResourceTypeAction) GetResourceType() string`

GetResourceType returns the ResourceType field if non-nil, zero value otherwise.

### GetResourceTypeOk

`func (o *ResourceTypeAction) GetResourceTypeOk() (*string, bool)`

GetResourceTypeOk returns a tuple with the ResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceType

`func (o *ResourceTypeAction) SetResourceType(v string)`

SetResourceType sets ResourceType field to given value.

### HasResourceType

`func (o *ResourceTypeAction) HasResourceType() bool`

HasResourceType returns a boolean if a field has been set.

### GetResourceTypeErn

`func (o *ResourceTypeAction) GetResourceTypeErn() string`

GetResourceTypeErn returns the ResourceTypeErn field if non-nil, zero value otherwise.

### GetResourceTypeErnOk

`func (o *ResourceTypeAction) GetResourceTypeErnOk() (*string, bool)`

GetResourceTypeErnOk returns a tuple with the ResourceTypeErn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceTypeErn

`func (o *ResourceTypeAction) SetResourceTypeErn(v string)`

SetResourceTypeErn sets ResourceTypeErn field to given value.


### GetAction

`func (o *ResourceTypeAction) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ResourceTypeAction) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ResourceTypeAction) SetAction(v string)`

SetAction sets Action field to given value.


### GetRev

`func (o *ResourceTypeAction) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *ResourceTypeAction) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *ResourceTypeAction) SetRev(v string)`

SetRev sets Rev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


