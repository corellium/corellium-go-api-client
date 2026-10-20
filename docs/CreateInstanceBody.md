# CreateInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharedSnapshot** | Pointer to **string** | Identifier of the snapshot that was shared. | [optional] 
**SharedSnapshotPassword** | Pointer to **string** | Password of the shared snapshot named by sharedSnapshot, as set when it was shared. Required when that snapshot was shared with sharing type passwordPublicLink. This is the same value passed as password to POST /v3/snapshots/accept. | [optional] 
**Name** | Pointer to **string** | The name of the device. | [optional] 
**Key** | Pointer to **string** | Key used to encrypt the instance (hex). | [optional] 
**Flavor** | Pointer to **string** | Which device model to create. Use a &#x60;flavor&#x60; value from &#x60;GET /v3/models&#x60;. | [optional] 
**ProjectId** | **string** | Project the device is created in. The device uses that project&#39;s quota (cores, memory, device count). Get IDs from &#x60;GET /v3/projects&#x60;. | 
**OsVersion** | Pointer to **string** | Operating-system version to install, as listed in &#x60;osVersion&#x60; by &#x60;GET /v3/models/{model}/software&#x60;. If you give only &#x60;osVersion&#x60;, the newest build of that version is used. | [optional] 
**OsBuild** | Pointer to **string** | Exact build to install, as listed in &#x60;osBuild&#x60; by &#x60;GET /v3/models/{model}/software&#x60;. Give it together with &#x60;osVersion&#x60; to pin one build. You must give at least one of &#x60;osVersion&#x60; and &#x60;osBuild&#x60;. | [optional] 
**Patches** | Pointer to **[]string** | List of patches to apply. | [optional] 
**FwPackage** | Pointer to **string** | Optional. Boots a specific firmware file instead of choosing one from the model&#39;s software list. Either the &#x60;id&#x60; of an uploaded &#x60;fw&#x60; image (for example one in your project, see &#x60;POST /v3/images&#x60;) or an http(s) URL. When set, it wins over the software list; still pass &#x60;osVersion&#x60; or &#x60;osBuild&#x60;. A domain-level image is copied into your project first. Models whose &#x60;supportsCustomFirmwareImage&#x60; is false reject an image ID here. | [optional] 
**OriginalFirmwarePackageUrl** | Pointer to **string** | URL that the firmware package is available at. | [optional] 
**Encrypt** | Pointer to **bool** | Whether to encrypt the instance. | [optional] 
**WifiMac** | Pointer to **string** | WiFi MAC address to assign to the instance. | [optional] 
**WanAccess** | Pointer to **bool** | Manages internet access. | [optional] 
**Volume** | Pointer to [**VolumeOptions**](VolumeOptions.md) |  | [optional] 
**Snapshot** | Pointer to **string** | Snapshot ID for this instance to be cloned from if defined. | [optional] 
**BootOptions** | Pointer to [**InstanceBootOptions**](InstanceBootOptions.md) |  | [optional] 
**Sbs** | Pointer to **bool** | Should attempt to create springboard snapshot. | [optional] 
**CharmBootArgs** | Pointer to **[]map[string]interface{}** | Optional charm boot args. | [optional] 

## Methods

### NewCreateInstanceBody

`func NewCreateInstanceBody(projectId string, ) *CreateInstanceBody`

NewCreateInstanceBody instantiates a new CreateInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInstanceBodyWithDefaults

`func NewCreateInstanceBodyWithDefaults() *CreateInstanceBody`

NewCreateInstanceBodyWithDefaults instantiates a new CreateInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharedSnapshot

`func (o *CreateInstanceBody) GetSharedSnapshot() string`

GetSharedSnapshot returns the SharedSnapshot field if non-nil, zero value otherwise.

### GetSharedSnapshotOk

`func (o *CreateInstanceBody) GetSharedSnapshotOk() (*string, bool)`

GetSharedSnapshotOk returns a tuple with the SharedSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSnapshot

`func (o *CreateInstanceBody) SetSharedSnapshot(v string)`

SetSharedSnapshot sets SharedSnapshot field to given value.

### HasSharedSnapshot

`func (o *CreateInstanceBody) HasSharedSnapshot() bool`

HasSharedSnapshot returns a boolean if a field has been set.

### GetSharedSnapshotPassword

`func (o *CreateInstanceBody) GetSharedSnapshotPassword() string`

