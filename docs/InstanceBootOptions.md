# InstanceBootOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BootArgs** | Pointer to **string** | Boot arguments passed to the kernel at normal boot. | [optional] 
**RestoreBootArgs** | Pointer to **string** | Boot arguments passed to the kernel during restore. | [optional] 
**Udid** | Pointer to **string** | Boot UDID. | [optional] 
**Ecid** | Pointer to **string** | Assigned ECID (hex). | [optional] 
**RandomSeed** | Pointer to **string** | Random seed provided to boot, if any. | [optional] 
**Pac** | Pointer to **bool** | Enable Pointer Authentication Codes (PAC), the Apple processor feature that signs pointers to block memory-corruption attacks. | [optional] 
**Aprr** | Pointer to **bool** | Enable APRR, the Apple processor feature that controls memory page permissions (used by kernel protections). | [optional] 
**Cores** | Pointer to **float32** | Number of CPU cores for the device. Only models whose &#x60;dynamicHardwareChanges&#x60; is true in &#x60;GET /v3/models&#x60; honor this; others always use the model default. The value must be between the model&#39;s &#x60;coresMin&#x60; and &#x60;coresMax&#x60;; a value outside that range is silently replaced by the model default rather than rejected, so check the device afterwards. | [optional] 
**Ram** | Pointer to **float32** | Memory for the device, in MiB (1024 MiB &#x3D; 1 GiB). Only models whose &#x60;dynamicHardwareChanges&#x60; is true honor this; others always use the model default. The value must be between the model&#39;s &#x60;ramMin&#x60; and &#x60;ramMax&#x60;, and at most 1 GiB per CPU core; otherwise the request fails with 400. | [optional] 
**AdditionalTags** | Pointer to [**[]CharmTag**](CharmTag.md) | Additional boot tags to apply to the instance. Each value must be one of the supported charm boot tags. | [optional] 
**Kernel** | Pointer to [**InstanceBootOptionsKernel**](InstanceBootOptionsKernel.md) |  | [optional] 
**Pongo** | Pointer to [**InstanceBootOptionsPongo**](InstanceBootOptionsPongo.md) |  | [optional] 
**Serial** | Pointer to **string** | Device serial number. | [optional] 
**NoSnapshotMount** | Pointer to **bool** | Do not mount iOS snapshot (iOS only). | [optional] 
**KernelSlide** | Pointer to **string** | Kernel slide value (iOS only). | [optional] 
**CdHashes** | Pointer to **[]string** | Hashes of trusted binaries (iOS only). | [optional] 
**Imei** | Pointer to **string** | IMEI. | [optional] 
**Imsi** | Pointer to **string** | IMSI. | [optional] 
**Ssid0** | Pointer to **string** | WiFi SSID. | [optional] 
**Ssid1** | Pointer to **string** | Secondary WiFi SSID. | [optional] 
**WifiMac** | Pointer to **string** | WiFi MAC address. | [optional] 
**ModelId** | Pointer to **string** | Device model identifier. | [optional] 
**ManufacturerId** | Pointer to **string** | Device manufacturer identifier. | [optional] 
**KernelPatches** | Pointer to **string** | Kernel patches to apply. | [optional] 
**StopOnFault** | Pointer to **bool** | Leaves the VM in the paused state on hypervisor vault if false. | [optional] [default to true]
**BootAddr** | Pointer to **string** | Boot address. | [optional] 
**Tzen** | Pointer to **NullableBool** | Enable TrustZone security. | [optional] 
**AuthorizedKeys** | Pointer to **string** | SSH authorized keys to install on the instance. | [optional] 
**VMMIO** | Pointer to [**[]InstanceBootOptionsVMMIOInner**](InstanceBootOptionsVMMIOInner.md) | Parameters to export a VM address space range (and IRQ &amp; DMA functionality) over TCP to different models running on different machines or inside a different VM. | [optional] 
**Fvp** | Pointer to [**InstanceBootOptionsFvp**](InstanceBootOptionsFvp.md) |  | [optional] 

## Methods

### NewInstanceBootOptions

`func NewInstanceBootOptions() *InstanceBootOptions`

NewInstanceBootOptions instantiates a new InstanceBootOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceBootOptionsWithDefaults

`func NewInstanceBootOptionsWithDefaults() *InstanceBootOptions`

NewInstanceBootOptionsWithDefaults instantiates a new InstanceBootOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBootArgs

`func (o *InstanceBootOptions) GetBootArgs() string`

GetBootArgs returns the BootArgs field if non-nil, zero value otherwise.

### GetBootArgsOk

`func (o *InstanceBootOptions) GetBootArgsOk() (*string, bool)`

GetBootArgsOk returns a tuple with the BootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootArgs

`func (o *InstanceBootOptions) SetBootArgs(v string)`

SetBootArgs sets BootArgs field to given value.

### HasBootArgs

`func (o *InstanceBootOptions) HasBootArgs() bool`

HasBootArgs returns a boolean if a field has been set.

### GetRestoreBootArgs

`func (o *InstanceBootOptions) GetRestoreBootArgs() string`

GetRestoreBootArgs returns the RestoreBootArgs field if non-nil, zero value otherwise.

### GetRestoreBootArgsOk

`func (o *InstanceBootOptions) GetRestoreBootArgsOk() (*string, bool)`

GetRestoreBootArgsOk returns a tuple with the RestoreBootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestoreBootArgs

`func (o *InstanceBootOptions) SetRestoreBootArgs(v string)`

SetRestoreBootArgs sets RestoreBootArgs field to given value.

### HasRestoreBootArgs

`func (o *InstanceBootOptions) HasRestoreBootArgs() bool`

HasRestoreBootArgs returns a boolean if a field has been set.

### GetUdid

`func (o *InstanceBootOptions) GetUdid() string`

GetUdid returns the Udid field if non-nil, zero value otherwise.

### GetUdidOk

`func (o *InstanceBootOptions) GetUdidOk() (*string, bool)`

GetUdidOk returns a tuple with the Udid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUdid

`func (o *InstanceBootOptions) SetUdid(v string)`

SetUdid sets Udid field to given value.

### HasUdid

`func (o *InstanceBootOptions) HasUdid() bool`

HasUdid returns a boolean if a field has been set.

### GetEcid

`func (o *InstanceBootOptions) GetEcid() string`

GetEcid returns the Ecid field if non-nil, zero value otherwise.

### GetEcidOk

`func (o *InstanceBootOptions) GetEcidOk() (*string, bool)`

GetEcidOk returns a tuple with the Ecid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEcid

`func (o *InstanceBootOptions) SetEcid(v string)`

SetEcid sets Ecid field to given value.

### HasEcid

`func (o *InstanceBootOptions) HasEcid() bool`

HasEcid returns a boolean if a field has been set.

### GetRandomSeed

`func (o *InstanceBootOptions) GetRandomSeed() string`

GetRandomSeed returns the RandomSeed field if non-nil, zero value otherwise.

### GetRandomSeedOk

`func (o *InstanceBootOptions) GetRandomSeedOk() (*string, bool)`

GetRandomSeedOk returns a tuple with the RandomSeed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRandomSeed

`func (o *InstanceBootOptions) SetRandomSeed(v string)`

SetRandomSeed sets RandomSeed field to given value.

### HasRandomSeed

`func (o *InstanceBootOptions) HasRandomSeed() bool`

HasRandomSeed returns a boolean if a field has been set.

### GetPac

`func (o *InstanceBootOptions) GetPac() bool`

GetPac returns the Pac field if non-nil, zero value otherwise.

### GetPacOk

`func (o *InstanceBootOptions) GetPacOk() (*bool, bool)`

GetPacOk returns a tuple with the Pac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPac

`func (o *InstanceBootOptions) SetPac(v bool)`

SetPac sets Pac field to given value.

### HasPac

`func (o *InstanceBootOptions) HasPac() bool`

HasPac returns a boolean if a field has been set.

### GetAprr

`func (o *InstanceBootOptions) GetAprr() bool`

GetAprr returns the Aprr field if non-nil, zero value otherwise.

### GetAprrOk

`func (o *InstanceBootOptions) GetAprrOk() (*bool, bool)`

GetAprrOk returns a tuple with the Aprr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAprr

`func (o *InstanceBootOptions) SetAprr(v bool)`

SetAprr sets Aprr field to given value.

### HasAprr

`func (o *InstanceBootOptions) HasAprr() bool`

HasAprr returns a boolean if a field has been set.

### GetCores

`func (o *InstanceBootOptions) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *InstanceBootOptions) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *InstanceBootOptions) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *InstanceBootOptions) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetRam

`func (o *InstanceBootOptions) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *InstanceBootOptions) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *InstanceBootOptions) SetRam(v float32)`

SetRam sets Ram field to given value.

### HasRam

`func (o *InstanceBootOptions) HasRam() bool`

HasRam returns a boolean if a field has been set.

### GetAdditionalTags

`func (o *InstanceBootOptions) GetAdditionalTags() []CharmTag`

GetAdditionalTags returns the AdditionalTags field if non-nil, zero value otherwise.

### GetAdditionalTagsOk

`func (o *InstanceBootOptions) GetAdditionalTagsOk() (*[]CharmTag, bool)`

GetAdditionalTagsOk returns a tuple with the AdditionalTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalTags

`func (o *InstanceBootOptions) SetAdditionalTags(v []CharmTag)`

SetAdditionalTags sets AdditionalTags field to given value.

### HasAdditionalTags

`func (o *InstanceBootOptions) HasAdditionalTags() bool`

HasAdditionalTags returns a boolean if a field has been set.

### GetKernel

`func (o *InstanceBootOptions) GetKernel() InstanceBootOptionsKernel`

GetKernel returns the Kernel field if non-nil, zero value otherwise.

### GetKernelOk

`func (o *InstanceBootOptions) GetKernelOk() (*InstanceBootOptionsKernel, bool)`

GetKernelOk returns a tuple with the Kernel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernel

`func (o *InstanceBootOptions) SetKernel(v InstanceBootOptionsKernel)`

SetKernel sets Kernel field to given value.

### HasKernel

`func (o *InstanceBootOptions) HasKernel() bool`

HasKernel returns a boolean if a field has been set.

### GetPongo

`func (o *InstanceBootOptions) GetPongo() InstanceBootOptionsPongo`

GetPongo returns the Pongo field if non-nil, zero value otherwise.

### GetPongoOk

`func (o *InstanceBootOptions) GetPongoOk() (*InstanceBootOptionsPongo, bool)`

GetPongoOk returns a tuple with the Pongo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPongo

`func (o *InstanceBootOptions) SetPongo(v InstanceBootOptionsPongo)`

SetPongo sets Pongo field to given value.

### HasPongo

`func (o *InstanceBootOptions) HasPongo() bool`

HasPongo returns a boolean if a field has been set.

### GetSerial

`func (o *InstanceBootOptions) GetSerial() string`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *InstanceBootOptions) GetSerialOk() (*string, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *InstanceBootOptions) SetSerial(v string)`

