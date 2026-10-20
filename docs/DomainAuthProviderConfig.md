# DomainAuthProviderConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentityProviderConfig** | [**SamlIdentityProviderConfig**](SamlIdentityProviderConfig.md) |  | 
**ServiceProviderConfig** | Pointer to [**SamlServiceProviderConfig**](SamlServiceProviderConfig.md) |  | [optional] 
**UserAttributeMapping** | Pointer to [**LdapUserAttributeMapping**](LdapUserAttributeMapping.md) |  | [optional] 
**GroupMapping** | Pointer to [**[]SamlGroupMapping**](SamlGroupMapping.md) |  | [optional] 
**DiscoveryUrl** | **string** | Service Discovery URL. | 
**ClientId** | **string** | Service Client ID. | 
**ClientSecret** | **string** | Service Client Secret. | 
**InvitedOnly** | Pointer to **bool** | Only accept individuals with invitations. | [optional] 
**ServerConnectionDetails** | [**LdapServerConnectionDetails**](LdapServerConnectionDetails.md) |  | 
**AuthenticationCredentials** | [**LdapAuthenticationCredentials**](LdapAuthenticationCredentials.md) |  | 
**UserSearchConfiguration** | [**LdapUserSearchConfiguration**](LdapUserSearchConfiguration.md) |  | 
**GroupSearchConfiguration** | Pointer to [**[]LdapGroupSearchConfiguration**](LdapGroupSearchConfiguration.md) |  | [optional] 

## Methods

### NewDomainAuthProviderConfig

`func NewDomainAuthProviderConfig(identityProviderConfig SamlIdentityProviderConfig, discoveryUrl string, clientId string, clientSecret string, serverConnectionDetails LdapServerConnectionDetails, authenticationCredentials LdapAuthenticationCredentials, userSearchConfiguration LdapUserSearchConfiguration, ) *DomainAuthProviderConfig`

NewDomainAuthProviderConfig instantiates a new DomainAuthProviderConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainAuthProviderConfigWithDefaults

`func NewDomainAuthProviderConfigWithDefaults() *DomainAuthProviderConfig`

NewDomainAuthProviderConfigWithDefaults instantiates a new DomainAuthProviderConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentityProviderConfig

`func (o *DomainAuthProviderConfig) GetIdentityProviderConfig() SamlIdentityProviderConfig`

GetIdentityProviderConfig returns the IdentityProviderConfig field if non-nil, zero value otherwise.

### GetIdentityProviderConfigOk

`func (o *DomainAuthProviderConfig) GetIdentityProviderConfigOk() (*SamlIdentityProviderConfig, bool)`

GetIdentityProviderConfigOk returns a tuple with the IdentityProviderConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityProviderConfig

`func (o *DomainAuthProviderConfig) SetIdentityProviderConfig(v SamlIdentityProviderConfig)`

SetIdentityProviderConfig sets IdentityProviderConfig field to given value.


### GetServiceProviderConfig

`func (o *DomainAuthProviderConfig) GetServiceProviderConfig() SamlServiceProviderConfig`

GetServiceProviderConfig returns the ServiceProviderConfig field if non-nil, zero value otherwise.

### GetServiceProviderConfigOk

`func (o *DomainAuthProviderConfig) GetServiceProviderConfigOk() (*SamlServiceProviderConfig, bool)`

GetServiceProviderConfigOk returns a tuple with the ServiceProviderConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceProviderConfig

`func (o *DomainAuthProviderConfig) SetServiceProviderConfig(v SamlServiceProviderConfig)`

SetServiceProviderConfig sets ServiceProviderConfig field to given value.

### HasServiceProviderConfig

`func (o *DomainAuthProviderConfig) HasServiceProviderConfig() bool`

HasServiceProviderConfig returns a boolean if a field has been set.

### GetUserAttributeMapping

`func (o *DomainAuthProviderConfig) GetUserAttributeMapping() LdapUserAttributeMapping`

GetUserAttributeMapping returns the UserAttributeMapping field if non-nil, zero value otherwise.

### GetUserAttributeMappingOk

`func (o *DomainAuthProviderConfig) GetUserAttributeMappingOk() (*LdapUserAttributeMapping, bool)`

GetUserAttributeMappingOk returns a tuple with the UserAttributeMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAttributeMapping

`func (o *DomainAuthProviderConfig) SetUserAttributeMapping(v LdapUserAttributeMapping)`

SetUserAttributeMapping sets UserAttributeMapping field to given value.

### HasUserAttributeMapping

`func (o *DomainAuthProviderConfig) HasUserAttributeMapping() bool`

HasUserAttributeMapping returns a boolean if a field has been set.

### GetGroupMapping

`func (o *DomainAuthProviderConfig) GetGroupMapping() []SamlGroupMapping`

GetGroupMapping returns the GroupMapping field if non-nil, zero value otherwise.

### GetGroupMappingOk

`func (o *DomainAuthProviderConfig) GetGroupMappingOk() (*[]SamlGroupMapping, bool)`

GetGroupMappingOk returns a tuple with the GroupMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMapping

