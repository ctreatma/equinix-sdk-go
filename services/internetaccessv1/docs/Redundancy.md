# Redundancy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | defines if redundancy is enabled. | 
**Priority** | [**RedundancyPriority**](RedundancyPriority.md) |  | 
**Group** | **string** | Group identifier | 

## Methods

### NewRedundancy

`func NewRedundancy(enabled bool, priority RedundancyPriority, group string, ) *Redundancy`

NewRedundancy instantiates a new Redundancy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedundancyWithDefaults

`func NewRedundancyWithDefaults() *Redundancy`

NewRedundancyWithDefaults instantiates a new Redundancy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *Redundancy) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Redundancy) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Redundancy) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetPriority

`func (o *Redundancy) GetPriority() RedundancyPriority`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *Redundancy) GetPriorityOk() (*RedundancyPriority, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *Redundancy) SetPriority(v RedundancyPriority)`

SetPriority sets Priority field to given value.


### GetGroup

`func (o *Redundancy) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *Redundancy) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *Redundancy) SetGroup(v string)`

SetGroup sets Group field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


