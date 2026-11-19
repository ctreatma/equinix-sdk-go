# Sort

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Direction** | [**SortDirection**](SortDirection.md) |  | 
**Property** | [**SortProperty**](SortProperty.md) |  | 

## Methods

### NewSort

`func NewSort(direction SortDirection, property SortProperty, ) *Sort`

NewSort instantiates a new Sort object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSortWithDefaults

`func NewSortWithDefaults() *Sort`

NewSortWithDefaults instantiates a new Sort object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDirection

`func (o *Sort) GetDirection() SortDirection`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *Sort) GetDirectionOk() (*SortDirection, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *Sort) SetDirection(v SortDirection)`

SetDirection sets Direction field to given value.


### GetProperty

`func (o *Sort) GetProperty() SortProperty`

GetProperty returns the Property field if non-nil, zero value otherwise.

### GetPropertyOk

`func (o *Sort) GetPropertyOk() (*SortProperty, bool)`

GetPropertyOk returns a tuple with the Property field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperty

`func (o *Sort) SetProperty(v SortProperty)`

SetProperty sets Property field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


