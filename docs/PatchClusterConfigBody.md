# PatchClusterConfigBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SnapshotLimit** | Pointer to **float32** | Maximum number of snapshots that can be taken in the cluster. | [optional] 
**CoordinatorConfig** | Pointer to [**CoordinatorConfig**](CoordinatorConfig.md) |  | [optional] 
**AiToolsConfig** | Pointer to [**AiToolsConfig**](AiToolsConfig.md) | Partial AI tools configuration to update. | [optional] 
**OriginatingNode** | Pointer to **string** | IP address of the node that originated this config change; prevents re-broadcast. | [optional] 

## Methods

### NewPatchClusterConfigBody

`func NewPatchClusterConfigBody() *PatchClusterConfigBody`

NewPatchClusterConfigBody instantiates a new PatchClusterConfigBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchClusterConfigBodyWithDefaults

`func NewPatchClusterConfigBodyWithDefaults() *PatchClusterConfigBody`

NewPatchClusterConfigBodyWithDefaults instantiates a new PatchClusterConfigBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSnapshotLimit

`func (o *PatchClusterConfigBody) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *PatchClusterConfigBody) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *PatchClusterConfigBody) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.

### HasSnapshotLimit

`func (o *PatchClusterConfigBody) HasSnapshotLimit() bool`

HasSnapshotLimit returns a boolean if a field has been set.

### GetCoordinatorConfig

`func (o *PatchClusterConfigBody) GetCoordinatorConfig() CoordinatorConfig`

GetCoordinatorConfig returns the CoordinatorConfig field if non-nil, zero value otherwise.

### GetCoordinatorConfigOk

`func (o *PatchClusterConfigBody) GetCoordinatorConfigOk() (*CoordinatorConfig, bool)`

GetCoordinatorConfigOk returns a tuple with the CoordinatorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorConfig

`func (o *PatchClusterConfigBody) SetCoordinatorConfig(v CoordinatorConfig)`

SetCoordinatorConfig sets CoordinatorConfig field to given value.

### HasCoordinatorConfig

`func (o *PatchClusterConfigBody) HasCoordinatorConfig() bool`

HasCoordinatorConfig returns a boolean if a field has been set.

### GetAiToolsConfig

`func (o *PatchClusterConfigBody) GetAiToolsConfig() AiToolsConfig`

GetAiToolsConfig returns the AiToolsConfig field if non-nil, zero value otherwise.

### GetAiToolsConfigOk

`func (o *PatchClusterConfigBody) GetAiToolsConfigOk() (*AiToolsConfig, bool)`

GetAiToolsConfigOk returns a tuple with the AiToolsConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiToolsConfig

`func (o *PatchClusterConfigBody) SetAiToolsConfig(v AiToolsConfig)`

SetAiToolsConfig sets AiToolsConfig field to given value.

### HasAiToolsConfig

`func (o *PatchClusterConfigBody) HasAiToolsConfig() bool`

HasAiToolsConfig returns a boolean if a field has been set.

### GetOriginatingNode

`func (o *PatchClusterConfigBody) GetOriginatingNode() string`

GetOriginatingNode returns the OriginatingNode field if non-nil, zero value otherwise.

### GetOriginatingNodeOk

`func (o *PatchClusterConfigBody) GetOriginatingNodeOk() (*string, bool)`

GetOriginatingNodeOk returns a tuple with the OriginatingNode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginatingNode

`func (o *PatchClusterConfigBody) SetOriginatingNode(v string)`

SetOriginatingNode sets OriginatingNode field to given value.

### HasOriginatingNode

`func (o *PatchClusterConfigBody) HasOriginatingNode() bool`

HasOriginatingNode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


