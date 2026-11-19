# QuoteDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineId** | Pointer to **string** | Unique identifier associated with line item. | [optional] 
**ParentLineId** | Pointer to **string** | Unique identifier associated with &#x60;lineId&#x60; to denote hierarchy of the product. When this field is null, item is at root level. | [optional] 
**RootLineId** | Pointer to **string** | Unique identifier to specify root item. Useful when product order hierarchy exceeds 2. | [optional] 
**Ibx** | Pointer to **string** | Location code of Equinix datacenter | [optional] 
**Cage** | Pointer to **string** | Cage ID | [optional] 
**ProductDescription** | Pointer to **string** | Description of the product.  | [optional] 
**ProductType** | Pointer to [**QuoteDetailsProductType**](QuoteDetailsProductType.md) |  | [optional] 
**ProductCode** | Pointer to **string** | Equinix Product catalog code. | [optional] 
**ProductName** | Pointer to **string** | Product name | [optional] 
**Assetizable** | Pointer to **bool** | When this value is &#x60;true&#x60;, line item is assetizable. | [optional] 
**LineItemModified** | Pointer to **bool** | When this value is &#x60;true&#x60;, it means there are changes to POE. | [optional] 
**Quantity** | Pointer to **float32** | The total amount of quantity bought. To be used with &#x60;unitOfMeasure&#x60; to derive value | [optional] 
**UnitOfMeasure** | Pointer to [**QuoteDetailsUnitOfMeasure**](QuoteDetailsUnitOfMeasure.md) |  | [optional] 
**UnitPricing** | Pointer to [**[]PricingDetails**](PricingDetails.md) |  | [optional] 
**TotalPricing** | Pointer to [**[]PricingDetails**](PricingDetails.md) |  | [optional] 
**RequestType** | Pointer to [**QuoteDetailsRequestType**](QuoteDetailsRequestType.md) |  | [optional] 
**AdditionalInfo** | Pointer to [**[]QuoteDetailsAdditionalInfoInner**](QuoteDetailsAdditionalInfoInner.md) | This section is reserved to display product specific information | [optional] 

## Methods

### NewQuoteDetails

`func NewQuoteDetails() *QuoteDetails`

NewQuoteDetails instantiates a new QuoteDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteDetailsWithDefaults

`func NewQuoteDetailsWithDefaults() *QuoteDetails`

NewQuoteDetailsWithDefaults instantiates a new QuoteDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineId

`func (o *QuoteDetails) GetLineId() string`

GetLineId returns the LineId field if non-nil, zero value otherwise.

### GetLineIdOk

`func (o *QuoteDetails) GetLineIdOk() (*string, bool)`

GetLineIdOk returns a tuple with the LineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineId

`func (o *QuoteDetails) SetLineId(v string)`

SetLineId sets LineId field to given value.

### HasLineId

`func (o *QuoteDetails) HasLineId() bool`

HasLineId returns a boolean if a field has been set.

### GetParentLineId

`func (o *QuoteDetails) GetParentLineId() string`

GetParentLineId returns the ParentLineId field if non-nil, zero value otherwise.

### GetParentLineIdOk

`func (o *QuoteDetails) GetParentLineIdOk() (*string, bool)`

GetParentLineIdOk returns a tuple with the ParentLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentLineId

`func (o *QuoteDetails) SetParentLineId(v string)`

SetParentLineId sets ParentLineId field to given value.

### HasParentLineId

`func (o *QuoteDetails) HasParentLineId() bool`

HasParentLineId returns a boolean if a field has been set.

### GetRootLineId

`func (o *QuoteDetails) GetRootLineId() string`

GetRootLineId returns the RootLineId field if non-nil, zero value otherwise.

### GetRootLineIdOk

`func (o *QuoteDetails) GetRootLineIdOk() (*string, bool)`

GetRootLineIdOk returns a tuple with the RootLineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRootLineId

`func (o *QuoteDetails) SetRootLineId(v string)`

SetRootLineId sets RootLineId field to given value.

### HasRootLineId

`func (o *QuoteDetails) HasRootLineId() bool`

HasRootLineId returns a boolean if a field has been set.

### GetIbx

`func (o *QuoteDetails) GetIbx() string`

GetIbx returns the Ibx field if non-nil, zero value otherwise.

### GetIbxOk

`func (o *QuoteDetails) GetIbxOk() (*string, bool)`

GetIbxOk returns a tuple with the Ibx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIbx

`func (o *QuoteDetails) SetIbx(v string)`

SetIbx sets Ibx field to given value.

### HasIbx

`func (o *QuoteDetails) HasIbx() bool`

HasIbx returns a boolean if a field has been set.

### GetCage

`func (o *QuoteDetails) GetCage() string`

GetCage returns the Cage field if non-nil, zero value otherwise.

### GetCageOk

`func (o *QuoteDetails) GetCageOk() (*string, bool)`

GetCageOk returns a tuple with the Cage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCage

`func (o *QuoteDetails) SetCage(v string)`

SetCage sets Cage field to given value.

### HasCage

`func (o *QuoteDetails) HasCage() bool`

HasCage returns a boolean if a field has been set.

### GetProductDescription

`func (o *QuoteDetails) GetProductDescription() string`

GetProductDescription returns the ProductDescription field if non-nil, zero value otherwise.

### GetProductDescriptionOk

`func (o *QuoteDetails) GetProductDescriptionOk() (*string, bool)`

GetProductDescriptionOk returns a tuple with the ProductDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductDescription

`func (o *QuoteDetails) SetProductDescription(v string)`

SetProductDescription sets ProductDescription field to given value.

### HasProductDescription

