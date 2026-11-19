# ZSideWithLOA

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LoaAttachmentId** | **string** | Attachment ID of Letter of Authorization (LOA). Refer to Attachment API to upload documents via API. | 
**Ibx** | **string** | IBX location code. | 
**ProviderName** | **string** | Account name of service provider. | 

## Methods

### NewZSideWithLOA

`func NewZSideWithLOA(loaAttachmentId string, ibx string, providerName string, ) *ZSideWithLOA`

NewZSideWithLOA instantiates a new ZSideWithLOA object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewZSideWithLOAWithDefaults

`func NewZSideWithLOAWithDefaults() *ZSideWithLOA`

NewZSideWithLOAWithDefaults instantiates a new ZSideWithLOA object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoaAttachmentId

`func (o *ZSideWithLOA) GetLoaAttachmentId() string`

GetLoaAttachmentId returns the LoaAttachmentId field if non-nil, zero value otherwise.

### GetLoaAttachmentIdOk

`func (o *ZSideWithLOA) GetLoaAttachmentIdOk() (*string, bool)`

GetLoaAttachmentIdOk returns a tuple with the LoaAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoaAttachmentId

`func (o *ZSideWithLOA) SetLoaAttachmentId(v string)`

SetLoaAttachmentId sets LoaAttachmentId field to given value.


### GetIbx

`func (o *ZSideWithLOA) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *ZSideWithLOA) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *ZSideWithLOA) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetProviderName

`func (o *ZSideWithLOA) GetProviderName() string`

GetProviderName returns the ProviderName field if non-nil, zero value otherwise.

### GetProviderNameOk

`func (o *ZSideWithLOA) GetProviderNameOk() (*string, bool)`

GetProviderNameOk returns a tuple with the ProviderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderName

`func (o *ZSideWithLOA) SetProviderName(v string)`

SetProviderName sets ProviderName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


