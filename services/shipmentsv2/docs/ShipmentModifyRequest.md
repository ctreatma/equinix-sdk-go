# ShipmentModifyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contacts** | Pointer to [**[]ContactRequestRegisteredUserUpdate**](ContactRequestRegisteredUserUpdate.md) |  | [optional] 
**RequestedDateTime** | Pointer to **time.Time** | Date the requested date and time. | [optional] 
**Details** | Pointer to [**ShipmentModifyRequestDetails**](ShipmentModifyRequestDetails.md) |  | [optional] 

## Methods

### NewShipmentModifyRequest

`func NewShipmentModifyRequest() *ShipmentModifyRequest`

NewShipmentModifyRequest instantiates a new ShipmentModifyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentModifyRequestWithDefaults

`func NewShipmentModifyRequestWithDefaults() *ShipmentModifyRequest`

NewShipmentModifyRequestWithDefaults instantiates a new ShipmentModifyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContacts

`func (o *ShipmentModifyRequest) GetContacts() []ContactRequestRegisteredUserUpdate`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *ShipmentModifyRequest) GetContactsOk() (*[]ContactRequestRegisteredUserUpdate, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *ShipmentModifyRequest) SetContacts(v []ContactRequestRegisteredUserUpdate)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *ShipmentModifyRequest) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetRequestedDateTime

`func (o *ShipmentModifyRequest) GetRequestedDateTime() time.Time`

GetRequestedDateTime returns the RequestedDateTime field if non-nil, zero value otherwise.

### GetRequestedDateTimeOk

`func (o *ShipmentModifyRequest) GetRequestedDateTimeOk() (*time.Time, bool)`

GetRequestedDateTimeOk returns a tuple with the RequestedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDateTime

`func (o *ShipmentModifyRequest) SetRequestedDateTime(v time.Time)`

SetRequestedDateTime sets RequestedDateTime field to given value.

### HasRequestedDateTime

`func (o *ShipmentModifyRequest) HasRequestedDateTime() bool`

HasRequestedDateTime returns a boolean if a field has been set.

### GetDetails

`func (o *ShipmentModifyRequest) GetDetails() ShipmentModifyRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ShipmentModifyRequest) GetDetailsOk() (*ShipmentModifyRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ShipmentModifyRequest) SetDetails(v ShipmentModifyRequestDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ShipmentModifyRequest) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


