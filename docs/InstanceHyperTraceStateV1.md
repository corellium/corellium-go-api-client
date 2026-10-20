# InstanceHyperTraceStateV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **NullableString** | HyperTrace (btrace) status | [optional] 
**Length** | Pointer to **NullableFloat32** | Length of trace data | [optional] 
**Filter** | Pointer to **NullableString** | Trace filter expression | [optional] 

## Methods

### NewInstanceHyperTraceStateV1

`func NewInstanceHyperTraceStateV1() *InstanceHyperTraceStateV1`

NewInstanceHyperTraceStateV1 instantiates a new InstanceHyperTraceStateV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceHyperTraceStateV1WithDefaults

`func NewInstanceHyperTraceStateV1WithDefaults() *InstanceHyperTraceStateV1`

NewInstanceHyperTraceStateV1WithDefaults instantiates a new InstanceHyperTraceStateV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *InstanceHyperTraceStateV1) GetEnabled() string`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *InstanceHyperTraceStateV1) GetEnabledOk() (*string, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *InstanceHyperTraceStateV1) SetEnabled(v string)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *InstanceHyperTraceStateV1) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *InstanceHyperTraceStateV1) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *InstanceHyperTraceStateV1) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetLength

`func (o *InstanceHyperTraceStateV1) GetLength() float32`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *InstanceHyperTraceStateV1) GetLengthOk() (*float32, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *InstanceHyperTraceStateV1) SetLength(v float32)`

SetLength sets Length field to given value.

### HasLength

`func (o *InstanceHyperTraceStateV1) HasLength() bool`

HasLength returns a boolean if a field has been set.

### SetLengthNil

`func (o *InstanceHyperTraceStateV1) SetLengthNil(b bool)`

 SetLengthNil sets the value for Length to be an explicit nil

### UnsetLength
`func (o *InstanceHyperTraceStateV1) UnsetLength()`

UnsetLength ensures that no value is present for Length, not even an explicit nil
### GetFilter

`func (o *InstanceHyperTraceStateV1) GetFilter() string`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *InstanceHyperTraceStateV1) GetFilterOk() (*string, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *InstanceHyperTraceStateV1) SetFilter(v string)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *InstanceHyperTraceStateV1) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### SetFilterNil

`func (o *InstanceHyperTraceStateV1) SetFilterNil(b bool)`

 SetFilterNil sets the value for Filter to be an explicit nil

### UnsetFilter
`func (o *InstanceHyperTraceStateV1) UnsetFilter()`

UnsetFilter ensures that no value is present for Filter, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


