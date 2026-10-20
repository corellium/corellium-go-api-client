# AgentAppsStatusList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Whether the agent request succeeded. | 
**Id** | **float32** | Agent sequence ID. | 
**Apps** | [**[]AgentAppStatus**](AgentAppStatus.md) | List of app statuses. | 
**Frontmost** | Pointer to **string** | Bundle ID of the frontmost app or empty string if none (iOS only). | [optional] 

## Methods

### NewAgentAppsStatusList

`func NewAgentAppsStatusList(success bool, id float32, apps []AgentAppStatus, ) *AgentAppsStatusList`

NewAgentAppsStatusList instantiates a new AgentAppsStatusList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppsStatusListWithDefaults

`func NewAgentAppsStatusListWithDefaults() *AgentAppsStatusList`

NewAgentAppsStatusListWithDefaults instantiates a new AgentAppsStatusList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AgentAppsStatusList) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AgentAppsStatusList) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AgentAppsStatusList) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetId

`func (o *AgentAppsStatusList) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentAppsStatusList) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentAppsStatusList) SetId(v float32)`

SetId sets Id field to given value.


### GetApps

`func (o *AgentAppsStatusList) GetApps() []AgentAppStatus`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *AgentAppsStatusList) GetAppsOk() (*[]AgentAppStatus, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *AgentAppsStatusList) SetApps(v []AgentAppStatus)`

SetApps sets Apps field to given value.


### GetFrontmost

`func (o *AgentAppsStatusList) GetFrontmost() string`

GetFrontmost returns the Frontmost field if non-nil, zero value otherwise.

### GetFrontmostOk

`func (o *AgentAppsStatusList) GetFrontmostOk() (*string, bool)`

GetFrontmostOk returns a tuple with the Frontmost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontmost

`func (o *AgentAppsStatusList) SetFrontmost(v string)`

SetFrontmost sets Frontmost field to given value.

### HasFrontmost

`func (o *AgentAppsStatusList) HasFrontmost() bool`

HasFrontmost returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


