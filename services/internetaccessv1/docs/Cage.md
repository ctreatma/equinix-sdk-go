# Cage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SpaceId** | **string** |  | 
**Number** | **string** |  | 
**CabinetsCount** | **int32** |  | 
**Location** | [**Location**](Location.md) |  | 
**Account** | [**SecureCageAccount**](SecureCageAccount.md) |  | 

## Methods

### NewCage

`func NewCage(spaceId string, number string, cabinetsCount int32, location Location, account SecureCageAccount, ) *Cage`

NewCage instantiates a new Cage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCageWithDefaults

`func NewCageWithDefaults() *Cage`

NewCageWithDefaults instantiates a new Cage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSpaceId

`func (o *Cage) GetSpaceId() string`

GetSpaceId returns the SpaceId field if non-nil, zero value otherwise.

### GetSpaceIdOk

`func (o *Cage) GetSpaceIdOk() (*string, bool)`

GetSpaceIdOk returns a tuple with the SpaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpaceId

`func (o *Cage) SetSpaceId(v string)`

SetSpaceId sets SpaceId field to given value.


### GetNumber

`func (o *Cage) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *Cage) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *Cage) SetNumber(v string)`

SetNumber sets Number field to given value.


### GetCabinetsCount

`func (o *Cage) GetCabinetsCount() int32`

GetCabinetsCount returns the CabinetsCount field if non-nil, zero value otherwise.

### GetCabinetsCountOk

`func (o *Cage) GetCabinetsCountOk() (*int32, bool)`

GetCabinetsCountOk returns a tuple with the CabinetsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCabinetsCount

`func (o *Cage) SetCabinetsCount(v int32)`

SetCabinetsCount sets CabinetsCount field to given value.


### GetLocation

`func (o *Cage) GetLocation() Location`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *Cage) GetLocationOk() (*Location, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *Cage) SetLocation(v Location)`

SetLocation sets Location field to given value.


### GetAccount

`func (o *Cage) GetAccount() SecureCageAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *Cage) GetAccountOk() (*SecureCageAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *Cage) SetAccount(v SecureCageAccount)`

SetAccount sets Account field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


