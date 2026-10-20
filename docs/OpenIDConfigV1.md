# OpenIDConfigV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DiscoveryUrl** | Pointer to **NullableString** | Service Discovery URL | [optional] 
**ClientId** | Pointer to **NullableString** | Service Client ID | [optional] 
**ClientSecret** | Pointer to **NullableString** | Service Client Secret | [optional] 
**InvitedOnly** | Pointer to **NullableBool** | Only accept individuals with invitations | [optional] 

## Methods

### NewOpenIDConfigV1

`func NewOpenIDConfigV1() *OpenIDConfigV1`

NewOpenIDConfigV1 instantiates a new OpenIDConfigV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenIDConfigV1WithDefaults

`func NewOpenIDConfigV1WithDefaults() *OpenIDConfigV1`

NewOpenIDConfigV1WithDefaults instantiates a new OpenIDConfigV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDiscoveryUrl

`func (o *OpenIDConfigV1) GetDiscoveryUrl() string`

GetDiscoveryUrl returns the DiscoveryUrl field if non-nil, zero value otherwise.

### GetDiscoveryUrlOk

`func (o *OpenIDConfigV1) GetDiscoveryUrlOk() (*string, bool)`

GetDiscoveryUrlOk returns a tuple with the DiscoveryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveryUrl

`func (o *OpenIDConfigV1) SetDiscoveryUrl(v string)`

SetDiscoveryUrl sets DiscoveryUrl field to given value.

### HasDiscoveryUrl

`func (o *OpenIDConfigV1) HasDiscoveryUrl() bool`

HasDiscoveryUrl returns a boolean if a field has been set.

### SetDiscoveryUrlNil

`func (o *OpenIDConfigV1) SetDiscoveryUrlNil(b bool)`

 SetDiscoveryUrlNil sets the value for DiscoveryUrl to be an explicit nil

### UnsetDiscoveryUrl
`func (o *OpenIDConfigV1) UnsetDiscoveryUrl()`

UnsetDiscoveryUrl ensures that no value is present for DiscoveryUrl, not even an explicit nil
### GetClientId

`func (o *OpenIDConfigV1) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *OpenIDConfigV1) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *OpenIDConfigV1) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *OpenIDConfigV1) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### SetClientIdNil

`func (o *OpenIDConfigV1) SetClientIdNil(b bool)`

 SetClientIdNil sets the value for ClientId to be an explicit nil

### UnsetClientId
`func (o *OpenIDConfigV1) UnsetClientId()`

UnsetClientId ensures that no value is present for ClientId, not even an explicit nil
### GetClientSecret

`func (o *OpenIDConfigV1) GetClientSecret() string`

GetClientSecret returns the ClientSecret field if non-nil, zero value otherwise.

### GetClientSecretOk

`func (o *OpenIDConfigV1) GetClientSecretOk() (*string, bool)`

GetClientSecretOk returns a tuple with the ClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientSecret

`func (o *OpenIDConfigV1) SetClientSecret(v string)`

SetClientSecret sets ClientSecret field to given value.

### HasClientSecret

`func (o *OpenIDConfigV1) HasClientSecret() bool`

HasClientSecret returns a boolean if a field has been set.

### SetClientSecretNil

`func (o *OpenIDConfigV1) SetClientSecretNil(b bool)`

 SetClientSecretNil sets the value for ClientSecret to be an explicit nil

### UnsetClientSecret
`func (o *OpenIDConfigV1) UnsetClientSecret()`

UnsetClientSecret ensures that no value is present for ClientSecret, not even an explicit nil
### GetInvitedOnly

`func (o *OpenIDConfigV1) GetInvitedOnly() bool`

GetInvitedOnly returns the InvitedOnly field if non-nil, zero value otherwise.

### GetInvitedOnlyOk

`func (o *OpenIDConfigV1) GetInvitedOnlyOk() (*bool, bool)`

GetInvitedOnlyOk returns a tuple with the InvitedOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedOnly

`func (o *OpenIDConfigV1) SetInvitedOnly(v bool)`

SetInvitedOnly sets InvitedOnly field to given value.

### HasInvitedOnly

`func (o *OpenIDConfigV1) HasInvitedOnly() bool`

HasInvitedOnly returns a boolean if a field has been set.

### SetInvitedOnlyNil

`func (o *OpenIDConfigV1) SetInvitedOnlyNil(b bool)`

 SetInvitedOnlyNil sets the value for InvitedOnly to be an explicit nil

### UnsetInvitedOnly
`func (o *OpenIDConfigV1) UnsetInvitedOnly()`

UnsetInvitedOnly ensures that no value is present for InvitedOnly, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


