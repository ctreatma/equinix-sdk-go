# Link

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rel** | [**LinkRel**](LinkRel.md) |  | 
**Href** | **string** | An absolute URL that is the subject of the link&#39;s context, such as a link to a service profile or set of statistics. | 
**Method** | Pointer to [**LinkMethod**](LinkMethod.md) |  | [optional] 
**ContentType** | Pointer to **string** | MIME type indicating the document format. Syntax complies with IETF RFC 6838. | [optional] 
**Authenticate** | Pointer to **bool** | Flag showing whether authentication is required to access the linked resource. The default value is false. | [optional] 

## Methods

### NewLink

`func NewLink(rel LinkRel, href string, ) *Link`

NewLink instantiates a new Link object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinkWithDefaults

`func NewLinkWithDefaults() *Link`

NewLinkWithDefaults instantiates a new Link object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRel

`func (o *Link) GetRel() LinkRel`

GetRel returns the Rel field if non-nil, zero value otherwise.

### GetRelOk

`func (o *Link) GetRelOk() (*LinkRel, bool)`

GetRelOk returns a tuple with the Rel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRel

`func (o *Link) SetRel(v LinkRel)`

SetRel sets Rel field to given value.


### GetHref

`func (o *Link) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *Link) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *Link) SetHref(v string)`

SetHref sets Href field to given value.


### GetMethod

`func (o *Link) GetMethod() LinkMethod`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *Link) GetMethodOk() (*LinkMethod, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *Link) SetMethod(v LinkMethod)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *Link) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetContentType

`func (o *Link) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *Link) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *Link) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *Link) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetAuthenticate

`func (o *Link) GetAuthenticate() bool`

GetAuthenticate returns the Authenticate field if non-nil, zero value otherwise.

### GetAuthenticateOk

`func (o *Link) GetAuthenticateOk() (*bool, bool)`

GetAuthenticateOk returns a tuple with the Authenticate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticate

`func (o *Link) SetAuthenticate(v bool)`

SetAuthenticate sets Authenticate field to given value.

### HasAuthenticate

`func (o *Link) HasAuthenticate() bool`

HasAuthenticate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


