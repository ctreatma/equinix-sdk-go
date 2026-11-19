# InvoiceSummaryDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | Pointer to **string** | Unique identifier for a specific transaction. A transaction type can be an &#x60;INVOICE&#x60; or &#x60;CREDIT_MEMO&#x60;.  | [optional] 
**BusinessLegalEntity** | Pointer to **string** | Name of the Equinix entity that issued billing document | [optional] 
**CustomerDetails** | Pointer to [**InvoiceSummaryDetailsCustomerDetails**](InvoiceSummaryDetailsCustomerDetails.md) |  | [optional] 
**TransactionType** | Pointer to [**InvoiceSummaryDetailsTransactionType**](InvoiceSummaryDetailsTransactionType.md) |  | [optional] 
**TransactionDate** | Pointer to **string** | Billing Date | [optional] 
**BillingPurchaseOrder** | Pointer to **string** | Purchase order reference for invoice. When there are more than 1 applicable purchase order reference, this field will display multiple instead of showing specific purchase order number.  | [optional] 
**BillingCycle** | Pointer to **string** | The start date which billing is being triggered | [optional] 
**BillingContacts** | Pointer to [**InvoiceSummaryDetailsBillingContacts**](InvoiceSummaryDetailsBillingContacts.md) |  | [optional] 
**PaymentDueDate** | Pointer to **string** | Date which payment is due for the invoice in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**PaymentTerms** | Pointer to **string** | Invoice payment terms | [optional] 
**CurrencyCode** | Pointer to [**CurrencyCode**](CurrencyCode.md) |  | [optional] 
**TotalRecurringAmount** | Pointer to **float32** | Total recurring charges. | [optional] 
**TotalNonRecurringAmount** | Pointer to **float32** | Total non-recurring charges. | [optional] 
**TotalAmount** | Pointer to **float32** | Total invoice charges. This includes recurring and non-recurring charges. | [optional] 
**TotalAdjustment** | Pointer to **float32** | Total adjustment amount.  | [optional] 
**VatNumber** | Pointer to **string** | Customer VAT Registration number | [optional] 
**PaymentInstructions** | Pointer to [**PaymentInstructions**](PaymentInstructions.md) |  | [optional] 
**TaxInfo** | Pointer to [**[]TaxInfo**](TaxInfo.md) |  | [optional] 
**PriorAdjustmentInfo** | Pointer to [**[]PriorAdjustmentInfo**](PriorAdjustmentInfo.md) |  | [optional] 
**TotalPriorAdjustmentAmount** | Pointer to **float32** | Adjusted original total amount. | [optional] 

## Methods

### NewInvoiceSummaryDetails

`func NewInvoiceSummaryDetails() *InvoiceSummaryDetails`

NewInvoiceSummaryDetails instantiates a new InvoiceSummaryDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceSummaryDetailsWithDefaults

`func NewInvoiceSummaryDetailsWithDefaults() *InvoiceSummaryDetails`

NewInvoiceSummaryDetailsWithDefaults instantiates a new InvoiceSummaryDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *InvoiceSummaryDetails) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *InvoiceSummaryDetails) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *InvoiceSummaryDetails) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *InvoiceSummaryDetails) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetBusinessLegalEntity

`func (o *InvoiceSummaryDetails) GetBusinessLegalEntity() string`

GetBusinessLegalEntity returns the BusinessLegalEntity field if non-nil, zero value otherwise.

### GetBusinessLegalEntityOk

`func (o *InvoiceSummaryDetails) GetBusinessLegalEntityOk() (*string, bool)`

GetBusinessLegalEntityOk returns a tuple with the BusinessLegalEntity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessLegalEntity

`func (o *InvoiceSummaryDetails) SetBusinessLegalEntity(v string)`

SetBusinessLegalEntity sets BusinessLegalEntity field to given value.

### HasBusinessLegalEntity

`func (o *InvoiceSummaryDetails) HasBusinessLegalEntity() bool`

HasBusinessLegalEntity returns a boolean if a field has been set.

### GetCustomerDetails

