# InstanceHyperTraceState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **NullableString** | HyperTrace (btrace) status. | [optional] 
**Length** | Pointer to **float32** | Length of trace data. | [optional] 
**Filter** | Pointer to [**[]InstanceTraceFilter**](InstanceTraceFilter.md) | Active trace filters matching traits to values. | [optional] 

## Methods

### NewInstanceHyperTraceState

`func NewInstanceHyperTraceState() *InstanceHyperTraceState`

NewInstanceHyperTraceState instantiates a new InstanceHyperTraceState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceHyperTraceStateWithDefaults

`func NewInstanceHyperTraceStateWithDefaults() *InstanceHyperTraceState`

NewInstanceHyperTraceStateWithDefaults instantiates a new InstanceHyperTraceState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *InstanceHyperTraceState) GetEnabled() string`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *InstanceHyperTraceState) GetEnabledOk() (*string, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *InstanceHyperTraceState) SetEnabled(v string)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *InstanceHyperTraceState) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *InstanceHyperTraceState) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *InstanceHyperTraceState) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetLength

`func (o *InstanceHyperTraceState) GetLength() float32`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *InstanceHyperTraceState) GetLengthOk() (*float32, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *InstanceHyperTraceState) SetLength(v float32)`

SetLength sets Length field to given value.

### HasLength

`func (o *InstanceHyperTraceState) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetFilter

`func (o *InstanceHyperTraceState) GetFilter() []InstanceTraceFilter`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *InstanceHyperTraceState) GetFilterOk() (*[]InstanceTraceFilter, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *InstanceHyperTraceState) SetFilter(v []InstanceTraceFilter)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *InstanceHyperTraceState) HasFilter() bool`

HasFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


