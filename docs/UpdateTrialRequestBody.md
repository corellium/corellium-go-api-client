# UpdateTrialRequestBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtensionDays** | Pointer to **float32** | Days to add to the trial before it ends. | [optional] 
**ExtensionHours** | Pointer to **float32** | Hours of usage to add to the trial (device-hours or core-hours). | [optional] 

## Methods

### NewUpdateTrialRequestBody

`func NewUpdateTrialRequestBody() *UpdateTrialRequestBody`

NewUpdateTrialRequestBody instantiates a new UpdateTrialRequestBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateTrialRequestBodyWithDefaults

`func NewUpdateTrialRequestBodyWithDefaults() *UpdateTrialRequestBody`

NewUpdateTrialRequestBodyWithDefaults instantiates a new UpdateTrialRequestBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtensionDays

`func (o *UpdateTrialRequestBody) GetExtensionDays() float32`

GetExtensionDays returns the ExtensionDays field if non-nil, zero value otherwise.

### GetExtensionDaysOk

`func (o *UpdateTrialRequestBody) GetExtensionDaysOk() (*float32, bool)`

GetExtensionDaysOk returns a tuple with the ExtensionDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtensionDays

`func (o *UpdateTrialRequestBody) SetExtensionDays(v float32)`

SetExtensionDays sets ExtensionDays field to given value.

### HasExtensionDays

`func (o *UpdateTrialRequestBody) HasExtensionDays() bool`

HasExtensionDays returns a boolean if a field has been set.

### GetExtensionHours

`func (o *UpdateTrialRequestBody) GetExtensionHours() float32`

GetExtensionHours returns the ExtensionHours field if non-nil, zero value otherwise.

### GetExtensionHoursOk

`func (o *UpdateTrialRequestBody) GetExtensionHoursOk() (*float32, bool)`

GetExtensionHoursOk returns a tuple with the ExtensionHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtensionHours

`func (o *UpdateTrialRequestBody) SetExtensionHours(v float32)`

SetExtensionHours sets ExtensionHours field to given value.

### HasExtensionHours

`func (o *UpdateTrialRequestBody) HasExtensionHours() bool`

HasExtensionHours returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


