# AgentIconsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Whether the agent request succeeded. | 
**Id** | **float32** | Agent sequence ID. | 
**Icons** | **map[string]string** | Map of bundle ID to base64-encoded icon data. | 

## Methods

### NewAgentIconsResponse

`func NewAgentIconsResponse(success bool, id float32, icons map[string]string, ) *AgentIconsResponse`

NewAgentIconsResponse instantiates a new AgentIconsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentIconsResponseWithDefaults

`func NewAgentIconsResponseWithDefaults() *AgentIconsResponse`

NewAgentIconsResponseWithDefaults instantiates a new AgentIconsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AgentIconsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AgentIconsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AgentIconsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetId

`func (o *AgentIconsResponse) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentIconsResponse) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentIconsResponse) SetId(v float32)`

SetId sets Id field to given value.


### GetIcons

`func (o *AgentIconsResponse) GetIcons() map[string]string`

GetIcons returns the Icons field if non-nil, zero value otherwise.

### GetIconsOk

`func (o *AgentIconsResponse) GetIconsOk() (*map[string]string, bool)`

GetIconsOk returns a tuple with the Icons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcons

`func (o *AgentIconsResponse) SetIcons(v map[string]string)`

SetIcons sets Icons field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


