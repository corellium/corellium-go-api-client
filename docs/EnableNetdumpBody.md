# EnableNetdumpBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PortRanges** | Pointer to **[]string** | Optional. Capture only traffic on ports in these ranges, each written &#x60;low-high&#x60;. | [optional] 
**SrcPorts** | Pointer to **[]string** | Source ports to capture. | [optional] 
**DstPorts** | Pointer to **[]string** | Destination ports to capture. | [optional] 
**Ports** | Pointer to **[]string** | Ports to capture. | [optional] 
**Protocols** | Pointer to **[]string** | Protocols to capture. | [optional] 
**Processes** | Pointer to **[]string** | Optional. Capture only traffic sent or received by processes with these names. | [optional] 
**Hosts** | Pointer to **[]string** | Host IP addresses to capture. | [optional] 

## Methods

### NewEnableNetdumpBody

`func NewEnableNetdumpBody() *EnableNetdumpBody`

NewEnableNetdumpBody instantiates a new EnableNetdumpBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnableNetdumpBodyWithDefaults

`func NewEnableNetdumpBodyWithDefaults() *EnableNetdumpBody`

NewEnableNetdumpBodyWithDefaults instantiates a new EnableNetdumpBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPortRanges

`func (o *EnableNetdumpBody) GetPortRanges() []string`

GetPortRanges returns the PortRanges field if non-nil, zero value otherwise.

### GetPortRangesOk

`func (o *EnableNetdumpBody) GetPortRangesOk() (*[]string, bool)`

GetPortRangesOk returns a tuple with the PortRanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortRanges

`func (o *EnableNetdumpBody) SetPortRanges(v []string)`

SetPortRanges sets PortRanges field to given value.

### HasPortRanges

`func (o *EnableNetdumpBody) HasPortRanges() bool`

HasPortRanges returns a boolean if a field has been set.

### GetSrcPorts

`func (o *EnableNetdumpBody) GetSrcPorts() []string`

GetSrcPorts returns the SrcPorts field if non-nil, zero value otherwise.

### GetSrcPortsOk

`func (o *EnableNetdumpBody) GetSrcPortsOk() (*[]string, bool)`

GetSrcPortsOk returns a tuple with the SrcPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSrcPorts

`func (o *EnableNetdumpBody) SetSrcPorts(v []string)`

SetSrcPorts sets SrcPorts field to given value.

### HasSrcPorts

`func (o *EnableNetdumpBody) HasSrcPorts() bool`

HasSrcPorts returns a boolean if a field has been set.

### GetDstPorts

`func (o *EnableNetdumpBody) GetDstPorts() []string`

GetDstPorts returns the DstPorts field if non-nil, zero value otherwise.

### GetDstPortsOk

`func (o *EnableNetdumpBody) GetDstPortsOk() (*[]string, bool)`

GetDstPortsOk returns a tuple with the DstPorts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDstPorts

`func (o *EnableNetdumpBody) SetDstPorts(v []string)`

SetDstPorts sets DstPorts field to given value.

### HasDstPorts

`func (o *EnableNetdumpBody) HasDstPorts() bool`

HasDstPorts returns a boolean if a field has been set.

### GetPorts

`func (o *EnableNetdumpBody) GetPorts() []string`

GetPorts returns the Ports field if non-nil, zero value otherwise.

### GetPortsOk

`func (o *EnableNetdumpBody) GetPortsOk() (*[]string, bool)`

GetPortsOk returns a tuple with the Ports field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorts

`func (o *EnableNetdumpBody) SetPorts(v []string)`

SetPorts sets Ports field to given value.

### HasPorts

`func (o *EnableNetdumpBody) HasPorts() bool`

HasPorts returns a boolean if a field has been set.

### GetProtocols

`func (o *EnableNetdumpBody) GetProtocols() []string`

GetProtocols returns the Protocols field if non-nil, zero value otherwise.

### GetProtocolsOk

`func (o *EnableNetdumpBody) GetProtocolsOk() (*[]string, bool)`

GetProtocolsOk returns a tuple with the Protocols field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocols

`func (o *EnableNetdumpBody) SetProtocols(v []string)`

SetProtocols sets Protocols field to given value.

### HasProtocols

`func (o *EnableNetdumpBody) HasProtocols() bool`

HasProtocols returns a boolean if a field has been set.

### GetProcesses

`func (o *EnableNetdumpBody) GetProcesses() []string`

GetProcesses returns the Processes field if non-nil, zero value otherwise.

### GetProcessesOk

`func (o *EnableNetdumpBody) GetProcessesOk() (*[]string, bool)`

GetProcessesOk returns a tuple with the Processes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcesses

`func (o *EnableNetdumpBody) SetProcesses(v []string)`

SetProcesses sets Processes field to given value.

### HasProcesses

`func (o *EnableNetdumpBody) HasProcesses() bool`

HasProcesses returns a boolean if a field has been set.

### GetHosts

`func (o *EnableNetdumpBody) GetHosts() []string`

GetHosts returns the Hosts field if non-nil, zero value otherwise.

### GetHostsOk

`func (o *EnableNetdumpBody) GetHostsOk() (*[]string, bool)`

GetHostsOk returns a tuple with the Hosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHosts

`func (o *EnableNetdumpBody) SetHosts(v []string)`

SetHosts sets Hosts field to given value.

### HasHosts

`func (o *EnableNetdumpBody) HasHosts() bool`

HasHosts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


