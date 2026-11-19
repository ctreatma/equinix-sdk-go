# ChangeData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Service** | [**ChangeDataService**](ChangeDataService.md) |  | 
**Request** | **string** |  | 

## Methods

### NewChangeData

`func NewChangeData(service ChangeDataService, request string, ) *ChangeData`

NewChangeData instantiates a new ChangeData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeDataWithDefaults

`func NewChangeDataWithDefaults() *ChangeData`

NewChangeDataWithDefaults instantiates a new ChangeData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetService

`func (o *ChangeData) GetService() ChangeDataService`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *ChangeData) GetServiceOk() (*ChangeDataService, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *ChangeData) SetService(v ChangeDataService)`

SetService sets Service field to given value.


### GetRequest

`func (o *ChangeData) GetRequest() string`

GetRequest returns the Request field if non-nil, zero value otherwise.

### GetRequestOk

`func (o *ChangeData) GetRequestOk() (*string, bool)`

GetRequestOk returns a tuple with the Request field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequest

`func (o *ChangeData) SetRequest(v string)`

SetRequest sets Request field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


