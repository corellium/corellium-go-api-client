# SnapshotMember

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | The email of the member. | 
**InviteSentAt** | **NullableTime** | The date when the invite was sent. | 
**SharedOn** | Pointer to **time.Time** | Date of when the snapshot was first shared with member. | [optional] 
**UserId** | Pointer to **NullableString** | The member&#39;s user ID. | [optional] 
**Name** | Pointer to **NullableString** | The user&#39;s label or name. | [optional] 

## Methods

### NewSnapshotMember

`func NewSnapshotMember(email string, inviteSentAt NullableTime, ) *SnapshotMember`

NewSnapshotMember instantiates a new SnapshotMember object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotMemberWithDefaults

`func NewSnapshotMemberWithDefaults() *SnapshotMember`

NewSnapshotMemberWithDefaults instantiates a new SnapshotMember object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *SnapshotMember) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SnapshotMember) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SnapshotMember) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetInviteSentAt

`func (o *SnapshotMember) GetInviteSentAt() time.Time`

GetInviteSentAt returns the InviteSentAt field if non-nil, zero value otherwise.

### GetInviteSentAtOk

`func (o *SnapshotMember) GetInviteSentAtOk() (*time.Time, bool)`

GetInviteSentAtOk returns a tuple with the InviteSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteSentAt

`func (o *SnapshotMember) SetInviteSentAt(v time.Time)`

SetInviteSentAt sets InviteSentAt field to given value.


### SetInviteSentAtNil

`func (o *SnapshotMember) SetInviteSentAtNil(b bool)`

 SetInviteSentAtNil sets the value for InviteSentAt to be an explicit nil

### UnsetInviteSentAt
`func (o *SnapshotMember) UnsetInviteSentAt()`

UnsetInviteSentAt ensures that no value is present for InviteSentAt, not even an explicit nil
### GetSharedOn

`func (o *SnapshotMember) GetSharedOn() time.Time`

GetSharedOn returns the SharedOn field if non-nil, zero value otherwise.

### GetSharedOnOk

`func (o *SnapshotMember) GetSharedOnOk() (*time.Time, bool)`

GetSharedOnOk returns a tuple with the SharedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedOn

`func (o *SnapshotMember) SetSharedOn(v time.Time)`

SetSharedOn sets SharedOn field to given value.

### HasSharedOn

`func (o *SnapshotMember) HasSharedOn() bool`

HasSharedOn returns a boolean if a field has been set.

### GetUserId

`func (o *SnapshotMember) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SnapshotMember) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SnapshotMember) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *SnapshotMember) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *SnapshotMember) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *SnapshotMember) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetName

`func (o *SnapshotMember) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SnapshotMember) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SnapshotMember) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SnapshotMember) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *SnapshotMember) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *SnapshotMember) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


