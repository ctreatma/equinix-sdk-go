# PendingStorageOrderResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderReferenceId** | Pointer to **string** | Order Reference Id | [optional] 
**OrderNumber** | **string** | Order Number | 
**Id** | Pointer to **string** | Order Id | [optional] 
**SRNumber** | Pointer to **string** | SR Number | [optional] 
**StorageID** | **string** |  | 
**Ibx** | **string** |  | 
**Cage** | **string** |  | 
**AccountNumber** | **string** |  | 
**TrackingNumber** | **string** |  | 

## Methods

### NewPendingStorageOrderResponseInner

`func NewPendingStorageOrderResponseInner(orderNumber string, storageID string, ibx string, cage string, accountNumber string, trackingNumber string, ) *PendingStorageOrderResponseInner`

NewPendingStorageOrderResponseInner instantiates a new PendingStorageOrderResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingStorageOrderResponseInnerWithDefaults

`func NewPendingStorageOrderResponseInnerWithDefaults() *PendingStorageOrderResponseInner`

NewPendingStorageOrderResponseInnerWithDefaults instantiates a new PendingStorageOrderResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderReferenceId

`func (o *PendingStorageOrderResponseInner) GetOrderReferenceId() string`

GetOrderReferenceId returns the OrderReferenceId field if non-nil, zero value otherwise.

### GetOrderReferenceIdOk

`func (o *PendingStorageOrderResponseInner) GetOrderReferenceIdOk() (*string, bool)`

GetOrderReferenceIdOk returns a tuple with the OrderReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderReferenceId

`func (o *PendingStorageOrderResponseInner) SetOrderReferenceId(v string)`

SetOrderReferenceId sets OrderReferenceId field to given value.

### HasOrderReferenceId

`func (o *PendingStorageOrderResponseInner) HasOrderReferenceId() bool`

HasOrderReferenceId returns a boolean if a field has been set.

### GetOrderNumber

`func (o *PendingStorageOrderResponseInner) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *PendingStorageOrderResponseInner) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *PendingStorageOrderResponseInner) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.


### GetId

`func (o *PendingStorageOrderResponseInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PendingStorageOrderResponseInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PendingStorageOrderResponseInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PendingStorageOrderResponseInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSRNumber

`func (o *PendingStorageOrderResponseInner) GetSRNumber() string`

GetSRNumber returns the SRNumber field if non-nil, zero value otherwise.

### GetSRNumberOk

`func (o *PendingStorageOrderResponseInner) GetSRNumberOk() (*string, bool)`

GetSRNumberOk returns a tuple with the SRNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSRNumber

`func (o *PendingStorageOrderResponseInner) SetSRNumber(v string)`

SetSRNumber sets SRNumber field to given value.

### HasSRNumber

`func (o *PendingStorageOrderResponseInner) HasSRNumber() bool`

HasSRNumber returns a boolean if a field has been set.

### GetStorageID

`func (o *PendingStorageOrderResponseInner) GetStorageID() string`

GetStorageID returns the StorageID field if non-nil, zero value otherwise.

### GetStorageIDOk

`func (o *PendingStorageOrderResponseInner) GetStorageIDOk() (*string, bool)`

GetStorageIDOk returns a tuple with the StorageID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageID

`func (o *PendingStorageOrderResponseInner) SetStorageID(v string)`

SetStorageID sets StorageID field to given value.


### GetIbx

`func (o *PendingStorageOrderResponseInner) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *PendingStorageOrderResponseInner) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *PendingStorageOrderResponseInner) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetCage

`func (o *PendingStorageOrderResponseInner) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *PendingStorageOrderResponseInner) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *PendingStorageOrderResponseInner) SetCage(v string)`

SetCage sets Cage field to given value.


### GetAccountNumber

`func (o *PendingStorageOrderResponseInner) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *PendingStorageOrderResponseInner) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *PendingStorageOrderResponseInner) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.


### GetTrackingNumber

`func (o *PendingStorageOrderResponseInner) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *PendingStorageOrderResponseInner) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *PendingStorageOrderResponseInner) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


