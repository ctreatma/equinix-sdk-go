# AccountDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountNumber** | **string** |  | 
**AccountName** | **string** |  | 
**Billing** | [**AccountBilling**](AccountBilling.md) |  | 
**OperationalUnits** | [**[]AccountOperationalUnit**](AccountOperationalUnit.md) |  | 
**OrgId** | Pointer to **string** | Customer organization identifier | [optional] 
**OrganizationName** | Pointer to **string** | Customer organization name | [optional] 

## Methods

### NewAccountDetails

`func NewAccountDetails(accountNumber string, accountName string, billing AccountBilling, operationalUnits []AccountOperationalUnit, ) *AccountDetails`

NewAccountDetails instantiates a new AccountDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountDetailsWithDefaults

`func NewAccountDetailsWithDefaults() *AccountDetails`

NewAccountDetailsWithDefaults instantiates a new AccountDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountNumber

`func (o *AccountDetails) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AccountDetails) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AccountDetails) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.


### GetAccountName

`func (o *AccountDetails) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *AccountDetails) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *AccountDetails) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.


### GetBilling

`func (o *AccountDetails) GetBilling() AccountBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *AccountDetails) GetBillingOk() (*AccountBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *AccountDetails) SetBilling(v AccountBilling)`

SetBilling sets Billing field to given value.


### GetOperationalUnits

`func (o *AccountDetails) GetOperationalUnits() []AccountOperationalUnit`

GetOperationalUnits returns the OperationalUnits field if non-nil, zero value otherwise.

### GetOperationalUnitsOk

`func (o *AccountDetails) GetOperationalUnitsOk() (*[]AccountOperationalUnit, bool)`

GetOperationalUnitsOk returns a tuple with the OperationalUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationalUnits

`func (o *AccountDetails) SetOperationalUnits(v []AccountOperationalUnit)`

SetOperationalUnits sets OperationalUnits field to given value.


### GetOrgId

`func (o *AccountDetails) GetOrgId() string`

GetOrgId returns the OrgId field if non-nil, zero value otherwise.

### GetOrgIdOk

`func (o *AccountDetails) GetOrgIdOk() (*string, bool)`

GetOrgIdOk returns a tuple with the OrgId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgId

`func (o *AccountDetails) SetOrgId(v string)`

SetOrgId sets OrgId field to given value.

### HasOrgId

`func (o *AccountDetails) HasOrgId() bool`

HasOrgId returns a boolean if a field has been set.

### GetOrganizationName

`func (o *AccountDetails) GetOrganizationName() string`

GetOrganizationName returns the OrganizationName field if non-nil, zero value otherwise.

### GetOrganizationNameOk

`func (o *AccountDetails) GetOrganizationNameOk() (*string, bool)`

GetOrganizationNameOk returns a tuple with the OrganizationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationName

`func (o *AccountDetails) SetOrganizationName(v string)`

SetOrganizationName sets OrganizationName field to given value.

### HasOrganizationName

`func (o *AccountDetails) HasOrganizationName() bool`

HasOrganizationName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


