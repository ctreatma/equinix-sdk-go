# ProcessingTimeReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EdgeCollectedOn** | Pointer to **time.Time** | when tag reading was collected on source | [optional] 
**TagCalculationJobProcessedOn** | Pointer to **time.Time** | when tag reading was processed by tag-calculation rtp | [optional] 
**ProcessingStartOn** | Pointer to **time.Time** | when tag reading was accepted by alert rtp | [optional] 
**ProcessingEndOn** | Pointer to **time.Time** | when tag reading was processed by alert rtp | [optional] 
**PublishedOn** | Pointer to **time.Time** | when tag reading was published by alert rtp | [optional] 

## Methods

### NewProcessingTimeReadModel

`func NewProcessingTimeReadModel() *ProcessingTimeReadModel`

NewProcessingTimeReadModel instantiates a new ProcessingTimeReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessingTimeReadModelWithDefaults

`func NewProcessingTimeReadModelWithDefaults() *ProcessingTimeReadModel`

NewProcessingTimeReadModelWithDefaults instantiates a new ProcessingTimeReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdgeCollectedOn

`func (o *ProcessingTimeReadModel) GetEdgeCollectedOn() time.Time`

GetEdgeCollectedOn returns the EdgeCollectedOn field if non-nil, zero value otherwise.

### GetEdgeCollectedOnOk

`func (o *ProcessingTimeReadModel) GetEdgeCollectedOnOk() (*time.Time, bool)`

GetEdgeCollectedOnOk returns a tuple with the EdgeCollectedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgeCollectedOn

`func (o *ProcessingTimeReadModel) SetEdgeCollectedOn(v time.Time)`

SetEdgeCollectedOn sets EdgeCollectedOn field to given value.

### HasEdgeCollectedOn

`func (o *ProcessingTimeReadModel) HasEdgeCollectedOn() bool`

HasEdgeCollectedOn returns a boolean if a field has been set.

### GetTagCalculationJobProcessedOn

`func (o *ProcessingTimeReadModel) GetTagCalculationJobProcessedOn() time.Time`

GetTagCalculationJobProcessedOn returns the TagCalculationJobProcessedOn field if non-nil, zero value otherwise.

### GetTagCalculationJobProcessedOnOk

`func (o *ProcessingTimeReadModel) GetTagCalculationJobProcessedOnOk() (*time.Time, bool)`

GetTagCalculationJobProcessedOnOk returns a tuple with the TagCalculationJobProcessedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagCalculationJobProcessedOn

`func (o *ProcessingTimeReadModel) SetTagCalculationJobProcessedOn(v time.Time)`

SetTagCalculationJobProcessedOn sets TagCalculationJobProcessedOn field to given value.

### HasTagCalculationJobProcessedOn

`func (o *ProcessingTimeReadModel) HasTagCalculationJobProcessedOn() bool`

HasTagCalculationJobProcessedOn returns a boolean if a field has been set.

### GetProcessingStartOn

`func (o *ProcessingTimeReadModel) GetProcessingStartOn() time.Time`

GetProcessingStartOn returns the ProcessingStartOn field if non-nil, zero value otherwise.

### GetProcessingStartOnOk

`func (o *ProcessingTimeReadModel) GetProcessingStartOnOk() (*time.Time, bool)`

GetProcessingStartOnOk returns a tuple with the ProcessingStartOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStartOn

`func (o *ProcessingTimeReadModel) SetProcessingStartOn(v time.Time)`

SetProcessingStartOn sets ProcessingStartOn field to given value.

### HasProcessingStartOn

`func (o *ProcessingTimeReadModel) HasProcessingStartOn() bool`

HasProcessingStartOn returns a boolean if a field has been set.

### GetProcessingEndOn

`func (o *ProcessingTimeReadModel) GetProcessingEndOn() time.Time`

GetProcessingEndOn returns the ProcessingEndOn field if non-nil, zero value otherwise.

### GetProcessingEndOnOk

`func (o *ProcessingTimeReadModel) GetProcessingEndOnOk() (*time.Time, bool)`

GetProcessingEndOnOk returns a tuple with the ProcessingEndOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingEndOn

`func (o *ProcessingTimeReadModel) SetProcessingEndOn(v time.Time)`

SetProcessingEndOn sets ProcessingEndOn field to given value.

### HasProcessingEndOn

`func (o *ProcessingTimeReadModel) HasProcessingEndOn() bool`

HasProcessingEndOn returns a boolean if a field has been set.

### GetPublishedOn

`func (o *ProcessingTimeReadModel) GetPublishedOn() time.Time`

GetPublishedOn returns the PublishedOn field if non-nil, zero value otherwise.

### GetPublishedOnOk

`func (o *ProcessingTimeReadModel) GetPublishedOnOk() (*time.Time, bool)`

GetPublishedOnOk returns a tuple with the PublishedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedOn

`func (o *ProcessingTimeReadModel) SetPublishedOn(v time.Time)`

SetPublishedOn sets PublishedOn field to given value.

### HasPublishedOn

`func (o *ProcessingTimeReadModel) HasPublishedOn() bool`

HasPublishedOn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


