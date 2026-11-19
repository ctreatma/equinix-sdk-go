# ErrorInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorCode** | **string** | Error Code | 
**ErrorMessage** | **string** | Error Message | 
**Details** | Pointer to **string** | Error Details | [optional] 
**CorrelationId** | Pointer to **string** | Correlation ID to trace the error back | [optional] 
**Help** | Pointer to **string** | URL to a help page for the corresponding errorCode | [optional] 
**AdditionalInfo** | Pointer to [**[]ErrorAdditionalInfo**](ErrorAdditionalInfo.md) | Additional information about the error | [optional] 

## Methods

### NewErrorInner

`func NewErrorInner(errorCode string, errorMessage string, ) *ErrorInner`

NewErrorInner instantiates a new ErrorInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorInnerWithDefaults

`func NewErrorInnerWithDefaults() *ErrorInner`

NewErrorInnerWithDefaults instantiates a new ErrorInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorCode

`func (o *ErrorInner) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *ErrorInner) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *ErrorInner) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetErrorMessage

`func (o *ErrorInner) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ErrorInner) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ErrorInner) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### GetDetails

`func (o *ErrorInner) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ErrorInner) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ErrorInner) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ErrorInner) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCorrelationId

`func (o *ErrorInner) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *ErrorInner) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *ErrorInner) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *ErrorInner) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetHelp

`func (o *ErrorInner) GetHelp() string`

GetHelp returns the Help field if non-nil, zero value otherwise.

### GetHelpOk

`func (o *ErrorInner) GetHelpOk() (*string, bool)`

GetHelpOk returns a tuple with the Help field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelp

`func (o *ErrorInner) SetHelp(v string)`

SetHelp sets Help field to given value.

### HasHelp

`func (o *ErrorInner) HasHelp() bool`

HasHelp returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *ErrorInner) GetAdditionalInfo() []ErrorAdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *ErrorInner) GetAdditionalInfoOk() (*[]ErrorAdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *ErrorInner) SetAdditionalInfo(v []ErrorAdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *ErrorInner) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


