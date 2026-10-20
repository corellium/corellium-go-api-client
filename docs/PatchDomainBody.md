# PatchDomainBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotpRequired** | Pointer to **bool** | If true, every user in the domain must set up two-factor sign-in with a time-based one-time password (TOTP) authenticator app before they can use the platform. | [optional] 
**TrialExtension** | Pointer to [**TrialExtension**](TrialExtension.md) |  | [optional] 
**DeviceAutoShutdown** | Pointer to [**DeviceAutoShutdownSchema**](DeviceAutoShutdownSchema.md) |  | [optional] 
**AllowedDevicesFilters** | Pointer to [**[]AllowedDevicesFilterSchema**](AllowedDevicesFilterSchema.md) | Device/firmware allowlist filters. | [optional] 
**Webplayer** | Pointer to [**PatchDomainBodyWebplayer**](PatchDomainBodyWebplayer.md) |  | [optional] 
**SnapshotSharingPermissions** | Pointer to [**SnapshotSharingPermissionsRequestSchema**](SnapshotSharingPermissionsRequestSchema.md) |  | [optional] 

## Methods

### NewPatchDomainBody

`func NewPatchDomainBody() *PatchDomainBody`

NewPatchDomainBody instantiates a new PatchDomainBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchDomainBodyWithDefaults

`func NewPatchDomainBodyWithDefaults() *PatchDomainBody`

NewPatchDomainBodyWithDefaults instantiates a new PatchDomainBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotpRequired

`func (o *PatchDomainBody) GetTotpRequired() bool`

GetTotpRequired returns the TotpRequired field if non-nil, zero value otherwise.

### GetTotpRequiredOk

`func (o *PatchDomainBody) GetTotpRequiredOk() (*bool, bool)`

GetTotpRequiredOk returns a tuple with the TotpRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpRequired

`func (o *PatchDomainBody) SetTotpRequired(v bool)`

SetTotpRequired sets TotpRequired field to given value.

### HasTotpRequired

`func (o *PatchDomainBody) HasTotpRequired() bool`

HasTotpRequired returns a boolean if a field has been set.

### GetTrialExtension

`func (o *PatchDomainBody) GetTrialExtension() TrialExtension`

GetTrialExtension returns the TrialExtension field if non-nil, zero value otherwise.

### GetTrialExtensionOk

`func (o *PatchDomainBody) GetTrialExtensionOk() (*TrialExtension, bool)`

GetTrialExtensionOk returns a tuple with the TrialExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialExtension

`func (o *PatchDomainBody) SetTrialExtension(v TrialExtension)`

SetTrialExtension sets TrialExtension field to given value.

### HasTrialExtension

`func (o *PatchDomainBody) HasTrialExtension() bool`

HasTrialExtension returns a boolean if a field has been set.

### GetDeviceAutoShutdown

`func (o *PatchDomainBody) GetDeviceAutoShutdown() DeviceAutoShutdownSchema`

GetDeviceAutoShutdown returns the DeviceAutoShutdown field if non-nil, zero value otherwise.

### GetDeviceAutoShutdownOk

`func (o *PatchDomainBody) GetDeviceAutoShutdownOk() (*DeviceAutoShutdownSchema, bool)`

GetDeviceAutoShutdownOk returns a tuple with the DeviceAutoShutdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceAutoShutdown

`func (o *PatchDomainBody) SetDeviceAutoShutdown(v DeviceAutoShutdownSchema)`

SetDeviceAutoShutdown sets DeviceAutoShutdown field to given value.

### HasDeviceAutoShutdown

`func (o *PatchDomainBody) HasDeviceAutoShutdown() bool`

HasDeviceAutoShutdown returns a boolean if a field has been set.

### GetAllowedDevicesFilters

`func (o *PatchDomainBody) GetAllowedDevicesFilters() []AllowedDevicesFilterSchema`

GetAllowedDevicesFilters returns the AllowedDevicesFilters field if non-nil, zero value otherwise.

### GetAllowedDevicesFiltersOk

`func (o *PatchDomainBody) GetAllowedDevicesFiltersOk() (*[]AllowedDevicesFilterSchema, bool)`

GetAllowedDevicesFiltersOk returns a tuple with the AllowedDevicesFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedDevicesFilters

`func (o *PatchDomainBody) SetAllowedDevicesFilters(v []AllowedDevicesFilterSchema)`

SetAllowedDevicesFilters sets AllowedDevicesFilters field to given value.

### HasAllowedDevicesFilters

`func (o *PatchDomainBody) HasAllowedDevicesFilters() bool`

HasAllowedDevicesFilters returns a boolean if a field has been set.

### GetWebplayer

`func (o *PatchDomainBody) GetWebplayer() PatchDomainBodyWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *PatchDomainBody) GetWebplayerOk() (*PatchDomainBodyWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *PatchDomainBody) SetWebplayer(v PatchDomainBodyWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *PatchDomainBody) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetSnapshotSharingPermissions

`func (o *PatchDomainBody) GetSnapshotSharingPermissions() SnapshotSharingPermissionsRequestSchema`

GetSnapshotSharingPermissions returns the SnapshotSharingPermissions field if non-nil, zero value otherwise.

### GetSnapshotSharingPermissionsOk

`func (o *PatchDomainBody) GetSnapshotSharingPermissionsOk() (*SnapshotSharingPermissionsRequestSchema, bool)`

GetSnapshotSharingPermissionsOk returns a tuple with the SnapshotSharingPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotSharingPermissions

`func (o *PatchDomainBody) SetSnapshotSharingPermissions(v SnapshotSharingPermissionsRequestSchema)`

SetSnapshotSharingPermissions sets SnapshotSharingPermissions field to given value.

### HasSnapshotSharingPermissions

`func (o *PatchDomainBody) HasSnapshotSharingPermissions() bool`

HasSnapshotSharingPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


