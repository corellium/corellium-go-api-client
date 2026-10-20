# ConfigAuthProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Provider name for a given provider type. | 
**ProviderType** | **string** | Provider type. | 
**Default** | **bool** | Denotes whether or not this is the default auth provider. | 
**Label** | **string** | Provider label. | 
**Enabled** | **bool** | Denotes whether they&#39;re enabled or not. | 
**AuthorizationUrl** | **string** | URL for provider auth. | 
**Identifier** | **string** | Provider identifier. | 
**Provider** | **string** | Auth provider. | 

## Methods

### NewConfigAuthProvider

`func NewConfigAuthProvider(name string, providerType string, default_ bool, label string, enabled bool, authorizationUrl string, identifier string, provider string, ) *ConfigAuthProvider`

NewConfigAuthProvider instantiates a new ConfigAuthProvider object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigAuthProviderWithDefaults

`func NewConfigAuthProviderWithDefaults() *ConfigAuthProvider`

NewConfigAuthProviderWithDefaults instantiates a new ConfigAuthProvider object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ConfigAuthProvider) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConfigAuthProvider) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConfigAuthProvider) SetName(v string)`

SetName sets Name field to given value.


### GetProviderType

`func (o *ConfigAuthProvider) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *ConfigAuthProvider) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *ConfigAuthProvider) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetDefault

`func (o *ConfigAuthProvider) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ConfigAuthProvider) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ConfigAuthProvider) SetDefault(v bool)`

SetDefault sets Default field to given value.


### GetLabel

`func (o *ConfigAuthProvider) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ConfigAuthProvider) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ConfigAuthProvider) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetEnabled

`func (o *ConfigAuthProvider) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ConfigAuthProvider) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ConfigAuthProvider) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetAuthorizationUrl

`func (o *ConfigAuthProvider) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *ConfigAuthProvider) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *ConfigAuthProvider) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.


### GetIdentifier

`func (o *ConfigAuthProvider) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *ConfigAuthProvider) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *ConfigAuthProvider) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetProvider

`func (o *ConfigAuthProvider) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ConfigAuthProvider) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ConfigAuthProvider) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