SetSerial sets Serial field to given value.

### HasSerial

`func (o *InstanceBootOptions) HasSerial() bool`

HasSerial returns a boolean if a field has been set.

### GetNoSnapshotMount

`func (o *InstanceBootOptions) GetNoSnapshotMount() bool`

GetNoSnapshotMount returns the NoSnapshotMount field if non-nil, zero value otherwise.

### GetNoSnapshotMountOk

`func (o *InstanceBootOptions) GetNoSnapshotMountOk() (*bool, bool)`

GetNoSnapshotMountOk returns a tuple with the NoSnapshotMount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoSnapshotMount

`func (o *InstanceBootOptions) SetNoSnapshotMount(v bool)`

SetNoSnapshotMount sets NoSnapshotMount field to given value.

### HasNoSnapshotMount

`func (o *InstanceBootOptions) HasNoSnapshotMount() bool`

HasNoSnapshotMount returns a boolean if a field has been set.

### GetKernelSlide

`func (o *InstanceBootOptions) GetKernelSlide() string`

GetKernelSlide returns the KernelSlide field if non-nil, zero value otherwise.

### GetKernelSlideOk

`func (o *InstanceBootOptions) GetKernelSlideOk() (*string, bool)`

GetKernelSlideOk returns a tuple with the KernelSlide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelSlide

