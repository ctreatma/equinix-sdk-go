# PriceSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Charges** | [**[]PriceCharge**](PriceCharge.md) |  | 
**TotalCharge** | [**TotalCharge**](TotalCharge.md) |  | 

## Methods

### NewPriceSummary

`func NewPriceSummary(charges []PriceCharge, totalCharge TotalCharge, ) *PriceSummary`

NewPriceSummary instantiates a new PriceSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceSummaryWithDefaults

`func NewPriceSummaryWithDefaults() *PriceSummary`

NewPriceSummaryWithDefaults instantiates a new PriceSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCharges

`func (o *PriceSummary) GetCharges() []PriceCharge`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *PriceSummary) GetChargesOk() (*[]PriceCharge, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *PriceSummary) SetCharges(v []PriceCharge)`

SetCharges sets Charges field to given value.


### GetTotalCharge

`func (o *PriceSummary) GetTotalCharge() TotalCharge`

GetTotalCharge returns the TotalCharge field if non-nil, zero value otherwise.

### GetTotalChargeOk

`func (o *PriceSummary) GetTotalChargeOk() (*TotalCharge, bool)`

GetTotalChargeOk returns a tuple with the TotalCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCharge

`func (o *PriceSummary) SetTotalCharge(v TotalCharge)`

SetTotalCharge sets TotalCharge field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


