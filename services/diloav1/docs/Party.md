# Party

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PartyType**](PartyType.md) |  | 

## Methods

### NewParty

`func NewParty(type_ PartyType, ) *Party`

NewParty instantiates a new Party object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartyWithDefaults

`func NewPartyWithDefaults() *Party`

NewPartyWithDefaults instantiates a new Party object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Party) GetType() PartyType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Party) GetTypeOk() (*PartyType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Party) SetType(v PartyType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