`func (o *InstanceBootOptions) SetKernelSlide(v string)`

SetKernelSlide sets KernelSlide field to given value.

### HasKernelSlide

`func (o *InstanceBootOptions) HasKernelSlide() bool`

HasKernelSlide returns a boolean if a field has been set.

### GetCdHashes

`func (o *InstanceBootOptions) GetCdHashes() []string`

GetCdHashes returns the CdHashes field if non-nil, zero value otherwise.

### GetCdHashesOk

`func (o *InstanceBootOptions) GetCdHashesOk() (*[]string, bool)`

GetCdHashesOk returns a tuple with the CdHashes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCdHashes

`func (o *InstanceBootOptions) SetCdHashes(v []string)`

SetCdHashes sets CdHashes field to given value.

### HasCdHashes

`func (o *InstanceBootOptions) HasCdHashes() bool`

HasCdHashes returns a boolean if a field has been set.

### GetImei

`func (o *InstanceBootOptions) GetImei() string`

GetImei returns the Imei field if non-nil, zero value otherwise.

### GetImeiOk

`func (o *InstanceBootOptions) GetImeiOk() (*string, bool)`

GetImeiOk returns a tuple with the Imei field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImei

`func (o *InstanceBootOptions) SetImei(v string)`

SetImei sets Imei field to given value.

