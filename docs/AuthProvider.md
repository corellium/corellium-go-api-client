# AuthProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Provider identifier. | 
**ProviderType** | **string** | Provider type (e.g. database, open-id-connect). | 
**Enabled** | **bool** | Whether the provider is enabled. | 
**Default** | **bool** | Whether this is the default provider. | 
**Label** | **NullableString** | Human-readable provider label. | 
**Name** | **string** | Provider display name. | 
**AuthorizationUrl** | **string** | Relative authorization URL for the provider. | 

## Methods

### NewAuthProvider

`func NewAuthProvider(identifier string, providerType string, enabled bool, default_ bool, label NullableString, name string, authorizationUrl string, ) *AuthProvider`

NewAuthProvider instantiates a new AuthProvider object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthProviderWithDefaults

`func NewAuthProviderWithDefaults() *AuthProvider`

NewAuthProviderWithDefaults instantiates a new AuthProvider object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *AuthProvider) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *AuthProvider) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *AuthProvider) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetProviderType

`func (o *AuthProvider) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *AuthProvider) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *AuthProvider) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetEnabled

`func (o *AuthProvider) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AuthProvider) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AuthProvider) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetDefault

`func (o *AuthProvider) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *AuthProvider) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *AuthProvider) SetDefault(v bool)`

SetDefault sets Default field to given value.


### GetLabel

`func (o *AuthProvider) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AuthProvider) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AuthProvider) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *AuthProvider) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *AuthProvider) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetName

`func (o *AuthProvider) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AuthProvider) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AuthProvider) SetName(v string)`

SetName sets Name field to given value.


### GetAuthorizationUrl

`func (o *AuthProvider) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *AuthProvider) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *AuthProvider) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


