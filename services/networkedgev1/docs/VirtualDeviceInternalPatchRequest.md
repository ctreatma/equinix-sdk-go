# VirtualDeviceInternalPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Core** | Pointer to **int32** | Use this field to resize your device. When you call this API for device resizing, you cannot change other fields simultaneously. | [optional] 
**Notifications** | Pointer to **[]string** |  | [optional] 
**TermLength** | Pointer to **string** | Term length in months. | [optional] 
**TermLengthEffectiveImmediate** | Pointer to **bool** | By default, this field is true. Set it to false if you want to change the term length at the end of the current term. You cannot downgrade the term length before the end of your current term. | [optional] 
**VirtualDeviceName** | Pointer to **string** | Virtual device name. This should be a minimum of 3 and a maximum of 50 characters. | [optional] 
**ClusterName** | Pointer to **string** | Cluster name. This should be a minimum of 3 and a maximum of 50 characters. | [optional] 
**Status** | Pointer to [**VirtualDeviceInternalPatchRequestStatus**](VirtualDeviceInternalPatchRequestStatus.md) |  | [optional] 
**AutoRenewalOptOut** | Pointer to **bool** | By default, the autoRenewalOptOut field is false. Set it to true if you do not want to automatically renew your terms. Your device will move to a monthly cycle at the expiration of the current terms. | [optional] 
**VendorConfig** | Pointer to [**VirtualDeviceInternalPatchRequestVendorConfig**](VirtualDeviceInternalPatchRequestVendorConfig.md) |  | [optional] 

## Methods

### NewVirtualDeviceInternalPatchRequest

`func NewVirtualDeviceInternalPatchRequest() *VirtualDeviceInternalPatchRequest`

NewVirtualDeviceInternalPatchRequest instantiates a new VirtualDeviceInternalPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVirtualDeviceInternalPatchRequestWithDefaults

`func NewVirtualDeviceInternalPatchRequestWithDefaults() *VirtualDeviceInternalPatchRequest`

NewVirtualDeviceInternalPatchRequestWithDefaults instantiates a new VirtualDeviceInternalPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCore

`func (o *VirtualDeviceInternalPatchRequest) GetCore() int32`

GetCore returns the Core field if non-nil, zero value otherwise.

### GetCoreOk

`func (o *VirtualDeviceInternalPatchRequest) GetCoreOk() (*int32, bool)`

GetCoreOk returns a tuple with the Core field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCore

`func (o *VirtualDeviceInternalPatchRequest) SetCore(v int32)`

SetCore sets Core field to given value.

### HasCore

`func (o *VirtualDeviceInternalPatchRequest) HasCore() bool`

HasCore returns a boolean if a field has been set.

### GetNotifications

