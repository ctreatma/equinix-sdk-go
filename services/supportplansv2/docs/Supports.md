# Supports

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the specific plan. Note that &#x60;id&#x60; can be repeated for rollover plans or plan assignment.  | [optional] 
**AccountNumber** | Pointer to **string** | Account number of the owner of support plan  | [optional] 
**PlanName** | Pointer to **string** | Name of support plan | [optional] 
**ProductCode** | Pointer to **string** | Equinix product catalog code | [optional] 
**Ibxs** | Pointer to **[]string** | List of IBXs where support plans can be used | [optional] 
**IbxSpecific** | Pointer to **bool** | When &#x60;true&#x60;, support plans can only be used on a specific IBX.  | [optional] 
**PlanFrequency** | Pointer to [**SupportsPlanFrequency**](SupportsPlanFrequency.md) |  | [optional] 
**PurchasedMinutes** | Pointer to **int32** | Shows the number of minutes purchased for a specific plan | [optional] 
**AssignedMinutes** | Pointer to **int32** | Shows the number of minutes assigned for a specific plan when plan is pro-rated. Plans are pro-rated when they are not purchased on the 1st of the month. | [optional] 
**ConsumedMinutes** | Pointer to **int32** | Shows the number of minutes consumed for a specific plan | [optional] 
**RemainingMinutes** | Pointer to **int32** | Shows the number of minutes remaining for a specific plan | [optional] 
**PreviousConsumedMinutes** | Pointer to **int32** | Shows the number of minutes consumed in the previous month. This is only  applicable for &#x60;MONTHLY&#x60; and &#x60;MONTHLY_ROLLOVER&#x60; | [optional] 
**CurrentConsumedMinutes** | Pointer to **int32** | Shows the number of minutes consumed in the current month. This is only  applicable for &#x60;MONTHLY&#x60; and &#x60;MONTHLY_ROLLOVER&#x60; | [optional] 
**PrepaidConsumedMinutes** | Pointer to **int32** | Shows the number of minutes consumed for prepaid plans. This is only applicable if plan frequency is of &#x60;ANNUAL&#x60;  | [optional] 
**TransitionMinutes** | Pointer to **int32** | Shows the number of minutes assigned to your end customer. Applicable to resellers only. | [optional] 
**StartDate** | Pointer to **string** | Plan start date in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**EndDate** | Pointer to **string** | Plan end date &#x60;YYYY-MM-DD&#x60; format | [optional] 
**Status** | Pointer to [**SupportsStatus**](SupportsStatus.md) |  | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Shows the date and time when support plan was created in ISO 8601 format | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** | Shows the date and time when support plan was last updated in ISO 8601 format. | [optional] 
**Assignment** | Pointer to [**Assignment**](Assignment.md) |  | [optional] 

## Methods

### NewSupports

`func NewSupports() *Supports`

NewSupports instantiates a new Supports object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupportsWithDefaults

`func NewSupportsWithDefaults() *Supports`

NewSupportsWithDefaults instantiates a new Supports object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Supports) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Supports) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Supports) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Supports) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAccountNumber

`func (o *Supports) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *Supports) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *Supports) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *Supports) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetPlanName

`func (o *Supports) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *Supports) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *Supports) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.

### HasPlanName

`func (o *Supports) HasPlanName() bool`

HasPlanName returns a boolean if a field has been set.

### GetProductCode

