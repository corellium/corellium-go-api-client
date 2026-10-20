# AllowedDevicesFilterSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceName** | **string** | Device flavor identifier. | 
**AllowedFirmwares** | [**[]AllowedFirmwareSchema**](AllowedFirmwareSchema.md) | Firmware versions permitted on this device. | 

## Methods

### NewAllowedDevicesFilterSchema

`func NewAllowedDevicesFilterSchema(deviceName string, allowedFirmwares []AllowedFirmwareSchema, ) *AllowedDevicesFilterSchema`

NewAllowedDevicesFilterSchema instantiates a new AllowedDevicesFilterSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAllowedDevicesFilterSchemaWithDefaults

`func NewAllowedDevicesFilterSchemaWithDefaults() *AllowedDevicesFilterSchema`

NewAllowedDevicesFilterSchemaWithDefaults instantiates a new AllowedDevicesFilterSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceName

`func (o *AllowedDevicesFilterSchema) GetDeviceName() string`

GetDeviceName returns the DeviceName field if non-nil, zero value otherwise.

### GetDeviceNameOk

`func (o *AllowedDevicesFilterSchema) GetDeviceNameOk() (*string, bool)`

GetDeviceNameOk returns a tuple with the DeviceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceName

`func (o *AllowedDevicesFilterSchema) SetDeviceName(v string)`

SetDeviceName sets DeviceName field to given value.


### GetAllowedFirmwares

`func (o *AllowedDevicesFilterSchema) GetAllowedFirmwares() []AllowedFirmwareSchema`

GetAllowedFirmwares returns the AllowedFirmwares field if non-nil, zero value otherwise.

### GetAllowedFirmwaresOk

`func (o *AllowedDevicesFilterSchema) GetAllowedFirmwaresOk() (*[]AllowedFirmwareSchema, bool)`

GetAllowedFirmwaresOk returns a tuple with the AllowedFirmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedFirmwares

`func (o *AllowedDevicesFilterSchema) SetAllowedFirmwares(v []AllowedFirmwareSchema)`

SetAllowedFirmwares sets AllowedFirmwares field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