### HasImei

`func (o *InstanceBootOptions) HasImei() bool`

HasImei returns a boolean if a field has been set.

### GetImsi

`func (o *InstanceBootOptions) GetImsi() string`

GetImsi returns the Imsi field if non-nil, zero value otherwise.

### GetImsiOk

`func (o *InstanceBootOptions) GetImsiOk() (*string, bool)`

GetImsiOk returns a tuple with the Imsi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImsi

`func (o *InstanceBootOptions) SetImsi(v string)`

SetImsi sets Imsi field to given value.

### HasImsi

`func (o *InstanceBootOptions) HasImsi() bool`

HasImsi returns a boolean if a field has been set.

### GetSsid0

`func (o *InstanceBootOptions) GetSsid0() string`

GetSsid0 returns the Ssid0 field if non-nil, zero value otherwise.

### GetSsid0Ok

`func (o *InstanceBootOptions) GetSsid0Ok() (*string, bool)`

GetSsid0Ok returns a tuple with the Ssid0 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSsid0

`func (o *InstanceBootOptions) SetSsid0(v string)`

SetSsid0 sets Ssid0 field to given value.

### HasSsid0

`func (o *InstanceBootOptions) HasSsid0() bool`

HasSsid0 returns a boolean if a field has been set.

### GetSsid1

`func (o *InstanceBootOptions) GetSsid1() string`

GetSsid1 returns the Ssid1 field if non-nil, zero value otherwise.

### GetSsid1Ok

`func (o *InstanceBootOptions) GetSsid1Ok() (*string, bool)`

GetSsid1Ok returns a tuple with the Ssid1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSsid1

`func (o *InstanceBootOptions) SetSsid1(v string)`

SetSsid1 sets Ssid1 field to given value.

### HasSsid1

`func (o *InstanceBootOptions) HasSsid1() bool`

HasSsid1 returns a boolean if a field has been set.

### GetWifiMac

`func (o *InstanceBootOptions) GetWifiMac() string`

GetWifiMac returns the WifiMac field if non-nil, zero value otherwise.

### GetWifiMacOk

`func (o *InstanceBootOptions) GetWifiMacOk() (*string, bool)`

GetWifiMacOk returns a tuple with the WifiMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiMac

`func (o *InstanceBootOptions) SetWifiMac(v string)`

SetWifiMac sets WifiMac field to given value.

### HasWifiMac

`func (o *InstanceBootOptions) HasWifiMac() bool`

HasWifiMac returns a boolean if a field has been set.

### GetModelId

`func (o *InstanceBootOptions) GetModelId() string`

GetModelId returns the ModelId field if non-nil, zero value otherwise.

### GetModelIdOk

`func (o *InstanceBootOptions) GetModelIdOk() (*string, bool)`

GetModelIdOk returns a tuple with the ModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelId

`func (o *InstanceBootOptions) SetModelId(v string)`

SetModelId sets ModelId field to given value.

### HasModelId

`func (o *InstanceBootOptions) HasModelId() bool`

HasModelId returns a boolean if a field has been set.

### GetManufacturerId

`func (o *InstanceBootOptions) GetManufacturerId() string`

GetManufacturerId returns the ManufacturerId field if non-nil, zero value otherwise.

### GetManufacturerIdOk

`func (o *InstanceBootOptions) GetManufacturerIdOk() (*string, bool)`

GetManufacturerIdOk returns a tuple with the ManufacturerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerId

`func (o *InstanceBootOptions) SetManufacturerId(v string)`

SetManufacturerId sets ManufacturerId field to given value.

### HasManufacturerId

`func (o *InstanceBootOptions) HasManufacturerId() bool`

HasManufacturerId returns a boolean if a field has been set.

### GetKernelPatches

`func (o *InstanceBootOptions) GetKernelPatches() string`

GetKernelPatches returns the KernelPatches field if non-nil, zero value otherwise.

### GetKernelPatchesOk

`func (o *InstanceBootOptions) GetKernelPatchesOk() (*string, bool)`

GetKernelPatchesOk returns a tuple with the KernelPatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelPatches

`func (o *InstanceBootOptions) SetKernelPatches(v string)`

