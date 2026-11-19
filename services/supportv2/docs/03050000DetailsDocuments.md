# 03050000DetailsDocuments

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionIds** | **[]string** | List of transaction numbers such as invoice, credit memo or payment numbers. | 
**Type** | [**Model03050000DetailsDocumentsType**](03050000DetailsDocumentsType.md) |  | 
**Formats** | [**[]Model03050000DetailsDocumentsFormatsInner**](Model03050000DetailsDocumentsFormatsInner.md) | Document file format. | 

## Methods

### New03050000DetailsDocuments

`func New03050000DetailsDocuments(transactionIds []string, type_ Model03050000DetailsDocumentsType, formats []Model03050000DetailsDocumentsFormatsInner, ) *03050000DetailsDocuments`

New03050000DetailsDocuments instantiates a new 03050000DetailsDocuments object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### New03050000DetailsDocumentsWithDefaults

`func New03050000DetailsDocumentsWithDefaults() *03050000DetailsDocuments`

New03050000DetailsDocumentsWithDefaults instantiates a new 03050000DetailsDocuments object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionIds

`func (o *03050000DetailsDocuments) GetTransactionIds() []string`

GetTransactionIds returns the TransactionIds field if non-nil, zero value otherwise.

### GetTransactionIdsOk

`func (o *03050000DetailsDocuments) GetTransactionIdsOk() (*[]string, bool)`

GetTransactionIdsOk returns a tuple with the TransactionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionIds

`func (o *03050000DetailsDocuments) SetTransactionIds(v []string)`

SetTransactionIds sets TransactionIds field to given value.


### GetType

`func (o *03050000DetailsDocuments) GetType() Model03050000DetailsDocumentsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *03050000DetailsDocuments) GetTypeOk() (*Model03050000DetailsDocumentsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *03050000DetailsDocuments) SetType(v Model03050000DetailsDocumentsType)`

SetType sets Type field to given value.


### GetFormats

`func (o *03050000DetailsDocuments) GetFormats() []Model03050000DetailsDocumentsFormatsInner`

GetFormats returns the Formats field if non-nil, zero value otherwise.

### GetFormatsOk

`func (o *03050000DetailsDocuments) GetFormatsOk() (*[]Model03050000DetailsDocumentsFormatsInner, bool)`

GetFormatsOk returns a tuple with the Formats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormats

`func (o *03050000DetailsDocuments) SetFormats(v []Model03050000DetailsDocumentsFormatsInner)`

SetFormats sets Formats field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


