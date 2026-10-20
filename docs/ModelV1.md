# ModelV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Name** | **string** |  | 
**Flavor** | **string** |  | 
**Description** | Pointer to **NullableString** |  | [optional] 
**Model** | **string** |  | 
**BoardConfig** | Pointer to **NullableString** |  | [optional] 
**Platform** | Pointer to **NullableString** |  | [optional] 
**Cpid** | Pointer to **NullableFloat32** |  | [optional] 
**Bdid** | Pointer to **NullableFloat32** |  | [optional] 
**Peripherals** | Pointer to **NullableBool** |  | [optional] 

## Methods

### NewModelV1

`func NewModelV1(type_ string, name string, flavor string, model string, ) *ModelV1`

NewModelV1 instantiates a new ModelV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelV1WithDefaults

`func NewModelV1WithDefaults() *ModelV1`

NewModelV1WithDefaults instantiates a new ModelV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ModelV1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ModelV1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ModelV1) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *ModelV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ModelV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ModelV1) SetName(v string)`

SetName sets Name field to given value.


### GetFlavor

`func (o *ModelV1) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *ModelV1) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *ModelV1) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.


### GetDescription

`func (o *ModelV1) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ModelV1) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ModelV1) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ModelV1) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ModelV1) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ModelV1) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetModel

`func (o *ModelV1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ModelV1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ModelV1) SetModel(v string)`

SetModel sets Model field to given value.


### GetBoardConfig

`func (o *ModelV1) GetBoardConfig() string`

GetBoardConfig returns the BoardConfig field if non-nil, zero value otherwise.

### GetBoardConfigOk

`func (o *ModelV1) GetBoardConfigOk() (*string, bool)`

GetBoardConfigOk returns a tuple with the BoardConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoardConfig

`func (o *ModelV1) SetBoardConfig(v string)`

SetBoardConfig sets BoardConfig field to given value.

### HasBoardConfig

`func (o *ModelV1) HasBoardConfig() bool`

HasBoardConfig returns a boolean if a field has been set.

### SetBoardConfigNil

`func (o *ModelV1) SetBoardConfigNil(b bool)`

 SetBoardConfigNil sets the value for BoardConfig to be an explicit nil

### UnsetBoardConfig
`func (o *ModelV1) UnsetBoardConfig()`

UnsetBoardConfig ensures that no value is present for BoardConfig, not even an explicit nil
### GetPlatform

`func (o *ModelV1) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *ModelV1) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *ModelV1) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *ModelV1) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### SetPlatformNil

`func (o *ModelV1) SetPlatformNil(b bool)`

 SetPlatformNil sets the value for Platform to be an explicit nil

### UnsetPlatform
`func (o *ModelV1) UnsetPlatform()`

UnsetPlatform ensures that no value is present for Platform, not even an explicit nil
### GetCpid

`func (o *ModelV1) GetCpid() float32`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *ModelV1) GetCpidOk() (*float32, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *ModelV1) SetCpid(v float32)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *ModelV1) HasCpid() bool`

HasCpid returns a boolean if a field has been set.

### SetCpidNil

`func (o *ModelV1) SetCpidNil(b bool)`

 SetCpidNil sets the value for Cpid to be an explicit nil

### UnsetCpid
`func (o *ModelV1) UnsetCpid()`

UnsetCpid ensures that no value is present for Cpid, not even an explicit nil
### GetBdid

`func (o *ModelV1) GetBdid() float32`

GetBdid returns the Bdid field if non-nil, zero value otherwise.

### GetBdidOk

`func (o *ModelV1) GetBdidOk() (*float32, bool)`

GetBdidOk returns a tuple with the Bdid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBdid

`func (o *ModelV1) SetBdid(v float32)`

SetBdid sets Bdid field to given value.

### HasBdid

`func (o *ModelV1) HasBdid() bool`

HasBdid returns a boolean if a field has been set.

### SetBdidNil

`func (o *ModelV1) SetBdidNil(b bool)`

 SetBdidNil sets the value for Bdid to be an explicit nil

### UnsetBdid
`func (o *ModelV1) UnsetBdid()`

UnsetBdid ensures that no value is present for Bdid, not even an explicit nil
### GetPeripherals

`func (o *ModelV1) GetPeripherals() bool`

GetPeripherals returns the Peripherals field if non-nil, zero value otherwise.

### GetPeripheralsOk

`func (o *ModelV1) GetPeripheralsOk() (*bool, bool)`

GetPeripheralsOk returns a tuple with the Peripherals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeripherals

`func (o *ModelV1) SetPeripherals(v bool)`

SetPeripherals sets Peripherals field to given value.

### HasPeripherals

`func (o *ModelV1) HasPeripherals() bool`

HasPeripherals returns a boolean if a field has been set.

### SetPeripheralsNil

`func (o *ModelV1) SetPeripheralsNil(b bool)`

 SetPeripheralsNil sets the value for Peripherals to be an explicit nil

### UnsetPeripherals
`func (o *ModelV1) UnsetPeripherals()`

UnsetPeripherals ensures that no value is present for Peripherals, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


