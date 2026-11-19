# ModifyTicketResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TicketId** | Pointer to **string** | Case or order number. | [optional] 
**Success** | Pointer to **bool** | Indicates whether the modification or reply was successful. | [optional] 

## Methods

### NewModifyTicketResponse

`func NewModifyTicketResponse() *ModifyTicketResponse`

NewModifyTicketResponse instantiates a new ModifyTicketResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModifyTicketResponseWithDefaults

`func NewModifyTicketResponseWithDefaults() *ModifyTicketResponse`

NewModifyTicketResponseWithDefaults instantiates a new ModifyTicketResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTicketId

`func (o *ModifyTicketResponse) GetTicketId() string`

GetTicketId returns the TicketId field if non-nil, zero value otherwise.

### GetTicketIdOk

`func (o *ModifyTicketResponse) GetTicketIdOk() (*string, bool)`

GetTicketIdOk returns a tuple with the TicketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTicketId

`func (o *ModifyTicketResponse) SetTicketId(v string)`

SetTicketId sets TicketId field to given value.

### HasTicketId

`func (o *ModifyTicketResponse) HasTicketId() bool`

HasTicketId returns a boolean if a field has been set.

### GetSuccess

`func (o *ModifyTicketResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ModifyTicketResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ModifyTicketResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *ModifyTicketResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


