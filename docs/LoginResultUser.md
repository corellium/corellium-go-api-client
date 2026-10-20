# LoginResultUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | User identifier. | 
**Name** | **NullableString** | Username. | 
**Label** | **NullableString** | Display name. | 
**Email** | **NullableString** | Email address. | 
**ClusterAdministrator** | **bool** | Whether the user is a cluster administrator. | 
**AgreedToTerms** | Pointer to **NullableString** | When the user last agreed to the terms of service. | [optional] 
**FederatedUserId** | Pointer to **NullableString** | Subject of the linked SSO credential, if any. | [optional] 
**IntercomHMAC** | **string** | HMAC used for Intercom identity verification. | 
**Misc** | **map[string]interface{}** | User metadata. API token bookkeeping only — the token itself is never returned. | 

## Methods

### NewLoginResultUser

`func NewLoginResultUser(id string, name NullableString, label NullableString, email NullableString, clusterAdministrator bool, intercomHMAC string, misc map[string]interface{}, ) *LoginResultUser`

NewLoginResultUser instantiates a new LoginResultUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultUserWithDefaults

`func NewLoginResultUserWithDefaults() *LoginResultUser`

NewLoginResultUserWithDefaults instantiates a new LoginResultUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LoginResultUser) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LoginResultUser) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LoginResultUser) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *LoginResultUser) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LoginResultUser) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LoginResultUser) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *LoginResultUser) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *LoginResultUser) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetLabel

`func (o *LoginResultUser) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *LoginResultUser) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *LoginResultUser) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *LoginResultUser) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *LoginResultUser) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetEmail

`func (o *LoginResultUser) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *LoginResultUser) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *LoginResultUser) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *LoginResultUser) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *LoginResultUser) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetClusterAdministrator

`func (o *LoginResultUser) GetClusterAdministrator() bool`

GetClusterAdministrator returns the ClusterAdministrator field if non-nil, zero value otherwise.

### GetClusterAdministratorOk

`func (o *LoginResultUser) GetClusterAdministratorOk() (*bool, bool)`

GetClusterAdministratorOk returns a tuple with the ClusterAdministrator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterAdministrator

`func (o *LoginResultUser) SetClusterAdministrator(v bool)`

SetClusterAdministrator sets ClusterAdministrator field to given value.


### GetAgreedToTerms

`func (o *LoginResultUser) GetAgreedToTerms() string`

GetAgreedToTerms returns the AgreedToTerms field if non-nil, zero value otherwise.

### GetAgreedToTermsOk

`func (o *LoginResultUser) GetAgreedToTermsOk() (*string, bool)`

GetAgreedToTermsOk returns a tuple with the AgreedToTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgreedToTerms

`func (o *LoginResultUser) SetAgreedToTerms(v string)`

SetAgreedToTerms sets AgreedToTerms field to given value.

### HasAgreedToTerms

`func (o *LoginResultUser) HasAgreedToTerms() bool`

HasAgreedToTerms returns a boolean if a field has been set.

### SetAgreedToTermsNil

`func (o *LoginResultUser) SetAgreedToTermsNil(b bool)`

 SetAgreedToTermsNil sets the value for AgreedToTerms to be an explicit nil

### UnsetAgreedToTerms
`func (o *LoginResultUser) UnsetAgreedToTerms()`

UnsetAgreedToTerms ensures that no value is present for AgreedToTerms, not even an explicit nil
### GetFederatedUserId

`func (o *LoginResultUser) GetFederatedUserId() string`

GetFederatedUserId returns the FederatedUserId field if non-nil, zero value otherwise.

### GetFederatedUserIdOk

`func (o *LoginResultUser) GetFederatedUserIdOk() (*string, bool)`

GetFederatedUserIdOk returns a tuple with the FederatedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFederatedUserId

`func (o *LoginResultUser) SetFederatedUserId(v string)`

SetFederatedUserId sets FederatedUserId field to given value.

### HasFederatedUserId

`func (o *LoginResultUser) HasFederatedUserId() bool`

HasFederatedUserId returns a boolean if a field has been set.

### SetFederatedUserIdNil

`func (o *LoginResultUser) SetFederatedUserIdNil(b bool)`

 SetFederatedUserIdNil sets the value for FederatedUserId to be an explicit nil

### UnsetFederatedUserId
`func (o *LoginResultUser) UnsetFederatedUserId()`

UnsetFederatedUserId ensures that no value is present for FederatedUserId, not even an explicit nil
### GetIntercomHMAC

`func (o *LoginResultUser) GetIntercomHMAC() string`

GetIntercomHMAC returns the IntercomHMAC field if non-nil, zero value otherwise.

### GetIntercomHMACOk

`func (o *LoginResultUser) GetIntercomHMACOk() (*string, bool)`

GetIntercomHMACOk returns a tuple with the IntercomHMAC field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercomHMAC

`func (o *LoginResultUser) SetIntercomHMAC(v string)`

SetIntercomHMAC sets IntercomHMAC field to given value.


### GetMisc

`func (o *LoginResultUser) GetMisc() map[string]interface{}`

GetMisc returns the Misc field if non-nil, zero value otherwise.

### GetMiscOk

`func (o *LoginResultUser) GetMiscOk() (*map[string]interface{}, bool)`

GetMiscOk returns a tuple with the Misc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMisc

`func (o *LoginResultUser) SetMisc(v map[string]interface{})`

SetMisc sets Misc field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


