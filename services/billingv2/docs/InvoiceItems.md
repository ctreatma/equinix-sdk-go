# InvoiceItems

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | Pointer to **string** | Unique identifier for a specific transaction. A transaction type can be an &#x60;INVOICE&#x60; or &#x60;CREDIT_MEMO&#x60;.  | [optional] 
**BusinessLegalEntity** | Pointer to **string** | Name of the Equinix entity that issued billing document | [optional] 
**Region** | Pointer to [**InvoiceItemsRegion**](InvoiceItemsRegion.md) |  | [optional] 
**CountryCode** | Pointer to **string** | Country code of the Equinix legal entity. This is not to be confused with the customer legal entity’s countryCode | [optional] 
**TransactionType** | Pointer to [**InvoiceItemsTransactionType**](InvoiceItemsTransactionType.md) |  | [optional] 
**TransactionDate** | Pointer to **string** | Date of transaction in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**OrderId** | Pointer to **string** | Unique identifier of the order | [optional] 
**Channel** | Pointer to [**InvoiceItemsChannel**](InvoiceItemsChannel.md) |  | [optional] 
**SubChannel** | Pointer to [**InvoiceItemsSubChannel**](InvoiceItemsSubChannel.md) |  | [optional] 
**LineNumber** | Pointer to **string** | Line number for line item. | [optional] 
**SubLineNumber** | Pointer to **string** | Sub-line number for line item. | [optional] 
**CustomerDetails** | Pointer to [**InvoiceItemsCustomerDetails**](InvoiceItemsCustomerDetails.md) |  | [optional] 
**PurchaseOrderNumber** | Pointer to **string** | Purchase order number | [optional] 
**BillingAgreementId** | Pointer to **string** | Billing Agreement Number. | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Identifier / External Reference Identifier | [optional] 
**PriorAdjustmentReference** | Pointer to **string** | Prior Adjustment Invoice Id or Credit Memo Id | [optional] 
**Ibxs** | Pointer to **[]string** | Equinix datacenter location code | [optional] 
**RecurringStartDate** | Pointer to **string** | This refers to the start date of &#x60;totalRecurringAmount&#x60; in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**RecurringEndDate** | Pointer to **string** | This refers to the end date of &#x60;totalRecurringAmount&#x60; in &#x60;YYYY-MM-DD&#x60; format | [optional] 
**Contacts** | Pointer to [**[]InvoiceItemsContactsInner**](InvoiceItemsContactsInner.md) |  | [optional] 
**OrderBookedDate** | Pointer to **string** |  | [optional] 
**ActivityType** | Pointer to [**InvoiceItemsActivityType**](InvoiceItemsActivityType.md) |  | [optional] 
**ProductCategory** | Pointer to **string** | Name of product category. | [optional] 
**ProductDescription** | Pointer to **string** | Description of the product. | [optional] 
**ProductCode** | Pointer to **string** | Product catalog code. | [optional] 
**ProductName** | Pointer to **string** | Product name. | [optional] 
**DetailedDescription** | Pointer to **string** |  | [optional] 
**IbxDescription** | Pointer to **string** |  | [optional] 
**Quantity** | Pointer to **float32** | The total amount of quantity bought. To be used with &#x60;unitOfMeasure&#x60; | [optional] 
**UnitOfMeasure** | Pointer to **string** | Metric of &#x60;quantity&#x60;  | [optional] 
**UnitPrice** | Pointer to **float32** | The unit price of product / service | [optional] 
**Frequency** | Pointer to [**InvoiceItemsFrequency**](InvoiceItemsFrequency.md) |  | [optional] 
**CurrencyCode** | Pointer to [**CurrencyCode**](CurrencyCode.md) |  | [optional] 
**LocalCurrencyCode** | Pointer to [**CurrencyCode**](CurrencyCode.md) |  | [optional] 
**ExchangeRate** | Pointer to **float32** | The exchange rate used in computing charges when local currency is different from invoice currency.  | [optional] 
**NonRecurringAmount** | Pointer to **float32** | Amount of non-recurring charges. | [optional] 
**RecurringAmount** | Pointer to **float32** | Amount of recurring charges. | [optional] 
**Adjustment** | Pointer to **float32** | Amount of discounts or adjustments applied | [optional] 
**TaxAmount** | Pointer to **float32** | Amount of tax applied | [optional] 
**TotalAmount** | Pointer to **float32** | Net total amount after applicable taxes and discounts.  | [optional] 
**LegacyOrderId** | Pointer to **string** | Order ID that were previously used in legacy orders | [optional] 
**AdditionalInfo** | Pointer to [**[]AdditionalDetailsOfTheProductInner**](AdditionalDetailsOfTheProductInner.md) |  | [optional] 
**TermsOfUse** | Pointer to [**[]TermsOfUseItems**](TermsOfUseItems.md) |  | [optional] 

