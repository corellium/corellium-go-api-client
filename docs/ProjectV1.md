# ProjectV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Project Identifier | 
**Name** | Pointer to **NullableString** | Project Name | [optional] 
**Settings** | Pointer to [**ProjectSettingsV1**](ProjectSettingsV1.md) |  | [optional] 
**Quotas** | Pointer to [**ProjectQuotaV1**](ProjectQuotaV1.md) |  | [optional] 
**QuotasUsed** | Pointer to [**ProjectUsageV1**](ProjectUsageV1.md) |  | [optional] 
**NetworkStatus** | Pointer to [**NetworkStatusV1**](NetworkStatusV1.md) |  | [optional] 

## Methods

### NewProjectV1

`func NewProjectV1(id string, ) *ProjectV1`

NewProjectV1 instantiates a new ProjectV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectV1WithDefaults

`func NewProjectV1WithDefaults() *ProjectV1`

NewProjectV1WithDefaults instantiates a new ProjectV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ProjectV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectV1) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProjectV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProjectV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProjectV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSettings

`func (o *ProjectV1) GetSettings() ProjectSettingsV1`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *ProjectV1) GetSettingsOk() (*ProjectSettingsV1, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *ProjectV1) SetSettings(v ProjectSettingsV1)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *ProjectV1) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetQuotas

`func (o *ProjectV1) GetQuotas() ProjectQuotaV1`

GetQuotas returns the Quotas field if non-nil, zero value otherwise.

### GetQuotasOk

`func (o *ProjectV1) GetQuotasOk() (*ProjectQuotaV1, bool)`

GetQuotasOk returns a tuple with the Quotas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotas

`func (o *ProjectV1) SetQuotas(v ProjectQuotaV1)`

SetQuotas sets Quotas field to given value.

### HasQuotas

`func (o *ProjectV1) HasQuotas() bool`

HasQuotas returns a boolean if a field has been set.

### GetQuotasUsed

`func (o *ProjectV1) GetQuotasUsed() ProjectUsageV1`

GetQuotasUsed returns the QuotasUsed field if non-nil, zero value otherwise.

### GetQuotasUsedOk

`func (o *ProjectV1) GetQuotasUsedOk() (*ProjectUsageV1, bool)`

GetQuotasUsedOk returns a tuple with the QuotasUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotasUsed

`func (o *ProjectV1) SetQuotasUsed(v ProjectUsageV1)`

SetQuotasUsed sets QuotasUsed field to given value.

### HasQuotasUsed

`func (o *ProjectV1) HasQuotasUsed() bool`

HasQuotasUsed returns a boolean if a field has been set.

### GetNetworkStatus

`func (o *ProjectV1) GetNetworkStatus() NetworkStatusV1`

GetNetworkStatus returns the NetworkStatus field if non-nil, zero value otherwise.

### GetNetworkStatusOk

`func (o *ProjectV1) GetNetworkStatusOk() (*NetworkStatusV1, bool)`

GetNetworkStatusOk returns a tuple with the NetworkStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkStatus

`func (o *ProjectV1) SetNetworkStatus(v NetworkStatusV1)`

SetNetworkStatus sets NetworkStatus field to given value.

### HasNetworkStatus

`func (o *ProjectV1) HasNetworkStatus() bool`

HasNetworkStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


