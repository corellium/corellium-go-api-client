# AgentContainerList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Containers** | [**[]AgentContainer**](AgentContainer.md) | List of containers on the VM. | 

## Methods

### NewAgentContainerList

`func NewAgentContainerList(containers []AgentContainer, ) *AgentContainerList`

NewAgentContainerList instantiates a new AgentContainerList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentContainerListWithDefaults

`func NewAgentContainerListWithDefaults() *AgentContainerList`

NewAgentContainerListWithDefaults instantiates a new AgentContainerList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContainers

`func (o *AgentContainerList) GetContainers() []AgentContainer`

GetContainers returns the Containers field if non-nil, zero value otherwise.

### GetContainersOk

`func (o *AgentContainerList) GetContainersOk() (*[]AgentContainer, bool)`

GetContainersOk returns a tuple with the Containers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainers

`func (o *AgentContainerList) SetContainers(v []AgentContainer)`

SetContainers sets Containers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


