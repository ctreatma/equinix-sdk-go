# ErrorAdditionalInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConstraintCode** | Pointer to **string** | Violated constraint name (simple class name). Can be used to render and localize the validation message by the consumer component such as a frontend application. | [optional] 
**Root** | Pointer to **string** | The root bean. Multiple parameters can be validated during a single validation call, this parameter indicates the validated parameter name (example pagination, requestBody etc.). | [optional] 
**Property** | Pointer to **string** | Represents the JSON path of the property that failed validation. Can be used to map the failed property to the UI input. | [optional] 
**Reason** | Pointer to **string** | Server side constraint violation message. Can be used as a translation fallback. The message will always be in English. | [optional] 

## Methods

### NewErrorAdditionalInfo

`func NewErrorAdditionalInfo() *ErrorAdditionalInfo`

NewErrorAdditionalInfo instantiates a new ErrorAdditionalInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorAdditionalInfoWithDefaults

`func NewErrorAdditionalInfoWithDefaults() *ErrorAdditionalInfo`

NewErrorAdditionalInfoWithDefaults instantiates a new ErrorAdditionalInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConstraintCode

`func (o *ErrorAdditionalInfo) GetConstraintCode() string`

GetConstraintCode returns the ConstraintCode field if non-nil, zero value otherwise.

### GetConstraintCodeOk

`func (o *ErrorAdditionalInfo) GetConstraintCodeOk() (*string, bool)`

GetConstraintCodeOk returns a tuple with the ConstraintCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraintCode

`func (o *ErrorAdditionalInfo) SetConstraintCode(v string)`

SetConstraintCode sets ConstraintCode field to given value.

### HasConstraintCode

`func (o *ErrorAdditionalInfo) HasConstraintCode() bool`

HasConstraintCode returns a boolean if a field has been set.

### GetRoot

`func (o *ErrorAdditionalInfo) GetRoot() string`

GetRoot returns the Root field if non-nil, zero value otherwise.

### GetRootOk

`func (o *ErrorAdditionalInfo) GetRootOk() (*string, bool)`

GetRootOk returns a tuple with the Root field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoot

`func (o *ErrorAdditionalInfo) SetRoot(v string)`

SetRoot sets Root field to given value.

### HasRoot

`func (o *ErrorAdditionalInfo) HasRoot() bool`

HasRoot returns a boolean if a field has been set.

### GetProperty

`func (o *ErrorAdditionalInfo) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *ErrorAdditionalInfo) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *ErrorAdditionalInfo) SetProperty(v string)`

SetProperty sets Property field to given value.

### HasProperty

`func (o *ErrorAdditionalInfo) HasProperty() bool`

HasProperty returns a boolean if a field has been set.

### GetReason

`func (o *ErrorAdditionalInfo) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ErrorAdditionalInfo) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ErrorAdditionalInfo) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *ErrorAdditionalInfo) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


