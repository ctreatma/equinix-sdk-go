# DowntimeNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationType** | Pointer to [**DowntimeNotificationNotificationType**](DowntimeNotificationNotificationType.md) |  | [optional] 
**StartDateTime** | Pointer to **time.Time** | Start of the downtime. | [optional] 
**EndDateTime** | Pointer to **time.Time** | End of the downtime. | [optional] 
**ImpactedServices** | Pointer to [**[]ImpactedServices**](ImpactedServices.md) | An array of services impacted by the downtime. | [optional] 
**AdditionalMessage** | Pointer to **string** | Any additional messages. | [optional] 

## Methods

### NewDowntimeNotification

`func NewDowntimeNotification() *DowntimeNotification`

NewDowntimeNotification instantiates a new DowntimeNotification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDowntimeNotificationWithDefaults

`func NewDowntimeNotificationWithDefaults() *DowntimeNotification`

NewDowntimeNotificationWithDefaults instantiates a new DowntimeNotification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationType

`func (o *DowntimeNotification) GetNotificationType() DowntimeNotificationNotificationType`

GetNotificationType returns the NotificationType field if non-nil, zero value otherwise.

### GetNotificationTypeOk

`func (o *DowntimeNotification) GetNotificationTypeOk() (*DowntimeNotificationNotificationType, bool)`

GetNotificationTypeOk returns a tuple with the NotificationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationType

`func (o *DowntimeNotification) SetNotificationType(v DowntimeNotificationNotificationType)`

SetNotificationType sets NotificationType field to given value.

### HasNotificationType

`func (o *DowntimeNotification) HasNotificationType() bool`

HasNotificationType returns a boolean if a field has been set.

### GetStartDateTime

`func (o *DowntimeNotification) GetStartDateTime() time.Time`

GetStartDateTime returns the StartDateTime field if non-nil, zero value otherwise.

### GetStartDateTimeOk

`func (o *DowntimeNotification) GetStartDateTimeOk() (*time.Time, bool)`

GetStartDateTimeOk returns a tuple with the StartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDateTime

`func (o *DowntimeNotification) SetStartDateTime(v time.Time)`

SetStartDateTime sets StartDateTime field to given value.

### HasStartDateTime

`func (o *DowntimeNotification) HasStartDateTime() bool`

HasStartDateTime returns a boolean if a field has been set.

### GetEndDateTime

`func (o *DowntimeNotification) GetEndDateTime() time.Time`

GetEndDateTime returns the EndDateTime field if non-nil, zero value otherwise.

### GetEndDateTimeOk

`func (o *DowntimeNotification) GetEndDateTimeOk() (*time.Time, bool)`

GetEndDateTimeOk returns a tuple with the EndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDateTime

`func (o *DowntimeNotification) SetEndDateTime(v time.Time)`

SetEndDateTime sets EndDateTime field to given value.

### HasEndDateTime

`func (o *DowntimeNotification) HasEndDateTime() bool`

HasEndDateTime returns a boolean if a field has been set.

### GetImpactedServices

`func (o *DowntimeNotification) GetImpactedServices() []ImpactedServices`

GetImpactedServices returns the ImpactedServices field if non-nil, zero value otherwise.

### GetImpactedServicesOk

`func (o *DowntimeNotification) GetImpactedServicesOk() (*[]ImpactedServices, bool)`

GetImpactedServicesOk returns a tuple with the ImpactedServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpactedServices

`func (o *DowntimeNotification) SetImpactedServices(v []ImpactedServices)`

SetImpactedServices sets ImpactedServices field to given value.

### HasImpactedServices

`func (o *DowntimeNotification) HasImpactedServices() bool`

HasImpactedServices returns a boolean if a field has been set.

### GetAdditionalMessage

`func (o *DowntimeNotification) GetAdditionalMessage() string`

GetAdditionalMessage returns the AdditionalMessage field if non-nil, zero value otherwise.

### GetAdditionalMessageOk

`func (o *DowntimeNotification) GetAdditionalMessageOk() (*string, bool)`

GetAdditionalMessageOk returns a tuple with the AdditionalMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalMessage

`func (o *DowntimeNotification) SetAdditionalMessage(v string)`

SetAdditionalMessage sets AdditionalMessage field to given value.

### HasAdditionalMessage

`func (o *DowntimeNotification) HasAdditionalMessage() bool`

HasAdditionalMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


