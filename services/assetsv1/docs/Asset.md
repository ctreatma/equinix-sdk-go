# Asset

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
**ProductDetails** | Pointer to [**[]AssetsProperty**](AssetsProperty.md) | key/value pairs of product details. | [optional] 

## Methods

### NewAsset

`func NewAsset() *Asset`

NewAsset instantiates a new Asset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetWithDefaults

`func NewAssetWithDefaults() *Asset`

NewAssetWithDefaults instantiates a new Asset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetNumber

`func (o *Asset) GetAssetNumber() string`

GetAssetNumber returns the AssetNumber field if non-nil, zero value otherwise.

### GetAssetNumberOk

`func (o *Asset) GetAssetNumberOk() (*string, bool)`

GetAssetNumberOk returns a tuple with the AssetNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetNumber

`func (o *Asset) SetAssetNumber(v string)`

SetAssetNumber sets AssetNumber field to given value.

### HasAssetNumber

`func (o *Asset) HasAssetNumber() bool`

HasAssetNumber returns a boolean if a field has been set.

### GetSerialNumber

`func (o *Asset) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *Asset) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *Asset) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.

### HasSerialNumber

`func (o *Asset) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.

### GetOrderNumber

`func (o *Asset) GetOrderNumber() string`

GetOrderNumber returns the OrderNumber field if non-nil, zero value otherwise.

### GetOrderNumberOk

`func (o *Asset) GetOrderNumberOk() (*string, bool)`

GetOrderNumberOk returns a tuple with the OrderNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderNumber

`func (o *Asset) SetOrderNumber(v string)`

SetOrderNumber sets OrderNumber field to given value.

### HasOrderNumber

`func (o *Asset) HasOrderNumber() bool`

HasOrderNumber returns a boolean if a field has been set.

### GetProductName

`func (o *Asset) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *Asset) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *Asset) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *Asset) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### GetIbx

`func (o *Asset) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *Asset) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *Asset) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *Asset) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetCage

`func (o *Asset) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *Asset) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *Asset) SetCage(v string)`

SetCage sets Cage field to given value.

### HasCage

`func (o *Asset) HasCage() bool`

HasCage returns a boolean if a field has been set.

### GetProductDescription

`func (o *Asset) GetProductDescription() string`

GetProductDescription returns the ProductDescription field if non-nil, zero value otherwise.

### GetProductDescriptionOk

`func (o *Asset) GetProductDescriptionOk() (*string, bool)`

GetProductDescriptionOk returns a tuple with the ProductDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDescription

`func (o *Asset) SetProductDescription(v string)`

SetProductDescription sets ProductDescription field to given value.

### HasProductDescription

`func (o *Asset) HasProductDescription() bool`

HasProductDescription returns a boolean if a field has been set.

### GetAccountNumber

`func (o *Asset) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *Asset) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *Asset) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *Asset) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetAccountName

`func (o *Asset) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *Asset) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *Asset) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *Asset) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetInstallationDate

`func (o *Asset) GetInstallationDate() time.Time`

GetInstallationDate returns the InstallationDate field if non-nil, zero value otherwise.

### GetInstallationDateOk

`func (o *Asset) GetInstallationDateOk() (*time.Time, bool)`

GetInstallationDateOk returns a tuple with the InstallationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationDate

`func (o *Asset) SetInstallationDate(v time.Time)`

SetInstallationDate sets InstallationDate field to given value.

### HasInstallationDate

`func (o *Asset) HasInstallationDate() bool`

HasInstallationDate returns a boolean if a field has been set.

### GetCustomerReferenceNumber

`func (o *Asset) GetCustomerReferenceNumber() string`

GetCustomerReferenceNumber returns the CustomerReferenceNumber field if non-nil, zero value otherwise.

### GetCustomerReferenceNumberOk

`func (o *Asset) GetCustomerReferenceNumberOk() (*string, bool)`

GetCustomerReferenceNumberOk returns a tuple with the CustomerReferenceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceNumber

`func (o *Asset) SetCustomerReferenceNumber(v string)`

SetCustomerReferenceNumber sets CustomerReferenceNumber field to given value.

### HasCustomerReferenceNumber

`func (o *Asset) HasCustomerReferenceNumber() bool`

HasCustomerReferenceNumber returns a boolean if a field has been set.

### GetStatus

`func (o *Asset) GetStatus() AssetsSummaryStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Asset) GetStatusOk() (*AssetsSummaryStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Asset) SetStatus(v AssetsSummaryStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Asset) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProductDetails

`func (o *Asset) GetProductDetails() []AssetsProperty`

GetProductDetails returns the ProductDetails field if non-nil, zero value otherwise.

### GetProductDetailsOk

`func (o *Asset) GetProductDetailsOk() (*[]AssetsProperty, bool)`

GetProductDetailsOk returns a tuple with the ProductDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDetails

`func (o *Asset) SetProductDetails(v []AssetsProperty)`

SetProductDetails sets ProductDetails field to given value.

### HasProductDetails

`func (o *Asset) HasProductDetails() bool`

HasProductDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


