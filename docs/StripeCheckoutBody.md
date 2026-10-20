# StripeCheckoutBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TermsOfService** | **bool** | Whether terms of service were accepted. | 
**Email** | **string** | Customer email. | 
**Name** | **string** | Customer name. | 
**Domain** | **string** | Domain name. | 
**Cores** | **float32** | Number of cores. | 
**LicenseType** | **string** | License type. | 
**ExistingDomain** | **bool** | Whether this targets an existing domain. | 
**PriceId** | **string** | Stripe price identifier. | 
**CouponCode** | Pointer to **string** | Optional coupon code. | [optional] 

## Methods

### NewStripeCheckoutBody

`func NewStripeCheckoutBody(termsOfService bool, email string, name string, domain string, cores float32, licenseType string, existingDomain bool, priceId string, ) *StripeCheckoutBody`

NewStripeCheckoutBody instantiates a new StripeCheckoutBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStripeCheckoutBodyWithDefaults

`func NewStripeCheckoutBodyWithDefaults() *StripeCheckoutBody`

NewStripeCheckoutBodyWithDefaults instantiates a new StripeCheckoutBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTermsOfService

`func (o *StripeCheckoutBody) GetTermsOfService() bool`

GetTermsOfService returns the TermsOfService field if non-nil, zero value otherwise.

### GetTermsOfServiceOk

`func (o *StripeCheckoutBody) GetTermsOfServiceOk() (*bool, bool)`

GetTermsOfServiceOk returns a tuple with the TermsOfService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfService

`func (o *StripeCheckoutBody) SetTermsOfService(v bool)`

SetTermsOfService sets TermsOfService field to given value.


### GetEmail

`func (o *StripeCheckoutBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *StripeCheckoutBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *StripeCheckoutBody) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetName

`func (o *StripeCheckoutBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *StripeCheckoutBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *StripeCheckoutBody) SetName(v string)`

SetName sets Name field to given value.


### GetDomain

`func (o *StripeCheckoutBody) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *StripeCheckoutBody) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *StripeCheckoutBody) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCores

`func (o *StripeCheckoutBody) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *StripeCheckoutBody) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *StripeCheckoutBody) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetLicenseType

`func (o *StripeCheckoutBody) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *StripeCheckoutBody) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *StripeCheckoutBody) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.


### GetExistingDomain

`func (o *StripeCheckoutBody) GetExistingDomain() bool`

GetExistingDomain returns the ExistingDomain field if non-nil, zero value otherwise.

### GetExistingDomainOk

`func (o *StripeCheckoutBody) GetExistingDomainOk() (*bool, bool)`

GetExistingDomainOk returns a tuple with the ExistingDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExistingDomain

`func (o *StripeCheckoutBody) SetExistingDomain(v bool)`

SetExistingDomain sets ExistingDomain field to given value.


### GetPriceId

`func (o *StripeCheckoutBody) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *StripeCheckoutBody) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *StripeCheckoutBody) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.


### GetCouponCode

`func (o *StripeCheckoutBody) GetCouponCode() string`

GetCouponCode returns the CouponCode field if non-nil, zero value otherwise.

### GetCouponCodeOk

`func (o *StripeCheckoutBody) GetCouponCodeOk() (*string, bool)`

GetCouponCodeOk returns a tuple with the CouponCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCouponCode

`func (o *StripeCheckoutBody) SetCouponCode(v string)`

SetCouponCode sets CouponCode field to given value.

### HasCouponCode

`func (o *StripeCheckoutBody) HasCouponCode() bool`

HasCouponCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


