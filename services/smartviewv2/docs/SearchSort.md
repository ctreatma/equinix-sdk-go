# SearchSort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Direction** | Pointer to [**SearchSortDirection**](SearchSortDirection.md) |  | [optional] 
**Property** | **string** | Property used for sorting the data. | 

## Methods

### NewSearchSort

`func NewSearchSort(property string, ) *SearchSort`

NewSearchSort instantiates a new SearchSort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchSortWithDefaults

`func NewSearchSortWithDefaults() *SearchSort`

NewSearchSortWithDefaults instantiates a new SearchSort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDirection

`func (o *SearchSort) GetDirection() SearchSortDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *SearchSort) GetDirectionOk() (*SearchSortDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *SearchSort) SetDirection(v SearchSortDirection)`

SetDirection sets Direction field to given value.

### HasDirection

`func (o *SearchSort) HasDirection() bool`

HasDirection returns a boolean if a field has been set.

### GetProperty

`func (o *SearchSort) GetProperty() string`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *SearchSort) GetPropertyOk() (*string, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *SearchSort) SetProperty(v string)`

SetProperty sets Property field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


