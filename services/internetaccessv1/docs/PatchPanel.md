# PatchPanel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Number** | **string** |  | 
**CustomerRefNumber** | Pointer to **string** |  | [optional] 
**Type** | [**PatchPanelType**](PatchPanelType.md) |  | 
**Prewired** | **bool** |  | 
**AvailablePortsCount** | Pointer to **int32** |  | [optional] 
**AvailablePorts** | **[]int32** |  | 
**OwnedPortsCount** | Pointer to **int32** |  | [optional] 
**OwnedPorts** | [**[]PatchPanelOwnedPorts**](PatchPanelOwnedPorts.md) |  | 
**MediaTypes** | **[]string** |  | 
**DedicatedMediaType** | **string** |  | 
**Cage** | [**CageRef**](CageRef.md) |  | 
**Cabinet** | [**CabinetRef**](CabinetRef.md) |  | 
**Location** | [**Location**](Location.md) |  | 
**Account** | [**SecureCageAccount**](SecureCageAccount.md) |  | 

## Methods

### NewPatchPanel

`func NewPatchPanel(number string, type_ PatchPanelType, prewired bool, availablePorts []int32, ownedPorts []PatchPanelOwnedPorts, mediaTypes []string, dedicatedMediaType string, cage CageRef, cabinet CabinetRef, location Location, account SecureCageAccount, ) *PatchPanel`

NewPatchPanel instantiates a new PatchPanel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchPanelWithDefaults

`func NewPatchPanelWithDefaults() *PatchPanel`

NewPatchPanelWithDefaults instantiates a new PatchPanel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumber

`func (o *PatchPanel) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PatchPanel) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PatchPanel) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetCustomerRefNumber

`func (o *PatchPanel) GetCustomerRefNumber() string`

GetCustomerRefNumber returns the CustomerRefNumber field if non-nil, zero value otherwise.

### GetCustomerRefNumberOk

`func (o *PatchPanel) GetCustomerRefNumberOk() (*string, bool)`

GetCustomerRefNumberOk returns a tuple with the CustomerRefNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerRefNumber

`func (o *PatchPanel) SetCustomerRefNumber(v string)`

SetCustomerRefNumber sets CustomerRefNumber field to given value.

### HasCustomerRefNumber

`func (o *PatchPanel) HasCustomerRefNumber() bool`

HasCustomerRefNumber returns a boolean if a field has been set.

### GetType

`func (o *PatchPanel) GetType() PatchPanelType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PatchPanel) GetTypeOk() (*PatchPanelType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PatchPanel) SetType(v PatchPanelType)`

SetType sets Type field to given value.


### GetPrewired

`func (o *PatchPanel) GetPrewired() bool`

GetPrewired returns the Prewired field if non-nil, zero value otherwise.

### GetPrewiredOk

`func (o *PatchPanel) GetPrewiredOk() (*bool, bool)`

GetPrewiredOk returns a tuple with the Prewired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrewired

`func (o *PatchPanel) SetPrewired(v bool)`

SetPrewired sets Prewired field to given value.


### GetAvailablePortsCount

`func (o *PatchPanel) GetAvailablePortsCount() int32`

GetAvailablePortsCount returns the AvailablePortsCount field if non-nil, zero value otherwise.

### GetAvailablePortsCountOk

`func (o *PatchPanel) GetAvailablePortsCountOk() (*int32, bool)`

GetAvailablePortsCountOk returns a tuple with the AvailablePortsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailablePortsCount

`func (o *PatchPanel) SetAvailablePortsCount(v int32)`

SetAvailablePortsCount sets AvailablePortsCount field to given value.

### HasAvailablePortsCount

`func (o *PatchPanel) HasAvailablePortsCount() bool`

HasAvailablePortsCount returns a boolean if a field has been set.

### GetAvailablePorts

`func (o *PatchPanel) GetAvailablePorts() []int32`

GetAvailablePorts returns the AvailablePorts field if non-nil, zero value otherwise.

### GetAvailablePortsOk

`func (o *PatchPanel) GetAvailablePortsOk() (*[]int32, bool)`

GetAvailablePortsOk returns a tuple with the AvailablePorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailablePorts

`func (o *PatchPanel) SetAvailablePorts(v []int32)`

SetAvailablePorts sets AvailablePorts field to given value.


### GetOwnedPortsCount

`func (o *PatchPanel) GetOwnedPortsCount() int32`

GetOwnedPortsCount returns the OwnedPortsCount field if non-nil, zero value otherwise.

### GetOwnedPortsCountOk

`func (o *PatchPanel) GetOwnedPortsCountOk() (*int32, bool)`

GetOwnedPortsCountOk returns a tuple with the OwnedPortsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedPortsCount

`func (o *PatchPanel) SetOwnedPortsCount(v int32)`

SetOwnedPortsCount sets OwnedPortsCount field to given value.

### HasOwnedPortsCount

`func (o *PatchPanel) HasOwnedPortsCount() bool`

HasOwnedPortsCount returns a boolean if a field has been set.

### GetOwnedPorts

`func (o *PatchPanel) GetOwnedPorts() []PatchPanelOwnedPorts`

GetOwnedPorts returns the OwnedPorts field if non-nil, zero value otherwise.

### GetOwnedPortsOk

`func (o *PatchPanel) GetOwnedPortsOk() (*[]PatchPanelOwnedPorts, bool)`

GetOwnedPortsOk returns a tuple with the OwnedPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedPorts

`func (o *PatchPanel) SetOwnedPorts(v []PatchPanelOwnedPorts)`

SetOwnedPorts sets OwnedPorts field to given value.


### GetMediaTypes

`func (o *PatchPanel) GetMediaTypes() []string`

GetMediaTypes returns the MediaTypes field if non-nil, zero value otherwise.

### GetMediaTypesOk

`func (o *PatchPanel) GetMediaTypesOk() (*[]string, bool)`

GetMediaTypesOk returns a tuple with the MediaTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaTypes

`func (o *PatchPanel) SetMediaTypes(v []string)`

SetMediaTypes sets MediaTypes field to given value.


### GetDedicatedMediaType

`func (o *PatchPanel) GetDedicatedMediaType() string`

GetDedicatedMediaType returns the DedicatedMediaType field if non-nil, zero value otherwise.

### GetDedicatedMediaTypeOk

`func (o *PatchPanel) GetDedicatedMediaTypeOk() (*string, bool)`

GetDedicatedMediaTypeOk returns a tuple with the DedicatedMediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDedicatedMediaType

`func (o *PatchPanel) SetDedicatedMediaType(v string)`

SetDedicatedMediaType sets DedicatedMediaType field to given value.


### GetCage

`func (o *PatchPanel) GetCage() CageRef`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *PatchPanel) GetCageOk() (*CageRef, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *PatchPanel) SetCage(v CageRef)`

SetCage sets Cage field to given value.


### GetCabinet

`func (o *PatchPanel) GetCabinet() CabinetRef`

GetCabinet returns the Cabinet field if non-nil, zero value otherwise.

### GetCabinetOk

`func (o *PatchPanel) GetCabinetOk() (*CabinetRef, bool)`

GetCabinetOk returns a tuple with the Cabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinet

`func (o *PatchPanel) SetCabinet(v CabinetRef)`

SetCabinet sets Cabinet field to given value.


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


### GetAccount

`func (o *PatchPanel) GetAccount() SecureCageAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *PatchPanel) GetAccountOk() (*SecureCageAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *PatchPanel) SetAccount(v SecureCageAccount)`

SetAccount sets Account field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


