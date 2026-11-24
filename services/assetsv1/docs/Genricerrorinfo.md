# Genricerrorinfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Errors** | Pointer to [**[]GenricerrorType**](GenricerrorType.md) |  | [optional] 
**TicketId** | Pointer to **string** |  | [optional] 

## Methods

### NewGenricerrorinfo

`func NewGenricerrorinfo() *Genricerrorinfo`

NewGenricerrorinfo instantiates a new Genricerrorinfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenricerrorinfoWithDefaults

`func NewGenricerrorinfoWithDefaults() *Genricerrorinfo`

NewGenricerrorinfoWithDefaults instantiates a new Genricerrorinfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetErrors

`func (o *Genricerrorinfo) GetErrors() []GenricerrorType`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Genricerrorinfo) GetErrorsOk() (*[]GenricerrorType, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Genricerrorinfo) SetErrors(v []GenricerrorType)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Genricerrorinfo) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetTicketId

`func (o *Genricerrorinfo) GetTicketId() string`

GetTicketId returns the TicketId field if non-nil, zero value otherwise.

### GetTicketIdOk

`func (o *Genricerrorinfo) GetTicketIdOk() (*string, bool)`

GetTicketIdOk returns a tuple with the TicketId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTicketId

`func (o *Genricerrorinfo) SetTicketId(v string)`

SetTicketId sets TicketId field to given value.

### HasTicketId

`func (o *Genricerrorinfo) HasTicketId() bool`

HasTicketId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