## Methods

### NewInvoiceItems

`func NewInvoiceItems() *InvoiceItems`

NewInvoiceItems instantiates a new InvoiceItems object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceItemsWithDefaults

`func NewInvoiceItemsWithDefaults() *InvoiceItems`

NewInvoiceItemsWithDefaults instantiates a new InvoiceItems object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *InvoiceItems) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *InvoiceItems) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *InvoiceItems) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *InvoiceItems) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetBusinessLegalEntity

`func (o *InvoiceItems) GetBusinessLegalEntity() string`

GetBusinessLegalEntity returns the BusinessLegalEntity field if non-nil, zero value otherwise.

### GetBusinessLegalEntityOk

`func (o *InvoiceItems) GetBusinessLegalEntityOk() (*string, bool)`

GetBusinessLegalEntityOk returns a tuple with the BusinessLegalEntity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessLegalEntity

`func (o *InvoiceItems) SetBusinessLegalEntity(v string)`

SetBusinessLegalEntity sets BusinessLegalEntity field to given value.

### HasBusinessLegalEntity

`func (o *InvoiceItems) HasBusinessLegalEntity() bool`

HasBusinessLegalEntity returns a boolean if a field has been set.

### GetRegion

`func (o *InvoiceItems) GetRegion() InvoiceItemsRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *InvoiceItems) GetRegionOk() (*InvoiceItemsRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *InvoiceItems) SetRegion(v InvoiceItemsRegion)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *InvoiceItems) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetCountryCode

`func (o *InvoiceItems) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *InvoiceItems) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *InvoiceItems) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *InvoiceItems) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetTransactionType

`func (o *InvoiceItems) GetTransactionType() InvoiceItemsTransactionType`

GetTransactionType returns the TransactionType field if non-nil, zero value otherwise.

### GetTransactionTypeOk

`func (o *InvoiceItems) GetTransactionTypeOk() (*InvoiceItemsTransactionType, bool)`

GetTransactionTypeOk returns a tuple with the TransactionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionType

`func (o *InvoiceItems) SetTransactionType(v InvoiceItemsTransactionType)`

SetTransactionType sets TransactionType field to given value.

### HasTransactionType

`func (o *InvoiceItems) HasTransactionType() bool`

HasTransactionType returns a boolean if a field has been set.

### GetTransactionDate

`func (o *InvoiceItems) GetTransactionDate() string`

GetTransactionDate returns the TransactionDate field if non-nil, zero value otherwise.

### GetTransactionDateOk

`func (o *InvoiceItems) GetTransactionDateOk() (*string, bool)`

GetTransactionDateOk returns a tuple with the TransactionDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionDate

`func (o *InvoiceItems) SetTransactionDate(v string)`

SetTransactionDate sets TransactionDate field to given value.

### HasTransactionDate

`func (o *InvoiceItems) HasTransactionDate() bool`

HasTransactionDate returns a boolean if a field has been set.

### GetOrderId

