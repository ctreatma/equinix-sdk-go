# NonRegisteredUserVisitor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | **string** | First name of the visitor. | 
**LastName** | **string** | Last name of the visitor. | 
**CompanyName** | **string** | Name of the company. | 
**Details** | Pointer to [**[]VisitorContactsRequestDetails**](VisitorContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | [optional] 

## Methods

### NewNonRegisteredUserVisitor

`func NewNonRegisteredUserVisitor(firstName string, lastName string, companyName string, ) *NonRegisteredUserVisitor`

NewNonRegisteredUserVisitor instantiates a new NonRegisteredUserVisitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNonRegisteredUserVisitorWithDefaults

`func NewNonRegisteredUserVisitorWithDefaults() *NonRegisteredUserVisitor`

NewNonRegisteredUserVisitorWithDefaults instantiates a new NonRegisteredUserVisitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *NonRegisteredUserVisitor) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *NonRegisteredUserVisitor) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *NonRegisteredUserVisitor) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *NonRegisteredUserVisitor) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *NonRegisteredUserVisitor) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *NonRegisteredUserVisitor) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetCompanyName

`func (o *NonRegisteredUserVisitor) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *NonRegisteredUserVisitor) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *NonRegisteredUserVisitor) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.


### GetDetails

`func (o *NonRegisteredUserVisitor) GetDetails() []VisitorContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *NonRegisteredUserVisitor) GetDetailsOk() (*[]VisitorContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *NonRegisteredUserVisitor) SetDetails(v []VisitorContactsRequestDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *NonRegisteredUserVisitor) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


