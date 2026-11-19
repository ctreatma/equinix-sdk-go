# GeneralPermissionSetRef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PermissionSet** | [**GeneralPermissionSetRefPermissionSet**](GeneralPermissionSetRefPermissionSet.md) |  | 
**Condition** | Pointer to **string** |  | [optional] 
**IbxLocationCondition** | Pointer to [**IbxLocationCondition**](IbxLocationCondition.md) |  | [optional] 

## Methods

### NewGeneralPermissionSetRef

`func NewGeneralPermissionSetRef(permissionSet GeneralPermissionSetRefPermissionSet, ) *GeneralPermissionSetRef`

NewGeneralPermissionSetRef instantiates a new GeneralPermissionSetRef object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGeneralPermissionSetRefWithDefaults

`func NewGeneralPermissionSetRefWithDefaults() *GeneralPermissionSetRef`

NewGeneralPermissionSetRefWithDefaults instantiates a new GeneralPermissionSetRef object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissionSet

`func (o *GeneralPermissionSetRef) GetPermissionSet() GeneralPermissionSetRefPermissionSet`

GetPermissionSet returns the PermissionSet field if non-nil, zero value otherwise.

### GetPermissionSetOk

`func (o *GeneralPermissionSetRef) GetPermissionSetOk() (*GeneralPermissionSetRefPermissionSet, bool)`

GetPermissionSetOk returns a tuple with the PermissionSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissionSet

`func (o *GeneralPermissionSetRef) SetPermissionSet(v GeneralPermissionSetRefPermissionSet)`

SetPermissionSet sets PermissionSet field to given value.


### GetCondition

`func (o *GeneralPermissionSetRef) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *GeneralPermissionSetRef) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *GeneralPermissionSetRef) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *GeneralPermissionSetRef) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### GetIbxLocationCondition

`func (o *GeneralPermissionSetRef) GetIbxLocationCondition() IbxLocationCondition`

GetIbxLocationCondition returns the IbxLocationCondition field if non-nil, zero value otherwise.

### GetIbxLocationConditionOk

`func (o *GeneralPermissionSetRef) GetIbxLocationConditionOk() (*IbxLocationCondition, bool)`

GetIbxLocationConditionOk returns a tuple with the IbxLocationCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbxLocationCondition

`func (o *GeneralPermissionSetRef) SetIbxLocationCondition(v IbxLocationCondition)`

SetIbxLocationCondition sets IbxLocationCondition field to given value.

### HasIbxLocationCondition

`func (o *GeneralPermissionSetRef) HasIbxLocationCondition() bool`

HasIbxLocationCondition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


