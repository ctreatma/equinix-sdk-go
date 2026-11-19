# AssetsSearchRequestFilterDateRange

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromDate** | **time.Time** | Start date to filter the installed date. | 
**ToDate** | **time.Time** | End date to filter the installed date. | 

## Methods

### NewAssetsSearchRequestFilterDateRange

`func NewAssetsSearchRequestFilterDateRange(fromDate time.Time, toDate time.Time, ) *AssetsSearchRequestFilterDateRange`

NewAssetsSearchRequestFilterDateRange instantiates a new AssetsSearchRequestFilterDateRange object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetsSearchRequestFilterDateRangeWithDefaults

`func NewAssetsSearchRequestFilterDateRangeWithDefaults() *AssetsSearchRequestFilterDateRange`

NewAssetsSearchRequestFilterDateRangeWithDefaults instantiates a new AssetsSearchRequestFilterDateRange object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromDate

`func (o *AssetsSearchRequestFilterDateRange) GetFromDate() time.Time`

GetFromDate returns the FromDate field if non-nil, zero value otherwise.

### GetFromDateOk

`func (o *AssetsSearchRequestFilterDateRange) GetFromDateOk() (*time.Time, bool)`

GetFromDateOk returns a tuple with the FromDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromDate

`func (o *AssetsSearchRequestFilterDateRange) SetFromDate(v time.Time)`

SetFromDate sets FromDate field to given value.


### GetToDate

`func (o *AssetsSearchRequestFilterDateRange) GetToDate() time.Time`

GetToDate returns the ToDate field if non-nil, zero value otherwise.

### GetToDateOk

`func (o *AssetsSearchRequestFilterDateRange) GetToDateOk() (*time.Time, bool)`

GetToDateOk returns a tuple with the ToDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToDate

`func (o *AssetsSearchRequestFilterDateRange) SetToDate(v time.Time)`

SetToDate sets ToDate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


