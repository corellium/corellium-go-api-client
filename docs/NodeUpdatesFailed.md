# NodeUpdatesFailed

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **NullableString** | Instructions to try again or resolve manually | [optional] 
**Nodes** | Pointer to [**[]NodeInformationV1**](NodeInformationV1.md) | List of nodes that failed to receive updates. | [optional] 

## Methods

### NewNodeUpdatesFailed

`func NewNodeUpdatesFailed() *NodeUpdatesFailed`

NewNodeUpdatesFailed instantiates a new NodeUpdatesFailed object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeUpdatesFailedWithDefaults

`func NewNodeUpdatesFailedWithDefaults() *NodeUpdatesFailed`

NewNodeUpdatesFailedWithDefaults instantiates a new NodeUpdatesFailed object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *NodeUpdatesFailed) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *NodeUpdatesFailed) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *NodeUpdatesFailed) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *NodeUpdatesFailed) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *NodeUpdatesFailed) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *NodeUpdatesFailed) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetNodes

`func (o *NodeUpdatesFailed) GetNodes() []NodeInformationV1`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *NodeUpdatesFailed) GetNodesOk() (*[]NodeInformationV1, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *NodeUpdatesFailed) SetNodes(v []NodeInformationV1)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *NodeUpdatesFailed) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### SetNodesNil

`func (o *NodeUpdatesFailed) SetNodesNil(b bool)`

 SetNodesNil sets the value for Nodes to be an explicit nil

### UnsetNodes
`func (o *NodeUpdatesFailed) UnsetNodes()`

UnsetNodes ensures that no value is present for Nodes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


