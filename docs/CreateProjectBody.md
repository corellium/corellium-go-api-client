# CreateProjectBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Project name. | 
**Color** | Pointer to **float32** | Project display color. | [optional] 
**Settings** | Pointer to [**ProjectSettings**](ProjectSettings.md) | Initial project settings. | [optional] 
**Quotas** | Pointer to [**ProjectQuotaInput**](ProjectQuotaInput.md) |  | [optional] 

## Methods

### NewCreateProjectBody

`func NewCreateProjectBody(name string, ) *CreateProjectBody`

NewCreateProjectBody instantiates a new CreateProjectBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProjectBodyWithDefaults

`func NewCreateProjectBodyWithDefaults() *CreateProjectBody`

NewCreateProjectBodyWithDefaults instantiates a new CreateProjectBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateProjectBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateProjectBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateProjectBody) SetName(v string)`

SetName sets Name field to given value.


### GetColor

`func (o *CreateProjectBody) GetColor() float32`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CreateProjectBody) GetColorOk() (*float32, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CreateProjectBody) SetColor(v float32)`

SetColor sets Color field to given value.

### HasColor

`func (o *CreateProjectBody) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetSettings

`func (o *CreateProjectBody) GetSettings() ProjectSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *CreateProjectBody) GetSettingsOk() (*ProjectSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *CreateProjectBody) SetSettings(v ProjectSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *CreateProjectBody) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetQuotas

`func (o *CreateProjectBody) GetQuotas() ProjectQuotaInput`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *CreateProjectBody) GetQuotasOk() (*ProjectQuotaInput, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *CreateProjectBody) SetQuotas(v ProjectQuotaInput)`

SetQuotas sets Quotas field to given value.

### HasQuotas

`func (o *CreateProjectBody) HasQuotas() bool`

HasQuotas returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


