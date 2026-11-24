# InvoiceSearchFilters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DateRange** | Pointer to [**InvoiceSearchFiltersDateRange**](InvoiceSearchFiltersDateRange.md) |  | [optional] 
**AccountNumbers** | Pointer to **[]string** |  | [optional] 
**TransactionIds** | Pointer to **[]string** |  | [optional] 
**ProductCodes** | Pointer to **[]string** |  | [optional] 

## Methods

### NewInvoiceSearchFilters

`func NewInvoiceSearchFilters() *InvoiceSearchFilters`

NewInvoiceSearchFilters instantiates a new InvoiceSearchFilters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceSearchFiltersWithDefaults

`func NewInvoiceSearchFiltersWithDefaults() *InvoiceSearchFilters`

NewInvoiceSearchFiltersWithDefaults instantiates a new InvoiceSearchFilters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDateRange

`func (o *InvoiceSearchFilters) GetDateRange() InvoiceSearchFiltersDateRange`

GetDateRange returns the DateRange field if non-nil, zero value otherwise.

### GetDateRangeOk

`func (o *InvoiceSearchFilters) GetDateRangeOk() (*InvoiceSearchFiltersDateRange, bool)`

GetDateRangeOk returns a tuple with the DateRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateRange

`func (o *InvoiceSearchFilters) SetDateRange(v InvoiceSearchFiltersDateRange)`

SetDateRange sets DateRange field to given value.

### HasDateRange

`func (o *InvoiceSearchFilters) HasDateRange() bool`

HasDateRange returns a boolean if a field has been set.

### GetAccountNumbers

`func (o *InvoiceSearchFilters) GetAccountNumbers() []string`

GetAccountNumbers returns the AccountNumbers field if non-nil, zero value otherwise.

### GetAccountNumbersOk

`func (o *InvoiceSearchFilters) GetAccountNumbersOk() (*[]string, bool)`

GetAccountNumbersOk returns a tuple with the AccountNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumbers

`func (o *InvoiceSearchFilters) SetAccountNumbers(v []string)`

SetAccountNumbers sets AccountNumbers field to given value.

### HasAccountNumbers

`func (o *InvoiceSearchFilters) HasAccountNumbers() bool`

HasAccountNumbers returns a boolean if a field has been set.

### GetTransactionIds

`func (o *InvoiceSearchFilters) GetTransactionIds() []string`

GetTransactionIds returns the TransactionIds field if non-nil, zero value otherwise.

### GetTransactionIdsOk

`func (o *InvoiceSearchFilters) GetTransactionIdsOk() (*[]string, bool)`

GetTransactionIdsOk returns a tuple with the TransactionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionIds

`func (o *InvoiceSearchFilters) SetTransactionIds(v []string)`

SetTransactionIds sets TransactionIds field to given value.

### HasTransactionIds

`func (o *InvoiceSearchFilters) HasTransactionIds() bool`

HasTransactionIds returns a boolean if a field has been set.

### GetProductCodes

`func (o *InvoiceSearchFilters) GetProductCodes() []string`

GetProductCodes returns the ProductCodes field if non-nil, zero value otherwise.

### GetProductCodesOk

`func (o *InvoiceSearchFilters) GetProductCodesOk() (*[]string, bool)`

GetProductCodesOk returns a tuple with the ProductCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCodes

`func (o *InvoiceSearchFilters) SetProductCodes(v []string)`

SetProductCodes sets ProductCodes field to given value.

### HasProductCodes

`func (o *InvoiceSearchFilters) HasProductCodes() bool`

HasProductCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