`func (o *InvoiceSummaryDetails) GetCustomerDetails() InvoiceSummaryDetailsCustomerDetails`

GetCustomerDetails returns the CustomerDetails field if non-nil, zero value otherwise.

### GetCustomerDetailsOk

`func (o *InvoiceSummaryDetails) GetCustomerDetailsOk() (*InvoiceSummaryDetailsCustomerDetails, bool)`

GetCustomerDetailsOk returns a tuple with the CustomerDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerDetails

`func (o *InvoiceSummaryDetails) SetCustomerDetails(v InvoiceSummaryDetailsCustomerDetails)`

SetCustomerDetails sets CustomerDetails field to given value.

### HasCustomerDetails

`func (o *InvoiceSummaryDetails) HasCustomerDetails() bool`

HasCustomerDetails returns a boolean if a field has been set.

### GetTransactionType

`func (o *InvoiceSummaryDetails) GetTransactionType() InvoiceSummaryDetailsTransactionType`

GetTransactionType returns the TransactionType field if non-nil, zero value otherwise.

### GetTransactionTypeOk

`func (o *InvoiceSummaryDetails) GetTransactionTypeOk() (*InvoiceSummaryDetailsTransactionType, bool)`

GetTransactionTypeOk returns a tuple with the TransactionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionType

`func (o *InvoiceSummaryDetails) SetTransactionType(v InvoiceSummaryDetailsTransactionType)`

SetTransactionType sets TransactionType field to given value.

### HasTransactionType

`func (o *InvoiceSummaryDetails) HasTransactionType() bool`

HasTransactionType returns a boolean if a field has been set.

### GetTransactionDate

`func (o *InvoiceSummaryDetails) GetTransactionDate() string`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *InvoiceSummaryDetails) GetTransactionDateOk() (*string, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *InvoiceSummaryDetails) SetTransactionDate(v string)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *InvoiceSummaryDetails) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetBillingPurchaseOrder

`func (o *InvoiceSummaryDetails) GetBillingPurchaseOrder() string`

GetBillingPurchaseOrder returns the BillingPurchaseOrder field if non-nil, zero value otherwise.

### GetBillingPurchaseOrderOk

`func (o *InvoiceSummaryDetails) GetBillingPurchaseOrderOk() (*string, bool)`

GetBillingPurchaseOrderOk returns a tuple with the BillingPurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPurchaseOrder

`func (o *InvoiceSummaryDetails) SetBillingPurchaseOrder(v string)`

SetBillingPurchaseOrder sets BillingPurchaseOrder field to given value.

### HasBillingPurchaseOrder

`func (o *InvoiceSummaryDetails) HasBillingPurchaseOrder() bool`

HasBillingPurchaseOrder returns a boolean if a field has been set.

### GetBillingCycle

