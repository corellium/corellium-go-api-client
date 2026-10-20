# InstanceBootOptionsFvp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ModelBinary** | Pointer to **string** | FVP model binary path. Populated by the server from the flavor; clients should not set this. | [optional] 
**Parameters** | Pointer to **map[string]string** | Key/value map of FVP model parameters. | [optional] 
**Data** | Pointer to **[]string** | Raw data to load at specified addresses (format: \&quot;file@address\&quot;). | [optional] 
**Breaks** | Pointer to **[]string** | Breakpoint addresses to set. | [optional] 
**Dumps** | Pointer to **[]string** | Memory regions to dump (format: \&quot;file@address,size\&quot;). | [optional] 
**CadiLog** | Pointer to **string** | Log all CADI calls into an XML log file. | [optional] 
**CadiServer** | Pointer to **string** | Start CADI server. | [optional] 
**IrisServer** | Pointer to **string** | Start Iris server. | [optional] 
**IrisLog** | Pointer to **string** | Iris log level. | [optional] 
**IrisAllowRemote** | Pointer to **string** | Allow remote connections to the Iris server. | [optional] 
**IrisPortRange** | Pointer to **string** | Port range to scan when starting the Iris server (format: \&quot;min:max\&quot;). | [optional] 
**IrisPort** | Pointer to **string** | Specific port for the Iris server. | [optional] 
**Run** | Pointer to **string** | Run the simulation immediately when a debug server is started. | [optional] 
**Stat** | Pointer to **string** | Print run statistics on simulation exit. | [optional] 
**Quiet** | Pointer to **string** | Suppress informational output. | [optional] 
**Start** | Pointer to **string** | Set initial PC to application start address. | [optional] 
**Plugin** | Pointer to **string** | Load plugin. | [optional] 
**FastRam** | Pointer to **string** | Enable FastRAM and load its configuration from file. | [optional] 
**Save** | Pointer to **string** | Save checkpoint to directory on simulation exit. | [optional] 
**Restore** | Pointer to **string** | Restore checkpoint from directory on simulation startup. | [optional] 
**CpiFile** | Pointer to **string** | File to set Cycle Per Instruction class. | [optional] 
**CycleLimit** | Pointer to **string** | Number of cycles to run. | [optional] 
**CpuLimit** | Pointer to **string** | Number of host active CPU seconds to run. | [optional] 
**TimeLimit** | Pointer to **string** | Number of wall-clock seconds to run. | [optional] 
**SimLimit** | Pointer to **string** | Number of seconds to simulate. | [optional] 

## Methods

### NewInstanceBootOptionsFvp

`func NewInstanceBootOptionsFvp() *InstanceBootOptionsFvp`

NewInstanceBootOptionsFvp instantiates a new InstanceBootOptionsFvp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceBootOptionsFvpWithDefaults

`func NewInstanceBootOptionsFvpWithDefaults() *InstanceBootOptionsFvp`

NewInstanceBootOptionsFvpWithDefaults instantiates a new InstanceBootOptionsFvp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModelBinary

`func (o *InstanceBootOptionsFvp) GetModelBinary() string`

GetModelBinary returns the ModelBinary field if non-nil, zero value otherwise.

### GetModelBinaryOk

`func (o *InstanceBootOptionsFvp) GetModelBinaryOk() (*string, bool)`

GetModelBinaryOk returns a tuple with the ModelBinary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelBinary

`func (o *InstanceBootOptionsFvp) SetModelBinary(v string)`

SetModelBinary sets ModelBinary field to given value.

### HasModelBinary

`func (o *InstanceBootOptionsFvp) HasModelBinary() bool`

HasModelBinary returns a boolean if a field has been set.

### GetParameters

`func (o *InstanceBootOptionsFvp) GetParameters() map[string]string`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *InstanceBootOptionsFvp) GetParametersOk() (*map[string]string, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *InstanceBootOptionsFvp) SetParameters(v map[string]string)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *InstanceBootOptionsFvp) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### GetData

`func (o *InstanceBootOptionsFvp) GetData() []string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *InstanceBootOptionsFvp) GetDataOk() (*[]string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *InstanceBootOptionsFvp) SetData(v []string)`

SetData sets Data field to given value.

### HasData

`func (o *InstanceBootOptionsFvp) HasData() bool`

HasData returns a boolean if a field has been set.

### GetBreaks

`func (o *InstanceBootOptionsFvp) GetBreaks() []string`

GetBreaks returns the Breaks field if non-nil, zero value otherwise.

### GetBreaksOk

