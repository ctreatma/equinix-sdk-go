# LastRevBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewLastRevBody

`func NewLastRevBody(lastRev string, ) *LastRevBody`

NewLastRevBody instantiates a new LastRevBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLastRevBodyWithDefaults

`func NewLastRevBodyWithDefaults() *LastRevBody`

NewLastRevBodyWithDefaults instantiates a new LastRevBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLastRev

`func (o *LastRevBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *LastRevBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *LastRevBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


