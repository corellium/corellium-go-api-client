# DomainAuthProviderResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Provider identifier. | 
**Config** | Pointer to [**NullableCreateDomainAuthProviderResponseConfig**](CreateDomainAuthProviderResponseConfig.md) |  | [optional] 
**ProviderType** | **string** | Provider type. | 
**Label** | **string** | Login button text. | 
**Enabled** | **bool** | Enabled/Disabled. | 
**CreatedBy** | Pointer to **NullableString** | Optional User ID of creator. | [optional] 
**Default** | **bool** | True: configured in coordinator.json, False: custom domain provider. | 
**AuthorizationUrl** | Pointer to **string** | Coordinator endpoint for Authorizing with this provider. | [optional] 
**Name** | Pointer to **string** | Provider name for a given provider type. | [optional] 
**CreatedAt** | Pointer to **time.Time** | Created date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Updated date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z. | [optional] 

## Methods

### NewDomainAuthProviderResponse

`func NewDomainAuthProviderResponse(identifier string, providerType string, label string, enabled bool, default_ bool, ) *DomainAuthProviderResponse`

NewDomainAuthProviderResponse instantiates a new DomainAuthProviderResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainAuthProviderResponseWithDefaults

`func NewDomainAuthProviderResponseWithDefaults() *DomainAuthProviderResponse`

NewDomainAuthProviderResponseWithDefaults instantiates a new DomainAuthProviderResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainAuthProviderResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainAuthProviderResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainAuthProviderResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetConfig

`func (o *DomainAuthProviderResponse) GetConfig() CreateDomainAuthProviderResponseConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *DomainAuthProviderResponse) GetConfigOk() (*CreateDomainAuthProviderResponseConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *DomainAuthProviderResponse) SetConfig(v CreateDomainAuthProviderResponseConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *DomainAuthProviderResponse) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *DomainAuthProviderResponse) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *DomainAuthProviderResponse) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetProviderType

`func (o *DomainAuthProviderResponse) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *DomainAuthProviderResponse) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *DomainAuthProviderResponse) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetLabel

`func (o *DomainAuthProviderResponse) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DomainAuthProviderResponse) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DomainAuthProviderResponse) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetEnabled

`func (o *DomainAuthProviderResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *DomainAuthProviderResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *DomainAuthProviderResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetCreatedBy

`func (o *DomainAuthProviderResponse) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *DomainAuthProviderResponse) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *DomainAuthProviderResponse) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *DomainAuthProviderResponse) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *DomainAuthProviderResponse) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *DomainAuthProviderResponse) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetDefault

`func (o *DomainAuthProviderResponse) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *DomainAuthProviderResponse) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *DomainAuthProviderResponse) SetDefault(v bool)`

SetDefault sets Default field to given value.


### GetAuthorizationUrl

`func (o *DomainAuthProviderResponse) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *DomainAuthProviderResponse) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *DomainAuthProviderResponse) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.

### HasAuthorizationUrl

`func (o *DomainAuthProviderResponse) HasAuthorizationUrl() bool`

HasAuthorizationUrl returns a boolean if a field has been set.

### GetName

`func (o *DomainAuthProviderResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainAuthProviderResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainAuthProviderResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DomainAuthProviderResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DomainAuthProviderResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DomainAuthProviderResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DomainAuthProviderResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DomainAuthProviderResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DomainAuthProviderResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainAuthProviderResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainAuthProviderResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DomainAuthProviderResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