`func (o *InstanceBootOptionsFvp) GetBreaksOk() (*[]string, bool)`

GetBreaksOk returns a tuple with the Breaks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreaks

`func (o *InstanceBootOptionsFvp) SetBreaks(v []string)`

SetBreaks sets Breaks field to given value.

### HasBreaks

`func (o *InstanceBootOptionsFvp) HasBreaks() bool`

HasBreaks returns a boolean if a field has been set.

### GetDumps

`func (o *InstanceBootOptionsFvp) GetDumps() []string`

GetDumps returns the Dumps field if non-nil, zero value otherwise.

### GetDumpsOk

`func (o *InstanceBootOptionsFvp) GetDumpsOk() (*[]string, bool)`

GetDumpsOk returns a tuple with the Dumps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDumps

`func (o *InstanceBootOptionsFvp) SetDumps(v []string)`

SetDumps sets Dumps field to given value.

### HasDumps

`func (o *InstanceBootOptionsFvp) HasDumps() bool`

HasDumps returns a boolean if a field has been set.

### GetCadiLog

`func (o *InstanceBootOptionsFvp) GetCadiLog() string`

GetCadiLog returns the CadiLog field if non-nil, zero value otherwise.

### GetCadiLogOk

`func (o *InstanceBootOptionsFvp) GetCadiLogOk() (*string, bool)`

GetCadiLogOk returns a tuple with the CadiLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadiLog

`func (o *InstanceBootOptionsFvp) SetCadiLog(v string)`

SetCadiLog sets CadiLog field to given value.

### HasCadiLog

`func (o *InstanceBootOptionsFvp) HasCadiLog() bool`

HasCadiLog returns a boolean if a field has been set.

### GetCadiServer

`func (o *InstanceBootOptionsFvp) GetCadiServer() string`

GetCadiServer returns the CadiServer field if non-nil, zero value otherwise.

### GetCadiServerOk

`func (o *InstanceBootOptionsFvp) GetCadiServerOk() (*string, bool)`

GetCadiServerOk returns a tuple with the CadiServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCadiServer

`func (o *InstanceBootOptionsFvp) SetCadiServer(v string)`

SetCadiServer sets CadiServer field to given value.

### HasCadiServer

`func (o *InstanceBootOptionsFvp) HasCadiServer() bool`

HasCadiServer returns a boolean if a field has been set.

### GetIrisServer

`func (o *InstanceBootOptionsFvp) GetIrisServer() string`

GetIrisServer returns the IrisServer field if non-nil, zero value otherwise.

### GetIrisServerOk

`func (o *InstanceBootOptionsFvp) GetIrisServerOk() (*string, bool)`

GetIrisServerOk returns a tuple with the IrisServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrisServer

`func (o *InstanceBootOptionsFvp) SetIrisServer(v string)`

SetIrisServer sets IrisServer field to given value.

### HasIrisServer

`func (o *InstanceBootOptionsFvp) HasIrisServer() bool`

HasIrisServer returns a boolean if a field has been set.

### GetIrisLog

`func (o *InstanceBootOptionsFvp) GetIrisLog() string`

GetIrisLog returns the IrisLog field if non-nil, zero value otherwise.

### GetIrisLogOk

`func (o *InstanceBootOptionsFvp) GetIrisLogOk() (*string, bool)`

GetIrisLogOk returns a tuple with the IrisLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrisLog

`func (o *InstanceBootOptionsFvp) SetIrisLog(v string)`

SetIrisLog sets IrisLog field to given value.

### HasIrisLog

`func (o *InstanceBootOptionsFvp) HasIrisLog() bool`

HasIrisLog returns a boolean if a field has been set.

### GetIrisAllowRemote

`func (o *InstanceBootOptionsFvp) GetIrisAllowRemote() string`

GetIrisAllowRemote returns the IrisAllowRemote field if non-nil, zero value otherwise.

### GetIrisAllowRemoteOk

`func (o *InstanceBootOptionsFvp) GetIrisAllowRemoteOk() (*string, bool)`

GetIrisAllowRemoteOk returns a tuple with the IrisAllowRemote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrisAllowRemote

`func (o *InstanceBootOptionsFvp) SetIrisAllowRemote(v string)`

SetIrisAllowRemote sets IrisAllowRemote field to given value.

### HasIrisAllowRemote

`func (o *InstanceBootOptionsFvp) HasIrisAllowRemote() bool`

HasIrisAllowRemote returns a boolean if a field has been set.

### GetIrisPortRange

`func (o *InstanceBootOptionsFvp) GetIrisPortRange() string`

