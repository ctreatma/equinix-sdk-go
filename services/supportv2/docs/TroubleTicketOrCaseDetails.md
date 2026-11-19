# TroubleTicketOrCaseDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestedTerminationDate** | **string** | Preferred termination date. | 
**Cage** | **string** | Cage number. | 
**Cabinet** | Pointer to **string** | Cabinet number. | [optional] 
**Details** | [**Model03050000Details**](03050000Details.md) |  | 
**OrderIds** | **[]string** | List of order numbers. | 
**TransactionIds** | **[]string** | List of transaction numbers such as invoice, credit memo or payment numbers. | 
**CompanyName** | Pointer to **string** | New company name. | [optional] 
**CompanyLocalName** | Pointer to **string** | New company name in local language. | [optional] 
**VatNumber** | Pointer to **string** | New VAT or tax registration number. | [optional] 
**Address** | [**Model03050301Address**](03050301Address.md) |  | 
**Contacts** | [**[]Model03050302ContactsInner**](Model03050302ContactsInner.md) | Contact information. | 
**Schedule1** | **string** | Preferred availability (Option 1). | 
**Schedule2** | **string** | Preferred availability (Option 2). | 
**Schedule3** | **string** | Preferred availability (Option 3). | 
**Timezone** | **string** | Preferred availability time zone. | 
**AssetId** | **string** | Asset number. | 
**OrderId** | **string** | Order number. | 
**Product** | [**Model03060000Product**](03060000Product.md) |  | 
**TestingOnSite** | [**Model03060000TestingOnSite**](03060000TestingOnSite.md) |  | 
**IsUrgentRequest** | [**Model03060000IsUrgentRequest**](03060000IsUrgentRequest.md) |  | 
**BusinessJustification** | Pointer to [**Model03060000BusinessJustification**](03060000BusinessJustification.md) |  | [optional] 
**OtherBusinessJustification** | Pointer to **string** | Other reason than the provided three for urgent request. | [optional] 
**Severity** | Pointer to [**DigitalProductDetailsSeverity**](DigitalProductDetailsSeverity.md) |  | [optional] 

## Methods

### NewTroubleTicketOrCaseDetails

`func NewTroubleTicketOrCaseDetails(requestedTerminationDate string, cage string, details Model03050000Details, orderIds []string, transactionIds []string, address Model03050301Address, contacts []Model03050302ContactsInner, schedule1 string, schedule2 string, schedule3 string, timezone string, assetId string, orderId string, product Model03060000Product, testingOnSite Model03060000TestingOnSite, isUrgentRequest Model03060000IsUrgentRequest, ) *TroubleTicketOrCaseDetails`

NewTroubleTicketOrCaseDetails instantiates a new TroubleTicketOrCaseDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketOrCaseDetailsWithDefaults

`func NewTroubleTicketOrCaseDetailsWithDefaults() *TroubleTicketOrCaseDetails`

NewTroubleTicketOrCaseDetailsWithDefaults instantiates a new TroubleTicketOrCaseDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestedTerminationDate

`func (o *TroubleTicketOrCaseDetails) GetRequestedTerminationDate() string`

GetRequestedTerminationDate returns the RequestedTerminationDate field if non-nil, zero value otherwise.

### GetRequestedTerminationDateOk

`func (o *TroubleTicketOrCaseDetails) GetRequestedTerminationDateOk() (*string, bool)`

GetRequestedTerminationDateOk returns a tuple with the RequestedTerminationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerminationDate

`func (o *TroubleTicketOrCaseDetails) SetRequestedTerminationDate(v string)`

SetRequestedTerminationDate sets RequestedTerminationDate field to given value.


### GetCage

`func (o *TroubleTicketOrCaseDetails) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *TroubleTicketOrCaseDetails) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *TroubleTicketOrCaseDetails) SetCage(v string)`

SetCage sets Cage field to given value.


### GetCabinet

`func (o *TroubleTicketOrCaseDetails) GetCabinet() string`

GetCabinet returns the Cabinet field if non-nil, zero value otherwise.

### GetCabinetOk

`func (o *TroubleTicketOrCaseDetails) GetCabinetOk() (*string, bool)`

GetCabinetOk returns a tuple with the Cabinet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinet

`func (o *TroubleTicketOrCaseDetails) SetCabinet(v string)`

SetCabinet sets Cabinet field to given value.

### HasCabinet

`func (o *TroubleTicketOrCaseDetails) HasCabinet() bool`

HasCabinet returns a boolean if a field has been set.

### GetDetails

