# ImageExtended

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **NullableString** | OS type | [optional] 
**Version** | Pointer to **NullableString** | OS version | [optional] 
**Buildid** | Pointer to **NullableString** | Build ID | [optional] 
**DeviceIds** | Pointer to **[]string** | List of device identifiers | [optional] 
**BoardConfig** | Pointer to **NullableString** | Board configuration identifier | [optional] 
**Device** | Pointer to [**ImageExtendedDevice**](ImageExtendedDevice.md) |  | [optional] 

## Methods

### NewImageExtended

`func NewImageExtended() *ImageExtended`

NewImageExtended instantiates a new ImageExtended object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageExtendedWithDefaults

`func NewImageExtendedWithDefaults() *ImageExtended`

NewImageExtendedWithDefaults instantiates a new ImageExtended object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ImageExtended) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ImageExtended) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ImageExtended) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ImageExtended) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *ImageExtended) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *ImageExtended) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetVersion

`func (o *ImageExtended) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ImageExtended) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ImageExtended) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ImageExtended) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *ImageExtended) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *ImageExtended) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetBuildid

`func (o *ImageExtended) GetBuildid() string`

GetBuildid returns the Buildid field if non-nil, zero value otherwise.

### GetBuildidOk

`func (o *ImageExtended) GetBuildidOk() (*string, bool)`

GetBuildidOk returns a tuple with the Buildid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildid

`func (o *ImageExtended) SetBuildid(v string)`

SetBuildid sets Buildid field to given value.

### HasBuildid

`func (o *ImageExtended) HasBuildid() bool`

HasBuildid returns a boolean if a field has been set.

### SetBuildidNil

`func (o *ImageExtended) SetBuildidNil(b bool)`

 SetBuildidNil sets the value for Buildid to be an explicit nil

### UnsetBuildid
`func (o *ImageExtended) UnsetBuildid()`

UnsetBuildid ensures that no value is present for Buildid, not even an explicit nil
### GetDeviceIds

`func (o *ImageExtended) GetDeviceIds() []string`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *ImageExtended) GetDeviceIdsOk() (*[]string, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *ImageExtended) SetDeviceIds(v []string)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *ImageExtended) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.

### SetDeviceIdsNil

`func (o *ImageExtended) SetDeviceIdsNil(b bool)`

 SetDeviceIdsNil sets the value for DeviceIds to be an explicit nil

### UnsetDeviceIds
`func (o *ImageExtended) UnsetDeviceIds()`

UnsetDeviceIds ensures that no value is present for DeviceIds, not even an explicit nil
### GetBoardConfig

`func (o *ImageExtended) GetBoardConfig() string`

GetBoardConfig returns the BoardConfig field if non-nil, zero value otherwise.

### GetBoardConfigOk

`func (o *ImageExtended) GetBoardConfigOk() (*string, bool)`

GetBoardConfigOk returns a tuple with the BoardConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardConfig

`func (o *ImageExtended) SetBoardConfig(v string)`

SetBoardConfig sets BoardConfig field to given value.

### HasBoardConfig

`func (o *ImageExtended) HasBoardConfig() bool`

HasBoardConfig returns a boolean if a field has been set.

### SetBoardConfigNil

`func (o *ImageExtended) SetBoardConfigNil(b bool)`

 SetBoardConfigNil sets the value for BoardConfig to be an explicit nil

### UnsetBoardConfig
`func (o *ImageExtended) UnsetBoardConfig()`

UnsetBoardConfig ensures that no value is present for BoardConfig, not even an explicit nil
### GetDevice

`func (o *ImageExtended) GetDevice() ImageExtendedDevice`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ImageExtended) GetDeviceOk() (*ImageExtendedDevice, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ImageExtended) SetDevice(v ImageExtendedDevice)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ImageExtended) HasDevice() bool`

HasDevice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