`func (o *Supports) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *Supports) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *Supports) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.

### HasProductCode

`func (o *Supports) HasProductCode() bool`

HasProductCode returns a boolean if a field has been set.

### GetIbxs

`func (o *Supports) GetIbxs() []string`

GetIbxs returns the Ibxs field if non-nil, zero value otherwise.

### GetIbxsOk

`func (o *Supports) GetIbxsOk() (*[]string, bool)`

GetIbxsOk returns a tuple with the Ibxs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxs

`func (o *Supports) SetIbxs(v []string)`

SetIbxs sets Ibxs field to given value.

### HasIbxs

`func (o *Supports) HasIbxs() bool`

HasIbxs returns a boolean if a field has been set.

### GetIbxSpecific

`func (o *Supports) GetIbxSpecific() bool`

GetIbxSpecific returns the IbxSpecific field if non-nil, zero value otherwise.

### GetIbxSpecificOk

`func (o *Supports) GetIbxSpecificOk() (*bool, bool)`

GetIbxSpecificOk returns a tuple with the IbxSpecific field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxSpecific

`func (o *Supports) SetIbxSpecific(v bool)`

SetIbxSpecific sets IbxSpecific field to given value.

### HasIbxSpecific

`func (o *Supports) HasIbxSpecific() bool`

HasIbxSpecific returns a boolean if a field has been set.

### GetPlanFrequency

`func (o *Supports) GetPlanFrequency() SupportsPlanFrequency`

GetPlanFrequency returns the PlanFrequency field if non-nil, zero value otherwise.

### GetPlanFrequencyOk

`func (o *Supports) GetPlanFrequencyOk() (*SupportsPlanFrequency, bool)`

GetPlanFrequencyOk returns a tuple with the PlanFrequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanFrequency

`func (o *Supports) SetPlanFrequency(v SupportsPlanFrequency)`

SetPlanFrequency sets PlanFrequency field to given value.

### HasPlanFrequency

`func (o *Supports) HasPlanFrequency() bool`

HasPlanFrequency returns a boolean if a field has been set.

### GetPurchasedMinutes

`func (o *Supports) GetPurchasedMinutes() int32`

GetPurchasedMinutes returns the PurchasedMinutes field if non-nil, zero value otherwise.

### GetPurchasedMinutesOk

`func (o *Supports) GetPurchasedMinutesOk() (*int32, bool)`

GetPurchasedMinutesOk returns a tuple with the PurchasedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasedMinutes

`func (o *Supports) SetPurchasedMinutes(v int32)`

SetPurchasedMinutes sets PurchasedMinutes field to given value.

### HasPurchasedMinutes

`func (o *Supports) HasPurchasedMinutes() bool`

HasPurchasedMinutes returns a boolean if a field has been set.

### GetAssignedMinutes

`func (o *Supports) GetAssignedMinutes() int32`

GetAssignedMinutes returns the AssignedMinutes field if non-nil, zero value otherwise.

### GetAssignedMinutesOk

`func (o *Supports) GetAssignedMinutesOk() (*int32, bool)`

GetAssignedMinutesOk returns a tuple with the AssignedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedMinutes

`func (o *Supports) SetAssignedMinutes(v int32)`

SetAssignedMinutes sets AssignedMinutes field to given value.

### HasAssignedMinutes

`func (o *Supports) HasAssignedMinutes() bool`

HasAssignedMinutes returns a boolean if a field has been set.

### GetConsumedMinutes

`func (o *Supports) GetConsumedMinutes() int32`

GetConsumedMinutes returns the ConsumedMinutes field if non-nil, zero value otherwise.

### GetConsumedMinutesOk

`func (o *Supports) GetConsumedMinutesOk() (*int32, bool)`

GetConsumedMinutesOk returns a tuple with the ConsumedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsumedMinutes

`func (o *Supports) SetConsumedMinutes(v int32)`

SetConsumedMinutes sets ConsumedMinutes field to given value.

### HasConsumedMinutes

`func (o *Supports) HasConsumedMinutes() bool`

HasConsumedMinutes returns a boolean if a field has been set.

### GetRemainingMinutes

`func (o *Supports) GetRemainingMinutes() int32`

GetRemainingMinutes returns the RemainingMinutes field if non-nil, zero value otherwise.

### GetRemainingMinutesOk

`func (o *Supports) GetRemainingMinutesOk() (*int32, bool)`

GetRemainingMinutesOk returns a tuple with the RemainingMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemainingMinutes

`func (o *Supports) SetRemainingMinutes(v int32)`

SetRemainingMinutes sets RemainingMinutes field to given value.

### HasRemainingMinutes

`func (o *Supports) HasRemainingMinutes() bool`

HasRemainingMinutes returns a boolean if a field has been set.

### GetPreviousConsumedMinutes

`func (o *Supports) GetPreviousConsumedMinutes() int32`

GetPreviousConsumedMinutes returns the PreviousConsumedMinutes field if non-nil, zero value otherwise.

### GetPreviousConsumedMinutesOk

`func (o *Supports) GetPreviousConsumedMinutesOk() (*int32, bool)`

GetPreviousConsumedMinutesOk returns a tuple with the PreviousConsumedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousConsumedMinutes

`func (o *Supports) SetPreviousConsumedMinutes(v int32)`

SetPreviousConsumedMinutes sets PreviousConsumedMinutes field to given value.

### HasPreviousConsumedMinutes

`func (o *Supports) HasPreviousConsumedMinutes() bool`

HasPreviousConsumedMinutes returns a boolean if a field has been set.

### GetCurrentConsumedMinutes

`func (o *Supports) GetCurrentConsumedMinutes() int32`

GetCurrentConsumedMinutes returns the CurrentConsumedMinutes field if non-nil, zero value otherwise.

### GetCurrentConsumedMinutesOk

`func (o *Supports) GetCurrentConsumedMinutesOk() (*int32, bool)`

GetCurrentConsumedMinutesOk returns a tuple with the CurrentConsumedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentConsumedMinutes

`func (o *Supports) SetCurrentConsumedMinutes(v int32)`

SetCurrentConsumedMinutes sets CurrentConsumedMinutes field to given value.

### HasCurrentConsumedMinutes

`func (o *Supports) HasCurrentConsumedMinutes() bool`

HasCurrentConsumedMinutes returns a boolean if a field has been set.

### GetPrepaidConsumedMinutes

`func (o *Supports) GetPrepaidConsumedMinutes() int32`

GetPrepaidConsumedMinutes returns the PrepaidConsumedMinutes field if non-nil, zero value otherwise.

### GetPrepaidConsumedMinutesOk

`func (o *Supports) GetPrepaidConsumedMinutesOk() (*int32, bool)`

GetPrepaidConsumedMinutesOk returns a tuple with the PrepaidConsumedMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrepaidConsumedMinutes

`func (o *Supports) SetPrepaidConsumedMinutes(v int32)`

SetPrepaidConsumedMinutes sets PrepaidConsumedMinutes field to given value.

### HasPrepaidConsumedMinutes

`func (o *Supports) HasPrepaidConsumedMinutes() bool`

HasPrepaidConsumedMinutes returns a boolean if a field has been set.

### GetTransitionMinutes

`func (o *Supports) GetTransitionMinutes() int32`

GetTransitionMinutes returns the TransitionMinutes field if non-nil, zero value otherwise.

### GetTransitionMinutesOk

`func (o *Supports) GetTransitionMinutesOk() (*int32, bool)`

GetTransitionMinutesOk returns a tuple with the TransitionMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransitionMinutes

`func (o *Supports) SetTransitionMinutes(v int32)`

SetTransitionMinutes sets TransitionMinutes field to given value.

### HasTransitionMinutes

`func (o *Supports) HasTransitionMinutes() bool`

HasTransitionMinutes returns a boolean if a field has been set.

### GetStartDate

`func (o *Supports) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *Supports) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *Supports) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *Supports) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetEndDate

`func (o *Supports) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *Supports) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *Supports) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *Supports) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetStatus

`func (o *Supports) GetStatus() SupportsStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Supports) GetStatusOk() (*SupportsStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Supports) SetStatus(v SupportsStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Supports) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *Supports) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *Supports) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *Supports) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *Supports) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *Supports) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *Supports) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *Supports) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *Supports) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetAssignment

`func (o *Supports) GetAssignment() Assignment`

GetAssignment returns the Assignment field if non-nil, zero value otherwise.

### GetAssignmentOk

`func (o *Supports) GetAssignmentOk() (*Assignment, bool)`

GetAssignmentOk returns a tuple with the Assignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignment

`func (o *Supports) SetAssignment(v Assignment)`

SetAssignment sets Assignment field to given value.

### HasAssignment

`func (o *Supports) HasAssignment() bool`

HasAssignment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


