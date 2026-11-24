# Attachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | UUID of the uploaded attachment. Use the attachmentId returned by the Attachment API. | [optional] 
**Name** | Pointer to **string** | File name of the uploaded attachment, including the extension. Use the attachmentName returned by the Attachment API. | [optional] 
**Source** | Pointer to [**AttachmentSource**](AttachmentSource.md) |  | [optional] 

## Methods

### NewAttachment

`func NewAttachment() *Attachment`

NewAttachment instantiates a new Attachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachmentWithDefaults

`func NewAttachmentWithDefaults() *Attachment`

NewAttachmentWithDefaults instantiates a new Attachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Attachment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Attachment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Attachment) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Attachment) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Attachment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Attachment) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Attachment) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Attachment) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSource

`func (o *Attachment) GetSource() AttachmentSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Attachment) GetSourceOk() (*AttachmentSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Attachment) SetSource(v AttachmentSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *Attachment) HasSource() bool`

HasSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


