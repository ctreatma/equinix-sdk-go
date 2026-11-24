# TermsAndConditions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Version** | **string** |  | 
**Location** | [**TermsAndConditionsLocation**](TermsAndConditionsLocation.md) |  | 
**Account** | [**TermsAndConditionsAccount**](TermsAndConditionsAccount.md) |  | 
**ConnectivitySource** | [**TermsAndConditionsConnectivitySource**](TermsAndConditionsConnectivitySource.md) |  | 
**Type** | [**TermsAndConditionsType**](TermsAndConditionsType.md) |  | [default to TERMSANDCONDITIONSTYPE_TERMS_AND_CONDITIONS]
**Product** | [**GetTermsAndConditionsProductParameter**](GetTermsAndConditionsProductParameter.md) |  | 
**Language** | **string** |  | 

## Methods

### NewTermsAndConditions

`func NewTermsAndConditions(text string, version string, location TermsAndConditionsLocation, account TermsAndConditionsAccount, connectivitySource TermsAndConditionsConnectivitySource, type_ TermsAndConditionsType, product GetTermsAndConditionsProductParameter, language string, ) *TermsAndConditions`

NewTermsAndConditions instantiates a new TermsAndConditions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTermsAndConditionsWithDefaults

`func NewTermsAndConditionsWithDefaults() *TermsAndConditions`

NewTermsAndConditionsWithDefaults instantiates a new TermsAndConditions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *TermsAndConditions) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TermsAndConditions) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TermsAndConditions) SetText(v string)`

SetText sets Text field to given value.


### GetVersion

`func (o *TermsAndConditions) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *TermsAndConditions) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *TermsAndConditions) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetLocation

`func (o *TermsAndConditions) GetLocation() TermsAndConditionsLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *TermsAndConditions) GetLocationOk() (*TermsAndConditionsLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *TermsAndConditions) SetLocation(v TermsAndConditionsLocation)`

SetLocation sets Location field to given value.


### GetAccount

`func (o *TermsAndConditions) GetAccount() TermsAndConditionsAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *TermsAndConditions) GetAccountOk() (*TermsAndConditionsAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *TermsAndConditions) SetAccount(v TermsAndConditionsAccount)`

SetAccount sets Account field to given value.


### GetConnectivitySource

`func (o *TermsAndConditions) GetConnectivitySource() TermsAndConditionsConnectivitySource`

GetConnectivitySource returns the ConnectivitySource field if non-nil, zero value otherwise.

### GetConnectivitySourceOk

`func (o *TermsAndConditions) GetConnectivitySourceOk() (*TermsAndConditionsConnectivitySource, bool)`

GetConnectivitySourceOk returns a tuple with the ConnectivitySource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectivitySource

`func (o *TermsAndConditions) SetConnectivitySource(v TermsAndConditionsConnectivitySource)`

SetConnectivitySource sets ConnectivitySource field to given value.


### GetType

`func (o *TermsAndConditions) GetType() TermsAndConditionsType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TermsAndConditions) GetTypeOk() (*TermsAndConditionsType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TermsAndConditions) SetType(v TermsAndConditionsType)`

SetType sets Type field to given value.


### GetProduct

`func (o *TermsAndConditions) GetProduct() GetTermsAndConditionsProductParameter`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *TermsAndConditions) GetProductOk() (*GetTermsAndConditionsProductParameter, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *TermsAndConditions) SetProduct(v GetTermsAndConditionsProductParameter)`

SetProduct sets Product field to given value.


### GetLanguage

`func (o *TermsAndConditions) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *TermsAndConditions) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *TermsAndConditions) SetLanguage(v string)`

SetLanguage sets Language field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


