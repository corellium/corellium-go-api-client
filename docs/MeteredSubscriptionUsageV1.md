# MeteredSubscriptionUsageV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BurstRate** | Pointer to **NullableFloat32** | Unit price | [optional] 
**AllocatedHours** | Pointer to **NullableFloat32** | Allocated hours | [optional] 
**PlanBilledAmount** | Pointer to **NullableFloat32** | Plan cost | [optional] 
**PlanBilledUnits** | Pointer to **NullableFloat32** | Units included in plan | [optional] 
**BurstBilledAmount** | Pointer to **NullableFloat32** | Amount billed | [optional] 
**BurstBilledUnits** | Pointer to **NullableFloat32** | Units billed | [optional] 
**BurstOutstandingAmount** | Pointer to **NullableFloat32** | Outstanding amount | [optional] 
**BurstOutstandingUnits** | Pointer to **NullableFloat32** | Outstanding units | [optional] 
**TotalUsageAmount** | Pointer to **NullableFloat32** | Total cost in cents for current period | [optional] 
**TotalUsedUnits** | Pointer to **NullableFloat32** | Total used units for current period | [optional] 

## Methods

### NewMeteredSubscriptionUsageV1

`func NewMeteredSubscriptionUsageV1() *MeteredSubscriptionUsageV1`

NewMeteredSubscriptionUsageV1 instantiates a new MeteredSubscriptionUsageV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeteredSubscriptionUsageV1WithDefaults

`func NewMeteredSubscriptionUsageV1WithDefaults() *MeteredSubscriptionUsageV1`

NewMeteredSubscriptionUsageV1WithDefaults instantiates a new MeteredSubscriptionUsageV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBurstRate

`func (o *MeteredSubscriptionUsageV1) GetBurstRate() float32`

GetBurstRate returns the BurstRate field if non-nil, zero value otherwise.

### GetBurstRateOk

`func (o *MeteredSubscriptionUsageV1) GetBurstRateOk() (*float32, bool)`

GetBurstRateOk returns a tuple with the BurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstRate

`func (o *MeteredSubscriptionUsageV1) SetBurstRate(v float32)`

SetBurstRate sets BurstRate field to given value.

### HasBurstRate

`func (o *MeteredSubscriptionUsageV1) HasBurstRate() bool`

HasBurstRate returns a boolean if a field has been set.

### SetBurstRateNil

`func (o *MeteredSubscriptionUsageV1) SetBurstRateNil(b bool)`

 SetBurstRateNil sets the value for BurstRate to be an explicit nil

### UnsetBurstRate
`func (o *MeteredSubscriptionUsageV1) UnsetBurstRate()`

UnsetBurstRate ensures that no value is present for BurstRate, not even an explicit nil
### GetAllocatedHours

`func (o *MeteredSubscriptionUsageV1) GetAllocatedHours() float32`

GetAllocatedHours returns the AllocatedHours field if non-nil, zero value otherwise.

### GetAllocatedHoursOk

`func (o *MeteredSubscriptionUsageV1) GetAllocatedHoursOk() (*float32, bool)`

GetAllocatedHoursOk returns a tuple with the AllocatedHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocatedHours

`func (o *MeteredSubscriptionUsageV1) SetAllocatedHours(v float32)`

SetAllocatedHours sets AllocatedHours field to given value.

### HasAllocatedHours

`func (o *MeteredSubscriptionUsageV1) HasAllocatedHours() bool`

HasAllocatedHours returns a boolean if a field has been set.

### SetAllocatedHoursNil

`func (o *MeteredSubscriptionUsageV1) SetAllocatedHoursNil(b bool)`

 SetAllocatedHoursNil sets the value for AllocatedHours to be an explicit nil

### UnsetAllocatedHours
`func (o *MeteredSubscriptionUsageV1) UnsetAllocatedHours()`

UnsetAllocatedHours ensures that no value is present for AllocatedHours, not even an explicit nil
### GetPlanBilledAmount

`func (o *MeteredSubscriptionUsageV1) GetPlanBilledAmount() float32`

GetPlanBilledAmount returns the PlanBilledAmount field if non-nil, zero value otherwise.

### GetPlanBilledAmountOk

`func (o *MeteredSubscriptionUsageV1) GetPlanBilledAmountOk() (*float32, bool)`

GetPlanBilledAmountOk returns a tuple with the PlanBilledAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanBilledAmount

`func (o *MeteredSubscriptionUsageV1) SetPlanBilledAmount(v float32)`

SetPlanBilledAmount sets PlanBilledAmount field to given value.

### HasPlanBilledAmount

`func (o *MeteredSubscriptionUsageV1) HasPlanBilledAmount() bool`

HasPlanBilledAmount returns a boolean if a field has been set.

### SetPlanBilledAmountNil

