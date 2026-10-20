# PatchUserBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Username. | [optional] 
**Label** | Pointer to **string** | User label (e.g. \&quot;Domain Administrator\&quot;). | [optional] 
**Email** | Pointer to **string** | User email. | [optional] 
**ClusterAdministrator** | Pointer to **bool** | Whether the user is a cluster administrator (cluster admins only). | [optional] 
**Password** | Pointer to **string** | Password (optional when using SSO). | [optional] 
**Misc** | Pointer to **map[string]interface{}** | Opaque metadata. | [optional] 
**Administrator** | Pointer to **bool** | Whether the user is a domain administrator (domain admins only). | [optional] 
**AgreedToTerms** | Pointer to **string** | Timestamp the terms were agreed to. | [optional] 
**TotpEnabled** | Pointer to **bool** | Whether two-factor authentication is enabled. | [optional] 

## Methods

### NewPatchUserBody

`func NewPatchUserBody() *PatchUserBody`

NewPatchUserBody instantiates a new PatchUserBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchUserBodyWithDefaults

`func NewPatchUserBodyWithDefaults() *PatchUserBody`

NewPatchUserBodyWithDefaults instantiates a new PatchUserBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchUserBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchUserBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchUserBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchUserBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLabel

`func (o *PatchUserBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *PatchUserBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *PatchUserBody) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *PatchUserBody) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetEmail

`func (o *PatchUserBody) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *PatchUserBody) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *PatchUserBody) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *PatchUserBody) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetClusterAdministrator

`func (o *PatchUserBody) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *PatchUserBody) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *PatchUserBody) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.

### HasClusterAdministrator

`func (o *PatchUserBody) HasClusterAdministrator() bool`

HasClusterAdministrator returns a boolean if a field has been set.

### GetPassword

`func (o *PatchUserBody) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *PatchUserBody) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *PatchUserBody) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *PatchUserBody) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetMisc

`func (o *PatchUserBody) GetMisc() map[string]interface{}`

GetMisc returns the Misc field if non-nil, zero value otherwise.

### GetMiscOk

`func (o *PatchUserBody) GetMiscOk() (*map[string]interface{}, bool)`

GetMiscOk returns a tuple with the Misc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc

`func (o *PatchUserBody) SetMisc(v map[string]interface{})`

SetMisc sets Misc field to given value.

### HasMisc

`func (o *PatchUserBody) HasMisc() bool`

HasMisc returns a boolean if a field has been set.

### GetAdministrator

`func (o *PatchUserBody) GetAdministrator() bool`

GetAdministrator returns the Administrator field if non-nil, zero value otherwise.

### GetAdministratorOk

`func (o *PatchUserBody) GetAdministratorOk() (*bool, bool)`

GetAdministratorOk returns a tuple with the Administrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdministrator

`func (o *PatchUserBody) SetAdministrator(v bool)`

SetAdministrator sets Administrator field to given value.

### HasAdministrator

`func (o *PatchUserBody) HasAdministrator() bool`

HasAdministrator returns a boolean if a field has been set.

### GetAgreedToTerms

`func (o *PatchUserBody) GetAgreedToTerms() string`

GetAgreedToTerms returns the AgreedToTerms field if non-nil, zero value otherwise.

### GetAgreedToTermsOk

`func (o *PatchUserBody) GetAgreedToTermsOk() (*string, bool)`

GetAgreedToTermsOk returns a tuple with the AgreedToTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgreedToTerms

`func (o *PatchUserBody) SetAgreedToTerms(v string)`

SetAgreedToTerms sets AgreedToTerms field to given value.

### HasAgreedToTerms

`func (o *PatchUserBody) HasAgreedToTerms() bool`

HasAgreedToTerms returns a boolean if a field has been set.

### GetTotpEnabled

`func (o *PatchUserBody) GetTotpEnabled() bool`

GetTotpEnabled returns the TotpEnabled field if non-nil, zero value otherwise.

### GetTotpEnabledOk

`func (o *PatchUserBody) GetTotpEnabledOk() (*bool, bool)`

GetTotpEnabledOk returns a tuple with the TotpEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpEnabled

`func (o *PatchUserBody) SetTotpEnabled(v bool)`

SetTotpEnabled sets TotpEnabled field to given value.

### HasTotpEnabled

`func (o *PatchUserBody) HasTotpEnabled() bool`

HasTotpEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