`func (o *InvoiceSummaryDetails) GetBillingCycle() string`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *InvoiceSummaryDetails) GetBillingCycleOk() (*string, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *InvoiceSummaryDetails) SetBillingCycle(v string)`

SetBillingCycle sets BillingCycle field to given value.

### HasBillingCycle

`func (o *InvoiceSummaryDetails) HasBillingCycle() bool`

HasBillingCycle returns a boolean if a field has been set.

### GetBillingContacts

`func (o *InvoiceSummaryDetails) GetBillingContacts() InvoiceSummaryDetailsBillingContacts`

GetBillingContacts returns the BillingContacts field if non-nil, zero value otherwise.

### GetBillingContactsOk

`func (o *InvoiceSummaryDetails) GetBillingContactsOk() (*InvoiceSummaryDetailsBillingContacts, bool)`

GetBillingContactsOk returns a tuple with the BillingContacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingContacts

`func (o *InvoiceSummaryDetails) SetBillingContacts(v InvoiceSummaryDetailsBillingContacts)`

SetBillingContacts sets BillingContacts field to given value.

### HasBillingContacts

`func (o *InvoiceSummaryDetails) HasBillingContacts() bool`

HasBillingContacts returns a boolean if a field has been set.

### GetPaymentDueDate

`func (o *InvoiceSummaryDetails) GetPaymentDueDate() string`

GetPaymentDueDate returns the PaymentDueDate field if non-nil, zero value otherwise.

### GetPaymentDueDateOk

`func (o *InvoiceSummaryDetails) GetPaymentDueDateOk() (*string, bool)`

GetPaymentDueDateOk returns a tuple with the PaymentDueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDate

`func (o *InvoiceSummaryDetails) SetPaymentDueDate(v string)`

SetPaymentDueDate sets PaymentDueDate field to given value.

### HasPaymentDueDate

`func (o *InvoiceSummaryDetails) HasPaymentDueDate() bool`

HasPaymentDueDate returns a boolean if a field has been set.

### GetPaymentTerms

`func (o *InvoiceSummaryDetails) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *InvoiceSummaryDetails) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *InvoiceSummaryDetails) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *InvoiceSummaryDetails) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *InvoiceSummaryDetails) GetCurrencyCode() CurrencyCode`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *InvoiceSummaryDetails) GetCurrencyCodeOk() (*CurrencyCode, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *InvoiceSummaryDetails) SetCurrencyCode(v CurrencyCode)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *InvoiceSummaryDetails) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTotalRecurringAmount

`func (o *InvoiceSummaryDetails) GetTotalRecurringAmount() float32`

GetTotalRecurringAmount returns the TotalRecurringAmount field if non-nil, zero value otherwise.

### GetTotalRecurringAmountOk

`func (o *InvoiceSummaryDetails) GetTotalRecurringAmountOk() (*float32, bool)`

GetTotalRecurringAmountOk returns a tuple with the TotalRecurringAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRecurringAmount

`func (o *InvoiceSummaryDetails) SetTotalRecurringAmount(v float32)`

SetTotalRecurringAmount sets TotalRecurringAmount field to given value.

### HasTotalRecurringAmount

`func (o *InvoiceSummaryDetails) HasTotalRecurringAmount() bool`

HasTotalRecurringAmount returns a boolean if a field has been set.

### GetTotalNonRecurringAmount

`func (o *InvoiceSummaryDetails) GetTotalNonRecurringAmount() float32`

GetTotalNonRecurringAmount returns the TotalNonRecurringAmount field if non-nil, zero value otherwise.

### GetTotalNonRecurringAmountOk

`func (o *InvoiceSummaryDetails) GetTotalNonRecurringAmountOk() (*float32, bool)`

GetTotalNonRecurringAmountOk returns a tuple with the TotalNonRecurringAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalNonRecurringAmount

`func (o *InvoiceSummaryDetails) SetTotalNonRecurringAmount(v float32)`

SetTotalNonRecurringAmount sets TotalNonRecurringAmount field to given value.

### HasTotalNonRecurringAmount

`func (o *InvoiceSummaryDetails) HasTotalNonRecurringAmount() bool`

HasTotalNonRecurringAmount returns a boolean if a field has been set.

### GetTotalAmount

`func (o *InvoiceSummaryDetails) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *InvoiceSummaryDetails) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *InvoiceSummaryDetails) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *InvoiceSummaryDetails) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### GetTotalAdjustment

`func (o *InvoiceSummaryDetails) GetTotalAdjustment() float32`

GetTotalAdjustment returns the TotalAdjustment field if non-nil, zero value otherwise.

### GetTotalAdjustmentOk

`func (o *InvoiceSummaryDetails) GetTotalAdjustmentOk() (*float32, bool)`

GetTotalAdjustmentOk returns a tuple with the TotalAdjustment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAdjustment

`func (o *InvoiceSummaryDetails) SetTotalAdjustment(v float32)`

SetTotalAdjustment sets TotalAdjustment field to given value.

### HasTotalAdjustment

`func (o *InvoiceSummaryDetails) HasTotalAdjustment() bool`

HasTotalAdjustment returns a boolean if a field has been set.

### GetVatNumber

`func (o *InvoiceSummaryDetails) GetVatNumber() string`

