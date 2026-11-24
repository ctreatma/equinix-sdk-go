# TicketCode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | Unique ticket code identifier (e.g. \&quot;0301-0000\&quot;). | [optional] 
**Classification** | Pointer to **NullableString** | Hierarchical classification in the format &#x60;&lt;Category&gt;-&lt;Sub-Category&gt;-&lt;Issue Type&gt;&#x60;. | [optional] 
**Description** | Pointer to **NullableString** | Human-readable description of the support ticket type. | [optional] 
**Status** | Pointer to [**NullableTicketCodeStatus**](TicketCodeStatus.md) |  | [optional] 
**Deprecation** | Pointer to [**NullableTicketCodeDeprecation**](TicketCodeDeprecation.md) |  | [optional] 

## Methods

### NewTicketCode

`func NewTicketCode() *TicketCode`

NewTicketCode instantiates a new TicketCode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTicketCodeWithDefaults

`func NewTicketCodeWithDefaults() *TicketCode`

NewTicketCodeWithDefaults instantiates a new TicketCode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *TicketCode) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TicketCode) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TicketCode) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *TicketCode) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetClassification

`func (o *TicketCode) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *TicketCode) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *TicketCode) SetClassification(v string)`

SetClassification sets Classification field to given value.

### HasClassification

`func (o *TicketCode) HasClassification() bool`

HasClassification returns a boolean if a field has been set.

### SetClassificationNil

`func (o *TicketCode) SetClassificationNil(b bool)`

 SetClassificationNil sets the value for Classification to be an explicit nil

### UnsetClassification
`func (o *TicketCode) UnsetClassification()`

UnsetClassification ensures that no value is present for Classification, not even an explicit nil
### GetDescription

`func (o *TicketCode) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *TicketCode) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *TicketCode) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *TicketCode) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *TicketCode) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *TicketCode) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetStatus

`func (o *TicketCode) GetStatus() TicketCodeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TicketCode) GetStatusOk() (*TicketCodeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TicketCode) SetStatus(v TicketCodeStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TicketCode) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *TicketCode) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *TicketCode) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetDeprecation

`func (o *TicketCode) GetDeprecation() TicketCodeDeprecation`

GetDeprecation returns the Deprecation field if non-nil, zero value otherwise.

### GetDeprecationOk

`func (o *TicketCode) GetDeprecationOk() (*TicketCodeDeprecation, bool)`

GetDeprecationOk returns a tuple with the Deprecation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeprecation

`func (o *TicketCode) SetDeprecation(v TicketCodeDeprecation)`

SetDeprecation sets Deprecation field to given value.

### HasDeprecation

`func (o *TicketCode) HasDeprecation() bool`

HasDeprecation returns a boolean if a field has been set.

### SetDeprecationNil

`func (o *TicketCode) SetDeprecationNil(b bool)`

 SetDeprecationNil sets the value for Deprecation to be an explicit nil

### UnsetDeprecation
`func (o *TicketCode) UnsetDeprecation()`

UnsetDeprecation ensures that no value is present for Deprecation, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


