# CreateLoa

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Products** | [**[]CreateProduct**](CreateProduct.md) | Specification of services that the given LOA document is valid for. | 
**Requestor** | [**Party**](Party.md) |  | 
**Provider** | [**PartyContacts**](PartyContacts.md) |  | 
**Notes** | Pointer to **string** | Additional information, added to the Digital LOA document, that should be taken under consideration. | [optional] 
**ExpiryDateTime** | Pointer to **time.Time** | Digital LOA expiration date. | [optional] 

## Methods

### NewCreateLoa

`func NewCreateLoa(products []CreateProduct, requestor Party, provider PartyContacts, ) *CreateLoa`

NewCreateLoa instantiates a new CreateLoa object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLoaWithDefaults

`func NewCreateLoaWithDefaults() *CreateLoa`

NewCreateLoaWithDefaults instantiates a new CreateLoa object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProducts

`func (o *CreateLoa) GetProducts() []CreateProduct`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *CreateLoa) GetProductsOk() (*[]CreateProduct, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *CreateLoa) SetProducts(v []CreateProduct)`

SetProducts sets Products field to given value.


### GetRequestor

`func (o *CreateLoa) GetRequestor() Party`

GetRequestor returns the Requestor field if non-nil, zero value otherwise.

### GetRequestorOk

`func (o *CreateLoa) GetRequestorOk() (*Party, bool)`

GetRequestorOk returns a tuple with the Requestor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestor

`func (o *CreateLoa) SetRequestor(v Party)`

SetRequestor sets Requestor field to given value.


### GetProvider

`func (o *CreateLoa) GetProvider() PartyContacts`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateLoa) GetProviderOk() (*PartyContacts, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateLoa) SetProvider(v PartyContacts)`

SetProvider sets Provider field to given value.


### GetNotes

`func (o *CreateLoa) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateLoa) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateLoa) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateLoa) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetExpiryDateTime

`func (o *CreateLoa) GetExpiryDateTime() time.Time`

GetExpiryDateTime returns the ExpiryDateTime field if non-nil, zero value otherwise.

### GetExpiryDateTimeOk

`func (o *CreateLoa) GetExpiryDateTimeOk() (*time.Time, bool)`

GetExpiryDateTimeOk returns a tuple with the ExpiryDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDateTime

`func (o *CreateLoa) SetExpiryDateTime(v time.Time)`

SetExpiryDateTime sets ExpiryDateTime field to given value.

### HasExpiryDateTime

`func (o *CreateLoa) HasExpiryDateTime() bool`

HasExpiryDateTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