GetIrisPortRange returns the IrisPortRange field if non-nil, zero value otherwise.

### GetIrisPortRangeOk

`func (o *InstanceBootOptionsFvp) GetIrisPortRangeOk() (*string, bool)`

GetIrisPortRangeOk returns a tuple with the IrisPortRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrisPortRange

`func (o *InstanceBootOptionsFvp) SetIrisPortRange(v string)`

SetIrisPortRange sets IrisPortRange field to given value.

### HasIrisPortRange

`func (o *InstanceBootOptionsFvp) HasIrisPortRange() bool`

HasIrisPortRange returns a boolean if a field has been set.

### GetIrisPort

`func (o *InstanceBootOptionsFvp) GetIrisPort() string`

GetIrisPort returns the IrisPort field if non-nil, zero value otherwise.

### GetIrisPortOk

`func (o *InstanceBootOptionsFvp) GetIrisPortOk() (*string, bool)`

GetIrisPortOk returns a tuple with the IrisPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIrisPort

`func (o *InstanceBootOptionsFvp) SetIrisPort(v string)`

SetIrisPort sets IrisPort field to given value.

### HasIrisPort

`func (o *InstanceBootOptionsFvp) HasIrisPort() bool`

HasIrisPort returns a boolean if a field has been set.

### GetRun

`func (o *InstanceBootOptionsFvp) GetRun() string`

GetRun returns the Run field if non-nil, zero value otherwise.

### GetRunOk

`func (o *InstanceBootOptionsFvp) GetRunOk() (*string, bool)`

GetRunOk returns a tuple with the Run field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRun

`func (o *InstanceBootOptionsFvp) SetRun(v string)`

SetRun sets Run field to given value.

### HasRun

`func (o *InstanceBootOptionsFvp) HasRun() bool`

HasRun returns a boolean if a field has been set.

### GetStat

`func (o *InstanceBootOptionsFvp) GetStat() string`

GetStat returns the Stat field if non-nil, zero value otherwise.

### GetStatOk

`func (o *InstanceBootOptionsFvp) GetStatOk() (*string, bool)`

GetStatOk returns a tuple with the Stat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStat

`func (o *InstanceBootOptionsFvp) SetStat(v string)`

SetStat sets Stat field to given value.

### HasStat

`func (o *InstanceBootOptionsFvp) HasStat() bool`

HasStat returns a boolean if a field has been set.

### GetQuiet

`func (o *InstanceBootOptionsFvp) GetQuiet() string`

GetQuiet returns the Quiet field if non-nil, zero value otherwise.

### GetQuietOk

`func (o *InstanceBootOptionsFvp) GetQuietOk() (*string, bool)`

GetQuietOk returns a tuple with the Quiet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuiet

`func (o *InstanceBootOptionsFvp) SetQuiet(v string)`

SetQuiet sets Quiet field to given value.

### HasQuiet

`func (o *InstanceBootOptionsFvp) HasQuiet() bool`

HasQuiet returns a boolean if a field has been set.

### GetStart

