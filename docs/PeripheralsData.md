# PeripheralsData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Acceleration** | Pointer to **[]float32** | Accelerometer reading as [x, y, z]. | [optional] 
**Gyroscope** | Pointer to **[]float32** | Gyroscope reading as [x, y, z]. | [optional] 
**Magnetic** | Pointer to **[]float32** | Magnetometer reading as [x, y, z]. | [optional] 
**Orientation** | Pointer to **[]float32** | Device orientation vector. | [optional] 
**Temperature** | Pointer to **float32** | Ambient temperature reading. | [optional] 
**Proximity** | Pointer to **float32** | Proximity sensor reading. | [optional] 
**Light** | Pointer to **float32** | Ambient light sensor reading. | [optional] 
**Pressure** | Pointer to **float32** | Barometric pressure reading. | [optional] 
**Humidity** | Pointer to **float32** | Relative humidity reading. | [optional] 
**GpsLat** | Pointer to **float32** | GPS latitude in decimal degrees. | [optional] 
**GpsLon** | Pointer to **float32** | GPS longitude in decimal degrees. | [optional] 
**GpsAlt** | Pointer to **float32** | GPS altitude in meters. | [optional] 
**GpsToffs** | Pointer to **float32** | GPS time offset in seconds. | [optional] 
**AcOnline** | Pointer to **float32** | AC power connection: 0 &#x3D; disconnected, 1 &#x3D; connected. | [optional] 
**BatteryPresent** | Pointer to **float32** | Battery presence: 0 &#x3D; absent, 1 &#x3D; present. | [optional] 
**BatteryStatus** | Pointer to **string** | Battery charging status. | [optional] 
**BatteryHealth** | Pointer to **string** | Battery health. | [optional] 
**BatteryCapacity** | Pointer to **float32** | Battery charge level as a percentage. | [optional] 
**BiometricPass** | Pointer to **float32** | Biometric bypass: 0 &#x3D; disabled, 1 &#x3D; enabled. | [optional] 

## Methods

### NewPeripheralsData

`func NewPeripheralsData() *PeripheralsData`

NewPeripheralsData instantiates a new PeripheralsData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeripheralsDataWithDefaults

`func NewPeripheralsDataWithDefaults() *PeripheralsData`

NewPeripheralsDataWithDefaults instantiates a new PeripheralsData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceleration

`func (o *PeripheralsData) GetAcceleration() []float32`

GetAcceleration returns the Acceleration field if non-nil, zero value otherwise.

### GetAccelerationOk

`func (o *PeripheralsData) GetAccelerationOk() (*[]float32, bool)`

GetAccelerationOk returns a tuple with the Acceleration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceleration

`func (o *PeripheralsData) SetAcceleration(v []float32)`

SetAcceleration sets Acceleration field to given value.

### HasAcceleration

`func (o *PeripheralsData) HasAcceleration() bool`

HasAcceleration returns a boolean if a field has been set.

### GetGyroscope

`func (o *PeripheralsData) GetGyroscope() []float32`

GetGyroscope returns the Gyroscope field if non-nil, zero value otherwise.

### GetGyroscopeOk

`func (o *PeripheralsData) GetGyroscopeOk() (*[]float32, bool)`

GetGyroscopeOk returns a tuple with the Gyroscope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGyroscope

`func (o *PeripheralsData) SetGyroscope(v []float32)`

SetGyroscope sets Gyroscope field to given value.

### HasGyroscope

`func (o *PeripheralsData) HasGyroscope() bool`

HasGyroscope returns a boolean if a field has been set.

### GetMagnetic

`func (o *PeripheralsData) GetMagnetic() []float32`

GetMagnetic returns the Magnetic field if non-nil, zero value otherwise.

### GetMagneticOk

`func (o *PeripheralsData) GetMagneticOk() (*[]float32, bool)`

GetMagneticOk returns a tuple with the Magnetic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMagnetic

`func (o *PeripheralsData) SetMagnetic(v []float32)`

SetMagnetic sets Magnetic field to given value.

### HasMagnetic

`func (o *PeripheralsData) HasMagnetic() bool`

HasMagnetic returns a boolean if a field has been set.

### GetOrientation

`func (o *PeripheralsData) GetOrientation() []float32`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *PeripheralsData) GetOrientationOk() (*[]float32, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *PeripheralsData) SetOrientation(v []float32)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *PeripheralsData) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### GetTemperature

