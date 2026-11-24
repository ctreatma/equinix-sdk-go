# ZSide

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotificationEmail** | Pointer to **string** | Z-Side customer will be notified when cross connect is complete via specified email address | [optional] 
**LoaAttachmentId** | **string** | Attachment ID of Letter of Authorization (LOA). Refer to Attachment API to upload documents via API. | 
**Ibx** | **string** | IBX location code. | 
**ProviderName** | **string** | Account name of service provider. | 
**ConnectorType** | [**ConnectorTypes**](ConnectorTypes.md) |  | 
**PatchPanel** | [**PatchPanel**](PatchPanel.md) |  | 
**CircuitId** | Pointer to **string** | Customer or carrier circuit ID cable reference number for verification purposes. | [optional] 

## Methods

### NewZSide

`func NewZSide(loaAttachmentId string, ibx string, providerName string, connectorType ConnectorTypes, patchPanel PatchPanel, ) *ZSide`

NewZSide instantiates a new ZSide object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewZSideWithDefaults

`func NewZSideWithDefaults() *ZSide`

NewZSideWithDefaults instantiates a new ZSide object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotificationEmail

`func (o *ZSide) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *ZSide) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *ZSide) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *ZSide) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### GetLoaAttachmentId

`func (o *ZSide) GetLoaAttachmentId() string`

GetLoaAttachmentId returns the LoaAttachmentId field if non-nil, zero value otherwise.

### GetLoaAttachmentIdOk

`func (o *ZSide) GetLoaAttachmentIdOk() (*string, bool)`

GetLoaAttachmentIdOk returns a tuple with the LoaAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoaAttachmentId

`func (o *ZSide) SetLoaAttachmentId(v string)`

SetLoaAttachmentId sets LoaAttachmentId field to given value.


### GetIbx

`func (o *ZSide) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *ZSide) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *ZSide) SetIbx(v string)`

SetIbx sets Ibx field to given value.


### GetProviderName

`func (o *ZSide) GetProviderName() string`

GetProviderName returns the ProviderName field if non-nil, zero value otherwise.

### GetProviderNameOk

`func (o *ZSide) GetProviderNameOk() (*string, bool)`

GetProviderNameOk returns a tuple with the ProviderName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderName

`func (o *ZSide) SetProviderName(v string)`

SetProviderName sets ProviderName field to given value.


### GetConnectorType

`func (o *ZSide) GetConnectorType() ConnectorTypes`

GetConnectorType returns the ConnectorType field if non-nil, zero value otherwise.

### GetConnectorTypeOk

`func (o *ZSide) GetConnectorTypeOk() (*ConnectorTypes, bool)`

GetConnectorTypeOk returns a tuple with the ConnectorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectorType

`func (o *ZSide) SetConnectorType(v ConnectorTypes)`

SetConnectorType sets ConnectorType field to given value.


### GetPatchPanel

`func (o *ZSide) GetPatchPanel() PatchPanel`

GetPatchPanel returns the PatchPanel field if non-nil, zero value otherwise.

### GetPatchPanelOk

`func (o *ZSide) GetPatchPanelOk() (*PatchPanel, bool)`

GetPatchPanelOk returns a tuple with the PatchPanel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchPanel

`func (o *ZSide) SetPatchPanel(v PatchPanel)`

SetPatchPanel sets PatchPanel field to given value.


### GetCircuitId

`func (o *ZSide) GetCircuitId() string`

GetCircuitId returns the CircuitId field if non-nil, zero value otherwise.

### GetCircuitIdOk

`func (o *ZSide) GetCircuitIdOk() (*string, bool)`

GetCircuitIdOk returns a tuple with the CircuitId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCircuitId

`func (o *ZSide) SetCircuitId(v string)`

SetCircuitId sets CircuitId field to given value.

### HasCircuitId

`func (o *ZSide) HasCircuitId() bool`

HasCircuitId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


