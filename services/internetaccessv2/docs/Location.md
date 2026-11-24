# Location

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MetroCode** | **string** |  | 
**IbxCode** | **string** | IBX data center code | 
**Region** | [**Region**](Region.md) |  | 

## Methods

### NewLocation

`func NewLocation(metroCode string, ibxCode string, region Region, ) *Location`

NewLocation instantiates a new Location object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationWithDefaults

`func NewLocationWithDefaults() *Location`

NewLocationWithDefaults instantiates a new Location object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetroCode

`func (o *Location) GetMetroCode() string`

GetMetroCode returns the MetroCode field if non-nil, zero value otherwise.

### GetMetroCodeOk

`func (o *Location) GetMetroCodeOk() (*string, bool)`

GetMetroCodeOk returns a tuple with the MetroCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroCode

`func (o *Location) SetMetroCode(v string)`

SetMetroCode sets MetroCode field to given value.


### GetIbxCode

`func (o *Location) GetIbxCode() string`

GetIbxCode returns the IbxCode field if non-nil, zero value otherwise.

### GetIbxCodeOk

`func (o *Location) GetIbxCodeOk() (*string, bool)`

GetIbxCodeOk returns a tuple with the IbxCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxCode

`func (o *Location) SetIbxCode(v string)`

SetIbxCode sets IbxCode field to given value.


### GetRegion

`func (o *Location) GetRegion() Region`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *Location) GetRegionOk() (*Region, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *Location) SetRegion(v Region)`

SetRegion sets Region field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


