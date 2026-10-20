# AgentAppStatusV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Running** | Pointer to **NullableBool** |  | [optional] 
**BundleID** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAgentAppStatusV1

`func NewAgentAppStatusV1() *AgentAppStatusV1`

NewAgentAppStatusV1 instantiates a new AgentAppStatusV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppStatusV1WithDefaults

`func NewAgentAppStatusV1WithDefaults() *AgentAppStatusV1`

NewAgentAppStatusV1WithDefaults instantiates a new AgentAppStatusV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunning

`func (o *AgentAppStatusV1) GetRunning() bool`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *AgentAppStatusV1) GetRunningOk() (*bool, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *AgentAppStatusV1) SetRunning(v bool)`

SetRunning sets Running field to given value.

### HasRunning

`func (o *AgentAppStatusV1) HasRunning() bool`

HasRunning returns a boolean if a field has been set.

### SetRunningNil

`func (o *AgentAppStatusV1) SetRunningNil(b bool)`

 SetRunningNil sets the value for Running to be an explicit nil

### UnsetRunning
`func (o *AgentAppStatusV1) UnsetRunning()`

UnsetRunning ensures that no value is present for Running, not even an explicit nil
### GetBundleID

`func (o *AgentAppStatusV1) GetBundleID() string`

GetBundleID returns the BundleID field if non-nil, zero value otherwise.

### GetBundleIDOk

`func (o *AgentAppStatusV1) GetBundleIDOk() (*string, bool)`

GetBundleIDOk returns a tuple with the BundleID field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleID

`func (o *AgentAppStatusV1) SetBundleID(v string)`

SetBundleID sets BundleID field to given value.

### HasBundleID

`func (o *AgentAppStatusV1) HasBundleID() bool`

HasBundleID returns a boolean if a field has been set.

### SetBundleIDNil

`func (o *AgentAppStatusV1) SetBundleIDNil(b bool)`

 SetBundleIDNil sets the value for BundleID to be an explicit nil

### UnsetBundleID
`func (o *AgentAppStatusV1) UnsetBundleID()`

UnsetBundleID ensures that no value is present for BundleID, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


