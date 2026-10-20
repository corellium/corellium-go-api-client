# DeviceAutoShutdownSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** | Whether devices in this domain are turned off automatically after running for &#x60;threshold&#x60; hours. Turning a device back on restarts its timer. | [optional] 
**Threshold** | Pointer to **float32** | Hours a device may run, counted from when it was last started, before it is turned off automatically. This is running time, not idle time: a device in active use is still stopped when the time is up. Whole number greater than 0. Defaults to 10 when not set. | [optional] 

## Methods

### NewDeviceAutoShutdownSchema

`func NewDeviceAutoShutdownSchema() *DeviceAutoShutdownSchema`

NewDeviceAutoShutdownSchema instantiates a new DeviceAutoShutdownSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceAutoShutdownSchemaWithDefaults

`func NewDeviceAutoShutdownSchemaWithDefaults() *DeviceAutoShutdownSchema`

NewDeviceAutoShutdownSchemaWithDefaults instantiates a new DeviceAutoShutdownSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *DeviceAutoShutdownSchema) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DeviceAutoShutdownSchema) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DeviceAutoShutdownSchema) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *DeviceAutoShutdownSchema) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetThreshold

`func (o *DeviceAutoShutdownSchema) GetThreshold() float32`

GetThreshold returns the Threshold field if non-nil, zero value otherwise.

### GetThresholdOk

`func (o *DeviceAutoShutdownSchema) GetThresholdOk() (*float32, bool)`

GetThresholdOk returns a tuple with the Threshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreshold

`func (o *DeviceAutoShutdownSchema) SetThreshold(v float32)`

SetThreshold sets Threshold field to given value.

### HasThreshold

`func (o *DeviceAutoShutdownSchema) HasThreshold() bool`

HasThreshold returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


