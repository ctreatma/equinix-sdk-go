# PriorAdjustmentInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | Pointer to **string** | Original invoice number which credit memo is applicable to. In some cases, this may include multiple documents consisting of credit memos and invoices. | [optional] 
**TotalAmount** | Pointer to **float32** | Original invoice value. This is only applicable to credit memo. | [optional] 
**TransactionDate** | Pointer to **string** | Original invoice date in YYYY-MM-DD. This is only applicable to credit memo. | [optional] 

## Methods

### NewPriorAdjustmentInfo

`func NewPriorAdjustmentInfo() *PriorAdjustmentInfo`

NewPriorAdjustmentInfo instantiates a new PriorAdjustmentInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriorAdjustmentInfoWithDefaults

`func NewPriorAdjustmentInfoWithDefaults() *PriorAdjustmentInfo`

NewPriorAdjustmentInfoWithDefaults instantiates a new PriorAdjustmentInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *PriorAdjustmentInfo) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *PriorAdjustmentInfo) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *PriorAdjustmentInfo) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *PriorAdjustmentInfo) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetTotalAmount

`func (o *PriorAdjustmentInfo) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *PriorAdjustmentInfo) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *PriorAdjustmentInfo) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *PriorAdjustmentInfo) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### GetTransactionDate

`func (o *PriorAdjustmentInfo) GetTransactionDate() string`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *PriorAdjustmentInfo) GetTransactionDateOk() (*string, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *PriorAdjustmentInfo) SetTransactionDate(v string)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *PriorAdjustmentInfo) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


