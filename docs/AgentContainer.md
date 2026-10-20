# AgentContainer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Autostart** | **string** | Whether the container starts automatically. | 
**Groups** | **string** | Container groups. | 
**Ipv4** | **string** | IPv4 address. | 
**Ipv6** | **string** | IPv6 address. | 
**Name** | **string** | Container name. | 
**Pid** | **string** | Process ID of the container. | 
**Ram** | **string** | RAM usage. | 
**State** | **string** | Container state (e.g. RUNNING, STOPPED). | 
**Swap** | **string** | Swap usage. | 
**Unprivileged** | **string** | Whether the container is unprivileged. | 

## Methods

### NewAgentContainer

`func NewAgentContainer(autostart string, groups string, ipv4 string, ipv6 string, name string, pid string, ram string, state string, swap string, unprivileged string, ) *AgentContainer`

NewAgentContainer instantiates a new AgentContainer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentContainerWithDefaults

`func NewAgentContainerWithDefaults() *AgentContainer`

NewAgentContainerWithDefaults instantiates a new AgentContainer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAutostart

`func (o *AgentContainer) GetAutostart() string`

GetAutostart returns the Autostart field if non-nil, zero value otherwise.

### GetAutostartOk

`func (o *AgentContainer) GetAutostartOk() (*string, bool)`

GetAutostartOk returns a tuple with the Autostart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutostart

`func (o *AgentContainer) SetAutostart(v string)`

SetAutostart sets Autostart field to given value.


### GetGroups

`func (o *AgentContainer) GetGroups() string`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *AgentContainer) GetGroupsOk() (*string, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *AgentContainer) SetGroups(v string)`

SetGroups sets Groups field to given value.


### GetIpv4

`func (o *AgentContainer) GetIpv4() string`

GetIpv4 returns the Ipv4 field if non-nil, zero value otherwise.

### GetIpv4Ok

`func (o *AgentContainer) GetIpv4Ok() (*string, bool)`

GetIpv4Ok returns a tuple with the Ipv4 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv4

`func (o *AgentContainer) SetIpv4(v string)`

SetIpv4 sets Ipv4 field to given value.


### GetIpv6

`func (o *AgentContainer) GetIpv6() string`

GetIpv6 returns the Ipv6 field if non-nil, zero value otherwise.

### GetIpv6Ok

`func (o *AgentContainer) GetIpv6Ok() (*string, bool)`

GetIpv6Ok returns a tuple with the Ipv6 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpv6

`func (o *AgentContainer) SetIpv6(v string)`

SetIpv6 sets Ipv6 field to given value.


### GetName

`func (o *AgentContainer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AgentContainer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AgentContainer) SetName(v string)`

SetName sets Name field to given value.


### GetPid

`func (o *AgentContainer) GetPid() string`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *AgentContainer) GetPidOk() (*string, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *AgentContainer) SetPid(v string)`

SetPid sets Pid field to given value.


### GetRam

`func (o *AgentContainer) GetRam() string`

GetRam returns the Ram field if non-nil, zero value otherwise.

### GetRamOk

`func (o *AgentContainer) GetRamOk() (*string, bool)`

GetRamOk returns a tuple with the Ram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRam

`func (o *AgentContainer) SetRam(v string)`

SetRam sets Ram field to given value.


### GetState

`func (o *AgentContainer) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AgentContainer) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AgentContainer) SetState(v string)`

SetState sets State field to given value.


### GetSwap

`func (o *AgentContainer) GetSwap() string`

GetSwap returns the Swap field if non-nil, zero value otherwise.

### GetSwapOk

`func (o *AgentContainer) GetSwapOk() (*string, bool)`

GetSwapOk returns a tuple with the Swap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSwap

`func (o *AgentContainer) SetSwap(v string)`

SetSwap sets Swap field to given value.


### GetUnprivileged

`func (o *AgentContainer) GetUnprivileged() string`

GetUnprivileged returns the Unprivileged field if non-nil, zero value otherwise.

### GetUnprivilegedOk

`func (o *AgentContainer) GetUnprivilegedOk() (*string, bool)`

GetUnprivilegedOk returns a tuple with the Unprivileged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnprivileged

`func (o *AgentContainer) SetUnprivileged(v string)`

SetUnprivileged sets Unprivileged field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


