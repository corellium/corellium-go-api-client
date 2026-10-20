# PatchDomainAuthProviderBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProviderType** | Pointer to **string** | Provider type. | [optional] 
**Enabled** | Pointer to **bool** | Whether the provider is enabled. | [optional] 
**Label** | Pointer to **string** | Login button text. | [optional] 
**Config** | Pointer to [**DomainAuthProviderConfig**](DomainAuthProviderConfig.md) |  | [optional] 

## Methods

### NewPatchDomainAuthProviderBody

`func NewPatchDomainAuthProviderBody() *PatchDomainAuthProviderBody`

NewPatchDomainAuthProviderBody instantiates a new PatchDomainAuthProviderBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchDomainAuthProviderBodyWithDefaults

`func NewPatchDomainAuthProviderBodyWithDefaults() *PatchDomainAuthProviderBody`

NewPatchDomainAuthProviderBodyWithDefaults instantiates a new PatchDomainAuthProviderBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProviderType

`func (o *PatchDomainAuthProviderBody) GetProviderType() string`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *PatchDomainAuthProviderBody) GetProviderTypeOk() (*string, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *PatchDomainAuthProviderBody) SetProviderType(v string)`

SetProviderType sets ProviderType field to given value.

### HasProviderType

`func (o *PatchDomainAuthProviderBody) HasProviderType() bool`

HasProviderType returns a boolean if a field has been set.

### GetEnabled

`func (o *PatchDomainAuthProviderBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PatchDomainAuthProviderBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PatchDomainAuthProviderBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *PatchDomainAuthProviderBody) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetLabel

`func (o *PatchDomainAuthProviderBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *PatchDomainAuthProviderBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *PatchDomainAuthProviderBody) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *PatchDomainAuthProviderBody) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetConfig

`func (o *PatchDomainAuthProviderBody) GetConfig() DomainAuthProviderConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *PatchDomainAuthProviderBody) GetConfigOk() (*DomainAuthProviderConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *PatchDomainAuthProviderBody) SetConfig(v DomainAuthProviderConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *PatchDomainAuthProviderBody) HasConfig() bool`

HasConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


