# AccountAgreementsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ibx** | Pointer to **string** |  | [optional] 
**Type** | Pointer to [**AccountAgreementsDataType**](AccountAgreementsDataType.md) |  | [optional] 
**Valid** | Pointer to **bool** |  | [optional] 

## Methods

### NewAccountAgreementsData

`func NewAccountAgreementsData() *AccountAgreementsData`

NewAccountAgreementsData instantiates a new AccountAgreementsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountAgreementsDataWithDefaults

`func NewAccountAgreementsDataWithDefaults() *AccountAgreementsData`

NewAccountAgreementsDataWithDefaults instantiates a new AccountAgreementsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbx

`func (o *AccountAgreementsData) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *AccountAgreementsData) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *AccountAgreementsData) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *AccountAgreementsData) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetType

`func (o *AccountAgreementsData) GetType() AccountAgreementsDataType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountAgreementsData) GetTypeOk() (*AccountAgreementsDataType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountAgreementsData) SetType(v AccountAgreementsDataType)`

SetType sets Type field to given value.

### HasType

`func (o *AccountAgreementsData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetValid

`func (o *AccountAgreementsData) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *AccountAgreementsData) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *AccountAgreementsData) SetValid(v bool)`

SetValid sets Valid field to given value.

### HasValid

`func (o *AccountAgreementsData) HasValid() bool`

HasValid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


