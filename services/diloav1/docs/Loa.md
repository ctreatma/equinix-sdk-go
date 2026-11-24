# Loa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | Pointer to **string** | User-friendly Digital LOA document identifier. | [optional] 
**Uuid** | Pointer to **string** | Digital LOA document identifier. | [optional] 
**State** | Pointer to [**State**](State.md) |  | [optional] 
**Products** | Pointer to [**[]Product**](Product.md) | Specification of services that the given LOA document is valid for. | [optional] 
**Requestor** | Pointer to [**Party**](Party.md) |  | [optional] 
**Provider** | Pointer to [**Party**](Party.md) |  | [optional] 
**ChangeLog** | Pointer to [**ChangeLog**](ChangeLog.md) |  | [optional] 
**Links** | Pointer to [**[]Link**](Link.md) | HATEOAS links specifying possible follow-up interactions. | [optional] 
**Notes** | Pointer to **string** | Additional information to be considered. | [optional] 
**ExpiryDateTime** | Pointer to **time.Time** | Digital LOA document expiration date. | [optional] 
**Href** | Pointer to **string** | Digital LOA document URI. | [optional] 

## Methods

### NewLoa

`func NewLoa() *Loa`

NewLoa instantiates a new Loa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoaWithDefaults

`func NewLoaWithDefaults() *Loa`

NewLoaWithDefaults instantiates a new Loa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *Loa) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *Loa) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *Loa) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *Loa) HasToken() bool`

HasToken returns a boolean if a field has been set.

### GetUuid

`func (o *Loa) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Loa) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Loa) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *Loa) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetState

`func (o *Loa) GetState() State`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Loa) GetStateOk() (*State, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Loa) SetState(v State)`

SetState sets State field to given value.

### HasState

`func (o *Loa) HasState() bool`

HasState returns a boolean if a field has been set.

### GetProducts

`func (o *Loa) GetProducts() []Product`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *Loa) GetProductsOk() (*[]Product, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *Loa) SetProducts(v []Product)`

SetProducts sets Products field to given value.

### HasProducts

`func (o *Loa) HasProducts() bool`

HasProducts returns a boolean if a field has been set.

### GetRequestor

`func (o *Loa) GetRequestor() Party`

GetRequestor returns the Requestor field if non-nil, zero value otherwise.

### GetRequestorOk

`func (o *Loa) GetRequestorOk() (*Party, bool)`

GetRequestorOk returns a tuple with the Requestor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestor

`func (o *Loa) SetRequestor(v Party)`

SetRequestor sets Requestor field to given value.

### HasRequestor

`func (o *Loa) HasRequestor() bool`

HasRequestor returns a boolean if a field has been set.

### GetProvider

`func (o *Loa) GetProvider() Party`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *Loa) GetProviderOk() (*Party, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *Loa) SetProvider(v Party)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *Loa) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetChangeLog

`func (o *Loa) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *Loa) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *Loa) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.

### HasChangeLog

`func (o *Loa) HasChangeLog() bool`

HasChangeLog returns a boolean if a field has been set.

### GetLinks

`func (o *Loa) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *Loa) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *Loa) SetLinks(v []Link)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *Loa) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetNotes

`func (o *Loa) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Loa) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Loa) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Loa) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetExpiryDateTime

`func (o *Loa) GetExpiryDateTime() time.Time`

GetExpiryDateTime returns the ExpiryDateTime field if non-nil, zero value otherwise.

### GetExpiryDateTimeOk

`func (o *Loa) GetExpiryDateTimeOk() (*time.Time, bool)`

GetExpiryDateTimeOk returns a tuple with the ExpiryDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDateTime

`func (o *Loa) SetExpiryDateTime(v time.Time)`

SetExpiryDateTime sets ExpiryDateTime field to given value.

### HasExpiryDateTime

`func (o *Loa) HasExpiryDateTime() bool`

HasExpiryDateTime returns a boolean if a field has been set.

### GetHref

`func (o *Loa) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *Loa) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *Loa) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *Loa) HasHref() bool`

HasHref returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