GetSharedSnapshotPassword returns the SharedSnapshotPassword field if non-nil, zero value otherwise.

### GetSharedSnapshotPasswordOk

`func (o *CreateInstanceBody) GetSharedSnapshotPasswordOk() (*string, bool)`

GetSharedSnapshotPasswordOk returns a tuple with the SharedSnapshotPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedSnapshotPassword

`func (o *CreateInstanceBody) SetSharedSnapshotPassword(v string)`

SetSharedSnapshotPassword sets SharedSnapshotPassword field to given value.

### HasSharedSnapshotPassword

`func (o *CreateInstanceBody) HasSharedSnapshotPassword() bool`

HasSharedSnapshotPassword returns a boolean if a field has been set.

### GetName

`func (o *CreateInstanceBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateInstanceBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateInstanceBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateInstanceBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetKey

`func (o *CreateInstanceBody) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateInstanceBody) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateInstanceBody) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *CreateInstanceBody) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetFlavor

`func (o *CreateInstanceBody) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *CreateInstanceBody) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *CreateInstanceBody) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *CreateInstanceBody) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateInstanceBody) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateInstanceBody) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateInstanceBody) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetOsVersion

`func (o *CreateInstanceBody) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *CreateInstanceBody) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *CreateInstanceBody) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.

### HasOsVersion

`func (o *CreateInstanceBody) HasOsVersion() bool`

HasOsVersion returns a boolean if a field has been set.

### GetOsBuild

