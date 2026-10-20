# UpdateNetworkConnectionOptionsConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | Pointer to **string** | Username for OpenVPN connection. | [optional] 
**Password** | Pointer to **string** | Password for OpenVPN connection. | [optional] 
**Config** | **string** | OpenVPN connection configuration. | 
**PhysicalInterface** | **string** | Physical network interface to create VLAN on. | 
**VlanId** | **float32** | VLAN ID (1-4094). | 
**DhcpMode** | **string** | DHCP server mode. | 
**Gateway** | Pointer to **string** | Gateway IP address. | [optional] 
**Network** | Pointer to **string** | Network address. | [optional] 
**DnsServers** | Pointer to **[]string** | List of DNS servers. | [optional] 

## Methods

### NewUpdateNetworkConnectionOptionsConfig

`func NewUpdateNetworkConnectionOptionsConfig(config string, physicalInterface string, vlanId float32, dhcpMode string, ) *UpdateNetworkConnectionOptionsConfig`

NewUpdateNetworkConnectionOptionsConfig instantiates a new UpdateNetworkConnectionOptionsConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateNetworkConnectionOptionsConfigWithDefaults

`func NewUpdateNetworkConnectionOptionsConfigWithDefaults() *UpdateNetworkConnectionOptionsConfig`

NewUpdateNetworkConnectionOptionsConfigWithDefaults instantiates a new UpdateNetworkConnectionOptionsConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsername

`func (o *UpdateNetworkConnectionOptionsConfig) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *UpdateNetworkConnectionOptionsConfig) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *UpdateNetworkConnectionOptionsConfig) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### GetPassword

`func (o *UpdateNetworkConnectionOptionsConfig) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UpdateNetworkConnectionOptionsConfig) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UpdateNetworkConnectionOptionsConfig) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetConfig

`func (o *UpdateNetworkConnectionOptionsConfig) GetConfig() string`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetConfigOk() (*string, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UpdateNetworkConnectionOptionsConfig) SetConfig(v string)`

SetConfig sets Config field to given value.


### GetPhysicalInterface

`func (o *UpdateNetworkConnectionOptionsConfig) GetPhysicalInterface() string`

GetPhysicalInterface returns the PhysicalInterface field if non-nil, zero value otherwise.

### GetPhysicalInterfaceOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetPhysicalInterfaceOk() (*string, bool)`

GetPhysicalInterfaceOk returns a tuple with the PhysicalInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterface

`func (o *UpdateNetworkConnectionOptionsConfig) SetPhysicalInterface(v string)`

SetPhysicalInterface sets PhysicalInterface field to given value.


### GetVlanId

`func (o *UpdateNetworkConnectionOptionsConfig) GetVlanId() float32`

GetVlanId returns the VlanId field if non-nil, zero value otherwise.

### GetVlanIdOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetVlanIdOk() (*float32, bool)`

GetVlanIdOk returns a tuple with the VlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVlanId

`func (o *UpdateNetworkConnectionOptionsConfig) SetVlanId(v float32)`

SetVlanId sets VlanId field to given value.


### GetDhcpMode

`func (o *UpdateNetworkConnectionOptionsConfig) GetDhcpMode() string`

GetDhcpMode returns the DhcpMode field if non-nil, zero value otherwise.

### GetDhcpModeOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetDhcpModeOk() (*string, bool)`

GetDhcpModeOk returns a tuple with the DhcpMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDhcpMode

`func (o *UpdateNetworkConnectionOptionsConfig) SetDhcpMode(v string)`

SetDhcpMode sets DhcpMode field to given value.


### GetGateway

`func (o *UpdateNetworkConnectionOptionsConfig) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *UpdateNetworkConnectionOptionsConfig) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *UpdateNetworkConnectionOptionsConfig) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetNetwork

`func (o *UpdateNetworkConnectionOptionsConfig) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *UpdateNetworkConnectionOptionsConfig) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *UpdateNetworkConnectionOptionsConfig) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetDnsServers

`func (o *UpdateNetworkConnectionOptionsConfig) GetDnsServers() []string`

GetDnsServers returns the DnsServers field if non-nil, zero value otherwise.

### GetDnsServersOk

`func (o *UpdateNetworkConnectionOptionsConfig) GetDnsServersOk() (*[]string, bool)`

GetDnsServersOk returns a tuple with the DnsServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDnsServers

`func (o *UpdateNetworkConnectionOptionsConfig) SetDnsServers(v []string)`

SetDnsServers sets DnsServers field to given value.

### HasDnsServers

`func (o *UpdateNetworkConnectionOptionsConfig) HasDnsServers() bool`

HasDnsServers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