`func (o *InvoiceItems) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *InvoiceItems) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *InvoiceItems) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *InvoiceItems) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetChannel

`func (o *InvoiceItems) GetChannel() InvoiceItemsChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *InvoiceItems) GetChannelOk() (*InvoiceItemsChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *InvoiceItems) SetChannel(v InvoiceItemsChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *InvoiceItems) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetSubChannel

`func (o *InvoiceItems) GetSubChannel() InvoiceItemsSubChannel`

GetSubChannel returns the SubChannel field if non-nil, zero value otherwise.

### GetSubChannelOk

`func (o *InvoiceItems) GetSubChannelOk() (*InvoiceItemsSubChannel, bool)`

GetSubChannelOk returns a tuple with the SubChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubChannel

`func (o *InvoiceItems) SetSubChannel(v InvoiceItemsSubChannel)`

SetSubChannel sets SubChannel field to given value.

### HasSubChannel

`func (o *InvoiceItems) HasSubChannel() bool`

HasSubChannel returns a boolean if a field has been set.

### GetLineNumber

`func (o *InvoiceItems) GetLineNumber() string`

GetLineNumber returns the LineNumber field if non-nil, zero value otherwise.

### GetLineNumberOk

`func (o *InvoiceItems) GetLineNumberOk() (*string, bool)`

GetLineNumberOk returns a tuple with the LineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineNumber

`func (o *InvoiceItems) SetLineNumber(v string)`

SetLineNumber sets LineNumber field to given value.

### HasLineNumber

`func (o *InvoiceItems) HasLineNumber() bool`

HasLineNumber returns a boolean if a field has been set.

### GetSubLineNumber

`func (o *InvoiceItems) GetSubLineNumber() string`

GetSubLineNumber returns the SubLineNumber field if non-nil, zero value otherwise.

### GetSubLineNumberOk

`func (o *InvoiceItems) GetSubLineNumberOk() (*string, bool)`

GetSubLineNumberOk returns a tuple with the SubLineNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubLineNumber

`func (o *InvoiceItems) SetSubLineNumber(v string)`

SetSubLineNumber sets SubLineNumber field to given value.

### HasSubLineNumber

`func (o *InvoiceItems) HasSubLineNumber() bool`

HasSubLineNumber returns a boolean if a field has been set.

### GetCustomerDetails

`func (o *InvoiceItems) GetCustomerDetails() InvoiceItemsCustomerDetails`

GetCustomerDetails returns the CustomerDetails field if non-nil, zero value otherwise.

### GetCustomerDetailsOk

`func (o *InvoiceItems) GetCustomerDetailsOk() (*InvoiceItemsCustomerDetails, bool)`

GetCustomerDetailsOk returns a tuple with the CustomerDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerDetails

`func (o *InvoiceItems) SetCustomerDetails(v InvoiceItemsCustomerDetails)`

SetCustomerDetails sets CustomerDetails field to given value.

### HasCustomerDetails

`func (o *InvoiceItems) HasCustomerDetails() bool`

HasCustomerDetails returns a boolean if a field has been set.

### GetPurchaseOrderNumber

`func (o *InvoiceItems) GetPurchaseOrderNumber() string`

GetPurchaseOrderNumber returns the PurchaseOrderNumber field if non-nil, zero value otherwise.

### GetPurchaseOrderNumberOk

`func (o *InvoiceItems) GetPurchaseOrderNumberOk() (*string, bool)`

GetPurchaseOrderNumberOk returns a tuple with the PurchaseOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderNumber

`func (o *InvoiceItems) SetPurchaseOrderNumber(v string)`

SetPurchaseOrderNumber sets PurchaseOrderNumber field to given value.

### HasPurchaseOrderNumber

`func (o *InvoiceItems) HasPurchaseOrderNumber() bool`

HasPurchaseOrderNumber returns a boolean if a field has been set.

### GetBillingAgreementId

`func (o *InvoiceItems) GetBillingAgreementId() string`

GetBillingAgreementId returns the BillingAgreementId field if non-nil, zero value otherwise.

### GetBillingAgreementIdOk

