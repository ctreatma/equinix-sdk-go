# WorkvisitCreateDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OpenCabinet** | Pointer to **bool** | Equinix Technicial to help to open the cage and an additional charge incured by the customer | [optional] [default to false]
**VisitStartDateTime** | **time.Time** |  | 
**VisitEndDateTime** | **time.Time** |  | 
**Visitors** | [**[]WorkvisitAdditionalDetailsVisitorsInner**](WorkvisitAdditionalDetailsVisitorsInner.md) | The maximum limit for non registered visitors is 50 | 
**Cages** | [**[]CagesDetails**](CagesDetails.md) |  | 

## Methods

### NewWorkvisitCreateDetails

`func NewWorkvisitCreateDetails(visitStartDateTime time.Time, visitEndDateTime time.Time, visitors []WorkvisitAdditionalDetailsVisitorsInner, cages []CagesDetails, ) *WorkvisitCreateDetails`

NewWorkvisitCreateDetails instantiates a new WorkvisitCreateDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitCreateDetailsWithDefaults

`func NewWorkvisitCreateDetailsWithDefaults() *WorkvisitCreateDetails`

NewWorkvisitCreateDetailsWithDefaults instantiates a new WorkvisitCreateDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOpenCabinet

`func (o *WorkvisitCreateDetails) GetOpenCabinet() bool`

GetOpenCabinet returns the OpenCabinet field if non-nil, zero value otherwise.

### GetOpenCabinetOk

`func (o *WorkvisitCreateDetails) GetOpenCabinetOk() (*bool, bool)`

GetOpenCabinetOk returns a tuple with the OpenCabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCabinet

`func (o *WorkvisitCreateDetails) SetOpenCabinet(v bool)`

SetOpenCabinet sets OpenCabinet field to given value.

### HasOpenCabinet

`func (o *WorkvisitCreateDetails) HasOpenCabinet() bool`

HasOpenCabinet returns a boolean if a field has been set.

### GetVisitStartDateTime

`func (o *WorkvisitCreateDetails) GetVisitStartDateTime() time.Time`

GetVisitStartDateTime returns the VisitStartDateTime field if non-nil, zero value otherwise.

### GetVisitStartDateTimeOk

`func (o *WorkvisitCreateDetails) GetVisitStartDateTimeOk() (*time.Time, bool)`

GetVisitStartDateTimeOk returns a tuple with the VisitStartDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitStartDateTime

`func (o *WorkvisitCreateDetails) SetVisitStartDateTime(v time.Time)`

SetVisitStartDateTime sets VisitStartDateTime field to given value.


### GetVisitEndDateTime

`func (o *WorkvisitCreateDetails) GetVisitEndDateTime() time.Time`

GetVisitEndDateTime returns the VisitEndDateTime field if non-nil, zero value otherwise.

### GetVisitEndDateTimeOk

`func (o *WorkvisitCreateDetails) GetVisitEndDateTimeOk() (*time.Time, bool)`

GetVisitEndDateTimeOk returns a tuple with the VisitEndDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitEndDateTime

`func (o *WorkvisitCreateDetails) SetVisitEndDateTime(v time.Time)`

SetVisitEndDateTime sets VisitEndDateTime field to given value.


### GetVisitors

`func (o *WorkvisitCreateDetails) GetVisitors() []WorkvisitAdditionalDetailsVisitorsInner`

GetVisitors returns the Visitors field if non-nil, zero value otherwise.

### GetVisitorsOk

`func (o *WorkvisitCreateDetails) GetVisitorsOk() (*[]WorkvisitAdditionalDetailsVisitorsInner, bool)`

GetVisitorsOk returns a tuple with the Visitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitors

`func (o *WorkvisitCreateDetails) SetVisitors(v []WorkvisitAdditionalDetailsVisitorsInner)`

SetVisitors sets Visitors field to given value.


### GetCages

`func (o *WorkvisitCreateDetails) GetCages() []CagesDetails`

GetCages returns the Cages field if non-nil, zero value otherwise.

### GetCagesOk

`func (o *WorkvisitCreateDetails) GetCagesOk() (*[]CagesDetails, bool)`

GetCagesOk returns a tuple with the Cages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCages

`func (o *WorkvisitCreateDetails) SetCages(v []CagesDetails)`

SetCages sets Cages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


