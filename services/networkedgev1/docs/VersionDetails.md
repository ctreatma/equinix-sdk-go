# VersionDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cause** | Pointer to [**VersionDetails**](VersionDetails.md) |  | [optional] 
**Version** | Pointer to **string** | Version. | [optional] 
**ImageName** | Pointer to **string** | Image name. | [optional] 
**VersionDateTime** | Pointer to **time.Time** | The date the software was released. | [optional] 
**RetireDateTime** | Pointer to **time.Time** | The date the software will no longer be available. | [optional] 
**Status** | Pointer to [**VersionDetailsStatus**](VersionDetailsStatus.md) |  | [optional] 
**StableVersion** | Pointer to **bool** | Whether this is a stable version. | [optional] 
**AllowedUpgradableVersions** | Pointer to **[]string** | List of allowed upgradable versions. | [optional] 
**SupportedLicenseTypes** | Pointer to [**[]VersionDetailsSupportedLicenseTypesInner**](VersionDetailsSupportedLicenseTypesInner.md) | Supported license types. | [optional] 

## Methods

### NewVersionDetails

`func NewVersionDetails() *VersionDetails`

NewVersionDetails instantiates a new VersionDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVersionDetailsWithDefaults

`func NewVersionDetailsWithDefaults() *VersionDetails`

NewVersionDetailsWithDefaults instantiates a new VersionDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCause

`func (o *VersionDetails) GetCause() VersionDetails`

GetCause returns the Cause field if non-nil, zero value otherwise.

### GetCauseOk

`func (o *VersionDetails) GetCauseOk() (*VersionDetails, bool)`

GetCauseOk returns a tuple with the Cause field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCause

`func (o *VersionDetails) SetCause(v VersionDetails)`

SetCause sets Cause field to given value.

### HasCause

`func (o *VersionDetails) HasCause() bool`

HasCause returns a boolean if a field has been set.

### GetVersion

`func (o *VersionDetails) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *VersionDetails) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *VersionDetails) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *VersionDetails) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetImageName

`func (o *VersionDetails) GetImageName() string`

GetImageName returns the ImageName field if non-nil, zero value otherwise.

### GetImageNameOk

`func (o *VersionDetails) GetImageNameOk() (*string, bool)`

GetImageNameOk returns a tuple with the ImageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageName

`func (o *VersionDetails) SetImageName(v string)`

SetImageName sets ImageName field to given value.

### HasImageName

`func (o *VersionDetails) HasImageName() bool`

HasImageName returns a boolean if a field has been set.

### GetVersionDateTime

`func (o *VersionDetails) GetVersionDateTime() time.Time`

GetVersionDateTime returns the VersionDateTime field if non-nil, zero value otherwise.

### GetVersionDateTimeOk

`func (o *VersionDetails) GetVersionDateTimeOk() (*time.Time, bool)`

GetVersionDateTimeOk returns a tuple with the VersionDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionDateTime

`func (o *VersionDetails) SetVersionDateTime(v time.Time)`

SetVersionDateTime sets VersionDateTime field to given value.

### HasVersionDateTime

`func (o *VersionDetails) HasVersionDateTime() bool`

HasVersionDateTime returns a boolean if a field has been set.

### GetRetireDateTime

`func (o *VersionDetails) GetRetireDateTime() time.Time`

GetRetireDateTime returns the RetireDateTime field if non-nil, zero value otherwise.

### GetRetireDateTimeOk

`func (o *VersionDetails) GetRetireDateTimeOk() (*time.Time, bool)`

GetRetireDateTimeOk returns a tuple with the RetireDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetireDateTime

`func (o *VersionDetails) SetRetireDateTime(v time.Time)`

SetRetireDateTime sets RetireDateTime field to given value.

### HasRetireDateTime

`func (o *VersionDetails) HasRetireDateTime() bool`

HasRetireDateTime returns a boolean if a field has been set.

### GetStatus

`func (o *VersionDetails) GetStatus() VersionDetailsStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *VersionDetails) GetStatusOk() (*VersionDetailsStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *VersionDetails) SetStatus(v VersionDetailsStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *VersionDetails) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStableVersion

`func (o *VersionDetails) GetStableVersion() bool`

GetStableVersion returns the StableVersion field if non-nil, zero value otherwise.

### GetStableVersionOk

`func (o *VersionDetails) GetStableVersionOk() (*bool, bool)`

GetStableVersionOk returns a tuple with the StableVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStableVersion

`func (o *VersionDetails) SetStableVersion(v bool)`

SetStableVersion sets StableVersion field to given value.

### HasStableVersion

`func (o *VersionDetails) HasStableVersion() bool`

HasStableVersion returns a boolean if a field has been set.

### GetAllowedUpgradableVersions

`func (o *VersionDetails) GetAllowedUpgradableVersions() []string`

GetAllowedUpgradableVersions returns the AllowedUpgradableVersions field if non-nil, zero value otherwise.

### GetAllowedUpgradableVersionsOk

`func (o *VersionDetails) GetAllowedUpgradableVersionsOk() (*[]string, bool)`

GetAllowedUpgradableVersionsOk returns a tuple with the AllowedUpgradableVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedUpgradableVersions

`func (o *VersionDetails) SetAllowedUpgradableVersions(v []string)`

SetAllowedUpgradableVersions sets AllowedUpgradableVersions field to given value.

### HasAllowedUpgradableVersions

`func (o *VersionDetails) HasAllowedUpgradableVersions() bool`

HasAllowedUpgradableVersions returns a boolean if a field has been set.

### GetSupportedLicenseTypes

`func (o *VersionDetails) GetSupportedLicenseTypes() []VersionDetailsSupportedLicenseTypesInner`

GetSupportedLicenseTypes returns the SupportedLicenseTypes field if non-nil, zero value otherwise.

### GetSupportedLicenseTypesOk

`func (o *VersionDetails) GetSupportedLicenseTypesOk() (*[]VersionDetailsSupportedLicenseTypesInner, bool)`

GetSupportedLicenseTypesOk returns a tuple with the SupportedLicenseTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedLicenseTypes

`func (o *VersionDetails) SetSupportedLicenseTypes(v []VersionDetailsSupportedLicenseTypesInner)`

SetSupportedLicenseTypes sets SupportedLicenseTypes field to given value.

### HasSupportedLicenseTypes

`func (o *VersionDetails) HasSupportedLicenseTypes() bool`

HasSupportedLicenseTypes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