`func (o *InvoiceItems) GetBillingAgreementIdOk() (*string, bool)`

GetBillingAgreementIdOk returns a tuple with the BillingAgreementId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingAgreementId

`func (o *InvoiceItems) SetBillingAgreementId(v string)`

SetBillingAgreementId sets BillingAgreementId field to given value.

### HasBillingAgreementId

`func (o *InvoiceItems) HasBillingAgreementId() bool`

HasBillingAgreementId returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *InvoiceItems) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *InvoiceItems) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *InvoiceItems) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *InvoiceItems) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetPriorAdjustmentReference

`func (o *InvoiceItems) GetPriorAdjustmentReference() string`

GetPriorAdjustmentReference returns the PriorAdjustmentReference field if non-nil, zero value otherwise.

### GetPriorAdjustmentReferenceOk

`func (o *InvoiceItems) GetPriorAdjustmentReferenceOk() (*string, bool)`

GetPriorAdjustmentReferenceOk returns a tuple with the PriorAdjustmentReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriorAdjustmentReference

`func (o *InvoiceItems) SetPriorAdjustmentReference(v string)`

SetPriorAdjustmentReference sets PriorAdjustmentReference field to given value.

### HasPriorAdjustmentReference

`func (o *InvoiceItems) HasPriorAdjustmentReference() bool`

HasPriorAdjustmentReference returns a boolean if a field has been set.

### GetIbxs

`func (o *InvoiceItems) GetIbxs() []string`

GetIbxs returns the Ibxs field if non-nil, zero value otherwise.

### GetIbxsOk

`func (o *InvoiceItems) GetIbxsOk() (*[]string, bool)`

GetIbxsOk returns a tuple with the Ibxs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxs

`func (o *InvoiceItems) SetIbxs(v []string)`

SetIbxs sets Ibxs field to given value.

### HasIbxs

`func (o *InvoiceItems) HasIbxs() bool`

HasIbxs returns a boolean if a field has been set.

### GetRecurringStartDate

`func (o *InvoiceItems) GetRecurringStartDate() string`

GetRecurringStartDate returns the RecurringStartDate field if non-nil, zero value otherwise.

### GetRecurringStartDateOk

`func (o *InvoiceItems) GetRecurringStartDateOk() (*string, bool)`

GetRecurringStartDateOk returns a tuple with the RecurringStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringStartDate

`func (o *InvoiceItems) SetRecurringStartDate(v string)`

SetRecurringStartDate sets RecurringStartDate field to given value.

### HasRecurringStartDate

`func (o *InvoiceItems) HasRecurringStartDate() bool`

HasRecurringStartDate returns a boolean if a field has been set.

### GetRecurringEndDate

`func (o *InvoiceItems) GetRecurringEndDate() string`

GetRecurringEndDate returns the RecurringEndDate field if non-nil, zero value otherwise.

### GetRecurringEndDateOk

`func (o *InvoiceItems) GetRecurringEndDateOk() (*string, bool)`

GetRecurringEndDateOk returns a tuple with the RecurringEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringEndDate

`func (o *InvoiceItems) SetRecurringEndDate(v string)`

SetRecurringEndDate sets RecurringEndDate field to given value.

### HasRecurringEndDate

`func (o *InvoiceItems) HasRecurringEndDate() bool`

HasRecurringEndDate returns a boolean if a field has been set.

### GetContacts

