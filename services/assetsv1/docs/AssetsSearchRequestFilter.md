# AssetsSearchRequestFilter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ibxs** | Pointer to **[]string** | List of IBX to be filtered. | [optional] 
**Cages** | Pointer to **[]string** | List of cages to be filtered. | [optional] 
**ProductTypes** | Pointer to [**[]AssetsSearchRequestFilterProductTypesInner**](AssetsSearchRequestFilterProductTypesInner.md) | List of product types to be filtered. | [optional] 
**DateRange** | Pointer to [**AssetsSearchRequestFilterDateRange**](AssetsSearchRequestFilterDateRange.md) |  | [optional] 

## Methods

### NewAssetsSearchRequestFilter

`func NewAssetsSearchRequestFilter() *AssetsSearchRequestFilter`

NewAssetsSearchRequestFilter instantiates a new AssetsSearchRequestFilter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetsSearchRequestFilterWithDefaults

`func NewAssetsSearchRequestFilterWithDefaults() *AssetsSearchRequestFilter`

NewAssetsSearchRequestFilterWithDefaults instantiates a new AssetsSearchRequestFilter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbxs

`func (o *AssetsSearchRequestFilter) GetIbxs() []string`

GetIbxs returns the Ibxs field if non-nil, zero value otherwise.

### GetIbxsOk

`func (o *AssetsSearchRequestFilter) GetIbxsOk() (*[]string, bool)`

GetIbxsOk returns a tuple with the Ibxs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxs

`func (o *AssetsSearchRequestFilter) SetIbxs(v []string)`

SetIbxs sets Ibxs field to given value.

### HasIbxs

`func (o *AssetsSearchRequestFilter) HasIbxs() bool`

HasIbxs returns a boolean if a field has been set.

### GetCages

`func (o *AssetsSearchRequestFilter) GetCages() []string`

GetCages returns the Cages field if non-nil, zero value otherwise.

### GetCagesOk

`func (o *AssetsSearchRequestFilter) GetCagesOk() (*[]string, bool)`

GetCagesOk returns a tuple with the Cages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCages

`func (o *AssetsSearchRequestFilter) SetCages(v []string)`

SetCages sets Cages field to given value.

### HasCages

`func (o *AssetsSearchRequestFilter) HasCages() bool`

HasCages returns a boolean if a field has been set.

### GetProductTypes

`func (o *AssetsSearchRequestFilter) GetProductTypes() []AssetsSearchRequestFilterProductTypesInner`

GetProductTypes returns the ProductTypes field if non-nil, zero value otherwise.

### GetProductTypesOk

`func (o *AssetsSearchRequestFilter) GetProductTypesOk() (*[]AssetsSearchRequestFilterProductTypesInner, bool)`

GetProductTypesOk returns a tuple with the ProductTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductTypes

`func (o *AssetsSearchRequestFilter) SetProductTypes(v []AssetsSearchRequestFilterProductTypesInner)`

SetProductTypes sets ProductTypes field to given value.

### HasProductTypes

`func (o *AssetsSearchRequestFilter) HasProductTypes() bool`

HasProductTypes returns a boolean if a field has been set.

### GetDateRange

`func (o *AssetsSearchRequestFilter) GetDateRange() AssetsSearchRequestFilterDateRange`

GetDateRange returns the DateRange field if non-nil, zero value otherwise.

### GetDateRangeOk

`func (o *AssetsSearchRequestFilter) GetDateRangeOk() (*AssetsSearchRequestFilterDateRange, bool)`

GetDateRangeOk returns a tuple with the DateRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateRange

`func (o *AssetsSearchRequestFilter) SetDateRange(v AssetsSearchRequestFilterDateRange)`

SetDateRange sets DateRange field to given value.

### HasDateRange

`func (o *AssetsSearchRequestFilter) HasDateRange() bool`

HasDateRange returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


