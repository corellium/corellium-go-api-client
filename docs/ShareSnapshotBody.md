# ShareSnapshotBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SharingType** | [**SnapshotSharingType**](SnapshotSharingType.md) |  | 
**Password** | Pointer to **NullableString** | Password to require from anyone accepting the snapshot. Required when sharingType is passwordPublicLink, and ignored for every other sharing type. Never returned by the API once set. | [optional] 

## Methods

### NewShareSnapshotBody

`func NewShareSnapshotBody(sharingType SnapshotSharingType, ) *ShareSnapshotBody`

NewShareSnapshotBody instantiates a new ShareSnapshotBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShareSnapshotBodyWithDefaults

`func NewShareSnapshotBodyWithDefaults() *ShareSnapshotBody`

NewShareSnapshotBodyWithDefaults instantiates a new ShareSnapshotBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSharingType

`func (o *ShareSnapshotBody) GetSharingType() SnapshotSharingType`

GetSharingType returns the SharingType field if non-nil, zero value otherwise.

### GetSharingTypeOk

`func (o *ShareSnapshotBody) GetSharingTypeOk() (*SnapshotSharingType, bool)`

GetSharingTypeOk returns a tuple with the SharingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharingType

`func (o *ShareSnapshotBody) SetSharingType(v SnapshotSharingType)`

SetSharingType sets SharingType field to given value.


### GetPassword

`func (o *ShareSnapshotBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ShareSnapshotBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ShareSnapshotBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *ShareSnapshotBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *ShareSnapshotBody) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *ShareSnapshotBody) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