`func (o *InvoiceItems) GetContacts() []InvoiceItemsContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *InvoiceItems) GetContactsOk() (*[]InvoiceItemsContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *InvoiceItems) SetContacts(v []InvoiceItemsContactsInner)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *InvoiceItems) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetOrderBookedDate

`func (o *InvoiceItems) GetOrderBookedDate() string`

GetOrderBookedDate returns the OrderBookedDate field if non-nil, zero value otherwise.

### GetOrderBookedDateOk

`func (o *InvoiceItems) GetOrderBookedDateOk() (*string, bool)`

GetOrderBookedDateOk returns a tuple with the OrderBookedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderBookedDate

`func (o *InvoiceItems) SetOrderBookedDate(v string)`

SetOrderBookedDate sets OrderBookedDate field to given value.

### HasOrderBookedDate

`func (o *InvoiceItems) HasOrderBookedDate() bool`

HasOrderBookedDate returns a boolean if a field has been set.

### GetActivityType

`func (o *InvoiceItems) GetActivityType() InvoiceItemsActivityType`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *InvoiceItems) GetActivityTypeOk() (*InvoiceItemsActivityType, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *InvoiceItems) SetActivityType(v InvoiceItemsActivityType)`

SetActivityType sets ActivityType field to given value.

### HasActivityType

`func (o *InvoiceItems) HasActivityType() bool`

HasActivityType returns a boolean if a field has been set.

### GetProductCategory

`func (o *InvoiceItems) GetProductCategory() string`

GetProductCategory returns the ProductCategory field if non-nil, zero value otherwise.

### GetProductCategoryOk

`func (o *InvoiceItems) GetProductCategoryOk() (*string, bool)`

GetProductCategoryOk returns a tuple with the ProductCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCategory

`func (o *InvoiceItems) SetProductCategory(v string)`

SetProductCategory sets ProductCategory field to given value.

### HasProductCategory

`func (o *InvoiceItems) HasProductCategory() bool`

HasProductCategory returns a boolean if a field has been set.

### GetProductDescription

`func (o *InvoiceItems) GetProductDescription() string`

GetProductDescription returns the ProductDescription field if non-nil, zero value otherwise.

### GetProductDescriptionOk

`func (o *InvoiceItems) GetProductDescriptionOk() (*string, bool)`

GetProductDescriptionOk returns a tuple with the ProductDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDescription

`func (o *InvoiceItems) SetProductDescription(v string)`

SetProductDescription sets ProductDescription field to given value.

### HasProductDescription

`func (o *InvoiceItems) HasProductDescription() bool`

HasProductDescription returns a boolean if a field has been set.

### GetProductCode

`func (o *InvoiceItems) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *InvoiceItems) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *InvoiceItems) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.

### HasProductCode

`func (o *InvoiceItems) HasProductCode() bool`

HasProductCode returns a boolean if a field has been set.

### GetProductName

`func (o *InvoiceItems) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *InvoiceItems) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *InvoiceItems) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *InvoiceItems) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### GetDetailedDescription

`func (o *InvoiceItems) GetDetailedDescription() string`

GetDetailedDescription returns the DetailedDescription field if non-nil, zero value otherwise.

### GetDetailedDescriptionOk

`func (o *InvoiceItems) GetDetailedDescriptionOk() (*string, bool)`

GetDetailedDescriptionOk returns a tuple with the DetailedDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetailedDescription

`func (o *InvoiceItems) SetDetailedDescription(v string)`

SetDetailedDescription sets DetailedDescription field to given value.

### HasDetailedDescription

`func (o *InvoiceItems) HasDetailedDescription() bool`

HasDetailedDescription returns a boolean if a field has been set.

### GetIbxDescription

`func (o *InvoiceItems) GetIbxDescription() string`

GetIbxDescription returns the IbxDescription field if non-nil, zero value otherwise.

### GetIbxDescriptionOk

`func (o *InvoiceItems) GetIbxDescriptionOk() (*string, bool)`

GetIbxDescriptionOk returns a tuple with the IbxDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxDescription

`func (o *InvoiceItems) SetIbxDescription(v string)`

SetIbxDescription sets IbxDescription field to given value.

### HasIbxDescription

`func (o *InvoiceItems) HasIbxDescription() bool`

HasIbxDescription returns a boolean if a field has been set.

### GetQuantity

