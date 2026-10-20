# NodeInformationV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** | Unique identifier for the node | 
**Address** | **string** | IP address of the node | 
**Hostname** | **string** | Hostname of the node | 
**SshPort** | Pointer to **NullableFloat32** | SSH port for the node | [optional] 
**NodeTypes** | **[]string** | Types of services running on this node [compute,controller,gpu] | 

## Methods

### NewNodeInformationV1

`func NewNodeInformationV1(nodeId string, address string, hostname string, nodeTypes []string, ) *NodeInformationV1`

NewNodeInformationV1 instantiates a new NodeInformationV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeInformationV1WithDefaults

`func NewNodeInformationV1WithDefaults() *NodeInformationV1`

NewNodeInformationV1WithDefaults instantiates a new NodeInformationV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *NodeInformationV1) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *NodeInformationV1) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *NodeInformationV1) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetAddress

`func (o *NodeInformationV1) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *NodeInformationV1) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *NodeInformationV1) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetHostname

`func (o *NodeInformationV1) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *NodeInformationV1) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *NodeInformationV1) SetHostname(v string)`

SetHostname sets Hostname field to given value.


### GetSshPort

`func (o *NodeInformationV1) GetSshPort() float32`

GetSshPort returns the SshPort field if non-nil, zero value otherwise.

### GetSshPortOk

`func (o *NodeInformationV1) GetSshPortOk() (*float32, bool)`

GetSshPortOk returns a tuple with the SshPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSshPort

`func (o *NodeInformationV1) SetSshPort(v float32)`

SetSshPort sets SshPort field to given value.

### HasSshPort

`func (o *NodeInformationV1) HasSshPort() bool`

HasSshPort returns a boolean if a field has been set.

### SetSshPortNil

`func (o *NodeInformationV1) SetSshPortNil(b bool)`

 SetSshPortNil sets the value for SshPort to be an explicit nil

### UnsetSshPort
`func (o *NodeInformationV1) UnsetSshPort()`

UnsetSshPort ensures that no value is present for SshPort, not even an explicit nil
### GetNodeTypes

`func (o *NodeInformationV1) GetNodeTypes() []string`

GetNodeTypes returns the NodeTypes field if non-nil, zero value otherwise.

### GetNodeTypesOk

`func (o *NodeInformationV1) GetNodeTypesOk() (*[]string, bool)`

GetNodeTypesOk returns a tuple with the NodeTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeTypes

`func (o *NodeInformationV1) SetNodeTypes(v []string)`

SetNodeTypes sets NodeTypes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


