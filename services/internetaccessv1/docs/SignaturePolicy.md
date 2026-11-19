# SignaturePolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Signature** | [**Signature**](Signature.md) |  | 
**ClickThroughAllowed** | **bool** |  | 
**Location** | [**SignaturePolicyLocation**](SignaturePolicyLocation.md) |  | 

## Methods

### NewSignaturePolicy

`func NewSignaturePolicy(signature Signature, clickThroughAllowed bool, location SignaturePolicyLocation, ) *SignaturePolicy`

NewSignaturePolicy instantiates a new SignaturePolicy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSignaturePolicyWithDefaults

`func NewSignaturePolicyWithDefaults() *SignaturePolicy`

NewSignaturePolicyWithDefaults instantiates a new SignaturePolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSignature

`func (o *SignaturePolicy) GetSignature() Signature`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *SignaturePolicy) GetSignatureOk() (*Signature, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *SignaturePolicy) SetSignature(v Signature)`

SetSignature sets Signature field to given value.


### GetClickThroughAllowed

`func (o *SignaturePolicy) GetClickThroughAllowed() bool`

GetClickThroughAllowed returns the ClickThroughAllowed field if non-nil, zero value otherwise.

### GetClickThroughAllowedOk

`func (o *SignaturePolicy) GetClickThroughAllowedOk() (*bool, bool)`

GetClickThroughAllowedOk returns a tuple with the ClickThroughAllowed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClickThroughAllowed

`func (o *SignaturePolicy) SetClickThroughAllowed(v bool)`

SetClickThroughAllowed sets ClickThroughAllowed field to given value.


### GetLocation

`func (o *SignaturePolicy) GetLocation() SignaturePolicyLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *SignaturePolicy) GetLocationOk() (*SignaturePolicyLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *SignaturePolicy) SetLocation(v SignaturePolicyLocation)`

SetLocation sets Location field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


