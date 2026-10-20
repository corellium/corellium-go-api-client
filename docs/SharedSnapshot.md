# SharedSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharedOn** | Pointer to **time.Time** | Date of when the snapshot was first shared with member. | [optional] 
**SharedWithMember** | Pointer to **string** | The member who the snapshot was shared with. Only present in sharedWithUser. | [optional] 
**SharingType** | [**SnapshotSharingType**](SnapshotSharingType.md) |  | 
**SharedBy** | Pointer to [**SnapshotOwner**](SnapshotOwner.md) |  | [optional] 
**Id** | **string** | The snapshot identifier. | 
**Date** | **float32** | Date that the snapshot was created (UNIX epoch milliseconds). | 
**HwPac** | **float32** | Denotes whether this snapshot requires a compute node with hardware PAC enabled. | 
**Instance** | **string** | The UUID of the instance that this snapshot is of. | 
**Live** | Pointer to **bool** | Live snapshot (included state and memory). | [optional] 
**Local** | **bool** | Denotes whether the snapshot has a local storage type. | 
**Model** | Pointer to **string** | The device model. | [optional] [default to ""]
**Type** | Pointer to **string** | Device type of the instance this snapshot belongs to. | [optional] 
**Name** | **string** | The snapshot name. | 
**Status** | [**SnapshotStatus**](SnapshotStatus.md) |  | 
**Fresh** | Pointer to **bool** | Denotes whether snapshot was created immediately after the device was restored. | [optional] 
**Sharing** | Pointer to [**SnapshotSharing**](SnapshotSharing.md) |  | [optional] 

## Methods

### NewSharedSnapshot

`func NewSharedSnapshot(sharingType SnapshotSharingType, id string, date float32, hwPac float32, instance string, local bool, name string, status SnapshotStatus, ) *SharedSnapshot`

NewSharedSnapshot instantiates a new SharedSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSharedSnapshotWithDefaults

`func NewSharedSnapshotWithDefaults() *SharedSnapshot`

NewSharedSnapshotWithDefaults instantiates a new SharedSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharedOn

`func (o *SharedSnapshot) GetSharedOn() time.Time`

GetSharedOn returns the SharedOn field if non-nil, zero value otherwise.

### GetSharedOnOk

`func (o *SharedSnapshot) GetSharedOnOk() (*time.Time, bool)`

GetSharedOnOk returns a tuple with the SharedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedOn

`func (o *SharedSnapshot) SetSharedOn(v time.Time)`

SetSharedOn sets SharedOn field to given value.

### HasSharedOn

`func (o *SharedSnapshot) HasSharedOn() bool`

HasSharedOn returns a boolean if a field has been set.

### GetSharedWithMember

`func (o *SharedSnapshot) GetSharedWithMember() string`

GetSharedWithMember returns the SharedWithMember field if non-nil, zero value otherwise.

### GetSharedWithMemberOk

`func (o *SharedSnapshot) GetSharedWithMemberOk() (*string, bool)`

GetSharedWithMemberOk returns a tuple with the SharedWithMember field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedWithMember

`func (o *SharedSnapshot) SetSharedWithMember(v string)`

SetSharedWithMember sets SharedWithMember field to given value.

### HasSharedWithMember

`func (o *SharedSnapshot) HasSharedWithMember() bool`

HasSharedWithMember returns a boolean if a field has been set.

### GetSharingType

`func (o *SharedSnapshot) GetSharingType() SnapshotSharingType`

GetSharingType returns the SharingType field if non-nil, zero value otherwise.

### GetSharingTypeOk

`func (o *SharedSnapshot) GetSharingTypeOk() (*SnapshotSharingType, bool)`

GetSharingTypeOk returns a tuple with the SharingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharingType

`func (o *SharedSnapshot) SetSharingType(v SnapshotSharingType)`

SetSharingType sets SharingType field to given value.


### GetSharedBy

`func (o *SharedSnapshot) GetSharedBy() SnapshotOwner`

GetSharedBy returns the SharedBy field if non-nil, zero value otherwise.

### GetSharedByOk

`func (o *SharedSnapshot) GetSharedByOk() (*SnapshotOwner, bool)`

