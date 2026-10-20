# AgentFileAttributesBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Path** | Pointer to **string** | New path to move/rename the file to. | [optional] 
**Mode** | Pointer to **float32** | New file mode as a decimal integer (octal 0644 &#x3D; 420). | [optional] 
**Uid** | Pointer to **float32** | New owner UID. | [optional] 
**Gid** | Pointer to **float32** | New group GID. | [optional] 

## Methods

### NewAgentFileAttributesBody

`func NewAgentFileAttributesBody() *AgentFileAttributesBody`

NewAgentFileAttributesBody instantiates a new AgentFileAttributesBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentFileAttributesBodyWithDefaults

`func NewAgentFileAttributesBodyWithDefaults() *AgentFileAttributesBody`

NewAgentFileAttributesBodyWithDefaults instantiates a new AgentFileAttributesBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPath

`func (o *AgentFileAttributesBody) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *AgentFileAttributesBody) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *AgentFileAttributesBody) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *AgentFileAttributesBody) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetMode

`func (o *AgentFileAttributesBody) GetMode() float32`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *AgentFileAttributesBody) GetModeOk() (*float32, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *AgentFileAttributesBody) SetMode(v float32)`

SetMode sets Mode field to given value.

### HasMode

`func (o *AgentFileAttributesBody) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetUid

`func (o *AgentFileAttributesBody) GetUid() float32`

GetUid returns the Uid field if non-nil, zero value otherwise.

### GetUidOk

`func (o *AgentFileAttributesBody) GetUidOk() (*float32, bool)`

GetUidOk returns a tuple with the Uid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUid

`func (o *AgentFileAttributesBody) SetUid(v float32)`

SetUid sets Uid field to given value.

### HasUid

`func (o *AgentFileAttributesBody) HasUid() bool`

HasUid returns a boolean if a field has been set.

### GetGid

`func (o *AgentFileAttributesBody) GetGid() float32`

GetGid returns the Gid field if non-nil, zero value otherwise.

### GetGidOk

`func (o *AgentFileAttributesBody) GetGidOk() (*float32, bool)`

GetGidOk returns a tuple with the Gid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGid

`func (o *AgentFileAttributesBody) SetGid(v float32)`

SetGid sets Gid field to given value.

### HasGid

`func (o *AgentFileAttributesBody) HasGid() bool`

HasGid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


