# ClusterSnapshotMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Live** | Pointer to **bool** | Whether this was a live snapshot. | [optional] 
**Fresh** | Pointer to **bool** | Whether the snapshot was created immediately after device restore. | [optional] 
**HwPac** | Pointer to **float32** | Hardware PAC value. | [optional] 
**Springboard** | Pointer to **bool** | Whether this is a springboard snapshot. | [optional] 
**BootOptions** | Pointer to [**InstanceBootOptions**](InstanceBootOptions.md) | Boot options. | [optional] 
**Device** | Pointer to **map[string]interface{}** | Device metadata. | [optional] 
**Flavor** | Pointer to **string** | Device flavor. | [optional] 
**OsVersion** | Pointer to **string** | OS version. | [optional] 
**OsBuild** | Pointer to **string** | OS build identifier. | [optional] 
**Patches** | Pointer to **string** | Patches applied. | [optional] 
**Cpid** | Pointer to **float32** | Chip ID. | [optional] 

## Methods

### NewClusterSnapshotMetadata

`func NewClusterSnapshotMetadata() *ClusterSnapshotMetadata`

NewClusterSnapshotMetadata instantiates a new ClusterSnapshotMetadata object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterSnapshotMetadataWithDefaults

`func NewClusterSnapshotMetadataWithDefaults() *ClusterSnapshotMetadata`

NewClusterSnapshotMetadataWithDefaults instantiates a new ClusterSnapshotMetadata object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLive

`func (o *ClusterSnapshotMetadata) GetLive() bool`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *ClusterSnapshotMetadata) GetLiveOk() (*bool, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *ClusterSnapshotMetadata) SetLive(v bool)`

SetLive sets Live field to given value.

### HasLive

`func (o *ClusterSnapshotMetadata) HasLive() bool`

HasLive returns a boolean if a field has been set.

### GetFresh

`func (o *ClusterSnapshotMetadata) GetFresh() bool`

GetFresh returns the Fresh field if non-nil, zero value otherwise.

### GetFreshOk

`func (o *ClusterSnapshotMetadata) GetFreshOk() (*bool, bool)`

GetFreshOk returns a tuple with the Fresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFresh

`func (o *ClusterSnapshotMetadata) SetFresh(v bool)`

SetFresh sets Fresh field to given value.

### HasFresh

`func (o *ClusterSnapshotMetadata) HasFresh() bool`

HasFresh returns a boolean if a field has been set.

### GetHwPac

`func (o *ClusterSnapshotMetadata) GetHwPac() float32`

GetHwPac returns the HwPac field if non-nil, zero value otherwise.

### GetHwPacOk

`func (o *ClusterSnapshotMetadata) GetHwPacOk() (*float32, bool)`

GetHwPacOk returns a tuple with the HwPac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHwPac

`func (o *ClusterSnapshotMetadata) SetHwPac(v float32)`

SetHwPac sets HwPac field to given value.

### HasHwPac

`func (o *ClusterSnapshotMetadata) HasHwPac() bool`

HasHwPac returns a boolean if a field has been set.

### GetSpringboard

`func (o *ClusterSnapshotMetadata) GetSpringboard() bool`

GetSpringboard returns the Springboard field if non-nil, zero value otherwise.

### GetSpringboardOk

`func (o *ClusterSnapshotMetadata) GetSpringboardOk() (*bool, bool)`

GetSpringboardOk returns a tuple with the Springboard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpringboard

`func (o *ClusterSnapshotMetadata) SetSpringboard(v bool)`

SetSpringboard sets Springboard field to given value.

### HasSpringboard

`func (o *ClusterSnapshotMetadata) HasSpringboard() bool`

HasSpringboard returns a boolean if a field has been set.

### GetBootOptions

`func (o *ClusterSnapshotMetadata) GetBootOptions() InstanceBootOptions`

GetBootOptions returns the BootOptions field if non-nil, zero value otherwise.

### GetBootOptionsOk

`func (o *ClusterSnapshotMetadata) GetBootOptionsOk() (*InstanceBootOptions, bool)`

GetBootOptionsOk returns a tuple with the BootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootOptions

`func (o *ClusterSnapshotMetadata) SetBootOptions(v InstanceBootOptions)`

SetBootOptions sets BootOptions field to given value.

### HasBootOptions

`func (o *ClusterSnapshotMetadata) HasBootOptions() bool`

HasBootOptions returns a boolean if a field has been set.

### GetDevice

`func (o *ClusterSnapshotMetadata) GetDevice() map[string]interface{}`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *ClusterSnapshotMetadata) GetDeviceOk() (*map[string]interface{}, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *ClusterSnapshotMetadata) SetDevice(v map[string]interface{})`

SetDevice sets Device field to given value.

### HasDevice

`func (o *ClusterSnapshotMetadata) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetFlavor

`func (o *ClusterSnapshotMetadata) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *ClusterSnapshotMetadata) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *ClusterSnapshotMetadata) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *ClusterSnapshotMetadata) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### GetOsVersion

`func (o *ClusterSnapshotMetadata) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *ClusterSnapshotMetadata) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *ClusterSnapshotMetadata) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.

### HasOsVersion

`func (o *ClusterSnapshotMetadata) HasOsVersion() bool`

HasOsVersion returns a boolean if a field has been set.

### GetOsBuild

`func (o *ClusterSnapshotMetadata) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *ClusterSnapshotMetadata) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *ClusterSnapshotMetadata) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.

### HasOsBuild

`func (o *ClusterSnapshotMetadata) HasOsBuild() bool`

HasOsBuild returns a boolean if a field has been set.

### GetPatches

`func (o *ClusterSnapshotMetadata) GetPatches() string`

GetPatches returns the Patches field if non-nil, zero value otherwise.

### GetPatchesOk

`func (o *ClusterSnapshotMetadata) GetPatchesOk() (*string, bool)`

GetPatchesOk returns a tuple with the Patches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatches

`func (o *ClusterSnapshotMetadata) SetPatches(v string)`

SetPatches sets Patches field to given value.

### HasPatches

`func (o *ClusterSnapshotMetadata) HasPatches() bool`

HasPatches returns a boolean if a field has been set.

### GetCpid

`func (o *ClusterSnapshotMetadata) GetCpid() float32`

GetCpid returns the Cpid field if non-nil, zero value otherwise.

### GetCpidOk

`func (o *ClusterSnapshotMetadata) GetCpidOk() (*float32, bool)`

GetCpidOk returns a tuple with the Cpid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpid

`func (o *ClusterSnapshotMetadata) SetCpid(v float32)`

SetCpid sets Cpid field to given value.

### HasCpid

`func (o *ClusterSnapshotMetadata) HasCpid() bool`

HasCpid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


