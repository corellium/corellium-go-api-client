# ClusterConfigurationPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SnapshotLimit** | Pointer to **NullableFloat32** | Designates the maximum number of snapshots that can be taken in a cluster | [optional] 
**CoordinatorConfig** | Pointer to [**CoordinatorConfigV1**](CoordinatorConfigV1.md) |  | [optional] 
**AiToolsConfig** | Pointer to [**AiToolsConfigV1**](AiToolsConfigV1.md) |  | [optional] 

## Methods

### NewClusterConfigurationPayload

`func NewClusterConfigurationPayload() *ClusterConfigurationPayload`

NewClusterConfigurationPayload instantiates a new ClusterConfigurationPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigurationPayloadWithDefaults

`func NewClusterConfigurationPayloadWithDefaults() *ClusterConfigurationPayload`

NewClusterConfigurationPayloadWithDefaults instantiates a new ClusterConfigurationPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSnapshotLimit

`func (o *ClusterConfigurationPayload) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *ClusterConfigurationPayload) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *ClusterConfigurationPayload) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.

### HasSnapshotLimit

`func (o *ClusterConfigurationPayload) HasSnapshotLimit() bool`

HasSnapshotLimit returns a boolean if a field has been set.

### SetSnapshotLimitNil

`func (o *ClusterConfigurationPayload) SetSnapshotLimitNil(b bool)`

 SetSnapshotLimitNil sets the value for SnapshotLimit to be an explicit nil

### UnsetSnapshotLimit
`func (o *ClusterConfigurationPayload) UnsetSnapshotLimit()`

UnsetSnapshotLimit ensures that no value is present for SnapshotLimit, not even an explicit nil
### GetCoordinatorConfig

`func (o *ClusterConfigurationPayload) GetCoordinatorConfig() CoordinatorConfigV1`

GetCoordinatorConfig returns the CoordinatorConfig field if non-nil, zero value otherwise.

### GetCoordinatorConfigOk

`func (o *ClusterConfigurationPayload) GetCoordinatorConfigOk() (*CoordinatorConfigV1, bool)`

GetCoordinatorConfigOk returns a tuple with the CoordinatorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorConfig

`func (o *ClusterConfigurationPayload) SetCoordinatorConfig(v CoordinatorConfigV1)`

SetCoordinatorConfig sets CoordinatorConfig field to given value.

### HasCoordinatorConfig

`func (o *ClusterConfigurationPayload) HasCoordinatorConfig() bool`

HasCoordinatorConfig returns a boolean if a field has been set.

### GetAiToolsConfig

`func (o *ClusterConfigurationPayload) GetAiToolsConfig() AiToolsConfigV1`

GetAiToolsConfig returns the AiToolsConfig field if non-nil, zero value otherwise.

### GetAiToolsConfigOk

`func (o *ClusterConfigurationPayload) GetAiToolsConfigOk() (*AiToolsConfigV1, bool)`

GetAiToolsConfigOk returns a tuple with the AiToolsConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiToolsConfig

`func (o *ClusterConfigurationPayload) SetAiToolsConfig(v AiToolsConfigV1)`

SetAiToolsConfig sets AiToolsConfig field to given value.

### HasAiToolsConfig

`func (o *ClusterConfigurationPayload) HasAiToolsConfig() bool`

HasAiToolsConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


