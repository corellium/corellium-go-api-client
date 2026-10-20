# SnapshotSharingV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharingType** | **string** |  | 
**SharedBy** | Pointer to [**SnapshotOwnerV1**](SnapshotOwnerV1.md) |  | [optional] 
**Members** | Pointer to [**[]SnapshotMemberV1**](SnapshotMemberV1.md) | The members who have access to the snapshot | [optional] 

## Methods

### NewSnapshotSharingV1

`func NewSnapshotSharingV1(sharingType string, ) *SnapshotSharingV1`

NewSnapshotSharingV1 instantiates a new SnapshotSharingV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotSharingV1WithDefaults

`func NewSnapshotSharingV1WithDefaults() *SnapshotSharingV1`

NewSnapshotSharingV1WithDefaults instantiates a new SnapshotSharingV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharingType

`func (o *SnapshotSharingV1) GetSharingType() string`

GetSharingType returns the SharingType field if non-nil, zero value otherwise.

### GetSharingTypeOk

`func (o *SnapshotSharingV1) GetSharingTypeOk() (*string, bool)`

GetSharingTypeOk returns a tuple with the SharingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharingType

`func (o *SnapshotSharingV1) SetSharingType(v string)`

SetSharingType sets SharingType field to given value.


### GetSharedBy

`func (o *SnapshotSharingV1) GetSharedBy() SnapshotOwnerV1`

GetSharedBy returns the SharedBy field if non-nil, zero value otherwise.

### GetSharedByOk

`func (o *SnapshotSharingV1) GetSharedByOk() (*SnapshotOwnerV1, bool)`

GetSharedByOk returns a tuple with the SharedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedBy

`func (o *SnapshotSharingV1) SetSharedBy(v SnapshotOwnerV1)`

SetSharedBy sets SharedBy field to given value.

### HasSharedBy

`func (o *SnapshotSharingV1) HasSharedBy() bool`

HasSharedBy returns a boolean if a field has been set.

### GetMembers

`func (o *SnapshotSharingV1) GetMembers() []SnapshotMemberV1`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *SnapshotSharingV1) GetMembersOk() (*[]SnapshotMemberV1, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *SnapshotSharingV1) SetMembers(v []SnapshotMemberV1)`

SetMembers sets Members field to given value.

### HasMembers

`func (o *SnapshotSharingV1) HasMembers() bool`

HasMembers returns a boolean if a field has been set.

### SetMembersNil

`func (o *SnapshotSharingV1) SetMembersNil(b bool)`

 SetMembersNil sets the value for Members to be an explicit nil

### UnsetMembers
`func (o *SnapshotSharingV1) UnsetMembers()`

UnsetMembers ensures that no value is present for Members, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


