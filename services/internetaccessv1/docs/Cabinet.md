# Cabinet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SpaceId** | **string** |  | 
**Number** | **string** |  | 
**PatchPanelsCount** | **int32** |  | 
**Cage** | [**CageRef**](CageRef.md) |  | 
**Location** | [**Location**](Location.md) |  | 
**Account** | [**SecureCageAccount**](SecureCageAccount.md) |  | 

## Methods

### NewCabinet

`func NewCabinet(spaceId string, number string, patchPanelsCount int32, cage CageRef, location Location, account SecureCageAccount, ) *Cabinet`

NewCabinet instantiates a new Cabinet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCabinetWithDefaults

`func NewCabinetWithDefaults() *Cabinet`

NewCabinetWithDefaults instantiates a new Cabinet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSpaceId

`func (o *Cabinet) GetSpaceId() string`

GetSpaceId returns the SpaceId field if non-nil, zero value otherwise.

### GetSpaceIdOk

`func (o *Cabinet) GetSpaceIdOk() (*string, bool)`

GetSpaceIdOk returns a tuple with the SpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpaceId

`func (o *Cabinet) SetSpaceId(v string)`

SetSpaceId sets SpaceId field to given value.


### GetNumber

`func (o *Cabinet) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *Cabinet) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *Cabinet) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetPatchPanelsCount

`func (o *Cabinet) GetPatchPanelsCount() int32`

GetPatchPanelsCount returns the PatchPanelsCount field if non-nil, zero value otherwise.

### GetPatchPanelsCountOk

`func (o *Cabinet) GetPatchPanelsCountOk() (*int32, bool)`

GetPatchPanelsCountOk returns a tuple with the PatchPanelsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanelsCount

`func (o *Cabinet) SetPatchPanelsCount(v int32)`

SetPatchPanelsCount sets PatchPanelsCount field to given value.


### GetCage

`func (o *Cabinet) GetCage() CageRef`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *Cabinet) GetCageOk() (*CageRef, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *Cabinet) SetCage(v CageRef)`

SetCage sets Cage field to given value.


### GetLocation

`func (o *Cabinet) GetLocation() Location`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *Cabinet) GetLocationOk() (*Location, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *Cabinet) SetLocation(v Location)`

SetLocation sets Location field to given value.


### GetAccount

`func (o *Cabinet) GetAccount() SecureCageAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *Cabinet) GetAccountOk() (*SecureCageAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *Cabinet) SetAccount(v SecureCageAccount)`

SetAccount sets Account field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