`func (o *MeteredSubscriptionUsageV1) SetPlanBilledAmountNil(b bool)`

 SetPlanBilledAmountNil sets the value for PlanBilledAmount to be an explicit nil

### UnsetPlanBilledAmount
`func (o *MeteredSubscriptionUsageV1) UnsetPlanBilledAmount()`

UnsetPlanBilledAmount ensures that no value is present for PlanBilledAmount, not even an explicit nil
### GetPlanBilledUnits

`func (o *MeteredSubscriptionUsageV1) GetPlanBilledUnits() float32`

GetPlanBilledUnits returns the PlanBilledUnits field if non-nil, zero value otherwise.

### GetPlanBilledUnitsOk

`func (o *MeteredSubscriptionUsageV1) GetPlanBilledUnitsOk() (*float32, bool)`

GetPlanBilledUnitsOk returns a tuple with the PlanBilledUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanBilledUnits

`func (o *MeteredSubscriptionUsageV1) SetPlanBilledUnits(v float32)`

SetPlanBilledUnits sets PlanBilledUnits field to given value.

### HasPlanBilledUnits

`func (o *MeteredSubscriptionUsageV1) HasPlanBilledUnits() bool`

HasPlanBilledUnits returns a boolean if a field has been set.

### SetPlanBilledUnitsNil

`func (o *MeteredSubscriptionUsageV1) SetPlanBilledUnitsNil(b bool)`

 SetPlanBilledUnitsNil sets the value for PlanBilledUnits to be an explicit nil

### UnsetPlanBilledUnits
`func (o *MeteredSubscriptionUsageV1) UnsetPlanBilledUnits()`

UnsetPlanBilledUnits ensures that no value is present for PlanBilledUnits, not even an explicit nil
### GetBurstBilledAmount

`func (o *MeteredSubscriptionUsageV1) GetBurstBilledAmount() float32`

GetBurstBilledAmount returns the BurstBilledAmount field if non-nil, zero value otherwise.

### GetBurstBilledAmountOk

`func (o *MeteredSubscriptionUsageV1) GetBurstBilledAmountOk() (*float32, bool)`

GetBurstBilledAmountOk returns a tuple with the BurstBilledAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstBilledAmount

`func (o *MeteredSubscriptionUsageV1) SetBurstBilledAmount(v float32)`

SetBurstBilledAmount sets BurstBilledAmount field to given value.

### HasBurstBilledAmount

`func (o *MeteredSubscriptionUsageV1) HasBurstBilledAmount() bool`

HasBurstBilledAmount returns a boolean if a field has been set.

### SetBurstBilledAmountNil

`func (o *MeteredSubscriptionUsageV1) SetBurstBilledAmountNil(b bool)`

 SetBurstBilledAmountNil sets the value for BurstBilledAmount to be an explicit nil

### UnsetBurstBilledAmount
`func (o *MeteredSubscriptionUsageV1) UnsetBurstBilledAmount()`

UnsetBurstBilledAmount ensures that no value is present for BurstBilledAmount, not even an explicit nil
### GetBurstBilledUnits

`func (o *MeteredSubscriptionUsageV1) GetBurstBilledUnits() float32`

GetBurstBilledUnits returns the BurstBilledUnits field if non-nil, zero value otherwise.

### GetBurstBilledUnitsOk

`func (o *MeteredSubscriptionUsageV1) GetBurstBilledUnitsOk() (*float32, bool)`

GetBurstBilledUnitsOk returns a tuple with the BurstBilledUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstBilledUnits

`func (o *MeteredSubscriptionUsageV1) SetBurstBilledUnits(v float32)`

SetBurstBilledUnits sets BurstBilledUnits field to given value.

### HasBurstBilledUnits

`func (o *MeteredSubscriptionUsageV1) HasBurstBilledUnits() bool`

HasBurstBilledUnits returns a boolean if a field has been set.

### SetBurstBilledUnitsNil

`func (o *MeteredSubscriptionUsageV1) SetBurstBilledUnitsNil(b bool)`

 SetBurstBilledUnitsNil sets the value for BurstBilledUnits to be an explicit nil

### UnsetBurstBilledUnits
`func (o *MeteredSubscriptionUsageV1) UnsetBurstBilledUnits()`

UnsetBurstBilledUnits ensures that no value is present for BurstBilledUnits, not even an explicit nil
### GetBurstOutstandingAmount

`func (o *MeteredSubscriptionUsageV1) GetBurstOutstandingAmount() float32`

GetBurstOutstandingAmount returns the BurstOutstandingAmount field if non-nil, zero value otherwise.

### GetBurstOutstandingAmountOk

`func (o *MeteredSubscriptionUsageV1) GetBurstOutstandingAmountOk() (*float32, bool)`

GetBurstOutstandingAmountOk returns a tuple with the BurstOutstandingAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstOutstandingAmount

