# DomainListItemSubscriptionHistoryInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanName** | **string** | Name of the subscription plan. | 
**PlanStart** | **time.Time** | Plan start date. | 
**PlanEnd** | **NullableTime** | Plan end date (null if still active). | 
**Status** | **string** | Display status (e.g. Active, Ended, Past Due). | 
**Administrator** | [**DomainListItemSubscriptionHistoryInnerAdministrator**](DomainListItemSubscriptionHistoryInnerAdministrator.md) |  | 
**StripeLink** | **NullableString** | Link to Stripe subscription. | 

## Methods

### NewDomainListItemSubscriptionHistoryInner

`func NewDomainListItemSubscriptionHistoryInner(planName string, planStart time.Time, planEnd NullableTime, status string, administrator DomainListItemSubscriptionHistoryInnerAdministrator, stripeLink NullableString, ) *DomainListItemSubscriptionHistoryInner`

NewDomainListItemSubscriptionHistoryInner instantiates a new DomainListItemSubscriptionHistoryInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemSubscriptionHistoryInnerWithDefaults

`func NewDomainListItemSubscriptionHistoryInnerWithDefaults() *DomainListItemSubscriptionHistoryInner`

NewDomainListItemSubscriptionHistoryInnerWithDefaults instantiates a new DomainListItemSubscriptionHistoryInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanName

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *DomainListItemSubscriptionHistoryInner) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.


### GetPlanStart

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanStart() time.Time`

GetPlanStart returns the PlanStart field if non-nil, zero value otherwise.

### GetPlanStartOk

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanStartOk() (*time.Time, bool)`

GetPlanStartOk returns a tuple with the PlanStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanStart

`func (o *DomainListItemSubscriptionHistoryInner) SetPlanStart(v time.Time)`

SetPlanStart sets PlanStart field to given value.


### GetPlanEnd

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanEnd() time.Time`

GetPlanEnd returns the PlanEnd field if non-nil, zero value otherwise.

### GetPlanEndOk

`func (o *DomainListItemSubscriptionHistoryInner) GetPlanEndOk() (*time.Time, bool)`

GetPlanEndOk returns a tuple with the PlanEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanEnd

`func (o *DomainListItemSubscriptionHistoryInner) SetPlanEnd(v time.Time)`

SetPlanEnd sets PlanEnd field to given value.


### SetPlanEndNil

`func (o *DomainListItemSubscriptionHistoryInner) SetPlanEndNil(b bool)`

 SetPlanEndNil sets the value for PlanEnd to be an explicit nil

### UnsetPlanEnd
`func (o *DomainListItemSubscriptionHistoryInner) UnsetPlanEnd()`

UnsetPlanEnd ensures that no value is present for PlanEnd, not even an explicit nil
### GetStatus

`func (o *DomainListItemSubscriptionHistoryInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DomainListItemSubscriptionHistoryInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DomainListItemSubscriptionHistoryInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAdministrator

`func (o *DomainListItemSubscriptionHistoryInner) GetAdministrator() DomainListItemSubscriptionHistoryInnerAdministrator`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *DomainListItemSubscriptionHistoryInner) GetAdministratorOk() (*DomainListItemSubscriptionHistoryInnerAdministrator, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *DomainListItemSubscriptionHistoryInner) SetAdministrator(v DomainListItemSubscriptionHistoryInnerAdministrator)`

SetAdministrator sets Administrator field to given value.


### GetStripeLink

`func (o *DomainListItemSubscriptionHistoryInner) GetStripeLink() string`

GetStripeLink returns the StripeLink field if non-nil, zero value otherwise.

### GetStripeLinkOk

`func (o *DomainListItemSubscriptionHistoryInner) GetStripeLinkOk() (*string, bool)`

GetStripeLinkOk returns a tuple with the StripeLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripeLink

`func (o *DomainListItemSubscriptionHistoryInner) SetStripeLink(v string)`

SetStripeLink sets StripeLink field to given value.


### SetStripeLinkNil

`func (o *DomainListItemSubscriptionHistoryInner) SetStripeLinkNil(b bool)`

 SetStripeLinkNil sets the value for StripeLink to be an explicit nil

### UnsetStripeLink
`func (o *DomainListItemSubscriptionHistoryInner) UnsetStripeLink()`

UnsetStripeLink ensures that no value is present for StripeLink, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


