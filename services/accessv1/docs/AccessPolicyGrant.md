# AccessPolicyGrant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GrantId** | **string** | Uniquely identifies an access policy grant. | 
**AccessPolicyId** | [**ListGrantsAccessPolicyIdParameterOneOf**](ListGrantsAccessPolicyIdParameterOneOf.md) |  | 
**AccessPolicyErn** | **string** | Equinix resource name, a universally unique identifier for a resource across all clouds, regions, and   services. Formatted as   \&quot;ern:&amp;lt;cloudId&amp;gt;:&amp;lt;serviceId&amp;gt;:&amp;lt;regionId&amp;gt;:&amp;lt;projectId&amp;gt;:&amp;lt;resourceType&amp;gt;:&amp;lt;resourceId&amp;gt;\&quot;. | 
**Grantee** | [**Grantee**](Grantee.md) |  | 
**CreatedBy** | **string** | A string indicating the principal who invoked an operation to create the resource. | 
**CreatedAt** | **string** | A string timestamp indicating when the resource was created. Formatted like: \&quot;2025-02-12T17:24:19.033772087Z\&quot; | 

## Methods

### NewAccessPolicyGrant

`func NewAccessPolicyGrant(grantId string, accessPolicyId ListGrantsAccessPolicyIdParameterOneOf, accessPolicyErn string, grantee Grantee, createdBy string, createdAt string, ) *AccessPolicyGrant`

NewAccessPolicyGrant instantiates a new AccessPolicyGrant object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccessPolicyGrantWithDefaults

`func NewAccessPolicyGrantWithDefaults() *AccessPolicyGrant`

NewAccessPolicyGrantWithDefaults instantiates a new AccessPolicyGrant object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrantId

`func (o *AccessPolicyGrant) GetGrantId() string`

GetGrantId returns the GrantId field if non-nil, zero value otherwise.

### GetGrantIdOk

`func (o *AccessPolicyGrant) GetGrantIdOk() (*string, bool)`

GetGrantIdOk returns a tuple with the GrantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantId

`func (o *AccessPolicyGrant) SetGrantId(v string)`

SetGrantId sets GrantId field to given value.


### GetAccessPolicyId

`func (o *AccessPolicyGrant) GetAccessPolicyId() ListGrantsAccessPolicyIdParameterOneOf`

GetAccessPolicyId returns the AccessPolicyId field if non-nil, zero value otherwise.

### GetAccessPolicyIdOk

`func (o *AccessPolicyGrant) GetAccessPolicyIdOk() (*ListGrantsAccessPolicyIdParameterOneOf, bool)`

GetAccessPolicyIdOk returns a tuple with the AccessPolicyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessPolicyId

`func (o *AccessPolicyGrant) SetAccessPolicyId(v ListGrantsAccessPolicyIdParameterOneOf)`

SetAccessPolicyId sets AccessPolicyId field to given value.


### GetAccessPolicyErn

`func (o *AccessPolicyGrant) GetAccessPolicyErn() string`

GetAccessPolicyErn returns the AccessPolicyErn field if non-nil, zero value otherwise.

### GetAccessPolicyErnOk

`func (o *AccessPolicyGrant) GetAccessPolicyErnOk() (*string, bool)`

GetAccessPolicyErnOk returns a tuple with the AccessPolicyErn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessPolicyErn

`func (o *AccessPolicyGrant) SetAccessPolicyErn(v string)`

SetAccessPolicyErn sets AccessPolicyErn field to given value.


### GetGrantee

`func (o *AccessPolicyGrant) GetGrantee() Grantee`

GetGrantee returns the Grantee field if non-nil, zero value otherwise.

### GetGranteeOk

`func (o *AccessPolicyGrant) GetGranteeOk() (*Grantee, bool)`

GetGranteeOk returns a tuple with the Grantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantee

`func (o *AccessPolicyGrant) SetGrantee(v Grantee)`

SetGrantee sets Grantee field to given value.


### GetCreatedBy

`func (o *AccessPolicyGrant) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *AccessPolicyGrant) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *AccessPolicyGrant) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetCreatedAt

`func (o *AccessPolicyGrant) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AccessPolicyGrant) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AccessPolicyGrant) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


