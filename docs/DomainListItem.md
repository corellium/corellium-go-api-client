# DomainListItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Domain identifier. | 
**UserId** | **string** | Owner user identifier. | 
**DomainUsage** | [**[]DomainListItemDomainUsageInner**](DomainListItemDomainUsageInner.md) | Monthly usage entries. | 
**UserCount** | **float32** | Number of users in the domain. | 
**UsersInfo** | [**[]DomainListItemUsersInfoInner**](DomainListItemUsersInfoInner.md) | Users in the domain. | 
**Domain** | **string** | Fully qualified domain name. | 
**DomainName** | **string** | Domain name. | 
**Disabled** | [**NullableDomainListItemDisabled**](DomainListItemDisabled.md) |  | 
**Config** | [**DomainConfig**](DomainConfig.md) |  | 
**Quotas** | [**DomainListItemQuotas**](DomainListItemQuotas.md) |  | 
**Usage** | [**DomainListItemUsage**](DomainListItemUsage.md) |  | 
**CreatedAt** | **float32** | Domain creation timestamp (epoch ms). | 
**Subscription** | [**NullableDomainListItemSubscription**](DomainListItemSubscription.md) |  | 
**SubscriptionHistory** | Pointer to [**[]DomainListItemSubscriptionHistoryInner**](DomainListItemSubscriptionHistoryInner.md) | Subscription history. | [optional] 
**PlanName** | Pointer to **NullableString** | Current plan name. | [optional] 
**Projects** | [**[]DomainListItemProjectsInner**](DomainListItemProjectsInner.md) | Projects in the domain. | 

## Methods

### NewDomainListItem

`func NewDomainListItem(identifier string, userId string, domainUsage []DomainListItemDomainUsageInner, userCount float32, usersInfo []DomainListItemUsersInfoInner, domain string, domainName string, disabled NullableDomainListItemDisabled, config DomainConfig, quotas DomainListItemQuotas, usage DomainListItemUsage, createdAt float32, subscription NullableDomainListItemSubscription, projects []DomainListItemProjectsInner, ) *DomainListItem`

NewDomainListItem instantiates a new DomainListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemWithDefaults

`func NewDomainListItemWithDefaults() *DomainListItem`

NewDomainListItemWithDefaults instantiates a new DomainListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainListItem) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainListItem) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainListItem) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetUserId

`func (o *DomainListItem) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *DomainListItem) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *DomainListItem) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetDomainUsage

`func (o *DomainListItem) GetDomainUsage() []DomainListItemDomainUsageInner`

GetDomainUsage returns the DomainUsage field if non-nil, zero value otherwise.

### GetDomainUsageOk

`func (o *DomainListItem) GetDomainUsageOk() (*[]DomainListItemDomainUsageInner, bool)`

GetDomainUsageOk returns a tuple with the DomainUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainUsage

`func (o *DomainListItem) SetDomainUsage(v []DomainListItemDomainUsageInner)`

SetDomainUsage sets DomainUsage field to given value.


### GetUserCount

`func (o *DomainListItem) GetUserCount() float32`

GetUserCount returns the UserCount field if non-nil, zero value otherwise.

### GetUserCountOk

`func (o *DomainListItem) GetUserCountOk() (*float32, bool)`

GetUserCountOk returns a tuple with the UserCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserCount

`func (o *DomainListItem) SetUserCount(v float32)`

SetUserCount sets UserCount field to given value.


### GetUsersInfo

`func (o *DomainListItem) GetUsersInfo() []DomainListItemUsersInfoInner`

GetUsersInfo returns the UsersInfo field if non-nil, zero value otherwise.

### GetUsersInfoOk

`func (o *DomainListItem) GetUsersInfoOk() (*[]DomainListItemUsersInfoInner, bool)`

GetUsersInfoOk returns a tuple with the UsersInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsersInfo

`func (o *DomainListItem) SetUsersInfo(v []DomainListItemUsersInfoInner)`

SetUsersInfo sets UsersInfo field to given value.


### GetDomain

`func (o *DomainListItem) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainListItem) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainListItem) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetDomainName

