# ErrorModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorCode** | **string** |  | 
**ErrorMessage** | **string** |  | 
**CorrelationId** | **string** |  | 
**Details** | Pointer to **string** |  | [optional] 
**Help** | Pointer to **string** |  | [optional] 
**AdditionalInfo** | Pointer to **[]map[string]string** |  | [optional] 

## Methods

### NewErrorModel

`func NewErrorModel(errorCode string, errorMessage string, correlationId string, ) *ErrorModel`

NewErrorModel instantiates a new ErrorModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorModelWithDefaults

`func NewErrorModelWithDefaults() *ErrorModel`

NewErrorModelWithDefaults instantiates a new ErrorModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorCode

`func (o *ErrorModel) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *ErrorModel) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *ErrorModel) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetErrorMessage

`func (o *ErrorModel) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ErrorModel) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ErrorModel) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### GetCorrelationId

`func (o *ErrorModel) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *ErrorModel) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *ErrorModel) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetDetails

`func (o *ErrorModel) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ErrorModel) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ErrorModel) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ErrorModel) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetHelp

`func (o *ErrorModel) GetHelp() string`

GetHelp returns the Help field if non-nil, zero value otherwise.

### GetHelpOk

`func (o *ErrorModel) GetHelpOk() (*string, bool)`

GetHelpOk returns a tuple with the Help field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelp

`func (o *ErrorModel) SetHelp(v string)`

SetHelp sets Help field to given value.

### HasHelp

`func (o *ErrorModel) HasHelp() bool`

HasHelp returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *ErrorModel) GetAdditionalInfo() []map[string]string`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *ErrorModel) GetAdditionalInfoOk() (*[]map[string]string, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *ErrorModel) SetAdditionalInfo(v []map[string]string)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *ErrorModel) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


