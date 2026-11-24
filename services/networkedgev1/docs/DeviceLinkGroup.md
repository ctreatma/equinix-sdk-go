# DeviceLinkGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | Unique Id of the linked group. | [optional] 
**GroupName** | Pointer to **string** | The name of the linked group | [optional] 
**Subnet** | Pointer to **string** | Subnet of the link group. | [optional] 
**RedundancyType** | Pointer to [**DeviceLinkGroupRedundancyType**](DeviceLinkGroupRedundancyType.md) |  | [optional] 
**Status** | Pointer to [**DeviceLinkGroupStatus**](DeviceLinkGroupStatus.md) |  | [optional] 
**CreatedBy** | Pointer to **string** | Created by username. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Created date. | [optional] 
**LastUpdatedBy** | Pointer to **string** | Last updated by user | [optional] 
**LastUpdatedDateTime** | Pointer to **time.Time** | Last updated date | [optional] 
**MetroLinks** | Pointer to [**[]LinkInfoResponse**](LinkInfoResponse.md) | An array of links between metros. | [optional] 
**LinkDevices** | Pointer to [**[]LinkDeviceResponse**](LinkDeviceResponse.md) | An array of metros and the devices in the metros belonging to the group. | [optional] 

## Methods

### NewDeviceLinkGroup

`func NewDeviceLinkGroup() *DeviceLinkGroup`

NewDeviceLinkGroup instantiates a new DeviceLinkGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceLinkGroupWithDefaults

`func NewDeviceLinkGroupWithDefaults() *DeviceLinkGroup`

NewDeviceLinkGroupWithDefaults instantiates a new DeviceLinkGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *DeviceLinkGroup) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *DeviceLinkGroup) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *DeviceLinkGroup) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *DeviceLinkGroup) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetGroupName

`func (o *DeviceLinkGroup) GetGroupName() string`

GetGroupName returns the GroupName field if non-nil, zero value otherwise.

### GetGroupNameOk

`func (o *DeviceLinkGroup) GetGroupNameOk() (*string, bool)`

GetGroupNameOk returns a tuple with the GroupName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupName

`func (o *DeviceLinkGroup) SetGroupName(v string)`

SetGroupName sets GroupName field to given value.

### HasGroupName

`func (o *DeviceLinkGroup) HasGroupName() bool`

HasGroupName returns a boolean if a field has been set.

### GetSubnet

`func (o *DeviceLinkGroup) GetSubnet() string`

GetSubnet returns the Subnet field if non-nil, zero value otherwise.

### GetSubnetOk

`func (o *DeviceLinkGroup) GetSubnetOk() (*string, bool)`

GetSubnetOk returns a tuple with the Subnet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubnet

`func (o *DeviceLinkGroup) SetSubnet(v string)`

SetSubnet sets Subnet field to given value.

### HasSubnet

`func (o *DeviceLinkGroup) HasSubnet() bool`

HasSubnet returns a boolean if a field has been set.

### GetRedundancyType

`func (o *DeviceLinkGroup) GetRedundancyType() DeviceLinkGroupRedundancyType`

GetRedundancyType returns the RedundancyType field if non-nil, zero value otherwise.

### GetRedundancyTypeOk

`func (o *DeviceLinkGroup) GetRedundancyTypeOk() (*DeviceLinkGroupRedundancyType, bool)`

GetRedundancyTypeOk returns a tuple with the RedundancyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedundancyType

`func (o *DeviceLinkGroup) SetRedundancyType(v DeviceLinkGroupRedundancyType)`

SetRedundancyType sets RedundancyType field to given value.

### HasRedundancyType

`func (o *DeviceLinkGroup) HasRedundancyType() bool`

HasRedundancyType returns a boolean if a field has been set.

### GetStatus

`func (o *DeviceLinkGroup) GetStatus() DeviceLinkGroupStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeviceLinkGroup) GetStatusOk() (*DeviceLinkGroupStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeviceLinkGroup) SetStatus(v DeviceLinkGroupStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DeviceLinkGroup) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedBy

`func (o *DeviceLinkGroup) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *DeviceLinkGroup) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *DeviceLinkGroup) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *DeviceLinkGroup) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *DeviceLinkGroup) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *DeviceLinkGroup) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *DeviceLinkGroup) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *DeviceLinkGroup) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetLastUpdatedBy

`func (o *DeviceLinkGroup) GetLastUpdatedBy() string`

GetLastUpdatedBy returns the LastUpdatedBy field if non-nil, zero value otherwise.

### GetLastUpdatedByOk

`func (o *DeviceLinkGroup) GetLastUpdatedByOk() (*string, bool)`

GetLastUpdatedByOk returns a tuple with the LastUpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedBy

`func (o *DeviceLinkGroup) SetLastUpdatedBy(v string)`

SetLastUpdatedBy sets LastUpdatedBy field to given value.

### HasLastUpdatedBy

`func (o *DeviceLinkGroup) HasLastUpdatedBy() bool`

HasLastUpdatedBy returns a boolean if a field has been set.

### GetLastUpdatedDateTime

`func (o *DeviceLinkGroup) GetLastUpdatedDateTime() time.Time`

GetLastUpdatedDateTime returns the LastUpdatedDateTime field if non-nil, zero value otherwise.

### GetLastUpdatedDateTimeOk

`func (o *DeviceLinkGroup) GetLastUpdatedDateTimeOk() (*time.Time, bool)`

GetLastUpdatedDateTimeOk returns a tuple with the LastUpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedDateTime

`func (o *DeviceLinkGroup) SetLastUpdatedDateTime(v time.Time)`

SetLastUpdatedDateTime sets LastUpdatedDateTime field to given value.

### HasLastUpdatedDateTime

`func (o *DeviceLinkGroup) HasLastUpdatedDateTime() bool`

HasLastUpdatedDateTime returns a boolean if a field has been set.

### GetMetroLinks

`func (o *DeviceLinkGroup) GetMetroLinks() []LinkInfoResponse`

GetMetroLinks returns the MetroLinks field if non-nil, zero value otherwise.

### GetMetroLinksOk

`func (o *DeviceLinkGroup) GetMetroLinksOk() (*[]LinkInfoResponse, bool)`

GetMetroLinksOk returns a tuple with the MetroLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroLinks

`func (o *DeviceLinkGroup) SetMetroLinks(v []LinkInfoResponse)`

SetMetroLinks sets MetroLinks field to given value.

### HasMetroLinks

`func (o *DeviceLinkGroup) HasMetroLinks() bool`

HasMetroLinks returns a boolean if a field has been set.

### GetLinkDevices

`func (o *DeviceLinkGroup) GetLinkDevices() []LinkDeviceResponse`

GetLinkDevices returns the LinkDevices field if non-nil, zero value otherwise.

### GetLinkDevicesOk

`func (o *DeviceLinkGroup) GetLinkDevicesOk() (*[]LinkDeviceResponse, bool)`

GetLinkDevicesOk returns a tuple with the LinkDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkDevices

`func (o *DeviceLinkGroup) SetLinkDevices(v []LinkDeviceResponse)`

SetLinkDevices sets LinkDevices field to given value.

### HasLinkDevices

`func (o *DeviceLinkGroup) HasLinkDevices() bool`

HasLinkDevices returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