`func (o *InstanceBootOptionsFvp) GetStart() string`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *InstanceBootOptionsFvp) GetStartOk() (*string, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *InstanceBootOptionsFvp) SetStart(v string)`

SetStart sets Start field to given value.

### HasStart

`func (o *InstanceBootOptionsFvp) HasStart() bool`

HasStart returns a boolean if a field has been set.

### GetPlugin

`func (o *InstanceBootOptionsFvp) GetPlugin() string`

GetPlugin returns the Plugin field if non-nil, zero value otherwise.

### GetPluginOk

`func (o *InstanceBootOptionsFvp) GetPluginOk() (*string, bool)`

GetPluginOk returns a tuple with the Plugin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlugin

`func (o *InstanceBootOptionsFvp) SetPlugin(v string)`

SetPlugin sets Plugin field to given value.

### HasPlugin

`func (o *InstanceBootOptionsFvp) HasPlugin() bool`

HasPlugin returns a boolean if a field has been set.

### GetFastRam

`func (o *InstanceBootOptionsFvp) GetFastRam() string`

GetFastRam returns the FastRam field if non-nil, zero value otherwise.

### GetFastRamOk

`func (o *InstanceBootOptionsFvp) GetFastRamOk() (*string, bool)`

GetFastRamOk returns a tuple with the FastRam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFastRam

`func (o *InstanceBootOptionsFvp) SetFastRam(v string)`

SetFastRam sets FastRam field to given value.

### HasFastRam

`func (o *InstanceBootOptionsFvp) HasFastRam() bool`

HasFastRam returns a boolean if a field has been set.

### GetSave

`func (o *InstanceBootOptionsFvp) GetSave() string`

GetSave returns the Save field if non-nil, zero value otherwise.

### GetSaveOk

`func (o *InstanceBootOptionsFvp) GetSaveOk() (*string, bool)`

GetSaveOk returns a tuple with the Save field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSave

`func (o *InstanceBootOptionsFvp) SetSave(v string)`

SetSave sets Save field to given value.

### HasSave

`func (o *InstanceBootOptionsFvp) HasSave() bool`

HasSave returns a boolean if a field has been set.

### GetRestore

`func (o *InstanceBootOptionsFvp) GetRestore() string`

GetRestore returns the Restore field if non-nil, zero value otherwise.

### GetRestoreOk

`func (o *InstanceBootOptionsFvp) GetRestoreOk() (*string, bool)`

GetRestoreOk returns a tuple with the Restore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestore

`func (o *InstanceBootOptionsFvp) SetRestore(v string)`

SetRestore sets Restore field to given value.

### HasRestore

`func (o *InstanceBootOptionsFvp) HasRestore() bool`

HasRestore returns a boolean if a field has been set.

### GetCpiFile

`func (o *InstanceBootOptionsFvp) GetCpiFile() string`

GetCpiFile returns the CpiFile field if non-nil, zero value otherwise.

### GetCpiFileOk

`func (o *InstanceBootOptionsFvp) GetCpiFileOk() (*string, bool)`

GetCpiFileOk returns a tuple with the CpiFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpiFile

`func (o *InstanceBootOptionsFvp) SetCpiFile(v string)`

SetCpiFile sets CpiFile field to given value.

### HasCpiFile

`func (o *InstanceBootOptionsFvp) HasCpiFile() bool`

HasCpiFile returns a boolean if a field has been set.

### GetCycleLimit

`func (o *InstanceBootOptionsFvp) GetCycleLimit() string`

GetCycleLimit returns the CycleLimit field if non-nil, zero value otherwise.

### GetCycleLimitOk

`func (o *InstanceBootOptionsFvp) GetCycleLimitOk() (*string, bool)`

GetCycleLimitOk returns a tuple with the CycleLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleLimit

`func (o *InstanceBootOptionsFvp) SetCycleLimit(v string)`

SetCycleLimit sets CycleLimit field to given value.

### HasCycleLimit

`func (o *InstanceBootOptionsFvp) HasCycleLimit() bool`

HasCycleLimit returns a boolean if a field has been set.

### GetCpuLimit

`func (o *InstanceBootOptionsFvp) GetCpuLimit() string`

GetCpuLimit returns the CpuLimit field if non-nil, zero value otherwise.

### GetCpuLimitOk

`func (o *InstanceBootOptionsFvp) GetCpuLimitOk() (*string, bool)`

GetCpuLimitOk returns a tuple with the CpuLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpuLimit

`func (o *InstanceBootOptionsFvp) SetCpuLimit(v string)`

SetCpuLimit sets CpuLimit field to given value.

### HasCpuLimit

`func (o *InstanceBootOptionsFvp) HasCpuLimit() bool`

HasCpuLimit returns a boolean if a field has been set.

### GetTimeLimit

`func (o *InstanceBootOptionsFvp) GetTimeLimit() string`

GetTimeLimit returns the TimeLimit field if non-nil, zero value otherwise.

### GetTimeLimitOk

`func (o *InstanceBootOptionsFvp) GetTimeLimitOk() (*string, bool)`

GetTimeLimitOk returns a tuple with the TimeLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeLimit

`func (o *InstanceBootOptionsFvp) SetTimeLimit(v string)`

SetTimeLimit sets TimeLimit field to given value.

### HasTimeLimit

`func (o *InstanceBootOptionsFvp) HasTimeLimit() bool`

HasTimeLimit returns a boolean if a field has been set.

### GetSimLimit

`func (o *InstanceBootOptionsFvp) GetSimLimit() string`

GetSimLimit returns the SimLimit field if non-nil, zero value otherwise.

### GetSimLimitOk

`func (o *InstanceBootOptionsFvp) GetSimLimitOk() (*string, bool)`

GetSimLimitOk returns a tuple with the SimLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSimLimit

`func (o *InstanceBootOptionsFvp) SetSimLimit(v string)`

SetSimLimit sets SimLimit field to given value.

### HasSimLimit

`func (o *InstanceBootOptionsFvp) HasSimLimit() bool`

HasSimLimit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


