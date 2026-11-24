# ContactsRequestDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**ContactsRequestDetailsType**](ContactsRequestDetailsType.md) |  | 
**Value** | **string** | Value of communications type. | 

## Methods

### NewContactsRequestDetails

`func NewContactsRequestDetails(type_ ContactsRequestDetailsType, value string, ) *ContactsRequestDetails`

NewContactsRequestDetails instantiates a new ContactsRequestDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsRequestDetailsWithDefaults

`func NewContactsRequestDetailsWithDefaults() *ContactsRequestDetails`

NewContactsRequestDetailsWithDefaults instantiates a new ContactsRequestDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContactsRequestDetails) GetType() ContactsRequestDetailsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactsRequestDetails) GetTypeOk() (*ContactsRequestDetailsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactsRequestDetails) SetType(v ContactsRequestDetailsType)`

SetType sets Type field to given value.


### GetValue

`func (o *ContactsRequestDetails) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ContactsRequestDetails) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ContactsRequestDetails) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


