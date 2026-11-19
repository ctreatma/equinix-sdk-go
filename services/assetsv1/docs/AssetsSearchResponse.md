# AssetsSearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AssetsSummary**](AssetsSummary.md) |  | [optional] 
**Page** | Pointer to [**PageInfo**](PageInfo.md) |  | [optional] 
**Links** | Pointer to [**Links**](Links.md) |  | [optional] 

## Methods

### NewAssetsSearchResponse

`func NewAssetsSearchResponse() *AssetsSearchResponse`

NewAssetsSearchResponse instantiates a new AssetsSearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetsSearchResponseWithDefaults

`func NewAssetsSearchResponseWithDefaults() *AssetsSearchResponse`

NewAssetsSearchResponseWithDefaults instantiates a new AssetsSearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AssetsSearchResponse) GetData() []AssetsSummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AssetsSearchResponse) GetDataOk() (*[]AssetsSummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AssetsSearchResponse) SetData(v []AssetsSummary)`

SetData sets Data field to given value.

### HasData

`func (o *AssetsSearchResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPage

`func (o *AssetsSearchResponse) GetPage() PageInfo`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *AssetsSearchResponse) GetPageOk() (*PageInfo, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *AssetsSearchResponse) SetPage(v PageInfo)`

SetPage sets Page field to given value.

### HasPage

`func (o *AssetsSearchResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetLinks

`func (o *AssetsSearchResponse) GetLinks() Links`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *AssetsSearchResponse) GetLinksOk() (*Links, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *AssetsSearchResponse) SetLinks(v Links)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *AssetsSearchResponse) HasLinks() bool`

HasLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


