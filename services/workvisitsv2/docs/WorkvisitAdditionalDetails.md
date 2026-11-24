# WorkvisitAdditionalDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OpenCabinet** | Pointer to **bool** | Equinix Technicial to help to open the cage and an additional charge incured by the customer | [optional] [default to false]
**VisitStartDateTime** | Pointer to **time.Time** |  | [optional] 
**VisitEndDateTime** | Pointer to **time.Time** |  | [optional] 
**Visitors** | Pointer to [**[]WorkvisitAdditionalDetailsVisitorsInner**](WorkvisitAdditionalDetailsVisitorsInner.md) | The maximum limit for non registered visitors is 50 | [optional] 

## Methods

### NewWorkvisitAdditionalDetails

`func NewWorkvisitAdditionalDetails() *WorkvisitAdditionalDetails`

NewWorkvisitAdditionalDetails instantiates a new WorkvisitAdditionalDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitAdditionalDetailsWithDefaults

`func NewWorkvisitAdditionalDetailsWithDefaults() *WorkvisitAdditionalDetails`

NewWorkvisitAdditionalDetailsWithDefaults instantiates a new WorkvisitAdditionalDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOpenCabinet

`func (o *WorkvisitAdditionalDetails) GetOpenCabinet() bool`

GetOpenCabinet returns the OpenCabinet field if non-nil, zero value otherwise.

### GetOpenCabinetOk

`func (o *WorkvisitAdditionalDetails) GetOpenCabinetOk() (*bool, bool)`

GetOpenCabinetOk returns a tuple with the OpenCabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCabinet

`func (o *WorkvisitAdditionalDetails) SetOpenCabinet(v bool)`

SetOpenCabinet sets OpenCabinet field to given value.

### HasOpenCabinet

`func (o *WorkvisitAdditionalDetails) HasOpenCabinet() bool`

HasOpenCabinet returns a boolean if a field has been set.

### GetVisitStartDateTime

`func (o *WorkvisitAdditionalDetails) GetVisitStartDateTime() time.Time`

GetVisitStartDateTime returns the VisitStartDateTime field if non-nil, zero value otherwise.

### GetVisitStartDateTimeOk

`func (o *WorkvisitAdditionalDetails) GetVisitStartDateTimeOk() (*time.Time, bool)`

GetVisitStartDateTimeOk returns a tuple with the VisitStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitStartDateTime

`func (o *WorkvisitAdditionalDetails) SetVisitStartDateTime(v time.Time)`

SetVisitStartDateTime sets VisitStartDateTime field to given value.

### HasVisitStartDateTime

`func (o *WorkvisitAdditionalDetails) HasVisitStartDateTime() bool`

HasVisitStartDateTime returns a boolean if a field has been set.

### GetVisitEndDateTime

`func (o *WorkvisitAdditionalDetails) GetVisitEndDateTime() time.Time`

GetVisitEndDateTime returns the VisitEndDateTime field if non-nil, zero value otherwise.

### GetVisitEndDateTimeOk

`func (o *WorkvisitAdditionalDetails) GetVisitEndDateTimeOk() (*time.Time, bool)`

GetVisitEndDateTimeOk returns a tuple with the VisitEndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitEndDateTime

`func (o *WorkvisitAdditionalDetails) SetVisitEndDateTime(v time.Time)`

SetVisitEndDateTime sets VisitEndDateTime field to given value.

### HasVisitEndDateTime

`func (o *WorkvisitAdditionalDetails) HasVisitEndDateTime() bool`

HasVisitEndDateTime returns a boolean if a field has been set.

### GetVisitors

`func (o *WorkvisitAdditionalDetails) GetVisitors() []WorkvisitAdditionalDetailsVisitorsInner`

GetVisitors returns the Visitors field if non-nil, zero value otherwise.

### GetVisitorsOk

`func (o *WorkvisitAdditionalDetails) GetVisitorsOk() (*[]WorkvisitAdditionalDetailsVisitorsInner, bool)`

GetVisitorsOk returns a tuple with the Visitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitors

`func (o *WorkvisitAdditionalDetails) SetVisitors(v []WorkvisitAdditionalDetailsVisitorsInner)`

SetVisitors sets Visitors field to given value.

### HasVisitors

`func (o *WorkvisitAdditionalDetails) HasVisitors() bool`

HasVisitors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


