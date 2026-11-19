# PendingStorageRequestShipmentDetailsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StorageId** | **string** |  | 
**Cage** | **string** |  | 
**AccountNumber** | **string** |  | 
**DeliverToCage** | **bool** |  | 
**AdditionalDetails** | Pointer to **string** | Scope of work | [optional] 
**CustomerReferenceNumber** | Pointer to **map[string]interface{}** | You may use numbers and text in this field to enter reference information for your records. This will also appear in your reports and details. You may use this information to search for this content on the submitted requests page. | [optional] 
**PurchaseInformation** | Pointer to **string** | Purchase Order Number | [optional] 

## Methods

### NewPendingStorageRequestShipmentDetailsInner

`func NewPendingStorageRequestShipmentDetailsInner(storageId string, cage string, accountNumber string, deliverToCage bool, ) *PendingStorageRequestShipmentDetailsInner`

NewPendingStorageRequestShipmentDetailsInner instantiates a new PendingStorageRequestShipmentDetailsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingStorageRequestShipmentDetailsInnerWithDefaults

`func NewPendingStorageRequestShipmentDetailsInnerWithDefaults() *PendingStorageRequestShipmentDetailsInner`

NewPendingStorageRequestShipmentDetailsInnerWithDefaults instantiates a new PendingStorageRequestShipmentDetailsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStorageId

`func (o *PendingStorageRequestShipmentDetailsInner) GetStorageId() string`

GetStorageId returns the StorageId field if non-nil, zero value otherwise.

### GetStorageIdOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetStorageIdOk() (*string, bool)`

GetStorageIdOk returns a tuple with the StorageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageId

`func (o *PendingStorageRequestShipmentDetailsInner) SetStorageId(v string)`

SetStorageId sets StorageId field to given value.


### GetCage

`func (o *PendingStorageRequestShipmentDetailsInner) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *PendingStorageRequestShipmentDetailsInner) SetCage(v string)`

SetCage sets Cage field to given value.


### GetAccountNumber

`func (o *PendingStorageRequestShipmentDetailsInner) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *PendingStorageRequestShipmentDetailsInner) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.


### GetDeliverToCage

`func (o *PendingStorageRequestShipmentDetailsInner) GetDeliverToCage() bool`

GetDeliverToCage returns the DeliverToCage field if non-nil, zero value otherwise.

### GetDeliverToCageOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetDeliverToCageOk() (*bool, bool)`

GetDeliverToCageOk returns a tuple with the DeliverToCage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverToCage

`func (o *PendingStorageRequestShipmentDetailsInner) SetDeliverToCage(v bool)`

SetDeliverToCage sets DeliverToCage field to given value.


### GetAdditionalDetails

`func (o *PendingStorageRequestShipmentDetailsInner) GetAdditionalDetails() string`

GetAdditionalDetails returns the AdditionalDetails field if non-nil, zero value otherwise.

### GetAdditionalDetailsOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetAdditionalDetailsOk() (*string, bool)`

GetAdditionalDetailsOk returns a tuple with the AdditionalDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalDetails

`func (o *PendingStorageRequestShipmentDetailsInner) SetAdditionalDetails(v string)`

SetAdditionalDetails sets AdditionalDetails field to given value.

### HasAdditionalDetails

`func (o *PendingStorageRequestShipmentDetailsInner) HasAdditionalDetails() bool`

HasAdditionalDetails returns a boolean if a field has been set.

### GetCustomerReferenceNumber

`func (o *PendingStorageRequestShipmentDetailsInner) GetCustomerReferenceNumber() map[string]interface{}`

GetCustomerReferenceNumber returns the CustomerReferenceNumber field if non-nil, zero value otherwise.

### GetCustomerReferenceNumberOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetCustomerReferenceNumberOk() (*map[string]interface{}, bool)`

GetCustomerReferenceNumberOk returns a tuple with the CustomerReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceNumber

`func (o *PendingStorageRequestShipmentDetailsInner) SetCustomerReferenceNumber(v map[string]interface{})`

SetCustomerReferenceNumber sets CustomerReferenceNumber field to given value.

### HasCustomerReferenceNumber

`func (o *PendingStorageRequestShipmentDetailsInner) HasCustomerReferenceNumber() bool`

HasCustomerReferenceNumber returns a boolean if a field has been set.

### GetPurchaseInformation

`func (o *PendingStorageRequestShipmentDetailsInner) GetPurchaseInformation() string`

GetPurchaseInformation returns the PurchaseInformation field if non-nil, zero value otherwise.

### GetPurchaseInformationOk

`func (o *PendingStorageRequestShipmentDetailsInner) GetPurchaseInformationOk() (*string, bool)`

GetPurchaseInformationOk returns a tuple with the PurchaseInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseInformation

`func (o *PendingStorageRequestShipmentDetailsInner) SetPurchaseInformation(v string)`

SetPurchaseInformation sets PurchaseInformation field to given value.

### HasPurchaseInformation

`func (o *PendingStorageRequestShipmentDetailsInner) HasPurchaseInformation() bool`

HasPurchaseInformation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


