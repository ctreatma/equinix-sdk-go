# TicketsDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CallFromCage** | Pointer to **bool** | Requirement for the IBX technician to call the technical contact from the cage. If true, IBX technician will call the technical contact from the cage. | [optional] [default to false]
**Availability** | Pointer to [**COMMONREQUESTCODE00000008Availability**](COMMONREQUESTCODE00000008Availability.md) |  | [optional] [default to COMMONREQUESTCODE00000008AVAILABILITY_ANYTIME]
**Timezone** | Pointer to [**TIMEZONELIST**](TIMEZONELIST.md) |  | [optional] 
**SubmarineEngineerRequired** | Pointer to **bool** | Requirement for submarine cable station engineering support. | [optional] [default to false]
**PurchaseOrderNumber** | Pointer to **string** | Purchase order number | [optional] 
**InvoiceId** | Pointer to **string** | Invoice number / Identifier | [optional] 
**PaymentId** | Pointer to **string** | Payment number / Identifier | [optional] 

## Methods

### NewTicketsDetails

`func NewTicketsDetails() *TicketsDetails`

NewTicketsDetails instantiates a new TicketsDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketsDetailsWithDefaults

`func NewTicketsDetailsWithDefaults() *TicketsDetails`

NewTicketsDetailsWithDefaults instantiates a new TicketsDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCallFromCage

`func (o *TicketsDetails) GetCallFromCage() bool`

GetCallFromCage returns the CallFromCage field if non-nil, zero value otherwise.

### GetCallFromCageOk

`func (o *TicketsDetails) GetCallFromCageOk() (*bool, bool)`

GetCallFromCageOk returns a tuple with the CallFromCage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallFromCage

`func (o *TicketsDetails) SetCallFromCage(v bool)`

SetCallFromCage sets CallFromCage field to given value.

### HasCallFromCage

`func (o *TicketsDetails) HasCallFromCage() bool`

HasCallFromCage returns a boolean if a field has been set.

### GetAvailability

`func (o *TicketsDetails) GetAvailability() COMMONREQUESTCODE00000008Availability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *TicketsDetails) GetAvailabilityOk() (*COMMONREQUESTCODE00000008Availability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *TicketsDetails) SetAvailability(v COMMONREQUESTCODE00000008Availability)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *TicketsDetails) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### GetTimezone

`func (o *TicketsDetails) GetTimezone() TIMEZONELIST`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *TicketsDetails) GetTimezoneOk() (*TIMEZONELIST, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *TicketsDetails) SetTimezone(v TIMEZONELIST)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *TicketsDetails) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetSubmarineEngineerRequired

`func (o *TicketsDetails) GetSubmarineEngineerRequired() bool`

GetSubmarineEngineerRequired returns the SubmarineEngineerRequired field if non-nil, zero value otherwise.

### GetSubmarineEngineerRequiredOk

`func (o *TicketsDetails) GetSubmarineEngineerRequiredOk() (*bool, bool)`

GetSubmarineEngineerRequiredOk returns a tuple with the SubmarineEngineerRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmarineEngineerRequired

`func (o *TicketsDetails) SetSubmarineEngineerRequired(v bool)`

SetSubmarineEngineerRequired sets SubmarineEngineerRequired field to given value.

### HasSubmarineEngineerRequired

`func (o *TicketsDetails) HasSubmarineEngineerRequired() bool`

HasSubmarineEngineerRequired returns a boolean if a field has been set.

### GetPurchaseOrderNumber

`func (o *TicketsDetails) GetPurchaseOrderNumber() string`

GetPurchaseOrderNumber returns the PurchaseOrderNumber field if non-nil, zero value otherwise.

### GetPurchaseOrderNumberOk

`func (o *TicketsDetails) GetPurchaseOrderNumberOk() (*string, bool)`

GetPurchaseOrderNumberOk returns a tuple with the PurchaseOrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrderNumber

`func (o *TicketsDetails) SetPurchaseOrderNumber(v string)`

SetPurchaseOrderNumber sets PurchaseOrderNumber field to given value.

### HasPurchaseOrderNumber

`func (o *TicketsDetails) HasPurchaseOrderNumber() bool`

HasPurchaseOrderNumber returns a boolean if a field has been set.

### GetInvoiceId

`func (o *TicketsDetails) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *TicketsDetails) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *TicketsDetails) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.

### HasInvoiceId

`func (o *TicketsDetails) HasInvoiceId() bool`

HasInvoiceId returns a boolean if a field has been set.

### GetPaymentId

`func (o *TicketsDetails) GetPaymentId() string`

GetPaymentId returns the PaymentId field if non-nil, zero value otherwise.

### GetPaymentIdOk

`func (o *TicketsDetails) GetPaymentIdOk() (*string, bool)`

GetPaymentIdOk returns a tuple with the PaymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentId

`func (o *TicketsDetails) SetPaymentId(v string)`

SetPaymentId sets PaymentId field to given value.

### HasPaymentId

`func (o *TicketsDetails) HasPaymentId() bool`

HasPaymentId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


