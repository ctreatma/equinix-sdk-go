# ConnectionReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | Pointer to **string** | Connection URI | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 
**Type** | [**ConnectionType**](ConnectionType.md) |  | 
**Name** | **string** | Name of the connection | 
**Description** | Pointer to **string** | Description of the connection | [optional] 
**ChangeLog** | [**ChangeLog**](ChangeLog.md) |  | 
**Bandwidth** | **int64** | Bandwidth of the Connection in Mbps | 
**Redundancy** | Pointer to [**Redundancy**](Redundancy.md) |  | [optional] 
**ASide** | [**ASide**](ASide.md) |  | 
**Tags** | Pointer to **[]string** |  | [optional] 
**Links** | [**[]Link**](Link.md) |  | 

## Methods

### NewConnectionReadModel

`func NewConnectionReadModel(type_ ConnectionType, name string, changeLog ChangeLog, bandwidth int64, aSide ASide, links []Link, ) *ConnectionReadModel`

NewConnectionReadModel instantiates a new ConnectionReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionReadModelWithDefaults

`func NewConnectionReadModelWithDefaults() *ConnectionReadModel`

NewConnectionReadModelWithDefaults instantiates a new ConnectionReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *ConnectionReadModel) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *ConnectionReadModel) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *ConnectionReadModel) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *ConnectionReadModel) HasHref() bool`

HasHref returns a boolean if a field has been set.

### GetUuid

`func (o *ConnectionReadModel) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ConnectionReadModel) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ConnectionReadModel) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *ConnectionReadModel) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *ConnectionReadModel) GetType() ConnectionType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ConnectionReadModel) GetTypeOk() (*ConnectionType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ConnectionReadModel) SetType(v ConnectionType)`

SetType sets Type field to given value.


### GetName

`func (o *ConnectionReadModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectionReadModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectionReadModel) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ConnectionReadModel) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ConnectionReadModel) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ConnectionReadModel) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ConnectionReadModel) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetChangeLog

`func (o *ConnectionReadModel) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *ConnectionReadModel) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *ConnectionReadModel) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.


### GetBandwidth

`func (o *ConnectionReadModel) GetBandwidth() int64`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *ConnectionReadModel) GetBandwidthOk() (*int64, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *ConnectionReadModel) SetBandwidth(v int64)`

SetBandwidth sets Bandwidth field to given value.


### GetRedundancy

`func (o *ConnectionReadModel) GetRedundancy() Redundancy`

GetRedundancy returns the Redundancy field if non-nil, zero value otherwise.

### GetRedundancyOk

`func (o *ConnectionReadModel) GetRedundancyOk() (*Redundancy, bool)`

GetRedundancyOk returns a tuple with the Redundancy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedundancy

`func (o *ConnectionReadModel) SetRedundancy(v Redundancy)`

SetRedundancy sets Redundancy field to given value.

### HasRedundancy

`func (o *ConnectionReadModel) HasRedundancy() bool`

HasRedundancy returns a boolean if a field has been set.

### GetASide

`func (o *ConnectionReadModel) GetASide() ASide`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *ConnectionReadModel) GetASideOk() (*ASide, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *ConnectionReadModel) SetASide(v ASide)`

SetASide sets ASide field to given value.


### GetTags

`func (o *ConnectionReadModel) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ConnectionReadModel) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ConnectionReadModel) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ConnectionReadModel) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetLinks

`func (o *ConnectionReadModel) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ConnectionReadModel) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ConnectionReadModel) SetLinks(v []Link)`

SetLinks sets Links field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


