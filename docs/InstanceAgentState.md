# InstanceAgentState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hash** | Pointer to **string** | Hash for agent authentication. | [optional] 
**Info** | Pointer to **string** | Encrypted info for agent authentication. | [optional] 

## Methods

### NewInstanceAgentState

`func NewInstanceAgentState() *InstanceAgentState`

NewInstanceAgentState instantiates a new InstanceAgentState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceAgentStateWithDefaults

`func NewInstanceAgentStateWithDefaults() *InstanceAgentState`

NewInstanceAgentStateWithDefaults instantiates a new InstanceAgentState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHash

`func (o *InstanceAgentState) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *InstanceAgentState) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *InstanceAgentState) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *InstanceAgentState) HasHash() bool`

HasHash returns a boolean if a field has been set.

### GetInfo

`func (o *InstanceAgentState) GetInfo() string`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *InstanceAgentState) GetInfoOk() (*string, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *InstanceAgentState) SetInfo(v string)`

SetInfo sets Info field to given value.

### HasInfo

`func (o *InstanceAgentState) HasInfo() bool`

HasInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


