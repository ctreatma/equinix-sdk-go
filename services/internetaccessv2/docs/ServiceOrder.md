# ServiceOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | Pointer to [**[]ContactItem**](ContactItem.md) |  | [optional] 
**PurchaseOrder** | Pointer to [**ServicePurchaseOrder**](ServicePurchaseOrder.md) |  | [optional] 
**ReferenceNumber** | Pointer to **string** |  | [optional] 
**Signature** | Pointer to [**OrderSignature**](OrderSignature.md) |  | [optional] 

## Methods

### NewServiceOrder

`func NewServiceOrder() *ServiceOrder`

NewServiceOrder instantiates a new ServiceOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceOrderWithDefaults

`func NewServiceOrderWithDefaults() *ServiceOrder`

NewServiceOrderWithDefaults instantiates a new ServiceOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ServiceOrder) GetContacts() []ContactItem`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ServiceOrder) GetContactsOk() (*[]ContactItem, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ServiceOrder) SetContacts(v []ContactItem)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *ServiceOrder) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *ServiceOrder) GetPurchaseOrder() ServicePurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *ServiceOrder) GetPurchaseOrderOk() (*ServicePurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *ServiceOrder) SetPurchaseOrder(v ServicePurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *ServiceOrder) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetReferenceNumber

`func (o *ServiceOrder) GetReferenceNumber() string`

GetReferenceNumber returns the ReferenceNumber field if non-nil, zero value otherwise.

### GetReferenceNumberOk

`func (o *ServiceOrder) GetReferenceNumberOk() (*string, bool)`

GetReferenceNumberOk returns a tuple with the ReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNumber

`func (o *ServiceOrder) SetReferenceNumber(v string)`

SetReferenceNumber sets ReferenceNumber field to given value.

### HasReferenceNumber

`func (o *ServiceOrder) HasReferenceNumber() bool`

HasReferenceNumber returns a boolean if a field has been set.

### GetSignature

`func (o *ServiceOrder) GetSignature() OrderSignature`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *ServiceOrder) GetSignatureOk() (*OrderSignature, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *ServiceOrder) SetSignature(v OrderSignature)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *ServiceOrder) HasSignature() bool`

HasSignature returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


