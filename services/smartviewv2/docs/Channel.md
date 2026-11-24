# Channel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChannelType** | Pointer to [**ChannelChannelType**](ChannelChannelType.md) |  | [optional] 
**AwsIotCoreChannelConfiguration** | Pointer to [**AwsIotCoreChannelConfiguration**](AwsIotCoreChannelConfiguration.md) |  | [optional] 
**WebhookChannelConfiguration** | Pointer to [**WebhookChannelConfiguration**](WebhookChannelConfiguration.md) |  | [optional] 
**AzureChannelConfiguration** | Pointer to [**AzureChannelConfiguration**](AzureChannelConfiguration.md) |  | [optional] 
**RestChannelConfiguration** | Pointer to **map[string]interface{}** | The configuration for a &#39;REST&#39; channel. No parameters are required; send an empty object. Use the subscription ID returned in the &#x60;Location&#x60; header to consume the real-time feed from the Equinix API. | [optional] 

## Methods

### NewChannel

`func NewChannel() *Channel`

NewChannel instantiates a new Channel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChannelWithDefaults

`func NewChannelWithDefaults() *Channel`

NewChannelWithDefaults instantiates a new Channel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannelType

`func (o *Channel) GetChannelType() ChannelChannelType`

GetChannelType returns the ChannelType field if non-nil, zero value otherwise.

### GetChannelTypeOk

`func (o *Channel) GetChannelTypeOk() (*ChannelChannelType, bool)`

GetChannelTypeOk returns a tuple with the ChannelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannelType

`func (o *Channel) SetChannelType(v ChannelChannelType)`

SetChannelType sets ChannelType field to given value.

### HasChannelType

`func (o *Channel) HasChannelType() bool`

HasChannelType returns a boolean if a field has been set.

### GetAwsIotCoreChannelConfiguration

`func (o *Channel) GetAwsIotCoreChannelConfiguration() AwsIotCoreChannelConfiguration`

GetAwsIotCoreChannelConfiguration returns the AwsIotCoreChannelConfiguration field if non-nil, zero value otherwise.

### GetAwsIotCoreChannelConfigurationOk

`func (o *Channel) GetAwsIotCoreChannelConfigurationOk() (*AwsIotCoreChannelConfiguration, bool)`

GetAwsIotCoreChannelConfigurationOk returns a tuple with the AwsIotCoreChannelConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwsIotCoreChannelConfiguration

`func (o *Channel) SetAwsIotCoreChannelConfiguration(v AwsIotCoreChannelConfiguration)`

SetAwsIotCoreChannelConfiguration sets AwsIotCoreChannelConfiguration field to given value.

### HasAwsIotCoreChannelConfiguration

`func (o *Channel) HasAwsIotCoreChannelConfiguration() bool`

HasAwsIotCoreChannelConfiguration returns a boolean if a field has been set.

### GetWebhookChannelConfiguration

`func (o *Channel) GetWebhookChannelConfiguration() WebhookChannelConfiguration`

GetWebhookChannelConfiguration returns the WebhookChannelConfiguration field if non-nil, zero value otherwise.

### GetWebhookChannelConfigurationOk

`func (o *Channel) GetWebhookChannelConfigurationOk() (*WebhookChannelConfiguration, bool)`

GetWebhookChannelConfigurationOk returns a tuple with the WebhookChannelConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookChannelConfiguration

`func (o *Channel) SetWebhookChannelConfiguration(v WebhookChannelConfiguration)`

SetWebhookChannelConfiguration sets WebhookChannelConfiguration field to given value.

### HasWebhookChannelConfiguration

`func (o *Channel) HasWebhookChannelConfiguration() bool`

HasWebhookChannelConfiguration returns a boolean if a field has been set.

### GetAzureChannelConfiguration

`func (o *Channel) GetAzureChannelConfiguration() AzureChannelConfiguration`

GetAzureChannelConfiguration returns the AzureChannelConfiguration field if non-nil, zero value otherwise.

### GetAzureChannelConfigurationOk

`func (o *Channel) GetAzureChannelConfigurationOk() (*AzureChannelConfiguration, bool)`

GetAzureChannelConfigurationOk returns a tuple with the AzureChannelConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAzureChannelConfiguration

`func (o *Channel) SetAzureChannelConfiguration(v AzureChannelConfiguration)`

SetAzureChannelConfiguration sets AzureChannelConfiguration field to given value.

### HasAzureChannelConfiguration

`func (o *Channel) HasAzureChannelConfiguration() bool`

HasAzureChannelConfiguration returns a boolean if a field has been set.

### GetRestChannelConfiguration

`func (o *Channel) GetRestChannelConfiguration() map[string]interface{}`

GetRestChannelConfiguration returns the RestChannelConfiguration field if non-nil, zero value otherwise.

### GetRestChannelConfigurationOk

`func (o *Channel) GetRestChannelConfigurationOk() (*map[string]interface{}, bool)`

GetRestChannelConfigurationOk returns a tuple with the RestChannelConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestChannelConfiguration

`func (o *Channel) SetRestChannelConfiguration(v map[string]interface{})`

SetRestChannelConfiguration sets RestChannelConfiguration field to given value.

### HasRestChannelConfiguration

`func (o *Channel) HasRestChannelConfiguration() bool`

HasRestChannelConfiguration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