`func (o *MeteredSubscriptionUsageV1) SetBurstOutstandingAmount(v float32)`

SetBurstOutstandingAmount sets BurstOutstandingAmount field to given value.

### HasBurstOutstandingAmount

`func (o *MeteredSubscriptionUsageV1) HasBurstOutstandingAmount() bool`

HasBurstOutstandingAmount returns a boolean if a field has been set.

### SetBurstOutstandingAmountNil

`func (o *MeteredSubscriptionUsageV1) SetBurstOutstandingAmountNil(b bool)`

 SetBurstOutstandingAmountNil sets the value for BurstOutstandingAmount to be an explicit nil

### UnsetBurstOutstandingAmount
`func (o *MeteredSubscriptionUsageV1) UnsetBurstOutstandingAmount()`

UnsetBurstOutstandingAmount ensures that no value is present for BurstOutstandingAmount, not even an explicit nil
### GetBurstOutstandingUnits

`func (o *MeteredSubscriptionUsageV1) GetBurstOutstandingUnits() float32`

GetBurstOutstandingUnits returns the BurstOutstandingUnits field if non-nil, zero value otherwise.

### GetBurstOutstandingUnitsOk

`func (o *MeteredSubscriptionUsageV1) GetBurstOutstandingUnitsOk() (*float32, bool)`

GetBurstOutstandingUnitsOk returns a tuple with the BurstOutstandingUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstOutstandingUnits

`func (o *MeteredSubscriptionUsageV1) SetBurstOutstandingUnits(v float32)`

SetBurstOutstandingUnits sets BurstOutstandingUnits field to given value.

### HasBurstOutstandingUnits

`func (o *MeteredSubscriptionUsageV1) HasBurstOutstandingUnits() bool`

HasBurstOutstandingUnits returns a boolean if a field has been set.

### SetBurstOutstandingUnitsNil

`func (o *MeteredSubscriptionUsageV1) SetBurstOutstandingUnitsNil(b bool)`

 SetBurstOutstandingUnitsNil sets the value for BurstOutstandingUnits to be an explicit nil

### UnsetBurstOutstandingUnits
`func (o *MeteredSubscriptionUsageV1) UnsetBurstOutstandingUnits()`

UnsetBurstOutstandingUnits ensures that no value is present for BurstOutstandingUnits, not even an explicit nil
### GetTotalUsageAmount

`func (o *MeteredSubscriptionUsageV1) GetTotalUsageAmount() float32`

GetTotalUsageAmount returns the TotalUsageAmount field if non-nil, zero value otherwise.

### GetTotalUsageAmountOk

`func (o *MeteredSubscriptionUsageV1) GetTotalUsageAmountOk() (*float32, bool)`

GetTotalUsageAmountOk returns a tuple with the TotalUsageAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsageAmount

`func (o *MeteredSubscriptionUsageV1) SetTotalUsageAmount(v float32)`

SetTotalUsageAmount sets TotalUsageAmount field to given value.

### HasTotalUsageAmount

`func (o *MeteredSubscriptionUsageV1) HasTotalUsageAmount() bool`

HasTotalUsageAmount returns a boolean if a field has been set.

### SetTotalUsageAmountNil

`func (o *MeteredSubscriptionUsageV1) SetTotalUsageAmountNil(b bool)`

 SetTotalUsageAmountNil sets the value for TotalUsageAmount to be an explicit nil

### UnsetTotalUsageAmount
`func (o *MeteredSubscriptionUsageV1) UnsetTotalUsageAmount()`

UnsetTotalUsageAmount ensures that no value is present for TotalUsageAmount, not even an explicit nil
### GetTotalUsedUnits

`func (o *MeteredSubscriptionUsageV1) GetTotalUsedUnits() float32`

GetTotalUsedUnits returns the TotalUsedUnits field if non-nil, zero value otherwise.

### GetTotalUsedUnitsOk

`func (o *MeteredSubscriptionUsageV1) GetTotalUsedUnitsOk() (*float32, bool)`

GetTotalUsedUnitsOk returns a tuple with the TotalUsedUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsedUnits

`func (o *MeteredSubscriptionUsageV1) SetTotalUsedUnits(v float32)`

SetTotalUsedUnits sets TotalUsedUnits field to given value.

### HasTotalUsedUnits

`func (o *MeteredSubscriptionUsageV1) HasTotalUsedUnits() bool`

HasTotalUsedUnits returns a boolean if a field has been set.

### SetTotalUsedUnitsNil

`func (o *MeteredSubscriptionUsageV1) SetTotalUsedUnitsNil(b bool)`

 SetTotalUsedUnitsNil sets the value for TotalUsedUnits to be an explicit nil

### UnsetTotalUsedUnits
`func (o *MeteredSubscriptionUsageV1) UnsetTotalUsedUnits()`

UnsetTotalUsedUnits ensures that no value is present for TotalUsedUnits, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


