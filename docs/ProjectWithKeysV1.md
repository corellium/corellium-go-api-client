# ProjectWithKeysV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Project Identifier | 
**Name** | Pointer to **NullableString** | Project Name | [optional] 
**Settings** | Pointer to [**ProjectSettingsV1**](ProjectSettingsV1.md) |  | [optional] 
**Quotas** | Pointer to [**ProjectQuotaV1**](ProjectQuotaV1.md) |  | [optional] 
**QuotasUsed** | Pointer to [**ProjectUsageV1**](ProjectUsageV1.md) |  | [optional] 
**NetworkStatus** | Pointer to [**NetworkStatusV1**](NetworkStatusV1.md) |  | [optional] 
**Keys** | Pointer to [**[]ProjectKeyV1**](ProjectKeyV1.md) |  | [optional] 

## Methods

### NewProjectWithKeysV1

`func NewProjectWithKeysV1(id string, ) *ProjectWithKeysV1`

NewProjectWithKeysV1 instantiates a new ProjectWithKeysV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWithKeysV1WithDefaults

`func NewProjectWithKeysV1WithDefaults() *ProjectWithKeysV1`

NewProjectWithKeysV1WithDefaults instantiates a new ProjectWithKeysV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectWithKeysV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectWithKeysV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectWithKeysV1) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectWithKeysV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectWithKeysV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectWithKeysV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProjectWithKeysV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProjectWithKeysV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProjectWithKeysV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSettings

`func (o *ProjectWithKeysV1) GetSettings() ProjectSettingsV1`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *ProjectWithKeysV1) GetSettingsOk() (*ProjectSettingsV1, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *ProjectWithKeysV1) SetSettings(v ProjectSettingsV1)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *ProjectWithKeysV1) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetQuotas

`func (o *ProjectWithKeysV1) GetQuotas() ProjectQuotaV1`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *ProjectWithKeysV1) GetQuotasOk() (*ProjectQuotaV1, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *ProjectWithKeysV1) SetQuotas(v ProjectQuotaV1)`

SetQuotas sets Quotas field to given value.

### HasQuotas

`func (o *ProjectWithKeysV1) HasQuotas() bool`

HasQuotas returns a boolean if a field has been set.

### GetQuotasUsed

`func (o *ProjectWithKeysV1) GetQuotasUsed() ProjectUsageV1`

GetQuotasUsed returns the QuotasUsed field if non-nil, zero value otherwise.

### GetQuotasUsedOk

`func (o *ProjectWithKeysV1) GetQuotasUsedOk() (*ProjectUsageV1, bool)`

GetQuotasUsedOk returns a tuple with the QuotasUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotasUsed

`func (o *ProjectWithKeysV1) SetQuotasUsed(v ProjectUsageV1)`

SetQuotasUsed sets QuotasUsed field to given value.

### HasQuotasUsed

`func (o *ProjectWithKeysV1) HasQuotasUsed() bool`

HasQuotasUsed returns a boolean if a field has been set.

### GetNetworkStatus

`func (o *ProjectWithKeysV1) GetNetworkStatus() NetworkStatusV1`

GetNetworkStatus returns the NetworkStatus field if non-nil, zero value otherwise.

### GetNetworkStatusOk

`func (o *ProjectWithKeysV1) GetNetworkStatusOk() (*NetworkStatusV1, bool)`

GetNetworkStatusOk returns a tuple with the NetworkStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkStatus

`func (o *ProjectWithKeysV1) SetNetworkStatus(v NetworkStatusV1)`

SetNetworkStatus sets NetworkStatus field to given value.

### HasNetworkStatus

`func (o *ProjectWithKeysV1) HasNetworkStatus() bool`

HasNetworkStatus returns a boolean if a field has been set.

### GetKeys

`func (o *ProjectWithKeysV1) GetKeys() []ProjectKeyV1`

GetKeys returns the Keys field if non-nil, zero value otherwise.

### GetKeysOk

`func (o *ProjectWithKeysV1) GetKeysOk() (*[]ProjectKeyV1, bool)`

GetKeysOk returns a tuple with the Keys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeys

`func (o *ProjectWithKeysV1) SetKeys(v []ProjectKeyV1)`

SetKeys sets Keys field to given value.

### HasKeys

`func (o *ProjectWithKeysV1) HasKeys() bool`

HasKeys returns a boolean if a field has been set.

### SetKeysNil

`func (o *ProjectWithKeysV1) SetKeysNil(b bool)`

 SetKeysNil sets the value for Keys to be an explicit nil

### UnsetKeys
`func (o *ProjectWithKeysV1) UnsetKeys()`

UnsetKeys ensures that no value is present for Keys, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


