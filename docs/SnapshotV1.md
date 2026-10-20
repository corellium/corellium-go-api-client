# SnapshotV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Snapshot ID | 
**Name** | **string** | Snapshot name | 
**Instance** | **string** | Instance that this snapshot is of | 
**Status** | [**SnapshotStatusV1**](SnapshotStatusV1.md) |  | 
**Date** | **float32** | UNIX Date that the snapshot was created | 
**Fresh** | **bool** |  | 
**Live** | **bool** | Live snapshot (included state and memory) | 
**Local** | **bool** |  | 
**Model** | Pointer to **NullableString** | The device model | [optional] 
**Sharing** | Pointer to [**SnapshotSharingV1**](SnapshotSharingV1.md) |  | [optional] 

## Methods

### NewSnapshotV1

`func NewSnapshotV1(id string, name string, instance string, status SnapshotStatusV1, date float32, fresh bool, live bool, local bool, ) *SnapshotV1`

NewSnapshotV1 instantiates a new SnapshotV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotV1WithDefaults

`func NewSnapshotV1WithDefaults() *SnapshotV1`

NewSnapshotV1WithDefaults instantiates a new SnapshotV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SnapshotV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SnapshotV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SnapshotV1) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *SnapshotV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SnapshotV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SnapshotV1) SetName(v string)`

SetName sets Name field to given value.


### GetInstance

`func (o *SnapshotV1) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *SnapshotV1) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *SnapshotV1) SetInstance(v string)`

SetInstance sets Instance field to given value.


### GetStatus

`func (o *SnapshotV1) GetStatus() SnapshotStatusV1`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SnapshotV1) GetStatusOk() (*SnapshotStatusV1, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SnapshotV1) SetStatus(v SnapshotStatusV1)`

SetStatus sets Status field to given value.


### GetDate

`func (o *SnapshotV1) GetDate() float32`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *SnapshotV1) GetDateOk() (*float32, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *SnapshotV1) SetDate(v float32)`

SetDate sets Date field to given value.


### GetFresh

`func (o *SnapshotV1) GetFresh() bool`

GetFresh returns the Fresh field if non-nil, zero value otherwise.

### GetFreshOk

`func (o *SnapshotV1) GetFreshOk() (*bool, bool)`

GetFreshOk returns a tuple with the Fresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFresh

`func (o *SnapshotV1) SetFresh(v bool)`

SetFresh sets Fresh field to given value.


### GetLive

`func (o *SnapshotV1) GetLive() bool`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *SnapshotV1) GetLiveOk() (*bool, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *SnapshotV1) SetLive(v bool)`

SetLive sets Live field to given value.


### GetLocal

`func (o *SnapshotV1) GetLocal() bool`

GetLocal returns the Local field if non-nil, zero value otherwise.

### GetLocalOk

`func (o *SnapshotV1) GetLocalOk() (*bool, bool)`

GetLocalOk returns a tuple with the Local field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocal

`func (o *SnapshotV1) SetLocal(v bool)`

SetLocal sets Local field to given value.


### GetModel

`func (o *SnapshotV1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SnapshotV1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SnapshotV1) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *SnapshotV1) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *SnapshotV1) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *SnapshotV1) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSharing

`func (o *SnapshotV1) GetSharing() SnapshotSharingV1`

GetSharing returns the Sharing field if non-nil, zero value otherwise.

### GetSharingOk

`func (o *SnapshotV1) GetSharingOk() (*SnapshotSharingV1, bool)`

GetSharingOk returns a tuple with the Sharing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharing

`func (o *SnapshotV1) SetSharing(v SnapshotSharingV1)`

SetSharing sets Sharing field to given value.

### HasSharing

`func (o *SnapshotV1) HasSharing() bool`

HasSharing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


