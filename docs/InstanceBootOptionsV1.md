# InstanceBootOptionsV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BootArgs** | Pointer to **NullableString** |  | [optional] 
**RestoreBootArgs** | Pointer to **NullableString** |  | [optional] 
**Udid** | Pointer to **NullableString** | Boot udid | [optional] 
**Ecid** | Pointer to **NullableString** | Assigned ECID | [optional] 
**RandomSeed** | Pointer to **NullableString** | Random seed to provide to boot if any | [optional] 
**Pac** | Pointer to **NullableBool** | Enable PAC | [optional] 
**Aprr** | Pointer to **NullableBool** | Enable APRR | [optional] 
**AdditionalTags** | Pointer to [**[]InstanceBootOptionsAdditionalTag**](InstanceBootOptionsAdditionalTag.md) |  | [optional] 
**Kernel** | Pointer to [**InstanceBootOptionsKernelV1**](InstanceBootOptionsKernelV1.md) |  | [optional] 
**Pongo** | Pointer to [**InstanceBootOptionsPongoV1**](InstanceBootOptionsPongoV1.md) |  | [optional] 

## Methods

### NewInstanceBootOptionsV1

`func NewInstanceBootOptionsV1() *InstanceBootOptionsV1`

NewInstanceBootOptionsV1 instantiates a new InstanceBootOptionsV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceBootOptionsV1WithDefaults

`func NewInstanceBootOptionsV1WithDefaults() *InstanceBootOptionsV1`

NewInstanceBootOptionsV1WithDefaults instantiates a new InstanceBootOptionsV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBootArgs

`func (o *InstanceBootOptionsV1) GetBootArgs() string`

GetBootArgs returns the BootArgs field if non-nil, zero value otherwise.

### GetBootArgsOk

`func (o *InstanceBootOptionsV1) GetBootArgsOk() (*string, bool)`

GetBootArgsOk returns a tuple with the BootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootArgs

`func (o *InstanceBootOptionsV1) SetBootArgs(v string)`

SetBootArgs sets BootArgs field to given value.

### HasBootArgs

`func (o *InstanceBootOptionsV1) HasBootArgs() bool`

HasBootArgs returns a boolean if a field has been set.

### SetBootArgsNil

`func (o *InstanceBootOptionsV1) SetBootArgsNil(b bool)`

 SetBootArgsNil sets the value for BootArgs to be an explicit nil

### UnsetBootArgs
`func (o *InstanceBootOptionsV1) UnsetBootArgs()`

UnsetBootArgs ensures that no value is present for BootArgs, not even an explicit nil
### GetRestoreBootArgs

`func (o *InstanceBootOptionsV1) GetRestoreBootArgs() string`

GetRestoreBootArgs returns the RestoreBootArgs field if non-nil, zero value otherwise.

### GetRestoreBootArgsOk

`func (o *InstanceBootOptionsV1) GetRestoreBootArgsOk() (*string, bool)`

GetRestoreBootArgsOk returns a tuple with the RestoreBootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestoreBootArgs

`func (o *InstanceBootOptionsV1) SetRestoreBootArgs(v string)`

SetRestoreBootArgs sets RestoreBootArgs field to given value.

### HasRestoreBootArgs

`func (o *InstanceBootOptionsV1) HasRestoreBootArgs() bool`

HasRestoreBootArgs returns a boolean if a field has been set.

### SetRestoreBootArgsNil

`func (o *InstanceBootOptionsV1) SetRestoreBootArgsNil(b bool)`

 SetRestoreBootArgsNil sets the value for RestoreBootArgs to be an explicit nil

### UnsetRestoreBootArgs
`func (o *InstanceBootOptionsV1) UnsetRestoreBootArgs()`

UnsetRestoreBootArgs ensures that no value is present for RestoreBootArgs, not even an explicit nil
### GetUdid

`func (o *InstanceBootOptionsV1) GetUdid() string`

GetUdid returns the Udid field if non-nil, zero value otherwise.

### GetUdidOk

`func (o *InstanceBootOptionsV1) GetUdidOk() (*string, bool)`

GetUdidOk returns a tuple with the Udid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUdid

`func (o *InstanceBootOptionsV1) SetUdid(v string)`

SetUdid sets Udid field to given value.

### HasUdid

`func (o *InstanceBootOptionsV1) HasUdid() bool`

HasUdid returns a boolean if a field has been set.

### SetUdidNil

`func (o *InstanceBootOptionsV1) SetUdidNil(b bool)`

 SetUdidNil sets the value for Udid to be an explicit nil

### UnsetUdid
`func (o *InstanceBootOptionsV1) UnsetUdid()`

UnsetUdid ensures that no value is present for Udid, not even an explicit nil
### GetEcid

`func (o *InstanceBootOptionsV1) GetEcid() string`

GetEcid returns the Ecid field if non-nil, zero value otherwise.

### GetEcidOk

`func (o *InstanceBootOptionsV1) GetEcidOk() (*string, bool)`

GetEcidOk returns a tuple with the Ecid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEcid

`func (o *InstanceBootOptionsV1) SetEcid(v string)`

SetEcid sets Ecid field to given value.

### HasEcid

`func (o *InstanceBootOptionsV1) HasEcid() bool`

HasEcid returns a boolean if a field has been set.

### SetEcidNil

`func (o *InstanceBootOptionsV1) SetEcidNil(b bool)`

 SetEcidNil sets the value for Ecid to be an explicit nil

### UnsetEcid
`func (o *InstanceBootOptionsV1) UnsetEcid()`