`func (o *DomainListItem) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *DomainListItem) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *DomainListItem) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.


### GetDisabled

`func (o *DomainListItem) GetDisabled() DomainListItemDisabled`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *DomainListItem) GetDisabledOk() (*DomainListItemDisabled, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *DomainListItem) SetDisabled(v DomainListItemDisabled)`

SetDisabled sets Disabled field to given value.


### SetDisabledNil

`func (o *DomainListItem) SetDisabledNil(b bool)`

 SetDisabledNil sets the value for Disabled to be an explicit nil

### UnsetDisabled
`func (o *DomainListItem) UnsetDisabled()`

UnsetDisabled ensures that no value is present for Disabled, not even an explicit nil
### GetConfig

`func (o *DomainListItem) GetConfig() DomainConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *DomainListItem) GetConfigOk() (*DomainConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *DomainListItem) SetConfig(v DomainConfig)`

SetConfig sets Config field to given value.


### GetQuotas

`func (o *DomainListItem) GetQuotas() DomainListItemQuotas`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *DomainListItem) GetQuotasOk() (*DomainListItemQuotas, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *DomainListItem) SetQuotas(v DomainListItemQuotas)`

SetQuotas sets Quotas field to given value.


### GetUsage

`func (o *DomainListItem) GetUsage() DomainListItemUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DomainListItem) GetUsageOk() (*DomainListItemUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DomainListItem) SetUsage(v DomainListItemUsage)`

SetUsage sets Usage field to given value.


### GetCreatedAt

`func (o *DomainListItem) GetCreatedAt() float32`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainListItem) GetCreatedAtOk() (*float32, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainListItem) SetCreatedAt(v float32)`

SetCreatedAt sets CreatedAt field to given value.


### GetSubscription

`func (o *DomainListItem) GetSubscription() DomainListItemSubscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *DomainListItem) GetSubscriptionOk() (*DomainListItemSubscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *DomainListItem) SetSubscription(v DomainListItemSubscription)`

SetSubscription sets Subscription field to given value.


### SetSubscriptionNil

`func (o *DomainListItem) SetSubscriptionNil(b bool)`

 SetSubscriptionNil sets the value for Subscription to be an explicit nil

### UnsetSubscription
`func (o *DomainListItem) UnsetSubscription()`

UnsetSubscription ensures that no value is present for Subscription, not even an explicit nil
### GetSubscriptionHistory

`func (o *DomainListItem) GetSubscriptionHistory() []DomainListItemSubscriptionHistoryInner`

GetSubscriptionHistory returns the SubscriptionHistory field if non-nil, zero value otherwise.

### GetSubscriptionHistoryOk

`func (o *DomainListItem) GetSubscriptionHistoryOk() (*[]DomainListItemSubscriptionHistoryInner, bool)`

GetSubscriptionHistoryOk returns a tuple with the SubscriptionHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionHistory

`func (o *DomainListItem) SetSubscriptionHistory(v []DomainListItemSubscriptionHistoryInner)`

SetSubscriptionHistory sets SubscriptionHistory field to given value.

### HasSubscriptionHistory

`func (o *DomainListItem) HasSubscriptionHistory() bool`

HasSubscriptionHistory returns a boolean if a field has been set.

### GetPlanName

`func (o *DomainListItem) GetPlanName() string`

GetPlanName returns the PlanName field if non-nil, zero value otherwise.

### GetPlanNameOk

`func (o *DomainListItem) GetPlanNameOk() (*string, bool)`

GetPlanNameOk returns a tuple with the PlanName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanName

`func (o *DomainListItem) SetPlanName(v string)`

SetPlanName sets PlanName field to given value.

### HasPlanName

`func (o *DomainListItem) HasPlanName() bool`

HasPlanName returns a boolean if a field has been set.

### SetPlanNameNil

`func (o *DomainListItem) SetPlanNameNil(b bool)`

 SetPlanNameNil sets the value for PlanName to be an explicit nil

### UnsetPlanName
`func (o *DomainListItem) UnsetPlanName()`

UnsetPlanName ensures that no value is present for PlanName, not even an explicit nil
### GetProjects

`func (o *DomainListItem) GetProjects() []DomainListItemProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *DomainListItem) GetProjectsOk() (*[]DomainListItemProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *DomainListItem) SetProjects(v []DomainListItemProjectsInner)`

SetProjects sets Projects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


