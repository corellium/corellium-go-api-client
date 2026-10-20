# SysInfoSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NumaNodes** | Pointer to **float32** | Number of NUMA nodes. | [optional] [default to 0]
**Cpu** | Pointer to **interface{}** | CPU availability. | [optional] 
**CpuAvail** | Pointer to **interface{}** | Available CPU. | [optional] 
**Slot** | Pointer to **float32** | Slot count. | [optional] [default to 0]
**SlotAvail** | Pointer to **float32** | Available slot count. | [optional] [default to 0]
**Ram** | Pointer to **float32** | Total RAM in MiB. | [optional] [default to 0]
**RamAvail** | Pointer to **float32** | Available RAM in MiB. | [optional] [default to 0]
**Vpn** | Pointer to **float32** | VPN count. | [optional] [default to 0]
**VpnAvail** | Pointer to **float32** | Available VPN count. | [optional] [default to 0]
**Gpu** | Pointer to **float32** | GPU count. | [optional] [default to 0]
**GpuAvail** | Pointer to **float32** | Available GPU count. | [optional] [default to 0]
**RamCpu** | Pointer to **string** | RAM per CPU. | [optional] [default to "0"]
**El032** | Pointer to **string** | EL0-32 capability. | [optional] [default to "0"]
**El132** | Pointer to **string** | EL1-32 capability. | [optional] [default to "0"]
**MmuTg16k** | Pointer to **string** | MMU 16K translation granule support. | [optional] [default to "0"]
**HwPac** | Pointer to **float32** | Hardware pointer authentication support. | [optional] [default to 0]
**ArmTrace** | Pointer to **string** | ARM trace capability. | [optional] [default to "0"]
**Cores** | Pointer to **float32** | Total core count. | [optional] [default to 0]
**CoresAvail** | Pointer to **float32** | Available core count. | [optional] [default to 0]
**RamCore** | Pointer to **float32** | RAM per core in MiB. | [optional] [default to 0]

## Methods

### NewSysInfoSchema

`func NewSysInfoSchema() *SysInfoSchema`

NewSysInfoSchema instantiates a new SysInfoSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSysInfoSchemaWithDefaults

`func NewSysInfoSchemaWithDefaults() *SysInfoSchema`

NewSysInfoSchemaWithDefaults instantiates a new SysInfoSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNumaNodes

`func (o *SysInfoSchema) GetNumaNodes() float32`

GetNumaNodes returns the NumaNodes field if non-nil, zero value otherwise.

### GetNumaNodesOk

`func (o *SysInfoSchema) GetNumaNodesOk() (*float32, bool)`

GetNumaNodesOk returns a tuple with the NumaNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumaNodes

`func (o *SysInfoSchema) SetNumaNodes(v float32)`

SetNumaNodes sets NumaNodes field to given value.

### HasNumaNodes

`func (o *SysInfoSchema) HasNumaNodes() bool`

HasNumaNodes returns a boolean if a field has been set.

### GetCpu

`func (o *SysInfoSchema) GetCpu() interface{}`

GetCpu returns the Cpu field if non-nil, zero value otherwise.

### GetCpuOk

`func (o *SysInfoSchema) GetCpuOk() (*interface{}, bool)`

GetCpuOk returns a tuple with the Cpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpu

`func (o *SysInfoSchema) SetCpu(v interface{})`

SetCpu sets Cpu field to given value.

### HasCpu

`func (o *SysInfoSchema) HasCpu() bool`

HasCpu returns a boolean if a field has been set.

### SetCpuNil

`func (o *SysInfoSchema) SetCpuNil(b bool)`

 SetCpuNil sets the value for Cpu to be an explicit nil

### UnsetCpu
`func (o *SysInfoSchema) UnsetCpu()`

UnsetCpu ensures that no value is present for Cpu, not even an explicit nil
### GetCpuAvail

`func (o *SysInfoSchema) GetCpuAvail() interface{}`

GetCpuAvail returns the CpuAvail field if non-nil, zero value otherwise.

### GetCpuAvailOk

`func (o *SysInfoSchema) GetCpuAvailOk() (*interface{}, bool)`

GetCpuAvailOk returns a tuple with the CpuAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuAvail

`func (o *SysInfoSchema) SetCpuAvail(v interface{})`

SetCpuAvail sets CpuAvail field to given value.

### HasCpuAvail

`func (o *SysInfoSchema) HasCpuAvail() bool`

HasCpuAvail returns a boolean if a field has been set.

### SetCpuAvailNil

`func (o *SysInfoSchema) SetCpuAvailNil(b bool)`

 SetCpuAvailNil sets the value for CpuAvail to be an explicit nil

### UnsetCpuAvail
`func (o *SysInfoSchema) UnsetCpuAvail()`

