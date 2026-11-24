# OpenIdConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Issuer** | **string** | Issuer identifier URI. | 
**JwksUri** | **string** | URI of the JSON Web Key Set. | 
**TokenEndpoint** | **string** | URI of the token endpoint. | 
**ClaimsSupported** | **[]string** | List of claim names the provider supports. | 
**ResponseTypesSupported** | **[]string** | List of supported response types. | 
**SubjectTypesSupported** | **[]string** | List of supported subject identifier types. | 
**IdTokenSigningAlgValuesSupported** | **[]string** | List of JWS signing algorithms supported for the ID token. | 

## Methods

### NewOpenIdConfiguration

`func NewOpenIdConfiguration(issuer string, jwksUri string, tokenEndpoint string, claimsSupported []string, responseTypesSupported []string, subjectTypesSupported []string, idTokenSigningAlgValuesSupported []string, ) *OpenIdConfiguration`

NewOpenIdConfiguration instantiates a new OpenIdConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenIdConfigurationWithDefaults

`func NewOpenIdConfigurationWithDefaults() *OpenIdConfiguration`

NewOpenIdConfigurationWithDefaults instantiates a new OpenIdConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIssuer

`func (o *OpenIdConfiguration) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *OpenIdConfiguration) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *OpenIdConfiguration) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.


### GetJwksUri

`func (o *OpenIdConfiguration) GetJwksUri() string`

GetJwksUri returns the JwksUri field if non-nil, zero value otherwise.

### GetJwksUriOk

`func (o *OpenIdConfiguration) GetJwksUriOk() (*string, bool)`

GetJwksUriOk returns a tuple with the JwksUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwksUri

`func (o *OpenIdConfiguration) SetJwksUri(v string)`

SetJwksUri sets JwksUri field to given value.


### GetTokenEndpoint

`func (o *OpenIdConfiguration) GetTokenEndpoint() string`

GetTokenEndpoint returns the TokenEndpoint field if non-nil, zero value otherwise.

### GetTokenEndpointOk

`func (o *OpenIdConfiguration) GetTokenEndpointOk() (*string, bool)`

GetTokenEndpointOk returns a tuple with the TokenEndpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenEndpoint

`func (o *OpenIdConfiguration) SetTokenEndpoint(v string)`

SetTokenEndpoint sets TokenEndpoint field to given value.


### GetClaimsSupported

`func (o *OpenIdConfiguration) GetClaimsSupported() []string`

GetClaimsSupported returns the ClaimsSupported field if non-nil, zero value otherwise.

### GetClaimsSupportedOk

`func (o *OpenIdConfiguration) GetClaimsSupportedOk() (*[]string, bool)`

GetClaimsSupportedOk returns a tuple with the ClaimsSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimsSupported

`func (o *OpenIdConfiguration) SetClaimsSupported(v []string)`

SetClaimsSupported sets ClaimsSupported field to given value.


### GetResponseTypesSupported

`func (o *OpenIdConfiguration) GetResponseTypesSupported() []string`

GetResponseTypesSupported returns the ResponseTypesSupported field if non-nil, zero value otherwise.

### GetResponseTypesSupportedOk

`func (o *OpenIdConfiguration) GetResponseTypesSupportedOk() (*[]string, bool)`

GetResponseTypesSupportedOk returns a tuple with the ResponseTypesSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseTypesSupported

`func (o *OpenIdConfiguration) SetResponseTypesSupported(v []string)`

SetResponseTypesSupported sets ResponseTypesSupported field to given value.


### GetSubjectTypesSupported

`func (o *OpenIdConfiguration) GetSubjectTypesSupported() []string`

GetSubjectTypesSupported returns the SubjectTypesSupported field if non-nil, zero value otherwise.

### GetSubjectTypesSupportedOk

`func (o *OpenIdConfiguration) GetSubjectTypesSupportedOk() (*[]string, bool)`

GetSubjectTypesSupportedOk returns a tuple with the SubjectTypesSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectTypesSupported

`func (o *OpenIdConfiguration) SetSubjectTypesSupported(v []string)`

SetSubjectTypesSupported sets SubjectTypesSupported field to given value.


### GetIdTokenSigningAlgValuesSupported

`func (o *OpenIdConfiguration) GetIdTokenSigningAlgValuesSupported() []string`

GetIdTokenSigningAlgValuesSupported returns the IdTokenSigningAlgValuesSupported field if non-nil, zero value otherwise.

### GetIdTokenSigningAlgValuesSupportedOk

`func (o *OpenIdConfiguration) GetIdTokenSigningAlgValuesSupportedOk() (*[]string, bool)`

GetIdTokenSigningAlgValuesSupportedOk returns a tuple with the IdTokenSigningAlgValuesSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdTokenSigningAlgValuesSupported

`func (o *OpenIdConfiguration) SetIdTokenSigningAlgValuesSupported(v []string)`

SetIdTokenSigningAlgValuesSupported sets IdTokenSigningAlgValuesSupported field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