`func (o *VirtualDeviceInternalPatchRequest) GetNotifications() []string`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *VirtualDeviceInternalPatchRequest) GetNotificationsOk() (*[]string, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *VirtualDeviceInternalPatchRequest) SetNotifications(v []string)`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *VirtualDeviceInternalPatchRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.

### GetTermLength

`func (o *VirtualDeviceInternalPatchRequest) GetTermLength() string`

GetTermLength returns the TermLength field if non-nil, zero value otherwise.

### GetTermLengthOk

`func (o *VirtualDeviceInternalPatchRequest) GetTermLengthOk() (*string, bool)`

GetTermLengthOk returns a tuple with the TermLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermLength

`func (o *VirtualDeviceInternalPatchRequest) SetTermLength(v string)`

SetTermLength sets TermLength field to given value.

### HasTermLength

`func (o *VirtualDeviceInternalPatchRequest) HasTermLength() bool`

HasTermLength returns a boolean if a field has been set.

### GetTermLengthEffectiveImmediate

`func (o *VirtualDeviceInternalPatchRequest) GetTermLengthEffectiveImmediate() bool`

GetTermLengthEffectiveImmediate returns the TermLengthEffectiveImmediate field if non-nil, zero value otherwise.

### GetTermLengthEffectiveImmediateOk

`func (o *VirtualDeviceInternalPatchRequest) GetTermLengthEffectiveImmediateOk() (*bool, bool)`

GetTermLengthEffectiveImmediateOk returns a tuple with the TermLengthEffectiveImmediate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermLengthEffectiveImmediate

`func (o *VirtualDeviceInternalPatchRequest) SetTermLengthEffectiveImmediate(v bool)`

SetTermLengthEffectiveImmediate sets TermLengthEffectiveImmediate field to given value.

### HasTermLengthEffectiveImmediate

`func (o *VirtualDeviceInternalPatchRequest) HasTermLengthEffectiveImmediate() bool`

HasTermLengthEffectiveImmediate returns a boolean if a field has been set.

### GetVirtualDeviceName

`func (o *VirtualDeviceInternalPatchRequest) GetVirtualDeviceName() string`

GetVirtualDeviceName returns the VirtualDeviceName field if non-nil, zero value otherwise.

### GetVirtualDeviceNameOk

`func (o *VirtualDeviceInternalPatchRequest) GetVirtualDeviceNameOk() (*string, bool)`

GetVirtualDeviceNameOk returns a tuple with the VirtualDeviceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualDeviceName

`func (o *VirtualDeviceInternalPatchRequest) SetVirtualDeviceName(v string)`

SetVirtualDeviceName sets VirtualDeviceName field to given value.

### HasVirtualDeviceName

`func (o *VirtualDeviceInternalPatchRequest) HasVirtualDeviceName() bool`

HasVirtualDeviceName returns a boolean if a field has been set.

### GetClusterName

`func (o *VirtualDeviceInternalPatchRequest) GetClusterName() string`

GetClusterName returns the ClusterName field if non-nil, zero value otherwise.

### GetClusterNameOk

`func (o *VirtualDeviceInternalPatchRequest) GetClusterNameOk() (*string, bool)`

GetClusterNameOk returns a tuple with the ClusterName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterName

`func (o *VirtualDeviceInternalPatchRequest) SetClusterName(v string)`

SetClusterName sets ClusterName field to given value.

### HasClusterName

`func (o *VirtualDeviceInternalPatchRequest) HasClusterName() bool`

HasClusterName returns a boolean if a field has been set.

### GetStatus

`func (o *VirtualDeviceInternalPatchRequest) GetStatus() VirtualDeviceInternalPatchRequestStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *VirtualDeviceInternalPatchRequest) GetStatusOk() (*VirtualDeviceInternalPatchRequestStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *VirtualDeviceInternalPatchRequest) SetStatus(v VirtualDeviceInternalPatchRequestStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *VirtualDeviceInternalPatchRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAutoRenewalOptOut

`func (o *VirtualDeviceInternalPatchRequest) GetAutoRenewalOptOut() bool`

GetAutoRenewalOptOut returns the AutoRenewalOptOut field if non-nil, zero value otherwise.

### GetAutoRenewalOptOutOk

`func (o *VirtualDeviceInternalPatchRequest) GetAutoRenewalOptOutOk() (*bool, bool)`

GetAutoRenewalOptOutOk returns a tuple with the AutoRenewalOptOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoRenewalOptOut

`func (o *VirtualDeviceInternalPatchRequest) SetAutoRenewalOptOut(v bool)`

SetAutoRenewalOptOut sets AutoRenewalOptOut field to given value.

### HasAutoRenewalOptOut

`func (o *VirtualDeviceInternalPatchRequest) HasAutoRenewalOptOut() bool`

HasAutoRenewalOptOut returns a boolean if a field has been set.

### GetVendorConfig

`func (o *VirtualDeviceInternalPatchRequest) GetVendorConfig() VirtualDeviceInternalPatchRequestVendorConfig`

GetVendorConfig returns the VendorConfig field if non-nil, zero value otherwise.

### GetVendorConfigOk

`func (o *VirtualDeviceInternalPatchRequest) GetVendorConfigOk() (*VirtualDeviceInternalPatchRequestVendorConfig, bool)`

GetVendorConfigOk returns a tuple with the VendorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVendorConfig

`func (o *VirtualDeviceInternalPatchRequest) SetVendorConfig(v VirtualDeviceInternalPatchRequestVendorConfig)`

SetVendorConfig sets VendorConfig field to given value.

### HasVendorConfig

`func (o *VirtualDeviceInternalPatchRequest) HasVendorConfig() bool`

HasVendorConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


