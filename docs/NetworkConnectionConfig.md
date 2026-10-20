# NetworkConnectionConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | Username for OpenVPN connection. | [optional] 
**Password** | Pointer to **string** | Password for OpenVPN connection. | [optional] 
**Config** | **string** | OpenVPN connection configuration. | 
**PhysicalInterface** | **string** | Physical network interface to create VLAN on | 
**VlanId** | **float32** | VLAN ID (1-4094) | 
**DhcpMode** | **string** | DHCP server mode | 
**Gateway** | Pointer to **string** | Gateway IP address | [optional] 
**Network** | Pointer to **string** | Network address | [optional] 
**DnsServers** | Pointer to **[]string** | List of DNS servers | [optional] 

## Methods

### NewNetworkConnectionConfig

`func NewNetworkConnectionConfig(config string, physicalInterface string, vlanId float32, dhcpMode string, ) *NetworkConnectionConfig`

NewNetworkConnectionConfig instantiates a new NetworkConnectionConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNetworkConnectionConfigWithDefaults

`func NewNetworkConnectionConfigWithDefaults() *NetworkConnectionConfig`

NewNetworkConnectionConfigWithDefaults instantiates a new NetworkConnectionConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *NetworkConnectionConfig) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *NetworkConnectionConfig) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *NetworkConnectionConfig) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *NetworkConnectionConfig) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPassword

`func (o *NetworkConnectionConfig) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *NetworkConnectionConfig) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *NetworkConnectionConfig) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *NetworkConnectionConfig) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetConfig

`func (o *NetworkConnectionConfig) GetConfig() string`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *NetworkConnectionConfig) GetConfigOk() (*string, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *NetworkConnectionConfig) SetConfig(v string)`

SetConfig sets Config field to given value.


### GetPhysicalInterface

`func (o *NetworkConnectionConfig) GetPhysicalInterface() string`

GetPhysicalInterface returns the PhysicalInterface field if non-nil, zero value otherwise.

### GetPhysicalInterfaceOk

`func (o *NetworkConnectionConfig) GetPhysicalInterfaceOk() (*string, bool)`

GetPhysicalInterfaceOk returns a tuple with the PhysicalInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterface

`func (o *NetworkConnectionConfig) SetPhysicalInterface(v string)`

SetPhysicalInterface sets PhysicalInterface field to given value.


### GetVlanId

`func (o *NetworkConnectionConfig) GetVlanId() float32`

GetVlanId returns the VlanId field if non-nil, zero value otherwise.

### GetVlanIdOk

`func (o *NetworkConnectionConfig) GetVlanIdOk() (*float32, bool)`

GetVlanIdOk returns a tuple with the VlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanId

`func (o *NetworkConnectionConfig) SetVlanId(v float32)`

SetVlanId sets VlanId field to given value.


### GetDhcpMode

`func (o *NetworkConnectionConfig) GetDhcpMode() string`

GetDhcpMode returns the DhcpMode field if non-nil, zero value otherwise.

### GetDhcpModeOk

`func (o *NetworkConnectionConfig) GetDhcpModeOk() (*string, bool)`

GetDhcpModeOk returns a tuple with the DhcpMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpMode

`func (o *NetworkConnectionConfig) SetDhcpMode(v string)`

SetDhcpMode sets DhcpMode field to given value.


### GetGateway

`func (o *NetworkConnectionConfig) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *NetworkConnectionConfig) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *NetworkConnectionConfig) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *NetworkConnectionConfig) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetNetwork

`func (o *NetworkConnectionConfig) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *NetworkConnectionConfig) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *NetworkConnectionConfig) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *NetworkConnectionConfig) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetDnsServers

`func (o *NetworkConnectionConfig) GetDnsServers() []string`

GetDnsServers returns the DnsServers field if non-nil, zero value otherwise.

### GetDnsServersOk

`func (o *NetworkConnectionConfig) GetDnsServersOk() (*[]string, bool)`

GetDnsServersOk returns a tuple with the DnsServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsServers

`func (o *NetworkConnectionConfig) SetDnsServers(v []string)`

SetDnsServers sets DnsServers field to given value.

### HasDnsServers

`func (o *NetworkConnectionConfig) HasDnsServers() bool`

HasDnsServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


