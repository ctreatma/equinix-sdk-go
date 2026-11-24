# DeviceRebootResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceUUID** | Pointer to **string** | Unique Id of the device. | [optional] 
**Status** | Pointer to [**DeviceRebootResponseStatus**](DeviceRebootResponseStatus.md) |  | [optional] 
**RequestedBy** | Pointer to **string** | Requested by | [optional] 
**RequestedDateTime** | Pointer to **time.Time** | Requested date | [optional] 
**CompletiondDateTime** | Pointer to **time.Time** | Completion date | [optional] 

## Methods

### NewDeviceRebootResponse

`func NewDeviceRebootResponse() *DeviceRebootResponse`

NewDeviceRebootResponse instantiates a new DeviceRebootResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceRebootResponseWithDefaults

`func NewDeviceRebootResponseWithDefaults() *DeviceRebootResponse`

NewDeviceRebootResponseWithDefaults instantiates a new DeviceRebootResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceUUID

`func (o *DeviceRebootResponse) GetDeviceUUID() string`

GetDeviceUUID returns the DeviceUUID field if non-nil, zero value otherwise.

### GetDeviceUUIDOk

`func (o *DeviceRebootResponse) GetDeviceUUIDOk() (*string, bool)`

GetDeviceUUIDOk returns a tuple with the DeviceUUID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceUUID

`func (o *DeviceRebootResponse) SetDeviceUUID(v string)`

SetDeviceUUID sets DeviceUUID field to given value.

### HasDeviceUUID

`func (o *DeviceRebootResponse) HasDeviceUUID() bool`

HasDeviceUUID returns a boolean if a field has been set.

### GetStatus

`func (o *DeviceRebootResponse) GetStatus() DeviceRebootResponseStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeviceRebootResponse) GetStatusOk() (*DeviceRebootResponseStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeviceRebootResponse) SetStatus(v DeviceRebootResponseStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DeviceRebootResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetRequestedBy

`func (o *DeviceRebootResponse) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *DeviceRebootResponse) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *DeviceRebootResponse) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.

### HasRequestedBy

`func (o *DeviceRebootResponse) HasRequestedBy() bool`

HasRequestedBy returns a boolean if a field has been set.

### GetRequestedDateTime

`func (o *DeviceRebootResponse) GetRequestedDateTime() time.Time`

GetRequestedDateTime returns the RequestedDateTime field if non-nil, zero value otherwise.

### GetRequestedDateTimeOk

`func (o *DeviceRebootResponse) GetRequestedDateTimeOk() (*time.Time, bool)`

GetRequestedDateTimeOk returns a tuple with the RequestedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDateTime

`func (o *DeviceRebootResponse) SetRequestedDateTime(v time.Time)`

SetRequestedDateTime sets RequestedDateTime field to given value.

### HasRequestedDateTime

`func (o *DeviceRebootResponse) HasRequestedDateTime() bool`

HasRequestedDateTime returns a boolean if a field has been set.

### GetCompletiondDateTime

`func (o *DeviceRebootResponse) GetCompletiondDateTime() time.Time`

GetCompletiondDateTime returns the CompletiondDateTime field if non-nil, zero value otherwise.

### GetCompletiondDateTimeOk

`func (o *DeviceRebootResponse) GetCompletiondDateTimeOk() (*time.Time, bool)`

GetCompletiondDateTimeOk returns a tuple with the CompletiondDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletiondDateTime

`func (o *DeviceRebootResponse) SetCompletiondDateTime(v time.Time)`

SetCompletiondDateTime sets CompletiondDateTime field to given value.

### HasCompletiondDateTime

`func (o *DeviceRebootResponse) HasCompletiondDateTime() bool`

HasCompletiondDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


