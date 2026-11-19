# QuoteResponseBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QuoteId** | Pointer to **string** | Equinix quote ID.  | [optional] 
**AccountName** | Pointer to **string** | Customer account name | [optional] 
**AccountNumber** | Pointer to **string** | Customer account number | [optional] 
**QuoteRequestType** | Pointer to [**QuoteResponseBaseQuoteRequestType**](QuoteResponseBaseQuoteRequestType.md) |  | [optional] 
**Contacts** | Pointer to [**[]Contacts**](Contacts.md) | The related party(ies) that are associated to the quote. | [optional] 
**Status** | Pointer to [**QuoteResponseBaseStatus**](QuoteResponseBaseStatus.md) |  | [optional] 
**CreatedDateTime** | Pointer to **time.Time** | The quote created date and time in UTC timezone. | [optional] 
**UpdatedDateTime** | Pointer to **time.Time** | The quote updated date and time in UTC timezone. | [optional] 
**ExpirationDateTime** | Pointer to **time.Time** | The quote expiration date and time in UTC timezone. Quote will be invalid when &#x60;expirationDateTime&#x60; has passed. | [optional] 
**Channel** | Pointer to [**QuoteResponseBaseChannel**](QuoteResponseBaseChannel.md) |  | [optional] 
**SubChannel** | Pointer to [**QuoteResponseBaseSubChannel**](QuoteResponseBaseSubChannel.md) |  | [optional] 
**CustomerReferenceId** | Pointer to **string** | Customer Reference Number / External Reference Number | [optional] 
**AgreementNumber** | Pointer to **string** | Quote agreement number | [optional] 
**CurrencyCode** | Pointer to [**QuoteResponseBaseCurrencyCode**](QuoteResponseBaseCurrencyCode.md) |  | [optional] 
**TermsOfUse** | Pointer to [**[]TermsOfUseDetails**](TermsOfUseDetails.md) | Terms and conditions of quote such as initial term, renewal period and non-renewal notice.  | [optional] 
**TotalPricing** | Pointer to [**[]PricingDetails**](PricingDetails.md) | Pricing details of grand total price | [optional] 
**VersionNumber** | Pointer to **string** | Version number will be updated when quote is revised | [optional] 

## Methods

### NewQuoteResponseBase

`func NewQuoteResponseBase() *QuoteResponseBase`

NewQuoteResponseBase instantiates a new QuoteResponseBase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteResponseBaseWithDefaults

`func NewQuoteResponseBaseWithDefaults() *QuoteResponseBase`

NewQuoteResponseBaseWithDefaults instantiates a new QuoteResponseBase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuoteId

`func (o *QuoteResponseBase) GetQuoteId() string`

GetQuoteId returns the QuoteId field if non-nil, zero value otherwise.

### GetQuoteIdOk

`func (o *QuoteResponseBase) GetQuoteIdOk() (*string, bool)`

GetQuoteIdOk returns a tuple with the QuoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteId

`func (o *QuoteResponseBase) SetQuoteId(v string)`

SetQuoteId sets QuoteId field to given value.

### HasQuoteId

`func (o *QuoteResponseBase) HasQuoteId() bool`

HasQuoteId returns a boolean if a field has been set.

### GetAccountName

`func (o *QuoteResponseBase) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *QuoteResponseBase) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *QuoteResponseBase) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *QuoteResponseBase) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *QuoteResponseBase) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *QuoteResponseBase) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *QuoteResponseBase) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *QuoteResponseBase) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetQuoteRequestType

`func (o *QuoteResponseBase) GetQuoteRequestType() QuoteResponseBaseQuoteRequestType`

GetQuoteRequestType returns the QuoteRequestType field if non-nil, zero value otherwise.

### GetQuoteRequestTypeOk

`func (o *QuoteResponseBase) GetQuoteRequestTypeOk() (*QuoteResponseBaseQuoteRequestType, bool)`

GetQuoteRequestTypeOk returns a tuple with the QuoteRequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteRequestType

`func (o *QuoteResponseBase) SetQuoteRequestType(v QuoteResponseBaseQuoteRequestType)`

SetQuoteRequestType sets QuoteRequestType field to given value.

### HasQuoteRequestType

`func (o *QuoteResponseBase) HasQuoteRequestType() bool`

HasQuoteRequestType returns a boolean if a field has been set.

### GetContacts

`func (o *QuoteResponseBase) GetContacts() []Contacts`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *QuoteResponseBase) GetContactsOk() (*[]Contacts, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *QuoteResponseBase) SetContacts(v []Contacts)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *QuoteResponseBase) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetStatus

`func (o *QuoteResponseBase) GetStatus() QuoteResponseBaseStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *QuoteResponseBase) GetStatusOk() (*QuoteResponseBaseStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *QuoteResponseBase) SetStatus(v QuoteResponseBaseStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *QuoteResponseBase) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *QuoteResponseBase) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *QuoteResponseBase) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *QuoteResponseBase) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *QuoteResponseBase) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *QuoteResponseBase) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *QuoteResponseBase) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *QuoteResponseBase) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *QuoteResponseBase) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetExpirationDateTime

