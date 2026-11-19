# InterfaceBasicInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **float32** | Interface ID. | [optional] 
**Name** | Pointer to **string** | Interface name. | [optional] 
**Status** | Pointer to [**InterfaceBasicInfoResponseStatus**](InterfaceBasicInfoResponseStatus.md) |  | [optional] 
**OperationStatus** | Pointer to [**InterfaceBasicInfoResponseOperationStatus**](InterfaceBasicInfoResponseOperationStatus.md) |  | [optional] 
**MacAddress** | Pointer to **string** | MAC address. | [optional] 
**IpAddress** | Pointer to **string** | IP address. | [optional] 
**AssignedType** | Pointer to [**InterfaceBasicInfoResponseAssignedType**](InterfaceBasicInfoResponseAssignedType.md) |  | [optional] 
**Type** | Pointer to [**InterfaceBasicInfoResponseType**](InterfaceBasicInfoResponseType.md) |  | [optional] 

## Methods

### NewInterfaceBasicInfoResponse

`func NewInterfaceBasicInfoResponse() *InterfaceBasicInfoResponse`

NewInterfaceBasicInfoResponse instantiates a new InterfaceBasicInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInterfaceBasicInfoResponseWithDefaults

`func NewInterfaceBasicInfoResponseWithDefaults() *InterfaceBasicInfoResponse`

NewInterfaceBasicInfoResponseWithDefaults instantiates a new InterfaceBasicInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InterfaceBasicInfoResponse) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InterfaceBasicInfoResponse) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InterfaceBasicInfoResponse) SetId(v float32)`

SetId sets Id field to given value.

### HasId

`func (o *InterfaceBasicInfoResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *InterfaceBasicInfoResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InterfaceBasicInfoResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InterfaceBasicInfoResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InterfaceBasicInfoResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *InterfaceBasicInfoResponse) GetStatus() InterfaceBasicInfoResponseStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InterfaceBasicInfoResponse) GetStatusOk() (*InterfaceBasicInfoResponseStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InterfaceBasicInfoResponse) SetStatus(v InterfaceBasicInfoResponseStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InterfaceBasicInfoResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetOperationStatus

`func (o *InterfaceBasicInfoResponse) GetOperationStatus() InterfaceBasicInfoResponseOperationStatus`

GetOperationStatus returns the OperationStatus field if non-nil, zero value otherwise.

### GetOperationStatusOk

`func (o *InterfaceBasicInfoResponse) GetOperationStatusOk() (*InterfaceBasicInfoResponseOperationStatus, bool)`

GetOperationStatusOk returns a tuple with the OperationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationStatus

`func (o *InterfaceBasicInfoResponse) SetOperationStatus(v InterfaceBasicInfoResponseOperationStatus)`

SetOperationStatus sets OperationStatus field to given value.

### HasOperationStatus

`func (o *InterfaceBasicInfoResponse) HasOperationStatus() bool`

HasOperationStatus returns a boolean if a field has been set.

### GetMacAddress

`func (o *InterfaceBasicInfoResponse) GetMacAddress() string`

GetMacAddress returns the MacAddress field if non-nil, zero value otherwise.

### GetMacAddressOk

`func (o *InterfaceBasicInfoResponse) GetMacAddressOk() (*string, bool)`

GetMacAddressOk returns a tuple with the MacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacAddress

`func (o *InterfaceBasicInfoResponse) SetMacAddress(v string)`

SetMacAddress sets MacAddress field to given value.

### HasMacAddress

`func (o *InterfaceBasicInfoResponse) HasMacAddress() bool`

HasMacAddress returns a boolean if a field has been set.

### GetIpAddress

`func (o *InterfaceBasicInfoResponse) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *InterfaceBasicInfoResponse) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *InterfaceBasicInfoResponse) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *InterfaceBasicInfoResponse) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.

### GetAssignedType

`func (o *InterfaceBasicInfoResponse) GetAssignedType() InterfaceBasicInfoResponseAssignedType`

GetAssignedType returns the AssignedType field if non-nil, zero value otherwise.

### GetAssignedTypeOk

`func (o *InterfaceBasicInfoResponse) GetAssignedTypeOk() (*InterfaceBasicInfoResponseAssignedType, bool)`

GetAssignedTypeOk returns a tuple with the AssignedType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedType

`func (o *InterfaceBasicInfoResponse) SetAssignedType(v InterfaceBasicInfoResponseAssignedType)`

SetAssignedType sets AssignedType field to given value.

### HasAssignedType

`func (o *InterfaceBasicInfoResponse) HasAssignedType() bool`

HasAssignedType returns a boolean if a field has been set.

### GetType

`func (o *InterfaceBasicInfoResponse) GetType() InterfaceBasicInfoResponseType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InterfaceBasicInfoResponse) GetTypeOk() (*InterfaceBasicInfoResponseType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InterfaceBasicInfoResponse) SetType(v InterfaceBasicInfoResponseType)`

SetType sets Type field to given value.

### HasType

`func (o *InterfaceBasicInfoResponse) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


