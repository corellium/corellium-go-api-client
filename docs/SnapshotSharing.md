# SnapshotSharing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharingType** | [**SnapshotSharingType**](SnapshotSharingType.md) |  | 
**AccessCode** | Pointer to **string** | Access code of shared snapshot. | [optional] 
**SharedOn** | Pointer to **time.Time** | Date of when the snapshot was first shared with member. | [optional] 
**SharedBy** | Pointer to [**SnapshotOwner**](SnapshotOwner.md) |  | [optional] 
**Members** | Pointer to [**[]SnapshotMember**](SnapshotMember.md) | The email addresses or user ids of the members. | [optional] 

## Methods

### NewSnapshotSharing

`func NewSnapshotSharing(sharingType SnapshotSharingType, ) *SnapshotSharing`

NewSnapshotSharing instantiates a new SnapshotSharing object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotSharingWithDefaults

`func NewSnapshotSharingWithDefaults() *SnapshotSharing`

NewSnapshotSharingWithDefaults instantiates a new SnapshotSharing object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharingType

`func (o *SnapshotSharing) GetSharingType() SnapshotSharingType`

GetSharingType returns the SharingType field if non-nil, zero value otherwise.

### GetSharingTypeOk

`func (o *SnapshotSharing) GetSharingTypeOk() (*SnapshotSharingType, bool)`

GetSharingTypeOk returns a tuple with the SharingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharingType

`func (o *SnapshotSharing) SetSharingType(v SnapshotSharingType)`

SetSharingType sets SharingType field to given value.


### GetAccessCode

`func (o *SnapshotSharing) GetAccessCode() string`

GetAccessCode returns the AccessCode field if non-nil, zero value otherwise.

### GetAccessCodeOk

`func (o *SnapshotSharing) GetAccessCodeOk() (*string, bool)`

GetAccessCodeOk returns a tuple with the AccessCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCode

`func (o *SnapshotSharing) SetAccessCode(v string)`

SetAccessCode sets AccessCode field to given value.

### HasAccessCode

`func (o *SnapshotSharing) HasAccessCode() bool`

HasAccessCode returns a boolean if a field has been set.

### GetSharedOn

`func (o *SnapshotSharing) GetSharedOn() time.Time`

GetSharedOn returns the SharedOn field if non-nil, zero value otherwise.

### GetSharedOnOk

`func (o *SnapshotSharing) GetSharedOnOk() (*time.Time, bool)`

GetSharedOnOk returns a tuple with the SharedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedOn

`func (o *SnapshotSharing) SetSharedOn(v time.Time)`

SetSharedOn sets SharedOn field to given value.

### HasSharedOn

`func (o *SnapshotSharing) HasSharedOn() bool`

HasSharedOn returns a boolean if a field has been set.

### GetSharedBy

`func (o *SnapshotSharing) GetSharedBy() SnapshotOwner`

GetSharedBy returns the SharedBy field if non-nil, zero value otherwise.

### GetSharedByOk

`func (o *SnapshotSharing) GetSharedByOk() (*SnapshotOwner, bool)`

GetSharedByOk returns a tuple with the SharedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedBy

`func (o *SnapshotSharing) SetSharedBy(v SnapshotOwner)`

SetSharedBy sets SharedBy field to given value.

### HasSharedBy

`func (o *SnapshotSharing) HasSharedBy() bool`

HasSharedBy returns a boolean if a field has been set.

### GetMembers

`func (o *SnapshotSharing) GetMembers() []SnapshotMember`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *SnapshotSharing) GetMembersOk() (*[]SnapshotMember, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *SnapshotSharing) SetMembers(v []SnapshotMember)`

SetMembers sets Members field to given value.

### HasMembers

`func (o *SnapshotSharing) HasMembers() bool`

HasMembers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


