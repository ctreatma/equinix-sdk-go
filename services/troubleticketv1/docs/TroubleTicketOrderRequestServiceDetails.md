# TroubleTicketOrderRequestServiceDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IncidentDateTime** | **time.Time** | Date and time of received event (ISO Date)&lt;br&gt; Cannot be in the future.  | 
**ProblemCode** | [**TroubleTicketOrderRequestServiceDetailsProblemCode**](TroubleTicketOrderRequestServiceDetailsProblemCode.md) |  | 
**ServiceName** | Pointer to **string** | Subcategory for managed services. It will be a mandatory field for managed services trouble ticket | [optional] 
**CallFromCage** | Pointer to **bool** | Allow the technician to call from the cage. | [optional] 
**NeedSupportFromASubmarineCableStationEngineer** | Pointer to **bool** | This flag is only applicable to Submarine Cable IBXs | [optional] 
**AdditionalDetails** | Pointer to **string** | Use this field to enter any information that applies to this trouble ticket request. | [optional] 

## Methods

### NewTroubleTicketOrderRequestServiceDetails

`func NewTroubleTicketOrderRequestServiceDetails(incidentDateTime time.Time, problemCode TroubleTicketOrderRequestServiceDetailsProblemCode, ) *TroubleTicketOrderRequestServiceDetails`

NewTroubleTicketOrderRequestServiceDetails instantiates a new TroubleTicketOrderRequestServiceDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketOrderRequestServiceDetailsWithDefaults

`func NewTroubleTicketOrderRequestServiceDetailsWithDefaults() *TroubleTicketOrderRequestServiceDetails`

NewTroubleTicketOrderRequestServiceDetailsWithDefaults instantiates a new TroubleTicketOrderRequestServiceDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIncidentDateTime

`func (o *TroubleTicketOrderRequestServiceDetails) GetIncidentDateTime() time.Time`

GetIncidentDateTime returns the IncidentDateTime field if non-nil, zero value otherwise.

### GetIncidentDateTimeOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetIncidentDateTimeOk() (*time.Time, bool)`

GetIncidentDateTimeOk returns a tuple with the IncidentDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncidentDateTime

`func (o *TroubleTicketOrderRequestServiceDetails) SetIncidentDateTime(v time.Time)`

SetIncidentDateTime sets IncidentDateTime field to given value.


### GetProblemCode

`func (o *TroubleTicketOrderRequestServiceDetails) GetProblemCode() TroubleTicketOrderRequestServiceDetailsProblemCode`

GetProblemCode returns the ProblemCode field if non-nil, zero value otherwise.

### GetProblemCodeOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetProblemCodeOk() (*TroubleTicketOrderRequestServiceDetailsProblemCode, bool)`

GetProblemCodeOk returns a tuple with the ProblemCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProblemCode

`func (o *TroubleTicketOrderRequestServiceDetails) SetProblemCode(v TroubleTicketOrderRequestServiceDetailsProblemCode)`

SetProblemCode sets ProblemCode field to given value.


### GetServiceName

`func (o *TroubleTicketOrderRequestServiceDetails) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *TroubleTicketOrderRequestServiceDetails) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.

### HasServiceName

`func (o *TroubleTicketOrderRequestServiceDetails) HasServiceName() bool`

HasServiceName returns a boolean if a field has been set.

### GetCallFromCage

`func (o *TroubleTicketOrderRequestServiceDetails) GetCallFromCage() bool`

GetCallFromCage returns the CallFromCage field if non-nil, zero value otherwise.

### GetCallFromCageOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetCallFromCageOk() (*bool, bool)`

GetCallFromCageOk returns a tuple with the CallFromCage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallFromCage

`func (o *TroubleTicketOrderRequestServiceDetails) SetCallFromCage(v bool)`

SetCallFromCage sets CallFromCage field to given value.

### HasCallFromCage

`func (o *TroubleTicketOrderRequestServiceDetails) HasCallFromCage() bool`

HasCallFromCage returns a boolean if a field has been set.

### GetNeedSupportFromASubmarineCableStationEngineer

`func (o *TroubleTicketOrderRequestServiceDetails) GetNeedSupportFromASubmarineCableStationEngineer() bool`

GetNeedSupportFromASubmarineCableStationEngineer returns the NeedSupportFromASubmarineCableStationEngineer field if non-nil, zero value otherwise.

### GetNeedSupportFromASubmarineCableStationEngineerOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetNeedSupportFromASubmarineCableStationEngineerOk() (*bool, bool)`

GetNeedSupportFromASubmarineCableStationEngineerOk returns a tuple with the NeedSupportFromASubmarineCableStationEngineer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedSupportFromASubmarineCableStationEngineer

`func (o *TroubleTicketOrderRequestServiceDetails) SetNeedSupportFromASubmarineCableStationEngineer(v bool)`

SetNeedSupportFromASubmarineCableStationEngineer sets NeedSupportFromASubmarineCableStationEngineer field to given value.

### HasNeedSupportFromASubmarineCableStationEngineer

`func (o *TroubleTicketOrderRequestServiceDetails) HasNeedSupportFromASubmarineCableStationEngineer() bool`

HasNeedSupportFromASubmarineCableStationEngineer returns a boolean if a field has been set.

### GetAdditionalDetails

`func (o *TroubleTicketOrderRequestServiceDetails) GetAdditionalDetails() string`

GetAdditionalDetails returns the AdditionalDetails field if non-nil, zero value otherwise.

### GetAdditionalDetailsOk

`func (o *TroubleTicketOrderRequestServiceDetails) GetAdditionalDetailsOk() (*string, bool)`

GetAdditionalDetailsOk returns a tuple with the AdditionalDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalDetails

`func (o *TroubleTicketOrderRequestServiceDetails) SetAdditionalDetails(v string)`

SetAdditionalDetails sets AdditionalDetails field to given value.

### HasAdditionalDetails

`func (o *TroubleTicketOrderRequestServiceDetails) HasAdditionalDetails() bool`

HasAdditionalDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


