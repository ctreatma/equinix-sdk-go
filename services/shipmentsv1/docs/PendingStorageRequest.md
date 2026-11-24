# PendingStorageRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShipmentDetails** | [**[]PendingStorageRequestShipmentDetailsInner**](PendingStorageRequestShipmentDetailsInner.md) |  | 
**Contacts** | [**[]ContactInfo**](ContactInfo.md) |  | 

## Methods

### NewPendingStorageRequest

`func NewPendingStorageRequest(shipmentDetails []PendingStorageRequestShipmentDetailsInner, contacts []ContactInfo, ) *PendingStorageRequest`

NewPendingStorageRequest instantiates a new PendingStorageRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingStorageRequestWithDefaults

`func NewPendingStorageRequestWithDefaults() *PendingStorageRequest`

NewPendingStorageRequestWithDefaults instantiates a new PendingStorageRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShipmentDetails

`func (o *PendingStorageRequest) GetShipmentDetails() []PendingStorageRequestShipmentDetailsInner`

GetShipmentDetails returns the ShipmentDetails field if non-nil, zero value otherwise.

### GetShipmentDetailsOk

`func (o *PendingStorageRequest) GetShipmentDetailsOk() (*[]PendingStorageRequestShipmentDetailsInner, bool)`

GetShipmentDetailsOk returns a tuple with the ShipmentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentDetails

`func (o *PendingStorageRequest) SetShipmentDetails(v []PendingStorageRequestShipmentDetailsInner)`

SetShipmentDetails sets ShipmentDetails field to given value.


### GetContacts

`func (o *PendingStorageRequest) GetContacts() []ContactInfo`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *PendingStorageRequest) GetContactsOk() (*[]ContactInfo, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *PendingStorageRequest) SetContacts(v []ContactInfo)`

SetContacts sets Contacts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


