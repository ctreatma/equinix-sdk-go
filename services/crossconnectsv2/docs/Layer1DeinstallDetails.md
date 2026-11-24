# Layer1DeinstallDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID of the cross connect you wish to de-install | 
**ProceedWithLiveTraffic** | Pointer to **bool** | When &#x60;true&#x60;, Equinix will proceed with deinstallation request despite detecting live traffic. | [optional] 
**PatchEquipment** | Pointer to [**Layer1DeinstallDetailsPatchEquipment**](Layer1DeinstallDetailsPatchEquipment.md) |  | [optional] 

## Methods

### NewLayer1DeinstallDetails

`func NewLayer1DeinstallDetails(assetId string, ) *Layer1DeinstallDetails`

NewLayer1DeinstallDetails instantiates a new Layer1DeinstallDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayer1DeinstallDetailsWithDefaults

`func NewLayer1DeinstallDetailsWithDefaults() *Layer1DeinstallDetails`

NewLayer1DeinstallDetailsWithDefaults instantiates a new Layer1DeinstallDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *Layer1DeinstallDetails) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *Layer1DeinstallDetails) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *Layer1DeinstallDetails) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetProceedWithLiveTraffic

`func (o *Layer1DeinstallDetails) GetProceedWithLiveTraffic() bool`

GetProceedWithLiveTraffic returns the ProceedWithLiveTraffic field if non-nil, zero value otherwise.

### GetProceedWithLiveTrafficOk

`func (o *Layer1DeinstallDetails) GetProceedWithLiveTrafficOk() (*bool, bool)`

GetProceedWithLiveTrafficOk returns a tuple with the ProceedWithLiveTraffic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProceedWithLiveTraffic

`func (o *Layer1DeinstallDetails) SetProceedWithLiveTraffic(v bool)`

SetProceedWithLiveTraffic sets ProceedWithLiveTraffic field to given value.

### HasProceedWithLiveTraffic

`func (o *Layer1DeinstallDetails) HasProceedWithLiveTraffic() bool`

HasProceedWithLiveTraffic returns a boolean if a field has been set.

### GetPatchEquipment

`func (o *Layer1DeinstallDetails) GetPatchEquipment() Layer1DeinstallDetailsPatchEquipment`

GetPatchEquipment returns the PatchEquipment field if non-nil, zero value otherwise.

### GetPatchEquipmentOk

`func (o *Layer1DeinstallDetails) GetPatchEquipmentOk() (*Layer1DeinstallDetailsPatchEquipment, bool)`

GetPatchEquipmentOk returns a tuple with the PatchEquipment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchEquipment

`func (o *Layer1DeinstallDetails) SetPatchEquipment(v Layer1DeinstallDetailsPatchEquipment)`

SetPatchEquipment sets PatchEquipment field to given value.

### HasPatchEquipment

`func (o *Layer1DeinstallDetails) HasPatchEquipment() bool`

HasPatchEquipment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


