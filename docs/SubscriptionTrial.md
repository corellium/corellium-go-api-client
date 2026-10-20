# SubscriptionTrial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | Trial status. | 
**Start** | **NullableTime** | Trial start time, or null. | 
**End** | **NullableTime** | Trial end time, or null. | 
**UsedHours** | **NullableFloat32** | Trial hours used, or null. | 
**MaxHours** | **NullableFloat32** | Trial hour allowance, or null. | 

## Methods

### NewSubscriptionTrial

`func NewSubscriptionTrial(status string, start NullableTime, end NullableTime, usedHours NullableFloat32, maxHours NullableFloat32, ) *SubscriptionTrial`

NewSubscriptionTrial instantiates a new SubscriptionTrial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionTrialWithDefaults

`func NewSubscriptionTrialWithDefaults() *SubscriptionTrial`

NewSubscriptionTrialWithDefaults instantiates a new SubscriptionTrial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *SubscriptionTrial) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionTrial) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionTrial) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStart

`func (o *SubscriptionTrial) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *SubscriptionTrial) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *SubscriptionTrial) SetStart(v time.Time)`

SetStart sets Start field to given value.


### SetStartNil

`func (o *SubscriptionTrial) SetStartNil(b bool)`

 SetStartNil sets the value for Start to be an explicit nil

### UnsetStart
`func (o *SubscriptionTrial) UnsetStart()`

UnsetStart ensures that no value is present for Start, not even an explicit nil
### GetEnd

`func (o *SubscriptionTrial) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *SubscriptionTrial) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *SubscriptionTrial) SetEnd(v time.Time)`

SetEnd sets End field to given value.


### SetEndNil

`func (o *SubscriptionTrial) SetEndNil(b bool)`

 SetEndNil sets the value for End to be an explicit nil

### UnsetEnd
`func (o *SubscriptionTrial) UnsetEnd()`

UnsetEnd ensures that no value is present for End, not even an explicit nil
### GetUsedHours

`func (o *SubscriptionTrial) GetUsedHours() float32`

GetUsedHours returns the UsedHours field if non-nil, zero value otherwise.

### GetUsedHoursOk

`func (o *SubscriptionTrial) GetUsedHoursOk() (*float32, bool)`

GetUsedHoursOk returns a tuple with the UsedHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsedHours

`func (o *SubscriptionTrial) SetUsedHours(v float32)`

SetUsedHours sets UsedHours field to given value.


### SetUsedHoursNil

`func (o *SubscriptionTrial) SetUsedHoursNil(b bool)`

 SetUsedHoursNil sets the value for UsedHours to be an explicit nil

### UnsetUsedHours
`func (o *SubscriptionTrial) UnsetUsedHours()`

UnsetUsedHours ensures that no value is present for UsedHours, not even an explicit nil
### GetMaxHours

`func (o *SubscriptionTrial) GetMaxHours() float32`

GetMaxHours returns the MaxHours field if non-nil, zero value otherwise.

### GetMaxHoursOk

`func (o *SubscriptionTrial) GetMaxHoursOk() (*float32, bool)`

GetMaxHoursOk returns a tuple with the MaxHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxHours

`func (o *SubscriptionTrial) SetMaxHours(v float32)`

SetMaxHours sets MaxHours field to given value.


### SetMaxHoursNil

`func (o *SubscriptionTrial) SetMaxHoursNil(b bool)`

 SetMaxHoursNil sets the value for MaxHours to be an explicit nil

### UnsetMaxHours
`func (o *SubscriptionTrial) UnsetMaxHours()`

UnsetMaxHours ensures that no value is present for MaxHours, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


