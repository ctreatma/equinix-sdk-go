# ResourceType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**UpdatedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**ResourceType** | **string** | Identifies a resource type within a service, formatted as \&quot;resourcetype:&lt;typeName&gt;\&quot;. | 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 
**ApprovedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Ern** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**Attributes** | Pointer to [**AttributeSet**](AttributeSet.md) | Identify the attributes which are included on this resource                                          type. | [optional] 
**ApprovedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to approve the resource. | [optional] 

## Methods

### NewResourceType

`func NewResourceType(tags map[string]string, resourceType string, rev string, ern string, ) *ResourceType`

NewResourceType instantiates a new ResourceType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceTypeWithDefaults

`func NewResourceTypeWithDefaults() *ResourceType`

NewResourceTypeWithDefaults instantiates a new ResourceType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *ResourceType) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ResourceType) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ResourceType) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetUpdatedAt

`func (o *ResourceType) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ResourceType) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ResourceType) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ResourceType) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetCreatedBy

`func (o *ResourceType) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ResourceType) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ResourceType) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *ResourceType) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ResourceType) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ResourceType) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ResourceType) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ResourceType) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetResourceType

`func (o *ResourceType) GetResourceType() string`

GetResourceType returns the ResourceType field if non-nil, zero value otherwise.

### GetResourceTypeOk

`func (o *ResourceType) GetResourceTypeOk() (*string, bool)`

GetResourceTypeOk returns a tuple with the ResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceType

`func (o *ResourceType) SetResourceType(v string)`

SetResourceType sets ResourceType field to given value.


### GetRev

`func (o *ResourceType) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *ResourceType) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *ResourceType) SetRev(v string)`

SetRev sets Rev field to given value.


### GetApprovedAt

`func (o *ResourceType) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *ResourceType) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *ResourceType) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *ResourceType) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetErn

`func (o *ResourceType) GetErn() string`

GetErn returns the Ern field if non-nil, zero value otherwise.

### GetErnOk

`func (o *ResourceType) GetErnOk() (*string, bool)`

GetErnOk returns a tuple with the Ern field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErn

`func (o *ResourceType) SetErn(v string)`

SetErn sets Ern field to given value.


### GetUpdatedBy

`func (o *ResourceType) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *ResourceType) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *ResourceType) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *ResourceType) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetAttributes

`func (o *ResourceType) GetAttributes() AttributeSet`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *ResourceType) GetAttributesOk() (*AttributeSet, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *ResourceType) SetAttributes(v AttributeSet)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *ResourceType) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.

### GetApprovedBy

`func (o *ResourceType) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *ResourceType) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *ResourceType) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *ResourceType) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


