# Event

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationNumber** | **string** | Notification reference number. | 
**Category** | Pointer to [**Category**](Category.md) |  | [optional] [default to CATEGORY_GENERAL]
**Type** | [**Type**](Type.md) |  | 
**ProductTypes** | Pointer to [**[]ProductType**](ProductType.md) | Product types associated with the given order notification. | [optional] 
**Ibxs** | Pointer to **[]string** | IBX(s) associated with the notification. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Time when the notification was sent. | [optional] 
**Summary** | **string** | Notification summary. | 
**Status** | Pointer to [**Status**](Status.md) |  | [optional] 
**Contacts** | Pointer to [**[]NotificationContact**](NotificationContact.md) | Notification recipient list, if any. | [optional] 
**AdditionalInfo** | Pointer to [**[]AdditionalInfo**](AdditionalInfo.md) | Additional info, if any. Available fields: SUPPORT_PLAN_PERCENTAGE, ACCOUNT_NAME, ACCOUNT_NUMBER, START_DATETIME, END_DATETIME, PRIORITY, IS_GLOBAL_NOTIFICATION | [optional] 

## Methods

### NewEvent

`func NewEvent(notificationNumber string, type_ Type, summary string, ) *Event`

NewEvent instantiates a new Event object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventWithDefaults

`func NewEventWithDefaults() *Event`

NewEventWithDefaults instantiates a new Event object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationNumber

`func (o *Event) GetNotificationNumber() string`

GetNotificationNumber returns the NotificationNumber field if non-nil, zero value otherwise.

### GetNotificationNumberOk

`func (o *Event) GetNotificationNumberOk() (*string, bool)`

GetNotificationNumberOk returns a tuple with the NotificationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationNumber

`func (o *Event) SetNotificationNumber(v string)`

SetNotificationNumber sets NotificationNumber field to given value.


### GetCategory

`func (o *Event) GetCategory() Category`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Event) GetCategoryOk() (*Category, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Event) SetCategory(v Category)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *Event) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetType

`func (o *Event) GetType() Type`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Event) GetTypeOk() (*Type, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Event) SetType(v Type)`

SetType sets Type field to given value.


### GetProductTypes

`func (o *Event) GetProductTypes() []ProductType`

GetProductTypes returns the ProductTypes field if non-nil, zero value otherwise.

### GetProductTypesOk

`func (o *Event) GetProductTypesOk() (*[]ProductType, bool)`

GetProductTypesOk returns a tuple with the ProductTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductTypes

`func (o *Event) SetProductTypes(v []ProductType)`

SetProductTypes sets ProductTypes field to given value.

### HasProductTypes

`func (o *Event) HasProductTypes() bool`

HasProductTypes returns a boolean if a field has been set.

### GetIbxs

`func (o *Event) GetIbxs() []string`

GetIbxs returns the Ibxs field if non-nil, zero value otherwise.

### GetIbxsOk

`func (o *Event) GetIbxsOk() (*[]string, bool)`

GetIbxsOk returns a tuple with the Ibxs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxs

`func (o *Event) SetIbxs(v []string)`

SetIbxs sets Ibxs field to given value.

### HasIbxs

`func (o *Event) HasIbxs() bool`

HasIbxs returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *Event) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *Event) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *Event) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *Event) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetSummary

`func (o *Event) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *Event) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *Event) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetStatus

`func (o *Event) GetStatus() Status`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Event) GetStatusOk() (*Status, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Event) SetStatus(v Status)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Event) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetContacts

`func (o *Event) GetContacts() []NotificationContact`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *Event) GetContactsOk() (*[]NotificationContact, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *Event) SetContacts(v []NotificationContact)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *Event) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *Event) GetAdditionalInfo() []AdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *Event) GetAdditionalInfoOk() (*[]AdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *Event) SetAdditionalInfo(v []AdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *Event) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


