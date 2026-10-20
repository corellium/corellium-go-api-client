# DomainAuthProviderResponseV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Provider ID | 
**Id** | Pointer to **NullableString** | Provider ID for backward compatibility with frontend | [optional] 
**ProviderType** | **string** | Provider Type | 
**Provider** | Pointer to **NullableString** | Provider Type for backward compatibility with frontend | [optional] 
**Label** | **string** | Login Button Text | 
**Name** | Pointer to **NullableString** | Title Text for the Frontend&#39;s Provider Configuration Form | [optional] 
**AuthorizationUrl** | Pointer to **NullableString** | Coordinator endpoint for Authorizing with this provider | [optional] 
**Default** | **bool** | True: Configured in coordinator.json, False: Custom Domain Provider | 
**Enabled** | **bool** | Enabled/Disabled | 
**Config** | Pointer to [**OpenIDConfigV1**](OpenIDConfigV1.md) |  | [optional] 
**CreatedBy** | Pointer to **NullableString** | Optional User ID of creator | [optional] 
**CreatedAt** | **string** | Created Date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z | 
**UpdatedAt** | **string** | Updated Date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z | 

## Methods

### NewDomainAuthProviderResponseV1

`func NewDomainAuthProviderResponseV1(identifier string, providerType string, label string, default_ bool, enabled bool, createdAt string, updatedAt string, ) *DomainAuthProviderResponseV1`

NewDomainAuthProviderResponseV1 instantiates a new DomainAuthProviderResponseV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainAuthProviderResponseV1WithDefaults

`func NewDomainAuthProviderResponseV1WithDefaults() *DomainAuthProviderResponseV1`

NewDomainAuthProviderResponseV1WithDefaults instantiates a new DomainAuthProviderResponseV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainAuthProviderResponseV1) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainAuthProviderResponseV1) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainAuthProviderResponseV1) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetId

`func (o *DomainAuthProviderResponseV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DomainAuthProviderResponseV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DomainAuthProviderResponseV1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DomainAuthProviderResponseV1) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *DomainAuthProviderResponseV1) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *DomainAuthProviderResponseV1) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetProviderType

`func (o *DomainAuthProviderResponseV1) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *DomainAuthProviderResponseV1) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *DomainAuthProviderResponseV1) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetProvider

`func (o *DomainAuthProviderResponseV1) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *DomainAuthProviderResponseV1) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *DomainAuthProviderResponseV1) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *DomainAuthProviderResponseV1) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *DomainAuthProviderResponseV1) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *DomainAuthProviderResponseV1) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetLabel

`func (o *DomainAuthProviderResponseV1) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainAuthProviderResponseV1) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainAuthProviderResponseV1) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetName

`func (o *DomainAuthProviderResponseV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainAuthProviderResponseV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainAuthProviderResponseV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DomainAuthProviderResponseV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *DomainAuthProviderResponseV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *DomainAuthProviderResponseV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetAuthorizationUrl

`func (o *DomainAuthProviderResponseV1) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *DomainAuthProviderResponseV1) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *DomainAuthProviderResponseV1) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.

### HasAuthorizationUrl

`func (o *DomainAuthProviderResponseV1) HasAuthorizationUrl() bool`

HasAuthorizationUrl returns a boolean if a field has been set.

### SetAuthorizationUrlNil

`func (o *DomainAuthProviderResponseV1) SetAuthorizationUrlNil(b bool)`

 SetAuthorizationUrlNil sets the value for AuthorizationUrl to be an explicit nil

### UnsetAuthorizationUrl
`func (o *DomainAuthProviderResponseV1) UnsetAuthorizationUrl()`

UnsetAuthorizationUrl ensures that no value is present for AuthorizationUrl, not even an explicit nil
### GetDefault

`func (o *DomainAuthProviderResponseV1) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *DomainAuthProviderResponseV1) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *DomainAuthProviderResponseV1) SetDefault(v bool)`

SetDefault sets Default field to given value.


### GetEnabled

`func (o *DomainAuthProviderResponseV1) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DomainAuthProviderResponseV1) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DomainAuthProviderResponseV1) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetConfig

`func (o *DomainAuthProviderResponseV1) GetConfig() OpenIDConfigV1`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *DomainAuthProviderResponseV1) GetConfigOk() (*OpenIDConfigV1, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *DomainAuthProviderResponseV1) SetConfig(v OpenIDConfigV1)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *DomainAuthProviderResponseV1) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetCreatedBy

`func (o *DomainAuthProviderResponseV1) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *DomainAuthProviderResponseV1) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *DomainAuthProviderResponseV1) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *DomainAuthProviderResponseV1) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *DomainAuthProviderResponseV1) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *DomainAuthProviderResponseV1) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetCreatedAt

`func (o *DomainAuthProviderResponseV1) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainAuthProviderResponseV1) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainAuthProviderResponseV1) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *DomainAuthProviderResponseV1) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainAuthProviderResponseV1) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainAuthProviderResponseV1) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


