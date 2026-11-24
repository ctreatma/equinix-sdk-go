# AddGrantBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Grantee** | [**Grantee**](Grantee.md) |  | 
**LastRev** | Pointer to **string** | An opaque string that represents the expected revision of a given resource. This is provided when a resource is   updated so that if a concurrent update has occurred since the resource was read, then the collision will be detected. | [optional] 

## Methods

### NewAddGrantBody

`func NewAddGrantBody(grantee Grantee, ) *AddGrantBody`

NewAddGrantBody instantiates a new AddGrantBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddGrantBodyWithDefaults

`func NewAddGrantBodyWithDefaults() *AddGrantBody`

NewAddGrantBodyWithDefaults instantiates a new AddGrantBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrantee

`func (o *AddGrantBody) GetGrantee() Grantee`

GetGrantee returns the Grantee field if non-nil, zero value otherwise.

### GetGranteeOk

`func (o *AddGrantBody) GetGranteeOk() (*Grantee, bool)`

GetGranteeOk returns a tuple with the Grantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantee

`func (o *AddGrantBody) SetGrantee(v Grantee)`

SetGrantee sets Grantee field to given value.


### GetLastRev

`func (o *AddGrantBody) GetLastRev() string`

GetLastRev returns the LastRev field if non-nil, zero value otherwise.

### GetLastRevOk

`func (o *AddGrantBody) GetLastRevOk() (*string, bool)`

GetLastRevOk returns a tuple with the LastRev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRev

`func (o *AddGrantBody) SetLastRev(v string)`

SetLastRev sets LastRev field to given value.

### HasLastRev

`func (o *AddGrantBody) HasLastRev() bool`

HasLastRev returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