`func (o *TroubleTicketOrCaseDetails) GetDetails() Model03050000Details`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *TroubleTicketOrCaseDetails) GetDetailsOk() (*Model03050000Details, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *TroubleTicketOrCaseDetails) SetDetails(v Model03050000Details)`

SetDetails sets Details field to given value.


### GetOrderIds

`func (o *TroubleTicketOrCaseDetails) GetOrderIds() []string`

GetOrderIds returns the OrderIds field if non-nil, zero value otherwise.

### GetOrderIdsOk

`func (o *TroubleTicketOrCaseDetails) GetOrderIdsOk() (*[]string, bool)`

GetOrderIdsOk returns a tuple with the OrderIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderIds

`func (o *TroubleTicketOrCaseDetails) SetOrderIds(v []string)`

SetOrderIds sets OrderIds field to given value.


### GetTransactionIds

`func (o *TroubleTicketOrCaseDetails) GetTransactionIds() []string`

GetTransactionIds returns the TransactionIds field if non-nil, zero value otherwise.

### GetTransactionIdsOk

`func (o *TroubleTicketOrCaseDetails) GetTransactionIdsOk() (*[]string, bool)`

GetTransactionIdsOk returns a tuple with the TransactionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionIds

`func (o *TroubleTicketOrCaseDetails) SetTransactionIds(v []string)`

SetTransactionIds sets TransactionIds field to given value.


### GetCompanyName

`func (o *TroubleTicketOrCaseDetails) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *TroubleTicketOrCaseDetails) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *TroubleTicketOrCaseDetails) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *TroubleTicketOrCaseDetails) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### GetCompanyLocalName

`func (o *TroubleTicketOrCaseDetails) GetCompanyLocalName() string`

GetCompanyLocalName returns the CompanyLocalName field if non-nil, zero value otherwise.

### GetCompanyLocalNameOk

`func (o *TroubleTicketOrCaseDetails) GetCompanyLocalNameOk() (*string, bool)`

GetCompanyLocalNameOk returns a tuple with the CompanyLocalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyLocalName

`func (o *TroubleTicketOrCaseDetails) SetCompanyLocalName(v string)`

SetCompanyLocalName sets CompanyLocalName field to given value.

### HasCompanyLocalName

`func (o *TroubleTicketOrCaseDetails) HasCompanyLocalName() bool`

HasCompanyLocalName returns a boolean if a field has been set.

### GetVatNumber

`func (o *TroubleTicketOrCaseDetails) GetVatNumber() string`

GetVatNumber returns the VatNumber field if non-nil, zero value otherwise.

### GetVatNumberOk

`func (o *TroubleTicketOrCaseDetails) GetVatNumberOk() (*string, bool)`

GetVatNumberOk returns a tuple with the VatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatNumber

`func (o *TroubleTicketOrCaseDetails) SetVatNumber(v string)`

SetVatNumber sets VatNumber field to given value.

### HasVatNumber

`func (o *TroubleTicketOrCaseDetails) HasVatNumber() bool`

HasVatNumber returns a boolean if a field has been set.

### GetAddress

`func (o *TroubleTicketOrCaseDetails) GetAddress() Model03050301Address`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *TroubleTicketOrCaseDetails) GetAddressOk() (*Model03050301Address, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *TroubleTicketOrCaseDetails) SetAddress(v Model03050301Address)`

SetAddress sets Address field to given value.


### GetContacts

`func (o *TroubleTicketOrCaseDetails) GetContacts() []Model03050302ContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *TroubleTicketOrCaseDetails) GetContactsOk() (*[]Model03050302ContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *TroubleTicketOrCaseDetails) SetContacts(v []Model03050302ContactsInner)`

SetContacts sets Contacts field to given value.


### GetSchedule1

`func (o *TroubleTicketOrCaseDetails) GetSchedule1() string`

GetSchedule1 returns the Schedule1 field if non-nil, zero value otherwise.

### GetSchedule1Ok

`func (o *TroubleTicketOrCaseDetails) GetSchedule1Ok() (*string, bool)`

GetSchedule1Ok returns a tuple with the Schedule1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule1

`func (o *TroubleTicketOrCaseDetails) SetSchedule1(v string)`

SetSchedule1 sets Schedule1 field to given value.


### GetSchedule2

`func (o *TroubleTicketOrCaseDetails) GetSchedule2() string`

GetSchedule2 returns the Schedule2 field if non-nil, zero value otherwise.

### GetSchedule2Ok

`func (o *TroubleTicketOrCaseDetails) GetSchedule2Ok() (*string, bool)`

GetSchedule2Ok returns a tuple with the Schedule2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule2

`func (o *TroubleTicketOrCaseDetails) SetSchedule2(v string)`

SetSchedule2 sets Schedule2 field to given value.


### GetSchedule3

`func (o *TroubleTicketOrCaseDetails) GetSchedule3() string`

GetSchedule3 returns the Schedule3 field if non-nil, zero value otherwise.

### GetSchedule3Ok

`func (o *TroubleTicketOrCaseDetails) GetSchedule3Ok() (*string, bool)`

GetSchedule3Ok returns a tuple with the Schedule3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule3

`func (o *TroubleTicketOrCaseDetails) SetSchedule3(v string)`

SetSchedule3 sets Schedule3 field to given value.


### GetTimezone

`func (o *TroubleTicketOrCaseDetails) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *TroubleTicketOrCaseDetails) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *TroubleTicketOrCaseDetails) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetAssetId

