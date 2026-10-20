# OpenIDConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DiscoveryUrl** | **string** | Service Discovery URL. | 
**ClientId** | **string** | Service Client ID. | 
**ClientSecret** | **string** | Service Client Secret. | 
**InvitedOnly** | Pointer to **bool** | Only accept individuals with invitations. | [optional] 

## Methods

### NewOpenIDConfig

`func NewOpenIDConfig(discoveryUrl string, clientId string, clientSecret string, ) *OpenIDConfig`

NewOpenIDConfig instantiates a new OpenIDConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenIDConfigWithDefaults

`func NewOpenIDConfigWithDefaults() *OpenIDConfig`

NewOpenIDConfigWithDefaults instantiates a new OpenIDConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDiscoveryUrl

`func (o *OpenIDConfig) GetDiscoveryUrl() string`

GetDiscoveryUrl returns the DiscoveryUrl field if non-nil, zero value otherwise.

### GetDiscoveryUrlOk

`func (o *OpenIDConfig) GetDiscoveryUrlOk() (*string, bool)`

GetDiscoveryUrlOk returns a tuple with the DiscoveryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveryUrl

`func (o *OpenIDConfig) SetDiscoveryUrl(v string)`

SetDiscoveryUrl sets DiscoveryUrl field to given value.


### GetClientId

`func (o *OpenIDConfig) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *OpenIDConfig) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *OpenIDConfig) SetClientId(v string)`

SetClientId sets ClientId field to given value.


### GetClientSecret

`func (o *OpenIDConfig) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *OpenIDConfig) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *OpenIDConfig) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.


### GetInvitedOnly

`func (o *OpenIDConfig) GetInvitedOnly() bool`

GetInvitedOnly returns the InvitedOnly field if non-nil, zero value otherwise.

### GetInvitedOnlyOk

`func (o *OpenIDConfig) GetInvitedOnlyOk() (*bool, bool)`

GetInvitedOnlyOk returns a tuple with the InvitedOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedOnly

`func (o *OpenIDConfig) SetInvitedOnly(v bool)`

SetInvitedOnly sets InvitedOnly field to given value.

### HasInvitedOnly

`func (o *OpenIDConfig) HasInvitedOnly() bool`

HasInvitedOnly returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


