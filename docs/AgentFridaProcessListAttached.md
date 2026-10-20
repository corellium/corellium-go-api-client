# AgentFridaProcessListAttached

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TargetName** | **string** | Name of the target process to attach to. | 
**TargetPid** | **float32** | PID of the process Frida is attached to. | 

## Methods

### NewAgentFridaProcessListAttached

`func NewAgentFridaProcessListAttached(targetName string, targetPid float32, ) *AgentFridaProcessListAttached`

NewAgentFridaProcessListAttached instantiates a new AgentFridaProcessListAttached object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentFridaProcessListAttachedWithDefaults

`func NewAgentFridaProcessListAttachedWithDefaults() *AgentFridaProcessListAttached`

NewAgentFridaProcessListAttachedWithDefaults instantiates a new AgentFridaProcessListAttached object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTargetName

`func (o *AgentFridaProcessListAttached) GetTargetName() string`

GetTargetName returns the TargetName field if non-nil, zero value otherwise.

### GetTargetNameOk

`func (o *AgentFridaProcessListAttached) GetTargetNameOk() (*string, bool)`

GetTargetNameOk returns a tuple with the TargetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetName

`func (o *AgentFridaProcessListAttached) SetTargetName(v string)`

SetTargetName sets TargetName field to given value.


### GetTargetPid

`func (o *AgentFridaProcessListAttached) GetTargetPid() float32`

GetTargetPid returns the TargetPid field if non-nil, zero value otherwise.

### GetTargetPidOk

`func (o *AgentFridaProcessListAttached) GetTargetPidOk() (*float32, bool)`

GetTargetPidOk returns a tuple with the TargetPid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetPid

`func (o *AgentFridaProcessListAttached) SetTargetPid(v float32)`

SetTargetPid sets TargetPid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


