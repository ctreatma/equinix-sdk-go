# ServiceActionSetNoErn

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Tags** | **map[string]string** | Additional user-controlled data about this resource. | 
**UpdatedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**CreatedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to create the resource. | [optional] 
**ActionSetId** | **string** | Uniquely identifies an ActionSet within a Service. | 
**CreatedAt** | Pointer to **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**Rev** | **string** | An opaque string that represents the revision of a given resource. Each time the resource is updated, this value   changes. | 
**ApprovedAt** | Pointer to **string** | A string timestamp indicating when the resource was last updated. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | [optional] 
**ServiceId** | **string** | Fully qualified, universally unique id of a service. Starts with the NamespaceId. Formatted like   \&quot;service:&amp;lt;namespace&amp;gt;/&amp;lt;service&amp;gt;\&quot;. | 
**UpdatedBy** | Pointer to **string** | A string indicating the principal who last invoked an operation to update the resource. | [optional] 
**ActionSet** | **[]string** |  | 
**ApprovedBy** | Pointer to **string** | A string indicating the principal who invoked an operation to approve the resource. | [optional] 

## Methods

### NewServiceActionSetNoErn

`func NewServiceActionSetNoErn(tags map[string]string, actionSetId string, rev string, serviceId string, actionSet []string, ) *ServiceActionSetNoErn`

NewServiceActionSetNoErn instantiates a new ServiceActionSetNoErn object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceActionSetNoErnWithDefaults

`func NewServiceActionSetNoErnWithDefaults() *ServiceActionSetNoErn`

NewServiceActionSetNoErnWithDefaults instantiates a new ServiceActionSetNoErn object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ServiceActionSetNoErn) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceActionSetNoErn) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceActionSetNoErn) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceActionSetNoErn) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetTags

`func (o *ServiceActionSetNoErn) GetTags() map[string]string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ServiceActionSetNoErn) GetTagsOk() (*map[string]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ServiceActionSetNoErn) SetTags(v map[string]string)`

SetTags sets Tags field to given value.


### GetUpdatedAt

`func (o *ServiceActionSetNoErn) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ServiceActionSetNoErn) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ServiceActionSetNoErn) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ServiceActionSetNoErn) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetCreatedBy

`func (o *ServiceActionSetNoErn) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ServiceActionSetNoErn) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ServiceActionSetNoErn) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *ServiceActionSetNoErn) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetActionSetId

`func (o *ServiceActionSetNoErn) GetActionSetId() string`

GetActionSetId returns the ActionSetId field if non-nil, zero value otherwise.

### GetActionSetIdOk

`func (o *ServiceActionSetNoErn) GetActionSetIdOk() (*string, bool)`

GetActionSetIdOk returns a tuple with the ActionSetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionSetId

`func (o *ServiceActionSetNoErn) SetActionSetId(v string)`

SetActionSetId sets ActionSetId field to given value.


### GetCreatedAt

`func (o *ServiceActionSetNoErn) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ServiceActionSetNoErn) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ServiceActionSetNoErn) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ServiceActionSetNoErn) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetRev

`func (o *ServiceActionSetNoErn) GetRev() string`

GetRev returns the Rev field if non-nil, zero value otherwise.

### GetRevOk

`func (o *ServiceActionSetNoErn) GetRevOk() (*string, bool)`

GetRevOk returns a tuple with the Rev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRev

`func (o *ServiceActionSetNoErn) SetRev(v string)`

SetRev sets Rev field to given value.


### GetApprovedAt

`func (o *ServiceActionSetNoErn) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *ServiceActionSetNoErn) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *ServiceActionSetNoErn) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.

### HasApprovedAt

`func (o *ServiceActionSetNoErn) HasApprovedAt() bool`

HasApprovedAt returns a boolean if a field has been set.

### GetServiceId

`func (o *ServiceActionSetNoErn) GetServiceId() string`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *ServiceActionSetNoErn) GetServiceIdOk() (*string, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *ServiceActionSetNoErn) SetServiceId(v string)`

SetServiceId sets ServiceId field to given value.


### GetUpdatedBy

`func (o *ServiceActionSetNoErn) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *ServiceActionSetNoErn) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *ServiceActionSetNoErn) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *ServiceActionSetNoErn) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### GetActionSet

`func (o *ServiceActionSetNoErn) GetActionSet() []string`

GetActionSet returns the ActionSet field if non-nil, zero value otherwise.

### GetActionSetOk

`func (o *ServiceActionSetNoErn) GetActionSetOk() (*[]string, bool)`

GetActionSetOk returns a tuple with the ActionSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionSet

`func (o *ServiceActionSetNoErn) SetActionSet(v []string)`

SetActionSet sets ActionSet field to given value.


### GetApprovedBy

`func (o *ServiceActionSetNoErn) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *ServiceActionSetNoErn) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *ServiceActionSetNoErn) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.

### HasApprovedBy

`func (o *ServiceActionSetNoErn) HasApprovedBy() bool`

HasApprovedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