GetSharedByOk returns a tuple with the SharedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedBy

`func (o *SharedSnapshot) SetSharedBy(v SnapshotOwner)`

SetSharedBy sets SharedBy field to given value.

### HasSharedBy

`func (o *SharedSnapshot) HasSharedBy() bool`

HasSharedBy returns a boolean if a field has been set.

### GetId

`func (o *SharedSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SharedSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SharedSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetDate

`func (o *SharedSnapshot) GetDate() float32`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *SharedSnapshot) GetDateOk() (*float32, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *SharedSnapshot) SetDate(v float32)`

SetDate sets Date field to given value.


### GetHwPac

`func (o *SharedSnapshot) GetHwPac() float32`

GetHwPac returns the HwPac field if non-nil, zero value otherwise.

### GetHwPacOk

`func (o *SharedSnapshot) GetHwPacOk() (*float32, bool)`

GetHwPacOk returns a tuple with the HwPac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHwPac

`func (o *SharedSnapshot) SetHwPac(v float32)`

SetHwPac sets HwPac field to given value.


### GetInstance

`func (o *SharedSnapshot) GetInstance() string`

GetInstance returns the Instance field if non-nil, zero value otherwise.

### GetInstanceOk

`func (o *SharedSnapshot) GetInstanceOk() (*string, bool)`

GetInstanceOk returns a tuple with the Instance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstance

`func (o *SharedSnapshot) SetInstance(v string)`

SetInstance sets Instance field to given value.


### GetLive

`func (o *SharedSnapshot) GetLive() bool`

GetLive returns the Live field if non-nil, zero value otherwise.

### GetLiveOk

`func (o *SharedSnapshot) GetLiveOk() (*bool, bool)`

GetLiveOk returns a tuple with the Live field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLive

`func (o *SharedSnapshot) SetLive(v bool)`

SetLive sets Live field to given value.

### HasLive

`func (o *SharedSnapshot) HasLive() bool`

HasLive returns a boolean if a field has been set.

### GetLocal

`func (o *SharedSnapshot) GetLocal() bool`

GetLocal returns the Local field if non-nil, zero value otherwise.

### GetLocalOk

`func (o *SharedSnapshot) GetLocalOk() (*bool, bool)`

GetLocalOk returns a tuple with the Local field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocal

`func (o *SharedSnapshot) SetLocal(v bool)`

SetLocal sets Local field to given value.


### GetModel

`func (o *SharedSnapshot) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SharedSnapshot) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SharedSnapshot) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *SharedSnapshot) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetType

`func (o *SharedSnapshot) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SharedSnapshot) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SharedSnapshot) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SharedSnapshot) HasType() bool`

HasType returns a boolean if a field has been set.

### GetName

`func (o *SharedSnapshot) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SharedSnapshot) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SharedSnapshot) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *SharedSnapshot) GetStatus() SnapshotStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SharedSnapshot) GetStatusOk() (*SnapshotStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SharedSnapshot) SetStatus(v SnapshotStatus)`

SetStatus sets Status field to given value.


### GetFresh

`func (o *SharedSnapshot) GetFresh() bool`

GetFresh returns the Fresh field if non-nil, zero value otherwise.

### GetFreshOk

`func (o *SharedSnapshot) GetFreshOk() (*bool, bool)`

GetFreshOk returns a tuple with the Fresh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFresh

`func (o *SharedSnapshot) SetFresh(v bool)`

SetFresh sets Fresh field to given value.

### HasFresh

`func (o *SharedSnapshot) HasFresh() bool`

HasFresh returns a boolean if a field has been set.

### GetSharing

`func (o *SharedSnapshot) GetSharing() SnapshotSharing`

GetSharing returns the Sharing field if non-nil, zero value otherwise.

### GetSharingOk

`func (o *SharedSnapshot) GetSharingOk() (*SnapshotSharing, bool)`

GetSharingOk returns a tuple with the Sharing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharing

`func (o *SharedSnapshot) SetSharing(v SnapshotSharing)`

SetSharing sets Sharing field to given value.

### HasSharing

`func (o *SharedSnapshot) HasSharing() bool`

HasSharing returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


