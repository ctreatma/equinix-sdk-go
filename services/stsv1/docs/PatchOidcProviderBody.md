# PatchOidcProviderBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | A human-friendly name for the identity provider. | [optional] 
**TrustedClientIds** | Pointer to **[]string** | List of OAuth 2.0 client ids for this provider that are permitted to exchange ID tokens for access tokens. The value of the &#x60;aud&#x60; claim in an ID token is checked against this list during token exchange. | [optional] 
**GroupMembershipClaim** | Pointer to [**PatchOidcProviderBodyGroupMembershipClaim**](PatchOidcProviderBodyGroupMembershipClaim.md) |  | [optional] 
**LastRev** | **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | 

## Methods

### NewPatchOidcProviderBody

`func NewPatchOidcProviderBody(lastRev string, ) *PatchOidcProviderBody`

NewPatchOidcProviderBody instantiates a new PatchOidcProviderBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchOidcProviderBodyWithDefaults

`func NewPatchOidcProviderBodyWithDefaults() *PatchOidcProviderBody`

NewPatchOidcProviderBodyWithDefaults instantiates a new PatchOidcProviderBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchOidcProviderBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchOidcProviderBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchOidcProviderBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchOidcProviderBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTrustedClientIds

`func (o *PatchOidcProviderBody) GetTrustedClientIds() []string`

GetTrustedClientIds returns the TrustedClientIds field if non-nil, zero value otherwise.

### GetTrustedClientIdsOk

`func (o *PatchOidcProviderBody) GetTrustedClientIdsOk() (*[]string, bool)`

GetTrustedClientIdsOk returns a tuple with the TrustedClientIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrustedClientIds

`func (o *PatchOidcProviderBody) SetTrustedClientIds(v []string)`

SetTrustedClientIds sets TrustedClientIds field to given value.

### HasTrustedClientIds

`func (o *PatchOidcProviderBody) HasTrustedClientIds() bool`

HasTrustedClientIds returns a boolean if a field has been set.

### GetGroupMembershipClaim

`func (o *PatchOidcProviderBody) GetGroupMembershipClaim() PatchOidcProviderBodyGroupMembershipClaim`

GetGroupMembershipClaim returns the GroupMembershipClaim field if non-nil, zero value otherwise.

### GetGroupMembershipClaimOk

`func (o *PatchOidcProviderBody) GetGroupMembershipClaimOk() (*PatchOidcProviderBodyGroupMembershipClaim, bool)`

GetGroupMembershipClaimOk returns a tuple with the GroupMembershipClaim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMembershipClaim

`func (o *PatchOidcProviderBody) SetGroupMembershipClaim(v PatchOidcProviderBodyGroupMembershipClaim)`

SetGroupMembershipClaim sets GroupMembershipClaim field to given value.

### HasGroupMembershipClaim

`func (o *PatchOidcProviderBody) HasGroupMembershipClaim() bool`

HasGroupMembershipClaim returns a boolean if a field has been set.

### GetLastRev

`func (o *PatchOidcProviderBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *PatchOidcProviderBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *PatchOidcProviderBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


