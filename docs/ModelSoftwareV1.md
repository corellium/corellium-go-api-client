# ModelSoftwareV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**BoardConfig** | Pointer to **NullableString** |  | [optional] 
**Platform** | Pointer to **NullableString** |  | [optional] 
**Cpid** | Pointer to **NullableFloat32** |  | [optional] 
**Bdid** | Pointer to **NullableFloat32** |  | [optional] 
**Firmwares** | Pointer to [**[]FirmwareV1**](FirmwareV1.md) |  | [optional] 

## Methods

### NewModelSoftwareV1

`func NewModelSoftwareV1() *ModelSoftwareV1`

NewModelSoftwareV1 instantiates a new ModelSoftwareV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelSoftwareV1WithDefaults

`func NewModelSoftwareV1WithDefaults() *ModelSoftwareV1`

NewModelSoftwareV1WithDefaults instantiates a new ModelSoftwareV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ModelSoftwareV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ModelSoftwareV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ModelSoftwareV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ModelSoftwareV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ModelSoftwareV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ModelSoftwareV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetBoardConfig

`func (o *ModelSoftwareV1) GetBoardConfig() string`

GetBoardConfig returns the BoardConfig field if non-nil, zero value otherwise.

### GetBoardConfigOk

`func (o *ModelSoftwareV1) GetBoardConfigOk() (*string, bool)`

GetBoardConfigOk returns a tuple with the BoardConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardConfig

`func (o *ModelSoftwareV1) SetBoardConfig(v string)`

SetBoardConfig sets BoardConfig field to given value.

### HasBoardConfig

`func (o *ModelSoftwareV1) HasBoardConfig() bool`

HasBoardConfig returns a boolean if a field has been set.

### SetBoardConfigNil

`func (o *ModelSoftwareV1) SetBoardConfigNil(b bool)`

 SetBoardConfigNil sets the value for BoardConfig to be an explicit nil

### UnsetBoardConfig
`func (o *ModelSoftwareV1) UnsetBoardConfig()`

UnsetBoardConfig ensures that no value is present for BoardConfig, not even an explicit nil
### GetPlatform

`func (o *ModelSoftwareV1) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *ModelSoftwareV1) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *ModelSoftwareV1) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *ModelSoftwareV1) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### SetPlatformNil

`func (o *ModelSoftwareV1) SetPlatformNil(b bool)`

 SetPlatformNil sets the value for Platform to be an explicit nil

### UnsetPlatform
`func (o *ModelSoftwareV1) UnsetPlatform()`

UnsetPlatform ensures that no value is present for Platform, not even an explicit nil
### GetCpid

`func (o *ModelSoftwareV1) GetCpid() float32`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *ModelSoftwareV1) GetCpidOk() (*float32, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *ModelSoftwareV1) SetCpid(v float32)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *ModelSoftwareV1) HasCpid() bool`

HasCpid returns a boolean if a field has been set.

### SetCpidNil

`func (o *ModelSoftwareV1) SetCpidNil(b bool)`

 SetCpidNil sets the value for Cpid to be an explicit nil

### UnsetCpid
`func (o *ModelSoftwareV1) UnsetCpid()`

UnsetCpid ensures that no value is present for Cpid, not even an explicit nil
### GetBdid

`func (o *ModelSoftwareV1) GetBdid() float32`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *ModelSoftwareV1) GetBdidOk() (*float32, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *ModelSoftwareV1) SetBdid(v float32)`

SetBdid sets Bdid field to given value.

### HasBdid

`func (o *ModelSoftwareV1) HasBdid() bool`

HasBdid returns a boolean if a field has been set.

### SetBdidNil

`func (o *ModelSoftwareV1) SetBdidNil(b bool)`

 SetBdidNil sets the value for Bdid to be an explicit nil

### UnsetBdid
`func (o *ModelSoftwareV1) UnsetBdid()`

UnsetBdid ensures that no value is present for Bdid, not even an explicit nil
### GetFirmwares

`func (o *ModelSoftwareV1) GetFirmwares() []FirmwareV1`

GetFirmwares returns the Firmwares field if non-nil, zero value otherwise.

### GetFirmwaresOk

`func (o *ModelSoftwareV1) GetFirmwaresOk() (*[]FirmwareV1, bool)`

GetFirmwaresOk returns a tuple with the Firmwares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwares

`func (o *ModelSoftwareV1) SetFirmwares(v []FirmwareV1)`

SetFirmwares sets Firmwares field to given value.

### HasFirmwares

`func (o *ModelSoftwareV1) HasFirmwares() bool`

HasFirmwares returns a boolean if a field has been set.

### SetFirmwaresNil

`func (o *ModelSoftwareV1) SetFirmwaresNil(b bool)`

 SetFirmwaresNil sets the value for Firmwares to be an explicit nil

### UnsetFirmwares
`func (o *ModelSoftwareV1) UnsetFirmwares()`

UnsetFirmwares ensures that no value is present for Firmwares, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


