# AddressDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressLine1** | Pointer to **string** | Address line 1 | [optional] 
**AddressLine2** | Pointer to **string** | Address line 2 | [optional] 
**City** | Pointer to **string** | City name. | [optional] 
**State** | Pointer to **string** | State of the city. | [optional] 
**CountryCode** | Pointer to [**CountryCode**](CountryCode.md) |  | [optional] 
**ZipCode** | Pointer to **string** | Postal address | [optional] 

## Methods

### NewAddressDetails

`func NewAddressDetails() *AddressDetails`

NewAddressDetails instantiates a new AddressDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddressDetailsWithDefaults

`func NewAddressDetailsWithDefaults() *AddressDetails`

NewAddressDetailsWithDefaults instantiates a new AddressDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressLine1

`func (o *AddressDetails) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *AddressDetails) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *AddressDetails) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *AddressDetails) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### GetAddressLine2

`func (o *AddressDetails) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *AddressDetails) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *AddressDetails) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *AddressDetails) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### GetCity

`func (o *AddressDetails) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *AddressDetails) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *AddressDetails) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *AddressDetails) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *AddressDetails) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AddressDetails) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AddressDetails) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *AddressDetails) HasState() bool`

HasState returns a boolean if a field has been set.

### GetCountryCode

`func (o *AddressDetails) GetCountryCode() CountryCode`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *AddressDetails) GetCountryCodeOk() (*CountryCode, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *AddressDetails) SetCountryCode(v CountryCode)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *AddressDetails) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetZipCode

`func (o *AddressDetails) GetZipCode() string`

GetZipCode returns the ZipCode field if non-nil, zero value otherwise.

### GetZipCodeOk

`func (o *AddressDetails) GetZipCodeOk() (*string, bool)`

GetZipCodeOk returns a tuple with the ZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipCode

`func (o *AddressDetails) SetZipCode(v string)`

SetZipCode sets ZipCode field to given value.

### HasZipCode

`func (o *AddressDetails) HasZipCode() bool`

HasZipCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


