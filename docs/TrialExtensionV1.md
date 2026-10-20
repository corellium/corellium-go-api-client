# TrialExtensionV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Duration** | Pointer to **NullableFloat32** | how many additional days? | [optional] 
**Reason** | Pointer to **NullableString** | why does the user want more time? | [optional] 
**Denied** | Pointer to **NullableBool** |  | [optional] 
**DeniedReason** | Pointer to **NullableString** | explanation for why the request was denied | [optional] 

## Methods

### NewTrialExtensionV1

`func NewTrialExtensionV1() *TrialExtensionV1`

NewTrialExtensionV1 instantiates a new TrialExtensionV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrialExtensionV1WithDefaults

`func NewTrialExtensionV1WithDefaults() *TrialExtensionV1`

NewTrialExtensionV1WithDefaults instantiates a new TrialExtensionV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuration

`func (o *TrialExtensionV1) GetDuration() float32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *TrialExtensionV1) GetDurationOk() (*float32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *TrialExtensionV1) SetDuration(v float32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *TrialExtensionV1) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### SetDurationNil

`func (o *TrialExtensionV1) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *TrialExtensionV1) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil
### GetReason

`func (o *TrialExtensionV1) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *TrialExtensionV1) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *TrialExtensionV1) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *TrialExtensionV1) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *TrialExtensionV1) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *TrialExtensionV1) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetDenied

`func (o *TrialExtensionV1) GetDenied() bool`

GetDenied returns the Denied field if non-nil, zero value otherwise.

### GetDeniedOk

`func (o *TrialExtensionV1) GetDeniedOk() (*bool, bool)`

GetDeniedOk returns a tuple with the Denied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenied

`func (o *TrialExtensionV1) SetDenied(v bool)`

SetDenied sets Denied field to given value.

### HasDenied

`func (o *TrialExtensionV1) HasDenied() bool`

HasDenied returns a boolean if a field has been set.

### SetDeniedNil

`func (o *TrialExtensionV1) SetDeniedNil(b bool)`

 SetDeniedNil sets the value for Denied to be an explicit nil

### UnsetDenied
`func (o *TrialExtensionV1) UnsetDenied()`

UnsetDenied ensures that no value is present for Denied, not even an explicit nil
### GetDeniedReason

`func (o *TrialExtensionV1) GetDeniedReason() string`

GetDeniedReason returns the DeniedReason field if non-nil, zero value otherwise.

### GetDeniedReasonOk

`func (o *TrialExtensionV1) GetDeniedReasonOk() (*string, bool)`

GetDeniedReasonOk returns a tuple with the DeniedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeniedReason

`func (o *TrialExtensionV1) SetDeniedReason(v string)`

SetDeniedReason sets DeniedReason field to given value.

### HasDeniedReason

`func (o *TrialExtensionV1) HasDeniedReason() bool`

HasDeniedReason returns a boolean if a field has been set.

### SetDeniedReasonNil

`func (o *TrialExtensionV1) SetDeniedReasonNil(b bool)`

 SetDeniedReasonNil sets the value for DeniedReason to be an explicit nil

### UnsetDeniedReason
`func (o *TrialExtensionV1) UnsetDeniedReason()`

UnsetDeniedReason ensures that no value is present for DeniedReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


