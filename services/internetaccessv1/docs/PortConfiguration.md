# PortConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | 
**Type** | [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) |  | 
**RoutingProtocol** | [**PortConfigurationRoutingProtocol**](PortConfigurationRoutingProtocol.md) |  | 
**Connection** | [**PortConfigurationConnection**](PortConfigurationConnection.md) |  | 

## Methods

### NewPortConfiguration

`func NewPortConfiguration(useCase GetRoutingConfigurationsUseCaseParameter, type_ ProductCatalogRedundancy, routingProtocol PortConfigurationRoutingProtocol, connection PortConfigurationConnection, ) *PortConfiguration`

NewPortConfiguration instantiates a new PortConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortConfigurationWithDefaults

`func NewPortConfigurationWithDefaults() *PortConfiguration`

NewPortConfigurationWithDefaults instantiates a new PortConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseCase

`func (o *PortConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *PortConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *PortConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.


### GetType

`func (o *PortConfiguration) GetType() ProductCatalogRedundancy`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PortConfiguration) GetTypeOk() (*ProductCatalogRedundancy, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PortConfiguration) SetType(v ProductCatalogRedundancy)`

SetType sets Type field to given value.


### GetRoutingProtocol

`func (o *PortConfiguration) GetRoutingProtocol() PortConfigurationRoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *PortConfiguration) GetRoutingProtocolOk() (*PortConfigurationRoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *PortConfiguration) SetRoutingProtocol(v PortConfigurationRoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.


### GetConnection

`func (o *PortConfiguration) GetConnection() PortConfigurationConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *PortConfiguration) GetConnectionOk() (*PortConfigurationConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *PortConfiguration) SetConnection(v PortConfigurationConnection)`

SetConnection sets Connection field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


