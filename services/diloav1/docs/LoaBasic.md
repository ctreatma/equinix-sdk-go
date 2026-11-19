# LoaBasic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | Pointer to **string** | User-friendly Digital LOA document identifier. | [optional] 
**Uuid** | Pointer to **string** | Digital LOA document identifier. | [optional] 
**State** | Pointer to [**State**](State.md) |  | [optional] 
**Draft** | Pointer to **bool** | Default: false | [optional] 
**ChangeLog** | Pointer to [**ChangeLog**](ChangeLog.md) |  | [optional] 
**Links** | Pointer to [**[]Link**](Link.md) | HATEOAS links specifying possible follow-up interactions. | [optional] 
**Change** | Pointer to [**Change**](Change.md) |  | [optional] 
**ExpiryDateTime** | Pointer to **time.Time** | Digital LOA document expiration date. | [optional] 
**Href** | Pointer to **string** | Digital LOA document URI. | [optional] 

## Methods

### NewLoaBasic

`func NewLoaBasic() *LoaBasic`

NewLoaBasic instantiates a new LoaBasic object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoaBasicWithDefaults

`func NewLoaBasicWithDefaults() *LoaBasic`

NewLoaBasicWithDefaults instantiates a new LoaBasic object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *LoaBasic) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *LoaBasic) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *LoaBasic) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *LoaBasic) HasToken() bool`

HasToken returns a boolean if a field has been set.

### GetUuid

`func (o *LoaBasic) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *LoaBasic) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *LoaBasic) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *LoaBasic) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetState

`func (o *LoaBasic) GetState() State`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *LoaBasic) GetStateOk() (*State, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *LoaBasic) SetState(v State)`

SetState sets State field to given value.

### HasState

`func (o *LoaBasic) HasState() bool`

HasState returns a boolean if a field has been set.

### GetDraft

`func (o *LoaBasic) GetDraft() bool`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *LoaBasic) GetDraftOk() (*bool, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *LoaBasic) SetDraft(v bool)`

SetDraft sets Draft field to given value.

### HasDraft

`func (o *LoaBasic) HasDraft() bool`

HasDraft returns a boolean if a field has been set.

### GetChangeLog

`func (o *LoaBasic) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *LoaBasic) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *LoaBasic) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.

### HasChangeLog

`func (o *LoaBasic) HasChangeLog() bool`

HasChangeLog returns a boolean if a field has been set.

### GetLinks

`func (o *LoaBasic) GetLinks() []Link`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *LoaBasic) GetLinksOk() (*[]Link, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *LoaBasic) SetLinks(v []Link)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *LoaBasic) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetChange

`func (o *LoaBasic) GetChange() Change`

GetChange returns the Change field if non-nil, zero value otherwise.

### GetChangeOk

`func (o *LoaBasic) GetChangeOk() (*Change, bool)`

GetChangeOk returns a tuple with the Change field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChange

`func (o *LoaBasic) SetChange(v Change)`

SetChange sets Change field to given value.

### HasChange

`func (o *LoaBasic) HasChange() bool`

HasChange returns a boolean if a field has been set.

### GetExpiryDateTime

`func (o *LoaBasic) GetExpiryDateTime() time.Time`

GetExpiryDateTime returns the ExpiryDateTime field if non-nil, zero value otherwise.

### GetExpiryDateTimeOk

`func (o *LoaBasic) GetExpiryDateTimeOk() (*time.Time, bool)`

GetExpiryDateTimeOk returns a tuple with the ExpiryDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDateTime

`func (o *LoaBasic) SetExpiryDateTime(v time.Time)`

SetExpiryDateTime sets ExpiryDateTime field to given value.

### HasExpiryDateTime

`func (o *LoaBasic) HasExpiryDateTime() bool`

HasExpiryDateTime returns a boolean if a field has been set.

### GetHref

`func (o *LoaBasic) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *LoaBasic) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *LoaBasic) SetHref(v string)`

SetHref sets Href field to given value.

### HasHref

`func (o *LoaBasic) HasHref() bool`

HasHref returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


