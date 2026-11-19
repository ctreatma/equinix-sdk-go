# SingleCaseResponseV2OtherDetailsDetailsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** |  | [optional] 
**ParentLineId** | Pointer to **string** |  | [optional] 
**ProductType** | Pointer to [**SingleCaseResponseV2OtherDetailsDetailsInnerProductType**](SingleCaseResponseV2OtherDetailsDetailsInnerProductType.md) |  | [optional] 
**ProductOfferingCode** | Pointer to **string** |  | [optional] 
**ProductCode** | Pointer to **string** |  | [optional] 
**ProductName** | Pointer to **string** |  | [optional] 
**Status** | Pointer to [**SingleCaseResponseV2OtherDetailsDetailsInnerStatus**](SingleCaseResponseV2OtherDetailsDetailsInnerStatus.md) |  | [optional] 
**ReOpen** | Pointer to **string** |  | [optional] 
**Respond** | Pointer to **bool** |  | [optional] 
**Ibx** | Pointer to **string** |  | [optional] 
**Cage** | Pointer to **string** |  | [optional] 
**RequestType** | Pointer to [**SingleCaseResponseV2OtherDetailsDetailsInnerRequestType**](SingleCaseResponseV2OtherDetailsDetailsInnerRequestType.md) |  | [optional] 
**ActivityId** | Pointer to **string** |  | [optional] 
**PurchaseOrder** | Pointer to **map[string]interface{}** |  | [optional] 
**EstimatedCompletion** | Pointer to [**SingleCaseResponseV2OtherDetailsDetailsInnerEstimatedCompletion**](SingleCaseResponseV2OtherDetailsDetailsInnerEstimatedCompletion.md) |  | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** |  | [optional] 
**AdditionalInfo** | Pointer to [**[]SingleCaseResponseV2OtherDetailsDetailsInnerAdditionalInfoInner**](SingleCaseResponseV2OtherDetailsDetailsInnerAdditionalInfoInner.md) |  | [optional] 
**Modifiable** | Pointer to **bool** |  | [optional] 
**Cancellable** | Pointer to **bool** |  | [optional] 

## Methods

### NewSingleCaseResponseV2OtherDetailsDetailsInner

`func NewSingleCaseResponseV2OtherDetailsDetailsInner() *SingleCaseResponseV2OtherDetailsDetailsInner`

NewSingleCaseResponseV2OtherDetailsDetailsInner instantiates a new SingleCaseResponseV2OtherDetailsDetailsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSingleCaseResponseV2OtherDetailsDetailsInnerWithDefaults

`func NewSingleCaseResponseV2OtherDetailsDetailsInnerWithDefaults() *SingleCaseResponseV2OtherDetailsDetailsInner`

NewSingleCaseResponseV2OtherDetailsDetailsInnerWithDefaults instantiates a new SingleCaseResponseV2OtherDetailsDetailsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetParentLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetParentLineId() string`

GetParentLineId returns the ParentLineId field if non-nil, zero value otherwise.

### GetParentLineIdOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetParentLineIdOk() (*string, bool)`

GetParentLineIdOk returns a tuple with the ParentLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetParentLineId(v string)`

SetParentLineId sets ParentLineId field to given value.

### HasParentLineId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasParentLineId() bool`

HasParentLineId returns a boolean if a field has been set.

### GetProductType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductType() SingleCaseResponseV2OtherDetailsDetailsInnerProductType`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductTypeOk() (*SingleCaseResponseV2OtherDetailsDetailsInnerProductType, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetProductType(v SingleCaseResponseV2OtherDetailsDetailsInnerProductType)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetProductOfferingCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductOfferingCode() string`

GetProductOfferingCode returns the ProductOfferingCode field if non-nil, zero value otherwise.

### GetProductOfferingCodeOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductOfferingCodeOk() (*string, bool)`

GetProductOfferingCodeOk returns a tuple with the ProductOfferingCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductOfferingCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetProductOfferingCode(v string)`

SetProductOfferingCode sets ProductOfferingCode field to given value.

### HasProductOfferingCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasProductOfferingCode() bool`

HasProductOfferingCode returns a boolean if a field has been set.

### GetProductCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.

### HasProductCode

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasProductCode() bool`

HasProductCode returns a boolean if a field has been set.

### GetProductName

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### GetStatus

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetStatus() SingleCaseResponseV2OtherDetailsDetailsInnerStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetStatusOk() (*SingleCaseResponseV2OtherDetailsDetailsInnerStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetStatus(v SingleCaseResponseV2OtherDetailsDetailsInnerStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetReOpen

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetReOpen() string`

