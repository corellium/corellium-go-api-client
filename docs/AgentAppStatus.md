# AgentAppStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Running** | **bool** | Whether the app is currently running. | 
**BundleId** | **string** | App bundle identifier. | 

## Methods

### NewAgentAppStatus

`func NewAgentAppStatus(running bool, bundleId string, ) *AgentAppStatus`

NewAgentAppStatus instantiates a new AgentAppStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppStatusWithDefaults

`func NewAgentAppStatusWithDefaults() *AgentAppStatus`

NewAgentAppStatusWithDefaults instantiates a new AgentAppStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunning

`func (o *AgentAppStatus) GetRunning() bool`

GetRunning returns the Running field if non-nil, zero value otherwise.

### GetRunningOk

`func (o *AgentAppStatus) GetRunningOk() (*bool, bool)`

GetRunningOk returns a tuple with the Running field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunning

`func (o *AgentAppStatus) SetRunning(v bool)`

SetRunning sets Running field to given value.


### GetBundleId

`func (o *AgentAppStatus) GetBundleId() string`

GetBundleId returns the BundleId field if non-nil, zero value otherwise.

### GetBundleIdOk

`func (o *AgentAppStatus) GetBundleIdOk() (*string, bool)`

GetBundleIdOk returns a tuple with the BundleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleId

`func (o *AgentAppStatus) SetBundleId(v string)`

SetBundleId sets BundleId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


