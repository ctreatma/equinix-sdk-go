# SingleCaseResponseV2OtherDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContactUCMID** | Pointer to **string** |  | [optional] 
**RecordType** | Pointer to [**SingleCaseResponseV2OtherDetailsRecordType**](SingleCaseResponseV2OtherDetailsRecordType.md) |  | [optional] 
**SubChannel** | Pointer to [**SingleCaseResponseV2OtherDetailsSubChannel**](SingleCaseResponseV2OtherDetailsSubChannel.md) |  | [optional] 
**FinalScheduledDate** | Pointer to **time.Time** | A datetime string with format YYYY-MM-DDTHH:mm:ss.sssZ. | [optional] 
**Category** | Pointer to **string** |  | [optional] 
**SubCategory** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** | A datetime string with format YYYY-MM-DDTHH:mm:ss.sssZ. | [optional] 
**UpdatedByFullName** | Pointer to **string** |  | [optional] 
**RequestedTerminationDate** | Pointer to **string** |  | [optional] 
**StatusHistory** | Pointer to [**[]SingleCaseResponseV2OtherDetailsStatusHistoryInner**](SingleCaseResponseV2OtherDetailsStatusHistoryInner.md) |  | [optional] 
**PurchaseOrders** | Pointer to **[]string** |  | [optional] 
**Products** | Pointer to **[]string** |  | [optional] 
**ProductOfferingCodes** | Pointer to **[]string** |  | [optional] 
**Details** | Pointer to [**[]SingleCaseResponseV2OtherDetailsDetailsInner**](SingleCaseResponseV2OtherDetailsDetailsInner.md) |  | [optional] 
**AdditionalInfo** | Pointer to [**[]SingleCaseResponseV2OtherDetailsAdditionalInfoInner**](SingleCaseResponseV2OtherDetailsAdditionalInfoInner.md) |  | [optional] 
**Modifiable** | Pointer to **bool** |  | [optional] 
**ReOpen** | Pointer to **bool** |  | [optional] 
**Cancellable** | Pointer to **bool** |  | [optional] 
**Respond** | Pointer to **bool** |  | [optional] 

## Methods

### NewSingleCaseResponseV2OtherDetails

`func NewSingleCaseResponseV2OtherDetails() *SingleCaseResponseV2OtherDetails`

NewSingleCaseResponseV2OtherDetails instantiates a new SingleCaseResponseV2OtherDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSingleCaseResponseV2OtherDetailsWithDefaults

`func NewSingleCaseResponseV2OtherDetailsWithDefaults() *SingleCaseResponseV2OtherDetails`

NewSingleCaseResponseV2OtherDetailsWithDefaults instantiates a new SingleCaseResponseV2OtherDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContactUCMID

`func (o *SingleCaseResponseV2OtherDetails) GetContactUCMID() string`

GetContactUCMID returns the ContactUCMID field if non-nil, zero value otherwise.

### GetContactUCMIDOk

`func (o *SingleCaseResponseV2OtherDetails) GetContactUCMIDOk() (*string, bool)`

GetContactUCMIDOk returns a tuple with the ContactUCMID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactUCMID

`func (o *SingleCaseResponseV2OtherDetails) SetContactUCMID(v string)`

SetContactUCMID sets ContactUCMID field to given value.

### HasContactUCMID

`func (o *SingleCaseResponseV2OtherDetails) HasContactUCMID() bool`

HasContactUCMID returns a boolean if a field has been set.

### GetRecordType

`func (o *SingleCaseResponseV2OtherDetails) GetRecordType() SingleCaseResponseV2OtherDetailsRecordType`

GetRecordType returns the RecordType field if non-nil, zero value otherwise.

### GetRecordTypeOk

`func (o *SingleCaseResponseV2OtherDetails) GetRecordTypeOk() (*SingleCaseResponseV2OtherDetailsRecordType, bool)`

GetRecordTypeOk returns a tuple with the RecordType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordType

