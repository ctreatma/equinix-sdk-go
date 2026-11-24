# WorkvisitAdditionalDetailsVisitorsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RegisteredUsers** | **[]string** | Username of a registered user. | 
**FirstName** | **string** | First name of the visitor. | 
**LastName** | **string** | Last name of the visitor. | 
**CompanyName** | **string** | Name of the company. | 
**Details** | Pointer to [**[]VisitorContactsRequestDetails**](VisitorContactsRequestDetails.md) | Reference of the related party, could be a party reference or a party role reference | [optional] 

## Methods

### NewWorkvisitAdditionalDetailsVisitorsInner

`func NewWorkvisitAdditionalDetailsVisitorsInner(registeredUsers []string, firstName string, lastName string, companyName string, ) *WorkvisitAdditionalDetailsVisitorsInner`

NewWorkvisitAdditionalDetailsVisitorsInner instantiates a new WorkvisitAdditionalDetailsVisitorsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkvisitAdditionalDetailsVisitorsInnerWithDefaults

`func NewWorkvisitAdditionalDetailsVisitorsInnerWithDefaults() *WorkvisitAdditionalDetailsVisitorsInner`

NewWorkvisitAdditionalDetailsVisitorsInnerWithDefaults instantiates a new WorkvisitAdditionalDetailsVisitorsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRegisteredUsers

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetRegisteredUsers() []string`

GetRegisteredUsers returns the RegisteredUsers field if non-nil, zero value otherwise.

### GetRegisteredUsersOk

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetRegisteredUsersOk() (*[]string, bool)`

GetRegisteredUsersOk returns a tuple with the RegisteredUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisteredUsers

`func (o *WorkvisitAdditionalDetailsVisitorsInner) SetRegisteredUsers(v []string)`

SetRegisteredUsers sets RegisteredUsers field to given value.


### GetFirstName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetCompanyName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *WorkvisitAdditionalDetailsVisitorsInner) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.


### GetDetails

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetDetails() []VisitorContactsRequestDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *WorkvisitAdditionalDetailsVisitorsInner) GetDetailsOk() (*[]VisitorContactsRequestDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *WorkvisitAdditionalDetailsVisitorsInner) SetDetails(v []VisitorContactsRequestDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *WorkvisitAdditionalDetailsVisitorsInner) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


