# DeviceUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HoursUsed** | **NullableFloat32** | Device hours used. | 
**HoursMax** | **NullableFloat32** | Device hours allowed. | 

## Methods

### NewDeviceUsage

`func NewDeviceUsage(hoursUsed NullableFloat32, hoursMax NullableFloat32, ) *DeviceUsage`

NewDeviceUsage instantiates a new DeviceUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeviceUsageWithDefaults

`func NewDeviceUsageWithDefaults() *DeviceUsage`

NewDeviceUsageWithDefaults instantiates a new DeviceUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHoursUsed

`func (o *DeviceUsage) GetHoursUsed() float32`

GetHoursUsed returns the HoursUsed field if non-nil, zero value otherwise.

### GetHoursUsedOk

`func (o *DeviceUsage) GetHoursUsedOk() (*float32, bool)`

GetHoursUsedOk returns a tuple with the HoursUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoursUsed

`func (o *DeviceUsage) SetHoursUsed(v float32)`

SetHoursUsed sets HoursUsed field to given value.


### SetHoursUsedNil

`func (o *DeviceUsage) SetHoursUsedNil(b bool)`

 SetHoursUsedNil sets the value for HoursUsed to be an explicit nil

### UnsetHoursUsed
`func (o *DeviceUsage) UnsetHoursUsed()`

UnsetHoursUsed ensures that no value is present for HoursUsed, not even an explicit nil
### GetHoursMax

`func (o *DeviceUsage) GetHoursMax() float32`

GetHoursMax returns the HoursMax field if non-nil, zero value otherwise.

### GetHoursMaxOk

`func (o *DeviceUsage) GetHoursMaxOk() (*float32, bool)`

GetHoursMaxOk returns a tuple with the HoursMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoursMax

`func (o *DeviceUsage) SetHoursMax(v float32)`

SetHoursMax sets HoursMax field to given value.


### SetHoursMaxNil

`func (o *DeviceUsage) SetHoursMaxNil(b bool)`

 SetHoursMaxNil sets the value for HoursMax to be an explicit nil

### UnsetHoursMax
`func (o *DeviceUsage) UnsetHoursMax()`

UnsetHoursMax ensures that no value is present for HoursMax, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


