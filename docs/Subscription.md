# Subscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Trial** | [**NullableSubscriptionTrial**](SubscriptionTrial.md) |  | 
**Status** | **NullableString** | Subscription status. Null on domains without billing. | 
**BillingType** | **string** | Billing type. | 
**PlanName** | **NullableString** | Plan name. | 
**NextBill** | Pointer to **NullableString** | Next billing date. Omitted on domains without billing. | [optional] 
**UseDeviceAccounting** | **NullableBool** | Whether device accounting is used. | 
**IsEnterprise** | **NullableBool** | Whether the plan is enterprise. | 
**IsUsageBased** | **NullableBool** | Whether the plan is usage based. | 
**CancelPolicy** | **NullableString** | Cancellation policy. | 

## Methods

### NewSubscription

`func NewSubscription(trial NullableSubscriptionTrial, status NullableString, billingType string, planName NullableString, useDeviceAccounting NullableBool, isEnterprise NullableBool, isUsageBased NullableBool, cancelPolicy NullableString, ) *Subscription`

NewSubscription instantiates a new Subscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionWithDefaults

`func NewSubscriptionWithDefaults() *Subscription`

NewSubscriptionWithDefaults instantiates a new Subscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrial

`func (o *Subscription) GetTrial() SubscriptionTrial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *Subscription) GetTrialOk() (*SubscriptionTrial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *Subscription) SetTrial(v SubscriptionTrial)`

SetTrial sets Trial field to given value.


### SetTrialNil

`func (o *Subscription) SetTrialNil(b bool)`

 SetTrialNil sets the value for Trial to be an explicit nil

### UnsetTrial
`func (o *Subscription) UnsetTrial()`

UnsetTrial ensures that no value is present for Trial, not even an explicit nil
### GetStatus

`func (o *Subscription) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Subscription) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Subscription) SetStatus(v string)`

SetStatus sets Status field to given value.


### SetStatusNil

`func (o *Subscription) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *Subscription) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetBillingType

`func (o *Subscription) GetBillingType() string`

GetBillingType returns the BillingType field if non-nil, zero value otherwise.

### GetBillingTypeOk

`func (o *Subscription) GetBillingTypeOk() (*string, bool)`

GetBillingTypeOk returns a tuple with the BillingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingType

`func (o *Subscription) SetBillingType(v string)`

SetBillingType sets BillingType field to given value.


### GetPlanName

`func (o *Subscription) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *Subscription) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *Subscription) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### SetPlanNameNil

`func (o *Subscription) SetPlanNameNil(b bool)`

 SetPlanNameNil sets the value for PlanName to be an explicit nil

### UnsetPlanName
`func (o *Subscription) UnsetPlanName()`

UnsetPlanName ensures that no value is present for PlanName, not even an explicit nil
### GetNextBill

`func (o *Subscription) GetNextBill() string`

GetNextBill returns the NextBill field if non-nil, zero value otherwise.

### GetNextBillOk

`func (o *Subscription) GetNextBillOk() (*string, bool)`

GetNextBillOk returns a tuple with the NextBill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBill

`func (o *Subscription) SetNextBill(v string)`

SetNextBill sets NextBill field to given value.

### HasNextBill

`func (o *Subscription) HasNextBill() bool`

HasNextBill returns a boolean if a field has been set.

### SetNextBillNil

`func (o *Subscription) SetNextBillNil(b bool)`

 SetNextBillNil sets the value for NextBill to be an explicit nil

### UnsetNextBill
`func (o *Subscription) UnsetNextBill()`

UnsetNextBill ensures that no value is present for NextBill, not even an explicit nil
### GetUseDeviceAccounting

`func (o *Subscription) GetUseDeviceAccounting() bool`

GetUseDeviceAccounting returns the UseDeviceAccounting field if non-nil, zero value otherwise.

### GetUseDeviceAccountingOk

`func (o *Subscription) GetUseDeviceAccountingOk() (*bool, bool)`

GetUseDeviceAccountingOk returns a tuple with the UseDeviceAccounting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseDeviceAccounting

`func (o *Subscription) SetUseDeviceAccounting(v bool)`

SetUseDeviceAccounting sets UseDeviceAccounting field to given value.


### SetUseDeviceAccountingNil

`func (o *Subscription) SetUseDeviceAccountingNil(b bool)`

 SetUseDeviceAccountingNil sets the value for UseDeviceAccounting to be an explicit nil

### UnsetUseDeviceAccounting
`func (o *Subscription) UnsetUseDeviceAccounting()`

UnsetUseDeviceAccounting ensures that no value is present for UseDeviceAccounting, not even an explicit nil
### GetIsEnterprise

`func (o *Subscription) GetIsEnterprise() bool`

GetIsEnterprise returns the IsEnterprise field if non-nil, zero value otherwise.

### GetIsEnterpriseOk

`func (o *Subscription) GetIsEnterpriseOk() (*bool, bool)`

GetIsEnterpriseOk returns a tuple with the IsEnterprise field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnterprise

`func (o *Subscription) SetIsEnterprise(v bool)`

SetIsEnterprise sets IsEnterprise field to given value.


### SetIsEnterpriseNil

`func (o *Subscription) SetIsEnterpriseNil(b bool)`

 SetIsEnterpriseNil sets the value for IsEnterprise to be an explicit nil

### UnsetIsEnterprise
`func (o *Subscription) UnsetIsEnterprise()`

UnsetIsEnterprise ensures that no value is present for IsEnterprise, not even an explicit nil
### GetIsUsageBased

`func (o *Subscription) GetIsUsageBased() bool`

GetIsUsageBased returns the IsUsageBased field if non-nil, zero value otherwise.

### GetIsUsageBasedOk

`func (o *Subscription) GetIsUsageBasedOk() (*bool, bool)`

GetIsUsageBasedOk returns a tuple with the IsUsageBased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsUsageBased

`func (o *Subscription) SetIsUsageBased(v bool)`

SetIsUsageBased sets IsUsageBased field to given value.


### SetIsUsageBasedNil

`func (o *Subscription) SetIsUsageBasedNil(b bool)`

 SetIsUsageBasedNil sets the value for IsUsageBased to be an explicit nil

### UnsetIsUsageBased
`func (o *Subscription) UnsetIsUsageBased()`

UnsetIsUsageBased ensures that no value is present for IsUsageBased, not even an explicit nil
### GetCancelPolicy

`func (o *Subscription) GetCancelPolicy() string`

GetCancelPolicy returns the CancelPolicy field if non-nil, zero value otherwise.

### GetCancelPolicyOk

`func (o *Subscription) GetCancelPolicyOk() (*string, bool)`

GetCancelPolicyOk returns a tuple with the CancelPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelPolicy

`func (o *Subscription) SetCancelPolicy(v string)`

SetCancelPolicy sets CancelPolicy field to given value.


### SetCancelPolicyNil

`func (o *Subscription) SetCancelPolicyNil(b bool)`

 SetCancelPolicyNil sets the value for CancelPolicy to be an explicit nil

### UnsetCancelPolicy
`func (o *Subscription) UnsetCancelPolicy()`

UnsetCancelPolicy ensures that no value is present for CancelPolicy, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


