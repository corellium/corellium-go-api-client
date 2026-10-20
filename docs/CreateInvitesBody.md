# CreateInvitesBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **[]string** | Emails to invite. | 
**Resend** | Pointer to **bool** | Resend the invite if it already exists. | [optional] 
**Settings** | Pointer to [**InviteSettings**](InviteSettings.md) | Settings applied to the created invites. | [optional] 

## Methods

### NewCreateInvitesBody

`func NewCreateInvitesBody(email []string, ) *CreateInvitesBody`

NewCreateInvitesBody instantiates a new CreateInvitesBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInvitesBodyWithDefaults

`func NewCreateInvitesBodyWithDefaults() *CreateInvitesBody`

NewCreateInvitesBodyWithDefaults instantiates a new CreateInvitesBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CreateInvitesBody) GetEmail() []string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateInvitesBody) GetEmailOk() (*[]string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateInvitesBody) SetEmail(v []string)`

SetEmail sets Email field to given value.


### GetResend

`func (o *CreateInvitesBody) GetResend() bool`

GetResend returns the Resend field if non-nil, zero value otherwise.

### GetResendOk

`func (o *CreateInvitesBody) GetResendOk() (*bool, bool)`

GetResendOk returns a tuple with the Resend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResend

`func (o *CreateInvitesBody) SetResend(v bool)`

SetResend sets Resend field to given value.

### HasResend

`func (o *CreateInvitesBody) HasResend() bool`

HasResend returns a boolean if a field has been set.

### GetSettings

`func (o *CreateInvitesBody) GetSettings() InviteSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *CreateInvitesBody) GetSettingsOk() (*InviteSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *CreateInvitesBody) SetSettings(v InviteSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *CreateInvitesBody) HasSettings() bool`

HasSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


