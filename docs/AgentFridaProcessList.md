# AgentFridaProcessList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Whether the agent request succeeded. | 
**ExitStatus** | **float32** | Exit status of the frida-ps command. | 
**Output** | **string** | Raw output of the frida-ps command. | 
**Attached** | Pointer to [**AgentFridaProcessListAttached**](AgentFridaProcessListAttached.md) |  | [optional] 

## Methods

### NewAgentFridaProcessList

`func NewAgentFridaProcessList(success bool, exitStatus float32, output string, ) *AgentFridaProcessList`

NewAgentFridaProcessList instantiates a new AgentFridaProcessList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentFridaProcessListWithDefaults

`func NewAgentFridaProcessListWithDefaults() *AgentFridaProcessList`

NewAgentFridaProcessListWithDefaults instantiates a new AgentFridaProcessList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AgentFridaProcessList) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AgentFridaProcessList) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AgentFridaProcessList) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetExitStatus

`func (o *AgentFridaProcessList) GetExitStatus() float32`

GetExitStatus returns the ExitStatus field if non-nil, zero value otherwise.

### GetExitStatusOk

`func (o *AgentFridaProcessList) GetExitStatusOk() (*float32, bool)`

GetExitStatusOk returns a tuple with the ExitStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitStatus

`func (o *AgentFridaProcessList) SetExitStatus(v float32)`

SetExitStatus sets ExitStatus field to given value.


### GetOutput

`func (o *AgentFridaProcessList) GetOutput() string`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *AgentFridaProcessList) GetOutputOk() (*string, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *AgentFridaProcessList) SetOutput(v string)`

SetOutput sets Output field to given value.


### GetAttached

`func (o *AgentFridaProcessList) GetAttached() AgentFridaProcessListAttached`

GetAttached returns the Attached field if non-nil, zero value otherwise.

### GetAttachedOk

`func (o *AgentFridaProcessList) GetAttachedOk() (*AgentFridaProcessListAttached, bool)`

GetAttachedOk returns a tuple with the Attached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttached

`func (o *AgentFridaProcessList) SetAttached(v AgentFridaProcessListAttached)`

SetAttached sets Attached field to given value.

### HasAttached

`func (o *AgentFridaProcessList) HasAttached() bool`

HasAttached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


