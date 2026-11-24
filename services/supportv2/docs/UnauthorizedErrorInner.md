# UnauthorizedErrorInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CorrelationId** | Pointer to **string** | Correlation ID to trace the error back | [optional] 
**ErrorMessage** | **string** | Error Message | 
**ErrorCode** | **string** | Error Code | 
**Details** | Pointer to **string** | Error Details | [optional] 
**Help** | Pointer to **string** | URL to a help page for the corresponding errorCode | [optional] 
**AdditionalInfo** | Pointer to [**[]ErrorAdditionalInfo**](ErrorAdditionalInfo.md) | Additional information about the error | [optional] 

## Methods

### NewUnauthorizedErrorInner

`func NewUnauthorizedErrorInner(errorMessage string, errorCode string, ) *UnauthorizedErrorInner`

NewUnauthorizedErrorInner instantiates a new UnauthorizedErrorInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnauthorizedErrorInnerWithDefaults

`func NewUnauthorizedErrorInnerWithDefaults() *UnauthorizedErrorInner`

NewUnauthorizedErrorInnerWithDefaults instantiates a new UnauthorizedErrorInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrelationId

`func (o *UnauthorizedErrorInner) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *UnauthorizedErrorInner) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *UnauthorizedErrorInner) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *UnauthorizedErrorInner) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetErrorMessage

`func (o *UnauthorizedErrorInner) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *UnauthorizedErrorInner) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *UnauthorizedErrorInner) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### GetErrorCode

`func (o *UnauthorizedErrorInner) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *UnauthorizedErrorInner) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *UnauthorizedErrorInner) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetDetails

`func (o *UnauthorizedErrorInner) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *UnauthorizedErrorInner) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *UnauthorizedErrorInner) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *UnauthorizedErrorInner) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetHelp

`func (o *UnauthorizedErrorInner) GetHelp() string`

GetHelp returns the Help field if non-nil, zero value otherwise.

### GetHelpOk

`func (o *UnauthorizedErrorInner) GetHelpOk() (*string, bool)`

GetHelpOk returns a tuple with the Help field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelp

`func (o *UnauthorizedErrorInner) SetHelp(v string)`

SetHelp sets Help field to given value.

### HasHelp

`func (o *UnauthorizedErrorInner) HasHelp() bool`

HasHelp returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *UnauthorizedErrorInner) GetAdditionalInfo() []ErrorAdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *UnauthorizedErrorInner) GetAdditionalInfoOk() (*[]ErrorAdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *UnauthorizedErrorInner) SetAdditionalInfo(v []ErrorAdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *UnauthorizedErrorInner) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


