# Records

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Attachment**](Attachment.md) | List of records | 
**Page** | Pointer to [**Page**](Page.md) |  | [optional] 
**Links** | [**Links**](Links.md) |  | 

## Methods

### NewRecords

`func NewRecords(data []Attachment, links Links, ) *Records`

NewRecords instantiates a new Records object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordsWithDefaults

`func NewRecordsWithDefaults() *Records`

NewRecordsWithDefaults instantiates a new Records object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *Records) GetData() []Attachment`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Records) GetDataOk() (*[]Attachment, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Records) SetData(v []Attachment)`

SetData sets Data field to given value.


### GetPage

`func (o *Records) GetPage() Page`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *Records) GetPageOk() (*Page, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *Records) SetPage(v Page)`

SetPage sets Page field to given value.

### HasPage

`func (o *Records) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetLinks

`func (o *Records) GetLinks() Links`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *Records) GetLinksOk() (*Links, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *Records) SetLinks(v Links)`

SetLinks sets Links field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