`func (o *PeripheralsData) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *PeripheralsData) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *PeripheralsData) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *PeripheralsData) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetProximity

`func (o *PeripheralsData) GetProximity() float32`

GetProximity returns the Proximity field if non-nil, zero value otherwise.

### GetProximityOk

`func (o *PeripheralsData) GetProximityOk() (*float32, bool)`

GetProximityOk returns a tuple with the Proximity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProximity

`func (o *PeripheralsData) SetProximity(v float32)`

SetProximity sets Proximity field to given value.

### HasProximity

`func (o *PeripheralsData) HasProximity() bool`

HasProximity returns a boolean if a field has been set.

### GetLight

`func (o *PeripheralsData) GetLight() float32`

GetLight returns the Light field if non-nil, zero value otherwise.

### GetLightOk

`func (o *PeripheralsData) GetLightOk() (*float32, bool)`

GetLightOk returns a tuple with the Light field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLight

`func (o *PeripheralsData) SetLight(v float32)`

SetLight sets Light field to given value.

### HasLight

`func (o *PeripheralsData) HasLight() bool`

HasLight returns a boolean if a field has been set.

### GetPressure

`func (o *PeripheralsData) GetPressure() float32`

GetPressure returns the Pressure field if non-nil, zero value otherwise.

### GetPressureOk

`func (o *PeripheralsData) GetPressureOk() (*float32, bool)`

GetPressureOk returns a tuple with the Pressure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPressure

`func (o *PeripheralsData) SetPressure(v float32)`

SetPressure sets Pressure field to given value.

### HasPressure

`func (o *PeripheralsData) HasPressure() bool`

HasPressure returns a boolean if a field has been set.

### GetHumidity

`func (o *PeripheralsData) GetHumidity() float32`

GetHumidity returns the Humidity field if non-nil, zero value otherwise.

### GetHumidityOk

`func (o *PeripheralsData) GetHumidityOk() (*float32, bool)`

GetHumidityOk returns a tuple with the Humidity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHumidity

`func (o *PeripheralsData) SetHumidity(v float32)`

SetHumidity sets Humidity field to given value.

### HasHumidity

`func (o *PeripheralsData) HasHumidity() bool`

HasHumidity returns a boolean if a field has been set.

### GetGpsLat

`func (o *PeripheralsData) GetGpsLat() float32`

GetGpsLat returns the GpsLat field if non-nil, zero value otherwise.

### GetGpsLatOk

`func (o *PeripheralsData) GetGpsLatOk() (*float32, bool)`

GetGpsLatOk returns a tuple with the GpsLat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsLat

`func (o *PeripheralsData) SetGpsLat(v float32)`

SetGpsLat sets GpsLat field to given value.

### HasGpsLat

`func (o *PeripheralsData) HasGpsLat() bool`

HasGpsLat returns a boolean if a field has been set.

### GetGpsLon

`func (o *PeripheralsData) GetGpsLon() float32`

GetGpsLon returns the GpsLon field if non-nil, zero value otherwise.

### GetGpsLonOk

`func (o *PeripheralsData) GetGpsLonOk() (*float32, bool)`

GetGpsLonOk returns a tuple with the GpsLon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsLon

`func (o *PeripheralsData) SetGpsLon(v float32)`

SetGpsLon sets GpsLon field to given value.

### HasGpsLon

`func (o *PeripheralsData) HasGpsLon() bool`

HasGpsLon returns a boolean if a field has been set.

### GetGpsAlt

`func (o *PeripheralsData) GetGpsAlt() float32`

GetGpsAlt returns the GpsAlt field if non-nil, zero value otherwise.

### GetGpsAltOk

`func (o *PeripheralsData) GetGpsAltOk() (*float32, bool)`

GetGpsAltOk returns a tuple with the GpsAlt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsAlt

`func (o *PeripheralsData) SetGpsAlt(v float32)`

SetGpsAlt sets GpsAlt field to given value.

### HasGpsAlt

`func (o *PeripheralsData) HasGpsAlt() bool`

HasGpsAlt returns a boolean if a field has been set.

### GetGpsToffs

`func (o *PeripheralsData) GetGpsToffs() float32`

GetGpsToffs returns the GpsToffs field if non-nil, zero value otherwise.

### GetGpsToffsOk

`func (o *PeripheralsData) GetGpsToffsOk() (*float32, bool)`

GetGpsToffsOk returns a tuple with the GpsToffs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpsToffs

`func (o *PeripheralsData) SetGpsToffs(v float32)`

SetGpsToffs sets GpsToffs field to given value.

### HasGpsToffs

`func (o *PeripheralsData) HasGpsToffs() bool`

HasGpsToffs returns a boolean if a field has been set.

### GetAcOnline

`func (o *PeripheralsData) GetAcOnline() float32`

GetAcOnline returns the AcOnline field if non-nil, zero value otherwise.

### GetAcOnlineOk

`func (o *PeripheralsData) GetAcOnlineOk() (*float32, bool)`

GetAcOnlineOk returns a tuple with the AcOnline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcOnline

`func (o *PeripheralsData) SetAcOnline(v float32)`

SetAcOnline sets AcOnline field to given value.

### HasAcOnline

`func (o *PeripheralsData) HasAcOnline() bool`

HasAcOnline returns a boolean if a field has been set.

### GetBatteryPresent

`func (o *PeripheralsData) GetBatteryPresent() float32`

GetBatteryPresent returns the BatteryPresent field if non-nil, zero value otherwise.

### GetBatteryPresentOk

`func (o *PeripheralsData) GetBatteryPresentOk() (*float32, bool)`

GetBatteryPresentOk returns a tuple with the BatteryPresent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryPresent

`func (o *PeripheralsData) SetBatteryPresent(v float32)`

SetBatteryPresent sets BatteryPresent field to given value.

### HasBatteryPresent

`func (o *PeripheralsData) HasBatteryPresent() bool`

HasBatteryPresent returns a boolean if a field has been set.

### GetBatteryStatus

`func (o *PeripheralsData) GetBatteryStatus() string`

GetBatteryStatus returns the BatteryStatus field if non-nil, zero value otherwise.

### GetBatteryStatusOk

`func (o *PeripheralsData) GetBatteryStatusOk() (*string, bool)`

GetBatteryStatusOk returns a tuple with the BatteryStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryStatus

`func (o *PeripheralsData) SetBatteryStatus(v string)`

SetBatteryStatus sets BatteryStatus field to given value.

### HasBatteryStatus

`func (o *PeripheralsData) HasBatteryStatus() bool`

HasBatteryStatus returns a boolean if a field has been set.

### GetBatteryHealth

`func (o *PeripheralsData) GetBatteryHealth() string`

GetBatteryHealth returns the BatteryHealth field if non-nil, zero value otherwise.

### GetBatteryHealthOk

`func (o *PeripheralsData) GetBatteryHealthOk() (*string, bool)`

GetBatteryHealthOk returns a tuple with the BatteryHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryHealth

`func (o *PeripheralsData) SetBatteryHealth(v string)`

SetBatteryHealth sets BatteryHealth field to given value.

### HasBatteryHealth

`func (o *PeripheralsData) HasBatteryHealth() bool`

HasBatteryHealth returns a boolean if a field has been set.

### GetBatteryCapacity

`func (o *PeripheralsData) GetBatteryCapacity() float32`

GetBatteryCapacity returns the BatteryCapacity field if non-nil, zero value otherwise.

### GetBatteryCapacityOk

`func (o *PeripheralsData) GetBatteryCapacityOk() (*float32, bool)`

GetBatteryCapacityOk returns a tuple with the BatteryCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryCapacity

`func (o *PeripheralsData) SetBatteryCapacity(v float32)`

SetBatteryCapacity sets BatteryCapacity field to given value.

### HasBatteryCapacity

`func (o *PeripheralsData) HasBatteryCapacity() bool`

HasBatteryCapacity returns a boolean if a field has been set.

### GetBiometricPass

`func (o *PeripheralsData) GetBiometricPass() float32`

GetBiometricPass returns the BiometricPass field if non-nil, zero value otherwise.

### GetBiometricPassOk

`func (o *PeripheralsData) GetBiometricPassOk() (*float32, bool)`

GetBiometricPassOk returns a tuple with the BiometricPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBiometricPass

`func (o *PeripheralsData) SetBiometricPass(v float32)`

SetBiometricPass sets BiometricPass field to given value.

### HasBiometricPass

`func (o *PeripheralsData) HasBiometricPass() bool`

HasBiometricPass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


