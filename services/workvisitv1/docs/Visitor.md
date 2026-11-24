# Visitor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserName** | Pointer to **string** | Equinix registered username. when username passed other attributes for vistor model will be ignored. | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**Company** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** | Visitor Email | [optional] 
**MobilePhoneCountryCode** | Pointer to **string** | Mobile country code of the visitor | [optional] 
**MobilePhone** | Pointer to **string** | Phone number allowed special characters are -.() and spaces. First character should either be numeric digit or &#39;(&#39;. Last character should only be a numeric digit. | [optional] 

## Methods

### NewVisitor

`func NewVisitor() *Visitor`

NewVisitor instantiates a new Visitor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVisitorWithDefaults

`func NewVisitorWithDefaults() *Visitor`

NewVisitorWithDefaults instantiates a new Visitor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserName

`func (o *Visitor) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *Visitor) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *Visitor) SetUserName(v string)`

SetUserName sets UserName field to given value.

### HasUserName

`func (o *Visitor) HasUserName() bool`

HasUserName returns a boolean if a field has been set.

### GetFirstName

`func (o *Visitor) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *Visitor) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *Visitor) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *Visitor) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *Visitor) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *Visitor) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *Visitor) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *Visitor) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetCompany

`func (o *Visitor) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *Visitor) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *Visitor) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *Visitor) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### GetEmail

`func (o *Visitor) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Visitor) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Visitor) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Visitor) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetMobilePhoneCountryCode

`func (o *Visitor) GetMobilePhoneCountryCode() string`

GetMobilePhoneCountryCode returns the MobilePhoneCountryCode field if non-nil, zero value otherwise.

### GetMobilePhoneCountryCodeOk

`func (o *Visitor) GetMobilePhoneCountryCodeOk() (*string, bool)`

GetMobilePhoneCountryCodeOk returns a tuple with the MobilePhoneCountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhoneCountryCode

`func (o *Visitor) SetMobilePhoneCountryCode(v string)`

SetMobilePhoneCountryCode sets MobilePhoneCountryCode field to given value.

### HasMobilePhoneCountryCode

`func (o *Visitor) HasMobilePhoneCountryCode() bool`

HasMobilePhoneCountryCode returns a boolean if a field has been set.

### GetMobilePhone

`func (o *Visitor) GetMobilePhone() string`

GetMobilePhone returns the MobilePhone field if non-nil, zero value otherwise.

### GetMobilePhoneOk

`func (o *Visitor) GetMobilePhoneOk() (*string, bool)`

GetMobilePhoneOk returns a tuple with the MobilePhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobilePhone

`func (o *Visitor) SetMobilePhone(v string)`

SetMobilePhone sets MobilePhone field to given value.

### HasMobilePhone

`func (o *Visitor) HasMobilePhone() bool`

HasMobilePhone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


