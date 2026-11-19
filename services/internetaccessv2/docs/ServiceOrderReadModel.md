# ServiceOrderReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | Pointer to [**[]ContactItem**](ContactItem.md) |  | [optional] 
**PurchaseOrder** | Pointer to [**ServicePurchaseOrder**](ServicePurchaseOrder.md) |  | [optional] 
**ReferenceNumber** | Pointer to **string** |  | [optional] 
**Signature** | Pointer to [**OrderSignature**](OrderSignature.md) |  | [optional] 
**Href** | **string** | Order URI | 
**Uuid** | **string** |  | 
**Type** | [**ServiceOrderType**](ServiceOrderType.md) |  | 
**Status** | [**ServiceOrderStatus**](ServiceOrderStatus.md) |  | 
**ChangeLog** | [**ChangeLog**](ChangeLog.md) |  | 
**Number** | **string** | Order number | 

## Methods

### NewServiceOrderReadModel

`func NewServiceOrderReadModel(href string, uuid string, type_ ServiceOrderType, status ServiceOrderStatus, changeLog ChangeLog, number string, ) *ServiceOrderReadModel`

NewServiceOrderReadModel instantiates a new ServiceOrderReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceOrderReadModelWithDefaults

`func NewServiceOrderReadModelWithDefaults() *ServiceOrderReadModel`

NewServiceOrderReadModelWithDefaults instantiates a new ServiceOrderReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ServiceOrderReadModel) GetContacts() []ContactItem`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ServiceOrderReadModel) GetContactsOk() (*[]ContactItem, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ServiceOrderReadModel) SetContacts(v []ContactItem)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *ServiceOrderReadModel) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *ServiceOrderReadModel) GetPurchaseOrder() ServicePurchaseOrder`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *ServiceOrderReadModel) GetPurchaseOrderOk() (*ServicePurchaseOrder, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *ServiceOrderReadModel) SetPurchaseOrder(v ServicePurchaseOrder)`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *ServiceOrderReadModel) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetReferenceNumber

`func (o *ServiceOrderReadModel) GetReferenceNumber() string`

GetReferenceNumber returns the ReferenceNumber field if non-nil, zero value otherwise.

### GetReferenceNumberOk

`func (o *ServiceOrderReadModel) GetReferenceNumberOk() (*string, bool)`

GetReferenceNumberOk returns a tuple with the ReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceNumber

`func (o *ServiceOrderReadModel) SetReferenceNumber(v string)`

SetReferenceNumber sets ReferenceNumber field to given value.

### HasReferenceNumber

`func (o *ServiceOrderReadModel) HasReferenceNumber() bool`

HasReferenceNumber returns a boolean if a field has been set.

### GetSignature

`func (o *ServiceOrderReadModel) GetSignature() OrderSignature`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *ServiceOrderReadModel) GetSignatureOk() (*OrderSignature, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *ServiceOrderReadModel) SetSignature(v OrderSignature)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *ServiceOrderReadModel) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### GetHref

`func (o *ServiceOrderReadModel) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *ServiceOrderReadModel) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *ServiceOrderReadModel) SetHref(v string)`

SetHref sets Href field to given value.


### GetUuid

`func (o *ServiceOrderReadModel) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ServiceOrderReadModel) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ServiceOrderReadModel) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *ServiceOrderReadModel) GetType() ServiceOrderType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServiceOrderReadModel) GetTypeOk() (*ServiceOrderType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServiceOrderReadModel) SetType(v ServiceOrderType)`

SetType sets Type field to given value.


### GetStatus

`func (o *ServiceOrderReadModel) GetStatus() ServiceOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ServiceOrderReadModel) GetStatusOk() (*ServiceOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ServiceOrderReadModel) SetStatus(v ServiceOrderStatus)`

SetStatus sets Status field to given value.


### GetChangeLog

`func (o *ServiceOrderReadModel) GetChangeLog() ChangeLog`

GetChangeLog returns the ChangeLog field if non-nil, zero value otherwise.

### GetChangeLogOk

`func (o *ServiceOrderReadModel) GetChangeLogOk() (*ChangeLog, bool)`

GetChangeLogOk returns a tuple with the ChangeLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeLog

`func (o *ServiceOrderReadModel) SetChangeLog(v ChangeLog)`

SetChangeLog sets ChangeLog field to given value.


### GetNumber

`func (o *ServiceOrderReadModel) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *ServiceOrderReadModel) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *ServiceOrderReadModel) SetNumber(v string)`

SetNumber sets Number field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


