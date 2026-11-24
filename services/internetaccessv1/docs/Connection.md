# Connection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | Pointer to **[]string** |  | [optional] 
**Type** | [**ConnectionType**](ConnectionType.md) |  | 
**Name** | Pointer to **string** | Connection name  | [optional] 
**Description** | Pointer to **string** | Connection name  | [optional] 
**ASide** | [**ConnectionASide**](ConnectionASide.md) |  | 

## Methods

### NewConnection

`func NewConnection(type_ ConnectionType, aSide ConnectionASide, ) *Connection`

NewConnection instantiates a new Connection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectionWithDefaults

`func NewConnectionWithDefaults() *Connection`

NewConnectionWithDefaults instantiates a new Connection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *Connection) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Connection) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Connection) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *Connection) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetType

`func (o *Connection) GetType() ConnectionType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Connection) GetTypeOk() (*ConnectionType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Connection) SetType(v ConnectionType)`

SetType sets Type field to given value.


### GetName

`func (o *Connection) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Connection) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Connection) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Connection) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *Connection) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Connection) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Connection) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Connection) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetASide

`func (o *Connection) GetASide() ConnectionASide`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *Connection) GetASideOk() (*ConnectionASide, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *Connection) SetASide(v ConnectionASide)`

SetASide sets ASide field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


