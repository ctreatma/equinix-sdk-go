# TicketCodeDeprecation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SunsetAt** | Pointer to **time.Time** | ISO 8601 date-time after which this code will no longer be accepted. | [optional] 
**Successor** | Pointer to **NullableString** | Replacement ticket code, or null if no direct successor exists. | [optional] 

## Methods

### NewTicketCodeDeprecation

`func NewTicketCodeDeprecation() *TicketCodeDeprecation`

NewTicketCodeDeprecation instantiates a new TicketCodeDeprecation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketCodeDeprecationWithDefaults

`func NewTicketCodeDeprecationWithDefaults() *TicketCodeDeprecation`

NewTicketCodeDeprecationWithDefaults instantiates a new TicketCodeDeprecation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSunsetAt

`func (o *TicketCodeDeprecation) GetSunsetAt() time.Time`

GetSunsetAt returns the SunsetAt field if non-nil, zero value otherwise.

### GetSunsetAtOk

`func (o *TicketCodeDeprecation) GetSunsetAtOk() (*time.Time, bool)`

GetSunsetAtOk returns a tuple with the SunsetAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSunsetAt

`func (o *TicketCodeDeprecation) SetSunsetAt(v time.Time)`

SetSunsetAt sets SunsetAt field to given value.

### HasSunsetAt

`func (o *TicketCodeDeprecation) HasSunsetAt() bool`

HasSunsetAt returns a boolean if a field has been set.

### GetSuccessor

`func (o *TicketCodeDeprecation) GetSuccessor() string`

GetSuccessor returns the Successor field if non-nil, zero value otherwise.

### GetSuccessorOk

`func (o *TicketCodeDeprecation) GetSuccessorOk() (*string, bool)`

GetSuccessorOk returns a tuple with the Successor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessor

`func (o *TicketCodeDeprecation) SetSuccessor(v string)`

SetSuccessor sets Successor field to given value.

### HasSuccessor

`func (o *TicketCodeDeprecation) HasSuccessor() bool`

HasSuccessor returns a boolean if a field has been set.

### SetSuccessorNil

`func (o *TicketCodeDeprecation) SetSuccessorNil(b bool)`

 SetSuccessorNil sets the value for Successor to be an explicit nil

### UnsetSuccessor
`func (o *TicketCodeDeprecation) UnsetSuccessor()`

UnsetSuccessor ensures that no value is present for Successor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


