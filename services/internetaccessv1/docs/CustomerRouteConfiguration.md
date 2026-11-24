# CustomerRouteConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to [**ProductCatalogRedundancy**](ProductCatalogRedundancy.md) |  | [optional] 
**UseCase** | Pointer to [**GetRoutingConfigurationsUseCaseParameter**](GetRoutingConfigurationsUseCaseParameter.md) |  | [optional] 
**RoutingProtocol** | Pointer to [**CustomerRouteConfigurationRoutingProtocol**](CustomerRouteConfigurationRoutingProtocol.md) |  | [optional] 

## Methods

### NewCustomerRouteConfiguration

`func NewCustomerRouteConfiguration() *CustomerRouteConfiguration`

NewCustomerRouteConfiguration instantiates a new CustomerRouteConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerRouteConfigurationWithDefaults

`func NewCustomerRouteConfigurationWithDefaults() *CustomerRouteConfiguration`

NewCustomerRouteConfigurationWithDefaults instantiates a new CustomerRouteConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CustomerRouteConfiguration) GetType() ProductCatalogRedundancy`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CustomerRouteConfiguration) GetTypeOk() (*ProductCatalogRedundancy, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CustomerRouteConfiguration) SetType(v ProductCatalogRedundancy)`

SetType sets Type field to given value.

### HasType

`func (o *CustomerRouteConfiguration) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUseCase

`func (o *CustomerRouteConfiguration) GetUseCase() GetRoutingConfigurationsUseCaseParameter`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *CustomerRouteConfiguration) GetUseCaseOk() (*GetRoutingConfigurationsUseCaseParameter, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *CustomerRouteConfiguration) SetUseCase(v GetRoutingConfigurationsUseCaseParameter)`

SetUseCase sets UseCase field to given value.

### HasUseCase

`func (o *CustomerRouteConfiguration) HasUseCase() bool`

HasUseCase returns a boolean if a field has been set.

### GetRoutingProtocol

`func (o *CustomerRouteConfiguration) GetRoutingProtocol() CustomerRouteConfigurationRoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *CustomerRouteConfiguration) GetRoutingProtocolOk() (*CustomerRouteConfigurationRoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *CustomerRouteConfiguration) SetRoutingProtocol(v CustomerRouteConfigurationRoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.

### HasRoutingProtocol

`func (o *CustomerRouteConfiguration) HasRoutingProtocol() bool`

HasRoutingProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


