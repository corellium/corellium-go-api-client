# AgentSystemGetPropResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **float32** | Agent sequence ID. | 
**Success** | **bool** | Whether the agent operation succeeded. | 
**Value** | Pointer to **string** | The value of the requested property. Omitted when the property is unset. | [optional] 

## Methods

### NewAgentSystemGetPropResponse

`func NewAgentSystemGetPropResponse(id float32, success bool, ) *AgentSystemGetPropResponse`

NewAgentSystemGetPropResponse instantiates a new AgentSystemGetPropResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentSystemGetPropResponseWithDefaults

`func NewAgentSystemGetPropResponseWithDefaults() *AgentSystemGetPropResponse`

NewAgentSystemGetPropResponseWithDefaults instantiates a new AgentSystemGetPropResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AgentSystemGetPropResponse) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentSystemGetPropResponse) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentSystemGetPropResponse) SetId(v float32)`

SetId sets Id field to given value.


### GetSuccess

`func (o *AgentSystemGetPropResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AgentSystemGetPropResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AgentSystemGetPropResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetValue

`func (o *AgentSystemGetPropResponse) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AgentSystemGetPropResponse) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AgentSystemGetPropResponse) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *AgentSystemGetPropResponse) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


