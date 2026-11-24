# PurchaseOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PurchaseOrderType**](PurchaseOrderType.md) |  | [default to PURCHASEORDERTYPE_EXEMPTED]
**Number** | **string** | Purchase order number is applicable when &#x60;type&#x60; is EXISTING or NEW | 
**Amount** | Pointer to **float32** | This is only applicable when &#x60;type&#x60; is NEW | [optional] 
**StartDate** | Pointer to **string** | This is only applicable when &#x60;type&#x60; is NEW | [optional] 
**EndDate** | Pointer to **string** | This is only applicable when &#x60;type&#x60; is NEW | [optional] 
**AttachmentId** | Pointer to **string** | Attachment ID of Purchase Order document. | [optional] 

## Methods

### NewPurchaseOrder

`func NewPurchaseOrder(type_ PurchaseOrderType, number string, ) *PurchaseOrder`

NewPurchaseOrder instantiates a new PurchaseOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseOrderWithDefaults

`func NewPurchaseOrderWithDefaults() *PurchaseOrder`

NewPurchaseOrderWithDefaults instantiates a new PurchaseOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PurchaseOrder) GetType() PurchaseOrderType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PurchaseOrder) GetTypeOk() (*PurchaseOrderType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PurchaseOrder) SetType(v PurchaseOrderType)`

SetType sets Type field to given value.


### GetNumber

`func (o *PurchaseOrder) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PurchaseOrder) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PurchaseOrder) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetAmount

`func (o *PurchaseOrder) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PurchaseOrder) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PurchaseOrder) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PurchaseOrder) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetStartDate

`func (o *PurchaseOrder) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *PurchaseOrder) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *PurchaseOrder) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *PurchaseOrder) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetEndDate

`func (o *PurchaseOrder) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *PurchaseOrder) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *PurchaseOrder) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *PurchaseOrder) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetAttachmentId

`func (o *PurchaseOrder) GetAttachmentId() string`

GetAttachmentId returns the AttachmentId field if non-nil, zero value otherwise.

### GetAttachmentIdOk

`func (o *PurchaseOrder) GetAttachmentIdOk() (*string, bool)`

GetAttachmentIdOk returns a tuple with the AttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentId

`func (o *PurchaseOrder) SetAttachmentId(v string)`

SetAttachmentId sets AttachmentId field to given value.

### HasAttachmentId

`func (o *PurchaseOrder) HasAttachmentId() bool`

HasAttachmentId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


