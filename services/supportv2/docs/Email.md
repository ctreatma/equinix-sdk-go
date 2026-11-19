# Email

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Identifier of the email. | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | Date and time the email was created. | [optional] 
**Subject** | Pointer to **string** | Subject of the email. | [optional] 
**AuthorName** | Pointer to **string** | Name of the email author. | [optional] 
**FromAddress** | Pointer to **string** | Email address of the email author. | [optional] 
**ToAddress** | Pointer to **string** | Email address of the email recipient. | [optional] 

## Methods

### NewEmail

`func NewEmail() *Email`

NewEmail instantiates a new Email object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailWithDefaults

`func NewEmailWithDefaults() *Email`

NewEmailWithDefaults instantiates a new Email object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Email) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Email) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Email) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Email) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *Email) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *Email) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *Email) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *Email) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetSubject

`func (o *Email) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *Email) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *Email) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *Email) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### GetAuthorName

`func (o *Email) GetAuthorName() string`

GetAuthorName returns the AuthorName field if non-nil, zero value otherwise.

### GetAuthorNameOk

`func (o *Email) GetAuthorNameOk() (*string, bool)`

GetAuthorNameOk returns a tuple with the AuthorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorName

`func (o *Email) SetAuthorName(v string)`

SetAuthorName sets AuthorName field to given value.

### HasAuthorName

`func (o *Email) HasAuthorName() bool`

HasAuthorName returns a boolean if a field has been set.

### GetFromAddress

`func (o *Email) GetFromAddress() string`

GetFromAddress returns the FromAddress field if non-nil, zero value otherwise.

### GetFromAddressOk

`func (o *Email) GetFromAddressOk() (*string, bool)`

GetFromAddressOk returns a tuple with the FromAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromAddress

`func (o *Email) SetFromAddress(v string)`

SetFromAddress sets FromAddress field to given value.

### HasFromAddress

`func (o *Email) HasFromAddress() bool`

HasFromAddress returns a boolean if a field has been set.

### GetToAddress

`func (o *Email) GetToAddress() string`

GetToAddress returns the ToAddress field if non-nil, zero value otherwise.

### GetToAddressOk

`func (o *Email) GetToAddressOk() (*string, bool)`

GetToAddressOk returns a tuple with the ToAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToAddress

`func (o *Email) SetToAddress(v string)`

SetToAddress sets ToAddress field to given value.

### HasToAddress

`func (o *Email) HasToAddress() bool`

HasToAddress returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


