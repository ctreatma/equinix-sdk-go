# CustomerDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountName** | Pointer to **string** | Customer account name | [optional] 
**AccountNumber** | Pointer to **string** | Customer account number | [optional] 
**Region** | Pointer to [**CustomerDetailsRegion**](CustomerDetailsRegion.md) |  | [optional] 

## Methods

### NewCustomerDetails

`func NewCustomerDetails() *CustomerDetails`

NewCustomerDetails instantiates a new CustomerDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerDetailsWithDefaults

`func NewCustomerDetailsWithDefaults() *CustomerDetails`

NewCustomerDetailsWithDefaults instantiates a new CustomerDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountName

`func (o *CustomerDetails) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *CustomerDetails) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *CustomerDetails) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *CustomerDetails) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *CustomerDetails) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *CustomerDetails) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *CustomerDetails) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *CustomerDetails) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetRegion

`func (o *CustomerDetails) GetRegion() CustomerDetailsRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CustomerDetails) GetRegionOk() (*CustomerDetailsRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CustomerDetails) SetRegion(v CustomerDetailsRegion)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CustomerDetails) HasRegion() bool`

HasRegion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


