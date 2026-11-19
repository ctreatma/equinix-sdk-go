# ChangeRejectedData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Service** | [**ChangeDataService**](ChangeDataService.md) |  | 
**Request** | **string** |  | 
**RejectionReason** | **string** |  | 

## Methods

### NewChangeRejectedData

`func NewChangeRejectedData(service ChangeDataService, request string, rejectionReason string, ) *ChangeRejectedData`

NewChangeRejectedData instantiates a new ChangeRejectedData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeRejectedDataWithDefaults

`func NewChangeRejectedDataWithDefaults() *ChangeRejectedData`

NewChangeRejectedDataWithDefaults instantiates a new ChangeRejectedData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetService

`func (o *ChangeRejectedData) GetService() ChangeDataService`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *ChangeRejectedData) GetServiceOk() (*ChangeDataService, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *ChangeRejectedData) SetService(v ChangeDataService)`

SetService sets Service field to given value.


### GetRequest

`func (o *ChangeRejectedData) GetRequest() string`

GetRequest returns the Request field if non-nil, zero value otherwise.

### GetRequestOk

`func (o *ChangeRejectedData) GetRequestOk() (*string, bool)`

GetRequestOk returns a tuple with the Request field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequest

`func (o *ChangeRejectedData) SetRequest(v string)`

SetRequest sets Request field to given value.


### GetRejectionReason

`func (o *ChangeRejectedData) GetRejectionReason() string`

GetRejectionReason returns the RejectionReason field if non-nil, zero value otherwise.

### GetRejectionReasonOk

`func (o *ChangeRejectedData) GetRejectionReasonOk() (*string, bool)`

GetRejectionReasonOk returns a tuple with the RejectionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejectionReason

`func (o *ChangeRejectedData) SetRejectionReason(v string)`

SetRejectionReason sets RejectionReason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


