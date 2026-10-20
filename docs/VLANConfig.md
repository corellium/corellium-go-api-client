# VLANConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PhysicalInterface** | **string** | Physical network interface to create VLAN on | 
**VlanId** | **float32** | VLAN ID (1-4094) | 
**DhcpMode** | **string** | DHCP server mode | 
**Gateway** | Pointer to **string** | Gateway IP address | [optional] 
**Network** | Pointer to **string** | Network address | [optional] 
**DnsServers** | Pointer to **[]string** | List of DNS servers | [optional] 

## Methods

### NewVLANConfig

`func NewVLANConfig(physicalInterface string, vlanId float32, dhcpMode string, ) *VLANConfig`

NewVLANConfig instantiates a new VLANConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVLANConfigWithDefaults

`func NewVLANConfigWithDefaults() *VLANConfig`

NewVLANConfigWithDefaults instantiates a new VLANConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhysicalInterface

`func (o *VLANConfig) GetPhysicalInterface() string`

GetPhysicalInterface returns the PhysicalInterface field if non-nil, zero value otherwise.

### GetPhysicalInterfaceOk

`func (o *VLANConfig) GetPhysicalInterfaceOk() (*string, bool)`

GetPhysicalInterfaceOk returns a tuple with the PhysicalInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterface

`func (o *VLANConfig) SetPhysicalInterface(v string)`

SetPhysicalInterface sets PhysicalInterface field to given value.


### GetVlanId

`func (o *VLANConfig) GetVlanId() float32`

GetVlanId returns the VlanId field if non-nil, zero value otherwise.

### GetVlanIdOk

`func (o *VLANConfig) GetVlanIdOk() (*float32, bool)`

GetVlanIdOk returns a tuple with the VlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanId

`func (o *VLANConfig) SetVlanId(v float32)`

SetVlanId sets VlanId field to given value.


### GetDhcpMode

`func (o *VLANConfig) GetDhcpMode() string`

GetDhcpMode returns the DhcpMode field if non-nil, zero value otherwise.

### GetDhcpModeOk

`func (o *VLANConfig) GetDhcpModeOk() (*string, bool)`

GetDhcpModeOk returns a tuple with the DhcpMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpMode

`func (o *VLANConfig) SetDhcpMode(v string)`

SetDhcpMode sets DhcpMode field to given value.


### GetGateway

`func (o *VLANConfig) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *VLANConfig) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *VLANConfig) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *VLANConfig) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetNetwork

`func (o *VLANConfig) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *VLANConfig) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *VLANConfig) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *VLANConfig) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetDnsServers

`func (o *VLANConfig) GetDnsServers() []string`

GetDnsServers returns the DnsServers field if non-nil, zero value otherwise.

### GetDnsServersOk

`func (o *VLANConfig) GetDnsServersOk() (*[]string, bool)`

GetDnsServersOk returns a tuple with the DnsServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsServers

`func (o *VLANConfig) SetDnsServers(v []string)`

SetDnsServers sets DnsServers field to given value.

### HasDnsServers

`func (o *VLANConfig) HasDnsServers() bool`

HasDnsServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


