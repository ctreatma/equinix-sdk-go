# CreateOidcProviderBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A human-friendly name for the identity provider. | 
**TrustedClientIds** | **[]string** | List of OAuth 2.0 client ids for this provider that are permitted to exchange ID tokens for access tokens. The value of the &#x60;aud&#x60; claim in an ID token is checked against this list during token exchange. | 
**GroupMembershipClaim** | Pointer to **string** | Name of the claim in the ID tokens provided by this OIDC issuer whose value the STS should interpret as containing a user&#39;s group memberships, for authorization purposes. The value of the group membership claim in an ID token must be an array of strings, where each string is a unique, non-reassignable identifier for a group. When this property is not set, the STS does not interpret any claim from this provider as a group membership claim. | [optional] 
**IssuerLocation** | **string** | The OIDC issuer location URL. | 
**IdpPrefix** | **string** |  | 

## Methods

### NewCreateOidcProviderBody

`func NewCreateOidcProviderBody(name string, trustedClientIds []string, issuerLocation string, idpPrefix string, ) *CreateOidcProviderBody`

NewCreateOidcProviderBody instantiates a new CreateOidcProviderBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOidcProviderBodyWithDefaults

`func NewCreateOidcProviderBodyWithDefaults() *CreateOidcProviderBody`

NewCreateOidcProviderBodyWithDefaults instantiates a new CreateOidcProviderBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOidcProviderBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOidcProviderBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOidcProviderBody) SetName(v string)`

SetName sets Name field to given value.


### GetTrustedClientIds

`func (o *CreateOidcProviderBody) GetTrustedClientIds() []string`

GetTrustedClientIds returns the TrustedClientIds field if non-nil, zero value otherwise.

### GetTrustedClientIdsOk

`func (o *CreateOidcProviderBody) GetTrustedClientIdsOk() (*[]string, bool)`

GetTrustedClientIdsOk returns a tuple with the TrustedClientIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrustedClientIds

`func (o *CreateOidcProviderBody) SetTrustedClientIds(v []string)`

SetTrustedClientIds sets TrustedClientIds field to given value.


### GetGroupMembershipClaim

`func (o *CreateOidcProviderBody) GetGroupMembershipClaim() string`

GetGroupMembershipClaim returns the GroupMembershipClaim field if non-nil, zero value otherwise.

### GetGroupMembershipClaimOk

`func (o *CreateOidcProviderBody) GetGroupMembershipClaimOk() (*string, bool)`

GetGroupMembershipClaimOk returns a tuple with the GroupMembershipClaim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMembershipClaim

`func (o *CreateOidcProviderBody) SetGroupMembershipClaim(v string)`

SetGroupMembershipClaim sets GroupMembershipClaim field to given value.

### HasGroupMembershipClaim

`func (o *CreateOidcProviderBody) HasGroupMembershipClaim() bool`

HasGroupMembershipClaim returns a boolean if a field has been set.

### GetIssuerLocation

`func (o *CreateOidcProviderBody) GetIssuerLocation() string`

GetIssuerLocation returns the IssuerLocation field if non-nil, zero value otherwise.

### GetIssuerLocationOk

`func (o *CreateOidcProviderBody) GetIssuerLocationOk() (*string, bool)`

GetIssuerLocationOk returns a tuple with the IssuerLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerLocation

`func (o *CreateOidcProviderBody) SetIssuerLocation(v string)`

SetIssuerLocation sets IssuerLocation field to given value.


### GetIdpPrefix

`func (o *CreateOidcProviderBody) GetIdpPrefix() string`

GetIdpPrefix returns the IdpPrefix field if non-nil, zero value otherwise.

### GetIdpPrefixOk

`func (o *CreateOidcProviderBody) GetIdpPrefixOk() (*string, bool)`

GetIdpPrefixOk returns a tuple with the IdpPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdpPrefix

`func (o *CreateOidcProviderBody) SetIdpPrefix(v string)`

SetIdpPrefix sets IdpPrefix field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


