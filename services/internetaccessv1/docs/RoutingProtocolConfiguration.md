# RoutingProtocolConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UseCase** | [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | 
**Type** | [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) |  | 
**RoutingProtocol** | [**RoutingProtocolConfigurationRoutingProtocol**](RoutingProtocolConfigurationRoutingProtocol.md) |  | 

## Methods

### NewRoutingProtocolConfiguration

`func NewRoutingProtocolConfiguration(useCase GetRoutingConfigurationsUseCaseParameter, type_ ProductCatalogRedundancy, routingProtocol RoutingProtocolConfigurationRoutingProtocol, ) *RoutingProtocolConfiguration`

NewRoutingProtocolConfiguration instantiates a new RoutingProtocolConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRoutingProtocolConfigurationWithDefaults

`func NewRoutingProtocolConfigurationWithDefaults() *RoutingProtocolConfiguration`

NewRoutingProtocolConfigurationWithDefaults instantiates a new RoutingProtocolConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUseCase

`func (o *RoutingProtocolConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *RoutingProtocolConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *RoutingProtocolConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.


### GetType

`func (o *RoutingProtocolConfiguration) GetType() ProductCatalogRedundancy`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RoutingProtocolConfiguration) GetTypeOk() (*ProductCatalogRedundancy, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RoutingProtocolConfiguration) SetType(v ProductCatalogRedundancy)`

SetType sets Type field to given value.


### GetRoutingProtocol

`func (o *RoutingProtocolConfiguration) GetRoutingProtocol() RoutingProtocolConfigurationRoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *RoutingProtocolConfiguration) GetRoutingProtocolOk() (*RoutingProtocolConfigurationRoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *RoutingProtocolConfiguration) SetRoutingProtocol(v RoutingProtocolConfigurationRoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


