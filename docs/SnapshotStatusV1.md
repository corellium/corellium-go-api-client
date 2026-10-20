# SnapshotStatusV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Task** | Pointer to **NullableString** | The current task being performed on the snapshot | [optional] 
**Created** | Pointer to **NullableBool** | Indicates if the snapshot has been successfully created | [optional] 

## Methods

### NewSnapshotStatusV1

`func NewSnapshotStatusV1() *SnapshotStatusV1`

NewSnapshotStatusV1 instantiates a new SnapshotStatusV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotStatusV1WithDefaults

`func NewSnapshotStatusV1WithDefaults() *SnapshotStatusV1`

NewSnapshotStatusV1WithDefaults instantiates a new SnapshotStatusV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTask

`func (o *SnapshotStatusV1) GetTask() string`

GetTask returns the Task field if non-nil, zero value otherwise.

### GetTaskOk

`func (o *SnapshotStatusV1) GetTaskOk() (*string, bool)`

GetTaskOk returns a tuple with the Task field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTask

`func (o *SnapshotStatusV1) SetTask(v string)`

SetTask sets Task field to given value.

### HasTask

`func (o *SnapshotStatusV1) HasTask() bool`

HasTask returns a boolean if a field has been set.

### SetTaskNil

`func (o *SnapshotStatusV1) SetTaskNil(b bool)`

 SetTaskNil sets the value for Task to be an explicit nil

### UnsetTask
`func (o *SnapshotStatusV1) UnsetTask()`

UnsetTask ensures that no value is present for Task, not even an explicit nil
### GetCreated

`func (o *SnapshotStatusV1) GetCreated() bool`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *SnapshotStatusV1) GetCreatedOk() (*bool, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *SnapshotStatusV1) SetCreated(v bool)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *SnapshotStatusV1) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### SetCreatedNil

`func (o *SnapshotStatusV1) SetCreatedNil(b bool)`

 SetCreatedNil sets the value for Created to be an explicit nil

### UnsetCreated
`func (o *SnapshotStatusV1) UnsetCreated()`

UnsetCreated ensures that no value is present for Created, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


