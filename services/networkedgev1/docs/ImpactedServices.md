# ImpactedServices

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServiceName** | Pointer to **string** | The name of the impacted service. | [optional] 
**Impact** | Pointer to **string** | The type of impact, whether the impacted service is down or delayed. | [optional] 
**ServiceStartDateTime** | Pointer to **time.Time** | Start of the downtime of the service. | [optional] 
**ServiceEndDateTime** | Pointer to **time.Time** | End of the downtime of the service. | [optional] 
**ErrorMessage** | Pointer to **string** | Downtime message of the service. | [optional] 

## Methods

### NewImpactedServices

`func NewImpactedServices() *ImpactedServices`

NewImpactedServices instantiates a new ImpactedServices object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImpactedServicesWithDefaults

`func NewImpactedServicesWithDefaults() *ImpactedServices`

NewImpactedServicesWithDefaults instantiates a new ImpactedServices object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServiceName

`func (o *ImpactedServices) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *ImpactedServices) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *ImpactedServices) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *ImpactedServices) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetImpact

`func (o *ImpactedServices) GetImpact() string`

GetImpact returns the Impact field if non-nil, zero value otherwise.

### GetImpactOk

`func (o *ImpactedServices) GetImpactOk() (*string, bool)`

GetImpactOk returns a tuple with the Impact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpact

`func (o *ImpactedServices) SetImpact(v string)`

SetImpact sets Impact field to given value.

### HasImpact

`func (o *ImpactedServices) HasImpact() bool`

HasImpact returns a boolean if a field has been set.

### GetServiceStartDateTime

`func (o *ImpactedServices) GetServiceStartDateTime() time.Time`

GetServiceStartDateTime returns the ServiceStartDateTime field if non-nil, zero value otherwise.

### GetServiceStartDateTimeOk

`func (o *ImpactedServices) GetServiceStartDateTimeOk() (*time.Time, bool)`

GetServiceStartDateTimeOk returns a tuple with the ServiceStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceStartDateTime

`func (o *ImpactedServices) SetServiceStartDateTime(v time.Time)`

SetServiceStartDateTime sets ServiceStartDateTime field to given value.

### HasServiceStartDateTime

`func (o *ImpactedServices) HasServiceStartDateTime() bool`

HasServiceStartDateTime returns a boolean if a field has been set.

### GetServiceEndDateTime

`func (o *ImpactedServices) GetServiceEndDateTime() time.Time`

GetServiceEndDateTime returns the ServiceEndDateTime field if non-nil, zero value otherwise.

### GetServiceEndDateTimeOk

`func (o *ImpactedServices) GetServiceEndDateTimeOk() (*time.Time, bool)`

GetServiceEndDateTimeOk returns a tuple with the ServiceEndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceEndDateTime

`func (o *ImpactedServices) SetServiceEndDateTime(v time.Time)`

SetServiceEndDateTime sets ServiceEndDateTime field to given value.

### HasServiceEndDateTime

`func (o *ImpactedServices) HasServiceEndDateTime() bool`

HasServiceEndDateTime returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ImpactedServices) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ImpactedServices) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ImpactedServices) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ImpactedServices) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


