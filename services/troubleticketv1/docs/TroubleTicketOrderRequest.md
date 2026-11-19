# TroubleTicketOrderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomerReferenceNumber** | Pointer to **string** | You may use numbers and text in this field to enter reference information for your records. This will also appear in your reports and details. You may use this information to search for this content on the submitted requests page. | [optional] 
**IbxLocation** | [**IbxLocation**](IbxLocation.md) |  | 
**Contacts** | [**[]ContactInfo**](ContactInfo.md) | Use this array to pass ordering contact, notification contacts and technical contact. Ordering contact and notification contact are mandatory.Only one ordering contact, technical contact are allowed. One or more notification contacts are allowed. Ordering and notification contacts are always registered customers with the customer portal | 
**Attachments** | Pointer to [**[]Attachment**](Attachment.md) | Use this to pass uploaded attachments. Attachments need to be uploaded using the attachments API | [optional] 
**ServiceDetails** | [**TroubleTicketOrderRequestServiceDetails**](TroubleTicketOrderRequestServiceDetails.md) |  | 

## Methods

### NewTroubleTicketOrderRequest

`func NewTroubleTicketOrderRequest(ibxLocation IbxLocation, contacts []ContactInfo, serviceDetails TroubleTicketOrderRequestServiceDetails, ) *TroubleTicketOrderRequest`

NewTroubleTicketOrderRequest instantiates a new TroubleTicketOrderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTroubleTicketOrderRequestWithDefaults

`func NewTroubleTicketOrderRequestWithDefaults() *TroubleTicketOrderRequest`

NewTroubleTicketOrderRequestWithDefaults instantiates a new TroubleTicketOrderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomerReferenceNumber

`func (o *TroubleTicketOrderRequest) GetCustomerReferenceNumber() string`

GetCustomerReferenceNumber returns the CustomerReferenceNumber field if non-nil, zero value otherwise.

### GetCustomerReferenceNumberOk

`func (o *TroubleTicketOrderRequest) GetCustomerReferenceNumberOk() (*string, bool)`

GetCustomerReferenceNumberOk returns a tuple with the CustomerReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceNumber

`func (o *TroubleTicketOrderRequest) SetCustomerReferenceNumber(v string)`

SetCustomerReferenceNumber sets CustomerReferenceNumber field to given value.

### HasCustomerReferenceNumber

`func (o *TroubleTicketOrderRequest) HasCustomerReferenceNumber() bool`

HasCustomerReferenceNumber returns a boolean if a field has been set.

### GetIbxLocation

`func (o *TroubleTicketOrderRequest) GetIbxLocation() IbxLocation`

GetIbxLocation returns the IbxLocation field if non-nil, zero value otherwise.

### GetIbxLocationOk

`func (o *TroubleTicketOrderRequest) GetIbxLocationOk() (*IbxLocation, bool)`

GetIbxLocationOk returns a tuple with the IbxLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocation

`func (o *TroubleTicketOrderRequest) SetIbxLocation(v IbxLocation)`

SetIbxLocation sets IbxLocation field to given value.


### GetContacts

`func (o *TroubleTicketOrderRequest) GetContacts() []ContactInfo`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *TroubleTicketOrderRequest) GetContactsOk() (*[]ContactInfo, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *TroubleTicketOrderRequest) SetContacts(v []ContactInfo)`

SetContacts sets Contacts field to given value.


### GetAttachments

`func (o *TroubleTicketOrderRequest) GetAttachments() []Attachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *TroubleTicketOrderRequest) GetAttachmentsOk() (*[]Attachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *TroubleTicketOrderRequest) SetAttachments(v []Attachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *TroubleTicketOrderRequest) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetServiceDetails

`func (o *TroubleTicketOrderRequest) GetServiceDetails() TroubleTicketOrderRequestServiceDetails`

GetServiceDetails returns the ServiceDetails field if non-nil, zero value otherwise.

### GetServiceDetailsOk

`func (o *TroubleTicketOrderRequest) GetServiceDetailsOk() (*TroubleTicketOrderRequestServiceDetails, bool)`

GetServiceDetailsOk returns a tuple with the ServiceDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDetails

`func (o *TroubleTicketOrderRequest) SetServiceDetails(v TroubleTicketOrderRequestServiceDetails)`

SetServiceDetails sets ServiceDetails field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


