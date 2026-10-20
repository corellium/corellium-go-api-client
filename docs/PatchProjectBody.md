# PatchProjectBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | New project name. | [optional] 
**Settings** | Pointer to [**ProjectSettings**](ProjectSettings.md) | Project settings to update. Provided fields are merged into the existing settings; omitted fields are preserved. | [optional] 
**Quotas** | Pointer to [**ProjectQuotaInput**](ProjectQuotaInput.md) | Updated resource quotas. | [optional] 

## Methods

### NewPatchProjectBody

`func NewPatchProjectBody() *PatchProjectBody`

NewPatchProjectBody instantiates a new PatchProjectBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchProjectBodyWithDefaults

`func NewPatchProjectBodyWithDefaults() *PatchProjectBody`

NewPatchProjectBodyWithDefaults instantiates a new PatchProjectBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchProjectBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchProjectBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchProjectBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchProjectBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSettings

`func (o *PatchProjectBody) GetSettings() ProjectSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *PatchProjectBody) GetSettingsOk() (*ProjectSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *PatchProjectBody) SetSettings(v ProjectSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *PatchProjectBody) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetQuotas

`func (o *PatchProjectBody) GetQuotas() ProjectQuotaInput`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *PatchProjectBody) GetQuotasOk() (*ProjectQuotaInput, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *PatchProjectBody) SetQuotas(v ProjectQuotaInput)`

SetQuotas sets Quotas field to given value.

### HasQuotas

`func (o *PatchProjectBody) HasQuotas() bool`

HasQuotas returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