`func (o *CreateInstanceBody) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *CreateInstanceBody) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *CreateInstanceBody) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.

### HasOsBuild

`func (o *CreateInstanceBody) HasOsBuild() bool`

HasOsBuild returns a boolean if a field has been set.

### GetPatches

`func (o *CreateInstanceBody) GetPatches() []string`

GetPatches returns the Patches field if non-nil, zero value otherwise.

### GetPatchesOk

`func (o *CreateInstanceBody) GetPatchesOk() (*[]string, bool)`

GetPatchesOk returns a tuple with the Patches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatches

`func (o *CreateInstanceBody) SetPatches(v []string)`

SetPatches sets Patches field to given value.

### HasPatches

`func (o *CreateInstanceBody) HasPatches() bool`

HasPatches returns a boolean if a field has been set.

### GetFwPackage

`func (o *CreateInstanceBody) GetFwPackage() string`

GetFwPackage returns the FwPackage field if non-nil, zero value otherwise.

### GetFwPackageOk

`func (o *CreateInstanceBody) GetFwPackageOk() (*string, bool)`

GetFwPackageOk returns a tuple with the FwPackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFwPackage

`func (o *CreateInstanceBody) SetFwPackage(v string)`

SetFwPackage sets FwPackage field to given value.

### HasFwPackage

`func (o *CreateInstanceBody) HasFwPackage() bool`

HasFwPackage returns a boolean if a field has been set.

### GetOriginalFirmwarePackageUrl

`func (o *CreateInstanceBody) GetOriginalFirmwarePackageUrl() string`

GetOriginalFirmwarePackageUrl returns the OriginalFirmwarePackageUrl field if non-nil, zero value otherwise.

### GetOriginalFirmwarePackageUrlOk

`func (o *CreateInstanceBody) GetOriginalFirmwarePackageUrlOk() (*string, bool)`

GetOriginalFirmwarePackageUrlOk returns a tuple with the OriginalFirmwarePackageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFirmwarePackageUrl

`func (o *CreateInstanceBody) SetOriginalFirmwarePackageUrl(v string)`

SetOriginalFirmwarePackageUrl sets OriginalFirmwarePackageUrl field to given value.

### HasOriginalFirmwarePackageUrl

`func (o *CreateInstanceBody) HasOriginalFirmwarePackageUrl() bool`

HasOriginalFirmwarePackageUrl returns a boolean if a field has been set.

### GetEncrypt

`func (o *CreateInstanceBody) GetEncrypt() bool`

GetEncrypt returns the Encrypt field if non-nil, zero value otherwise.

### GetEncryptOk

`func (o *CreateInstanceBody) GetEncryptOk() (*bool, bool)`

GetEncryptOk returns a tuple with the Encrypt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncrypt

`func (o *CreateInstanceBody) SetEncrypt(v bool)`

SetEncrypt sets Encrypt field to given value.

### HasEncrypt

`func (o *CreateInstanceBody) HasEncrypt() bool`

HasEncrypt returns a boolean if a field has been set.

### GetWifiMac

`func (o *CreateInstanceBody) GetWifiMac() string`

GetWifiMac returns the WifiMac field if non-nil, zero value otherwise.

### GetWifiMacOk

`func (o *CreateInstanceBody) GetWifiMacOk() (*string, bool)`

GetWifiMacOk returns a tuple with the WifiMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiMac

`func (o *CreateInstanceBody) SetWifiMac(v string)`

SetWifiMac sets WifiMac field to given value.

### HasWifiMac

`func (o *CreateInstanceBody) HasWifiMac() bool`

HasWifiMac returns a boolean if a field has been set.

### GetWanAccess

`func (o *CreateInstanceBody) GetWanAccess() bool`

GetWanAccess returns the WanAccess field if non-nil, zero value otherwise.

### GetWanAccessOk

`func (o *CreateInstanceBody) GetWanAccessOk() (*bool, bool)`

GetWanAccessOk returns a tuple with the WanAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanAccess

`func (o *CreateInstanceBody) SetWanAccess(v bool)`

SetWanAccess sets WanAccess field to given value.

### HasWanAccess

`func (o *CreateInstanceBody) HasWanAccess() bool`

HasWanAccess returns a boolean if a field has been set.

### GetVolume

`func (o *CreateInstanceBody) GetVolume() VolumeOptions`

GetVolume returns the Volume field if non-nil, zero value otherwise.

### GetVolumeOk

`func (o *CreateInstanceBody) GetVolumeOk() (*VolumeOptions, bool)`

GetVolumeOk returns a tuple with the Volume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume

`func (o *CreateInstanceBody) SetVolume(v VolumeOptions)`

SetVolume sets Volume field to given value.

### HasVolume

`func (o *CreateInstanceBody) HasVolume() bool`

HasVolume returns a boolean if a field has been set.

### GetSnapshot

`func (o *CreateInstanceBody) GetSnapshot() string`

GetSnapshot returns the Snapshot field if non-nil, zero value otherwise.

### GetSnapshotOk

`func (o *CreateInstanceBody) GetSnapshotOk() (*string, bool)`

GetSnapshotOk returns a tuple with the Snapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshot

`func (o *CreateInstanceBody) SetSnapshot(v string)`

SetSnapshot sets Snapshot field to given value.

### HasSnapshot

`func (o *CreateInstanceBody) HasSnapshot() bool`

HasSnapshot returns a boolean if a field has been set.

### GetBootOptions

`func (o *CreateInstanceBody) GetBootOptions() InstanceBootOptions`

GetBootOptions returns the BootOptions field if non-nil, zero value otherwise.

### GetBootOptionsOk

`func (o *CreateInstanceBody) GetBootOptionsOk() (*InstanceBootOptions, bool)`

GetBootOptionsOk returns a tuple with the BootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootOptions

`func (o *CreateInstanceBody) SetBootOptions(v InstanceBootOptions)`

SetBootOptions sets BootOptions field to given value.

### HasBootOptions

`func (o *CreateInstanceBody) HasBootOptions() bool`

HasBootOptions returns a boolean if a field has been set.

### GetSbs

`func (o *CreateInstanceBody) GetSbs() bool`

GetSbs returns the Sbs field if non-nil, zero value otherwise.

### GetSbsOk

`func (o *CreateInstanceBody) GetSbsOk() (*bool, bool)`

GetSbsOk returns a tuple with the Sbs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSbs

`func (o *CreateInstanceBody) SetSbs(v bool)`

SetSbs sets Sbs field to given value.

### HasSbs

`func (o *CreateInstanceBody) HasSbs() bool`

HasSbs returns a boolean if a field has been set.

### GetCharmBootArgs

`func (o *CreateInstanceBody) GetCharmBootArgs() []map[string]interface{}`

GetCharmBootArgs returns the CharmBootArgs field if non-nil, zero value otherwise.

### GetCharmBootArgsOk

`func (o *CreateInstanceBody) GetCharmBootArgsOk() (*[]map[string]interface{}, bool)`

GetCharmBootArgsOk returns a tuple with the CharmBootArgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmBootArgs

`func (o *CreateInstanceBody) SetCharmBootArgs(v []map[string]interface{})`

SetCharmBootArgs sets CharmBootArgs field to given value.

### HasCharmBootArgs

`func (o *CreateInstanceBody) HasCharmBootArgs() bool`

HasCharmBootArgs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


