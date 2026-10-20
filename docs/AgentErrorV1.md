# AgentErrorV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** | The error encountered by the agent | 
**ErrorID** | **string** | AgentError | 
**OriginalError** | Pointer to **map[string]interface{}** | The full error encountered by the agent | [optional] 

## Methods

### NewAgentErrorV1

`func NewAgentErrorV1(error_ string, errorID string, ) *AgentErrorV1`

NewAgentErrorV1 instantiates a new AgentErrorV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentErrorV1WithDefaults

`func NewAgentErrorV1WithDefaults() *AgentErrorV1`

NewAgentErrorV1WithDefaults instantiates a new AgentErrorV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *AgentErrorV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AgentErrorV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AgentErrorV1) SetError(v string)`

SetError sets Error field to given value.


### GetErrorID

`func (o *AgentErrorV1) GetErrorID() string`

GetErrorID returns the ErrorID field if non-nil, zero value otherwise.

### GetErrorIDOk

`func (o *AgentErrorV1) GetErrorIDOk() (*string, bool)`

GetErrorIDOk returns a tuple with the ErrorID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorID

`func (o *AgentErrorV1) SetErrorID(v string)`

SetErrorID sets ErrorID field to given value.


### GetOriginalError

`func (o *AgentErrorV1) GetOriginalError() map[string]interface{}`

GetOriginalError returns the OriginalError field if non-nil, zero value otherwise.

### GetOriginalErrorOk

`func (o *AgentErrorV1) GetOriginalErrorOk() (*map[string]interface{}, bool)`

GetOriginalErrorOk returns a tuple with the OriginalError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalError

`func (o *AgentErrorV1) SetOriginalError(v map[string]interface{})`

SetOriginalError sets OriginalError field to given value.

### HasOriginalError

`func (o *AgentErrorV1) HasOriginalError() bool`

HasOriginalError returns a boolean if a field has been set.

### SetOriginalErrorNil

`func (o *AgentErrorV1) SetOriginalErrorNil(b bool)`

 SetOriginalErrorNil sets the value for OriginalError to be an explicit nil

### UnsetOriginalError
`func (o *AgentErrorV1) UnsetOriginalError()`

UnsetOriginalError ensures that no value is present for OriginalError, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