`func (o *SingleCaseResponseV2OtherDetails) SetRecordType(v SingleCaseResponseV2OtherDetailsRecordType)`

SetRecordType sets RecordType field to given value.

### HasRecordType

`func (o *SingleCaseResponseV2OtherDetails) HasRecordType() bool`

HasRecordType returns a boolean if a field has been set.

### GetSubChannel

`func (o *SingleCaseResponseV2OtherDetails) GetSubChannel() SingleCaseResponseV2OtherDetailsSubChannel`

GetSubChannel returns the SubChannel field if non-nil, zero value otherwise.

### GetSubChannelOk

`func (o *SingleCaseResponseV2OtherDetails) GetSubChannelOk() (*SingleCaseResponseV2OtherDetailsSubChannel, bool)`

GetSubChannelOk returns a tuple with the SubChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubChannel

`func (o *SingleCaseResponseV2OtherDetails) SetSubChannel(v SingleCaseResponseV2OtherDetailsSubChannel)`

SetSubChannel sets SubChannel field to given value.

### HasSubChannel

`func (o *SingleCaseResponseV2OtherDetails) HasSubChannel() bool`

HasSubChannel returns a boolean if a field has been set.

### GetFinalScheduledDate

`func (o *SingleCaseResponseV2OtherDetails) GetFinalScheduledDate() time.Time`

GetFinalScheduledDate returns the FinalScheduledDate field if non-nil, zero value otherwise.

### GetFinalScheduledDateOk

`func (o *SingleCaseResponseV2OtherDetails) GetFinalScheduledDateOk() (*time.Time, bool)`

GetFinalScheduledDateOk returns a tuple with the FinalScheduledDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalScheduledDate

`func (o *SingleCaseResponseV2OtherDetails) SetFinalScheduledDate(v time.Time)`

SetFinalScheduledDate sets FinalScheduledDate field to given value.

### HasFinalScheduledDate

`func (o *SingleCaseResponseV2OtherDetails) HasFinalScheduledDate() bool`

HasFinalScheduledDate returns a boolean if a field has been set.

### GetCategory

`func (o *SingleCaseResponseV2OtherDetails) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *SingleCaseResponseV2OtherDetails) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *SingleCaseResponseV2OtherDetails) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *SingleCaseResponseV2OtherDetails) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetSubCategory

`func (o *SingleCaseResponseV2OtherDetails) GetSubCategory() string`

GetSubCategory returns the SubCategory field if non-nil, zero value otherwise.

### GetSubCategoryOk

`func (o *SingleCaseResponseV2OtherDetails) GetSubCategoryOk() (*string, bool)`

GetSubCategoryOk returns a tuple with the SubCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubCategory

`func (o *SingleCaseResponseV2OtherDetails) SetSubCategory(v string)`

SetSubCategory sets SubCategory field to given value.

### HasSubCategory

`func (o *SingleCaseResponseV2OtherDetails) HasSubCategory() bool`

HasSubCategory returns a boolean if a field has been set.

### GetDescription

`func (o *SingleCaseResponseV2OtherDetails) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SingleCaseResponseV2OtherDetails) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SingleCaseResponseV2OtherDetails) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SingleCaseResponseV2OtherDetails) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetails) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *SingleCaseResponseV2OtherDetails) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetails) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *SingleCaseResponseV2OtherDetails) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetUpdatedByFullName

`func (o *SingleCaseResponseV2OtherDetails) GetUpdatedByFullName() string`

GetUpdatedByFullName returns the UpdatedByFullName field if non-nil, zero value otherwise.

### GetUpdatedByFullNameOk

`func (o *SingleCaseResponseV2OtherDetails) GetUpdatedByFullNameOk() (*string, bool)`

GetUpdatedByFullNameOk returns a tuple with the UpdatedByFullName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedByFullName

`func (o *SingleCaseResponseV2OtherDetails) SetUpdatedByFullName(v string)`

SetUpdatedByFullName sets UpdatedByFullName field to given value.

