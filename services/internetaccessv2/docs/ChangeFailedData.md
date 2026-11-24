# ChangeFailedData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Service** | [**ChangeDataService**](ChangeDataService.md) |  | 
**Request** | **string** |  | 
**Errors** | [**[]Error**](Error.md) | List of Error Message | 

## Methods

### NewChangeFailedData

`func NewChangeFailedData(service ChangeDataService, request string, errors []Error, ) *ChangeFailedData`

NewChangeFailedData instantiates a new ChangeFailedData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeFailedDataWithDefaults

`func NewChangeFailedDataWithDefaults() *ChangeFailedData`

NewChangeFailedDataWithDefaults instantiates a new ChangeFailedData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetService

`func (o *ChangeFailedData) GetService() ChangeDataService`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *ChangeFailedData) GetServiceOk() (*ChangeDataService, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *ChangeFailedData) SetService(v ChangeDataService)`

SetService sets Service field to given value.


### GetRequest

`func (o *ChangeFailedData) GetRequest() string`

GetRequest returns the Request field if non-nil, zero value otherwise.

### GetRequestOk

`func (o *ChangeFailedData) GetRequestOk() (*string, bool)`

GetRequestOk returns a tuple with the Request field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequest

`func (o *ChangeFailedData) SetRequest(v string)`

SetRequest sets Request field to given value.


### GetErrors

`func (o *ChangeFailedData) GetErrors() []Error`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ChangeFailedData) GetErrorsOk() (*[]Error, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ChangeFailedData) SetErrors(v []Error)`

SetErrors sets Errors field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


