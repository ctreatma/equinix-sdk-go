# EmailDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | Pointer to **string** | Identifier of the order/case the email is associated with. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Date and time the email was created. | [optional] 
**Subject** | Pointer to **string** | Subject of the email. | [optional] 
**EmailContent** | Pointer to **string** | HTML Body content of the email. | [optional] 
**FromAddress** | Pointer to **string** | Email address of the email author. | [optional] 
**ToAddress** | Pointer to **string** | Semi-colon separated email address(es) of the email recipients. | [optional] 
**CcAddress** | Pointer to **string** | Semi-colon separated email address(es) of the email CC recipients. | [optional] 

## Methods

### NewEmailDetailsResponse

`func NewEmailDetailsResponse() *EmailDetailsResponse`

NewEmailDetailsResponse instantiates a new EmailDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailDetailsResponseWithDefaults

`func NewEmailDetailsResponseWithDefaults() *EmailDetailsResponse`

NewEmailDetailsResponseWithDefaults instantiates a new EmailDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *EmailDetailsResponse) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *EmailDetailsResponse) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *EmailDetailsResponse) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *EmailDetailsResponse) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *EmailDetailsResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *EmailDetailsResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *EmailDetailsResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *EmailDetailsResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetSubject

`func (o *EmailDetailsResponse) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *EmailDetailsResponse) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *EmailDetailsResponse) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *EmailDetailsResponse) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetEmailContent

`func (o *EmailDetailsResponse) GetEmailContent() string`

GetEmailContent returns the EmailContent field if non-nil, zero value otherwise.

### GetEmailContentOk

`func (o *EmailDetailsResponse) GetEmailContentOk() (*string, bool)`

GetEmailContentOk returns a tuple with the EmailContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailContent

`func (o *EmailDetailsResponse) SetEmailContent(v string)`

SetEmailContent sets EmailContent field to given value.

### HasEmailContent

`func (o *EmailDetailsResponse) HasEmailContent() bool`

HasEmailContent returns a boolean if a field has been set.

### GetFromAddress

`func (o *EmailDetailsResponse) GetFromAddress() string`

GetFromAddress returns the FromAddress field if non-nil, zero value otherwise.

### GetFromAddressOk

`func (o *EmailDetailsResponse) GetFromAddressOk() (*string, bool)`

GetFromAddressOk returns a tuple with the FromAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromAddress

`func (o *EmailDetailsResponse) SetFromAddress(v string)`

SetFromAddress sets FromAddress field to given value.

### HasFromAddress

`func (o *EmailDetailsResponse) HasFromAddress() bool`

HasFromAddress returns a boolean if a field has been set.

### GetToAddress

`func (o *EmailDetailsResponse) GetToAddress() string`

GetToAddress returns the ToAddress field if non-nil, zero value otherwise.

### GetToAddressOk

`func (o *EmailDetailsResponse) GetToAddressOk() (*string, bool)`

GetToAddressOk returns a tuple with the ToAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToAddress

`func (o *EmailDetailsResponse) SetToAddress(v string)`

SetToAddress sets ToAddress field to given value.

### HasToAddress

`func (o *EmailDetailsResponse) HasToAddress() bool`

HasToAddress returns a boolean if a field has been set.

### GetCcAddress

`func (o *EmailDetailsResponse) GetCcAddress() string`

GetCcAddress returns the CcAddress field if non-nil, zero value otherwise.

### GetCcAddressOk

`func (o *EmailDetailsResponse) GetCcAddressOk() (*string, bool)`

GetCcAddressOk returns a tuple with the CcAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCcAddress

`func (o *EmailDetailsResponse) SetCcAddress(v string)`

SetCcAddress sets CcAddress field to given value.

### HasCcAddress

`func (o *EmailDetailsResponse) HasCcAddress() bool`

HasCcAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


