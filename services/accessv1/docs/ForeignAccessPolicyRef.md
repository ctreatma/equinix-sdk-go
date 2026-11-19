# ForeignAccessPolicyRef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ForeignAccessPolicy** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**Condition** | Pointer to **string** |  | [optional] 
**IbxLocationCondition** | Pointer to [**IbxLocationCondition**](IbxLocationCondition.md) |  | [optional] 

## Methods

### NewForeignAccessPolicyRef

`func NewForeignAccessPolicyRef(foreignAccessPolicy string, ) *ForeignAccessPolicyRef`

NewForeignAccessPolicyRef instantiates a new ForeignAccessPolicyRef object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForeignAccessPolicyRefWithDefaults

`func NewForeignAccessPolicyRefWithDefaults() *ForeignAccessPolicyRef`

NewForeignAccessPolicyRefWithDefaults instantiates a new ForeignAccessPolicyRef object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForeignAccessPolicy

`func (o *ForeignAccessPolicyRef) GetForeignAccessPolicy() string`

GetForeignAccessPolicy returns the ForeignAccessPolicy field if non-nil, zero value otherwise.

### GetForeignAccessPolicyOk

`func (o *ForeignAccessPolicyRef) GetForeignAccessPolicyOk() (*string, bool)`

GetForeignAccessPolicyOk returns a tuple with the ForeignAccessPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeignAccessPolicy

`func (o *ForeignAccessPolicyRef) SetForeignAccessPolicy(v string)`

SetForeignAccessPolicy sets ForeignAccessPolicy field to given value.


### GetCondition

`func (o *ForeignAccessPolicyRef) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *ForeignAccessPolicyRef) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *ForeignAccessPolicyRef) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *ForeignAccessPolicyRef) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetIbxLocationCondition

`func (o *ForeignAccessPolicyRef) GetIbxLocationCondition() IbxLocationCondition`

GetIbxLocationCondition returns the IbxLocationCondition field if non-nil, zero value otherwise.

### GetIbxLocationConditionOk

`func (o *ForeignAccessPolicyRef) GetIbxLocationConditionOk() (*IbxLocationCondition, bool)`

GetIbxLocationConditionOk returns a tuple with the IbxLocationCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocationCondition

`func (o *ForeignAccessPolicyRef) SetIbxLocationCondition(v IbxLocationCondition)`

SetIbxLocationCondition sets IbxLocationCondition field to given value.

### HasIbxLocationCondition

`func (o *ForeignAccessPolicyRef) HasIbxLocationCondition() bool`

HasIbxLocationCondition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


