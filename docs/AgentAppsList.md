# AgentAppsList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Whether the agent request succeeded. | 
**Apps** | [**[]AgentApp**](AgentApp.md) | List of installed apps. | 
**Frontmost** | Pointer to **string** | Bundle ID of the frontmost app or empty string if none (iOS only). | [optional] 

## Methods

### NewAgentAppsList

`func NewAgentAppsList(success bool, apps []AgentApp, ) *AgentAppsList`

NewAgentAppsList instantiates a new AgentAppsList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppsListWithDefaults

`func NewAgentAppsListWithDefaults() *AgentAppsList`

NewAgentAppsListWithDefaults instantiates a new AgentAppsList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AgentAppsList) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AgentAppsList) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AgentAppsList) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetApps

`func (o *AgentAppsList) GetApps() []AgentApp`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *AgentAppsList) GetAppsOk() (*[]AgentApp, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *AgentAppsList) SetApps(v []AgentApp)`

SetApps sets Apps field to given value.


### GetFrontmost

`func (o *AgentAppsList) GetFrontmost() string`

GetFrontmost returns the Frontmost field if non-nil, zero value otherwise.

### GetFrontmostOk

`func (o *AgentAppsList) GetFrontmostOk() (*string, bool)`

GetFrontmostOk returns a tuple with the Frontmost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontmost

`func (o *AgentAppsList) SetFrontmost(v string)`

SetFrontmost sets Frontmost field to given value.

### HasFrontmost

`func (o *AgentAppsList) HasFrontmost() bool`

HasFrontmost returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


