# ServicePrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** | Unique identifier assigned to the service. Either the uuid or the remaining attributes must be supplied. | [optional] 
**Type** | Pointer to [**ServicePriceType**](ServicePriceType.md) |  | [optional] 
**Bandwidth** | Pointer to **int32** | Connection bandwidth (Mbps). | [optional] 
**MinBandwidthCommit** | Pointer to **int32** | Minimum bandwidth commit (Mbps). Used in case of Burst Based billing. | [optional] 
**Billing** | Pointer to [**ServicePriceBilling**](ServicePriceBilling.md) |  | [optional] [default to SERVICEPRICEBILLING_FIXED]
**UseCase** | Pointer to [**ServicePriceUseCase**](ServicePriceUseCase.md) |  | [optional] 
**Connection** | Pointer to [**ConnectionPrice**](ConnectionPrice.md) |  | [optional] 
**RoutingProtocol** | Pointer to [**RoutingProtocol**](RoutingProtocol.md) |  | [optional] 

## Methods

### NewServicePrice

`func NewServicePrice() *ServicePrice`

NewServicePrice instantiates a new ServicePrice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServicePriceWithDefaults

`func NewServicePriceWithDefaults() *ServicePrice`

NewServicePriceWithDefaults instantiates a new ServicePrice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ServicePrice) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ServicePrice) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ServicePrice) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *ServicePrice) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetType

`func (o *ServicePrice) GetType() ServicePriceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServicePrice) GetTypeOk() (*ServicePriceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServicePrice) SetType(v ServicePriceType)`

SetType sets Type field to given value.

### HasType

`func (o *ServicePrice) HasType() bool`

HasType returns a boolean if a field has been set.

### GetBandwidth

`func (o *ServicePrice) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *ServicePrice) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *ServicePrice) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.

### HasBandwidth

`func (o *ServicePrice) HasBandwidth() bool`

HasBandwidth returns a boolean if a field has been set.

### GetMinBandwidthCommit

`func (o *ServicePrice) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *ServicePrice) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *ServicePrice) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *ServicePrice) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.

### GetBilling

`func (o *ServicePrice) GetBilling() ServicePriceBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *ServicePrice) GetBillingOk() (*ServicePriceBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *ServicePrice) SetBilling(v ServicePriceBilling)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *ServicePrice) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetUseCase

`func (o *ServicePrice) GetUseCase() ServicePriceUseCase`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *ServicePrice) GetUseCaseOk() (*ServicePriceUseCase, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *ServicePrice) SetUseCase(v ServicePriceUseCase)`

SetUseCase sets UseCase field to given value.

### HasUseCase

`func (o *ServicePrice) HasUseCase() bool`

HasUseCase returns a boolean if a field has been set.

### GetConnection

`func (o *ServicePrice) GetConnection() ConnectionPrice`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *ServicePrice) GetConnectionOk() (*ConnectionPrice, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *ServicePrice) SetConnection(v ConnectionPrice)`

SetConnection sets Connection field to given value.

### HasConnection

`func (o *ServicePrice) HasConnection() bool`

HasConnection returns a boolean if a field has been set.

### GetRoutingProtocol

`func (o *ServicePrice) GetRoutingProtocol() RoutingProtocol`

GetRoutingProtocol returns the RoutingProtocol field if non-nil, zero value otherwise.

### GetRoutingProtocolOk

`func (o *ServicePrice) GetRoutingProtocolOk() (*RoutingProtocol, bool)`

GetRoutingProtocolOk returns a tuple with the RoutingProtocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocol

`func (o *ServicePrice) SetRoutingProtocol(v RoutingProtocol)`

SetRoutingProtocol sets RoutingProtocol field to given value.

### HasRoutingProtocol

`func (o *ServicePrice) HasRoutingProtocol() bool`

HasRoutingProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


