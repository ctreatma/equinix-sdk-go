# HierarchyNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LevelType** | Pointer to [**HierarchyNodeLevelType**](HierarchyNodeLevelType.md) |  | [optional] 
**LevelValue** | Pointer to **string** | ibx code, zone us id, cage us id, cabinet us id, sensor number for levelType ibx, zone, cage, cabinet, sensor resp. | [optional] 
**Label** | Pointer to **string** | ibx code, zone unique space id, cage unique space id, cabinet unique space id, sensor number for levelType ibx, zone, cage, cabinet, sensor resp. | [optional] 
**Children** | Pointer to [**[]HierarchyNode**](HierarchyNode.md) | Nodes one level below this node, in the order ibx, zone, cage, cabinet, sensor. Sensor nodes have no children. | [optional] 

## Methods

### NewHierarchyNode

`func NewHierarchyNode() *HierarchyNode`

NewHierarchyNode instantiates a new HierarchyNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHierarchyNodeWithDefaults

`func NewHierarchyNodeWithDefaults() *HierarchyNode`

NewHierarchyNodeWithDefaults instantiates a new HierarchyNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLevelType

`func (o *HierarchyNode) GetLevelType() HierarchyNodeLevelType`

GetLevelType returns the LevelType field if non-nil, zero value otherwise.

### GetLevelTypeOk

`func (o *HierarchyNode) GetLevelTypeOk() (*HierarchyNodeLevelType, bool)`

GetLevelTypeOk returns a tuple with the LevelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevelType

`func (o *HierarchyNode) SetLevelType(v HierarchyNodeLevelType)`

SetLevelType sets LevelType field to given value.

### HasLevelType

`func (o *HierarchyNode) HasLevelType() bool`

HasLevelType returns a boolean if a field has been set.

### GetLevelValue

`func (o *HierarchyNode) GetLevelValue() string`

GetLevelValue returns the LevelValue field if non-nil, zero value otherwise.

### GetLevelValueOk

`func (o *HierarchyNode) GetLevelValueOk() (*string, bool)`

GetLevelValueOk returns a tuple with the LevelValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevelValue

`func (o *HierarchyNode) SetLevelValue(v string)`

SetLevelValue sets LevelValue field to given value.

### HasLevelValue

`func (o *HierarchyNode) HasLevelValue() bool`

HasLevelValue returns a boolean if a field has been set.

### GetLabel

`func (o *HierarchyNode) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *HierarchyNode) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *HierarchyNode) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *HierarchyNode) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetChildren

`func (o *HierarchyNode) GetChildren() []HierarchyNode`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *HierarchyNode) GetChildrenOk() (*[]HierarchyNode, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *HierarchyNode) SetChildren(v []HierarchyNode)`

SetChildren sets Children field to given value.

### HasChildren

`func (o *HierarchyNode) HasChildren() bool`

HasChildren returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


