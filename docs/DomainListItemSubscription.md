# DomainListItemSubscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RenewAction** | **map[string]interface{}** | Renewal action configuration (varies by billing backend). | 
**Domain** | **string** | Domain identifier. | 
**BillingType** | **string** | Billing type. | 
**BillingBackend** | **string** | Billing backend (stripe, etc.). | 
**BillingId** | **NullableString** | External billing identifier. | 
**NextBill** | **NullableTime** | ISO timestamp of next billing date. | 
**UsageBased** | **bool** | Whether billing is usage-based. | 
**LastUsageBill** | **NullableTime** | ISO timestamp of last usage bill. | 
**LastPaymentAmount** | **NullableFloat32** | Last payment amount, in cents. | 
**UsageBillIntervalDays** | **NullableFloat32** | Interval in days between usage bills. | 
**UsageBillingThresholdDollars** | **NullableFloat32** | Dollar threshold that triggers a usage bill. | 
**PastDue** | **NullableBool** | Whether the subscription is past due. | 
**PaymentAttempts** | **NullableFloat32** | Number of payment attempts. | 
**LastPaymentAttempt** | **NullableTime** | ISO timestamp of last payment attempt. | 
**CreatedAt** | **time.Time** | ISO timestamp of subscription creation. | 
**UpdatedAt** | **time.Time** | ISO timestamp of last subscription update. | 

## Methods

### NewDomainListItemSubscription

`func NewDomainListItemSubscription(renewAction map[string]interface{}, domain string, billingType string, billingBackend string, billingId NullableString, nextBill NullableTime, usageBased bool, lastUsageBill NullableTime, lastPaymentAmount NullableFloat32, usageBillIntervalDays NullableFloat32, usageBillingThresholdDollars NullableFloat32, pastDue NullableBool, paymentAttempts NullableFloat32, lastPaymentAttempt NullableTime, createdAt time.Time, updatedAt time.Time, ) *DomainListItemSubscription`

NewDomainListItemSubscription instantiates a new DomainListItemSubscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemSubscriptionWithDefaults

`func NewDomainListItemSubscriptionWithDefaults() *DomainListItemSubscription`

NewDomainListItemSubscriptionWithDefaults instantiates a new DomainListItemSubscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRenewAction

`func (o *DomainListItemSubscription) GetRenewAction() map[string]interface{}`

GetRenewAction returns the RenewAction field if non-nil, zero value otherwise.

### GetRenewActionOk

`func (o *DomainListItemSubscription) GetRenewActionOk() (*map[string]interface{}, bool)`

GetRenewActionOk returns a tuple with the RenewAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewAction

`func (o *DomainListItemSubscription) SetRenewAction(v map[string]interface{})`

SetRenewAction sets RenewAction field to given value.


### SetRenewActionNil

`func (o *DomainListItemSubscription) SetRenewActionNil(b bool)`

 SetRenewActionNil sets the value for RenewAction to be an explicit nil

### UnsetRenewAction
`func (o *DomainListItemSubscription) UnsetRenewAction()`

UnsetRenewAction ensures that no value is present for RenewAction, not even an explicit nil
### GetDomain

