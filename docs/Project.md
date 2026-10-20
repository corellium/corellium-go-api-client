# Project

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Project identifier. | 
**Name** | **string** | Project name. | 
**Settings** | [**ProjectSettings**](ProjectSettings.md) |  | 
**Quotas** | [**ProjectQuota**](ProjectQuota.md) |  | 
**QuotasUsed** | [**ProjectUsage**](ProjectUsage.md) |  | 
**NetworkStatus** | Pointer to [**NetworkStatus**](NetworkStatus.md) |  | [optional] 
**Config** | Pointer to [**ProjectConfig**](ProjectConfig.md) |  | [optional] 

## Methods

### NewProject

`func NewProject(id string, name string, settings ProjectSettings, quotas ProjectQuota, quotasUsed ProjectUsage, ) *Project`

NewProject instantiates a new Project object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWithDefaults

`func NewProjectWithDefaults() *Project`

NewProjectWithDefaults instantiates a new Project object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Project) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Project) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Project) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Project) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Project) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Project) SetName(v string)`

SetName sets Name field to given value.


### GetSettings

`func (o *Project) GetSettings() ProjectSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *Project) GetSettingsOk() (*ProjectSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *Project) SetSettings(v ProjectSettings)`

SetSettings sets Settings field to given value.


### GetQuotas

`func (o *Project) GetQuotas() ProjectQuota`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *Project) GetQuotasOk() (*ProjectQuota, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *Project) SetQuotas(v ProjectQuota)`

SetQuotas sets Quotas field to given value.


### GetQuotasUsed

`func (o *Project) GetQuotasUsed() ProjectUsage`

GetQuotasUsed returns the QuotasUsed field if non-nil, zero value otherwise.

### GetQuotasUsedOk

`func (o *Project) GetQuotasUsedOk() (*ProjectUsage, bool)`

GetQuotasUsedOk returns a tuple with the QuotasUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotasUsed

`func (o *Project) SetQuotasUsed(v ProjectUsage)`

SetQuotasUsed sets QuotasUsed field to given value.


### GetNetworkStatus

`func (o *Project) GetNetworkStatus() NetworkStatus`

GetNetworkStatus returns the NetworkStatus field if non-nil, zero value otherwise.

### GetNetworkStatusOk

`func (o *Project) GetNetworkStatusOk() (*NetworkStatus, bool)`

GetNetworkStatusOk returns a tuple with the NetworkStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkStatus

`func (o *Project) SetNetworkStatus(v NetworkStatus)`

SetNetworkStatus sets NetworkStatus field to given value.

### HasNetworkStatus

`func (o *Project) HasNetworkStatus() bool`

HasNetworkStatus returns a boolean if a field has been set.

### GetConfig

`func (o *Project) GetConfig() ProjectConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *Project) GetConfigOk() (*ProjectConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *Project) SetConfig(v ProjectConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *Project) HasConfig() bool`

HasConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


