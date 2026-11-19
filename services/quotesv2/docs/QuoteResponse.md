# QuoteResponse

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
**Details** | Pointer to [**[]QuoteDetails**](QuoteDetails.md) | Quote details of line items | [optional] 

## Methods

### NewQuoteResponse

`func NewQuoteResponse() *QuoteResponse`

NewQuoteResponse instantiates a new QuoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteResponseWithDefaults

`func NewQuoteResponseWithDefaults() *QuoteResponse`

NewQuoteResponseWithDefaults instantiates a new QuoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuoteId

`func (o *QuoteResponse) GetQuoteId() string`

GetQuoteId returns the QuoteId field if non-nil, zero value otherwise.

### GetQuoteIdOk

`func (o *QuoteResponse) GetQuoteIdOk() (*string, bool)`

GetQuoteIdOk returns a tuple with the QuoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteId

`func (o *QuoteResponse) SetQuoteId(v string)`

SetQuoteId sets QuoteId field to given value.

### HasQuoteId

`func (o *QuoteResponse) HasQuoteId() bool`

HasQuoteId returns a boolean if a field has been set.

### GetAccountName

`func (o *QuoteResponse) GetAccountName() string`

GetAccountName returns the AccountName field if non-nil, zero value otherwise.

### GetAccountNameOk

`func (o *QuoteResponse) GetAccountNameOk() (*string, bool)`

GetAccountNameOk returns a tuple with the AccountName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountName

`func (o *QuoteResponse) SetAccountName(v string)`

SetAccountName sets AccountName field to given value.

### HasAccountName

`func (o *QuoteResponse) HasAccountName() bool`

HasAccountName returns a boolean if a field has been set.

### GetAccountNumber

`func (o *QuoteResponse) GetAccountNumber() string`

GetAccountNumber returns the AccountNumber field if non-nil, zero value otherwise.

### GetAccountNumberOk

`func (o *QuoteResponse) GetAccountNumberOk() (*string, bool)`

GetAccountNumberOk returns a tuple with the AccountNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountNumber

`func (o *QuoteResponse) SetAccountNumber(v string)`

SetAccountNumber sets AccountNumber field to given value.

### HasAccountNumber

`func (o *QuoteResponse) HasAccountNumber() bool`

HasAccountNumber returns a boolean if a field has been set.

### GetQuoteRequestType

`func (o *QuoteResponse) GetQuoteRequestType() QuoteResponseBaseQuoteRequestType`

GetQuoteRequestType returns the QuoteRequestType field if non-nil, zero value otherwise.

### GetQuoteRequestTypeOk

`func (o *QuoteResponse) GetQuoteRequestTypeOk() (*QuoteResponseBaseQuoteRequestType, bool)`

GetQuoteRequestTypeOk returns a tuple with the QuoteRequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteRequestType

`func (o *QuoteResponse) SetQuoteRequestType(v QuoteResponseBaseQuoteRequestType)`

SetQuoteRequestType sets QuoteRequestType field to given value.

### HasQuoteRequestType

`func (o *QuoteResponse) HasQuoteRequestType() bool`

HasQuoteRequestType returns a boolean if a field has been set.

### GetContacts

