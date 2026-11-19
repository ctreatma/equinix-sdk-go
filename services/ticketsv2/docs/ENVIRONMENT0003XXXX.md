# ENVIRONMENT0003XXXX

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CallFromCage** | Pointer to **bool** | Requirement for the IBX technician to call the technical contact from the cage. If true, IBX technician will call the technical contact from the cage. | [optional] [default to false]
**Availability** | Pointer to [**COMMONREQUESTCODE00000008Availability**](COMMONREQUESTCODE00000008Availability.md) |  | [optional] [default to COMMONREQUESTCODE00000008AVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 
**SubmarineEngineerRequired** | Pointer to **bool** | Requirement for submarine cable station engineering support. | [optional] [default to false]

## Methods

### NewENVIRONMENT0003XXXX

`func NewENVIRONMENT0003XXXX() *ENVIRONMENT0003XXXX`

NewENVIRONMENT0003XXXX instantiates a new ENVIRONMENT0003XXXX object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewENVIRONMENT0003XXXXWithDefaults

`func NewENVIRONMENT0003XXXXWithDefaults() *ENVIRONMENT0003XXXX`

NewENVIRONMENT0003XXXXWithDefaults instantiates a new ENVIRONMENT0003XXXX object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCallFromCage

`func (o *ENVIRONMENT0003XXXX) GetCallFromCage() bool`

GetCallFromCage returns the CallFromCage field if non-nil, zero value otherwise.

### GetCallFromCageOk

`func (o *ENVIRONMENT0003XXXX) GetCallFromCageOk() (*bool, bool)`

GetCallFromCageOk returns a tuple with the CallFromCage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallFromCage

`func (o *ENVIRONMENT0003XXXX) SetCallFromCage(v bool)`

SetCallFromCage sets CallFromCage field to given value.

### HasCallFromCage

`func (o *ENVIRONMENT0003XXXX) HasCallFromCage() bool`

HasCallFromCage returns a boolean if a field has been set.

### GetAvailability

`func (o *ENVIRONMENT0003XXXX) GetAvailability() COMMONREQUESTCODE00000008Availability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ENVIRONMENT0003XXXX) GetAvailabilityOk() (*COMMONREQUESTCODE00000008Availability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ENVIRONMENT0003XXXX) SetAvailability(v COMMONREQUESTCODE00000008Availability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ENVIRONMENT0003XXXX) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *ENVIRONMENT0003XXXX) GetTimezone() TIMEZONELIST`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *ENVIRONMENT0003XXXX) GetTimezoneOk() (*TIMEZONELIST, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *ENVIRONMENT0003XXXX) SetTimezone(v TIMEZONELIST)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *ENVIRONMENT0003XXXX) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetSubmarineEngineerRequired

`func (o *ENVIRONMENT0003XXXX) GetSubmarineEngineerRequired() bool`

GetSubmarineEngineerRequired returns the SubmarineEngineerRequired field if non-nil, zero value otherwise.

### GetSubmarineEngineerRequiredOk

`func (o *ENVIRONMENT0003XXXX) GetSubmarineEngineerRequiredOk() (*bool, bool)`

GetSubmarineEngineerRequiredOk returns a tuple with the SubmarineEngineerRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmarineEngineerRequired

`func (o *ENVIRONMENT0003XXXX) SetSubmarineEngineerRequired(v bool)`

SetSubmarineEngineerRequired sets SubmarineEngineerRequired field to given value.

### HasSubmarineEngineerRequired

`func (o *ENVIRONMENT0003XXXX) HasSubmarineEngineerRequired() bool`

HasSubmarineEngineerRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


