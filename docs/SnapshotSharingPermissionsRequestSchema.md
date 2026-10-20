# SnapshotSharingPermissionsRequestSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** | Whether snapshot sharing is enabled. | [optional] 
**PublicLink** | Pointer to **bool** | Whether public link access is enabled. | [optional] [default to true]
**DomainRestrictedLink** | Pointer to **bool** | Whether domain-restricted link access is enabled. | [optional] [default to true]
**PasswordPublicLink** | Pointer to **bool** | Whether password-protected public link access is enabled. | [optional] [default to true]
**EmailInvite** | Pointer to **bool** | Whether email invite access is enabled. | [optional] [default to true]

## Methods

### NewSnapshotSharingPermissionsRequestSchema

`func NewSnapshotSharingPermissionsRequestSchema() *SnapshotSharingPermissionsRequestSchema`

NewSnapshotSharingPermissionsRequestSchema instantiates a new SnapshotSharingPermissionsRequestSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSnapshotSharingPermissionsRequestSchemaWithDefaults

`func NewSnapshotSharingPermissionsRequestSchemaWithDefaults() *SnapshotSharingPermissionsRequestSchema`

NewSnapshotSharingPermissionsRequestSchemaWithDefaults instantiates a new SnapshotSharingPermissionsRequestSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *SnapshotSharingPermissionsRequestSchema) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *SnapshotSharingPermissionsRequestSchema) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *SnapshotSharingPermissionsRequestSchema) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *SnapshotSharingPermissionsRequestSchema) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) GetPublicLink() bool`

GetPublicLink returns the PublicLink field if non-nil, zero value otherwise.

### GetPublicLinkOk

`func (o *SnapshotSharingPermissionsRequestSchema) GetPublicLinkOk() (*bool, bool)`

GetPublicLinkOk returns a tuple with the PublicLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) SetPublicLink(v bool)`

SetPublicLink sets PublicLink field to given value.

### HasPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) HasPublicLink() bool`

HasPublicLink returns a boolean if a field has been set.

### GetDomainRestrictedLink

`func (o *SnapshotSharingPermissionsRequestSchema) GetDomainRestrictedLink() bool`

GetDomainRestrictedLink returns the DomainRestrictedLink field if non-nil, zero value otherwise.

### GetDomainRestrictedLinkOk

`func (o *SnapshotSharingPermissionsRequestSchema) GetDomainRestrictedLinkOk() (*bool, bool)`

GetDomainRestrictedLinkOk returns a tuple with the DomainRestrictedLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainRestrictedLink

`func (o *SnapshotSharingPermissionsRequestSchema) SetDomainRestrictedLink(v bool)`

SetDomainRestrictedLink sets DomainRestrictedLink field to given value.

### HasDomainRestrictedLink

`func (o *SnapshotSharingPermissionsRequestSchema) HasDomainRestrictedLink() bool`

HasDomainRestrictedLink returns a boolean if a field has been set.

### GetPasswordPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) GetPasswordPublicLink() bool`

GetPasswordPublicLink returns the PasswordPublicLink field if non-nil, zero value otherwise.

### GetPasswordPublicLinkOk

`func (o *SnapshotSharingPermissionsRequestSchema) GetPasswordPublicLinkOk() (*bool, bool)`

GetPasswordPublicLinkOk returns a tuple with the PasswordPublicLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) SetPasswordPublicLink(v bool)`

SetPasswordPublicLink sets PasswordPublicLink field to given value.

### HasPasswordPublicLink

`func (o *SnapshotSharingPermissionsRequestSchema) HasPasswordPublicLink() bool`

HasPasswordPublicLink returns a boolean if a field has been set.

### GetEmailInvite

`func (o *SnapshotSharingPermissionsRequestSchema) GetEmailInvite() bool`

GetEmailInvite returns the EmailInvite field if non-nil, zero value otherwise.

### GetEmailInviteOk

`func (o *SnapshotSharingPermissionsRequestSchema) GetEmailInviteOk() (*bool, bool)`

GetEmailInviteOk returns a tuple with the EmailInvite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailInvite

`func (o *SnapshotSharingPermissionsRequestSchema) SetEmailInvite(v bool)`

SetEmailInvite sets EmailInvite field to given value.

### HasEmailInvite

`func (o *SnapshotSharingPermissionsRequestSchema) HasEmailInvite() bool`

HasEmailInvite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