GetReOpen returns the ReOpen field if non-nil, zero value otherwise.

### GetReOpenOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetReOpenOk() (*string, bool)`

GetReOpenOk returns a tuple with the ReOpen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReOpen

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetReOpen(v string)`

SetReOpen sets ReOpen field to given value.

### HasReOpen

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasReOpen() bool`

HasReOpen returns a boolean if a field has been set.

### GetRespond

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetRespond() bool`

GetRespond returns the Respond field if non-nil, zero value otherwise.

### GetRespondOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetRespondOk() (*bool, bool)`

GetRespondOk returns a tuple with the Respond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRespond

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetRespond(v bool)`

SetRespond sets Respond field to given value.

### HasRespond

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasRespond() bool`

HasRespond returns a boolean if a field has been set.

### GetIbx

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetCage

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetCage(v string)`

SetCage sets Cage field to given value.

### HasCage

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasCage() bool`

HasCage returns a boolean if a field has been set.

### GetRequestType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetRequestType() SingleCaseResponseV2OtherDetailsDetailsInnerRequestType`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetRequestTypeOk() (*SingleCaseResponseV2OtherDetailsDetailsInnerRequestType, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetRequestType(v SingleCaseResponseV2OtherDetailsDetailsInnerRequestType)`

SetRequestType sets RequestType field to given value.

### HasRequestType

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasRequestType() bool`

HasRequestType returns a boolean if a field has been set.

### GetActivityId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetActivityId() string`

GetActivityId returns the ActivityId field if non-nil, zero value otherwise.

### GetActivityIdOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetActivityIdOk() (*string, bool)`

GetActivityIdOk returns a tuple with the ActivityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetActivityId(v string)`

SetActivityId sets ActivityId field to given value.

### HasActivityId

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasActivityId() bool`

HasActivityId returns a boolean if a field has been set.

### GetPurchaseOrder

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetPurchaseOrder() map[string]interface{}`

GetPurchaseOrder returns the PurchaseOrder field if non-nil, zero value otherwise.

### GetPurchaseOrderOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetPurchaseOrderOk() (*map[string]interface{}, bool)`

GetPurchaseOrderOk returns a tuple with the PurchaseOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrder

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetPurchaseOrder(v map[string]interface{})`

SetPurchaseOrder sets PurchaseOrder field to given value.

### HasPurchaseOrder

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasPurchaseOrder() bool`

HasPurchaseOrder returns a boolean if a field has been set.

### GetEstimatedCompletion

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetEstimatedCompletion() SingleCaseResponseV2OtherDetailsDetailsInnerEstimatedCompletion`

GetEstimatedCompletion returns the EstimatedCompletion field if non-nil, zero value otherwise.

### GetEstimatedCompletionOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetEstimatedCompletionOk() (*SingleCaseResponseV2OtherDetailsDetailsInnerEstimatedCompletion, bool)`

GetEstimatedCompletionOk returns a tuple with the EstimatedCompletion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCompletion

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetEstimatedCompletion(v SingleCaseResponseV2OtherDetailsDetailsInnerEstimatedCompletion)`

SetEstimatedCompletion sets EstimatedCompletion field to given value.

### HasEstimatedCompletion

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasEstimatedCompletion() bool`

HasEstimatedCompletion returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetAdditionalInfo() []SingleCaseResponseV2OtherDetailsDetailsInnerAdditionalInfoInner`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetAdditionalInfoOk() (*[]SingleCaseResponseV2OtherDetailsDetailsInnerAdditionalInfoInner, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetAdditionalInfo(v []SingleCaseResponseV2OtherDetailsDetailsInnerAdditionalInfoInner)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.

### GetModifiable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetModifiable() bool`

GetModifiable returns the Modifiable field if non-nil, zero value otherwise.

### GetModifiableOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetModifiableOk() (*bool, bool)`

GetModifiableOk returns a tuple with the Modifiable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetModifiable(v bool)`

SetModifiable sets Modifiable field to given value.

### HasModifiable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasModifiable() bool`

HasModifiable returns a boolean if a field has been set.

### GetCancellable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetCancellable() bool`

GetCancellable returns the Cancellable field if non-nil, zero value otherwise.

### GetCancellableOk

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) GetCancellableOk() (*bool, bool)`

GetCancellableOk returns a tuple with the Cancellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) SetCancellable(v bool)`

SetCancellable sets Cancellable field to given value.

### HasCancellable

`func (o *SingleCaseResponseV2OtherDetailsDetailsInner) HasCancellable() bool`

HasCancellable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


