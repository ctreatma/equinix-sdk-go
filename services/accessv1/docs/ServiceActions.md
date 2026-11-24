# ServiceActions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceId** | **string** | Fully qualified, universally unique id of a service. Starts with the NamespaceId. Formatted like   \&quot;service:&amp;lt;namespace&amp;gt;/&amp;lt;service&amp;gt;\&quot;. | 
**Actions** | [**[]ServiceActionsActionsInner**](ServiceActionsActionsInner.md) |  | 

## Methods

### NewServiceActions

`func NewServiceActions(serviceId string, actions []ServiceActionsActionsInner, ) *ServiceActions`

NewServiceActions instantiates a new ServiceActions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceActionsWithDefaults

`func NewServiceActionsWithDefaults() *ServiceActions`

NewServiceActionsWithDefaults instantiates a new ServiceActions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceId

`func (o *ServiceActions) GetServiceId() string`

GetServiceId returns the ServiceId field if non-nil, zero value otherwise.

### GetServiceIdOk

`func (o *ServiceActions) GetServiceIdOk() (*string, bool)`

GetServiceIdOk returns a tuple with the ServiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceId

`func (o *ServiceActions) SetServiceId(v string)`

SetServiceId sets ServiceId field to given value.


### GetActions

`func (o *ServiceActions) GetActions() []ServiceActionsActionsInner`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *ServiceActions) GetActionsOk() (*[]ServiceActionsActionsInner, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *ServiceActions) SetActions(v []ServiceActionsActionsInner)`

SetActions sets Actions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


