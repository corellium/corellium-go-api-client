# InstanceTraceState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **NullableBool** | Whether tracing is enabled. | [optional] 
**Length** | Pointer to **float32** | Length of trace data. | [optional] 
**Filter** | Pointer to [**[]InstanceTraceFilter**](InstanceTraceFilter.md) | Active trace filters matching traits to values. | [optional] 

## Methods

### NewInstanceTraceState

`func NewInstanceTraceState() *InstanceTraceState`

NewInstanceTraceState instantiates a new InstanceTraceState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceTraceStateWithDefaults

`func NewInstanceTraceStateWithDefaults() *InstanceTraceState`

NewInstanceTraceStateWithDefaults instantiates a new InstanceTraceState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *InstanceTraceState) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *InstanceTraceState) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *InstanceTraceState) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *InstanceTraceState) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *InstanceTraceState) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *InstanceTraceState) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetLength

`func (o *InstanceTraceState) GetLength() float32`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *InstanceTraceState) GetLengthOk() (*float32, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *InstanceTraceState) SetLength(v float32)`

SetLength sets Length field to given value.

### HasLength

`func (o *InstanceTraceState) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetFilter

`func (o *InstanceTraceState) GetFilter() []InstanceTraceFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *InstanceTraceState) GetFilterOk() (*[]InstanceTraceFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *InstanceTraceState) SetFilter(v []InstanceTraceFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *InstanceTraceState) HasFilter() bool`

HasFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


