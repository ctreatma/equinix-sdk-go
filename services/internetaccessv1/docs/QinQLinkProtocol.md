# QinQLinkProtocol

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VlanCTag** | **int32** | VLAN C-Tag number for QINQ link protocol type  | 
**VlanSTag** | **int32** | VLAN S-Tag number for QINQ link protocol type  | 

## Methods

### NewQinQLinkProtocol

`func NewQinQLinkProtocol(vlanCTag int32, vlanSTag int32, ) *QinQLinkProtocol`

NewQinQLinkProtocol instantiates a new QinQLinkProtocol object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQinQLinkProtocolWithDefaults

`func NewQinQLinkProtocolWithDefaults() *QinQLinkProtocol`

NewQinQLinkProtocolWithDefaults instantiates a new QinQLinkProtocol object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVlanCTag

`func (o *QinQLinkProtocol) GetVlanCTag() int32`

GetVlanCTag returns the VlanCTag field if non-nil, zero value otherwise.

### GetVlanCTagOk

`func (o *QinQLinkProtocol) GetVlanCTagOk() (*int32, bool)`

GetVlanCTagOk returns a tuple with the VlanCTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanCTag

`func (o *QinQLinkProtocol) SetVlanCTag(v int32)`

SetVlanCTag sets VlanCTag field to given value.


### GetVlanSTag

`func (o *QinQLinkProtocol) GetVlanSTag() int32`

GetVlanSTag returns the VlanSTag field if non-nil, zero value otherwise.

### GetVlanSTagOk

`func (o *QinQLinkProtocol) GetVlanSTagOk() (*int32, bool)`

GetVlanSTagOk returns a tuple with the VlanSTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanSTag

`func (o *QinQLinkProtocol) SetVlanSTag(v int32)`

SetVlanSTag sets VlanSTag field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


