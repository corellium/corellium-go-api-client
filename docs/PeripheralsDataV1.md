# PeripheralsDataV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Acceleration** | Pointer to **[]float32** |  | [optional] 
**Gyroscope** | Pointer to **[]float32** |  | [optional] 
**Magnetic** | Pointer to **[]float32** |  | [optional] 
**Orientation** | Pointer to **[]float32** |  | [optional] 
**Temperature** | Pointer to **NullableFloat32** |  | [optional] 
**Proximity** | Pointer to **NullableFloat32** |  | [optional] 
**Light** | Pointer to **NullableFloat32** |  | [optional] 
**Pressure** | Pointer to **NullableFloat32** |  | [optional] 
**Humidity** | Pointer to **NullableFloat32** |  | [optional] 
**GpsLat** | Pointer to **NullableFloat32** |  | [optional] 
**GpsLon** | Pointer to **NullableFloat32** |  | [optional] 
**GpsAlt** | Pointer to **NullableFloat32** |  | [optional] 
**GpsToffs** | Pointer to **NullableFloat32** | GPS time offset in seconds. | [optional] 
**AcOnline** | Pointer to **NullableFloat32** | Whether the device is on AC power (0 or 1). | [optional] 
**BatteryPresent** | Pointer to **NullableFloat32** | Whether a battery is present (0 or 1). | [optional] 
**BatteryStatus** | Pointer to **NullableString** | Battery charging status | [optional] 
**BatteryHealth** | Pointer to **NullableString** | Battery health | [optional] 
**BatteryCapacity** | Pointer to **NullableFloat32** |  | [optional] 
**BiometricPass** | Pointer to **NullableFloat32** | Whether biometric authentication passes (0 or 1). | [optional] 

## Methods

### NewPeripheralsDataV1

`func NewPeripheralsDataV1() *PeripheralsDataV1`

NewPeripheralsDataV1 instantiates a new PeripheralsDataV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeripheralsDataV1WithDefaults

`func NewPeripheralsDataV1WithDefaults() *PeripheralsDataV1`

NewPeripheralsDataV1WithDefaults instantiates a new PeripheralsDataV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceleration

`func (o *PeripheralsDataV1) GetAcceleration() []float32`

GetAcceleration returns the Acceleration field if non-nil, zero value otherwise.

### GetAccelerationOk

`func (o *PeripheralsDataV1) GetAccelerationOk() (*[]float32, bool)`

GetAccelerationOk returns a tuple with the Acceleration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceleration

`func (o *PeripheralsDataV1) SetAcceleration(v []float32)`

SetAcceleration sets Acceleration field to given value.

### HasAcceleration

`func (o *PeripheralsDataV1) HasAcceleration() bool`

HasAcceleration returns a boolean if a field has been set.

### SetAccelerationNil

`func (o *PeripheralsDataV1) SetAccelerationNil(b bool)`

 SetAccelerationNil sets the value for Acceleration to be an explicit nil

### UnsetAcceleration
`func (o *PeripheralsDataV1) UnsetAcceleration()`

UnsetAcceleration ensures that no value is present for Acceleration, not even an explicit nil
### GetGyroscope

`func (o *PeripheralsDataV1) GetGyroscope() []float32`

GetGyroscope returns the Gyroscope field if non-nil, zero value otherwise.

### GetGyroscopeOk

`func (o *PeripheralsDataV1) GetGyroscopeOk() (*[]float32, bool)`

GetGyroscopeOk returns a tuple with the Gyroscope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGyroscope

`func (o *PeripheralsDataV1) SetGyroscope(v []float32)`

SetGyroscope sets Gyroscope field to given value.

### HasGyroscope

`func (o *PeripheralsDataV1) HasGyroscope() bool`

HasGyroscope returns a boolean if a field has been set.

### SetGyroscopeNil

`func (o *PeripheralsDataV1) SetGyroscopeNil(b bool)`

 SetGyroscopeNil sets the value for Gyroscope to be an explicit nil

### UnsetGyroscope
`func (o *PeripheralsDataV1) UnsetGyroscope()`