`func (o *QuoteResponseBase) GetExpirationDateTime() time.Time`

GetExpirationDateTime returns the ExpirationDateTime field if non-nil, zero value otherwise.

### GetExpirationDateTimeOk

`func (o *QuoteResponseBase) GetExpirationDateTimeOk() (*time.Time, bool)`

GetExpirationDateTimeOk returns a tuple with the ExpirationDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDateTime

`func (o *QuoteResponseBase) SetExpirationDateTime(v time.Time)`

SetExpirationDateTime sets ExpirationDateTime field to given value.

### HasExpirationDateTime

`func (o *QuoteResponseBase) HasExpirationDateTime() bool`

HasExpirationDateTime returns a boolean if a field has been set.

### GetChannel

`func (o *QuoteResponseBase) GetChannel() QuoteResponseBaseChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *QuoteResponseBase) GetChannelOk() (*QuoteResponseBaseChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *QuoteResponseBase) SetChannel(v QuoteResponseBaseChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *QuoteResponseBase) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetSubChannel

`func (o *QuoteResponseBase) GetSubChannel() QuoteResponseBaseSubChannel`

GetSubChannel returns the SubChannel field if non-nil, zero value otherwise.

### GetSubChannelOk

`func (o *QuoteResponseBase) GetSubChannelOk() (*QuoteResponseBaseSubChannel, bool)`

GetSubChannelOk returns a tuple with the SubChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubChannel

`func (o *QuoteResponseBase) SetSubChannel(v QuoteResponseBaseSubChannel)`

SetSubChannel sets SubChannel field to given value.

### HasSubChannel

`func (o *QuoteResponseBase) HasSubChannel() bool`

HasSubChannel returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *QuoteResponseBase) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *QuoteResponseBase) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *QuoteResponseBase) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *QuoteResponseBase) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAgreementNumber

`func (o *QuoteResponseBase) GetAgreementNumber() string`

GetAgreementNumber returns the AgreementNumber field if non-nil, zero value otherwise.

### GetAgreementNumberOk

`func (o *QuoteResponseBase) GetAgreementNumberOk() (*string, bool)`

GetAgreementNumberOk returns a tuple with the AgreementNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgreementNumber

`func (o *QuoteResponseBase) SetAgreementNumber(v string)`

SetAgreementNumber sets AgreementNumber field to given value.

### HasAgreementNumber

`func (o *QuoteResponseBase) HasAgreementNumber() bool`

HasAgreementNumber returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *QuoteResponseBase) GetCurrencyCode() QuoteResponseBaseCurrencyCode`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *QuoteResponseBase) GetCurrencyCodeOk() (*QuoteResponseBaseCurrencyCode, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *QuoteResponseBase) SetCurrencyCode(v QuoteResponseBaseCurrencyCode)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *QuoteResponseBase) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTermsOfUse

`func (o *QuoteResponseBase) GetTermsOfUse() []TermsOfUseDetails`

GetTermsOfUse returns the TermsOfUse field if non-nil, zero value otherwise.

### GetTermsOfUseOk

`func (o *QuoteResponseBase) GetTermsOfUseOk() (*[]TermsOfUseDetails, bool)`

GetTermsOfUseOk returns a tuple with the TermsOfUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfUse

`func (o *QuoteResponseBase) SetTermsOfUse(v []TermsOfUseDetails)`

SetTermsOfUse sets TermsOfUse field to given value.

### HasTermsOfUse

`func (o *QuoteResponseBase) HasTermsOfUse() bool`

HasTermsOfUse returns a boolean if a field has been set.

### GetTotalPricing

`func (o *QuoteResponseBase) GetTotalPricing() []PricingDetails`

GetTotalPricing returns the TotalPricing field if non-nil, zero value otherwise.

### GetTotalPricingOk

`func (o *QuoteResponseBase) GetTotalPricingOk() (*[]PricingDetails, bool)`

GetTotalPricingOk returns a tuple with the TotalPricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPricing

`func (o *QuoteResponseBase) SetTotalPricing(v []PricingDetails)`

SetTotalPricing sets TotalPricing field to given value.

### HasTotalPricing

`func (o *QuoteResponseBase) HasTotalPricing() bool`

HasTotalPricing returns a boolean if a field has been set.

### GetVersionNumber

`func (o *QuoteResponseBase) GetVersionNumber() string`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *QuoteResponseBase) GetVersionNumberOk() (*string, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *QuoteResponseBase) SetVersionNumber(v string)`

SetVersionNumber sets VersionNumber field to given value.

### HasVersionNumber

`func (o *QuoteResponseBase) HasVersionNumber() bool`

HasVersionNumber returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