### HasUpdatedByFullName

`func (o *SingleCaseResponseV2OtherDetails) HasUpdatedByFullName() bool`

HasUpdatedByFullName returns a boolean if a field has been set.

### GetRequestedTerminationDate

`func (o *SingleCaseResponseV2OtherDetails) GetRequestedTerminationDate() string`

GetRequestedTerminationDate returns the RequestedTerminationDate field if non-nil, zero value otherwise.

### GetRequestedTerminationDateOk

`func (o *SingleCaseResponseV2OtherDetails) GetRequestedTerminationDateOk() (*string, bool)`

GetRequestedTerminationDateOk returns a tuple with the RequestedTerminationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedTerminationDate

`func (o *SingleCaseResponseV2OtherDetails) SetRequestedTerminationDate(v string)`

SetRequestedTerminationDate sets RequestedTerminationDate field to given value.

### HasRequestedTerminationDate

`func (o *SingleCaseResponseV2OtherDetails) HasRequestedTerminationDate() bool`

HasRequestedTerminationDate returns a boolean if a field has been set.

### GetStatusHistory

`func (o *SingleCaseResponseV2OtherDetails) GetStatusHistory() []SingleCaseResponseV2OtherDetailsStatusHistoryInner`

GetStatusHistory returns the StatusHistory field if non-nil, zero value otherwise.

### GetStatusHistoryOk

`func (o *SingleCaseResponseV2OtherDetails) GetStatusHistoryOk() (*[]SingleCaseResponseV2OtherDetailsStatusHistoryInner, bool)`

GetStatusHistoryOk returns a tuple with the StatusHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusHistory

`func (o *SingleCaseResponseV2OtherDetails) SetStatusHistory(v []SingleCaseResponseV2OtherDetailsStatusHistoryInner)`

SetStatusHistory sets StatusHistory field to given value.

### HasStatusHistory

`func (o *SingleCaseResponseV2OtherDetails) HasStatusHistory() bool`

HasStatusHistory returns a boolean if a field has been set.

### GetPurchaseOrders

`func (o *SingleCaseResponseV2OtherDetails) GetPurchaseOrders() []string`

GetPurchaseOrders returns the PurchaseOrders field if non-nil, zero value otherwise.

### GetPurchaseOrdersOk

`func (o *SingleCaseResponseV2OtherDetails) GetPurchaseOrdersOk() (*[]string, bool)`

GetPurchaseOrdersOk returns a tuple with the PurchaseOrders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchaseOrders

`func (o *SingleCaseResponseV2OtherDetails) SetPurchaseOrders(v []string)`

SetPurchaseOrders sets PurchaseOrders field to given value.

### HasPurchaseOrders

`func (o *SingleCaseResponseV2OtherDetails) HasPurchaseOrders() bool`

HasPurchaseOrders returns a boolean if a field has been set.

### GetProducts

`func (o *SingleCaseResponseV2OtherDetails) GetProducts() []string`

GetProducts returns the Products field if non-nil, zero value otherwise.

### GetProductsOk

`func (o *SingleCaseResponseV2OtherDetails) GetProductsOk() (*[]string, bool)`

GetProductsOk returns a tuple with the Products field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducts

`func (o *SingleCaseResponseV2OtherDetails) SetProducts(v []string)`

SetProducts sets Products field to given value.

### HasProducts

`func (o *SingleCaseResponseV2OtherDetails) HasProducts() bool`

HasProducts returns a boolean if a field has been set.

### GetProductOfferingCodes

`func (o *SingleCaseResponseV2OtherDetails) GetProductOfferingCodes() []string`

GetProductOfferingCodes returns the ProductOfferingCodes field if non-nil, zero value otherwise.

### GetProductOfferingCodesOk

`func (o *SingleCaseResponseV2OtherDetails) GetProductOfferingCodesOk() (*[]string, bool)`

GetProductOfferingCodesOk returns a tuple with the ProductOfferingCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductOfferingCodes

