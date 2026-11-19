# Location

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ibx** | **string** | IBX data center identifier. | 
**Region** | [**LocationRegion**](LocationRegion.md) |  | 
**MetroName** | **string** | Metropolitan area name. | 
**MetroCode** | **string** | Metropolitan area identifier. | 
**CountryCode** | **string** | Country code. | 
**Address** | **string** | IBX data center address information. | 

## Methods

### NewLocation

`func NewLocation(ibx string, region LocationRegion, metroName string, metroCode string, countryCode string, address string, ) *Location`

NewLocation instantiates a new Location object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationWithDefaults

`func NewLocationWithDefaults() *Location`

NewLocationWithDefaults instantiates a new Location object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIbx

`func (o *Location) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *Location) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *Location) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetRegion

`func (o *Location) GetRegion() LocationRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *Location) GetRegionOk() (*LocationRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *Location) SetRegion(v LocationRegion)`

SetRegion sets Region field to given value.


### GetMetroName

`func (o *Location) GetMetroName() string`

GetMetroName returns the MetroName field if non-nil, zero value otherwise.

### GetMetroNameOk

`func (o *Location) GetMetroNameOk() (*string, bool)`

GetMetroNameOk returns a tuple with the MetroName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroName

`func (o *Location) SetMetroName(v string)`

SetMetroName sets MetroName field to given value.


### GetMetroCode

`func (o *Location) GetMetroCode() string`

GetMetroCode returns the MetroCode field if non-nil, zero value otherwise.

### GetMetroCodeOk

`func (o *Location) GetMetroCodeOk() (*string, bool)`

GetMetroCodeOk returns a tuple with the MetroCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroCode

`func (o *Location) SetMetroCode(v string)`

SetMetroCode sets MetroCode field to given value.


### GetCountryCode

`func (o *Location) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *Location) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *Location) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.


### GetAddress

`func (o *Location) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Location) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Location) SetAddress(v string)`

SetAddress sets Address field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


