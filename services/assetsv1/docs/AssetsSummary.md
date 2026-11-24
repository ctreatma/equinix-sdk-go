# AssetsSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetNumber** | Pointer to **string** | Asset number. | [optional] 
**SerialNumber** | Pointer to **string** | Serial number of the asset. | [optional] 
**OrderNumber** | Pointer to **string** | Order number associated with the asset/service. | [optional] 
**ProductName** | Pointer to **string** | Product type. | [optional] 
**Ibx** | Pointer to **string** | Ibx of the location. | [optional] 
**Cage** | Pointer to **string** | Cage of the location. | [optional] 
**ProductDescription** | Pointer to **string** | Product description. | [optional] 
**AccountNumber** | Pointer to **string** | Account number of the product/services belongs to. | [optional] 
**AccountName** | Pointer to **string** | Account name of the product/services. | [optional] 
**InstallationDate** | Pointer to **time.Time** | Date time of the product or service is purchased/installed. | [optional] 
**CustomerReferenceNumber** | Pointer to **string** | Customer reference number. | [optional] 
**Status** | Pointer to [**AssetsSummaryStatus**](AssetsSummaryStatus.md) |  | [optional] 
**AdditionalDetails** | Pointer to [**AdditionalDetails**](AdditionalDetails.md) |  | [optional] 

## Methods

### NewAssetsSummary

`func NewAssetsSummary() *AssetsSummary`

NewAssetsSummary instantiates a new AssetsSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetsSummaryWithDefaults

`func NewAssetsSummaryWithDefaults() *AssetsSummary`

NewAssetsSummaryWithDefaults instantiates a new AssetsSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetNumber

`func (o *AssetsSummary) GetAssetNumber() string`

GetAssetNumber returns the AssetNumber field if non-nil, zero value otherwise.

### GetAssetNumberOk

`func (o *AssetsSummary) GetAssetNumberOk() (*string, bool)`

GetAssetNumberOk returns a tuple with the AssetNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetNumber

`func (o *AssetsSummary) SetAssetNumber(v string)`

SetAssetNumber sets AssetNumber field to given value.

### HasAssetNumber

`func (o *AssetsSummary) HasAssetNumber() bool`

HasAssetNumber returns a boolean if a field has been set.

### GetSerialNumber

`func (o *AssetsSummary) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *AssetsSummary) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *AssetsSummary) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *AssetsSummary) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetOrderNumber

`func (o *AssetsSummary) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *AssetsSummary) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *AssetsSummary) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *AssetsSummary) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### GetProductName

`func (o *AssetsSummary) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *AssetsSummary) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *AssetsSummary) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *AssetsSummary) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### GetIbx

`func (o *AssetsSummary) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *AssetsSummary) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *AssetsSummary) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *AssetsSummary) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetCage

`func (o *AssetsSummary) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *AssetsSummary) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *AssetsSummary) SetCage(v string)`

SetCage sets Cage field to given value.

### HasCage

`func (o *AssetsSummary) HasCage() bool`

HasCage returns a boolean if a field has been set.

### GetProductDescription

`func (o *AssetsSummary) GetProductDescription() string`

GetProductDescription returns the ProductDescription field if non-nil, zero value otherwise.

### GetProductDescriptionOk

`func (o *AssetsSummary) GetProductDescriptionOk() (*string, bool)`

GetProductDescriptionOk returns a tuple with the ProductDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDescription

`func (o *AssetsSummary) SetProductDescription(v string)`

SetProductDescription sets ProductDescription field to given value.

### HasProductDescription

`func (o *AssetsSummary) HasProductDescription() bool`

HasProductDescription returns a boolean if a field has been set.

### GetAccountNumber

`func (o *AssetsSummary) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *AssetsSummary) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *AssetsSummary) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *AssetsSummary) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountName

`func (o *AssetsSummary) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *AssetsSummary) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *AssetsSummary) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *AssetsSummary) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetInstallationDate

`func (o *AssetsSummary) GetInstallationDate() time.Time`

GetInstallationDate returns the InstallationDate field if non-nil, zero value otherwise.

### GetInstallationDateOk

`func (o *AssetsSummary) GetInstallationDateOk() (*time.Time, bool)`

GetInstallationDateOk returns a tuple with the InstallationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationDate

`func (o *AssetsSummary) SetInstallationDate(v time.Time)`

SetInstallationDate sets InstallationDate field to given value.

### HasInstallationDate

`func (o *AssetsSummary) HasInstallationDate() bool`

HasInstallationDate returns a boolean if a field has been set.

### GetCustomerReferenceNumber

`func (o *AssetsSummary) GetCustomerReferenceNumber() string`

GetCustomerReferenceNumber returns the CustomerReferenceNumber field if non-nil, zero value otherwise.

### GetCustomerReferenceNumberOk

`func (o *AssetsSummary) GetCustomerReferenceNumberOk() (*string, bool)`

GetCustomerReferenceNumberOk returns a tuple with the CustomerReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceNumber

`func (o *AssetsSummary) SetCustomerReferenceNumber(v string)`

SetCustomerReferenceNumber sets CustomerReferenceNumber field to given value.

### HasCustomerReferenceNumber

`func (o *AssetsSummary) HasCustomerReferenceNumber() bool`

HasCustomerReferenceNumber returns a boolean if a field has been set.

### GetStatus

`func (o *AssetsSummary) GetStatus() AssetsSummaryStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AssetsSummary) GetStatusOk() (*AssetsSummaryStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AssetsSummary) SetStatus(v AssetsSummaryStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AssetsSummary) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAdditionalDetails

`func (o *AssetsSummary) GetAdditionalDetails() AdditionalDetails`

GetAdditionalDetails returns the AdditionalDetails field if non-nil, zero value otherwise.

### GetAdditionalDetailsOk

`func (o *AssetsSummary) GetAdditionalDetailsOk() (*AdditionalDetails, bool)`

GetAdditionalDetailsOk returns a tuple with the AdditionalDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalDetails

`func (o *AssetsSummary) SetAdditionalDetails(v AdditionalDetails)`

SetAdditionalDetails sets AdditionalDetails field to given value.

### HasAdditionalDetails

`func (o *AssetsSummary) HasAdditionalDetails() bool`

HasAdditionalDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


