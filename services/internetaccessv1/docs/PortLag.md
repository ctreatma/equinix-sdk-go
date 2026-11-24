# PortLag

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Flag indicating whether the Link Aggregation is enabled on the port or not  | 
**Name** | Pointer to **string** |  | [optional] 

## Methods

### NewPortLag

`func NewPortLag(enabled bool, ) *PortLag`

NewPortLag instantiates a new PortLag object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortLagWithDefaults

`func NewPortLagWithDefaults() *PortLag`

NewPortLagWithDefaults instantiates a new PortLag object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *PortLag) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PortLag) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PortLag) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetName

`func (o *PortLag) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PortLag) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PortLag) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PortLag) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


