# PhysicalPort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PhysicalPortType**](PhysicalPortType.md) |  | 
**Speed** | **int32** | Entity bandwidth in Mbps  | 
**DemarcationPoint** | [**DemarcationPoint**](DemarcationPoint.md) |  | 

## Methods

### NewPhysicalPort

`func NewPhysicalPort(type_ PhysicalPortType, speed int32, demarcationPoint DemarcationPoint, ) *PhysicalPort`

NewPhysicalPort instantiates a new PhysicalPort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPhysicalPortWithDefaults

`func NewPhysicalPortWithDefaults() *PhysicalPort`

NewPhysicalPortWithDefaults instantiates a new PhysicalPort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PhysicalPort) GetType() PhysicalPortType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PhysicalPort) GetTypeOk() (*PhysicalPortType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PhysicalPort) SetType(v PhysicalPortType)`

SetType sets Type field to given value.


### GetSpeed

`func (o *PhysicalPort) GetSpeed() int32`

GetSpeed returns the Speed field if non-nil, zero value otherwise.

### GetSpeedOk

`func (o *PhysicalPort) GetSpeedOk() (*int32, bool)`

GetSpeedOk returns a tuple with the Speed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeed

`func (o *PhysicalPort) SetSpeed(v int32)`

SetSpeed sets Speed field to given value.


### GetDemarcationPoint

`func (o *PhysicalPort) GetDemarcationPoint() DemarcationPoint`

GetDemarcationPoint returns the DemarcationPoint field if non-nil, zero value otherwise.

### GetDemarcationPointOk

`func (o *PhysicalPort) GetDemarcationPointOk() (*DemarcationPoint, bool)`

GetDemarcationPointOk returns a tuple with the DemarcationPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDemarcationPoint

`func (o *PhysicalPort) SetDemarcationPoint(v DemarcationPoint)`

SetDemarcationPoint sets DemarcationPoint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


