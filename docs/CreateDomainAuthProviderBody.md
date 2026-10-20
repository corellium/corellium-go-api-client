# CreateDomainAuthProviderBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProviderType** | **string** | Provider type. | 
**Enabled** | **bool** | Whether the provider is enabled. | 
**Label** | Pointer to **string** | Login button text. | [optional] 
**Config** | Pointer to [**DomainAuthProviderConfig**](DomainAuthProviderConfig.md) |  | [optional] 

## Methods

### NewCreateDomainAuthProviderBody

`func NewCreateDomainAuthProviderBody(providerType string, enabled bool, ) *CreateDomainAuthProviderBody`

NewCreateDomainAuthProviderBody instantiates a new CreateDomainAuthProviderBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDomainAuthProviderBodyWithDefaults

`func NewCreateDomainAuthProviderBodyWithDefaults() *CreateDomainAuthProviderBody`

NewCreateDomainAuthProviderBodyWithDefaults instantiates a new CreateDomainAuthProviderBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProviderType

`func (o *CreateDomainAuthProviderBody) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *CreateDomainAuthProviderBody) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *CreateDomainAuthProviderBody) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.


### GetEnabled

`func (o *CreateDomainAuthProviderBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateDomainAuthProviderBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateDomainAuthProviderBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetLabel

`func (o *CreateDomainAuthProviderBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateDomainAuthProviderBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateDomainAuthProviderBody) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *CreateDomainAuthProviderBody) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetConfig

`func (o *CreateDomainAuthProviderBody) GetConfig() DomainAuthProviderConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateDomainAuthProviderBody) GetConfigOk() (*DomainAuthProviderConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateDomainAuthProviderBody) SetConfig(v DomainAuthProviderConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *CreateDomainAuthProviderBody) HasConfig() bool`

HasConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


