# LayoutSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FreeCpus** | Pointer to **interface{}** | Free CPU list. | [optional] 
**FreeRam** | Pointer to **interface{}** | Free RAM. | [optional] 
**FreeRanges** | Pointer to **float32** | Free address ranges. | [optional] [default to 0]
**NumaNodes** | Pointer to **float32** | Number of NUMA nodes. | [optional] [default to 0]
**RamCpu** | Pointer to **string** | RAM per CPU. | [optional] [default to "0"]
**NodeMap** | Pointer to **interface{}** | Node map. | [optional] 
**FreeCores** | Pointer to **interface{}** | Free cores list. | [optional] 
**RamCore** | Pointer to **float32** | RAM per core in MiB. | [optional] [default to 0]

## Methods

### NewLayoutSchema

`func NewLayoutSchema() *LayoutSchema`

NewLayoutSchema instantiates a new LayoutSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLayoutSchemaWithDefaults

`func NewLayoutSchemaWithDefaults() *LayoutSchema`

NewLayoutSchemaWithDefaults instantiates a new LayoutSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFreeCpus

`func (o *LayoutSchema) GetFreeCpus() interface{}`

GetFreeCpus returns the FreeCpus field if non-nil, zero value otherwise.

### GetFreeCpusOk

`func (o *LayoutSchema) GetFreeCpusOk() (*interface{}, bool)`

GetFreeCpusOk returns a tuple with the FreeCpus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeCpus

`func (o *LayoutSchema) SetFreeCpus(v interface{})`

SetFreeCpus sets FreeCpus field to given value.

### HasFreeCpus

`func (o *LayoutSchema) HasFreeCpus() bool`

HasFreeCpus returns a boolean if a field has been set.

### SetFreeCpusNil

`func (o *LayoutSchema) SetFreeCpusNil(b bool)`

 SetFreeCpusNil sets the value for FreeCpus to be an explicit nil

### UnsetFreeCpus
`func (o *LayoutSchema) UnsetFreeCpus()`

UnsetFreeCpus ensures that no value is present for FreeCpus, not even an explicit nil
### GetFreeRam

`func (o *LayoutSchema) GetFreeRam() interface{}`

GetFreeRam returns the FreeRam field if non-nil, zero value otherwise.

### GetFreeRamOk

`func (o *LayoutSchema) GetFreeRamOk() (*interface{}, bool)`

GetFreeRamOk returns a tuple with the FreeRam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeRam

`func (o *LayoutSchema) SetFreeRam(v interface{})`

SetFreeRam sets FreeRam field to given value.

### HasFreeRam

`func (o *LayoutSchema) HasFreeRam() bool`

HasFreeRam returns a boolean if a field has been set.

### SetFreeRamNil

`func (o *LayoutSchema) SetFreeRamNil(b bool)`

 SetFreeRamNil sets the value for FreeRam to be an explicit nil

### UnsetFreeRam
`func (o *LayoutSchema) UnsetFreeRam()`

UnsetFreeRam ensures that no value is present for FreeRam, not even an explicit nil
### GetFreeRanges

`func (o *LayoutSchema) GetFreeRanges() float32`

GetFreeRanges returns the FreeRanges field if non-nil, zero value otherwise.

### GetFreeRangesOk

`func (o *LayoutSchema) GetFreeRangesOk() (*float32, bool)`

GetFreeRangesOk returns a tuple with the FreeRanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeRanges

`func (o *LayoutSchema) SetFreeRanges(v float32)`

SetFreeRanges sets FreeRanges field to given value.

### HasFreeRanges

`func (o *LayoutSchema) HasFreeRanges() bool`

HasFreeRanges returns a boolean if a field has been set.

### GetNumaNodes

`func (o *LayoutSchema) GetNumaNodes() float32`

GetNumaNodes returns the NumaNodes field if non-nil, zero value otherwise.

### GetNumaNodesOk

`func (o *LayoutSchema) GetNumaNodesOk() (*float32, bool)`

GetNumaNodesOk returns a tuple with the NumaNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumaNodes

`func (o *LayoutSchema) SetNumaNodes(v float32)`

SetNumaNodes sets NumaNodes field to given value.

### HasNumaNodes

`func (o *LayoutSchema) HasNumaNodes() bool`

HasNumaNodes returns a boolean if a field has been set.

### GetRamCpu

`func (o *LayoutSchema) GetRamCpu() string`

GetRamCpu returns the RamCpu field if non-nil, zero value otherwise.

### GetRamCpuOk

`func (o *LayoutSchema) GetRamCpuOk() (*string, bool)`

GetRamCpuOk returns a tuple with the RamCpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamCpu

`func (o *LayoutSchema) SetRamCpu(v string)`

SetRamCpu sets RamCpu field to given value.

### HasRamCpu

`func (o *LayoutSchema) HasRamCpu() bool`

HasRamCpu returns a boolean if a field has been set.

### GetNodeMap

`func (o *LayoutSchema) GetNodeMap() interface{}`

GetNodeMap returns the NodeMap field if non-nil, zero value otherwise.

### GetNodeMapOk

`func (o *LayoutSchema) GetNodeMapOk() (*interface{}, bool)`

GetNodeMapOk returns a tuple with the NodeMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeMap

`func (o *LayoutSchema) SetNodeMap(v interface{})`

SetNodeMap sets NodeMap field to given value.

### HasNodeMap

`func (o *LayoutSchema) HasNodeMap() bool`

HasNodeMap returns a boolean if a field has been set.

### SetNodeMapNil

`func (o *LayoutSchema) SetNodeMapNil(b bool)`

 SetNodeMapNil sets the value for NodeMap to be an explicit nil

### UnsetNodeMap
`func (o *LayoutSchema) UnsetNodeMap()`

UnsetNodeMap ensures that no value is present for NodeMap, not even an explicit nil
### GetFreeCores

`func (o *LayoutSchema) GetFreeCores() interface{}`

GetFreeCores returns the FreeCores field if non-nil, zero value otherwise.

### GetFreeCoresOk

`func (o *LayoutSchema) GetFreeCoresOk() (*interface{}, bool)`

GetFreeCoresOk returns a tuple with the FreeCores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeCores

`func (o *LayoutSchema) SetFreeCores(v interface{})`

SetFreeCores sets FreeCores field to given value.

### HasFreeCores

`func (o *LayoutSchema) HasFreeCores() bool`

HasFreeCores returns a boolean if a field has been set.

### SetFreeCoresNil

`func (o *LayoutSchema) SetFreeCoresNil(b bool)`

 SetFreeCoresNil sets the value for FreeCores to be an explicit nil

### UnsetFreeCores
`func (o *LayoutSchema) UnsetFreeCores()`

UnsetFreeCores ensures that no value is present for FreeCores, not even an explicit nil
### GetRamCore

`func (o *LayoutSchema) GetRamCore() float32`

GetRamCore returns the RamCore field if non-nil, zero value otherwise.

### GetRamCoreOk

`func (o *LayoutSchema) GetRamCoreOk() (*float32, bool)`

GetRamCoreOk returns a tuple with the RamCore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamCore

`func (o *LayoutSchema) SetRamCore(v float32)`

SetRamCore sets RamCore field to given value.

### HasRamCore

`func (o *LayoutSchema) HasRamCore() bool`

HasRamCore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