`func (o *InvoiceItems) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InvoiceItems) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InvoiceItems) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *InvoiceItems) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetUnitOfMeasure

`func (o *InvoiceItems) GetUnitOfMeasure() string`

GetUnitOfMeasure returns the UnitOfMeasure field if non-nil, zero value otherwise.

### GetUnitOfMeasureOk

`func (o *InvoiceItems) GetUnitOfMeasureOk() (*string, bool)`

GetUnitOfMeasureOk returns a tuple with the UnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitOfMeasure

`func (o *InvoiceItems) SetUnitOfMeasure(v string)`

SetUnitOfMeasure sets UnitOfMeasure field to given value.

### HasUnitOfMeasure

`func (o *InvoiceItems) HasUnitOfMeasure() bool`

HasUnitOfMeasure returns a boolean if a field has been set.

### GetUnitPrice

`func (o *InvoiceItems) GetUnitPrice() float32`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *InvoiceItems) GetUnitPriceOk() (*float32, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *InvoiceItems) SetUnitPrice(v float32)`

SetUnitPrice sets UnitPrice field to given value.

### HasUnitPrice

`func (o *InvoiceItems) HasUnitPrice() bool`

HasUnitPrice returns a boolean if a field has been set.

### GetFrequency

`func (o *InvoiceItems) GetFrequency() InvoiceItemsFrequency`

GetFrequency returns the Frequency field if non-nil, zero value otherwise.

### GetFrequencyOk

`func (o *InvoiceItems) GetFrequencyOk() (*InvoiceItemsFrequency, bool)`

GetFrequencyOk returns a tuple with the Frequency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequency

`func (o *InvoiceItems) SetFrequency(v InvoiceItemsFrequency)`

SetFrequency sets Frequency field to given value.

### HasFrequency

`func (o *InvoiceItems) HasFrequency() bool`

