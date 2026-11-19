# ServiceDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | **string** | Internet access URI | 
**Uuid** | **string** | Equinix-assigned internet access identifier | 
**Type** | [**ServiceType**](ServiceType.md) |  | 
**Name** | **string** | Name of the service This name should only contain spaces, the characters \&quot;_\&quot;, \&quot;-\&quot;, letters or numbers. The name cannot start or end with a \&quot;-\&quot;. This name can have only maximum of 24 characters  | 
**Description** | Pointer to **string** | Description of the service | [optional] 
**Bandwidth** | **int64** | Bandwidth of the service in Mbps | 
**Billing** | [**ServiceBilling**](ServiceBilling.md) |  | 
**State** | [**ServiceState**](ServiceState.md) |  | 
**Draft** | **bool** | Describes if the service is a draft | 
**UseCase** | [**ServiceUseCase**](ServiceUseCase.md) |  | 
**Change** | [**Change**](Change.md) |  | 
**ChangeLog** | [**ChangeLog**](ChangeLog.md) |  | 
**Connections** | [**[]ConnectionReadModel**](ConnectionReadModel.md) |  | 
**RoutingProtocols** | [**[]RoutingProtocolReadModel**](RoutingProtocolReadModel.md) |  | 
**Account** | [**Account**](Account.md) |  | 
**Project** | Pointer to [**ProjectReadModel**](ProjectReadModel.md) |  | [optional] 
**Order** | [**OrderReadModel**](OrderReadModel.md) |  | 
**Tags** | Pointer to **[]string** |  | [optional] 
**Links** | [**[]Link**](Link.md) |  | 

## Methods

### NewServiceDetailsResponse

`func NewServiceDetailsResponse(href string, uuid string, type_ ServiceType, name string, bandwidth int64, billing ServiceBilling, state ServiceState, draft bool, useCase ServiceUseCase, change Change, changeLog ChangeLog, connections []ConnectionReadModel, routingProtocols []RoutingProtocolReadModel, account Account, order OrderReadModel, links []Link, ) *ServiceDetailsResponse`

NewServiceDetailsResponse instantiates a new ServiceDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceDetailsResponseWithDefaults

`func NewServiceDetailsResponseWithDefaults() *ServiceDetailsResponse`

NewServiceDetailsResponseWithDefaults instantiates a new ServiceDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *ServiceDetailsResponse) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *ServiceDetailsResponse) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *ServiceDetailsResponse) SetHref(v string)`

SetHref sets Href field to given value.


### GetUuid

`func (o *ServiceDetailsResponse) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ServiceDetailsResponse) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ServiceDetailsResponse) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *ServiceDetailsResponse) GetType() ServiceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServiceDetailsResponse) GetTypeOk() (*ServiceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServiceDetailsResponse) SetType(v ServiceType)`

SetType sets Type field to given value.


### GetName

`func (o *ServiceDetailsResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServiceDetailsResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServiceDetailsResponse) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ServiceDetailsResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ServiceDetailsResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ServiceDetailsResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ServiceDetailsResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetBandwidth

`func (o *ServiceDetailsResponse) GetBandwidth() int64`

GetBandwidth returns the Bandwidth field if non-nil, zero value otherwise.

### GetBandwidthOk

`func (o *ServiceDetailsResponse) GetBandwidthOk() (*int64, bool)`

GetBandwidthOk returns a tuple with the Bandwidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBandwidth

`func (o *ServiceDetailsResponse) SetBandwidth(v int64)`

SetBandwidth sets Bandwidth field to given value.


### GetBilling

`func (o *ServiceDetailsResponse) GetBilling() ServiceBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *ServiceDetailsResponse) GetBillingOk() (*ServiceBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *ServiceDetailsResponse) SetBilling(v ServiceBilling)`

SetBilling sets Billing field to given value.


### GetState

`func (o *ServiceDetailsResponse) GetState() ServiceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ServiceDetailsResponse) GetStateOk() (*ServiceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ServiceDetailsResponse) SetState(v ServiceState)`

SetState sets State field to given value.


### GetDraft

`func (o *ServiceDetailsResponse) GetDraft() bool`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *ServiceDetailsResponse) GetDraftOk() (*bool, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *ServiceDetailsResponse) SetDraft(v bool)`

SetDraft sets Draft field to given value.


### GetUseCase

`func (o *ServiceDetailsResponse) GetUseCase() ServiceUseCase`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *ServiceDetailsResponse) GetUseCaseOk() (*ServiceUseCase, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *ServiceDetailsResponse) SetUseCase(v ServiceUseCase)`

SetUseCase sets UseCase field to given value.


### GetChange

`func (o *ServiceDetailsResponse) GetChange() Change`

GetChange returns the Change field if non-nil, zero value otherwise.

### GetChangeOk

`func (o *ServiceDetailsResponse) GetChangeOk() (*Change, bool)`

GetChangeOk returns a tuple with the Change field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChange

`func (o *ServiceDetailsResponse) SetChange(v Change)`

SetChange sets Change field to given value.


### GetChangeLog

`func (o *ServiceDetailsResponse) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *ServiceDetailsResponse) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *ServiceDetailsResponse) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.


### GetConnections

`func (o *ServiceDetailsResponse) GetConnections() []ConnectionReadModel`

GetConnections returns the Connections field if non-nil, zero value otherwise.

### GetConnectionsOk

`func (o *ServiceDetailsResponse) GetConnectionsOk() (*[]ConnectionReadModel, bool)`

GetConnectionsOk returns a tuple with the Connections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnections

`func (o *ServiceDetailsResponse) SetConnections(v []ConnectionReadModel)`

SetConnections sets Connections field to given value.


### GetRoutingProtocols

`func (o *ServiceDetailsResponse) GetRoutingProtocols() []RoutingProtocolReadModel`

GetRoutingProtocols returns the RoutingProtocols field if non-nil, zero value otherwise.

### GetRoutingProtocolsOk

`func (o *ServiceDetailsResponse) GetRoutingProtocolsOk() (*[]RoutingProtocolReadModel, bool)`

GetRoutingProtocolsOk returns a tuple with the RoutingProtocols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoutingProtocols

`func (o *ServiceDetailsResponse) SetRoutingProtocols(v []RoutingProtocolReadModel)`

SetRoutingProtocols sets RoutingProtocols field to given value.


### GetAccount

`func (o *ServiceDetailsResponse) GetAccount() Account`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *ServiceDetailsResponse) GetAccountOk() (*Account, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *ServiceDetailsResponse) SetAccount(v Account)`

SetAccount sets Account field to given value.


### GetProject

`func (o *ServiceDetailsResponse) GetProject() ProjectReadModel`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ServiceDetailsResponse) GetProjectOk() (*ProjectReadModel, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ServiceDetailsResponse) SetProject(v ProjectReadModel)`

SetProject sets Project field to given value.

### HasProject

`func (o *ServiceDetailsResponse) HasProject() bool`

HasProject returns a boolean if a field has been set.

### GetOrder

`func (o *ServiceDetailsResponse) GetOrder() OrderReadModel`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ServiceDetailsResponse) GetOrderOk() (*OrderReadModel, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ServiceDetailsResponse) SetOrder(v OrderReadModel)`

SetOrder sets Order field to given value.


### GetTags

`func (o *ServiceDetailsResponse) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ServiceDetailsResponse) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ServiceDetailsResponse) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ServiceDetailsResponse) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetLinks

`func (o *ServiceDetailsResponse) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ServiceDetailsResponse) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ServiceDetailsResponse) SetLinks(v []Link)`

SetLinks sets Links field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


