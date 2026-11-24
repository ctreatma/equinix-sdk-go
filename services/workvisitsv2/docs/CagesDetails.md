# CagesDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | ID of the cage that is scheduled for work visit | 
**AccountNumber** | Pointer to **string** | Customer account number that is linked to the cage. | [optional] 
**CabinetId** | Pointer to **string** | The unique ID of cabinet. Provide cabinet ID if you want to limit access to specific cabinets. | [optional] 

## Methods

### NewCagesDetails

`func NewCagesDetails(id string, ) *CagesDetails`

NewCagesDetails instantiates a new CagesDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCagesDetailsWithDefaults

`func NewCagesDetailsWithDefaults() *CagesDetails`

NewCagesDetailsWithDefaults instantiates a new CagesDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CagesDetails) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CagesDetails) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CagesDetails) SetId(v string)`

SetId sets Id field to given value.


### GetAccountNumber

`func (o *CagesDetails) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *CagesDetails) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *CagesDetails) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *CagesDetails) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetCabinetId

`func (o *CagesDetails) GetCabinetId() string`

GetCabinetId returns the CabinetId field if non-nil, zero value otherwise.

### GetCabinetIdOk

`func (o *CagesDetails) GetCabinetIdOk() (*string, bool)`

GetCabinetIdOk returns a tuple with the CabinetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinetId

`func (o *CagesDetails) SetCabinetId(v string)`

SetCabinetId sets CabinetId field to given value.

### HasCabinetId

`func (o *CagesDetails) HasCabinetId() bool`

HasCabinetId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


