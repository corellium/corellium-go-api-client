# SetSnapshotPermissionsBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Members** | **[]string** | The people who may use the snapshot, by email address or user ID. Used with sharing type &#x60;emailInvite&#x60;. | 

## Methods

### NewSetSnapshotPermissionsBody

`func NewSetSnapshotPermissionsBody(members []string, ) *SetSnapshotPermissionsBody`

NewSetSnapshotPermissionsBody instantiates a new SetSnapshotPermissionsBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetSnapshotPermissionsBodyWithDefaults

`func NewSetSnapshotPermissionsBodyWithDefaults() *SetSnapshotPermissionsBody`

NewSetSnapshotPermissionsBodyWithDefaults instantiates a new SetSnapshotPermissionsBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMembers

`func (o *SetSnapshotPermissionsBody) GetMembers() []string`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *SetSnapshotPermissionsBody) GetMembersOk() (*[]string, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *SetSnapshotPermissionsBody) SetMembers(v []string)`

SetMembers sets Members field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


