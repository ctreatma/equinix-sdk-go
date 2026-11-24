# Attachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttachmentId** | **string** | Unique Identifier for the attachment | 
**AttachmentName** | **string** | File name of the attachment | 
**AttachmentType** | **string** | Extension of the document | 
**AttachmentSize** | **float32** | size of the attachment in bytes | 
**CreatedDate** | **time.Time** | Created date | 
**CreatedBy** | **string** | User key of the author of the attachment | 
**LastUpdatedDate** | **time.Time** | Last accessed date for the record | 

## Methods

### NewAttachment

`func NewAttachment(attachmentId string, attachmentName string, attachmentType string, attachmentSize float32, createdDate time.Time, createdBy string, lastUpdatedDate time.Time, ) *Attachment`

NewAttachment instantiates a new Attachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachmentWithDefaults

`func NewAttachmentWithDefaults() *Attachment`

NewAttachmentWithDefaults instantiates a new Attachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachmentId

`func (o *Attachment) GetAttachmentId() string`

GetAttachmentId returns the AttachmentId field if non-nil, zero value otherwise.

### GetAttachmentIdOk

`func (o *Attachment) GetAttachmentIdOk() (*string, bool)`

GetAttachmentIdOk returns a tuple with the AttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentId

`func (o *Attachment) SetAttachmentId(v string)`

SetAttachmentId sets AttachmentId field to given value.


### GetAttachmentName

`func (o *Attachment) GetAttachmentName() string`

GetAttachmentName returns the AttachmentName field if non-nil, zero value otherwise.

### GetAttachmentNameOk

`func (o *Attachment) GetAttachmentNameOk() (*string, bool)`

GetAttachmentNameOk returns a tuple with the AttachmentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentName

`func (o *Attachment) SetAttachmentName(v string)`

SetAttachmentName sets AttachmentName field to given value.


### GetAttachmentType

`func (o *Attachment) GetAttachmentType() string`

GetAttachmentType returns the AttachmentType field if non-nil, zero value otherwise.

### GetAttachmentTypeOk

`func (o *Attachment) GetAttachmentTypeOk() (*string, bool)`

GetAttachmentTypeOk returns a tuple with the AttachmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentType

`func (o *Attachment) SetAttachmentType(v string)`

SetAttachmentType sets AttachmentType field to given value.


### GetAttachmentSize

`func (o *Attachment) GetAttachmentSize() float32`

GetAttachmentSize returns the AttachmentSize field if non-nil, zero value otherwise.

### GetAttachmentSizeOk

`func (o *Attachment) GetAttachmentSizeOk() (*float32, bool)`

GetAttachmentSizeOk returns a tuple with the AttachmentSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentSize

`func (o *Attachment) SetAttachmentSize(v float32)`

SetAttachmentSize sets AttachmentSize field to given value.


### GetCreatedDate

`func (o *Attachment) GetCreatedDate() time.Time`

GetCreatedDate returns the CreatedDate field if non-nil, zero value otherwise.

### GetCreatedDateOk

`func (o *Attachment) GetCreatedDateOk() (*time.Time, bool)`

GetCreatedDateOk returns a tuple with the CreatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDate

`func (o *Attachment) SetCreatedDate(v time.Time)`

SetCreatedDate sets CreatedDate field to given value.


### GetCreatedBy

`func (o *Attachment) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *Attachment) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *Attachment) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetLastUpdatedDate

`func (o *Attachment) GetLastUpdatedDate() time.Time`

GetLastUpdatedDate returns the LastUpdatedDate field if non-nil, zero value otherwise.

### GetLastUpdatedDateOk

`func (o *Attachment) GetLastUpdatedDateOk() (*time.Time, bool)`

GetLastUpdatedDateOk returns a tuple with the LastUpdatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedDate

`func (o *Attachment) SetLastUpdatedDate(v time.Time)`

SetLastUpdatedDate sets LastUpdatedDate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


