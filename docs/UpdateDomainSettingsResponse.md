# UpdateDomainSettingsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainId** | **string** | Domain identifier. | 
**Settings** | [**UpdateDomainSettingsResponseSettings**](UpdateDomainSettingsResponseSettings.md) |  | 
**TrialExtension** | Pointer to [**TrialExtension**](TrialExtension.md) |  | [optional] 
**DeviceAutoShutdown** | Pointer to [**DeviceAutoShutdownSchema**](DeviceAutoShutdownSchema.md) |  | [optional] 
**AllowedDevicesFilters** | Pointer to [**[]AllowedDevicesFilterSchema**](AllowedDevicesFilterSchema.md) | Applied device/firmware allowlist filters. | [optional] 
**Webplayer** | Pointer to [**UpdateDomainSettingsResponseWebplayer**](UpdateDomainSettingsResponseWebplayer.md) |  | [optional] 
**SnapshotSharingPermissions** | Pointer to [**UpdateDomainSettingsResponseSnapshotSharingPermissions**](UpdateDomainSettingsResponseSnapshotSharingPermissions.md) |  | [optional] 

## Methods

### NewUpdateDomainSettingsResponse

`func NewUpdateDomainSettingsResponse(domainId string, settings UpdateDomainSettingsResponseSettings, ) *UpdateDomainSettingsResponse`

NewUpdateDomainSettingsResponse instantiates a new UpdateDomainSettingsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDomainSettingsResponseWithDefaults

`func NewUpdateDomainSettingsResponseWithDefaults() *UpdateDomainSettingsResponse`

NewUpdateDomainSettingsResponseWithDefaults instantiates a new UpdateDomainSettingsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainId

`func (o *UpdateDomainSettingsResponse) GetDomainId() string`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *UpdateDomainSettingsResponse) GetDomainIdOk() (*string, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *UpdateDomainSettingsResponse) SetDomainId(v string)`

SetDomainId sets DomainId field to given value.


### GetSettings

`func (o *UpdateDomainSettingsResponse) GetSettings() UpdateDomainSettingsResponseSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *UpdateDomainSettingsResponse) GetSettingsOk() (*UpdateDomainSettingsResponseSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *UpdateDomainSettingsResponse) SetSettings(v UpdateDomainSettingsResponseSettings)`

SetSettings sets Settings field to given value.


### GetTrialExtension

`func (o *UpdateDomainSettingsResponse) GetTrialExtension() TrialExtension`

GetTrialExtension returns the TrialExtension field if non-nil, zero value otherwise.

### GetTrialExtensionOk

`func (o *UpdateDomainSettingsResponse) GetTrialExtensionOk() (*TrialExtension, bool)`

GetTrialExtensionOk returns a tuple with the TrialExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialExtension

`func (o *UpdateDomainSettingsResponse) SetTrialExtension(v TrialExtension)`

SetTrialExtension sets TrialExtension field to given value.

### HasTrialExtension

`func (o *UpdateDomainSettingsResponse) HasTrialExtension() bool`

HasTrialExtension returns a boolean if a field has been set.

### GetDeviceAutoShutdown

`func (o *UpdateDomainSettingsResponse) GetDeviceAutoShutdown() DeviceAutoShutdownSchema`

GetDeviceAutoShutdown returns the DeviceAutoShutdown field if non-nil, zero value otherwise.

### GetDeviceAutoShutdownOk

`func (o *UpdateDomainSettingsResponse) GetDeviceAutoShutdownOk() (*DeviceAutoShutdownSchema, bool)`

GetDeviceAutoShutdownOk returns a tuple with the DeviceAutoShutdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceAutoShutdown

`func (o *UpdateDomainSettingsResponse) SetDeviceAutoShutdown(v DeviceAutoShutdownSchema)`

SetDeviceAutoShutdown sets DeviceAutoShutdown field to given value.

### HasDeviceAutoShutdown

`func (o *UpdateDomainSettingsResponse) HasDeviceAutoShutdown() bool`

HasDeviceAutoShutdown returns a boolean if a field has been set.

### GetAllowedDevicesFilters

`func (o *UpdateDomainSettingsResponse) GetAllowedDevicesFilters() []AllowedDevicesFilterSchema`

GetAllowedDevicesFilters returns the AllowedDevicesFilters field if non-nil, zero value otherwise.

### GetAllowedDevicesFiltersOk

`func (o *UpdateDomainSettingsResponse) GetAllowedDevicesFiltersOk() (*[]AllowedDevicesFilterSchema, bool)`

GetAllowedDevicesFiltersOk returns a tuple with the AllowedDevicesFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedDevicesFilters

`func (o *UpdateDomainSettingsResponse) SetAllowedDevicesFilters(v []AllowedDevicesFilterSchema)`

SetAllowedDevicesFilters sets AllowedDevicesFilters field to given value.

### HasAllowedDevicesFilters

`func (o *UpdateDomainSettingsResponse) HasAllowedDevicesFilters() bool`

HasAllowedDevicesFilters returns a boolean if a field has been set.

### GetWebplayer

`func (o *UpdateDomainSettingsResponse) GetWebplayer() UpdateDomainSettingsResponseWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *UpdateDomainSettingsResponse) GetWebplayerOk() (*UpdateDomainSettingsResponseWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *UpdateDomainSettingsResponse) SetWebplayer(v UpdateDomainSettingsResponseWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *UpdateDomainSettingsResponse) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetSnapshotSharingPermissions

`func (o *UpdateDomainSettingsResponse) GetSnapshotSharingPermissions() UpdateDomainSettingsResponseSnapshotSharingPermissions`

GetSnapshotSharingPermissions returns the SnapshotSharingPermissions field if non-nil, zero value otherwise.

### GetSnapshotSharingPermissionsOk

`func (o *UpdateDomainSettingsResponse) GetSnapshotSharingPermissionsOk() (*UpdateDomainSettingsResponseSnapshotSharingPermissions, bool)`

GetSnapshotSharingPermissionsOk returns a tuple with the SnapshotSharingPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotSharingPermissions

`func (o *UpdateDomainSettingsResponse) SetSnapshotSharingPermissions(v UpdateDomainSettingsResponseSnapshotSharingPermissions)`

SetSnapshotSharingPermissions sets SnapshotSharingPermissions field to given value.

### HasSnapshotSharingPermissions

`func (o *UpdateDomainSettingsResponse) HasSnapshotSharingPermissions() bool`

HasSnapshotSharingPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