`func (o *DomainListItemSubscription) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainListItemSubscription) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainListItemSubscription) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetBillingType

`func (o *DomainListItemSubscription) GetBillingType() string`

GetBillingType returns the BillingType field if non-nil, zero value otherwise.

### GetBillingTypeOk

`func (o *DomainListItemSubscription) GetBillingTypeOk() (*string, bool)`

GetBillingTypeOk returns a tuple with the BillingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingType

`func (o *DomainListItemSubscription) SetBillingType(v string)`

SetBillingType sets BillingType field to given value.


### GetBillingBackend

`func (o *DomainListItemSubscription) GetBillingBackend() string`

GetBillingBackend returns the BillingBackend field if non-nil, zero value otherwise.

### GetBillingBackendOk

`func (o *DomainListItemSubscription) GetBillingBackendOk() (*string, bool)`

GetBillingBackendOk returns a tuple with the BillingBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingBackend

`func (o *DomainListItemSubscription) SetBillingBackend(v string)`

SetBillingBackend sets BillingBackend field to given value.


### GetBillingId

`func (o *DomainListItemSubscription) GetBillingId() string`

GetBillingId returns the BillingId field if non-nil, zero value otherwise.

### GetBillingIdOk

`func (o *DomainListItemSubscription) GetBillingIdOk() (*string, bool)`

GetBillingIdOk returns a tuple with the BillingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingId

`func (o *DomainListItemSubscription) SetBillingId(v string)`

SetBillingId sets BillingId field to given value.


### SetBillingIdNil

`func (o *DomainListItemSubscription) SetBillingIdNil(b bool)`

 SetBillingIdNil sets the value for BillingId to be an explicit nil

### UnsetBillingId
`func (o *DomainListItemSubscription) UnsetBillingId()`

UnsetBillingId ensures that no value is present for BillingId, not even an explicit nil
### GetNextBill

`func (o *DomainListItemSubscription) GetNextBill() time.Time`

GetNextBill returns the NextBill field if non-nil, zero value otherwise.

### GetNextBillOk

`func (o *DomainListItemSubscription) GetNextBillOk() (*time.Time, bool)`

GetNextBillOk returns a tuple with the NextBill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBill

`func (o *DomainListItemSubscription) SetNextBill(v time.Time)`

SetNextBill sets NextBill field to given value.


### SetNextBillNil

`func (o *DomainListItemSubscription) SetNextBillNil(b bool)`

 SetNextBillNil sets the value for NextBill to be an explicit nil

### UnsetNextBill
`func (o *DomainListItemSubscription) UnsetNextBill()`

UnsetNextBill ensures that no value is present for NextBill, not even an explicit nil
### GetUsageBased

`func (o *DomainListItemSubscription) GetUsageBased() bool`

GetUsageBased returns the UsageBased field if non-nil, zero value otherwise.

### GetUsageBasedOk

`func (o *DomainListItemSubscription) GetUsageBasedOk() (*bool, bool)`

GetUsageBasedOk returns a tuple with the UsageBased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageBased

`func (o *DomainListItemSubscription) SetUsageBased(v bool)`

SetUsageBased sets UsageBased field to given value.


### GetLastUsageBill

`func (o *DomainListItemSubscription) GetLastUsageBill() time.Time`

GetLastUsageBill returns the LastUsageBill field if non-nil, zero value otherwise.

### GetLastUsageBillOk

`func (o *DomainListItemSubscription) GetLastUsageBillOk() (*time.Time, bool)`

GetLastUsageBillOk returns a tuple with the LastUsageBill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsageBill

`func (o *DomainListItemSubscription) SetLastUsageBill(v time.Time)`

SetLastUsageBill sets LastUsageBill field to given value.


### SetLastUsageBillNil

`func (o *DomainListItemSubscription) SetLastUsageBillNil(b bool)`

 SetLastUsageBillNil sets the value for LastUsageBill to be an explicit nil

### UnsetLastUsageBill
`func (o *DomainListItemSubscription) UnsetLastUsageBill()`

UnsetLastUsageBill ensures that no value is present for LastUsageBill, not even an explicit nil
### GetLastPaymentAmount

`func (o *DomainListItemSubscription) GetLastPaymentAmount() float32`

GetLastPaymentAmount returns the LastPaymentAmount field if non-nil, zero value otherwise.

### GetLastPaymentAmountOk

`func (o *DomainListItemSubscription) GetLastPaymentAmountOk() (*float32, bool)`

GetLastPaymentAmountOk returns a tuple with the LastPaymentAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPaymentAmount

`func (o *DomainListItemSubscription) SetLastPaymentAmount(v float32)`

SetLastPaymentAmount sets LastPaymentAmount field to given value.


### SetLastPaymentAmountNil

`func (o *DomainListItemSubscription) SetLastPaymentAmountNil(b bool)`

 SetLastPaymentAmountNil sets the value for LastPaymentAmount to be an explicit nil

### UnsetLastPaymentAmount
`func (o *DomainListItemSubscription) UnsetLastPaymentAmount()`

UnsetLastPaymentAmount ensures that no value is present for LastPaymentAmount, not even an explicit nil
### GetUsageBillIntervalDays

`func (o *DomainListItemSubscription) GetUsageBillIntervalDays() float32`

GetUsageBillIntervalDays returns the UsageBillIntervalDays field if non-nil, zero value otherwise.

### GetUsageBillIntervalDaysOk

`func (o *DomainListItemSubscription) GetUsageBillIntervalDaysOk() (*float32, bool)`

GetUsageBillIntervalDaysOk returns a tuple with the UsageBillIntervalDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageBillIntervalDays

`func (o *DomainListItemSubscription) SetUsageBillIntervalDays(v float32)`

SetUsageBillIntervalDays sets UsageBillIntervalDays field to given value.


### SetUsageBillIntervalDaysNil

`func (o *DomainListItemSubscription) SetUsageBillIntervalDaysNil(b bool)`

 SetUsageBillIntervalDaysNil sets the value for UsageBillIntervalDays to be an explicit nil

### UnsetUsageBillIntervalDays
`func (o *DomainListItemSubscription) UnsetUsageBillIntervalDays()`

UnsetUsageBillIntervalDays ensures that no value is present for UsageBillIntervalDays, not even an explicit nil
### GetUsageBillingThresholdDollars

`func (o *DomainListItemSubscription) GetUsageBillingThresholdDollars() float32`

GetUsageBillingThresholdDollars returns the UsageBillingThresholdDollars field if non-nil, zero value otherwise.

### GetUsageBillingThresholdDollarsOk

`func (o *DomainListItemSubscription) GetUsageBillingThresholdDollarsOk() (*float32, bool)`

GetUsageBillingThresholdDollarsOk returns a tuple with the UsageBillingThresholdDollars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageBillingThresholdDollars

`func (o *DomainListItemSubscription) SetUsageBillingThresholdDollars(v float32)`

SetUsageBillingThresholdDollars sets UsageBillingThresholdDollars field to given value.


### SetUsageBillingThresholdDollarsNil

`func (o *DomainListItemSubscription) SetUsageBillingThresholdDollarsNil(b bool)`

 SetUsageBillingThresholdDollarsNil sets the value for UsageBillingThresholdDollars to be an explicit nil

### UnsetUsageBillingThresholdDollars
`func (o *DomainListItemSubscription) UnsetUsageBillingThresholdDollars()`

UnsetUsageBillingThresholdDollars ensures that no value is present for UsageBillingThresholdDollars, not even an explicit nil
### GetPastDue

`func (o *DomainListItemSubscription) GetPastDue() bool`

GetPastDue returns the PastDue field if non-nil, zero value otherwise.

### GetPastDueOk

`func (o *DomainListItemSubscription) GetPastDueOk() (*bool, bool)`

GetPastDueOk returns a tuple with the PastDue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPastDue

`func (o *DomainListItemSubscription) SetPastDue(v bool)`

SetPastDue sets PastDue field to given value.


### SetPastDueNil

`func (o *DomainListItemSubscription) SetPastDueNil(b bool)`

 SetPastDueNil sets the value for PastDue to be an explicit nil

### UnsetPastDue
`func (o *DomainListItemSubscription) UnsetPastDue()`

UnsetPastDue ensures that no value is present for PastDue, not even an explicit nil
### GetPaymentAttempts

`func (o *DomainListItemSubscription) GetPaymentAttempts() float32`

GetPaymentAttempts returns the PaymentAttempts field if non-nil, zero value otherwise.

### GetPaymentAttemptsOk

`func (o *DomainListItemSubscription) GetPaymentAttemptsOk() (*float32, bool)`

GetPaymentAttemptsOk returns a tuple with the PaymentAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentAttempts

`func (o *DomainListItemSubscription) SetPaymentAttempts(v float32)`

SetPaymentAttempts sets PaymentAttempts field to given value.


### SetPaymentAttemptsNil

`func (o *DomainListItemSubscription) SetPaymentAttemptsNil(b bool)`

 SetPaymentAttemptsNil sets the value for PaymentAttempts to be an explicit nil

### UnsetPaymentAttempts
`func (o *DomainListItemSubscription) UnsetPaymentAttempts()`

UnsetPaymentAttempts ensures that no value is present for PaymentAttempts, not even an explicit nil
### GetLastPaymentAttempt

`func (o *DomainListItemSubscription) GetLastPaymentAttempt() time.Time`

GetLastPaymentAttempt returns the LastPaymentAttempt field if non-nil, zero value otherwise.

### GetLastPaymentAttemptOk

`func (o *DomainListItemSubscription) GetLastPaymentAttemptOk() (*time.Time, bool)`

GetLastPaymentAttemptOk returns a tuple with the LastPaymentAttempt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPaymentAttempt

`func (o *DomainListItemSubscription) SetLastPaymentAttempt(v time.Time)`

SetLastPaymentAttempt sets LastPaymentAttempt field to given value.


### SetLastPaymentAttemptNil

`func (o *DomainListItemSubscription) SetLastPaymentAttemptNil(b bool)`

 SetLastPaymentAttemptNil sets the value for LastPaymentAttempt to be an explicit nil

### UnsetLastPaymentAttempt
`func (o *DomainListItemSubscription) UnsetLastPaymentAttempt()`

UnsetLastPaymentAttempt ensures that no value is present for LastPaymentAttempt, not even an explicit nil
### GetCreatedAt

`func (o *DomainListItemSubscription) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainListItemSubscription) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainListItemSubscription) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DomainListItemSubscription) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainListItemSubscription) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainListItemSubscription) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


