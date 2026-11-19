# PatchPanel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Patch panel identifier. | 
**CabinetSpaceId** | **string** | Cabinet space identifier. | 
**CageSpaceId** | **string** | Cage space identifier. | 
**Location** | [**Location**](Location.md) |  | 

## Methods

### NewPatchPanel

`func NewPatchPanel(id string, cabinetSpaceId string, cageSpaceId string, location Location, ) *PatchPanel`

NewPatchPanel instantiates a new PatchPanel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchPanelWithDefaults

`func NewPatchPanelWithDefaults() *PatchPanel`

NewPatchPanelWithDefaults instantiates a new PatchPanel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PatchPanel) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PatchPanel) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PatchPanel) SetId(v string)`

SetId sets Id field to given value.


### GetCabinetSpaceId

`func (o *PatchPanel) GetCabinetSpaceId() string`

GetCabinetSpaceId returns the CabinetSpaceId field if non-nil, zero value otherwise.

### GetCabinetSpaceIdOk

`func (o *PatchPanel) GetCabinetSpaceIdOk() (*string, bool)`

GetCabinetSpaceIdOk returns a tuple with the CabinetSpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinetSpaceId

`func (o *PatchPanel) SetCabinetSpaceId(v string)`

SetCabinetSpaceId sets CabinetSpaceId field to given value.


### GetCageSpaceId

`func (o *PatchPanel) GetCageSpaceId() string`

GetCageSpaceId returns the CageSpaceId field if non-nil, zero value otherwise.

### GetCageSpaceIdOk

`func (o *PatchPanel) GetCageSpaceIdOk() (*string, bool)`

GetCageSpaceIdOk returns a tuple with the CageSpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCageSpaceId

`func (o *PatchPanel) SetCageSpaceId(v string)`

SetCageSpaceId sets CageSpaceId field to given value.


### GetLocation

`func (o *PatchPanel) GetLocation() Location`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *PatchPanel) GetLocationOk() (*Location, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *PatchPanel) SetLocation(v Location)`

SetLocation sets Location field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


