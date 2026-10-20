# ClusterSnapshotStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Task** | Pointer to **string** | Current task being performed on the snapshot. | [optional] 
**Created** | Pointer to **bool** | Whether the snapshot has been successfully created. | [optional] 

## Methods

### NewClusterSnapshotStatus

`func NewClusterSnapshotStatus() *ClusterSnapshotStatus`

NewClusterSnapshotStatus instantiates a new ClusterSnapshotStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterSnapshotStatusWithDefaults

`func NewClusterSnapshotStatusWithDefaults() *ClusterSnapshotStatus`

NewClusterSnapshotStatusWithDefaults instantiates a new ClusterSnapshotStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTask

`func (o *ClusterSnapshotStatus) GetTask() string`

GetTask returns the Task field if non-nil, zero value otherwise.

### GetTaskOk

`func (o *ClusterSnapshotStatus) GetTaskOk() (*string, bool)`

GetTaskOk returns a tuple with the Task field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTask

`func (o *ClusterSnapshotStatus) SetTask(v string)`

SetTask sets Task field to given value.

### HasTask

`func (o *ClusterSnapshotStatus) HasTask() bool`

HasTask returns a boolean if a field has been set.

### GetCreated

`func (o *ClusterSnapshotStatus) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *ClusterSnapshotStatus) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *ClusterSnapshotStatus) SetCreated(v bool)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *ClusterSnapshotStatus) HasCreated() bool`

HasCreated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


