# SnapshotMemberV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | The email of the member | 
**InviteSentAt** | **float32** | The date when the invite was sent | 
**SharedOn** | **float32** | UNIX Date of when the snapshot was first shared with member | 
**UserId** | Pointer to **NullableString** | The member&#39;s user ID | [optional] 
**Label** | Pointer to **NullableString** | The user&#39;s label or name | [optional] 

## Methods

### NewSnapshotMemberV1

`func NewSnapshotMemberV1(email string, inviteSentAt float32, sharedOn float32, ) *SnapshotMemberV1`

NewSnapshotMemberV1 instantiates a new SnapshotMemberV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotMemberV1WithDefaults

`func NewSnapshotMemberV1WithDefaults() *SnapshotMemberV1`

NewSnapshotMemberV1WithDefaults instantiates a new SnapshotMemberV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *SnapshotMemberV1) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SnapshotMemberV1) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SnapshotMemberV1) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetInviteSentAt

`func (o *SnapshotMemberV1) GetInviteSentAt() float32`

GetInviteSentAt returns the InviteSentAt field if non-nil, zero value otherwise.

### GetInviteSentAtOk

`func (o *SnapshotMemberV1) GetInviteSentAtOk() (*float32, bool)`

GetInviteSentAtOk returns a tuple with the InviteSentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInviteSentAt

`func (o *SnapshotMemberV1) SetInviteSentAt(v float32)`

SetInviteSentAt sets InviteSentAt field to given value.


### GetSharedOn

`func (o *SnapshotMemberV1) GetSharedOn() float32`

GetSharedOn returns the SharedOn field if non-nil, zero value otherwise.

### GetSharedOnOk

`func (o *SnapshotMemberV1) GetSharedOnOk() (*float32, bool)`

GetSharedOnOk returns a tuple with the SharedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedOn

`func (o *SnapshotMemberV1) SetSharedOn(v float32)`

SetSharedOn sets SharedOn field to given value.


### GetUserId

`func (o *SnapshotMemberV1) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *SnapshotMemberV1) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *SnapshotMemberV1) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *SnapshotMemberV1) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *SnapshotMemberV1) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *SnapshotMemberV1) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetLabel

`func (o *SnapshotMemberV1) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SnapshotMemberV1) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SnapshotMemberV1) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *SnapshotMemberV1) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *SnapshotMemberV1) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *SnapshotMemberV1) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


