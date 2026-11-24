# ShipmentAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CarrierAccountNumber** | Pointer to **string** | Shipment Carrier account number | [optional] 
**ShipToName** | Pointer to **string** | Shipment receiver name | [optional] 
**AddressLine1** | Pointer to **string** | Address line 1 | [optional] 
**AddressLine2** | Pointer to **string** | Address line 2 | [optional] 
**City** | Pointer to **string** | City name. | [optional] 
**State** | Pointer to **string** | State of the city. | [optional] 
**CountryCode** | Pointer to [**ShipmentAddressCountryCode**](ShipmentAddressCountryCode.md) |  | [optional] 
**ZipCode** | Pointer to **string** | Postal address | [optional] 
**PhoneNumber** | Pointer to **string** | Ship To contact phone number | [optional] 

## Methods

### NewShipmentAddress

`func NewShipmentAddress() *ShipmentAddress`

NewShipmentAddress instantiates a new ShipmentAddress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShipmentAddressWithDefaults

`func NewShipmentAddressWithDefaults() *ShipmentAddress`

NewShipmentAddressWithDefaults instantiates a new ShipmentAddress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCarrierAccountNumber

`func (o *ShipmentAddress) GetCarrierAccountNumber() string`

GetCarrierAccountNumber returns the CarrierAccountNumber field if non-nil, zero value otherwise.

### GetCarrierAccountNumberOk

`func (o *ShipmentAddress) GetCarrierAccountNumberOk() (*string, bool)`

GetCarrierAccountNumberOk returns a tuple with the CarrierAccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarrierAccountNumber

`func (o *ShipmentAddress) SetCarrierAccountNumber(v string)`

SetCarrierAccountNumber sets CarrierAccountNumber field to given value.

### HasCarrierAccountNumber

`func (o *ShipmentAddress) HasCarrierAccountNumber() bool`

HasCarrierAccountNumber returns a boolean if a field has been set.

### GetShipToName

`func (o *ShipmentAddress) GetShipToName() string`

GetShipToName returns the ShipToName field if non-nil, zero value otherwise.

### GetShipToNameOk

`func (o *ShipmentAddress) GetShipToNameOk() (*string, bool)`

GetShipToNameOk returns a tuple with the ShipToName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipToName

`func (o *ShipmentAddress) SetShipToName(v string)`

SetShipToName sets ShipToName field to given value.

### HasShipToName

`func (o *ShipmentAddress) HasShipToName() bool`

HasShipToName returns a boolean if a field has been set.

### GetAddressLine1

`func (o *ShipmentAddress) GetAddressLine1() string`

GetAddressLine1 returns the AddressLine1 field if non-nil, zero value otherwise.

### GetAddressLine1Ok

`func (o *ShipmentAddress) GetAddressLine1Ok() (*string, bool)`

GetAddressLine1Ok returns a tuple with the AddressLine1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine1

`func (o *ShipmentAddress) SetAddressLine1(v string)`

SetAddressLine1 sets AddressLine1 field to given value.

### HasAddressLine1

`func (o *ShipmentAddress) HasAddressLine1() bool`

HasAddressLine1 returns a boolean if a field has been set.

### GetAddressLine2

`func (o *ShipmentAddress) GetAddressLine2() string`

GetAddressLine2 returns the AddressLine2 field if non-nil, zero value otherwise.

### GetAddressLine2Ok

`func (o *ShipmentAddress) GetAddressLine2Ok() (*string, bool)`

GetAddressLine2Ok returns a tuple with the AddressLine2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressLine2

`func (o *ShipmentAddress) SetAddressLine2(v string)`

SetAddressLine2 sets AddressLine2 field to given value.

### HasAddressLine2

`func (o *ShipmentAddress) HasAddressLine2() bool`

HasAddressLine2 returns a boolean if a field has been set.

### GetCity

`func (o *ShipmentAddress) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ShipmentAddress) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ShipmentAddress) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ShipmentAddress) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetState

`func (o *ShipmentAddress) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ShipmentAddress) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ShipmentAddress) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ShipmentAddress) HasState() bool`

HasState returns a boolean if a field has been set.

### GetCountryCode

`func (o *ShipmentAddress) GetCountryCode() ShipmentAddressCountryCode`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *ShipmentAddress) GetCountryCodeOk() (*ShipmentAddressCountryCode, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *ShipmentAddress) SetCountryCode(v ShipmentAddressCountryCode)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *ShipmentAddress) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetZipCode

`func (o *ShipmentAddress) GetZipCode() string`

GetZipCode returns the ZipCode field if non-nil, zero value otherwise.

### GetZipCodeOk

`func (o *ShipmentAddress) GetZipCodeOk() (*string, bool)`

GetZipCodeOk returns a tuple with the ZipCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZipCode

`func (o *ShipmentAddress) SetZipCode(v string)`

SetZipCode sets ZipCode field to given value.

### HasZipCode

`func (o *ShipmentAddress) HasZipCode() bool`

HasZipCode returns a boolean if a field has been set.

### GetPhoneNumber

`func (o *ShipmentAddress) GetPhoneNumber() string`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *ShipmentAddress) GetPhoneNumberOk() (*string, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *ShipmentAddress) SetPhoneNumber(v string)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *ShipmentAddress) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


