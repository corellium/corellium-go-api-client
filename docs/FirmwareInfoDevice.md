# FirmwareInfoDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Flavor** | Pointer to **string** | Matched device flavor. | [optional] 
**Firmwares** | Pointer to [**[]FirmwareInfoDeviceFirmwaresInner**](FirmwareInfoDeviceFirmwaresInner.md) | Supported firmwares matching the version and build ID of this image. | [optional] 

## Methods

### NewFirmwareInfoDevice

`func NewFirmwareInfoDevice() *FirmwareInfoDevice`

NewFirmwareInfoDevice instantiates a new FirmwareInfoDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirmwareInfoDeviceWithDefaults

`func NewFirmwareInfoDeviceWithDefaults() *FirmwareInfoDevice`

NewFirmwareInfoDeviceWithDefaults instantiates a new FirmwareInfoDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFlavor

`func (o *FirmwareInfoDevice) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *FirmwareInfoDevice) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *FirmwareInfoDevice) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *FirmwareInfoDevice) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### GetFirmwares

`func (o *FirmwareInfoDevice) GetFirmwares() []FirmwareInfoDeviceFirmwaresInner`

GetFirmwares returns the Firmwares field if non-nil, zero value otherwise.

### GetFirmwaresOk

`func (o *FirmwareInfoDevice) GetFirmwaresOk() (*[]FirmwareInfoDeviceFirmwaresInner, bool)`

GetFirmwaresOk returns a tuple with the Firmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwares

`func (o *FirmwareInfoDevice) SetFirmwares(v []FirmwareInfoDeviceFirmwaresInner)`

SetFirmwares sets Firmwares field to given value.

### HasFirmwares

`func (o *FirmwareInfoDevice) HasFirmwares() bool`

HasFirmwares returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


