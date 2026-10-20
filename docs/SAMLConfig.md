# SAMLConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentityProviderConfig** | [**SamlIdentityProviderConfig**](SamlIdentityProviderConfig.md) |  | 
**ServiceProviderConfig** | Pointer to [**SamlServiceProviderConfig**](SamlServiceProviderConfig.md) |  | [optional] 
**UserAttributeMapping** | Pointer to [**SamlUserAttributeMapping**](SamlUserAttributeMapping.md) |  | [optional] 
**GroupMapping** | Pointer to [**[]SamlGroupMapping**](SamlGroupMapping.md) |  | [optional] 

## Methods

### NewSAMLConfig

`func NewSAMLConfig(identityProviderConfig SamlIdentityProviderConfig, ) *SAMLConfig`

NewSAMLConfig instantiates a new SAMLConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSAMLConfigWithDefaults

`func NewSAMLConfigWithDefaults() *SAMLConfig`

NewSAMLConfigWithDefaults instantiates a new SAMLConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentityProviderConfig

`func (o *SAMLConfig) GetIdentityProviderConfig() SamlIdentityProviderConfig`

GetIdentityProviderConfig returns the IdentityProviderConfig field if non-nil, zero value otherwise.

### GetIdentityProviderConfigOk

`func (o *SAMLConfig) GetIdentityProviderConfigOk() (*SamlIdentityProviderConfig, bool)`

GetIdentityProviderConfigOk returns a tuple with the IdentityProviderConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityProviderConfig

`func (o *SAMLConfig) SetIdentityProviderConfig(v SamlIdentityProviderConfig)`

SetIdentityProviderConfig sets IdentityProviderConfig field to given value.


### GetServiceProviderConfig

`func (o *SAMLConfig) GetServiceProviderConfig() SamlServiceProviderConfig`

GetServiceProviderConfig returns the ServiceProviderConfig field if non-nil, zero value otherwise.

### GetServiceProviderConfigOk

`func (o *SAMLConfig) GetServiceProviderConfigOk() (*SamlServiceProviderConfig, bool)`

GetServiceProviderConfigOk returns a tuple with the ServiceProviderConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceProviderConfig

`func (o *SAMLConfig) SetServiceProviderConfig(v SamlServiceProviderConfig)`

SetServiceProviderConfig sets ServiceProviderConfig field to given value.

### HasServiceProviderConfig

`func (o *SAMLConfig) HasServiceProviderConfig() bool`

HasServiceProviderConfig returns a boolean if a field has been set.

### GetUserAttributeMapping

`func (o *SAMLConfig) GetUserAttributeMapping() SamlUserAttributeMapping`

GetUserAttributeMapping returns the UserAttributeMapping field if non-nil, zero value otherwise.

### GetUserAttributeMappingOk

`func (o *SAMLConfig) GetUserAttributeMappingOk() (*SamlUserAttributeMapping, bool)`

GetUserAttributeMappingOk returns a tuple with the UserAttributeMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAttributeMapping

`func (o *SAMLConfig) SetUserAttributeMapping(v SamlUserAttributeMapping)`

SetUserAttributeMapping sets UserAttributeMapping field to given value.

### HasUserAttributeMapping

`func (o *SAMLConfig) HasUserAttributeMapping() bool`

HasUserAttributeMapping returns a boolean if a field has been set.

### GetGroupMapping

`func (o *SAMLConfig) GetGroupMapping() []SamlGroupMapping`

GetGroupMapping returns the GroupMapping field if non-nil, zero value otherwise.

### GetGroupMappingOk

`func (o *SAMLConfig) GetGroupMappingOk() (*[]SamlGroupMapping, bool)`

GetGroupMappingOk returns a tuple with the GroupMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupMapping

`func (o *SAMLConfig) SetGroupMapping(v []SamlGroupMapping)`

SetGroupMapping sets GroupMapping field to given value.

### HasGroupMapping

`func (o *SAMLConfig) HasGroupMapping() bool`

HasGroupMapping returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


