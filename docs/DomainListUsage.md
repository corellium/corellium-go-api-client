# DomainListUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveInstances** | **float32** | Number of active instances. | 
**ImageBytes** | **float32** | Image storage used in bytes. | 
**Cores** | **float32** | Cores in use. | 
**Instances** | **float32** | Total instances. | 
**Ram** | **float32** | RAM in use in MiB. | 
**Gpu** | **float32** | GPUs in use. | 
**ReservedCores** | Pointer to **float32** | Reserved cores. | [optional] 

## Methods

### NewDomainListUsage

`func NewDomainListUsage(activeInstances float32, imageBytes float32, cores float32, instances float32, ram float32, gpu float32, ) *DomainListUsage`

NewDomainListUsage instantiates a new DomainListUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListUsageWithDefaults

`func NewDomainListUsageWithDefaults() *DomainListUsage`

NewDomainListUsageWithDefaults instantiates a new DomainListUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveInstances

`func (o *DomainListUsage) GetActiveInstances() float32`

GetActiveInstances returns the ActiveInstances field if non-nil, zero value otherwise.

### GetActiveInstancesOk

`func (o *DomainListUsage) GetActiveInstancesOk() (*float32, bool)`

GetActiveInstancesOk returns a tuple with the ActiveInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveInstances

`func (o *DomainListUsage) SetActiveInstances(v float32)`

SetActiveInstances sets ActiveInstances field to given value.


### GetImageBytes

`func (o *DomainListUsage) GetImageBytes() float32`

GetImageBytes returns the ImageBytes field if non-nil, zero value otherwise.

### GetImageBytesOk

`func (o *DomainListUsage) GetImageBytesOk() (*float32, bool)`

GetImageBytesOk returns a tuple with the ImageBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageBytes

`func (o *DomainListUsage) SetImageBytes(v float32)`

SetImageBytes sets ImageBytes field to given value.


### GetCores

`func (o *DomainListUsage) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *DomainListUsage) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *DomainListUsage) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetInstances

`func (o *DomainListUsage) GetInstances() float32`

GetInstances returns the Instances field if non-nil, zero value otherwise.

### GetInstancesOk

`func (o *DomainListUsage) GetInstancesOk() (*float32, bool)`

GetInstancesOk returns a tuple with the Instances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstances

`func (o *DomainListUsage) SetInstances(v float32)`

SetInstances sets Instances field to given value.


### GetRam

`func (o *DomainListUsage) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *DomainListUsage) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *DomainListUsage) SetRam(v float32)`

SetRam sets Ram field to given value.


### GetGpu

`func (o *DomainListUsage) GetGpu() float32`

GetGpu returns the Gpu field if non-nil, zero value otherwise.

### GetGpuOk

`func (o *DomainListUsage) GetGpuOk() (*float32, bool)`

GetGpuOk returns a tuple with the Gpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpu

`func (o *DomainListUsage) SetGpu(v float32)`

SetGpu sets Gpu field to given value.


### GetReservedCores

`func (o *DomainListUsage) GetReservedCores() float32`

GetReservedCores returns the ReservedCores field if non-nil, zero value otherwise.

### GetReservedCoresOk

`func (o *DomainListUsage) GetReservedCoresOk() (*float32, bool)`

GetReservedCoresOk returns a tuple with the ReservedCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedCores

`func (o *DomainListUsage) SetReservedCores(v float32)`

SetReservedCores sets ReservedCores field to given value.

### HasReservedCores

`func (o *DomainListUsage) HasReservedCores() bool`

HasReservedCores returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


