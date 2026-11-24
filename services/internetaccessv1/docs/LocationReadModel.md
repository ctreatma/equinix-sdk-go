# LocationReadModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Href** | **string** | Location URI | 
**Region** | [**LocationReadModelRegion**](LocationReadModelRegion.md) |  | 
**MetroName** | **string** | Name of the city in which a specified Equinix asset is located. | 
**MetroCode** | **string** | Two-letter prefix indicating the metropolitan area in which a specified Equinix asset is located.  | 
**Ibx** | Pointer to **string** | Alphanumeric identifier assigned to an Equinix International Business Exchange (IBX) data center in which a specified asset is located.  | [optional] 

## Methods

### NewLocationReadModel

`func NewLocationReadModel(href string, region LocationReadModelRegion, metroName string, metroCode string, ) *LocationReadModel`

NewLocationReadModel instantiates a new LocationReadModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationReadModelWithDefaults

`func NewLocationReadModelWithDefaults() *LocationReadModel`

NewLocationReadModelWithDefaults instantiates a new LocationReadModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHref

`func (o *LocationReadModel) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *LocationReadModel) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *LocationReadModel) SetHref(v string)`

SetHref sets Href field to given value.


### GetRegion

`func (o *LocationReadModel) GetRegion() LocationReadModelRegion`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *LocationReadModel) GetRegionOk() (*LocationReadModelRegion, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *LocationReadModel) SetRegion(v LocationReadModelRegion)`

SetRegion sets Region field to given value.


### GetMetroName

`func (o *LocationReadModel) GetMetroName() string`

GetMetroName returns the MetroName field if non-nil, zero value otherwise.

### GetMetroNameOk

`func (o *LocationReadModel) GetMetroNameOk() (*string, bool)`

GetMetroNameOk returns a tuple with the MetroName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroName

`func (o *LocationReadModel) SetMetroName(v string)`

SetMetroName sets MetroName field to given value.


### GetMetroCode

`func (o *LocationReadModel) GetMetroCode() string`

GetMetroCode returns the MetroCode field if non-nil, zero value otherwise.

### GetMetroCodeOk

`func (o *LocationReadModel) GetMetroCodeOk() (*string, bool)`

GetMetroCodeOk returns a tuple with the MetroCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetroCode

`func (o *LocationReadModel) SetMetroCode(v string)`

SetMetroCode sets MetroCode field to given value.


### GetIbx

`func (o *LocationReadModel) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *LocationReadModel) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *LocationReadModel) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *LocationReadModel) HasIbx() bool`

HasIbx returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


