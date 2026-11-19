# ServiceDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdditionalDetails** | Pointer to **string** | Any additional information related to work visit | [optional] 
**Schedule** | [**ServiceDetailSchedule**](ServiceDetailSchedule.md) |  | 
**Visitors** | [**[]Visitor**](Visitor.md) |  | 
**OpenCabinet** | Pointer to **bool** |  | [optional] [default to false]
**SupervisionRequired** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewServiceDetail

`func NewServiceDetail(schedule ServiceDetailSchedule, visitors []Visitor, ) *ServiceDetail`

NewServiceDetail instantiates a new ServiceDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceDetailWithDefaults

`func NewServiceDetailWithDefaults() *ServiceDetail`

NewServiceDetailWithDefaults instantiates a new ServiceDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdditionalDetails

`func (o *ServiceDetail) GetAdditionalDetails() string`

GetAdditionalDetails returns the AdditionalDetails field if non-nil, zero value otherwise.

### GetAdditionalDetailsOk

`func (o *ServiceDetail) GetAdditionalDetailsOk() (*string, bool)`

GetAdditionalDetailsOk returns a tuple with the AdditionalDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalDetails

`func (o *ServiceDetail) SetAdditionalDetails(v string)`

SetAdditionalDetails sets AdditionalDetails field to given value.

### HasAdditionalDetails

`func (o *ServiceDetail) HasAdditionalDetails() bool`

HasAdditionalDetails returns a boolean if a field has been set.

### GetSchedule

`func (o *ServiceDetail) GetSchedule() ServiceDetailSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *ServiceDetail) GetScheduleOk() (*ServiceDetailSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *ServiceDetail) SetSchedule(v ServiceDetailSchedule)`

SetSchedule sets Schedule field to given value.


### GetVisitors

`func (o *ServiceDetail) GetVisitors() []Visitor`

GetVisitors returns the Visitors field if non-nil, zero value otherwise.

### GetVisitorsOk

`func (o *ServiceDetail) GetVisitorsOk() (*[]Visitor, bool)`

GetVisitorsOk returns a tuple with the Visitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitors

`func (o *ServiceDetail) SetVisitors(v []Visitor)`

SetVisitors sets Visitors field to given value.


### GetOpenCabinet

`func (o *ServiceDetail) GetOpenCabinet() bool`

GetOpenCabinet returns the OpenCabinet field if non-nil, zero value otherwise.

### GetOpenCabinetOk

`func (o *ServiceDetail) GetOpenCabinetOk() (*bool, bool)`

GetOpenCabinetOk returns a tuple with the OpenCabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCabinet

`func (o *ServiceDetail) SetOpenCabinet(v bool)`

SetOpenCabinet sets OpenCabinet field to given value.

### HasOpenCabinet

`func (o *ServiceDetail) HasOpenCabinet() bool`

HasOpenCabinet returns a boolean if a field has been set.

### GetSupervisionRequired

`func (o *ServiceDetail) GetSupervisionRequired() bool`

GetSupervisionRequired returns the SupervisionRequired field if non-nil, zero value otherwise.

### GetSupervisionRequiredOk

`func (o *ServiceDetail) GetSupervisionRequiredOk() (*bool, bool)`

GetSupervisionRequiredOk returns a tuple with the SupervisionRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupervisionRequired

`func (o *ServiceDetail) SetSupervisionRequired(v bool)`

SetSupervisionRequired sets SupervisionRequired field to given value.

### HasSupervisionRequired

`func (o *ServiceDetail) HasSupervisionRequired() bool`

HasSupervisionRequired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


