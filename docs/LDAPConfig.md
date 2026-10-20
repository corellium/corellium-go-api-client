# LDAPConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ServerConnectionDetails** | [**LdapServerConnectionDetails**](LdapServerConnectionDetails.md) |  | 
**AuthenticationCredentials** | [**LdapAuthenticationCredentials**](LdapAuthenticationCredentials.md) |  | 
**UserSearchConfiguration** | [**LdapUserSearchConfiguration**](LdapUserSearchConfiguration.md) |  | 
**UserAttributeMapping** | Pointer to [**LdapUserAttributeMapping**](LdapUserAttributeMapping.md) |  | [optional] 
**GroupSearchConfiguration** | Pointer to [**[]LdapGroupSearchConfiguration**](LdapGroupSearchConfiguration.md) |  | [optional] 

## Methods

### NewLDAPConfig

`func NewLDAPConfig(serverConnectionDetails LdapServerConnectionDetails, authenticationCredentials LdapAuthenticationCredentials, userSearchConfiguration LdapUserSearchConfiguration, ) *LDAPConfig`

NewLDAPConfig instantiates a new LDAPConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLDAPConfigWithDefaults

`func NewLDAPConfigWithDefaults() *LDAPConfig`

NewLDAPConfigWithDefaults instantiates a new LDAPConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetServerConnectionDetails

`func (o *LDAPConfig) GetServerConnectionDetails() LdapServerConnectionDetails`

GetServerConnectionDetails returns the ServerConnectionDetails field if non-nil, zero value otherwise.

### GetServerConnectionDetailsOk

`func (o *LDAPConfig) GetServerConnectionDetailsOk() (*LdapServerConnectionDetails, bool)`

GetServerConnectionDetailsOk returns a tuple with the ServerConnectionDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServerConnectionDetails

`func (o *LDAPConfig) SetServerConnectionDetails(v LdapServerConnectionDetails)`

SetServerConnectionDetails sets ServerConnectionDetails field to given value.


### GetAuthenticationCredentials

`func (o *LDAPConfig) GetAuthenticationCredentials() LdapAuthenticationCredentials`

GetAuthenticationCredentials returns the AuthenticationCredentials field if non-nil, zero value otherwise.

### GetAuthenticationCredentialsOk

`func (o *LDAPConfig) GetAuthenticationCredentialsOk() (*LdapAuthenticationCredentials, bool)`

GetAuthenticationCredentialsOk returns a tuple with the AuthenticationCredentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthenticationCredentials

`func (o *LDAPConfig) SetAuthenticationCredentials(v LdapAuthenticationCredentials)`

SetAuthenticationCredentials sets AuthenticationCredentials field to given value.


### GetUserSearchConfiguration

`func (o *LDAPConfig) GetUserSearchConfiguration() LdapUserSearchConfiguration`

GetUserSearchConfiguration returns the UserSearchConfiguration field if non-nil, zero value otherwise.

### GetUserSearchConfigurationOk

`func (o *LDAPConfig) GetUserSearchConfigurationOk() (*LdapUserSearchConfiguration, bool)`

GetUserSearchConfigurationOk returns a tuple with the UserSearchConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserSearchConfiguration

`func (o *LDAPConfig) SetUserSearchConfiguration(v LdapUserSearchConfiguration)`

SetUserSearchConfiguration sets UserSearchConfiguration field to given value.


### GetUserAttributeMapping

`func (o *LDAPConfig) GetUserAttributeMapping() LdapUserAttributeMapping`

GetUserAttributeMapping returns the UserAttributeMapping field if non-nil, zero value otherwise.

### GetUserAttributeMappingOk

`func (o *LDAPConfig) GetUserAttributeMappingOk() (*LdapUserAttributeMapping, bool)`

GetUserAttributeMappingOk returns a tuple with the UserAttributeMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAttributeMapping

`func (o *LDAPConfig) SetUserAttributeMapping(v LdapUserAttributeMapping)`

SetUserAttributeMapping sets UserAttributeMapping field to given value.

### HasUserAttributeMapping

`func (o *LDAPConfig) HasUserAttributeMapping() bool`

HasUserAttributeMapping returns a boolean if a field has been set.

### GetGroupSearchConfiguration

`func (o *LDAPConfig) GetGroupSearchConfiguration() []LdapGroupSearchConfiguration`

GetGroupSearchConfiguration returns the GroupSearchConfiguration field if non-nil, zero value otherwise.

### GetGroupSearchConfigurationOk

`func (o *LDAPConfig) GetGroupSearchConfigurationOk() (*[]LdapGroupSearchConfiguration, bool)`

GetGroupSearchConfigurationOk returns a tuple with the GroupSearchConfiguration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSearchConfiguration

`func (o *LDAPConfig) SetGroupSearchConfiguration(v []LdapGroupSearchConfiguration)`

SetGroupSearchConfiguration sets GroupSearchConfiguration field to given value.

### HasGroupSearchConfiguration

`func (o *LDAPConfig) HasGroupSearchConfiguration() bool`

HasGroupSearchConfiguration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


