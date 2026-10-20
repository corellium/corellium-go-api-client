# ImageExtendedDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Flavor** | Pointer to **NullableString** | Device flavor/model name | [optional] 
**Firmwares** | Pointer to [**[]ImageFirmware**](ImageFirmware.md) | List of associated firmware entries | [optional] 

## Methods

### NewImageExtendedDevice

`func NewImageExtendedDevice() *ImageExtendedDevice`

NewImageExtendedDevice instantiates a new ImageExtendedDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageExtendedDeviceWithDefaults

`func NewImageExtendedDeviceWithDefaults() *ImageExtendedDevice`

NewImageExtendedDeviceWithDefaults instantiates a new ImageExtendedDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFlavor

`func (o *ImageExtendedDevice) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *ImageExtendedDevice) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *ImageExtendedDevice) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *ImageExtendedDevice) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### SetFlavorNil

`func (o *ImageExtendedDevice) SetFlavorNil(b bool)`

 SetFlavorNil sets the value for Flavor to be an explicit nil

### UnsetFlavor
`func (o *ImageExtendedDevice) UnsetFlavor()`

UnsetFlavor ensures that no value is present for Flavor, not even an explicit nil
### GetFirmwares

`func (o *ImageExtendedDevice) GetFirmwares() []ImageFirmware`

GetFirmwares returns the Firmwares field if non-nil, zero value otherwise.

### GetFirmwaresOk

`func (o *ImageExtendedDevice) GetFirmwaresOk() (*[]ImageFirmware, bool)`

GetFirmwaresOk returns a tuple with the Firmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwares

`func (o *ImageExtendedDevice) SetFirmwares(v []ImageFirmware)`

SetFirmwares sets Firmwares field to given value.

### HasFirmwares

`func (o *ImageExtendedDevice) HasFirmwares() bool`

HasFirmwares returns a boolean if a field has been set.

### SetFirmwaresNil

`func (o *ImageExtendedDevice) SetFirmwaresNil(b bool)`

 SetFirmwaresNil sets the value for Firmwares to be an explicit nil

### UnsetFirmwares
`func (o *ImageExtendedDevice) UnsetFirmwares()`

UnsetFirmwares ensures that no value is present for Firmwares, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


