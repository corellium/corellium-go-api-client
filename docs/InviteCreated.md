# InviteCreated

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** | Invite ID | [optional] 
**Email** | Pointer to **NullableString** | Invited email address | [optional] 
**Settings** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewInviteCreated

`func NewInviteCreated() *InviteCreated`

NewInviteCreated instantiates a new InviteCreated object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteCreatedWithDefaults

`func NewInviteCreatedWithDefaults() *InviteCreated`

NewInviteCreatedWithDefaults instantiates a new InviteCreated object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InviteCreated) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InviteCreated) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InviteCreated) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InviteCreated) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *InviteCreated) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *InviteCreated) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetEmail

`func (o *InviteCreated) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *InviteCreated) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *InviteCreated) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *InviteCreated) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *InviteCreated) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *InviteCreated) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetSettings

`func (o *InviteCreated) GetSettings() map[string]interface{}`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *InviteCreated) GetSettingsOk() (*map[string]interface{}, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *InviteCreated) SetSettings(v map[string]interface{})`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *InviteCreated) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### SetSettingsNil

`func (o *InviteCreated) SetSettingsNil(b bool)`

 SetSettingsNil sets the value for Settings to be an explicit nil

### UnsetSettings
`func (o *InviteCreated) UnsetSettings()`

UnsetSettings ensures that no value is present for Settings, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