`func (o *TroubleTicketOrCaseDetails) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *TroubleTicketOrCaseDetails) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *TroubleTicketOrCaseDetails) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetOrderId

`func (o *TroubleTicketOrCaseDetails) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *TroubleTicketOrCaseDetails) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *TroubleTicketOrCaseDetails) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetProduct

`func (o *TroubleTicketOrCaseDetails) GetProduct() Model03060000Product`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *TroubleTicketOrCaseDetails) GetProductOk() (*Model03060000Product, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *TroubleTicketOrCaseDetails) SetProduct(v Model03060000Product)`

SetProduct sets Product field to given value.


### GetTestingOnSite

`func (o *TroubleTicketOrCaseDetails) GetTestingOnSite() Model03060000TestingOnSite`

GetTestingOnSite returns the TestingOnSite field if non-nil, zero value otherwise.

### GetTestingOnSiteOk

`func (o *TroubleTicketOrCaseDetails) GetTestingOnSiteOk() (*Model03060000TestingOnSite, bool)`

GetTestingOnSiteOk returns a tuple with the TestingOnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTestingOnSite

`func (o *TroubleTicketOrCaseDetails) SetTestingOnSite(v Model03060000TestingOnSite)`

SetTestingOnSite sets TestingOnSite field to given value.


### GetIsUrgentRequest

`func (o *TroubleTicketOrCaseDetails) GetIsUrgentRequest() Model03060000IsUrgentRequest`

GetIsUrgentRequest returns the IsUrgentRequest field if non-nil, zero value otherwise.

### GetIsUrgentRequestOk

`func (o *TroubleTicketOrCaseDetails) GetIsUrgentRequestOk() (*Model03060000IsUrgentRequest, bool)`

GetIsUrgentRequestOk returns a tuple with the IsUrgentRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsUrgentRequest

`func (o *TroubleTicketOrCaseDetails) SetIsUrgentRequest(v Model03060000IsUrgentRequest)`

SetIsUrgentRequest sets IsUrgentRequest field to given value.


### GetBusinessJustification

`func (o *TroubleTicketOrCaseDetails) GetBusinessJustification() Model03060000BusinessJustification`

GetBusinessJustification returns the BusinessJustification field if non-nil, zero value otherwise.

### GetBusinessJustificationOk

`func (o *TroubleTicketOrCaseDetails) GetBusinessJustificationOk() (*Model03060000BusinessJustification, bool)`

GetBusinessJustificationOk returns a tuple with the BusinessJustification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessJustification

`func (o *TroubleTicketOrCaseDetails) SetBusinessJustification(v Model03060000BusinessJustification)`

SetBusinessJustification sets BusinessJustification field to given value.

### HasBusinessJustification

`func (o *TroubleTicketOrCaseDetails) HasBusinessJustification() bool`

HasBusinessJustification returns a boolean if a field has been set.

### GetOtherBusinessJustification

`func (o *TroubleTicketOrCaseDetails) GetOtherBusinessJustification() string`

GetOtherBusinessJustification returns the OtherBusinessJustification field if non-nil, zero value otherwise.

### GetOtherBusinessJustificationOk

`func (o *TroubleTicketOrCaseDetails) GetOtherBusinessJustificationOk() (*string, bool)`

GetOtherBusinessJustificationOk returns a tuple with the OtherBusinessJustification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherBusinessJustification

`func (o *TroubleTicketOrCaseDetails) SetOtherBusinessJustification(v string)`

SetOtherBusinessJustification sets OtherBusinessJustification field to given value.

### HasOtherBusinessJustification

`func (o *TroubleTicketOrCaseDetails) HasOtherBusinessJustification() bool`

HasOtherBusinessJustification returns a boolean if a field has been set.

### GetSeverity

`func (o *TroubleTicketOrCaseDetails) GetSeverity() DigitalProductDetailsSeverity`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *TroubleTicketOrCaseDetails) GetSeverityOk() (*DigitalProductDetailsSeverity, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *TroubleTicketOrCaseDetails) SetSeverity(v DigitalProductDetailsSeverity)`

SetSeverity sets Severity field to given value.

### HasSeverity

`func (o *TroubleTicketOrCaseDetails) HasSeverity() bool`

HasSeverity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


