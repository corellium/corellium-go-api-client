# AgentAppsListV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Apps** | Pointer to [**[]AgentAppV1**](AgentAppV1.md) |  | [optional] 
**Frontmost** | Pointer to **NullableString** | bundleID of frontmost app or empty string if none are frontmost | [optional] 

## Methods

### NewAgentAppsListV1

`func NewAgentAppsListV1() *AgentAppsListV1`

NewAgentAppsListV1 instantiates a new AgentAppsListV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentAppsListV1WithDefaults

`func NewAgentAppsListV1WithDefaults() *AgentAppsListV1`

NewAgentAppsListV1WithDefaults instantiates a new AgentAppsListV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApps

`func (o *AgentAppsListV1) GetApps() []AgentAppV1`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *AgentAppsListV1) GetAppsOk() (*[]AgentAppV1, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *AgentAppsListV1) SetApps(v []AgentAppV1)`

SetApps sets Apps field to given value.

### HasApps

`func (o *AgentAppsListV1) HasApps() bool`

HasApps returns a boolean if a field has been set.

### SetAppsNil

`func (o *AgentAppsListV1) SetAppsNil(b bool)`

 SetAppsNil sets the value for Apps to be an explicit nil

### UnsetApps
`func (o *AgentAppsListV1) UnsetApps()`

UnsetApps ensures that no value is present for Apps, not even an explicit nil
### GetFrontmost

`func (o *AgentAppsListV1) GetFrontmost() string`

GetFrontmost returns the Frontmost field if non-nil, zero value otherwise.

### GetFrontmostOk

`func (o *AgentAppsListV1) GetFrontmostOk() (*string, bool)`

GetFrontmostOk returns a tuple with the Frontmost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontmost

`func (o *AgentAppsListV1) SetFrontmost(v string)`

SetFrontmost sets Frontmost field to given value.

### HasFrontmost

`func (o *AgentAppsListV1) HasFrontmost() bool`

HasFrontmost returns a boolean if a field has been set.

### SetFrontmostNil

`func (o *AgentAppsListV1) SetFrontmostNil(b bool)`

 SetFrontmostNil sets the value for Frontmost to be an explicit nil

### UnsetFrontmost
`func (o *AgentAppsListV1) UnsetFrontmost()`

UnsetFrontmost ensures that no value is present for Frontmost, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


