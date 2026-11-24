# CreateCrossConnect

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionService** | **string** | Connection service type. For applicable values, use the Equinix Customer Portal - Lookup - Get Patch Panel Details API request. | 
**MediaType** | **string** | Media type. For applicable values, use the Equinix Customer Portal - Lookup - Get Patch Panel Details API request. | 
**ProtocolType** | **string** | Connection protocol. For applicable values, use the Equinix Customer Portal - Lookup - Get Patch Panel Details API request. | 
**ASide** | Pointer to [**CreatePatchPanelPort**](CreatePatchPanelPort.md) |  | [optional] 
**ZSide** | [**CreatePatchPanelPort**](CreatePatchPanelPort.md) |  | 

## Methods

### NewCreateCrossConnect

`func NewCreateCrossConnect(connectionService string, mediaType string, protocolType string, zSide CreatePatchPanelPort, ) *CreateCrossConnect`

NewCreateCrossConnect instantiates a new CreateCrossConnect object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCrossConnectWithDefaults

`func NewCreateCrossConnectWithDefaults() *CreateCrossConnect`

NewCreateCrossConnectWithDefaults instantiates a new CreateCrossConnect object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionService

`func (o *CreateCrossConnect) GetConnectionService() string`

GetConnectionService returns the ConnectionService field if non-nil, zero value otherwise.

### GetConnectionServiceOk

`func (o *CreateCrossConnect) GetConnectionServiceOk() (*string, bool)`

GetConnectionServiceOk returns a tuple with the ConnectionService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionService

`func (o *CreateCrossConnect) SetConnectionService(v string)`

SetConnectionService sets ConnectionService field to given value.


### GetMediaType

`func (o *CreateCrossConnect) GetMediaType() string`

GetMediaType returns the MediaType field if non-nil, zero value otherwise.

### GetMediaTypeOk

`func (o *CreateCrossConnect) GetMediaTypeOk() (*string, bool)`

GetMediaTypeOk returns a tuple with the MediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaType

`func (o *CreateCrossConnect) SetMediaType(v string)`

SetMediaType sets MediaType field to given value.


### GetProtocolType

`func (o *CreateCrossConnect) GetProtocolType() string`

GetProtocolType returns the ProtocolType field if non-nil, zero value otherwise.

### GetProtocolTypeOk

`func (o *CreateCrossConnect) GetProtocolTypeOk() (*string, bool)`

GetProtocolTypeOk returns a tuple with the ProtocolType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocolType

`func (o *CreateCrossConnect) SetProtocolType(v string)`

SetProtocolType sets ProtocolType field to given value.


### GetASide

`func (o *CreateCrossConnect) GetASide() CreatePatchPanelPort`

GetASide returns the ASide field if non-nil, zero value otherwise.

### GetASideOk

`func (o *CreateCrossConnect) GetASideOk() (*CreatePatchPanelPort, bool)`

GetASideOk returns a tuple with the ASide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetASide

`func (o *CreateCrossConnect) SetASide(v CreatePatchPanelPort)`

SetASide sets ASide field to given value.

### HasASide

`func (o *CreateCrossConnect) HasASide() bool`

HasASide returns a boolean if a field has been set.

### GetZSide

`func (o *CreateCrossConnect) GetZSide() CreatePatchPanelPort`

GetZSide returns the ZSide field if non-nil, zero value otherwise.

### GetZSideOk

`func (o *CreateCrossConnect) GetZSideOk() (*CreatePatchPanelPort, bool)`

GetZSideOk returns a tuple with the ZSide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZSide

`func (o *CreateCrossConnect) SetZSide(v CreatePatchPanelPort)`

SetZSide sets ZSide field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


