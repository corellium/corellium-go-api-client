# InstanceTraceStateV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **NullableBool** | Whether tracing is enabled | [optional] 
**Length** | Pointer to **NullableFloat32** | Length of trace data | [optional] 
**Filter** | Pointer to **NullableString** | Trace filter expression | [optional] 

## Methods

### NewInstanceTraceStateV1

`func NewInstanceTraceStateV1() *InstanceTraceStateV1`

NewInstanceTraceStateV1 instantiates a new InstanceTraceStateV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceTraceStateV1WithDefaults

`func NewInstanceTraceStateV1WithDefaults() *InstanceTraceStateV1`

NewInstanceTraceStateV1WithDefaults instantiates a new InstanceTraceStateV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *InstanceTraceStateV1) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *InstanceTraceStateV1) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *InstanceTraceStateV1) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *InstanceTraceStateV1) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *InstanceTraceStateV1) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *InstanceTraceStateV1) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetLength

`func (o *InstanceTraceStateV1) GetLength() float32`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *InstanceTraceStateV1) GetLengthOk() (*float32, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *InstanceTraceStateV1) SetLength(v float32)`

SetLength sets Length field to given value.

### HasLength

`func (o *InstanceTraceStateV1) HasLength() bool`

HasLength returns a boolean if a field has been set.

### SetLengthNil

`func (o *InstanceTraceStateV1) SetLengthNil(b bool)`

 SetLengthNil sets the value for Length to be an explicit nil

### UnsetLength
`func (o *InstanceTraceStateV1) UnsetLength()`

UnsetLength ensures that no value is present for Length, not even an explicit nil
### GetFilter

`func (o *InstanceTraceStateV1) GetFilter() string`

GetFilter returns the Filter field if non-nil, zero value otherwise.

### GetFilterOk

`func (o *InstanceTraceStateV1) GetFilterOk() (*string, bool)`

GetFilterOk returns a tuple with the Filter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilter

`func (o *InstanceTraceStateV1) SetFilter(v string)`

SetFilter sets Filter field to given value.

### HasFilter

`func (o *InstanceTraceStateV1) HasFilter() bool`

HasFilter returns a boolean if a field has been set.

### SetFilterNil

`func (o *InstanceTraceStateV1) SetFilterNil(b bool)`

 SetFilterNil sets the value for Filter to be an explicit nil

### UnsetFilter
`func (o *InstanceTraceStateV1) UnsetFilter()`

UnsetFilter ensures that no value is present for Filter, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


