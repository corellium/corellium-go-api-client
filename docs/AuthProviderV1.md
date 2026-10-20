# AuthProviderV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** | Provider name for a given provider type | [optional] 
**Identifier** | Pointer to **NullableString** | The identifier for the provider | [optional] 
**ProviderType** | Pointer to **NullableString** | Provider type | [optional] 
**Default** | Pointer to **NullableBool** | Denotes whether it&#39;s the default | [optional] 
**Label** | Pointer to **NullableString** | Provider label | [optional] 
**Enabled** | Pointer to **NullableBool** | Denotes whether they&#39;re enabled or not | [optional] 
**AuthorizationUrl** | Pointer to **NullableString** | URL for provider auth | [optional] 
**Id** | Pointer to **NullableString** | The identifier for the provider | [optional] 
**Provider** | Pointer to **NullableString** | Auth provider | [optional] 

## Methods

### NewAuthProviderV1

`func NewAuthProviderV1() *AuthProviderV1`

NewAuthProviderV1 instantiates a new AuthProviderV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthProviderV1WithDefaults

`func NewAuthProviderV1WithDefaults() *AuthProviderV1`

NewAuthProviderV1WithDefaults instantiates a new AuthProviderV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *AuthProviderV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AuthProviderV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AuthProviderV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AuthProviderV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AuthProviderV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AuthProviderV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIdentifier

`func (o *AuthProviderV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *AuthProviderV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *AuthProviderV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *AuthProviderV1) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.

### SetIdentifierNil

`func (o *AuthProviderV1) SetIdentifierNil(b bool)`

 SetIdentifierNil sets the value for Identifier to be an explicit nil

### UnsetIdentifier
`func (o *AuthProviderV1) UnsetIdentifier()`

UnsetIdentifier ensures that no value is present for Identifier, not even an explicit nil
### GetProviderType

`func (o *AuthProviderV1) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *AuthProviderV1) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *AuthProviderV1) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.

### HasProviderType

`func (o *AuthProviderV1) HasProviderType() bool`

HasProviderType returns a boolean if a field has been set.

### SetProviderTypeNil

`func (o *AuthProviderV1) SetProviderTypeNil(b bool)`

 SetProviderTypeNil sets the value for ProviderType to be an explicit nil

### UnsetProviderType
`func (o *AuthProviderV1) UnsetProviderType()`

UnsetProviderType ensures that no value is present for ProviderType, not even an explicit nil
### GetDefault

`func (o *AuthProviderV1) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *AuthProviderV1) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *AuthProviderV1) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *AuthProviderV1) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### SetDefaultNil

`func (o *AuthProviderV1) SetDefaultNil(b bool)`

 SetDefaultNil sets the value for Default to be an explicit nil

### UnsetDefault
`func (o *AuthProviderV1) UnsetDefault()`

UnsetDefault ensures that no value is present for Default, not even an explicit nil
### GetLabel

`func (o *AuthProviderV1) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AuthProviderV1) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AuthProviderV1) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AuthProviderV1) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *AuthProviderV1) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *AuthProviderV1) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetEnabled

`func (o *AuthProviderV1) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AuthProviderV1) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AuthProviderV1) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *AuthProviderV1) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### SetEnabledNil

`func (o *AuthProviderV1) SetEnabledNil(b bool)`

 SetEnabledNil sets the value for Enabled to be an explicit nil

### UnsetEnabled
`func (o *AuthProviderV1) UnsetEnabled()`

UnsetEnabled ensures that no value is present for Enabled, not even an explicit nil
### GetAuthorizationUrl

`func (o *AuthProviderV1) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *AuthProviderV1) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *AuthProviderV1) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.

### HasAuthorizationUrl

`func (o *AuthProviderV1) HasAuthorizationUrl() bool`

HasAuthorizationUrl returns a boolean if a field has been set.

### SetAuthorizationUrlNil

`func (o *AuthProviderV1) SetAuthorizationUrlNil(b bool)`

 SetAuthorizationUrlNil sets the value for AuthorizationUrl to be an explicit nil

### UnsetAuthorizationUrl
`func (o *AuthProviderV1) UnsetAuthorizationUrl()`

UnsetAuthorizationUrl ensures that no value is present for AuthorizationUrl, not even an explicit nil
### GetId

`func (o *AuthProviderV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuthProviderV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuthProviderV1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AuthProviderV1) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *AuthProviderV1) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *AuthProviderV1) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetProvider

`func (o *AuthProviderV1) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AuthProviderV1) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AuthProviderV1) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *AuthProviderV1) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *AuthProviderV1) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *AuthProviderV1) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