`func (o *QuoteResponse) GetContacts() []Contacts`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *QuoteResponse) GetContactsOk() (*[]Contacts, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *QuoteResponse) SetContacts(v []Contacts)`

SetContacts sets Contacts field to given value.

### HasContacts

`func (o *QuoteResponse) HasContacts() bool`

HasContacts returns a boolean if a field has been set.

### GetStatus

`func (o *QuoteResponse) GetStatus() QuoteResponseBaseStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *QuoteResponse) GetStatusOk() (*QuoteResponseBaseStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *QuoteResponse) SetStatus(v QuoteResponseBaseStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *QuoteResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCreatedDateTime

`func (o *QuoteResponse) GetCreatedDateTime() time.Time`

GetCreatedDateTime returns the CreatedDateTime field if non-nil, zero value otherwise.

### GetCreatedDateTimeOk

`func (o *QuoteResponse) GetCreatedDateTimeOk() (*time.Time, bool)`

GetCreatedDateTimeOk returns a tuple with the CreatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDateTime

`func (o *QuoteResponse) SetCreatedDateTime(v time.Time)`

SetCreatedDateTime sets CreatedDateTime field to given value.

### HasCreatedDateTime

`func (o *QuoteResponse) HasCreatedDateTime() bool`

HasCreatedDateTime returns a boolean if a field has been set.

### GetUpdatedDateTime

`func (o *QuoteResponse) GetUpdatedDateTime() time.Time`

GetUpdatedDateTime returns the UpdatedDateTime field if non-nil, zero value otherwise.

### GetUpdatedDateTimeOk

`func (o *QuoteResponse) GetUpdatedDateTimeOk() (*time.Time, bool)`

GetUpdatedDateTimeOk returns a tuple with the UpdatedDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedDateTime

`func (o *QuoteResponse) SetUpdatedDateTime(v time.Time)`

SetUpdatedDateTime sets UpdatedDateTime field to given value.

### HasUpdatedDateTime

`func (o *QuoteResponse) HasUpdatedDateTime() bool`

HasUpdatedDateTime returns a boolean if a field has been set.

### GetExpirationDateTime

`func (o *QuoteResponse) GetExpirationDateTime() time.Time`

GetExpirationDateTime returns the ExpirationDateTime field if non-nil, zero value otherwise.

### GetExpirationDateTimeOk

`func (o *QuoteResponse) GetExpirationDateTimeOk() (*time.Time, bool)`

GetExpirationDateTimeOk returns a tuple with the ExpirationDateTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationDateTime

`func (o *QuoteResponse) SetExpirationDateTime(v time.Time)`

SetExpirationDateTime sets ExpirationDateTime field to given value.

### HasExpirationDateTime

`func (o *QuoteResponse) HasExpirationDateTime() bool`

HasExpirationDateTime returns a boolean if a field has been set.

### GetChannel

`func (o *QuoteResponse) GetChannel() QuoteResponseBaseChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *QuoteResponse) GetChannelOk() (*QuoteResponseBaseChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *QuoteResponse) SetChannel(v QuoteResponseBaseChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *QuoteResponse) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetSubChannel

`func (o *QuoteResponse) GetSubChannel() QuoteResponseBaseSubChannel`

GetSubChannel returns the SubChannel field if non-nil, zero value otherwise.

### GetSubChannelOk

`func (o *QuoteResponse) GetSubChannelOk() (*QuoteResponseBaseSubChannel, bool)`

GetSubChannelOk returns a tuple with the SubChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubChannel

`func (o *QuoteResponse) SetSubChannel(v QuoteResponseBaseSubChannel)`

SetSubChannel sets SubChannel field to given value.

### HasSubChannel

`func (o *QuoteResponse) HasSubChannel() bool`

HasSubChannel returns a boolean if a field has been set.

### GetCustomerReferenceId

`func (o *QuoteResponse) GetCustomerReferenceId() string`

GetCustomerReferenceId returns the CustomerReferenceId field if non-nil, zero value otherwise.

### GetCustomerReferenceIdOk

`func (o *QuoteResponse) GetCustomerReferenceIdOk() (*string, bool)`

GetCustomerReferenceIdOk returns a tuple with the CustomerReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerReferenceId

`func (o *QuoteResponse) SetCustomerReferenceId(v string)`

SetCustomerReferenceId sets CustomerReferenceId field to given value.

### HasCustomerReferenceId

`func (o *QuoteResponse) HasCustomerReferenceId() bool`

HasCustomerReferenceId returns a boolean if a field has been set.

### GetAgreementNumber

`func (o *QuoteResponse) GetAgreementNumber() string`

GetAgreementNumber returns the AgreementNumber field if non-nil, zero value otherwise.

### GetAgreementNumberOk

`func (o *QuoteResponse) GetAgreementNumberOk() (*string, bool)`

GetAgreementNumberOk returns a tuple with the AgreementNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgreementNumber

`func (o *QuoteResponse) SetAgreementNumber(v string)`

SetAgreementNumber sets AgreementNumber field to given value.

### HasAgreementNumber

`func (o *QuoteResponse) HasAgreementNumber() bool`

HasAgreementNumber returns a boolean if a field has been set.

### GetCurrencyCode

`func (o *QuoteResponse) GetCurrencyCode() QuoteResponseBaseCurrencyCode`

GetCurrencyCode returns the CurrencyCode field if non-nil, zero value otherwise.

### GetCurrencyCodeOk

`func (o *QuoteResponse) GetCurrencyCodeOk() (*QuoteResponseBaseCurrencyCode, bool)`

GetCurrencyCodeOk returns a tuple with the CurrencyCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrencyCode

`func (o *QuoteResponse) SetCurrencyCode(v QuoteResponseBaseCurrencyCode)`

SetCurrencyCode sets CurrencyCode field to given value.

### HasCurrencyCode

`func (o *QuoteResponse) HasCurrencyCode() bool`

HasCurrencyCode returns a boolean if a field has been set.

### GetTermsOfUse

`func (o *QuoteResponse) GetTermsOfUse() []TermsOfUseDetails`

GetTermsOfUse returns the TermsOfUse field if non-nil, zero value otherwise.

### GetTermsOfUseOk

`func (o *QuoteResponse) GetTermsOfUseOk() (*[]TermsOfUseDetails, bool)`

GetTermsOfUseOk returns a tuple with the TermsOfUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfUse

`func (o *QuoteResponse) SetTermsOfUse(v []TermsOfUseDetails)`

SetTermsOfUse sets TermsOfUse field to given value.

### HasTermsOfUse

`func (o *QuoteResponse) HasTermsOfUse() bool`

HasTermsOfUse returns a boolean if a field has been set.

### GetTotalPricing

`func (o *QuoteResponse) GetTotalPricing() []PricingDetails`

GetTotalPricing returns the TotalPricing field if non-nil, zero value otherwise.

### GetTotalPricingOk

`func (o *QuoteResponse) GetTotalPricingOk() (*[]PricingDetails, bool)`

GetTotalPricingOk returns a tuple with the TotalPricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPricing

`func (o *QuoteResponse) SetTotalPricing(v []PricingDetails)`

SetTotalPricing sets TotalPricing field to given value.

### HasTotalPricing

`func (o *QuoteResponse) HasTotalPricing() bool`

HasTotalPricing returns a boolean if a field has been set.

### GetVersionNumber

`func (o *QuoteResponse) GetVersionNumber() string`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *QuoteResponse) GetVersionNumberOk() (*string, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *QuoteResponse) SetVersionNumber(v string)`

SetVersionNumber sets VersionNumber field to given value.

### HasVersionNumber

`func (o *QuoteResponse) HasVersionNumber() bool`

HasVersionNumber returns a boolean if a field has been set.

### GetDetails

`func (o *QuoteResponse) GetDetails() []QuoteDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *QuoteResponse) GetDetailsOk() (*[]QuoteDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *QuoteResponse) SetDetails(v []QuoteDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *QuoteResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


