# CreateLoaRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ibx** | **string** | IBX data center identifier. | 
**RequestedNumber** | **int32** | Number of requested connections. | 
**Requestor** | [**PartyContacts**](PartyContacts.md) |  | 
**Provider** | [**Party**](Party.md) |  | 
**Notes** | Pointer to **string** | Additional information to be considered. | [optional] 

## Methods

### NewCreateLoaRequest

`func NewCreateLoaRequest(ibx string, requestedNumber int32, requestor PartyContacts, provider Party, ) *CreateLoaRequest`

NewCreateLoaRequest instantiates a new CreateLoaRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLoaRequestWithDefaults

`func NewCreateLoaRequestWithDefaults() *CreateLoaRequest`

NewCreateLoaRequestWithDefaults instantiates a new CreateLoaRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbx

`func (o *CreateLoaRequest) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *CreateLoaRequest) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *CreateLoaRequest) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetRequestedNumber

`func (o *CreateLoaRequest) GetRequestedNumber() int32`

GetRequestedNumber returns the RequestedNumber field if non-nil, zero value otherwise.

### GetRequestedNumberOk

`func (o *CreateLoaRequest) GetRequestedNumberOk() (*int32, bool)`

GetRequestedNumberOk returns a tuple with the RequestedNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedNumber

`func (o *CreateLoaRequest) SetRequestedNumber(v int32)`

SetRequestedNumber sets RequestedNumber field to given value.


### GetRequestor

`func (o *CreateLoaRequest) GetRequestor() PartyContacts`

GetRequestor returns the Requestor field if non-nil, zero value otherwise.

### GetRequestorOk

`func (o *CreateLoaRequest) GetRequestorOk() (*PartyContacts, bool)`

GetRequestorOk returns a tuple with the Requestor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestor

`func (o *CreateLoaRequest) SetRequestor(v PartyContacts)`

SetRequestor sets Requestor field to given value.


### GetProvider

`func (o *CreateLoaRequest) GetProvider() Party`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateLoaRequest) GetProviderOk() (*Party, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateLoaRequest) SetProvider(v Party)`

SetProvider sets Provider field to given value.


### GetNotes

`func (o *CreateLoaRequest) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateLoaRequest) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateLoaRequest) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateLoaRequest) HasNotes() bool`

HasNotes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


