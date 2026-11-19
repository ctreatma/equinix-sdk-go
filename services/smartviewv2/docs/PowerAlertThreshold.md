# PowerAlertThreshold

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Unit** | Pointer to **string** | Unit of measurement for the threshold value (e.g., %) | [optional] 
**Value** | Pointer to **string** | Threshold value that triggers the alert | [optional] 
**Min** | Pointer to **map[string]interface{}** | Minimum threshold value (used for range-based conditions) | [optional] 
**Max** | Pointer to **map[string]interface{}** | Maximum threshold value (used for range-based conditions) | [optional] 

## Methods

### NewPowerAlertThreshold

`func NewPowerAlertThreshold() *PowerAlertThreshold`

NewPowerAlertThreshold instantiates a new PowerAlertThreshold object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPowerAlertThresholdWithDefaults

`func NewPowerAlertThresholdWithDefaults() *PowerAlertThreshold`

NewPowerAlertThresholdWithDefaults instantiates a new PowerAlertThreshold object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUnit

`func (o *PowerAlertThreshold) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *PowerAlertThreshold) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *PowerAlertThreshold) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *PowerAlertThreshold) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetValue

`func (o *PowerAlertThreshold) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *PowerAlertThreshold) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *PowerAlertThreshold) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *PowerAlertThreshold) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetMin

`func (o *PowerAlertThreshold) GetMin() map[string]interface{}`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *PowerAlertThreshold) GetMinOk() (*map[string]interface{}, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *PowerAlertThreshold) SetMin(v map[string]interface{})`

SetMin sets Min field to given value.

### HasMin

`func (o *PowerAlertThreshold) HasMin() bool`

HasMin returns a boolean if a field has been set.

### SetMinNil

`func (o *PowerAlertThreshold) SetMinNil(b bool)`

 SetMinNil sets the value for Min to be an explicit nil

### UnsetMin
`func (o *PowerAlertThreshold) UnsetMin()`

UnsetMin ensures that no value is present for Min, not even an explicit nil
### GetMax

`func (o *PowerAlertThreshold) GetMax() map[string]interface{}`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *PowerAlertThreshold) GetMaxOk() (*map[string]interface{}, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *PowerAlertThreshold) SetMax(v map[string]interface{})`

SetMax sets Max field to given value.

### HasMax

`func (o *PowerAlertThreshold) HasMax() bool`

HasMax returns a boolean if a field has been set.

### SetMaxNil

`func (o *PowerAlertThreshold) SetMaxNil(b bool)`

 SetMaxNil sets the value for Max to be an explicit nil

### UnsetMax
`func (o *PowerAlertThreshold) UnsetMax()`

UnsetMax ensures that no value is present for Max, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


