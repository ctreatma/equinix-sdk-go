# SupportPlanResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]Supports**](Supports.md) |  | [optional] 
**Pagination** | Pointer to [**Pagination**](Pagination.md) |  | [optional] 

## Methods

### NewSupportPlanResponse

`func NewSupportPlanResponse() *SupportPlanResponse`

NewSupportPlanResponse instantiates a new SupportPlanResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupportPlanResponseWithDefaults

`func NewSupportPlanResponseWithDefaults() *SupportPlanResponse`

NewSupportPlanResponseWithDefaults instantiates a new SupportPlanResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SupportPlanResponse) GetData() []Supports`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SupportPlanResponse) GetDataOk() (*[]Supports, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SupportPlanResponse) SetData(v []Supports)`

SetData sets Data field to given value.

### HasData

`func (o *SupportPlanResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPagination

`func (o *SupportPlanResponse) GetPagination() Pagination`

GetPagination returns the Pagination field if non-nil, zero value otherwise.

### GetPaginationOk

`func (o *SupportPlanResponse) GetPaginationOk() (*Pagination, bool)`

GetPaginationOk returns a tuple with the Pagination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagination

`func (o *SupportPlanResponse) SetPagination(v Pagination)`

SetPagination sets Pagination field to given value.

### HasPagination

`func (o *SupportPlanResponse) HasPagination() bool`

HasPagination returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


