# VLANConfigV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PhysicalInterface** | **string** | Physical network interface to create VLAN on. | 
**VlanId** | **float32** | VLAN ID (1-4094). | 
**DhcpMode** | **string** | DHCP server mode. | 
**Gateway** | Pointer to **string** | Gateway IP address. | [optional] 
**Network** | Pointer to **string** | Network address. | [optional] 
**DnsServers** | Pointer to **[]string** | List of DNS servers. | [optional] 

## Methods

### NewVLANConfigV1

`func NewVLANConfigV1(physicalInterface string, vlanId float32, dhcpMode string, ) *VLANConfigV1`

NewVLANConfigV1 instantiates a new VLANConfigV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVLANConfigV1WithDefaults

`func NewVLANConfigV1WithDefaults() *VLANConfigV1`

NewVLANConfigV1WithDefaults instantiates a new VLANConfigV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhysicalInterface

`func (o *VLANConfigV1) GetPhysicalInterface() string`

GetPhysicalInterface returns the PhysicalInterface field if non-nil, zero value otherwise.

### GetPhysicalInterfaceOk

`func (o *VLANConfigV1) GetPhysicalInterfaceOk() (*string, bool)`

GetPhysicalInterfaceOk returns a tuple with the PhysicalInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterface

`func (o *VLANConfigV1) SetPhysicalInterface(v string)`

SetPhysicalInterface sets PhysicalInterface field to given value.


### GetVlanId

`func (o *VLANConfigV1) GetVlanId() float32`

GetVlanId returns the VlanId field if non-nil, zero value otherwise.

### GetVlanIdOk

`func (o *VLANConfigV1) GetVlanIdOk() (*float32, bool)`

GetVlanIdOk returns a tuple with the VlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanId

`func (o *VLANConfigV1) SetVlanId(v float32)`

SetVlanId sets VlanId field to given value.


### GetDhcpMode

`func (o *VLANConfigV1) GetDhcpMode() string`

GetDhcpMode returns the DhcpMode field if non-nil, zero value otherwise.

### GetDhcpModeOk

`func (o *VLANConfigV1) GetDhcpModeOk() (*string, bool)`

GetDhcpModeOk returns a tuple with the DhcpMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpMode

`func (o *VLANConfigV1) SetDhcpMode(v string)`

SetDhcpMode sets DhcpMode field to given value.


### GetGateway

`func (o *VLANConfigV1) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *VLANConfigV1) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *VLANConfigV1) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *VLANConfigV1) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetNetwork

`func (o *VLANConfigV1) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *VLANConfigV1) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *VLANConfigV1) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *VLANConfigV1) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetDnsServers

`func (o *VLANConfigV1) GetDnsServers() []string`

GetDnsServers returns the DnsServers field if non-nil, zero value otherwise.

### GetDnsServersOk

`func (o *VLANConfigV1) GetDnsServersOk() (*[]string, bool)`

GetDnsServersOk returns a tuple with the DnsServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsServers

`func (o *VLANConfigV1) SetDnsServers(v []string)`

SetDnsServers sets DnsServers field to given value.

### HasDnsServers

`func (o *VLANConfigV1) HasDnsServers() bool`

HasDnsServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