`func (o *QuoteDetails) HasProductDescription() bool`

HasProductDescription returns a boolean if a field has been set.

### GetProductType

`func (o *QuoteDetails) GetProductType() QuoteDetailsProductType`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *QuoteDetails) GetProductTypeOk() (*QuoteDetailsProductType, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *QuoteDetails) SetProductType(v QuoteDetailsProductType)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *QuoteDetails) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### GetProductCode

`func (o *QuoteDetails) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *QuoteDetails) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *QuoteDetails) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.

### HasProductCode

`func (o *QuoteDetails) HasProductCode() bool`

HasProductCode returns a boolean if a field has been set.

### GetProductName

`func (o *QuoteDetails) GetProductName() string`

GetProductName returns the ProductName field if non-nil, zero value otherwise.

### GetProductNameOk

`func (o *QuoteDetails) GetProductNameOk() (*string, bool)`

GetProductNameOk returns a tuple with the ProductName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductName

`func (o *QuoteDetails) SetProductName(v string)`

SetProductName sets ProductName field to given value.

### HasProductName

`func (o *QuoteDetails) HasProductName() bool`

HasProductName returns a boolean if a field has been set.

### GetAssetizable

`func (o *QuoteDetails) GetAssetizable() bool`

GetAssetizable returns the Assetizable field if non-nil, zero value otherwise.

### GetAssetizableOk

`func (o *QuoteDetails) GetAssetizableOk() (*bool, bool)`

GetAssetizableOk returns a tuple with the Assetizable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetizable

`func (o *QuoteDetails) SetAssetizable(v bool)`

SetAssetizable sets Assetizable field to given value.

### HasAssetizable

`func (o *QuoteDetails) HasAssetizable() bool`

HasAssetizable returns a boolean if a field has been set.

### GetLineItemModified

`func (o *QuoteDetails) GetLineItemModified() bool`

GetLineItemModified returns the LineItemModified field if non-nil, zero value otherwise.

### GetLineItemModifiedOk

`func (o *QuoteDetails) GetLineItemModifiedOk() (*bool, bool)`

GetLineItemModifiedOk returns a tuple with the LineItemModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItemModified

`func (o *QuoteDetails) SetLineItemModified(v bool)`

SetLineItemModified sets LineItemModified field to given value.

### HasLineItemModified

`func (o *QuoteDetails) HasLineItemModified() bool`

HasLineItemModified returns a boolean if a field has been set.

### GetQuantity

`func (o *QuoteDetails) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *QuoteDetails) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *QuoteDetails) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.

### HasQuantity

`func (o *QuoteDetails) HasQuantity() bool`

HasQuantity returns a boolean if a field has been set.

### GetUnitOfMeasure

`func (o *QuoteDetails) GetUnitOfMeasure() QuoteDetailsUnitOfMeasure`

GetUnitOfMeasure returns the UnitOfMeasure field if non-nil, zero value otherwise.

### GetUnitOfMeasureOk

`func (o *QuoteDetails) GetUnitOfMeasureOk() (*QuoteDetailsUnitOfMeasure, bool)`

GetUnitOfMeasureOk returns a tuple with the UnitOfMeasure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitOfMeasure

`func (o *QuoteDetails) SetUnitOfMeasure(v QuoteDetailsUnitOfMeasure)`

SetUnitOfMeasure sets UnitOfMeasure field to given value.

### HasUnitOfMeasure

`func (o *QuoteDetails) HasUnitOfMeasure() bool`

HasUnitOfMeasure returns a boolean if a field has been set.

### GetUnitPricing

`func (o *QuoteDetails) GetUnitPricing() []PricingDetails`

GetUnitPricing returns the UnitPricing field if non-nil, zero value otherwise.

### GetUnitPricingOk

`func (o *QuoteDetails) GetUnitPricingOk() (*[]PricingDetails, bool)`

GetUnitPricingOk returns a tuple with the UnitPricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPricing

`func (o *QuoteDetails) SetUnitPricing(v []PricingDetails)`

SetUnitPricing sets UnitPricing field to given value.

### HasUnitPricing

`func (o *QuoteDetails) HasUnitPricing() bool`

HasUnitPricing returns a boolean if a field has been set.

### GetTotalPricing

`func (o *QuoteDetails) GetTotalPricing() []PricingDetails`

GetTotalPricing returns the TotalPricing field if non-nil, zero value otherwise.

### GetTotalPricingOk

`func (o *QuoteDetails) GetTotalPricingOk() (*[]PricingDetails, bool)`

GetTotalPricingOk returns a tuple with the TotalPricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPricing

`func (o *QuoteDetails) SetTotalPricing(v []PricingDetails)`

SetTotalPricing sets TotalPricing field to given value.

### HasTotalPricing

`func (o *QuoteDetails) HasTotalPricing() bool`

HasTotalPricing returns a boolean if a field has been set.

### GetRequestType

`func (o *QuoteDetails) GetRequestType() QuoteDetailsRequestType`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *QuoteDetails) GetRequestTypeOk() (*QuoteDetailsRequestType, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *QuoteDetails) SetRequestType(v QuoteDetailsRequestType)`

SetRequestType sets RequestType field to given value.

### HasRequestType

`func (o *QuoteDetails) HasRequestType() bool`

HasRequestType returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *QuoteDetails) GetAdditionalInfo() []QuoteDetailsAdditionalInfoInner`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *QuoteDetails) GetAdditionalInfoOk() (*[]QuoteDetailsAdditionalInfoInner, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *QuoteDetails) SetAdditionalInfo(v []QuoteDetailsAdditionalInfoInner)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *QuoteDetails) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


