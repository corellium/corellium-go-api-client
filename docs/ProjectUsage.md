# ProjectUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cores** | Pointer to **float32** | CPU cores in use. | [optional] 
**Instances** | Pointer to **float32** | Instances in use. | [optional] 
**Ram** | Pointer to **float32** | RAM in use, in mebibytes. | [optional] 
**Gpu** | Pointer to **float32** | GPU units in use. | [optional] 

## Methods

### NewProjectUsage

`func NewProjectUsage() *ProjectUsage`

NewProjectUsage instantiates a new ProjectUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectUsageWithDefaults

`func NewProjectUsageWithDefaults() *ProjectUsage`

NewProjectUsageWithDefaults instantiates a new ProjectUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCores

`func (o *ProjectUsage) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *ProjectUsage) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *ProjectUsage) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *ProjectUsage) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetInstances

`func (o *ProjectUsage) GetInstances() float32`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *ProjectUsage) GetInstancesOk() (*float32, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *ProjectUsage) SetInstances(v float32)`

SetInstances sets Instances field to given value.

### HasInstances

`func (o *ProjectUsage) HasInstances() bool`

HasInstances returns a boolean if a field has been set.

### GetRam

`func (o *ProjectUsage) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *ProjectUsage) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *ProjectUsage) SetRam(v float32)`

SetRam sets Ram field to given value.

### HasRam

`func (o *ProjectUsage) HasRam() bool`

HasRam returns a boolean if a field has been set.

### GetGpu

`func (o *ProjectUsage) GetGpu() float32`

GetGpu returns the Gpu field if non-nil, zero value otherwise.

### GetGpuOk

`func (o *ProjectUsage) GetGpuOk() (*float32, bool)`

GetGpuOk returns a tuple with the Gpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpu

`func (o *ProjectUsage) SetGpu(v float32)`

SetGpu sets Gpu field to given value.

### HasGpu

`func (o *ProjectUsage) HasGpu() bool`

HasGpu returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


