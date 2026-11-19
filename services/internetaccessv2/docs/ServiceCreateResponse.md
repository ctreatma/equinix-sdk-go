# ServiceCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Type** | [**ServiceType**](ServiceType.md) |  | 
**Connections** | [**[]Connection**](Connection.md) | Collection of service connections uuids | 
**RoutingProtocol** | [**RoutingProtocolReadModel**](RoutingProtocolReadModel.md) |  | 
**Bandwidth** | Pointer to **int32** | Service bandwidth in Mbps | [optional] 
**Project** | Pointer to [**ProjectReadModel**](ProjectReadModel.md) |  | [optional] 
**Account** | Pointer to [**Account**](Account.md) |  | [optional] 
**Change** | [**Change**](Change.md) |  | 
**ChangeLog** | Pointer to [**ChangeLog**](ChangeLog.md) |  | [optional] 
**Order** | Pointer to [**ServiceOrderReadModel**](ServiceOrderReadModel.md) |  | [optional] 
**Uuid** | **string** | Service identifier | 
**State** | [**ServiceState**](ServiceState.md) |  | 
**UseCase** | [**UseCase**](UseCase.md) |  | 

## Methods

### NewServiceCreateResponse

`func NewServiceCreateResponse(type_ ServiceType, connections []Connection, routingProtocol RoutingProtocolReadModel, change Change, uuid string, state ServiceState, useCase UseCase, ) *ServiceCreateResponse`

NewServiceCreateResponse instantiates a new ServiceCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceCreateResponseWithDefaults

`func NewServiceCreateResponseWithDefaults() *ServiceCreateResponse`

NewServiceCreateResponseWithDefaults instantiates a new ServiceCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ServiceCreateResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServiceCreateResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServiceCreateResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ServiceCreateResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ServiceCreateResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceCreateResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceCreateResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceCreateResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetType

`func (o *ServiceCreateResponse) GetType() ServiceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServiceCreateResponse) GetTypeOk() (*ServiceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServiceCreateResponse) SetType(v ServiceType)`

SetType sets Type field to given value.


### GetConnections

`func (o *ServiceCreateResponse) GetConnections() []Connection`

GetConnections returns the Connections field if non-nil, zero value otherwise.

### GetConnectionsOk

`func (o *ServiceCreateResponse) GetConnectionsOk() (*[]Connection, bool)`

GetConnectionsOk returns a tuple with the Connections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnections

`func (o *ServiceCreateResponse) SetConnections(v []Connection)`

SetConnections sets Connections field to given value.


### GetRoutingProtocol

`func (o *ServiceCreateResponse) GetRoutingProtocol() RoutingProtocolReadModel`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *ServiceCreateResponse) GetRoutingProtocolOk() (*RoutingProtocolReadModel, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *ServiceCreateResponse) SetRoutingProtocol(v RoutingProtocolReadModel)`

SetRoutingProtocol sets RoutingProtocol field to given value.


### GetBandwidth

`func (o *ServiceCreateResponse) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *ServiceCreateResponse) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *ServiceCreateResponse) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.

### HasBandwidth

`func (o *ServiceCreateResponse) HasBandwidth() bool`

HasBandwidth returns a boolean if a field has been set.

### GetProject

`func (o *ServiceCreateResponse) GetProject() ProjectReadModel`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ServiceCreateResponse) GetProjectOk() (*ProjectReadModel, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ServiceCreateResponse) SetProject(v ProjectReadModel)`

SetProject sets Project field to given value.

### HasProject

`func (o *ServiceCreateResponse) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetAccount

`func (o *ServiceCreateResponse) GetAccount() Account`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *ServiceCreateResponse) GetAccountOk() (*Account, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *ServiceCreateResponse) SetAccount(v Account)`

SetAccount sets Account field to given value.

### HasAccount

`func (o *ServiceCreateResponse) HasAccount() bool`

HasAccount returns a boolean if a field has been set.

### GetChange

`func (o *ServiceCreateResponse) GetChange() Change`

GetChange returns the Change field if non-nil, zero value otherwise.

### GetChangeOk

`func (o *ServiceCreateResponse) GetChangeOk() (*Change, bool)`

GetChangeOk returns a tuple with the Change field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChange

`func (o *ServiceCreateResponse) SetChange(v Change)`

SetChange sets Change field to given value.


### GetChangeLog

`func (o *ServiceCreateResponse) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *ServiceCreateResponse) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *ServiceCreateResponse) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.

### HasChangeLog

`func (o *ServiceCreateResponse) HasChangeLog() bool`

HasChangeLog returns a boolean if a field has been set.

### GetOrder

`func (o *ServiceCreateResponse) GetOrder() ServiceOrderReadModel`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ServiceCreateResponse) GetOrderOk() (*ServiceOrderReadModel, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ServiceCreateResponse) SetOrder(v ServiceOrderReadModel)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ServiceCreateResponse) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetUuid

`func (o *ServiceCreateResponse) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ServiceCreateResponse) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ServiceCreateResponse) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetState

`func (o *ServiceCreateResponse) GetState() ServiceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ServiceCreateResponse) GetStateOk() (*ServiceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ServiceCreateResponse) SetState(v ServiceState)`

SetState sets State field to given value.


### GetUseCase

`func (o *ServiceCreateResponse) GetUseCase() UseCase`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *ServiceCreateResponse) GetUseCaseOk() (*UseCase, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *ServiceCreateResponse) SetUseCase(v UseCase)`

SetUseCase sets UseCase field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


