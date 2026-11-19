# TicketResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Case or order number. | 
**Type** | [**TicketResponseType**](TicketResponseType.md) |  | 

## Methods

### NewTicketResponse

`func NewTicketResponse(id string, type_ TicketResponseType, ) *TicketResponse`

NewTicketResponse instantiates a new TicketResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketResponseWithDefaults

`func NewTicketResponseWithDefaults() *TicketResponse`

NewTicketResponseWithDefaults instantiates a new TicketResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TicketResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TicketResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TicketResponse) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *TicketResponse) GetType() TicketResponseType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TicketResponse) GetTypeOk() (*TicketResponseType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TicketResponse) SetType(v TicketResponseType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


