# InvoiceSummaryDetailsBillingContacts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** | First name of the contact. | [optional] 
**LastName** | Pointer to **string** | Last name of the contact. | [optional] 
**Details** | Pointer to [**[]ContactDetails**](ContactDetails.md) | Reference of the related party, could be a party reference or a party role reference | [optional] 

## Methods

### NewInvoiceSummaryDetailsBillingContacts

`func NewInvoiceSummaryDetailsBillingContacts() *InvoiceSummaryDetailsBillingContacts`

NewInvoiceSummaryDetailsBillingContacts instantiates a new InvoiceSummaryDetailsBillingContacts object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceSummaryDetailsBillingContactsWithDefaults

`func NewInvoiceSummaryDetailsBillingContactsWithDefaults() *InvoiceSummaryDetailsBillingContacts`

NewInvoiceSummaryDetailsBillingContactsWithDefaults instantiates a new InvoiceSummaryDetailsBillingContacts object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *InvoiceSummaryDetailsBillingContacts) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *InvoiceSummaryDetailsBillingContacts) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *InvoiceSummaryDetailsBillingContacts) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *InvoiceSummaryDetailsBillingContacts) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *InvoiceSummaryDetailsBillingContacts) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *InvoiceSummaryDetailsBillingContacts) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *InvoiceSummaryDetailsBillingContacts) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *InvoiceSummaryDetailsBillingContacts) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetDetails

`func (o *InvoiceSummaryDetailsBillingContacts) GetDetails() []ContactDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *InvoiceSummaryDetailsBillingContacts) GetDetailsOk() (*[]ContactDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *InvoiceSummaryDetailsBillingContacts) SetDetails(v []ContactDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *InvoiceSummaryDetailsBillingContacts) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


