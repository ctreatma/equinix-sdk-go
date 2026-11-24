# ErrorItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ErrorCode** | **string** | Error code | 
**ErrorMessage** | **string** | Error message | 
**Details** | Pointer to **string** | Error details | [optional] 
**CorrelationId** | Pointer to **string** | Correlation ID identyfying the request | [optional] 
**Help** | Pointer to **string** | Link to the help information | [optional] 
**AdditionalInfo** | Pointer to [**[]AdditionalInfo**](AdditionalInfo.md) | Collection of additional information | [optional] 

## Methods

### NewErrorItem

`func NewErrorItem(errorCode string, errorMessage string, ) *ErrorItem`

NewErrorItem instantiates a new ErrorItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorItemWithDefaults

`func NewErrorItemWithDefaults() *ErrorItem`

NewErrorItemWithDefaults instantiates a new ErrorItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrorCode

`func (o *ErrorItem) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *ErrorItem) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *ErrorItem) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetErrorMessage

`func (o *ErrorItem) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ErrorItem) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ErrorItem) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### GetDetails

`func (o *ErrorItem) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ErrorItem) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ErrorItem) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ErrorItem) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCorrelationId

`func (o *ErrorItem) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *ErrorItem) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *ErrorItem) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *ErrorItem) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetHelp

`func (o *ErrorItem) GetHelp() string`

GetHelp returns the Help field if non-nil, zero value otherwise.

### GetHelpOk

`func (o *ErrorItem) GetHelpOk() (*string, bool)`

GetHelpOk returns a tuple with the Help field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHelp

`func (o *ErrorItem) SetHelp(v string)`

SetHelp sets Help field to given value.

### HasHelp

`func (o *ErrorItem) HasHelp() bool`

HasHelp returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *ErrorItem) GetAdditionalInfo() []AdditionalInfo`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *ErrorItem) GetAdditionalInfoOk() (*[]AdditionalInfo, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *ErrorItem) SetAdditionalInfo(v []AdditionalInfo)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *ErrorItem) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


