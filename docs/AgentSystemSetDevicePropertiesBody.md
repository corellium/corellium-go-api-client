# AgentSystemSetDevicePropertiesBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ModelId** | Pointer to **NullableString** | New model ID for the instance. Use null to reset to the default model ID. | [optional] 
**ManufacturerId** | Pointer to **NullableString** | New manufacturer ID for the instance. Use null to reset to the default manufacturer ID. | [optional] 

## Methods

### NewAgentSystemSetDevicePropertiesBody

`func NewAgentSystemSetDevicePropertiesBody() *AgentSystemSetDevicePropertiesBody`

NewAgentSystemSetDevicePropertiesBody instantiates a new AgentSystemSetDevicePropertiesBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentSystemSetDevicePropertiesBodyWithDefaults

`func NewAgentSystemSetDevicePropertiesBodyWithDefaults() *AgentSystemSetDevicePropertiesBody`

NewAgentSystemSetDevicePropertiesBodyWithDefaults instantiates a new AgentSystemSetDevicePropertiesBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModelId

`func (o *AgentSystemSetDevicePropertiesBody) GetModelId() string`

GetModelId returns the ModelId field if non-nil, zero value otherwise.

### GetModelIdOk

`func (o *AgentSystemSetDevicePropertiesBody) GetModelIdOk() (*string, bool)`

GetModelIdOk returns a tuple with the ModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelId

`func (o *AgentSystemSetDevicePropertiesBody) SetModelId(v string)`

SetModelId sets ModelId field to given value.

### HasModelId

`func (o *AgentSystemSetDevicePropertiesBody) HasModelId() bool`

HasModelId returns a boolean if a field has been set.

### SetModelIdNil

`func (o *AgentSystemSetDevicePropertiesBody) SetModelIdNil(b bool)`

 SetModelIdNil sets the value for ModelId to be an explicit nil

### UnsetModelId
`func (o *AgentSystemSetDevicePropertiesBody) UnsetModelId()`

UnsetModelId ensures that no value is present for ModelId, not even an explicit nil
### GetManufacturerId

`func (o *AgentSystemSetDevicePropertiesBody) GetManufacturerId() string`

GetManufacturerId returns the ManufacturerId field if non-nil, zero value otherwise.

### GetManufacturerIdOk

`func (o *AgentSystemSetDevicePropertiesBody) GetManufacturerIdOk() (*string, bool)`

GetManufacturerIdOk returns a tuple with the ManufacturerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerId

`func (o *AgentSystemSetDevicePropertiesBody) SetManufacturerId(v string)`

SetManufacturerId sets ManufacturerId field to given value.

### HasManufacturerId

`func (o *AgentSystemSetDevicePropertiesBody) HasManufacturerId() bool`

HasManufacturerId returns a boolean if a field has been set.

### SetManufacturerIdNil

`func (o *AgentSystemSetDevicePropertiesBody) SetManufacturerIdNil(b bool)`

 SetManufacturerIdNil sets the value for ManufacturerId to be an explicit nil

### UnsetManufacturerId
`func (o *AgentSystemSetDevicePropertiesBody) UnsetManufacturerId()`

UnsetManufacturerId ensures that no value is present for ManufacturerId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


