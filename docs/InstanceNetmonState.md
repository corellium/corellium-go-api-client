# InstanceNetmonState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hash** | Pointer to **string** | Hash for network monitor authentication. | [optional] 
**Info** | Pointer to **string** | Encrypted info for network monitor authentication. | [optional] 
**Enabled** | Pointer to **bool** | Whether network monitoring is enabled. | [optional] 

## Methods

### NewInstanceNetmonState

`func NewInstanceNetmonState() *InstanceNetmonState`

NewInstanceNetmonState instantiates a new InstanceNetmonState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceNetmonStateWithDefaults

`func NewInstanceNetmonStateWithDefaults() *InstanceNetmonState`

NewInstanceNetmonStateWithDefaults instantiates a new InstanceNetmonState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHash

`func (o *InstanceNetmonState) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *InstanceNetmonState) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *InstanceNetmonState) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *InstanceNetmonState) HasHash() bool`

HasHash returns a boolean if a field has been set.

### GetInfo

`func (o *InstanceNetmonState) GetInfo() string`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *InstanceNetmonState) GetInfoOk() (*string, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *InstanceNetmonState) SetInfo(v string)`

SetInfo sets Info field to given value.

### HasInfo

`func (o *InstanceNetmonState) HasInfo() bool`

HasInfo returns a boolean if a field has been set.

### GetEnabled

`func (o *InstanceNetmonState) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *InstanceNetmonState) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *InstanceNetmonState) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *InstanceNetmonState) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


