# FieldErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorCode** | **string** | Error code | 
**ErrorMessage** | **string** | Error message | 
**AdditionalInfo** | Pointer to [**[]AdditionalInfo**](AdditionalInfo.md) | More information about the error | [optional] 
**Details** | Pointer to **string** | The property that caused the error | [optional] 
**Help** | Pointer to **string** | help String | [optional] 
**CorrelationId** | Pointer to **string** | correlationId | [optional] 

## Methods

### NewFieldErrorResponse

`func NewFieldErrorResponse(errorCode string, errorMessage string, ) *FieldErrorResponse`

NewFieldErrorResponse instantiates a new FieldErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldErrorResponseWithDefaults

`func NewFieldErrorResponseWithDefaults() *FieldErrorResponse`

NewFieldErrorResponseWithDefaults instantiates a new FieldErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorCode

`func (o *FieldErrorResponse) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *FieldErrorResponse) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *FieldErrorResponse) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetErrorMessage

`func (o *FieldErrorResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *FieldErrorResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *FieldErrorResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### GetAdditionalInfo

`func (o *FieldErrorResponse) GetAdditionalInfo() []AdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *FieldErrorResponse) GetAdditionalInfoOk() (*[]AdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *FieldErrorResponse) SetAdditionalInfo(v []AdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *FieldErrorResponse) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.

### GetDetails

`func (o *FieldErrorResponse) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *FieldErrorResponse) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *FieldErrorResponse) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *FieldErrorResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetHelp

`func (o *FieldErrorResponse) GetHelp() string`

GetHelp returns the Help field if non-nil, zero value otherwise.

### GetHelpOk

`func (o *FieldErrorResponse) GetHelpOk() (*string, bool)`

GetHelpOk returns a tuple with the Help field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelp

`func (o *FieldErrorResponse) SetHelp(v string)`

SetHelp sets Help field to given value.

### HasHelp

`func (o *FieldErrorResponse) HasHelp() bool`

HasHelp returns a boolean if a field has been set.

### GetCorrelationId

`func (o *FieldErrorResponse) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *FieldErrorResponse) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *FieldErrorResponse) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *FieldErrorResponse) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


