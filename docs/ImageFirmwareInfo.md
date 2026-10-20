# ImageFirmwareInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Firmware type, e.g. &#39;ios&#39;. | [optional] 
**Version** | Pointer to **string** | OS version. | [optional] 
**BuildId** | Pointer to **string** | OS build ID. | [optional] 
**DeviceIds** | Pointer to **[]string** | Device identifiers this firmware supports. | [optional] 
**BoardConfig** | Pointer to **string** | Board configuration. | [optional] 
**Bdid** | Pointer to **float32** | Board ID. | [optional] 
**Cpid** | Pointer to **float32** | Chip ID. | [optional] 
**Platform** | Pointer to **string** | Chip platform. | [optional] 
**BootArgs** | Pointer to [**ImageFirmwareInfoBootArgs**](ImageFirmwareInfoBootArgs.md) |  | [optional] 
**Variants** | Pointer to **[]string** | Firmware variants. | [optional] 
**Device** | Pointer to [**FirmwareInfoDevice**](FirmwareInfoDevice.md) |  | [optional] 

## Methods

### NewImageFirmwareInfo

`func NewImageFirmwareInfo() *ImageFirmwareInfo`

NewImageFirmwareInfo instantiates a new ImageFirmwareInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageFirmwareInfoWithDefaults

`func NewImageFirmwareInfoWithDefaults() *ImageFirmwareInfo`

NewImageFirmwareInfoWithDefaults instantiates a new ImageFirmwareInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ImageFirmwareInfo) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ImageFirmwareInfo) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ImageFirmwareInfo) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ImageFirmwareInfo) HasType() bool`

HasType returns a boolean if a field has been set.

### GetVersion

`func (o *ImageFirmwareInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ImageFirmwareInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ImageFirmwareInfo) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ImageFirmwareInfo) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetBuildId

`func (o *ImageFirmwareInfo) GetBuildId() string`

GetBuildId returns the BuildId field if non-nil, zero value otherwise.

### GetBuildIdOk

`func (o *ImageFirmwareInfo) GetBuildIdOk() (*string, bool)`

GetBuildIdOk returns a tuple with the BuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildId

`func (o *ImageFirmwareInfo) SetBuildId(v string)`

SetBuildId sets BuildId field to given value.

### HasBuildId

`func (o *ImageFirmwareInfo) HasBuildId() bool`

HasBuildId returns a boolean if a field has been set.

### GetDeviceIds

`func (o *ImageFirmwareInfo) GetDeviceIds() []string`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *ImageFirmwareInfo) GetDeviceIdsOk() (*[]string, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *ImageFirmwareInfo) SetDeviceIds(v []string)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *ImageFirmwareInfo) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### GetBoardConfig

`func (o *ImageFirmwareInfo) GetBoardConfig() string`

GetBoardConfig returns the BoardConfig field if non-nil, zero value otherwise.

### GetBoardConfigOk

`func (o *ImageFirmwareInfo) GetBoardConfigOk() (*string, bool)`

GetBoardConfigOk returns a tuple with the BoardConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardConfig

`func (o *ImageFirmwareInfo) SetBoardConfig(v string)`

SetBoardConfig sets BoardConfig field to given value.

### HasBoardConfig

`func (o *ImageFirmwareInfo) HasBoardConfig() bool`

HasBoardConfig returns a boolean if a field has been set.

### GetBdid

`func (o *ImageFirmwareInfo) GetBdid() float32`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *ImageFirmwareInfo) GetBdidOk() (*float32, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *ImageFirmwareInfo) SetBdid(v float32)`

SetBdid sets Bdid field to given value.

### HasBdid

`func (o *ImageFirmwareInfo) HasBdid() bool`

HasBdid returns a boolean if a field has been set.

### GetCpid

`func (o *ImageFirmwareInfo) GetCpid() float32`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *ImageFirmwareInfo) GetCpidOk() (*float32, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *ImageFirmwareInfo) SetCpid(v float32)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *ImageFirmwareInfo) HasCpid() bool`

HasCpid returns a boolean if a field has been set.

### GetPlatform

`func (o *ImageFirmwareInfo) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *ImageFirmwareInfo) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *ImageFirmwareInfo) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *ImageFirmwareInfo) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetBootArgs

`func (o *ImageFirmwareInfo) GetBootArgs() ImageFirmwareInfoBootArgs`

GetBootArgs returns the BootArgs field if non-nil, zero value otherwise.

### GetBootArgsOk

`func (o *ImageFirmwareInfo) GetBootArgsOk() (*ImageFirmwareInfoBootArgs, bool)`

GetBootArgsOk returns a tuple with the BootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootArgs

`func (o *ImageFirmwareInfo) SetBootArgs(v ImageFirmwareInfoBootArgs)`

SetBootArgs sets BootArgs field to given value.

### HasBootArgs

`func (o *ImageFirmwareInfo) HasBootArgs() bool`

HasBootArgs returns a boolean if a field has been set.

### GetVariants

`func (o *ImageFirmwareInfo) GetVariants() []string`

GetVariants returns the Variants field if non-nil, zero value otherwise.

### GetVariantsOk

`func (o *ImageFirmwareInfo) GetVariantsOk() (*[]string, bool)`

GetVariantsOk returns a tuple with the Variants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariants

`func (o *ImageFirmwareInfo) SetVariants(v []string)`

SetVariants sets Variants field to given value.

### HasVariants

`func (o *ImageFirmwareInfo) HasVariants() bool`

HasVariants returns a boolean if a field has been set.

### GetDevice

`func (o *ImageFirmwareInfo) GetDevice() FirmwareInfoDevice`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ImageFirmwareInfo) GetDeviceOk() (*FirmwareInfoDevice, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ImageFirmwareInfo) SetDevice(v FirmwareInfoDevice)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ImageFirmwareInfo) HasDevice() bool`

HasDevice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


