# ClusterNodeReserved

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cores** | **NullableFloat32** | Number of CPU cores. | 
**Ram** | **NullableFloat32** | RAM in MiB. | 
**Disk** | **NullableFloat32** | Disk in GiB. | 
**Slot** | **NullableFloat32** | Number of device slots. | 
**Gpu** | **NullableFloat32** | Number of GPUs. | 

## Methods

### NewClusterNodeReserved

`func NewClusterNodeReserved(cores NullableFloat32, ram NullableFloat32, disk NullableFloat32, slot NullableFloat32, gpu NullableFloat32, ) *ClusterNodeReserved`

NewClusterNodeReserved instantiates a new ClusterNodeReserved object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterNodeReservedWithDefaults

`func NewClusterNodeReservedWithDefaults() *ClusterNodeReserved`

NewClusterNodeReservedWithDefaults instantiates a new ClusterNodeReserved object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCores

`func (o *ClusterNodeReserved) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *ClusterNodeReserved) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *ClusterNodeReserved) SetCores(v float32)`

SetCores sets Cores field to given value.


### SetCoresNil

`func (o *ClusterNodeReserved) SetCoresNil(b bool)`

 SetCoresNil sets the value for Cores to be an explicit nil

### UnsetCores
`func (o *ClusterNodeReserved) UnsetCores()`

UnsetCores ensures that no value is present for Cores, not even an explicit nil
### GetRam

`func (o *ClusterNodeReserved) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *ClusterNodeReserved) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *ClusterNodeReserved) SetRam(v float32)`

SetRam sets Ram field to given value.


### SetRamNil

`func (o *ClusterNodeReserved) SetRamNil(b bool)`

 SetRamNil sets the value for Ram to be an explicit nil

### UnsetRam
`func (o *ClusterNodeReserved) UnsetRam()`

UnsetRam ensures that no value is present for Ram, not even an explicit nil
### GetDisk

`func (o *ClusterNodeReserved) GetDisk() float32`

GetDisk returns the Disk field if non-nil, zero value otherwise.

### GetDiskOk

`func (o *ClusterNodeReserved) GetDiskOk() (*float32, bool)`

GetDiskOk returns a tuple with the Disk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisk

`func (o *ClusterNodeReserved) SetDisk(v float32)`

SetDisk sets Disk field to given value.


### SetDiskNil

`func (o *ClusterNodeReserved) SetDiskNil(b bool)`

 SetDiskNil sets the value for Disk to be an explicit nil

### UnsetDisk
`func (o *ClusterNodeReserved) UnsetDisk()`

UnsetDisk ensures that no value is present for Disk, not even an explicit nil
### GetSlot

`func (o *ClusterNodeReserved) GetSlot() float32`

GetSlot returns the Slot field if non-nil, zero value otherwise.

### GetSlotOk

`func (o *ClusterNodeReserved) GetSlotOk() (*float32, bool)`

GetSlotOk returns a tuple with the Slot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlot

`func (o *ClusterNodeReserved) SetSlot(v float32)`

SetSlot sets Slot field to given value.


### SetSlotNil

`func (o *ClusterNodeReserved) SetSlotNil(b bool)`

 SetSlotNil sets the value for Slot to be an explicit nil

### UnsetSlot
`func (o *ClusterNodeReserved) UnsetSlot()`

UnsetSlot ensures that no value is present for Slot, not even an explicit nil
### GetGpu

`func (o *ClusterNodeReserved) GetGpu() float32`

GetGpu returns the Gpu field if non-nil, zero value otherwise.

### GetGpuOk

`func (o *ClusterNodeReserved) GetGpuOk() (*float32, bool)`

GetGpuOk returns a tuple with the Gpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpu

`func (o *ClusterNodeReserved) SetGpu(v float32)`

SetGpu sets Gpu field to given value.


### SetGpuNil

`func (o *ClusterNodeReserved) SetGpuNil(b bool)`

 SetGpuNil sets the value for Gpu to be an explicit nil

### UnsetGpu
`func (o *ClusterNodeReserved) UnsetGpu()`

UnsetGpu ensures that no value is present for Gpu, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