UnsetGyroscope ensures that no value is present for Gyroscope, not even an explicit nil
### GetMagnetic

`func (o *PeripheralsDataV1) GetMagnetic() []float32`

GetMagnetic returns the Magnetic field if non-nil, zero value otherwise.

### GetMagneticOk

`func (o *PeripheralsDataV1) GetMagneticOk() (*[]float32, bool)`

GetMagneticOk returns a tuple with the Magnetic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMagnetic

`func (o *PeripheralsDataV1) SetMagnetic(v []float32)`

SetMagnetic sets Magnetic field to given value.

### HasMagnetic

`func (o *PeripheralsDataV1) HasMagnetic() bool`

HasMagnetic returns a boolean if a field has been set.

### SetMagneticNil

`func (o *PeripheralsDataV1) SetMagneticNil(b bool)`

 SetMagneticNil sets the value for Magnetic to be an explicit nil

### UnsetMagnetic
`func (o *PeripheralsDataV1) UnsetMagnetic()`

UnsetMagnetic ensures that no value is present for Magnetic, not even an explicit nil
### GetOrientation

`func (o *PeripheralsDataV1) GetOrientation() []float32`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *PeripheralsDataV1) GetOrientationOk() (*[]float32, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *PeripheralsDataV1) SetOrientation(v []float32)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *PeripheralsDataV1) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### SetOrientationNil

`func (o *PeripheralsDataV1) SetOrientationNil(b bool)`

 SetOrientationNil sets the value for Orientation to be an explicit nil

### UnsetOrientation
`func (o *PeripheralsDataV1) UnsetOrientation()`

UnsetOrientation ensures that no value is present for Orientation, not even an explicit nil
### GetTemperature

