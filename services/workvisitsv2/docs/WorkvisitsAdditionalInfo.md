# WorkvisitsAdditionalInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VisitStartDateTime** | Pointer to **time.Time** | Requested start date and time of the work visit in UTC timezone in ISO 8601 format | [optional] 
**VisitEndDateTime** | Pointer to **time.Time** | Requested end date and time of the work visit in UTC timezone in ISO 8601 format | [optional] 
**OpenCabinet** | Pointer to **bool** | This is an additional request for Equinix to open your secure cabinet during the work visit.  When &#x60;true&#x60;, Equinix staff will open cabinet during work visit. | [optional] [default to false]

## Methods

### NewWorkvisitsAdditionalInfo

`func NewWorkvisitsAdditionalInfo() *WorkvisitsAdditionalInfo`

NewWorkvisitsAdditionalInfo instantiates a new WorkvisitsAdditionalInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitsAdditionalInfoWithDefaults

`func NewWorkvisitsAdditionalInfoWithDefaults() *WorkvisitsAdditionalInfo`

NewWorkvisitsAdditionalInfoWithDefaults instantiates a new WorkvisitsAdditionalInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVisitStartDateTime

`func (o *WorkvisitsAdditionalInfo) GetVisitStartDateTime() time.Time`

GetVisitStartDateTime returns the VisitStartDateTime field if non-nil, zero value otherwise.

### GetVisitStartDateTimeOk

`func (o *WorkvisitsAdditionalInfo) GetVisitStartDateTimeOk() (*time.Time, bool)`

GetVisitStartDateTimeOk returns a tuple with the VisitStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitStartDateTime

`func (o *WorkvisitsAdditionalInfo) SetVisitStartDateTime(v time.Time)`

SetVisitStartDateTime sets VisitStartDateTime field to given value.

### HasVisitStartDateTime

`func (o *WorkvisitsAdditionalInfo) HasVisitStartDateTime() bool`

HasVisitStartDateTime returns a boolean if a field has been set.

### GetVisitEndDateTime

`func (o *WorkvisitsAdditionalInfo) GetVisitEndDateTime() time.Time`

GetVisitEndDateTime returns the VisitEndDateTime field if non-nil, zero value otherwise.

### GetVisitEndDateTimeOk

`func (o *WorkvisitsAdditionalInfo) GetVisitEndDateTimeOk() (*time.Time, bool)`

GetVisitEndDateTimeOk returns a tuple with the VisitEndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitEndDateTime

`func (o *WorkvisitsAdditionalInfo) SetVisitEndDateTime(v time.Time)`

SetVisitEndDateTime sets VisitEndDateTime field to given value.

### HasVisitEndDateTime

`func (o *WorkvisitsAdditionalInfo) HasVisitEndDateTime() bool`

HasVisitEndDateTime returns a boolean if a field has been set.

### GetOpenCabinet

`func (o *WorkvisitsAdditionalInfo) GetOpenCabinet() bool`

GetOpenCabinet returns the OpenCabinet field if non-nil, zero value otherwise.

### GetOpenCabinetOk

`func (o *WorkvisitsAdditionalInfo) GetOpenCabinetOk() (*bool, bool)`

GetOpenCabinetOk returns a tuple with the OpenCabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCabinet

`func (o *WorkvisitsAdditionalInfo) SetOpenCabinet(v bool)`

SetOpenCabinet sets OpenCabinet field to given value.

### HasOpenCabinet

`func (o *WorkvisitsAdditionalInfo) HasOpenCabinet() bool`

HasOpenCabinet returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


