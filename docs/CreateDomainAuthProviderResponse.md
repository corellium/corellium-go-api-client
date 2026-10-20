# CreateDomainAuthProviderResponse

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
**CreatedAt** | Pointer to **time.Time** | Created date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Updated date in ISO-8601 format e.g. 2022-05-06T02:39:23.000Z. | [optional] 

## Methods

### NewCreateDomainAuthProviderResponse

`func NewCreateDomainAuthProviderResponse(identifier string, providerType string, label string, enabled bool, default_ bool, ) *CreateDomainAuthProviderResponse`

NewCreateDomainAuthProviderResponse instantiates a new CreateDomainAuthProviderResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDomainAuthProviderResponseWithDefaults

`func NewCreateDomainAuthProviderResponseWithDefaults() *CreateDomainAuthProviderResponse`

NewCreateDomainAuthProviderResponseWithDefaults instantiates a new CreateDomainAuthProviderResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *CreateDomainAuthProviderResponse) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *CreateDomainAuthProviderResponse) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *CreateDomainAuthProviderResponse) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetConfig

`func (o *CreateDomainAuthProviderResponse) GetConfig() CreateDomainAuthProviderResponseConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateDomainAuthProviderResponse) GetConfigOk() (*CreateDomainAuthProviderResponseConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateDomainAuthProviderResponse) SetConfig(v CreateDomainAuthProviderResponseConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *CreateDomainAuthProviderResponse) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### SetConfigNil

`func (o *CreateDomainAuthProviderResponse) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *CreateDomainAuthProviderResponse) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetProviderType

`func (o *CreateDomainAuthProviderResponse) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *CreateDomainAuthProviderResponse) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *CreateDomainAuthProviderResponse) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetLabel

`func (o *CreateDomainAuthProviderResponse) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateDomainAuthProviderResponse) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateDomainAuthProviderResponse) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetEnabled

`func (o *CreateDomainAuthProviderResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDomainAuthProviderResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDomainAuthProviderResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetCreatedBy

`func (o *CreateDomainAuthProviderResponse) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *CreateDomainAuthProviderResponse) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *CreateDomainAuthProviderResponse) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *CreateDomainAuthProviderResponse) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *CreateDomainAuthProviderResponse) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *CreateDomainAuthProviderResponse) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetDefault

`func (o *CreateDomainAuthProviderResponse) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *CreateDomainAuthProviderResponse) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *CreateDomainAuthProviderResponse) SetDefault(v bool)`

SetDefault sets Default field to given value.


### GetCreatedAt

`func (o *CreateDomainAuthProviderResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateDomainAuthProviderResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateDomainAuthProviderResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateDomainAuthProviderResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateDomainAuthProviderResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateDomainAuthProviderResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateDomainAuthProviderResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateDomainAuthProviderResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


