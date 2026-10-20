# UpdateTrialRequestParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtensionDays** | Pointer to **NullableFloat32** | Days to add to the trial before it ends. | [optional] 
**ExtensionHours** | Pointer to **NullableFloat32** | Hours of usage to add to the trial. This will be either device-hours or core-hours depending on the trial. | [optional] 

## Methods

### NewUpdateTrialRequestParams

`func NewUpdateTrialRequestParams() *UpdateTrialRequestParams`

NewUpdateTrialRequestParams instantiates a new UpdateTrialRequestParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTrialRequestParamsWithDefaults

`func NewUpdateTrialRequestParamsWithDefaults() *UpdateTrialRequestParams`

NewUpdateTrialRequestParamsWithDefaults instantiates a new UpdateTrialRequestParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtensionDays

`func (o *UpdateTrialRequestParams) GetExtensionDays() float32`

GetExtensionDays returns the ExtensionDays field if non-nil, zero value otherwise.

### GetExtensionDaysOk

`func (o *UpdateTrialRequestParams) GetExtensionDaysOk() (*float32, bool)`

GetExtensionDaysOk returns a tuple with the ExtensionDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtensionDays

`func (o *UpdateTrialRequestParams) SetExtensionDays(v float32)`

SetExtensionDays sets ExtensionDays field to given value.

### HasExtensionDays

`func (o *UpdateTrialRequestParams) HasExtensionDays() bool`

HasExtensionDays returns a boolean if a field has been set.

### SetExtensionDaysNil

`func (o *UpdateTrialRequestParams) SetExtensionDaysNil(b bool)`

 SetExtensionDaysNil sets the value for ExtensionDays to be an explicit nil

### UnsetExtensionDays
`func (o *UpdateTrialRequestParams) UnsetExtensionDays()`

UnsetExtensionDays ensures that no value is present for ExtensionDays, not even an explicit nil
### GetExtensionHours

`func (o *UpdateTrialRequestParams) GetExtensionHours() float32`

GetExtensionHours returns the ExtensionHours field if non-nil, zero value otherwise.

### GetExtensionHoursOk

`func (o *UpdateTrialRequestParams) GetExtensionHoursOk() (*float32, bool)`

GetExtensionHoursOk returns a tuple with the ExtensionHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtensionHours

`func (o *UpdateTrialRequestParams) SetExtensionHours(v float32)`

SetExtensionHours sets ExtensionHours field to given value.

### HasExtensionHours

`func (o *UpdateTrialRequestParams) HasExtensionHours() bool`

HasExtensionHours returns a boolean if a field has been set.

### SetExtensionHoursNil

`func (o *UpdateTrialRequestParams) SetExtensionHoursNil(b bool)`

 SetExtensionHoursNil sets the value for ExtensionHours to be an explicit nil

### UnsetExtensionHours
`func (o *UpdateTrialRequestParams) UnsetExtensionHours()`

UnsetExtensionHours ensures that no value is present for ExtensionHours, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


