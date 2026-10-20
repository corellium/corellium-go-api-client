# NodeInformation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** | Unique identifier for the node. | 
**Address** | **string** | IP address of the node. | 
**Hostname** | **string** | Hostname of the node. | 
**SshPort** | **NullableFloat32** | SSH port for the node (1-65535), or null if unavailable. | 
**NodeTypes** | **[]string** | Types of services running on this node. | 

## Methods

### NewNodeInformation

`func NewNodeInformation(nodeId string, address string, hostname string, sshPort NullableFloat32, nodeTypes []string, ) *NodeInformation`

NewNodeInformation instantiates a new NodeInformation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeInformationWithDefaults

`func NewNodeInformationWithDefaults() *NodeInformation`

NewNodeInformationWithDefaults instantiates a new NodeInformation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *NodeInformation) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *NodeInformation) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *NodeInformation) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetAddress

`func (o *NodeInformation) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *NodeInformation) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *NodeInformation) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetHostname

`func (o *NodeInformation) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *NodeInformation) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *NodeInformation) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### GetSshPort

`func (o *NodeInformation) GetSshPort() float32`

GetSshPort returns the SshPort field if non-nil, zero value otherwise.

### GetSshPortOk

`func (o *NodeInformation) GetSshPortOk() (*float32, bool)`

GetSshPortOk returns a tuple with the SshPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSshPort

`func (o *NodeInformation) SetSshPort(v float32)`

SetSshPort sets SshPort field to given value.


### SetSshPortNil

`func (o *NodeInformation) SetSshPortNil(b bool)`

 SetSshPortNil sets the value for SshPort to be an explicit nil

### UnsetSshPort
`func (o *NodeInformation) UnsetSshPort()`

UnsetSshPort ensures that no value is present for SshPort, not even an explicit nil
### GetNodeTypes

`func (o *NodeInformation) GetNodeTypes() []string`

GetNodeTypes returns the NodeTypes field if non-nil, zero value otherwise.

### GetNodeTypesOk

`func (o *NodeInformation) GetNodeTypesOk() (*[]string, bool)`

GetNodeTypesOk returns a tuple with the NodeTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeTypes

`func (o *NodeInformation) SetNodeTypes(v []string)`

SetNodeTypes sets NodeTypes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


