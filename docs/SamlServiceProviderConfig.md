# SamlServiceProviderConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SsoUrl** | **string** | SP assertion consumer service URL. | 
**PublicCertificate** | **string** | SP X.509 public certificate. | 
**AudienceUrl** | **string** | SP audience / entity ID. | 

## Methods

### NewSamlServiceProviderConfig

`func NewSamlServiceProviderConfig(ssoUrl string, publicCertificate string, audienceUrl string, ) *SamlServiceProviderConfig`

NewSamlServiceProviderConfig instantiates a new SamlServiceProviderConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSamlServiceProviderConfigWithDefaults

`func NewSamlServiceProviderConfigWithDefaults() *SamlServiceProviderConfig`

NewSamlServiceProviderConfigWithDefaults instantiates a new SamlServiceProviderConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSsoUrl

`func (o *SamlServiceProviderConfig) GetSsoUrl() string`

GetSsoUrl returns the SsoUrl field if non-nil, zero value otherwise.

### GetSsoUrlOk

`func (o *SamlServiceProviderConfig) GetSsoUrlOk() (*string, bool)`

GetSsoUrlOk returns a tuple with the SsoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSsoUrl

`func (o *SamlServiceProviderConfig) SetSsoUrl(v string)`

SetSsoUrl sets SsoUrl field to given value.


### GetPublicCertificate

`func (o *SamlServiceProviderConfig) GetPublicCertificate() string`

GetPublicCertificate returns the PublicCertificate field if non-nil, zero value otherwise.

### GetPublicCertificateOk

`func (o *SamlServiceProviderConfig) GetPublicCertificateOk() (*string, bool)`

GetPublicCertificateOk returns a tuple with the PublicCertificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicCertificate

`func (o *SamlServiceProviderConfig) SetPublicCertificate(v string)`

SetPublicCertificate sets PublicCertificate field to given value.


### GetAudienceUrl

`func (o *SamlServiceProviderConfig) GetAudienceUrl() string`

GetAudienceUrl returns the AudienceUrl field if non-nil, zero value otherwise.

### GetAudienceUrlOk

`func (o *SamlServiceProviderConfig) GetAudienceUrlOk() (*string, bool)`

GetAudienceUrlOk returns a tuple with the AudienceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceUrl

`func (o *SamlServiceProviderConfig) SetAudienceUrl(v string)`

SetAudienceUrl sets AudienceUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


