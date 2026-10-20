# EnsureDomainSettingsBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Fqdn** | Pointer to **string** | Fully qualified domain name. | [optional] 
**Name** | Pointer to **string** | Domain name. | [optional] 
**Cores** | Pointer to **float32** | Core quota. | [optional] 
**Password** | Pointer to **string** | Admin user password. | [optional] 
**PasswordIfEmpty** | Pointer to **string** | Admin password (only applied if no password is currently set). | [optional] 
**Config** | Pointer to [**DomainConfigInput**](DomainConfigInput.md) |  | [optional] 
**AdminUser** | Pointer to [**EnsureDomainSettingsBodyAdminUser**](EnsureDomainSettingsBodyAdminUser.md) |  | [optional] 

## Methods

### NewEnsureDomainSettingsBody

`func NewEnsureDomainSettingsBody() *EnsureDomainSettingsBody`

NewEnsureDomainSettingsBody instantiates a new EnsureDomainSettingsBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEnsureDomainSettingsBodyWithDefaults

`func NewEnsureDomainSettingsBodyWithDefaults() *EnsureDomainSettingsBody`

NewEnsureDomainSettingsBodyWithDefaults instantiates a new EnsureDomainSettingsBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFqdn

`func (o *EnsureDomainSettingsBody) GetFqdn() string`

GetFqdn returns the Fqdn field if non-nil, zero value otherwise.

### GetFqdnOk

`func (o *EnsureDomainSettingsBody) GetFqdnOk() (*string, bool)`

GetFqdnOk returns a tuple with the Fqdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFqdn

`func (o *EnsureDomainSettingsBody) SetFqdn(v string)`

SetFqdn sets Fqdn field to given value.

### HasFqdn

`func (o *EnsureDomainSettingsBody) HasFqdn() bool`

HasFqdn returns a boolean if a field has been set.

### GetName

`func (o *EnsureDomainSettingsBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *EnsureDomainSettingsBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *EnsureDomainSettingsBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *EnsureDomainSettingsBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCores

`func (o *EnsureDomainSettingsBody) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *EnsureDomainSettingsBody) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *EnsureDomainSettingsBody) SetCores(v float32)`

SetCores sets Cores field to given value.

### HasCores

`func (o *EnsureDomainSettingsBody) HasCores() bool`

HasCores returns a boolean if a field has been set.

### GetPassword

`func (o *EnsureDomainSettingsBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *EnsureDomainSettingsBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *EnsureDomainSettingsBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *EnsureDomainSettingsBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPasswordIfEmpty

`func (o *EnsureDomainSettingsBody) GetPasswordIfEmpty() string`

GetPasswordIfEmpty returns the PasswordIfEmpty field if non-nil, zero value otherwise.

### GetPasswordIfEmptyOk

`func (o *EnsureDomainSettingsBody) GetPasswordIfEmptyOk() (*string, bool)`

GetPasswordIfEmptyOk returns a tuple with the PasswordIfEmpty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordIfEmpty

`func (o *EnsureDomainSettingsBody) SetPasswordIfEmpty(v string)`

SetPasswordIfEmpty sets PasswordIfEmpty field to given value.

### HasPasswordIfEmpty

`func (o *EnsureDomainSettingsBody) HasPasswordIfEmpty() bool`

HasPasswordIfEmpty returns a boolean if a field has been set.

### GetConfig

`func (o *EnsureDomainSettingsBody) GetConfig() DomainConfigInput`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *EnsureDomainSettingsBody) GetConfigOk() (*DomainConfigInput, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *EnsureDomainSettingsBody) SetConfig(v DomainConfigInput)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *EnsureDomainSettingsBody) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetAdminUser

`func (o *EnsureDomainSettingsBody) GetAdminUser() EnsureDomainSettingsBodyAdminUser`

GetAdminUser returns the AdminUser field if non-nil, zero value otherwise.

### GetAdminUserOk

`func (o *EnsureDomainSettingsBody) GetAdminUserOk() (*EnsureDomainSettingsBodyAdminUser, bool)`

GetAdminUserOk returns a tuple with the AdminUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminUser

`func (o *EnsureDomainSettingsBody) SetAdminUser(v EnsureDomainSettingsBodyAdminUser)`

SetAdminUser sets AdminUser field to given value.

### HasAdminUser

`func (o *EnsureDomainSettingsBody) HasAdminUser() bool`

HasAdminUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