`func (o *DomainAuthProviderConfig) SetGroupMapping(v []SamlGroupMapping)`

SetGroupMapping sets GroupMapping field to given value.

### HasGroupMapping

`func (o *DomainAuthProviderConfig) HasGroupMapping() bool`

HasGroupMapping returns a boolean if a field has been set.

### GetDiscoveryUrl

`func (o *DomainAuthProviderConfig) GetDiscoveryUrl() string`

GetDiscoveryUrl returns the DiscoveryUrl field if non-nil, zero value otherwise.

### GetDiscoveryUrlOk

`func (o *DomainAuthProviderConfig) GetDiscoveryUrlOk() (*string, bool)`

GetDiscoveryUrlOk returns a tuple with the DiscoveryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveryUrl

`func (o *DomainAuthProviderConfig) SetDiscoveryUrl(v string)`

SetDiscoveryUrl sets DiscoveryUrl field to given value.


### GetClientId

`func (o *DomainAuthProviderConfig) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *DomainAuthProviderConfig) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *DomainAuthProviderConfig) SetClientId(v string)`

SetClientId sets ClientId field to given value.


### GetClientSecret

`func (o *DomainAuthProviderConfig) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *DomainAuthProviderConfig) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *DomainAuthProviderConfig) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.


### GetInvitedOnly

`func (o *DomainAuthProviderConfig) GetInvitedOnly() bool`

GetInvitedOnly returns the InvitedOnly field if non-nil, zero value otherwise.

### GetInvitedOnlyOk

`func (o *DomainAuthProviderConfig) GetInvitedOnlyOk() (*bool, bool)`

GetInvitedOnlyOk returns a tuple with the InvitedOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedOnly

`func (o *DomainAuthProviderConfig) SetInvitedOnly(v bool)`

SetInvitedOnly sets InvitedOnly field to given value.

### HasInvitedOnly

`func (o *DomainAuthProviderConfig) HasInvitedOnly() bool`

HasInvitedOnly returns a boolean if a field has been set.

### GetServerConnectionDetails

`func (o *DomainAuthProviderConfig) GetServerConnectionDetails() LdapServerConnectionDetails`

GetServerConnectionDetails returns the ServerConnectionDetails field if non-nil, zero value otherwise.

### GetServerConnectionDetailsOk

`func (o *DomainAuthProviderConfig) GetServerConnectionDetailsOk() (*LdapServerConnectionDetails, bool)`

GetServerConnectionDetailsOk returns a tuple with the ServerConnectionDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerConnectionDetails

`func (o *DomainAuthProviderConfig) SetServerConnectionDetails(v LdapServerConnectionDetails)`

SetServerConnectionDetails sets ServerConnectionDetails field to given value.


### GetAuthenticationCredentials

`func (o *DomainAuthProviderConfig) GetAuthenticationCredentials() LdapAuthenticationCredentials`

GetAuthenticationCredentials returns the AuthenticationCredentials field if non-nil, zero value otherwise.

### GetAuthenticationCredentialsOk

`func (o *DomainAuthProviderConfig) GetAuthenticationCredentialsOk() (*LdapAuthenticationCredentials, bool)`

GetAuthenticationCredentialsOk returns a tuple with the AuthenticationCredentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationCredentials

`func (o *DomainAuthProviderConfig) SetAuthenticationCredentials(v LdapAuthenticationCredentials)`

SetAuthenticationCredentials sets AuthenticationCredentials field to given value.


### GetUserSearchConfiguration

`func (o *DomainAuthProviderConfig) GetUserSearchConfiguration() LdapUserSearchConfiguration`

GetUserSearchConfiguration returns the UserSearchConfiguration field if non-nil, zero value otherwise.

### GetUserSearchConfigurationOk

`func (o *DomainAuthProviderConfig) GetUserSearchConfigurationOk() (*LdapUserSearchConfiguration, bool)`

GetUserSearchConfigurationOk returns a tuple with the UserSearchConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserSearchConfiguration

`func (o *DomainAuthProviderConfig) SetUserSearchConfiguration(v LdapUserSearchConfiguration)`

SetUserSearchConfiguration sets UserSearchConfiguration field to given value.


### GetGroupSearchConfiguration

`func (o *DomainAuthProviderConfig) GetGroupSearchConfiguration() []LdapGroupSearchConfiguration`

GetGroupSearchConfiguration returns the GroupSearchConfiguration field if non-nil, zero value otherwise.

### GetGroupSearchConfigurationOk

`func (o *DomainAuthProviderConfig) GetGroupSearchConfigurationOk() (*[]LdapGroupSearchConfiguration, bool)`

GetGroupSearchConfigurationOk returns a tuple with the GroupSearchConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSearchConfiguration

`func (o *DomainAuthProviderConfig) SetGroupSearchConfiguration(v []LdapGroupSearchConfiguration)`

SetGroupSearchConfiguration sets GroupSearchConfiguration field to given value.

### HasGroupSearchConfiguration

`func (o *DomainAuthProviderConfig) HasGroupSearchConfiguration() bool`

HasGroupSearchConfiguration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


