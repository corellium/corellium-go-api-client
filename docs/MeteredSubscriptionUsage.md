# MeteredSubscriptionUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BurstRate** | **float32** | Unit price for burst usage. | 
**AllocatedHours** | **float32** | Allocated hours. | 
**PlanBilledAmount** | **float32** | Plan cost. | 
**BurstBilledAmount** | **float32** | Burst amount billed. | 
**BurstBilledUnits** | **float32** | Burst units billed. | 
**BurstOutstandingAmount** | **float32** | Outstanding burst amount. | 
**BurstOutstandingUnits** | **float32** | Outstanding burst units. | 
**TotalUsageAmount** | **float32** | Total cost in cents for the period. | 
**TotalUsedUnits** | **float32** | Total used units for the period. | 

## Methods

### NewMeteredSubscriptionUsage

`func NewMeteredSubscriptionUsage(burstRate float32, allocatedHours float32, planBilledAmount float32, burstBilledAmount float32, burstBilledUnits float32, burstOutstandingAmount float32, burstOutstandingUnits float32, totalUsageAmount float32, totalUsedUnits float32, ) *MeteredSubscriptionUsage`

NewMeteredSubscriptionUsage instantiates a new MeteredSubscriptionUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMeteredSubscriptionUsageWithDefaults

`func NewMeteredSubscriptionUsageWithDefaults() *MeteredSubscriptionUsage`

NewMeteredSubscriptionUsageWithDefaults instantiates a new MeteredSubscriptionUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBurstRate

`func (o *MeteredSubscriptionUsage) GetBurstRate() float32`

GetBurstRate returns the BurstRate field if non-nil, zero value otherwise.

### GetBurstRateOk

`func (o *MeteredSubscriptionUsage) GetBurstRateOk() (*float32, bool)`

GetBurstRateOk returns a tuple with the BurstRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstRate

`func (o *MeteredSubscriptionUsage) SetBurstRate(v float32)`

SetBurstRate sets BurstRate field to given value.


### GetAllocatedHours

`func (o *MeteredSubscriptionUsage) GetAllocatedHours() float32`

GetAllocatedHours returns the AllocatedHours field if non-nil, zero value otherwise.

### GetAllocatedHoursOk

`func (o *MeteredSubscriptionUsage) GetAllocatedHoursOk() (*float32, bool)`

GetAllocatedHoursOk returns a tuple with the AllocatedHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocatedHours

`func (o *MeteredSubscriptionUsage) SetAllocatedHours(v float32)`

SetAllocatedHours sets AllocatedHours field to given value.


### GetPlanBilledAmount

`func (o *MeteredSubscriptionUsage) GetPlanBilledAmount() float32`

GetPlanBilledAmount returns the PlanBilledAmount field if non-nil, zero value otherwise.

### GetPlanBilledAmountOk

`func (o *MeteredSubscriptionUsage) GetPlanBilledAmountOk() (*float32, bool)`

GetPlanBilledAmountOk returns a tuple with the PlanBilledAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanBilledAmount

`func (o *MeteredSubscriptionUsage) SetPlanBilledAmount(v float32)`

SetPlanBilledAmount sets PlanBilledAmount field to given value.


### GetBurstBilledAmount

`func (o *MeteredSubscriptionUsage) GetBurstBilledAmount() float32`

GetBurstBilledAmount returns the BurstBilledAmount field if non-nil, zero value otherwise.

### GetBurstBilledAmountOk

`func (o *MeteredSubscriptionUsage) GetBurstBilledAmountOk() (*float32, bool)`

GetBurstBilledAmountOk returns a tuple with the BurstBilledAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstBilledAmount

`func (o *MeteredSubscriptionUsage) SetBurstBilledAmount(v float32)`

SetBurstBilledAmount sets BurstBilledAmount field to given value.


### GetBurstBilledUnits

`func (o *MeteredSubscriptionUsage) GetBurstBilledUnits() float32`

GetBurstBilledUnits returns the BurstBilledUnits field if non-nil, zero value otherwise.

### GetBurstBilledUnitsOk

`func (o *MeteredSubscriptionUsage) GetBurstBilledUnitsOk() (*float32, bool)`

GetBurstBilledUnitsOk returns a tuple with the BurstBilledUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstBilledUnits

`func (o *MeteredSubscriptionUsage) SetBurstBilledUnits(v float32)`

SetBurstBilledUnits sets BurstBilledUnits field to given value.


### GetBurstOutstandingAmount

`func (o *MeteredSubscriptionUsage) GetBurstOutstandingAmount() float32`

GetBurstOutstandingAmount returns the BurstOutstandingAmount field if non-nil, zero value otherwise.

### GetBurstOutstandingAmountOk

`func (o *MeteredSubscriptionUsage) GetBurstOutstandingAmountOk() (*float32, bool)`

GetBurstOutstandingAmountOk returns a tuple with the BurstOutstandingAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstOutstandingAmount

`func (o *MeteredSubscriptionUsage) SetBurstOutstandingAmount(v float32)`

SetBurstOutstandingAmount sets BurstOutstandingAmount field to given value.


### GetBurstOutstandingUnits

`func (o *MeteredSubscriptionUsage) GetBurstOutstandingUnits() float32`

GetBurstOutstandingUnits returns the BurstOutstandingUnits field if non-nil, zero value otherwise.

### GetBurstOutstandingUnitsOk

`func (o *MeteredSubscriptionUsage) GetBurstOutstandingUnitsOk() (*float32, bool)`

GetBurstOutstandingUnitsOk returns a tuple with the BurstOutstandingUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBurstOutstandingUnits

`func (o *MeteredSubscriptionUsage) SetBurstOutstandingUnits(v float32)`

SetBurstOutstandingUnits sets BurstOutstandingUnits field to given value.


### GetTotalUsageAmount

`func (o *MeteredSubscriptionUsage) GetTotalUsageAmount() float32`

GetTotalUsageAmount returns the TotalUsageAmount field if non-nil, zero value otherwise.

### GetTotalUsageAmountOk

`func (o *MeteredSubscriptionUsage) GetTotalUsageAmountOk() (*float32, bool)`

GetTotalUsageAmountOk returns a tuple with the TotalUsageAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsageAmount

`func (o *MeteredSubscriptionUsage) SetTotalUsageAmount(v float32)`

SetTotalUsageAmount sets TotalUsageAmount field to given value.


### GetTotalUsedUnits

`func (o *MeteredSubscriptionUsage) GetTotalUsedUnits() float32`

GetTotalUsedUnits returns the TotalUsedUnits field if non-nil, zero value otherwise.

### GetTotalUsedUnitsOk

`func (o *MeteredSubscriptionUsage) GetTotalUsedUnitsOk() (*float32, bool)`

GetTotalUsedUnitsOk returns a tuple with the TotalUsedUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsedUnits

`func (o *MeteredSubscriptionUsage) SetTotalUsedUnits(v float32)`

SetTotalUsedUnits sets TotalUsedUnits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