`func (o *PeripheralsDataV1) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *PeripheralsDataV1) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *PeripheralsDataV1) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *PeripheralsDataV1) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### SetTemperatureNil

`func (o *PeripheralsDataV1) SetTemperatureNil(b bool)`

 SetTemperatureNil sets the value for Temperature to be an explicit nil

### UnsetTemperature
`func (o *PeripheralsDataV1) UnsetTemperature()`

UnsetTemperature ensures that no value is present for Temperature, not even an explicit nil
### GetProximity

`func (o *PeripheralsDataV1) GetProximity() float32`

GetProximity returns the Proximity field if non-nil, zero value otherwise.

### GetProximityOk

`func (o *PeripheralsDataV1) GetProximityOk() (*float32, bool)`

GetProximityOk returns a tuple with the Proximity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProximity

`func (o *PeripheralsDataV1) SetProximity(v float32)`

SetProximity sets Proximity field to given value.

### HasProximity

`func (o *PeripheralsDataV1) HasProximity() bool`

HasProximity returns a boolean if a field has been set.

### SetProximityNil

`func (o *PeripheralsDataV1) SetProximityNil(b bool)`

 SetProximityNil sets the value for Proximity to be an explicit nil

### UnsetProximity
`func (o *PeripheralsDataV1) UnsetProximity()`

UnsetProximity ensures that no value is present for Proximity, not even an explicit nil
### GetLight

`func (o *PeripheralsDataV1) GetLight() float32`

GetLight returns the Light field if non-nil, zero value otherwise.

### GetLightOk

`func (o *PeripheralsDataV1) GetLightOk() (*float32, bool)`

GetLightOk returns a tuple with the Light field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLight

`func (o *PeripheralsDataV1) SetLight(v float32)`

SetLight sets Light field to given value.

### HasLight

`func (o *PeripheralsDataV1) HasLight() bool`

HasLight returns a boolean if a field has been set.

### SetLightNil

`func (o *PeripheralsDataV1) SetLightNil(b bool)`

 SetLightNil sets the value for Light to be an explicit nil

### UnsetLight
`func (o *PeripheralsDataV1) UnsetLight()`

UnsetLight ensures that no value is present for Light, not even an explicit nil
### GetPressure

`func (o *PeripheralsDataV1) GetPressure() float32`

GetPressure returns the Pressure field if non-nil, zero value otherwise.

### GetPressureOk

`func (o *PeripheralsDataV1) GetPressureOk() (*float32, bool)`

GetPressureOk returns a tuple with the Pressure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPressure

`func (o *PeripheralsDataV1) SetPressure(v float32)`

SetPressure sets Pressure field to given value.

### HasPressure

`func (o *PeripheralsDataV1) HasPressure() bool`

HasPressure returns a boolean if a field has been set.

### SetPressureNil

`func (o *PeripheralsDataV1) SetPressureNil(b bool)`

 SetPressureNil sets the value for Pressure to be an explicit nil

### UnsetPressure
`func (o *PeripheralsDataV1) UnsetPressure()`

UnsetPressure ensures that no value is present for Pressure, not even an explicit nil
### GetHumidity

`func (o *PeripheralsDataV1) GetHumidity() float32`

GetHumidity returns the Humidity field if non-nil, zero value otherwise.

### GetHumidityOk

`func (o *PeripheralsDataV1) GetHumidityOk() (*float32, bool)`

GetHumidityOk returns a tuple with the Humidity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHumidity

`func (o *PeripheralsDataV1) SetHumidity(v float32)`

SetHumidity sets Humidity field to given value.

### HasHumidity

`func (o *PeripheralsDataV1) HasHumidity() bool`

HasHumidity returns a boolean if a field has been set.

### SetHumidityNil

`func (o *PeripheralsDataV1) SetHumidityNil(b bool)`

 SetHumidityNil sets the value for Humidity to be an explicit nil

### UnsetHumidity
`func (o *PeripheralsDataV1) UnsetHumidity()`

UnsetHumidity ensures that no value is present for Humidity, not even an explicit nil
### GetGpsLat

`func (o *PeripheralsDataV1) GetGpsLat() float32`

GetGpsLat returns the GpsLat field if non-nil, zero value otherwise.

### GetGpsLatOk

`func (o *PeripheralsDataV1) GetGpsLatOk() (*float32, bool)`

GetGpsLatOk returns a tuple with the GpsLat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsLat

`func (o *PeripheralsDataV1) SetGpsLat(v float32)`

SetGpsLat sets GpsLat field to given value.

### HasGpsLat

`func (o *PeripheralsDataV1) HasGpsLat() bool`

HasGpsLat returns a boolean if a field has been set.

### SetGpsLatNil

`func (o *PeripheralsDataV1) SetGpsLatNil(b bool)`

 SetGpsLatNil sets the value for GpsLat to be an explicit nil

### UnsetGpsLat
`func (o *PeripheralsDataV1) UnsetGpsLat()`

UnsetGpsLat ensures that no value is present for GpsLat, not even an explicit nil
### GetGpsLon

`func (o *PeripheralsDataV1) GetGpsLon() float32`

GetGpsLon returns the GpsLon field if non-nil, zero value otherwise.

### GetGpsLonOk

`func (o *PeripheralsDataV1) GetGpsLonOk() (*float32, bool)`

GetGpsLonOk returns a tuple with the GpsLon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsLon

`func (o *PeripheralsDataV1) SetGpsLon(v float32)`

SetGpsLon sets GpsLon field to given value.

### HasGpsLon

`func (o *PeripheralsDataV1) HasGpsLon() bool`

HasGpsLon returns a boolean if a field has been set.

### SetGpsLonNil

`func (o *PeripheralsDataV1) SetGpsLonNil(b bool)`

 SetGpsLonNil sets the value for GpsLon to be an explicit nil

### UnsetGpsLon
`func (o *PeripheralsDataV1) UnsetGpsLon()`

UnsetGpsLon ensures that no value is present for GpsLon, not even an explicit nil
### GetGpsAlt

`func (o *PeripheralsDataV1) GetGpsAlt() float32`

GetGpsAlt returns the GpsAlt field if non-nil, zero value otherwise.

### GetGpsAltOk

`func (o *PeripheralsDataV1) GetGpsAltOk() (*float32, bool)`

GetGpsAltOk returns a tuple with the GpsAlt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsAlt

`func (o *PeripheralsDataV1) SetGpsAlt(v float32)`

SetGpsAlt sets GpsAlt field to given value.

### HasGpsAlt

`func (o *PeripheralsDataV1) HasGpsAlt() bool`

HasGpsAlt returns a boolean if a field has been set.

### SetGpsAltNil

`func (o *PeripheralsDataV1) SetGpsAltNil(b bool)`

 SetGpsAltNil sets the value for GpsAlt to be an explicit nil

### UnsetGpsAlt
`func (o *PeripheralsDataV1) UnsetGpsAlt()`

UnsetGpsAlt ensures that no value is present for GpsAlt, not even an explicit nil
### GetGpsToffs

`func (o *PeripheralsDataV1) GetGpsToffs() float32`

GetGpsToffs returns the GpsToffs field if non-nil, zero value otherwise.

### GetGpsToffsOk

`func (o *PeripheralsDataV1) GetGpsToffsOk() (*float32, bool)`

GetGpsToffsOk returns a tuple with the GpsToffs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsToffs

`func (o *PeripheralsDataV1) SetGpsToffs(v float32)`

SetGpsToffs sets GpsToffs field to given value.

### HasGpsToffs

`func (o *PeripheralsDataV1) HasGpsToffs() bool`

HasGpsToffs returns a boolean if a field has been set.

### SetGpsToffsNil

`func (o *PeripheralsDataV1) SetGpsToffsNil(b bool)`

 SetGpsToffsNil sets the value for GpsToffs to be an explicit nil

### UnsetGpsToffs
`func (o *PeripheralsDataV1) UnsetGpsToffs()`

UnsetGpsToffs ensures that no value is present for GpsToffs, not even an explicit nil
### GetAcOnline

`func (o *PeripheralsDataV1) GetAcOnline() float32`

GetAcOnline returns the AcOnline field if non-nil, zero value otherwise.

### GetAcOnlineOk

`func (o *PeripheralsDataV1) GetAcOnlineOk() (*float32, bool)`

GetAcOnlineOk returns a tuple with the AcOnline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcOnline

`func (o *PeripheralsDataV1) SetAcOnline(v float32)`

SetAcOnline sets AcOnline field to given value.

### HasAcOnline

`func (o *PeripheralsDataV1) HasAcOnline() bool`

HasAcOnline returns a boolean if a field has been set.

### SetAcOnlineNil

`func (o *PeripheralsDataV1) SetAcOnlineNil(b bool)`

 SetAcOnlineNil sets the value for AcOnline to be an explicit nil

### UnsetAcOnline
`func (o *PeripheralsDataV1) UnsetAcOnline()`

UnsetAcOnline ensures that no value is present for AcOnline, not even an explicit nil
### GetBatteryPresent

`func (o *PeripheralsDataV1) GetBatteryPresent() float32`

GetBatteryPresent returns the BatteryPresent field if non-nil, zero value otherwise.

### GetBatteryPresentOk

`func (o *PeripheralsDataV1) GetBatteryPresentOk() (*float32, bool)`

GetBatteryPresentOk returns a tuple with the BatteryPresent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryPresent

`func (o *PeripheralsDataV1) SetBatteryPresent(v float32)`

SetBatteryPresent sets BatteryPresent field to given value.

### HasBatteryPresent

`func (o *PeripheralsDataV1) HasBatteryPresent() bool`

HasBatteryPresent returns a boolean if a field has been set.

### SetBatteryPresentNil

`func (o *PeripheralsDataV1) SetBatteryPresentNil(b bool)`

 SetBatteryPresentNil sets the value for BatteryPresent to be an explicit nil

### UnsetBatteryPresent
`func (o *PeripheralsDataV1) UnsetBatteryPresent()`

UnsetBatteryPresent ensures that no value is present for BatteryPresent, not even an explicit nil
### GetBatteryStatus

`func (o *PeripheralsDataV1) GetBatteryStatus() string`

GetBatteryStatus returns the BatteryStatus field if non-nil, zero value otherwise.

### GetBatteryStatusOk

`func (o *PeripheralsDataV1) GetBatteryStatusOk() (*string, bool)`

GetBatteryStatusOk returns a tuple with the BatteryStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryStatus

`func (o *PeripheralsDataV1) SetBatteryStatus(v string)`

SetBatteryStatus sets BatteryStatus field to given value.

### HasBatteryStatus

`func (o *PeripheralsDataV1) HasBatteryStatus() bool`

HasBatteryStatus returns a boolean if a field has been set.

### SetBatteryStatusNil

`func (o *PeripheralsDataV1) SetBatteryStatusNil(b bool)`

 SetBatteryStatusNil sets the value for BatteryStatus to be an explicit nil

### UnsetBatteryStatus
`func (o *PeripheralsDataV1) UnsetBatteryStatus()`

UnsetBatteryStatus ensures that no value is present for BatteryStatus, not even an explicit nil
### GetBatteryHealth

`func (o *PeripheralsDataV1) GetBatteryHealth() string`

GetBatteryHealth returns the BatteryHealth field if non-nil, zero value otherwise.

### GetBatteryHealthOk

`func (o *PeripheralsDataV1) GetBatteryHealthOk() (*string, bool)`

GetBatteryHealthOk returns a tuple with the BatteryHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryHealth

`func (o *PeripheralsDataV1) SetBatteryHealth(v string)`

SetBatteryHealth sets BatteryHealth field to given value.

### HasBatteryHealth

`func (o *PeripheralsDataV1) HasBatteryHealth() bool`

HasBatteryHealth returns a boolean if a field has been set.

### SetBatteryHealthNil

`func (o *PeripheralsDataV1) SetBatteryHealthNil(b bool)`

 SetBatteryHealthNil sets the value for BatteryHealth to be an explicit nil

### UnsetBatteryHealth
`func (o *PeripheralsDataV1) UnsetBatteryHealth()`

UnsetBatteryHealth ensures that no value is present for BatteryHealth, not even an explicit nil
### GetBatteryCapacity

`func (o *PeripheralsDataV1) GetBatteryCapacity() float32`

GetBatteryCapacity returns the BatteryCapacity field if non-nil, zero value otherwise.

### GetBatteryCapacityOk

`func (o *PeripheralsDataV1) GetBatteryCapacityOk() (*float32, bool)`

GetBatteryCapacityOk returns a tuple with the BatteryCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryCapacity

`func (o *PeripheralsDataV1) SetBatteryCapacity(v float32)`

SetBatteryCapacity sets BatteryCapacity field to given value.

### HasBatteryCapacity

`func (o *PeripheralsDataV1) HasBatteryCapacity() bool`

HasBatteryCapacity returns a boolean if a field has been set.

### SetBatteryCapacityNil

`func (o *PeripheralsDataV1) SetBatteryCapacityNil(b bool)`

 SetBatteryCapacityNil sets the value for BatteryCapacity to be an explicit nil

### UnsetBatteryCapacity
`func (o *PeripheralsDataV1) UnsetBatteryCapacity()`

UnsetBatteryCapacity ensures that no value is present for BatteryCapacity, not even an explicit nil
### GetBiometricPass

`func (o *PeripheralsDataV1) GetBiometricPass() float32`

GetBiometricPass returns the BiometricPass field if non-nil, zero value otherwise.

### GetBiometricPassOk

`func (o *PeripheralsDataV1) GetBiometricPassOk() (*float32, bool)`

GetBiometricPassOk returns a tuple with the BiometricPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBiometricPass

`func (o *PeripheralsDataV1) SetBiometricPass(v float32)`

SetBiometricPass sets BiometricPass field to given value.

### HasBiometricPass

`func (o *PeripheralsDataV1) HasBiometricPass() bool`

HasBiometricPass returns a boolean if a field has been set.

### SetBiometricPassNil

`func (o *PeripheralsDataV1) SetBiometricPassNil(b bool)`

 SetBiometricPassNil sets the value for BiometricPass to be an explicit nil

### UnsetBiometricPass
`func (o *PeripheralsDataV1) UnsetBiometricPass()`

UnsetBiometricPass ensures that no value is present for BiometricPass, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