UnsetCpuAvail ensures that no value is present for CpuAvail, not even an explicit nil
### GetSlot

`func (o *SysInfoSchema) GetSlot() float32`

GetSlot returns the Slot field if non-nil, zero value otherwise.

### GetSlotOk

`func (o *SysInfoSchema) GetSlotOk() (*float32, bool)`

GetSlotOk returns a tuple with the Slot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlot

`func (o *SysInfoSchema) SetSlot(v float32)`

SetSlot sets Slot field to given value.

### HasSlot

`func (o *SysInfoSchema) HasSlot() bool`

HasSlot returns a boolean if a field has been set.

### GetSlotAvail

`func (o *SysInfoSchema) GetSlotAvail() float32`

GetSlotAvail returns the SlotAvail field if non-nil, zero value otherwise.

### GetSlotAvailOk

`func (o *SysInfoSchema) GetSlotAvailOk() (*float32, bool)`

GetSlotAvailOk returns a tuple with the SlotAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlotAvail

`func (o *SysInfoSchema) SetSlotAvail(v float32)`

SetSlotAvail sets SlotAvail field to given value.

### HasSlotAvail

`func (o *SysInfoSchema) HasSlotAvail() bool`

HasSlotAvail returns a boolean if a field has been set.

### GetRam

`func (o *SysInfoSchema) GetRam() float32`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *SysInfoSchema) GetRamOk() (*float32, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *SysInfoSchema) SetRam(v float32)`

SetRam sets Ram field to given value.

### HasRam

`func (o *SysInfoSchema) HasRam() bool`

HasRam returns a boolean if a field has been set.

### GetRamAvail

`func (o *SysInfoSchema) GetRamAvail() float32`

GetRamAvail returns the RamAvail field if non-nil, zero value otherwise.

### GetRamAvailOk

`func (o *SysInfoSchema) GetRamAvailOk() (*float32, bool)`

GetRamAvailOk returns a tuple with the RamAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamAvail

`func (o *SysInfoSchema) SetRamAvail(v float32)`

SetRamAvail sets RamAvail field to given value.

### HasRamAvail

`func (o *SysInfoSchema) HasRamAvail() bool`

HasRamAvail returns a boolean if a field has been set.

### GetVpn

`func (o *SysInfoSchema) GetVpn() float32`

GetVpn returns the Vpn field if non-nil, zero value otherwise.

### GetVpnOk

`func (o *SysInfoSchema) GetVpnOk() (*float32, bool)`

GetVpnOk returns a tuple with the Vpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpn

`func (o *SysInfoSchema) SetVpn(v float32)`

SetVpn sets Vpn field to given value.

### HasVpn

`func (o *SysInfoSchema) HasVpn() bool`

HasVpn returns a boolean if a field has been set.

### GetVpnAvail

`func (o *SysInfoSchema) GetVpnAvail() float32`

GetVpnAvail returns the VpnAvail field if non-nil, zero value otherwise.

### GetVpnAvailOk

`func (o *SysInfoSchema) GetVpnAvailOk() (*float32, bool)`

GetVpnAvailOk returns a tuple with the VpnAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpnAvail

`func (o *SysInfoSchema) SetVpnAvail(v float32)`

SetVpnAvail sets VpnAvail field to given value.

### HasVpnAvail

`func (o *SysInfoSchema) HasVpnAvail() bool`

HasVpnAvail returns a boolean if a field has been set.

### GetGpu

`func (o *SysInfoSchema) GetGpu() float32`

GetGpu returns the Gpu field if non-nil, zero value otherwise.

### GetGpuOk

`func (o *SysInfoSchema) GetGpuOk() (*float32, bool)`

GetGpuOk returns a tuple with the Gpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpu

`func (o *SysInfoSchema) SetGpu(v float32)`

SetGpu sets Gpu field to given value.

### HasGpu

`func (o *SysInfoSchema) HasGpu() bool`

HasGpu returns a boolean if a field has been set.

### GetGpuAvail

`func (o *SysInfoSchema) GetGpuAvail() float32`

GetGpuAvail returns the GpuAvail field if non-nil, zero value otherwise.

### GetGpuAvailOk

`func (o *SysInfoSchema) GetGpuAvailOk() (*float32, bool)`

GetGpuAvailOk returns a tuple with the GpuAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGpuAvail

`func (o *SysInfoSchema) SetGpuAvail(v float32)`

SetGpuAvail sets GpuAvail field to given value.

### HasGpuAvail

`func (o *SysInfoSchema) HasGpuAvail() bool`

HasGpuAvail returns a boolean if a field has been set.

### GetRamCpu

`func (o *SysInfoSchema) GetRamCpu() string`

GetRamCpu returns the RamCpu field if non-nil, zero value otherwise.

### GetRamCpuOk

`func (o *SysInfoSchema) GetRamCpuOk() (*string, bool)`

GetRamCpuOk returns a tuple with the RamCpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamCpu

`func (o *SysInfoSchema) SetRamCpu(v string)`

SetRamCpu sets RamCpu field to given value.

### HasRamCpu

`func (o *SysInfoSchema) HasRamCpu() bool`

HasRamCpu returns a boolean if a field has been set.

### GetEl032

`func (o *SysInfoSchema) GetEl032() string`

GetEl032 returns the El032 field if non-nil, zero value otherwise.

### GetEl032Ok

`func (o *SysInfoSchema) GetEl032Ok() (*string, bool)`

GetEl032Ok returns a tuple with the El032 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEl032

`func (o *SysInfoSchema) SetEl032(v string)`

SetEl032 sets El032 field to given value.

### HasEl032

`func (o *SysInfoSchema) HasEl032() bool`

HasEl032 returns a boolean if a field has been set.

### GetEl132

`func (o *SysInfoSchema) GetEl132() string`

GetEl132 returns the El132 field if non-nil, zero value otherwise.

### GetEl132Ok

`func (o *SysInfoSchema) GetEl132Ok() (*string, bool)`

GetEl132Ok returns a tuple with the El132 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEl132

`func (o *SysInfoSchema) SetEl132(v string)`

SetEl132 sets El132 field to given value.

### HasEl132

`func (o *SysInfoSchema) HasEl132() bool`

HasEl132 returns a boolean if a field has been set.

### GetMmuTg16k

`func (o *SysInfoSchema) GetMmuTg16k() string`

GetMmuTg16k returns the MmuTg16k field if non-nil, zero value otherwise.

### GetMmuTg16kOk

`func (o *SysInfoSchema) GetMmuTg16kOk() (*string, bool)`

GetMmuTg16kOk returns a tuple with the MmuTg16k field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMmuTg16k

`func (o *SysInfoSchema) SetMmuTg16k(v string)`

SetMmuTg16k sets MmuTg16k field to given value.

### HasMmuTg16k

`func (o *SysInfoSchema) HasMmuTg16k() bool`

HasMmuTg16k returns a boolean if a field has been set.

### GetHwPac

`func (o *SysInfoSchema) GetHwPac() float32`

GetHwPac returns the HwPac field if non-nil, zero value otherwise.

### GetHwPacOk

`func (o *SysInfoSchema) GetHwPacOk() (*float32, bool)`

GetHwPacOk returns a tuple with the HwPac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHwPac

`func (o *SysInfoSchema) SetHwPac(v float32)`

SetHwPac sets HwPac field to given value.

### HasHwPac

`func (o *SysInfoSchema) HasHwPac() bool`

HasHwPac returns a boolean if a field has been set.

### GetArmTrace

`func (o *SysInfoSchema) GetArmTrace() string`

GetArmTrace returns the ArmTrace field if non-nil, zero value otherwise.

### GetArmTraceOk

`func (o *SysInfoSchema) GetArmTraceOk() (*string, bool)`

GetArmTraceOk returns a tuple with the ArmTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArmTrace

`func (o *SysInfoSchema) SetArmTrace(v string)`

SetArmTrace sets ArmTrace field to given value.

### HasArmTrace

`func (o *SysInfoSchema) HasArmTrace() bool`

HasArmTrace returns a boolean if a field has been set.

### GetCores

`func (o *SysInfoSchema) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *SysInfoSchema) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *SysInfoSchema) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *SysInfoSchema) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetCoresAvail

`func (o *SysInfoSchema) GetCoresAvail() float32`

GetCoresAvail returns the CoresAvail field if non-nil, zero value otherwise.

### GetCoresAvailOk

`func (o *SysInfoSchema) GetCoresAvailOk() (*float32, bool)`

GetCoresAvailOk returns a tuple with the CoresAvail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoresAvail

`func (o *SysInfoSchema) SetCoresAvail(v float32)`

SetCoresAvail sets CoresAvail field to given value.

### HasCoresAvail

`func (o *SysInfoSchema) HasCoresAvail() bool`

HasCoresAvail returns a boolean if a field has been set.

### GetRamCore

`func (o *SysInfoSchema) GetRamCore() float32`

GetRamCore returns the RamCore field if non-nil, zero value otherwise.

### GetRamCoreOk

`func (o *SysInfoSchema) GetRamCoreOk() (*float32, bool)`

GetRamCoreOk returns a tuple with the RamCore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRamCore

`func (o *SysInfoSchema) SetRamCore(v float32)`

SetRamCore sets RamCore field to given value.

### HasRamCore

`func (o *SysInfoSchema) HasRamCore() bool`

HasRamCore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


