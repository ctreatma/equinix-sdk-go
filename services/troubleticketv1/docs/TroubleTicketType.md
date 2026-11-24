# TroubleTicketType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | **string** | Type of trouble ticket. | 
**Code** | **string** | Code of trouble ticket. Use this code while placing Trouble Ticket Order | 
**Description** | **string** | Description trouble ticket. | 
**Severity** | **string** | Severity of trouble ticket. | 
**AdditionalDetails** | Pointer to [**TroubleTicketTypeAdditionalDetails**](TroubleTicketTypeAdditionalDetails.md) |  | [optional] 

## Methods

### NewTroubleTicketType

`func NewTroubleTicketType(category string, code string, description string, severity string, ) *TroubleTicketType`

NewTroubleTicketType instantiates a new TroubleTicketType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketTypeWithDefaults

`func NewTroubleTicketTypeWithDefaults() *TroubleTicketType`

NewTroubleTicketTypeWithDefaults instantiates a new TroubleTicketType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *TroubleTicketType) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *TroubleTicketType) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *TroubleTicketType) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetCode

`func (o *TroubleTicketType) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TroubleTicketType) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TroubleTicketType) SetCode(v string)`

SetCode sets Code field to given value.


### GetDescription

`func (o *TroubleTicketType) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TroubleTicketType) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TroubleTicketType) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetSeverity

`func (o *TroubleTicketType) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *TroubleTicketType) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *TroubleTicketType) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetAdditionalDetails

`func (o *TroubleTicketType) GetAdditionalDetails() TroubleTicketTypeAdditionalDetails`

GetAdditionalDetails returns the AdditionalDetails field if non-nil, zero value otherwise.

### GetAdditionalDetailsOk

`func (o *TroubleTicketType) GetAdditionalDetailsOk() (*TroubleTicketTypeAdditionalDetails, bool)`

GetAdditionalDetailsOk returns a tuple with the AdditionalDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalDetails

`func (o *TroubleTicketType) SetAdditionalDetails(v TroubleTicketTypeAdditionalDetails)`

SetAdditionalDetails sets AdditionalDetails field to given value.

### HasAdditionalDetails

`func (o *TroubleTicketType) HasAdditionalDetails() bool`

HasAdditionalDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