GetVatNumber returns the VatNumber field if non-nil, zero value otherwise.

### GetVatNumberOk

`func (o *InvoiceSummaryDetails) GetVatNumberOk() (*string, bool)`

GetVatNumberOk returns a tuple with the VatNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatNumber

`func (o *InvoiceSummaryDetails) SetVatNumber(v string)`

SetVatNumber sets VatNumber field to given value.

### HasVatNumber

`func (o *InvoiceSummaryDetails) HasVatNumber() bool`

HasVatNumber returns a boolean if a field has been set.

### GetPaymentInstructions

`func (o *InvoiceSummaryDetails) GetPaymentInstructions() PaymentInstructions`

GetPaymentInstructions returns the PaymentInstructions field if non-nil, zero value otherwise.

### GetPaymentInstructionsOk

`func (o *InvoiceSummaryDetails) GetPaymentInstructionsOk() (*PaymentInstructions, bool)`

GetPaymentInstructionsOk returns a tuple with the PaymentInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentInstructions

`func (o *InvoiceSummaryDetails) SetPaymentInstructions(v PaymentInstructions)`

SetPaymentInstructions sets PaymentInstructions field to given value.

### HasPaymentInstructions

`func (o *InvoiceSummaryDetails) HasPaymentInstructions() bool`

HasPaymentInstructions returns a boolean if a field has been set.

### GetTaxInfo

`func (o *InvoiceSummaryDetails) GetTaxInfo() []TaxInfo`

GetTaxInfo returns the TaxInfo field if non-nil, zero value otherwise.

### GetTaxInfoOk

`func (o *InvoiceSummaryDetails) GetTaxInfoOk() (*[]TaxInfo, bool)`

GetTaxInfoOk returns a tuple with the TaxInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxInfo

`func (o *InvoiceSummaryDetails) SetTaxInfo(v []TaxInfo)`

SetTaxInfo sets TaxInfo field to given value.

### HasTaxInfo

`func (o *InvoiceSummaryDetails) HasTaxInfo() bool`

HasTaxInfo returns a boolean if a field has been set.

### GetPriorAdjustmentInfo

`func (o *InvoiceSummaryDetails) GetPriorAdjustmentInfo() []PriorAdjustmentInfo`

GetPriorAdjustmentInfo returns the PriorAdjustmentInfo field if non-nil, zero value otherwise.

### GetPriorAdjustmentInfoOk

`func (o *InvoiceSummaryDetails) GetPriorAdjustmentInfoOk() (*[]PriorAdjustmentInfo, bool)`

GetPriorAdjustmentInfoOk returns a tuple with the PriorAdjustmentInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorAdjustmentInfo

`func (o *InvoiceSummaryDetails) SetPriorAdjustmentInfo(v []PriorAdjustmentInfo)`

SetPriorAdjustmentInfo sets PriorAdjustmentInfo field to given value.

### HasPriorAdjustmentInfo

`func (o *InvoiceSummaryDetails) HasPriorAdjustmentInfo() bool`

HasPriorAdjustmentInfo returns a boolean if a field has been set.

### GetTotalPriorAdjustmentAmount

`func (o *InvoiceSummaryDetails) GetTotalPriorAdjustmentAmount() float32`

GetTotalPriorAdjustmentAmount returns the TotalPriorAdjustmentAmount field if non-nil, zero value otherwise.

### GetTotalPriorAdjustmentAmountOk

`func (o *InvoiceSummaryDetails) GetTotalPriorAdjustmentAmountOk() (*float32, bool)`

GetTotalPriorAdjustmentAmountOk returns a tuple with the TotalPriorAdjustmentAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPriorAdjustmentAmount

`func (o *InvoiceSummaryDetails) SetTotalPriorAdjustmentAmount(v float32)`

SetTotalPriorAdjustmentAmount sets TotalPriorAdjustmentAmount field to given value.

### HasTotalPriorAdjustmentAmount

`func (o *InvoiceSummaryDetails) HasTotalPriorAdjustmentAmount() bool`

HasTotalPriorAdjustmentAmount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


