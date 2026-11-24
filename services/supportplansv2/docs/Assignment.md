# Assignment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Customer name of assigned plans | [optional] 
**AccountNumber** | Pointer to **string** | Customer account number of assigned plans | [optional] 
**Status** | Pointer to [**AssignmentStatus**](AssignmentStatus.md) |  | [optional] 
**Eligible** | Pointer to **bool** | When &#x60;true&#x60;, plans can be assigned to customers | [optional] 

## Methods

### NewAssignment

`func NewAssignment() *Assignment`

NewAssignment instantiates a new Assignment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssignmentWithDefaults

`func NewAssignmentWithDefaults() *Assignment`

NewAssignmentWithDefaults instantiates a new Assignment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Assignment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Assignment) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Assignment) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Assignment) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *Assignment) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *Assignment) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *Assignment) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *Assignment) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetStatus

`func (o *Assignment) GetStatus() AssignmentStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Assignment) GetStatusOk() (*AssignmentStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Assignment) SetStatus(v AssignmentStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Assignment) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEligible

`func (o *Assignment) GetEligible() bool`

GetEligible returns the Eligible field if non-nil, zero value otherwise.

### GetEligibleOk

`func (o *Assignment) GetEligibleOk() (*bool, bool)`

GetEligibleOk returns a tuple with the Eligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligible

`func (o *Assignment) SetEligible(v bool)`

SetEligible sets Eligible field to given value.

### HasEligible

`func (o *Assignment) HasEligible() bool`

HasEligible returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


