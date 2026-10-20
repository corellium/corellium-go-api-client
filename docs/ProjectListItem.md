# ProjectListItem

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
**KeyCount** | **float32** | Number of authorized keys on the project. | 

## Methods

### NewProjectListItem

`func NewProjectListItem(id string, name string, settings ProjectSettings, quotas ProjectQuota, quotasUsed ProjectUsage, keyCount float32, ) *ProjectListItem`

NewProjectListItem instantiates a new ProjectListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectListItemWithDefaults

`func NewProjectListItemWithDefaults() *ProjectListItem`

NewProjectListItemWithDefaults instantiates a new ProjectListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectListItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectListItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectListItem) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectListItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectListItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectListItem) SetName(v string)`

SetName sets Name field to given value.


### GetSettings

`func (o *ProjectListItem) GetSettings() ProjectSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *ProjectListItem) GetSettingsOk() (*ProjectSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *ProjectListItem) SetSettings(v ProjectSettings)`

SetSettings sets Settings field to given value.


### GetQuotas

`func (o *ProjectListItem) GetQuotas() ProjectQuota`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *ProjectListItem) GetQuotasOk() (*ProjectQuota, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *ProjectListItem) SetQuotas(v ProjectQuota)`

SetQuotas sets Quotas field to given value.


### GetQuotasUsed

`func (o *ProjectListItem) GetQuotasUsed() ProjectUsage`

GetQuotasUsed returns the QuotasUsed field if non-nil, zero value otherwise.

### GetQuotasUsedOk

`func (o *ProjectListItem) GetQuotasUsedOk() (*ProjectUsage, bool)`

GetQuotasUsedOk returns a tuple with the QuotasUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotasUsed

`func (o *ProjectListItem) SetQuotasUsed(v ProjectUsage)`

SetQuotasUsed sets QuotasUsed field to given value.


### GetNetworkStatus

`func (o *ProjectListItem) GetNetworkStatus() NetworkStatus`

GetNetworkStatus returns the NetworkStatus field if non-nil, zero value otherwise.

### GetNetworkStatusOk

`func (o *ProjectListItem) GetNetworkStatusOk() (*NetworkStatus, bool)`

GetNetworkStatusOk returns a tuple with the NetworkStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkStatus

`func (o *ProjectListItem) SetNetworkStatus(v NetworkStatus)`

SetNetworkStatus sets NetworkStatus field to given value.

### HasNetworkStatus

`func (o *ProjectListItem) HasNetworkStatus() bool`

HasNetworkStatus returns a boolean if a field has been set.

### GetConfig

`func (o *ProjectListItem) GetConfig() ProjectConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *ProjectListItem) GetConfigOk() (*ProjectConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *ProjectListItem) SetConfig(v ProjectConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *ProjectListItem) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetKeyCount

`func (o *ProjectListItem) GetKeyCount() float32`

GetKeyCount returns the KeyCount field if non-nil, zero value otherwise.

### GetKeyCountOk

`func (o *ProjectListItem) GetKeyCountOk() (*float32, bool)`

GetKeyCountOk returns a tuple with the KeyCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyCount

`func (o *ProjectListItem) SetKeyCount(v float32)`

SetKeyCount sets KeyCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


