# ErrorAdditionalInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Property** | **string** | The property that caused the error | 
**Reason** | **string** | The reason why the property caused the error | 

## Methods

### NewErrorAdditionalInfo

`func NewErrorAdditionalInfo(property string, reason string, ) *ErrorAdditionalInfo`

NewErrorAdditionalInfo instantiates a new ErrorAdditionalInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorAdditionalInfoWithDefaults

`func NewErrorAdditionalInfoWithDefaults() *ErrorAdditionalInfo`

NewErrorAdditionalInfoWithDefaults instantiates a new ErrorAdditionalInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