HasFrequency returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *InvoiceItems) GetCurrencyCode() CurrencyCode`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *InvoiceItems) GetCurrencyCodeOk() (*CurrencyCode, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *InvoiceItems) SetCurrencyCode(v CurrencyCode)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *InvoiceItems) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetLocalCurrencyCode

`func (o *InvoiceItems) GetLocalCurrencyCode() CurrencyCode`

GetLocalCurrencyCode returns the LocalCurrencyCode field if non-nil, zero value otherwise.

### GetLocalCurrencyCodeOk

`func (o *InvoiceItems) GetLocalCurrencyCodeOk() (*CurrencyCode, bool)`

GetLocalCurrencyCodeOk returns a tuple with the LocalCurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalCurrencyCode

`func (o *InvoiceItems) SetLocalCurrencyCode(v CurrencyCode)`

SetLocalCurrencyCode sets LocalCurrencyCode field to given value.

### HasLocalCurrencyCode

`func (o *InvoiceItems) HasLocalCurrencyCode() bool`

HasLocalCurrencyCode returns a boolean if a field has been set.

### GetExchangeRate

`func (o *InvoiceItems) GetExchangeRate() float32`

GetExchangeRate returns the ExchangeRate field if non-nil, zero value otherwise.

### GetExchangeRateOk

`func (o *InvoiceItems) GetExchangeRateOk() (*float32, bool)`

GetExchangeRateOk returns a tuple with the ExchangeRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeRate

`func (o *InvoiceItems) SetExchangeRate(v float32)`

SetExchangeRate sets ExchangeRate field to given value.

### HasExchangeRate

`func (o *InvoiceItems) HasExchangeRate() bool`

HasExchangeRate returns a boolean if a field has been set.

### GetNonRecurringAmount

`func (o *InvoiceItems) GetNonRecurringAmount() float32`

GetNonRecurringAmount returns the NonRecurringAmount field if non-nil, zero value otherwise.

### GetNonRecurringAmountOk

`func (o *InvoiceItems) GetNonRecurringAmountOk() (*float32, bool)`

GetNonRecurringAmountOk returns a tuple with the NonRecurringAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonRecurringAmount

`func (o *InvoiceItems) SetNonRecurringAmount(v float32)`

SetNonRecurringAmount sets NonRecurringAmount field to given value.

### HasNonRecurringAmount

`func (o *InvoiceItems) HasNonRecurringAmount() bool`

HasNonRecurringAmount returns a boolean if a field has been set.

### GetRecurringAmount

`func (o *InvoiceItems) GetRecurringAmount() float32`

GetRecurringAmount returns the RecurringAmount field if non-nil, zero value otherwise.

### GetRecurringAmountOk

`func (o *InvoiceItems) GetRecurringAmountOk() (*float32, bool)`

GetRecurringAmountOk returns a tuple with the RecurringAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringAmount

`func (o *InvoiceItems) SetRecurringAmount(v float32)`

SetRecurringAmount sets RecurringAmount field to given value.

### HasRecurringAmount

`func (o *InvoiceItems) HasRecurringAmount() bool`

HasRecurringAmount returns a boolean if a field has been set.

### GetAdjustment

`func (o *InvoiceItems) GetAdjustment() float32`

GetAdjustment returns the Adjustment field if non-nil, zero value otherwise.

### GetAdjustmentOk

`func (o *InvoiceItems) GetAdjustmentOk() (*float32, bool)`

GetAdjustmentOk returns a tuple with the Adjustment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustment

`func (o *InvoiceItems) SetAdjustment(v float32)`

SetAdjustment sets Adjustment field to given value.

### HasAdjustment

`func (o *InvoiceItems) HasAdjustment() bool`

HasAdjustment returns a boolean if a field has been set.

### GetTaxAmount

`func (o *InvoiceItems) GetTaxAmount() float32`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *InvoiceItems) GetTaxAmountOk() (*float32, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *InvoiceItems) SetTaxAmount(v float32)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *InvoiceItems) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### GetTotalAmount

`func (o *InvoiceItems) GetTotalAmount() float32`

GetTotalAmount returns the TotalAmount field if non-nil, zero value otherwise.

### GetTotalAmountOk

`func (o *InvoiceItems) GetTotalAmountOk() (*float32, bool)`

GetTotalAmountOk returns a tuple with the TotalAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmount

`func (o *InvoiceItems) SetTotalAmount(v float32)`

SetTotalAmount sets TotalAmount field to given value.

### HasTotalAmount

`func (o *InvoiceItems) HasTotalAmount() bool`

HasTotalAmount returns a boolean if a field has been set.

### GetLegacyOrderId

`func (o *InvoiceItems) GetLegacyOrderId() string`

GetLegacyOrderId returns the LegacyOrderId field if non-nil, zero value otherwise.

### GetLegacyOrderIdOk

`func (o *InvoiceItems) GetLegacyOrderIdOk() (*string, bool)`

GetLegacyOrderIdOk returns a tuple with the LegacyOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegacyOrderId

`func (o *InvoiceItems) SetLegacyOrderId(v string)`

SetLegacyOrderId sets LegacyOrderId field to given value.

### HasLegacyOrderId

`func (o *InvoiceItems) HasLegacyOrderId() bool`

HasLegacyOrderId returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *InvoiceItems) GetAdditionalInfo() []AdditionalDetailsOfTheProductInner`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *InvoiceItems) GetAdditionalInfoOk() (*[]AdditionalDetailsOfTheProductInner, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *InvoiceItems) SetAdditionalInfo(v []AdditionalDetailsOfTheProductInner)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *InvoiceItems) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.

### GetTermsOfUse

`func (o *InvoiceItems) GetTermsOfUse() []TermsOfUseItems`

GetTermsOfUse returns the TermsOfUse field if non-nil, zero value otherwise.

### GetTermsOfUseOk

`func (o *InvoiceItems) GetTermsOfUseOk() (*[]TermsOfUseItems, bool)`

GetTermsOfUseOk returns a tuple with the TermsOfUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfUse

`func (o *InvoiceItems) SetTermsOfUse(v []TermsOfUseItems)`

SetTermsOfUse sets TermsOfUse field to given value.

### HasTermsOfUse

`func (o *InvoiceItems) HasTermsOfUse() bool`

HasTermsOfUse returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


