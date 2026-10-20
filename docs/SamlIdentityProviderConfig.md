# SamlIdentityProviderConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LoginUrl** | **string** | IdP SSO login endpoint the AuthnRequest is sent to. | 
**PublicCertificate** | **string** | IdP X.509 public certificate, used to verify the SAML response. | 
**IssuerUrl** | **string** | IdP unique identifier (issuer / entity ID). | 
**LogoutUrl** | Pointer to **string** | Optional IdP Single Logout URL. | [optional] 

## Methods

### NewSamlIdentityProviderConfig

`func NewSamlIdentityProviderConfig(loginUrl string, publicCertificate string, issuerUrl string, ) *SamlIdentityProviderConfig`

NewSamlIdentityProviderConfig instantiates a new SamlIdentityProviderConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSamlIdentityProviderConfigWithDefaults

`func NewSamlIdentityProviderConfigWithDefaults() *SamlIdentityProviderConfig`

NewSamlIdentityProviderConfigWithDefaults instantiates a new SamlIdentityProviderConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoginUrl

`func (o *SamlIdentityProviderConfig) GetLoginUrl() string`

GetLoginUrl returns the LoginUrl field if non-nil, zero value otherwise.

### GetLoginUrlOk

`func (o *SamlIdentityProviderConfig) GetLoginUrlOk() (*string, bool)`

GetLoginUrlOk returns a tuple with the LoginUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginUrl

`func (o *SamlIdentityProviderConfig) SetLoginUrl(v string)`

SetLoginUrl sets LoginUrl field to given value.


### GetPublicCertificate

`func (o *SamlIdentityProviderConfig) GetPublicCertificate() string`

GetPublicCertificate returns the PublicCertificate field if non-nil, zero value otherwise.

### GetPublicCertificateOk

`func (o *SamlIdentityProviderConfig) GetPublicCertificateOk() (*string, bool)`

GetPublicCertificateOk returns a tuple with the PublicCertificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicCertificate

`func (o *SamlIdentityProviderConfig) SetPublicCertificate(v string)`

SetPublicCertificate sets PublicCertificate field to given value.


### GetIssuerUrl

`func (o *SamlIdentityProviderConfig) GetIssuerUrl() string`

GetIssuerUrl returns the IssuerUrl field if non-nil, zero value otherwise.

### GetIssuerUrlOk

`func (o *SamlIdentityProviderConfig) GetIssuerUrlOk() (*string, bool)`

GetIssuerUrlOk returns a tuple with the IssuerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerUrl

`func (o *SamlIdentityProviderConfig) SetIssuerUrl(v string)`

SetIssuerUrl sets IssuerUrl field to given value.


### GetLogoutUrl

`func (o *SamlIdentityProviderConfig) GetLogoutUrl() string`

GetLogoutUrl returns the LogoutUrl field if non-nil, zero value otherwise.

### GetLogoutUrlOk

`func (o *SamlIdentityProviderConfig) GetLogoutUrlOk() (*string, bool)`

GetLogoutUrlOk returns a tuple with the LogoutUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoutUrl

`func (o *SamlIdentityProviderConfig) SetLogoutUrl(v string)`

SetLogoutUrl sets LogoutUrl field to given value.

### HasLogoutUrl

`func (o *SamlIdentityProviderConfig) HasLogoutUrl() bool`

HasLogoutUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


