# CreateAlertConfigurationCommandAssets

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CAGE** | Pointer to [**[]PowerAlertConfigurationAsset**](PowerAlertConfigurationAsset.md) | List of cage assets to monitor | [optional] 
**CABINET** | Pointer to [**[]PowerAlertConfigurationAsset**](PowerAlertConfigurationAsset.md) | List of cabinet assets to monitor | [optional] 
**CIRCUIT** | Pointer to [**[]PowerAlertConfigurationAsset**](PowerAlertConfigurationAsset.md) | List of circuit assets to monitor | [optional] 

## Methods

### NewCreateAlertConfigurationCommandAssets

`func NewCreateAlertConfigurationCommandAssets() *CreateAlertConfigurationCommandAssets`

NewCreateAlertConfigurationCommandAssets instantiates a new CreateAlertConfigurationCommandAssets object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlertConfigurationCommandAssetsWithDefaults

`func NewCreateAlertConfigurationCommandAssetsWithDefaults() *CreateAlertConfigurationCommandAssets`

NewCreateAlertConfigurationCommandAssetsWithDefaults instantiates a new CreateAlertConfigurationCommandAssets object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCAGE

`func (o *CreateAlertConfigurationCommandAssets) GetCAGE() []PowerAlertConfigurationAsset`

GetCAGE returns the CAGE field if non-nil, zero value otherwise.

### GetCAGEOk

`func (o *CreateAlertConfigurationCommandAssets) GetCAGEOk() (*[]PowerAlertConfigurationAsset, bool)`

GetCAGEOk returns a tuple with the CAGE field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCAGE

`func (o *CreateAlertConfigurationCommandAssets) SetCAGE(v []PowerAlertConfigurationAsset)`

SetCAGE sets CAGE field to given value.

### HasCAGE

`func (o *CreateAlertConfigurationCommandAssets) HasCAGE() bool`

HasCAGE returns a boolean if a field has been set.

### GetCABINET

`func (o *CreateAlertConfigurationCommandAssets) GetCABINET() []PowerAlertConfigurationAsset`

GetCABINET returns the CABINET field if non-nil, zero value otherwise.

### GetCABINETOk

`func (o *CreateAlertConfigurationCommandAssets) GetCABINETOk() (*[]PowerAlertConfigurationAsset, bool)`

GetCABINETOk returns a tuple with the CABINET field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCABINET

`func (o *CreateAlertConfigurationCommandAssets) SetCABINET(v []PowerAlertConfigurationAsset)`

SetCABINET sets CABINET field to given value.

### HasCABINET

`func (o *CreateAlertConfigurationCommandAssets) HasCABINET() bool`

HasCABINET returns a boolean if a field has been set.

### GetCIRCUIT

`func (o *CreateAlertConfigurationCommandAssets) GetCIRCUIT() []PowerAlertConfigurationAsset`

GetCIRCUIT returns the CIRCUIT field if non-nil, zero value otherwise.

### GetCIRCUITOk

`func (o *CreateAlertConfigurationCommandAssets) GetCIRCUITOk() (*[]PowerAlertConfigurationAsset, bool)`

GetCIRCUITOk returns a tuple with the CIRCUIT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCIRCUIT

`func (o *CreateAlertConfigurationCommandAssets) SetCIRCUIT(v []PowerAlertConfigurationAsset)`

SetCIRCUIT sets CIRCUIT field to given value.

### HasCIRCUIT

`func (o *CreateAlertConfigurationCommandAssets) HasCIRCUIT() bool`

HasCIRCUIT returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