UnsetEcid ensures that no value is present for Ecid, not even an explicit nil
### GetRandomSeed

`func (o *InstanceBootOptionsV1) GetRandomSeed() string`

GetRandomSeed returns the RandomSeed field if non-nil, zero value otherwise.

### GetRandomSeedOk

`func (o *InstanceBootOptionsV1) GetRandomSeedOk() (*string, bool)`

GetRandomSeedOk returns a tuple with the RandomSeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRandomSeed

`func (o *InstanceBootOptionsV1) SetRandomSeed(v string)`

SetRandomSeed sets RandomSeed field to given value.

### HasRandomSeed

`func (o *InstanceBootOptionsV1) HasRandomSeed() bool`

HasRandomSeed returns a boolean if a field has been set.

### SetRandomSeedNil

`func (o *InstanceBootOptionsV1) SetRandomSeedNil(b bool)`

 SetRandomSeedNil sets the value for RandomSeed to be an explicit nil

### UnsetRandomSeed
`func (o *InstanceBootOptionsV1) UnsetRandomSeed()`

UnsetRandomSeed ensures that no value is present for RandomSeed, not even an explicit nil
### GetPac

`func (o *InstanceBootOptionsV1) GetPac() bool`

GetPac returns the Pac field if non-nil, zero value otherwise.

### GetPacOk

`func (o *InstanceBootOptionsV1) GetPacOk() (*bool, bool)`

GetPacOk returns a tuple with the Pac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPac

`func (o *InstanceBootOptionsV1) SetPac(v bool)`

SetPac sets Pac field to given value.

### HasPac

`func (o *InstanceBootOptionsV1) HasPac() bool`

HasPac returns a boolean if a field has been set.

### SetPacNil

`func (o *InstanceBootOptionsV1) SetPacNil(b bool)`

 SetPacNil sets the value for Pac to be an explicit nil

### UnsetPac
`func (o *InstanceBootOptionsV1) UnsetPac()`

UnsetPac ensures that no value is present for Pac, not even an explicit nil
### GetAprr

`func (o *InstanceBootOptionsV1) GetAprr() bool`

GetAprr returns the Aprr field if non-nil, zero value otherwise.

### GetAprrOk

`func (o *InstanceBootOptionsV1) GetAprrOk() (*bool, bool)`

GetAprrOk returns a tuple with the Aprr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAprr

`func (o *InstanceBootOptionsV1) SetAprr(v bool)`

SetAprr sets Aprr field to given value.

### HasAprr

`func (o *InstanceBootOptionsV1) HasAprr() bool`

HasAprr returns a boolean if a field has been set.

### SetAprrNil

`func (o *InstanceBootOptionsV1) SetAprrNil(b bool)`

 SetAprrNil sets the value for Aprr to be an explicit nil

### UnsetAprr
`func (o *InstanceBootOptionsV1) UnsetAprr()`

UnsetAprr ensures that no value is present for Aprr, not even an explicit nil
### GetAdditionalTags

`func (o *InstanceBootOptionsV1) GetAdditionalTags() []InstanceBootOptionsAdditionalTag`

GetAdditionalTags returns the AdditionalTags field if non-nil, zero value otherwise.

### GetAdditionalTagsOk

`func (o *InstanceBootOptionsV1) GetAdditionalTagsOk() (*[]InstanceBootOptionsAdditionalTag, bool)`

GetAdditionalTagsOk returns a tuple with the AdditionalTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalTags

`func (o *InstanceBootOptionsV1) SetAdditionalTags(v []InstanceBootOptionsAdditionalTag)`

SetAdditionalTags sets AdditionalTags field to given value.

### HasAdditionalTags

`func (o *InstanceBootOptionsV1) HasAdditionalTags() bool`

HasAdditionalTags returns a boolean if a field has been set.

### SetAdditionalTagsNil

`func (o *InstanceBootOptionsV1) SetAdditionalTagsNil(b bool)`

 SetAdditionalTagsNil sets the value for AdditionalTags to be an explicit nil

### UnsetAdditionalTags
`func (o *InstanceBootOptionsV1) UnsetAdditionalTags()`

UnsetAdditionalTags ensures that no value is present for AdditionalTags, not even an explicit nil
### GetKernel

`func (o *InstanceBootOptionsV1) GetKernel() InstanceBootOptionsKernelV1`

GetKernel returns the Kernel field if non-nil, zero value otherwise.

### GetKernelOk

`func (o *InstanceBootOptionsV1) GetKernelOk() (*InstanceBootOptionsKernelV1, bool)`

GetKernelOk returns a tuple with the Kernel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernel

`func (o *InstanceBootOptionsV1) SetKernel(v InstanceBootOptionsKernelV1)`

SetKernel sets Kernel field to given value.

### HasKernel

`func (o *InstanceBootOptionsV1) HasKernel() bool`

HasKernel returns a boolean if a field has been set.

### GetPongo

`func (o *InstanceBootOptionsV1) GetPongo() InstanceBootOptionsPongoV1`

GetPongo returns the Pongo field if non-nil, zero value otherwise.

### GetPongoOk

`func (o *InstanceBootOptionsV1) GetPongoOk() (*InstanceBootOptionsPongoV1, bool)`

GetPongoOk returns a tuple with the Pongo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPongo

`func (o *InstanceBootOptionsV1) SetPongo(v InstanceBootOptionsPongoV1)`

SetPongo sets Pongo field to given value.

### HasPongo

`func (o *InstanceBootOptionsV1) HasPongo() bool`

HasPongo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