SetKernelPatches sets KernelPatches field to given value.

### HasKernelPatches

`func (o *InstanceBootOptions) HasKernelPatches() bool`

HasKernelPatches returns a boolean if a field has been set.

### GetStopOnFault

`func (o *InstanceBootOptions) GetStopOnFault() bool`

GetStopOnFault returns the StopOnFault field if non-nil, zero value otherwise.

### GetStopOnFaultOk

`func (o *InstanceBootOptions) GetStopOnFaultOk() (*bool, bool)`

GetStopOnFaultOk returns a tuple with the StopOnFault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnFault

`func (o *InstanceBootOptions) SetStopOnFault(v bool)`

SetStopOnFault sets StopOnFault field to given value.

### HasStopOnFault

`func (o *InstanceBootOptions) HasStopOnFault() bool`

HasStopOnFault returns a boolean if a field has been set.

### GetBootAddr

`func (o *InstanceBootOptions) GetBootAddr() string`

GetBootAddr returns the BootAddr field if non-nil, zero value otherwise.

### GetBootAddrOk

`func (o *InstanceBootOptions) GetBootAddrOk() (*string, bool)`

GetBootAddrOk returns a tuple with the BootAddr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootAddr

`func (o *InstanceBootOptions) SetBootAddr(v string)`

SetBootAddr sets BootAddr field to given value.

### HasBootAddr

`func (o *InstanceBootOptions) HasBootAddr() bool`

HasBootAddr returns a boolean if a field has been set.

### GetTzen

`func (o *InstanceBootOptions) GetTzen() bool`

GetTzen returns the Tzen field if non-nil, zero value otherwise.

### GetTzenOk

`func (o *InstanceBootOptions) GetTzenOk() (*bool, bool)`

GetTzenOk returns a tuple with the Tzen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTzen

`func (o *InstanceBootOptions) SetTzen(v bool)`

SetTzen sets Tzen field to given value.

### HasTzen

`func (o *InstanceBootOptions) HasTzen() bool`

HasTzen returns a boolean if a field has been set.

### SetTzenNil

`func (o *InstanceBootOptions) SetTzenNil(b bool)`

 SetTzenNil sets the value for Tzen to be an explicit nil

### UnsetTzen
`func (o *InstanceBootOptions) UnsetTzen()`

UnsetTzen ensures that no value is present for Tzen, not even an explicit nil
### GetAuthorizedKeys

`func (o *InstanceBootOptions) GetAuthorizedKeys() string`

GetAuthorizedKeys returns the AuthorizedKeys field if non-nil, zero value otherwise.

### GetAuthorizedKeysOk

`func (o *InstanceBootOptions) GetAuthorizedKeysOk() (*string, bool)`

GetAuthorizedKeysOk returns a tuple with the AuthorizedKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizedKeys

`func (o *InstanceBootOptions) SetAuthorizedKeys(v string)`

SetAuthorizedKeys sets AuthorizedKeys field to given value.

### HasAuthorizedKeys

`func (o *InstanceBootOptions) HasAuthorizedKeys() bool`

HasAuthorizedKeys returns a boolean if a field has been set.

### GetVMMIO

`func (o *InstanceBootOptions) GetVMMIO() []InstanceBootOptionsVMMIOInner`

GetVMMIO returns the VMMIO field if non-nil, zero value otherwise.

### GetVMMIOOk

`func (o *InstanceBootOptions) GetVMMIOOk() (*[]InstanceBootOptionsVMMIOInner, bool)`

GetVMMIOOk returns a tuple with the VMMIO field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVMMIO

`func (o *InstanceBootOptions) SetVMMIO(v []InstanceBootOptionsVMMIOInner)`

SetVMMIO sets VMMIO field to given value.

### HasVMMIO

`func (o *InstanceBootOptions) HasVMMIO() bool`

HasVMMIO returns a boolean if a field has been set.

### GetFvp

`func (o *InstanceBootOptions) GetFvp() InstanceBootOptionsFvp`

GetFvp returns the Fvp field if non-nil, zero value otherwise.

### GetFvpOk

`func (o *InstanceBootOptions) GetFvpOk() (*InstanceBootOptionsFvp, bool)`

GetFvpOk returns a tuple with the Fvp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFvp

`func (o *InstanceBootOptions) SetFvp(v InstanceBootOptionsFvp)`

SetFvp sets Fvp field to given value.

### HasFvp

`func (o *InstanceBootOptions) HasFvp() bool`

HasFvp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


