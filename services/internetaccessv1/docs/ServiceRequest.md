# ServiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tags** | Pointer to **[]string** |  | [optional] 
**Type** | [**ServiceType**](ServiceType.md) |  | 
**UseCase** | [**UseCaseType**](UseCaseType.md) |  | 
**Name** | **string** | Name of the service instance  | 
**Description** | Pointer to **string** | Description of the service instance  | [optional] 
**Bandwidth** | **int32** | Service bandwidth in Mbps  | 
**MinBandwidthCommit** | Pointer to **int32** | Service min bandwidth commit in Mbps  | [optional] 
**Billing** | Pointer to [**BillingType**](BillingType.md) |  | [optional] [default to BILLINGTYPE_FIXED]
**Connections** | [**[]Connection**](Connection.md) | Collection of service connections  | 
**Draft** | Pointer to **bool** |  | [optional] [default to false]
**RoutingProtocols** | [**[]RoutingProtocolRequest**](RoutingProtocolRequest.md) | Collection of routing protocols  | 
**Order** | Pointer to [**ServiceOrderRequest**](ServiceOrderRequest.md) |  | [optional] 
**Account** | [**CustomerBillingAccount**](CustomerBillingAccount.md) |  | 
**Project** | Pointer to [**Project**](Project.md) |  | [optional] 

## Methods

### NewServiceRequest

`func NewServiceRequest(type_ ServiceType, useCase UseCaseType, name string, bandwidth int32, connections []Connection, routingProtocols []RoutingProtocolRequest, account CustomerBillingAccount, ) *ServiceRequest`

NewServiceRequest instantiates a new ServiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceRequestWithDefaults

`func NewServiceRequestWithDefaults() *ServiceRequest`

NewServiceRequestWithDefaults instantiates a new ServiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTags

`func (o *ServiceRequest) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ServiceRequest) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ServiceRequest) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ServiceRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetType

`func (o *ServiceRequest) GetType() ServiceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServiceRequest) GetTypeOk() (*ServiceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServiceRequest) SetType(v ServiceType)`

SetType sets Type field to given value.


### GetUseCase

`func (o *ServiceRequest) GetUseCase() UseCaseType`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *ServiceRequest) GetUseCaseOk() (*UseCaseType, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *ServiceRequest) SetUseCase(v UseCaseType)`

SetUseCase sets UseCase field to given value.


### GetName

`func (o *ServiceRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServiceRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServiceRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ServiceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBandwidth

`func (o *ServiceRequest) GetBandwidth() int32`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *ServiceRequest) GetBandwidthOk() (*int32, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *ServiceRequest) SetBandwidth(v int32)`

SetBandwidth sets Bandwidth field to given value.


### GetMinBandwidthCommit

`func (o *ServiceRequest) GetMinBandwidthCommit() int32`

GetMinBandwidthCommit returns the MinBandwidthCommit field if non-nil, zero value otherwise.

### GetMinBandwidthCommitOk

`func (o *ServiceRequest) GetMinBandwidthCommitOk() (*int32, bool)`

GetMinBandwidthCommitOk returns a tuple with the MinBandwidthCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinBandwidthCommit

`func (o *ServiceRequest) SetMinBandwidthCommit(v int32)`

SetMinBandwidthCommit sets MinBandwidthCommit field to given value.

### HasMinBandwidthCommit

`func (o *ServiceRequest) HasMinBandwidthCommit() bool`

HasMinBandwidthCommit returns a boolean if a field has been set.

### GetBilling

`func (o *ServiceRequest) GetBilling() BillingType`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *ServiceRequest) GetBillingOk() (*BillingType, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *ServiceRequest) SetBilling(v BillingType)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *ServiceRequest) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetConnections

`func (o *ServiceRequest) GetConnections() []Connection`

GetConnections returns the Connections field if non-nil, zero value otherwise.

### GetConnectionsOk

`func (o *ServiceRequest) GetConnectionsOk() (*[]Connection, bool)`

GetConnectionsOk returns a tuple with the Connections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnections

`func (o *ServiceRequest) SetConnections(v []Connection)`

SetConnections sets Connections field to given value.


### GetDraft

`func (o *ServiceRequest) GetDraft() bool`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *ServiceRequest) GetDraftOk() (*bool, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *ServiceRequest) SetDraft(v bool)`

SetDraft sets Draft field to given value.

### HasDraft

`func (o *ServiceRequest) HasDraft() bool`

HasDraft returns a boolean if a field has been set.

### GetRoutingProtocols

`func (o *ServiceRequest) GetRoutingProtocols() []RoutingProtocolRequest`

GetRoutingProtocols returns the RoutingProtocols field if non-nil, zero value otherwise.

### GetRoutingProtocolsOk

`func (o *ServiceRequest) GetRoutingProtocolsOk() (*[]RoutingProtocolRequest, bool)`

GetRoutingProtocolsOk returns a tuple with the RoutingProtocols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocols

`func (o *ServiceRequest) SetRoutingProtocols(v []RoutingProtocolRequest)`

SetRoutingProtocols sets RoutingProtocols field to given value.


### GetOrder

`func (o *ServiceRequest) GetOrder() ServiceOrderRequest`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ServiceRequest) GetOrderOk() (*ServiceOrderRequest, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ServiceRequest) SetOrder(v ServiceOrderRequest)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ServiceRequest) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetAccount

`func (o *ServiceRequest) GetAccount() CustomerBillingAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *ServiceRequest) GetAccountOk() (*CustomerBillingAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *ServiceRequest) SetAccount(v CustomerBillingAccount)`

SetAccount sets Account field to given value.


### GetProject

`func (o *ServiceRequest) GetProject() Project`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ServiceRequest) GetProjectOk() (*Project, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ServiceRequest) SetProject(v Project)`

SetProject sets Project field to given value.

### HasProject

`func (o *ServiceRequest) HasProject() bool`

HasProject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


