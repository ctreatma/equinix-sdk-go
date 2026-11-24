# Links

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**First** | [**ReferenceLink**](ReferenceLink.md) |  | 
**Next** | Pointer to [**ReferenceLink**](ReferenceLink.md) |  | [optional] 
**Self** | [**ReferenceLink**](ReferenceLink.md) |  | 
**Prev** | Pointer to [**ReferenceLink**](ReferenceLink.md) |  | [optional] 
**Last** | Pointer to [**ReferenceLink**](ReferenceLink.md) |  | [optional] 

## Methods

### NewLinks

`func NewLinks(first ReferenceLink, self ReferenceLink, ) *Links`

NewLinks instantiates a new Links object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinksWithDefaults

`func NewLinksWithDefaults() *Links`

NewLinksWithDefaults instantiates a new Links object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirst

`func (o *Links) GetFirst() ReferenceLink`

GetFirst returns the First field if non-nil, zero value otherwise.

### GetFirstOk

`func (o *Links) GetFirstOk() (*ReferenceLink, bool)`

GetFirstOk returns a tuple with the First field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirst

`func (o *Links) SetFirst(v ReferenceLink)`

SetFirst sets First field to given value.


### GetNext

`func (o *Links) GetNext() ReferenceLink`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *Links) GetNextOk() (*ReferenceLink, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *Links) SetNext(v ReferenceLink)`

SetNext sets Next field to given value.

### HasNext

`func (o *Links) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetSelf

`func (o *Links) GetSelf() ReferenceLink`

GetSelf returns the Self field if non-nil, zero value otherwise.

### GetSelfOk

`func (o *Links) GetSelfOk() (*ReferenceLink, bool)`

GetSelfOk returns a tuple with the Self field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelf

`func (o *Links) SetSelf(v ReferenceLink)`

SetSelf sets Self field to given value.


### GetPrev

`func (o *Links) GetPrev() ReferenceLink`

GetPrev returns the Prev field if non-nil, zero value otherwise.

### GetPrevOk

`func (o *Links) GetPrevOk() (*ReferenceLink, bool)`

GetPrevOk returns a tuple with the Prev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrev

`func (o *Links) SetPrev(v ReferenceLink)`

SetPrev sets Prev field to given value.

### HasPrev

`func (o *Links) HasPrev() bool`

HasPrev returns a boolean if a field has been set.

### GetLast

`func (o *Links) GetLast() ReferenceLink`

GetLast returns the Last field if non-nil, zero value otherwise.

### GetLastOk

`func (o *Links) GetLastOk() (*ReferenceLink, bool)`

GetLastOk returns a tuple with the Last field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast

`func (o *Links) SetLast(v ReferenceLink)`

SetLast sets Last field to given value.

### HasLast

`func (o *Links) HasLast() bool`

HasLast returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


