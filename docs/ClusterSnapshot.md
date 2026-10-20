# ClusterSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique identifier for the snapshot. | 
**Name** | Pointer to **string** | Snapshot name. | [optional] 
**Volume** | **NullableString** | Identifier of the volume this snapshot was taken from. | 
**Instance** | **NullableString** | Identifier of the instance this snapshot is associated with. | 
**Status** | [**ClusterSnapshotStatus**](ClusterSnapshotStatus.md) |  | 
**Type** | **string** | Storage backend type. | 
**ComputeNode** | Pointer to **string** | Address of the compute node that owns this snapshot. | [optional] 
**Metadata** | [**ClusterSnapshotMetadata**](ClusterSnapshotMetadata.md) |  | 
**CreatedAt** | **time.Time** | Timestamp when the snapshot was created. | 
**UpdatedAt** | **time.Time** | Timestamp when the snapshot was last updated. | 

## Methods

### NewClusterSnapshot

`func NewClusterSnapshot(id string, volume NullableString, instance NullableString, status ClusterSnapshotStatus, type_ string, metadata ClusterSnapshotMetadata, createdAt time.Time, updatedAt time.Time, ) *ClusterSnapshot`

NewClusterSnapshot instantiates a new ClusterSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterSnapshotWithDefaults

`func NewClusterSnapshotWithDefaults() *ClusterSnapshot`

NewClusterSnapshotWithDefaults instantiates a new ClusterSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ClusterSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClusterSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClusterSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ClusterSnapshot) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ClusterSnapshot) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ClusterSnapshot) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ClusterSnapshot) HasName() bool`

HasName returns a boolean if a field has been set.

### GetVolume

`func (o *ClusterSnapshot) GetVolume() string`

GetVolume returns the Volume field if non-nil, zero value otherwise.

### GetVolumeOk

`func (o *ClusterSnapshot) GetVolumeOk() (*string, bool)`

GetVolumeOk returns a tuple with the Volume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume

`func (o *ClusterSnapshot) SetVolume(v string)`

SetVolume sets Volume field to given value.


### SetVolumeNil

`func (o *ClusterSnapshot) SetVolumeNil(b bool)`

 SetVolumeNil sets the value for Volume to be an explicit nil

### UnsetVolume
`func (o *ClusterSnapshot) UnsetVolume()`

UnsetVolume ensures that no value is present for Volume, not even an explicit nil
### GetInstance

`func (o *ClusterSnapshot) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *ClusterSnapshot) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *ClusterSnapshot) SetInstance(v string)`

SetInstance sets Instance field to given value.


### SetInstanceNil

`func (o *ClusterSnapshot) SetInstanceNil(b bool)`

 SetInstanceNil sets the value for Instance to be an explicit nil

### UnsetInstance
`func (o *ClusterSnapshot) UnsetInstance()`

UnsetInstance ensures that no value is present for Instance, not even an explicit nil
### GetStatus

`func (o *ClusterSnapshot) GetStatus() ClusterSnapshotStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClusterSnapshot) GetStatusOk() (*ClusterSnapshotStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClusterSnapshot) SetStatus(v ClusterSnapshotStatus)`

SetStatus sets Status field to given value.


### GetType

`func (o *ClusterSnapshot) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ClusterSnapshot) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ClusterSnapshot) SetType(v string)`

SetType sets Type field to given value.


### GetComputeNode

`func (o *ClusterSnapshot) GetComputeNode() string`

GetComputeNode returns the ComputeNode field if non-nil, zero value otherwise.

### GetComputeNodeOk

`func (o *ClusterSnapshot) GetComputeNodeOk() (*string, bool)`

GetComputeNodeOk returns a tuple with the ComputeNode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeNode

`func (o *ClusterSnapshot) SetComputeNode(v string)`

SetComputeNode sets ComputeNode field to given value.

### HasComputeNode

`func (o *ClusterSnapshot) HasComputeNode() bool`

HasComputeNode returns a boolean if a field has been set.

### GetMetadata

`func (o *ClusterSnapshot) GetMetadata() ClusterSnapshotMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ClusterSnapshot) GetMetadataOk() (*ClusterSnapshotMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ClusterSnapshot) SetMetadata(v ClusterSnapshotMetadata)`

SetMetadata sets Metadata field to given value.


### GetCreatedAt

`func (o *ClusterSnapshot) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClusterSnapshot) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClusterSnapshot) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ClusterSnapshot) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClusterSnapshot) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClusterSnapshot) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


