# LoginResultDomainDeviceAutoShutdown

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** | Whether idle devices are shut down. | [optional] 
**Threshold** | Pointer to **float32** | Hours an instance may run before it is shut down (defaults to 10). | [optional] 

## Methods

### NewLoginResultDomainDeviceAutoShutdown

`func NewLoginResultDomainDeviceAutoShutdown() *LoginResultDomainDeviceAutoShutdown`

NewLoginResultDomainDeviceAutoShutdown instantiates a new LoginResultDomainDeviceAutoShutdown object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultDomainDeviceAutoShutdownWithDefaults

`func NewLoginResultDomainDeviceAutoShutdownWithDefaults() *LoginResultDomainDeviceAutoShutdown`

NewLoginResultDomainDeviceAutoShutdownWithDefaults instantiates a new LoginResultDomainDeviceAutoShutdown object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *LoginResultDomainDeviceAutoShutdown) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *LoginResultDomainDeviceAutoShutdown) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *LoginResultDomainDeviceAutoShutdown) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *LoginResultDomainDeviceAutoShutdown) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetThreshold

`func (o *LoginResultDomainDeviceAutoShutdown) GetThreshold() float32`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *LoginResultDomainDeviceAutoShutdown) GetThresholdOk() (*float32, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *LoginResultDomainDeviceAutoShutdown) SetThreshold(v float32)`

SetThreshold sets Threshold field to given value.

### HasThreshold

`func (o *LoginResultDomainDeviceAutoShutdown) HasThreshold() bool`

HasThreshold returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