`func (o *SingleCaseResponseV2OtherDetails) SetProductOfferingCodes(v []string)`

SetProductOfferingCodes sets ProductOfferingCodes field to given value.

### HasProductOfferingCodes

`func (o *SingleCaseResponseV2OtherDetails) HasProductOfferingCodes() bool`

HasProductOfferingCodes returns a boolean if a field has been set.

### GetDetails

`func (o *SingleCaseResponseV2OtherDetails) GetDetails() []SingleCaseResponseV2OtherDetailsDetailsInner`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *SingleCaseResponseV2OtherDetails) GetDetailsOk() (*[]SingleCaseResponseV2OtherDetailsDetailsInner, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *SingleCaseResponseV2OtherDetails) SetDetails(v []SingleCaseResponseV2OtherDetailsDetailsInner)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *SingleCaseResponseV2OtherDetails) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetails) GetAdditionalInfo() []SingleCaseResponseV2OtherDetailsAdditionalInfoInner`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *SingleCaseResponseV2OtherDetails) GetAdditionalInfoOk() (*[]SingleCaseResponseV2OtherDetailsAdditionalInfoInner, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetails) SetAdditionalInfo(v []SingleCaseResponseV2OtherDetailsAdditionalInfoInner)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *SingleCaseResponseV2OtherDetails) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.

### GetModifiable

`func (o *SingleCaseResponseV2OtherDetails) GetModifiable() bool`

GetModifiable returns the Modifiable field if non-nil, zero value otherwise.

### GetModifiableOk

`func (o *SingleCaseResponseV2OtherDetails) GetModifiableOk() (*bool, bool)`

GetModifiableOk returns a tuple with the Modifiable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiable

`func (o *SingleCaseResponseV2OtherDetails) SetModifiable(v bool)`

SetModifiable sets Modifiable field to given value.

### HasModifiable

`func (o *SingleCaseResponseV2OtherDetails) HasModifiable() bool`

HasModifiable returns a boolean if a field has been set.

### GetReOpen

`func (o *SingleCaseResponseV2OtherDetails) GetReOpen() bool`

GetReOpen returns the ReOpen field if non-nil, zero value otherwise.

### GetReOpenOk

`func (o *SingleCaseResponseV2OtherDetails) GetReOpenOk() (*bool, bool)`

GetReOpenOk returns a tuple with the ReOpen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReOpen

`func (o *SingleCaseResponseV2OtherDetails) SetReOpen(v bool)`

SetReOpen sets ReOpen field to given value.

### HasReOpen

`func (o *SingleCaseResponseV2OtherDetails) HasReOpen() bool`

HasReOpen returns a boolean if a field has been set.

### GetCancellable

`func (o *SingleCaseResponseV2OtherDetails) GetCancellable() bool`

GetCancellable returns the Cancellable field if non-nil, zero value otherwise.

### GetCancellableOk

`func (o *SingleCaseResponseV2OtherDetails) GetCancellableOk() (*bool, bool)`

GetCancellableOk returns a tuple with the Cancellable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellable

`func (o *SingleCaseResponseV2OtherDetails) SetCancellable(v bool)`

SetCancellable sets Cancellable field to given value.

### HasCancellable

`func (o *SingleCaseResponseV2OtherDetails) HasCancellable() bool`

HasCancellable returns a boolean if a field has been set.

### GetRespond

`func (o *SingleCaseResponseV2OtherDetails) GetRespond() bool`

GetRespond returns the Respond field if non-nil, zero value otherwise.

### GetRespondOk

`func (o *SingleCaseResponseV2OtherDetails) GetRespondOk() (*bool, bool)`

GetRespondOk returns a tuple with the Respond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRespond

`func (o *SingleCaseResponseV2OtherDetails) SetRespond(v bool)`

SetRespond sets Respond field to given value.

### HasRespond

`func (o *SingleCaseResponseV2OtherDetails) HasRespond() bool`

HasRespond returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


