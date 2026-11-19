# OperationalUnit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Address** | [**Address**](Address.md) |  | 
**Location** | [**OperationalUnitLocation**](OperationalUnitLocation.md) |  | 

## Methods

### NewOperationalUnit

`func NewOperationalUnit(name string, address Address, location OperationalUnitLocation, ) *OperationalUnit`

NewOperationalUnit instantiates a new OperationalUnit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationalUnitWithDefaults

`func NewOperationalUnitWithDefaults() *OperationalUnit`

NewOperationalUnitWithDefaults instantiates a new OperationalUnit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *OperationalUnit) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OperationalUnit) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OperationalUnit) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *OperationalUnit) GetAddress() Address`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *OperationalUnit) GetAddressOk() (*Address, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *OperationalUnit) SetAddress(v Address)`

SetAddress sets Address field to given value.


### GetLocation

`func (o *OperationalUnit) GetLocation() OperationalUnitLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *OperationalUnit) GetLocationOk() (*OperationalUnitLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *OperationalUnit) SetLocation(v OperationalUnitLocation)`

SetLocation sets Location field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


