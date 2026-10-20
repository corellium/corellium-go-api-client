# ConfigResponseV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OnSite** | Pointer to **NullableBool** | Denotes whether it&#39;s an on-site install | [optional] 
**NetworkTypes** | Pointer to **[]string** | Valid network types (e.g. \&quot;nat\&quot;, \&quot;bridged\&quot;, \&quot;routed\&quot;) | [optional] 
**NetworkType** | Pointer to **NullableString** | Current network type setting | [optional] 
**ShowDomainSettings** | Pointer to **NullableBool** | Denotes whether to show domain settings | [optional] 
**Version** | Pointer to **NullableString** | Denotes the version | [optional] 
**InvalidBuild** | Pointer to **NullableBool** | Denotes whether the build is invalid | [optional] 
**SepSim** | Pointer to **NullableBool** | Denotes whether sepSim is enabled | [optional] 
**InstallerAvailable** | Pointer to **NullableBool** | Denotes whether installer is available | [optional] 
**InvoicedPublishableKey** | Pointer to **NullableString** | API publishable key to use for Invoiced | [optional] 
**StripePublicKey** | Pointer to **NullableString** | Stripe public key | [optional] 
**IntercomId** | Pointer to **NullableString** | Intercom app ID, also known as workspace ID | [optional] 
**GtmId** | Pointer to **NullableString** | Google Tag Manager | [optional] 
**BillingBackend** | Pointer to **NullableString** | Default backend billing api name for new subscriptions (e.g. \&quot;stripe\&quot;) | [optional] 
**Maintenance** | Pointer to **interface{}** | Denotes whether the server is undergoing maintenance (legacy v1 shape; v3 returns Maintenance|null) | [optional] 
**Logging** | Pointer to [**LoggingV1**](LoggingV1.md) |  | [optional] 
**CloudAdmin** | Pointer to **NullableString** | URL for cloud admin login | [optional] 
**FilesAdmin** | Pointer to **NullableString** | URL for files admin login | [optional] 
**CloudDomain** | Pointer to **NullableString** | Cloud domain name (usually corellium.com or staging.corellium.com) | [optional] 
**BillingDomain** | Pointer to **NullableString** | Billing domain name | [optional] 
**AppDomain** | Pointer to **NullableString** | App domain name (usually app.corellium.com or app.staging.corellium.com) | [optional] 
**MaxNetworkMonitorFileSize** | Pointer to **NullableString** | Maximum network monitor file size | [optional] 
**EnableFirmwareImageUpload** | Pointer to **NullableBool** | Denotes whether users can upload firmware images | [optional] 
**AuthProviders** | Pointer to [**[]AuthProviderV1**](AuthProviderV1.md) | Auth providers | [optional] 
**SnapshotLimit** | Pointer to **NullableFloat32** | Maximum number of snapshots to allow | [optional] 
**MaxKernelSize** | Pointer to **NullableFloat32** | The maximum size, in bytes, (default: 100 MiB) that an uploaded kernel should be | [optional] 
**MaxRamdiskSize** | Pointer to **NullableFloat32** | The maximum size, in bytes, (default: 500 MiB) that an uploaded ramdisk should be | [optional] 
**CharmSDK** | Pointer to **NullableBool** | Denotes whether charmSDK is enabled | [optional] 
**Trial** | Pointer to [**TrialV1**](TrialV1.md) |  | [optional] 
**SentryUrl** | Pointer to **NullableString** | Sentry URL | [optional] 
**DomainAuthenticationProviders** | Pointer to **NullableBool** | If enabled, adds the default providers in their current configuration | [optional] 
**DefaultSsid** | Pointer to **NullableString** | The configured Default SSID from /etc/corellium/setup.json | [optional] 
**CoordinatorConfig** | Pointer to [**CoordinatorConfigV1**](CoordinatorConfigV1.md) |  | [optional] 

## Methods

### NewConfigResponseV1

`func NewConfigResponseV1() *ConfigResponseV1`

NewConfigResponseV1 instantiates a new ConfigResponseV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigResponseV1WithDefaults

`func NewConfigResponseV1WithDefaults() *ConfigResponseV1`

NewConfigResponseV1WithDefaults instantiates a new ConfigResponseV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOnSite

`func (o *ConfigResponseV1) GetOnSite() bool`

GetOnSite returns the OnSite field if non-nil, zero value otherwise.

### GetOnSiteOk

`func (o *ConfigResponseV1) GetOnSiteOk() (*bool, bool)`

GetOnSiteOk returns a tuple with the OnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnSite

`func (o *ConfigResponseV1) SetOnSite(v bool)`

SetOnSite sets OnSite field to given value.

### HasOnSite

`func (o *ConfigResponseV1) HasOnSite() bool`

HasOnSite returns a boolean if a field has been set.

### SetOnSiteNil

`func (o *ConfigResponseV1) SetOnSiteNil(b bool)`

 SetOnSiteNil sets the value for OnSite to be an explicit nil

### UnsetOnSite
`func (o *ConfigResponseV1) UnsetOnSite()`

UnsetOnSite ensures that no value is present for OnSite, not even an explicit nil
### GetNetworkTypes

`func (o *ConfigResponseV1) GetNetworkTypes() []string`

GetNetworkTypes returns the NetworkTypes field if non-nil, zero value otherwise.

### GetNetworkTypesOk

`func (o *ConfigResponseV1) GetNetworkTypesOk() (*[]string, bool)`

GetNetworkTypesOk returns a tuple with the NetworkTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTypes

`func (o *ConfigResponseV1) SetNetworkTypes(v []string)`

SetNetworkTypes sets NetworkTypes field to given value.

### HasNetworkTypes

`func (o *ConfigResponseV1) HasNetworkTypes() bool`

HasNetworkTypes returns a boolean if a field has been set.

### SetNetworkTypesNil

`func (o *ConfigResponseV1) SetNetworkTypesNil(b bool)`

 SetNetworkTypesNil sets the value for NetworkTypes to be an explicit nil

### UnsetNetworkTypes
`func (o *ConfigResponseV1) UnsetNetworkTypes()`

UnsetNetworkTypes ensures that no value is present for NetworkTypes, not even an explicit nil
### GetNetworkType

`func (o *ConfigResponseV1) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *ConfigResponseV1) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *ConfigResponseV1) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.

### HasNetworkType

`func (o *ConfigResponseV1) HasNetworkType() bool`

HasNetworkType returns a boolean if a field has been set.

### SetNetworkTypeNil

`func (o *ConfigResponseV1) SetNetworkTypeNil(b bool)`

 SetNetworkTypeNil sets the value for NetworkType to be an explicit nil

### UnsetNetworkType
`func (o *ConfigResponseV1) UnsetNetworkType()`

UnsetNetworkType ensures that no value is present for NetworkType, not even an explicit nil
### GetShowDomainSettings

`func (o *ConfigResponseV1) GetShowDomainSettings() bool`

GetShowDomainSettings returns the ShowDomainSettings field if non-nil, zero value otherwise.

### GetShowDomainSettingsOk

`func (o *ConfigResponseV1) GetShowDomainSettingsOk() (*bool, bool)`

GetShowDomainSettingsOk returns a tuple with the ShowDomainSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDomainSettings

`func (o *ConfigResponseV1) SetShowDomainSettings(v bool)`

SetShowDomainSettings sets ShowDomainSettings field to given value.

### HasShowDomainSettings

`func (o *ConfigResponseV1) HasShowDomainSettings() bool`

HasShowDomainSettings returns a boolean if a field has been set.

### SetShowDomainSettingsNil

`func (o *ConfigResponseV1) SetShowDomainSettingsNil(b bool)`

 SetShowDomainSettingsNil sets the value for ShowDomainSettings to be an explicit nil

### UnsetShowDomainSettings
`func (o *ConfigResponseV1) UnsetShowDomainSettings()`

UnsetShowDomainSettings ensures that no value is present for ShowDomainSettings, not even an explicit nil
### GetVersion

`func (o *ConfigResponseV1) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ConfigResponseV1) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ConfigResponseV1) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ConfigResponseV1) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *ConfigResponseV1) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *ConfigResponseV1) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetInvalidBuild

`func (o *ConfigResponseV1) GetInvalidBuild() bool`

GetInvalidBuild returns the InvalidBuild field if non-nil, zero value otherwise.

### GetInvalidBuildOk

`func (o *ConfigResponseV1) GetInvalidBuildOk() (*bool, bool)`

GetInvalidBuildOk returns a tuple with the InvalidBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidBuild

`func (o *ConfigResponseV1) SetInvalidBuild(v bool)`

SetInvalidBuild sets InvalidBuild field to given value.

### HasInvalidBuild

`func (o *ConfigResponseV1) HasInvalidBuild() bool`

HasInvalidBuild returns a boolean if a field has been set.

### SetInvalidBuildNil

`func (o *ConfigResponseV1) SetInvalidBuildNil(b bool)`

 SetInvalidBuildNil sets the value for InvalidBuild to be an explicit nil

### UnsetInvalidBuild
`func (o *ConfigResponseV1) UnsetInvalidBuild()`

UnsetInvalidBuild ensures that no value is present for InvalidBuild, not even an explicit nil
### GetSepSim

`func (o *ConfigResponseV1) GetSepSim() bool`

GetSepSim returns the SepSim field if non-nil, zero value otherwise.

### GetSepSimOk

`func (o *ConfigResponseV1) GetSepSimOk() (*bool, bool)`

GetSepSimOk returns a tuple with the SepSim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepSim

`func (o *ConfigResponseV1) SetSepSim(v bool)`

SetSepSim sets SepSim field to given value.

### HasSepSim

`func (o *ConfigResponseV1) HasSepSim() bool`

HasSepSim returns a boolean if a field has been set.

### SetSepSimNil

`func (o *ConfigResponseV1) SetSepSimNil(b bool)`

 SetSepSimNil sets the value for SepSim to be an explicit nil

### UnsetSepSim
`func (o *ConfigResponseV1) UnsetSepSim()`

UnsetSepSim ensures that no value is present for SepSim, not even an explicit nil
### GetInstallerAvailable

`func (o *ConfigResponseV1) GetInstallerAvailable() bool`

GetInstallerAvailable returns the InstallerAvailable field if non-nil, zero value otherwise.

### GetInstallerAvailableOk

`func (o *ConfigResponseV1) GetInstallerAvailableOk() (*bool, bool)`

GetInstallerAvailableOk returns a tuple with the InstallerAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallerAvailable

`func (o *ConfigResponseV1) SetInstallerAvailable(v bool)`

SetInstallerAvailable sets InstallerAvailable field to given value.

### HasInstallerAvailable

`func (o *ConfigResponseV1) HasInstallerAvailable() bool`

HasInstallerAvailable returns a boolean if a field has been set.

### SetInstallerAvailableNil

`func (o *ConfigResponseV1) SetInstallerAvailableNil(b bool)`

 SetInstallerAvailableNil sets the value for InstallerAvailable to be an explicit nil

### UnsetInstallerAvailable
`func (o *ConfigResponseV1) UnsetInstallerAvailable()`

UnsetInstallerAvailable ensures that no value is present for InstallerAvailable, not even an explicit nil
### GetInvoicedPublishableKey

`func (o *ConfigResponseV1) GetInvoicedPublishableKey() string`

GetInvoicedPublishableKey returns the InvoicedPublishableKey field if non-nil, zero value otherwise.

### GetInvoicedPublishableKeyOk

`func (o *ConfigResponseV1) GetInvoicedPublishableKeyOk() (*string, bool)`

GetInvoicedPublishableKeyOk returns a tuple with the InvoicedPublishableKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoicedPublishableKey

`func (o *ConfigResponseV1) SetInvoicedPublishableKey(v string)`

SetInvoicedPublishableKey sets InvoicedPublishableKey field to given value.

### HasInvoicedPublishableKey

`func (o *ConfigResponseV1) HasInvoicedPublishableKey() bool`

HasInvoicedPublishableKey returns a boolean if a field has been set.

### SetInvoicedPublishableKeyNil

`func (o *ConfigResponseV1) SetInvoicedPublishableKeyNil(b bool)`

 SetInvoicedPublishableKeyNil sets the value for InvoicedPublishableKey to be an explicit nil

### UnsetInvoicedPublishableKey
`func (o *ConfigResponseV1) UnsetInvoicedPublishableKey()`

UnsetInvoicedPublishableKey ensures that no value is present for InvoicedPublishableKey, not even an explicit nil
### GetStripePublicKey

`func (o *ConfigResponseV1) GetStripePublicKey() string`

GetStripePublicKey returns the StripePublicKey field if non-nil, zero value otherwise.

### GetStripePublicKeyOk

`func (o *ConfigResponseV1) GetStripePublicKeyOk() (*string, bool)`

GetStripePublicKeyOk returns a tuple with the StripePublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripePublicKey

`func (o *ConfigResponseV1) SetStripePublicKey(v string)`

SetStripePublicKey sets StripePublicKey field to given value.

### HasStripePublicKey

`func (o *ConfigResponseV1) HasStripePublicKey() bool`

HasStripePublicKey returns a boolean if a field has been set.

### SetStripePublicKeyNil

`func (o *ConfigResponseV1) SetStripePublicKeyNil(b bool)`

 SetStripePublicKeyNil sets the value for StripePublicKey to be an explicit nil

### UnsetStripePublicKey
`func (o *ConfigResponseV1) UnsetStripePublicKey()`

UnsetStripePublicKey ensures that no value is present for StripePublicKey, not even an explicit nil
### GetIntercomId

`func (o *ConfigResponseV1) GetIntercomId() string`

GetIntercomId returns the IntercomId field if non-nil, zero value otherwise.

### GetIntercomIdOk

`func (o *ConfigResponseV1) GetIntercomIdOk() (*string, bool)`

GetIntercomIdOk returns a tuple with the IntercomId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercomId

`func (o *ConfigResponseV1) SetIntercomId(v string)`

SetIntercomId sets IntercomId field to given value.

### HasIntercomId

`func (o *ConfigResponseV1) HasIntercomId() bool`

HasIntercomId returns a boolean if a field has been set.

### SetIntercomIdNil

`func (o *ConfigResponseV1) SetIntercomIdNil(b bool)`

 SetIntercomIdNil sets the value for IntercomId to be an explicit nil

### UnsetIntercomId
`func (o *ConfigResponseV1) UnsetIntercomId()`

UnsetIntercomId ensures that no value is present for IntercomId, not even an explicit nil
### GetGtmId

`func (o *ConfigResponseV1) GetGtmId() string`

GetGtmId returns the GtmId field if non-nil, zero value otherwise.

### GetGtmIdOk

`func (o *ConfigResponseV1) GetGtmIdOk() (*string, bool)`

GetGtmIdOk returns a tuple with the GtmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtmId

`func (o *ConfigResponseV1) SetGtmId(v string)`

SetGtmId sets GtmId field to given value.

### HasGtmId

`func (o *ConfigResponseV1) HasGtmId() bool`

HasGtmId returns a boolean if a field has been set.

### SetGtmIdNil

`func (o *ConfigResponseV1) SetGtmIdNil(b bool)`

 SetGtmIdNil sets the value for GtmId to be an explicit nil

### UnsetGtmId
`func (o *ConfigResponseV1) UnsetGtmId()`

UnsetGtmId ensures that no value is present for GtmId, not even an explicit nil
### GetBillingBackend

`func (o *ConfigResponseV1) GetBillingBackend() string`

GetBillingBackend returns the BillingBackend field if non-nil, zero value otherwise.

### GetBillingBackendOk

`func (o *ConfigResponseV1) GetBillingBackendOk() (*string, bool)`

GetBillingBackendOk returns a tuple with the BillingBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingBackend

`func (o *ConfigResponseV1) SetBillingBackend(v string)`

SetBillingBackend sets BillingBackend field to given value.

### HasBillingBackend

`func (o *ConfigResponseV1) HasBillingBackend() bool`

HasBillingBackend returns a boolean if a field has been set.

### SetBillingBackendNil

`func (o *ConfigResponseV1) SetBillingBackendNil(b bool)`

 SetBillingBackendNil sets the value for BillingBackend to be an explicit nil

### UnsetBillingBackend
`func (o *ConfigResponseV1) UnsetBillingBackend()`

UnsetBillingBackend ensures that no value is present for BillingBackend, not even an explicit nil
### GetMaintenance

`func (o *ConfigResponseV1) GetMaintenance() interface{}`

GetMaintenance returns the Maintenance field if non-nil, zero value otherwise.

### GetMaintenanceOk

`func (o *ConfigResponseV1) GetMaintenanceOk() (*interface{}, bool)`

GetMaintenanceOk returns a tuple with the Maintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenance

`func (o *ConfigResponseV1) SetMaintenance(v interface{})`

SetMaintenance sets Maintenance field to given value.

### HasMaintenance

`func (o *ConfigResponseV1) HasMaintenance() bool`

HasMaintenance returns a boolean if a field has been set.

### SetMaintenanceNil

`func (o *ConfigResponseV1) SetMaintenanceNil(b bool)`

 SetMaintenanceNil sets the value for Maintenance to be an explicit nil

### UnsetMaintenance
`func (o *ConfigResponseV1) UnsetMaintenance()`

UnsetMaintenance ensures that no value is present for Maintenance, not even an explicit nil
### GetLogging

`func (o *ConfigResponseV1) GetLogging() LoggingV1`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ConfigResponseV1) GetLoggingOk() (*LoggingV1, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ConfigResponseV1) SetLogging(v LoggingV1)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ConfigResponseV1) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetCloudAdmin

`func (o *ConfigResponseV1) GetCloudAdmin() string`

GetCloudAdmin returns the CloudAdmin field if non-nil, zero value otherwise.

### GetCloudAdminOk

`func (o *ConfigResponseV1) GetCloudAdminOk() (*string, bool)`

GetCloudAdminOk returns a tuple with the CloudAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudAdmin

`func (o *ConfigResponseV1) SetCloudAdmin(v string)`

SetCloudAdmin sets CloudAdmin field to given value.

### HasCloudAdmin

`func (o *ConfigResponseV1) HasCloudAdmin() bool`

HasCloudAdmin returns a boolean if a field has been set.

### SetCloudAdminNil

`func (o *ConfigResponseV1) SetCloudAdminNil(b bool)`

 SetCloudAdminNil sets the value for CloudAdmin to be an explicit nil

### UnsetCloudAdmin
`func (o *ConfigResponseV1) UnsetCloudAdmin()`

UnsetCloudAdmin ensures that no value is present for CloudAdmin, not even an explicit nil
### GetFilesAdmin

`func (o *ConfigResponseV1) GetFilesAdmin() string`

GetFilesAdmin returns the FilesAdmin field if non-nil, zero value otherwise.

### GetFilesAdminOk

`func (o *ConfigResponseV1) GetFilesAdminOk() (*string, bool)`

GetFilesAdminOk returns a tuple with the FilesAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesAdmin

`func (o *ConfigResponseV1) SetFilesAdmin(v string)`

SetFilesAdmin sets FilesAdmin field to given value.

### HasFilesAdmin

`func (o *ConfigResponseV1) HasFilesAdmin() bool`

HasFilesAdmin returns a boolean if a field has been set.

### SetFilesAdminNil

`func (o *ConfigResponseV1) SetFilesAdminNil(b bool)`

 SetFilesAdminNil sets the value for FilesAdmin to be an explicit nil

### UnsetFilesAdmin
`func (o *ConfigResponseV1) UnsetFilesAdmin()`

UnsetFilesAdmin ensures that no value is present for FilesAdmin, not even an explicit nil
### GetCloudDomain

`func (o *ConfigResponseV1) GetCloudDomain() string`

GetCloudDomain returns the CloudDomain field if non-nil, zero value otherwise.

### GetCloudDomainOk

`func (o *ConfigResponseV1) GetCloudDomainOk() (*string, bool)`

GetCloudDomainOk returns a tuple with the CloudDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudDomain

`func (o *ConfigResponseV1) SetCloudDomain(v string)`

SetCloudDomain sets CloudDomain field to given value.

### HasCloudDomain

`func (o *ConfigResponseV1) HasCloudDomain() bool`

HasCloudDomain returns a boolean if a field has been set.

### SetCloudDomainNil

`func (o *ConfigResponseV1) SetCloudDomainNil(b bool)`

 SetCloudDomainNil sets the value for CloudDomain to be an explicit nil

### UnsetCloudDomain
`func (o *ConfigResponseV1) UnsetCloudDomain()`

UnsetCloudDomain ensures that no value is present for CloudDomain, not even an explicit nil
### GetBillingDomain

`func (o *ConfigResponseV1) GetBillingDomain() string`

GetBillingDomain returns the BillingDomain field if non-nil, zero value otherwise.

### GetBillingDomainOk

`func (o *ConfigResponseV1) GetBillingDomainOk() (*string, bool)`

GetBillingDomainOk returns a tuple with the BillingDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingDomain

`func (o *ConfigResponseV1) SetBillingDomain(v string)`

SetBillingDomain sets BillingDomain field to given value.

### HasBillingDomain

`func (o *ConfigResponseV1) HasBillingDomain() bool`

HasBillingDomain returns a boolean if a field has been set.

### SetBillingDomainNil

`func (o *ConfigResponseV1) SetBillingDomainNil(b bool)`

 SetBillingDomainNil sets the value for BillingDomain to be an explicit nil

### UnsetBillingDomain
`func (o *ConfigResponseV1) UnsetBillingDomain()`

UnsetBillingDomain ensures that no value is present for BillingDomain, not even an explicit nil
### GetAppDomain

`func (o *ConfigResponseV1) GetAppDomain() string`

GetAppDomain returns the AppDomain field if non-nil, zero value otherwise.

### GetAppDomainOk

`func (o *ConfigResponseV1) GetAppDomainOk() (*string, bool)`

GetAppDomainOk returns a tuple with the AppDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppDomain

`func (o *ConfigResponseV1) SetAppDomain(v string)`

SetAppDomain sets AppDomain field to given value.

### HasAppDomain

`func (o *ConfigResponseV1) HasAppDomain() bool`

HasAppDomain returns a boolean if a field has been set.

### SetAppDomainNil

`func (o *ConfigResponseV1) SetAppDomainNil(b bool)`

 SetAppDomainNil sets the value for AppDomain to be an explicit nil

### UnsetAppDomain
`func (o *ConfigResponseV1) UnsetAppDomain()`

UnsetAppDomain ensures that no value is present for AppDomain, not even an explicit nil
### GetMaxNetworkMonitorFileSize

`func (o *ConfigResponseV1) GetMaxNetworkMonitorFileSize() string`

GetMaxNetworkMonitorFileSize returns the MaxNetworkMonitorFileSize field if non-nil, zero value otherwise.

### GetMaxNetworkMonitorFileSizeOk

`func (o *ConfigResponseV1) GetMaxNetworkMonitorFileSizeOk() (*string, bool)`

GetMaxNetworkMonitorFileSizeOk returns a tuple with the MaxNetworkMonitorFileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNetworkMonitorFileSize

`func (o *ConfigResponseV1) SetMaxNetworkMonitorFileSize(v string)`

SetMaxNetworkMonitorFileSize sets MaxNetworkMonitorFileSize field to given value.

### HasMaxNetworkMonitorFileSize

`func (o *ConfigResponseV1) HasMaxNetworkMonitorFileSize() bool`

HasMaxNetworkMonitorFileSize returns a boolean if a field has been set.

### SetMaxNetworkMonitorFileSizeNil

`func (o *ConfigResponseV1) SetMaxNetworkMonitorFileSizeNil(b bool)`

 SetMaxNetworkMonitorFileSizeNil sets the value for MaxNetworkMonitorFileSize to be an explicit nil

### UnsetMaxNetworkMonitorFileSize
`func (o *ConfigResponseV1) UnsetMaxNetworkMonitorFileSize()`

UnsetMaxNetworkMonitorFileSize ensures that no value is present for MaxNetworkMonitorFileSize, not even an explicit nil
### GetEnableFirmwareImageUpload

`func (o *ConfigResponseV1) GetEnableFirmwareImageUpload() bool`

GetEnableFirmwareImageUpload returns the EnableFirmwareImageUpload field if non-nil, zero value otherwise.

### GetEnableFirmwareImageUploadOk

`func (o *ConfigResponseV1) GetEnableFirmwareImageUploadOk() (*bool, bool)`

GetEnableFirmwareImageUploadOk returns a tuple with the EnableFirmwareImageUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableFirmwareImageUpload

`func (o *ConfigResponseV1) SetEnableFirmwareImageUpload(v bool)`

SetEnableFirmwareImageUpload sets EnableFirmwareImageUpload field to given value.

### HasEnableFirmwareImageUpload

`func (o *ConfigResponseV1) HasEnableFirmwareImageUpload() bool`

HasEnableFirmwareImageUpload returns a boolean if a field has been set.

### SetEnableFirmwareImageUploadNil

`func (o *ConfigResponseV1) SetEnableFirmwareImageUploadNil(b bool)`

 SetEnableFirmwareImageUploadNil sets the value for EnableFirmwareImageUpload to be an explicit nil

### UnsetEnableFirmwareImageUpload
`func (o *ConfigResponseV1) UnsetEnableFirmwareImageUpload()`

UnsetEnableFirmwareImageUpload ensures that no value is present for EnableFirmwareImageUpload, not even an explicit nil
### GetAuthProviders

`func (o *ConfigResponseV1) GetAuthProviders() []AuthProviderV1`

GetAuthProviders returns the AuthProviders field if non-nil, zero value otherwise.

### GetAuthProvidersOk

`func (o *ConfigResponseV1) GetAuthProvidersOk() (*[]AuthProviderV1, bool)`

GetAuthProvidersOk returns a tuple with the AuthProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthProviders

`func (o *ConfigResponseV1) SetAuthProviders(v []AuthProviderV1)`

SetAuthProviders sets AuthProviders field to given value.

### HasAuthProviders

`func (o *ConfigResponseV1) HasAuthProviders() bool`

HasAuthProviders returns a boolean if a field has been set.

### SetAuthProvidersNil

`func (o *ConfigResponseV1) SetAuthProvidersNil(b bool)`

 SetAuthProvidersNil sets the value for AuthProviders to be an explicit nil

### UnsetAuthProviders
`func (o *ConfigResponseV1) UnsetAuthProviders()`

UnsetAuthProviders ensures that no value is present for AuthProviders, not even an explicit nil
### GetSnapshotLimit

`func (o *ConfigResponseV1) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *ConfigResponseV1) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *ConfigResponseV1) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.

### HasSnapshotLimit

`func (o *ConfigResponseV1) HasSnapshotLimit() bool`

HasSnapshotLimit returns a boolean if a field has been set.

### SetSnapshotLimitNil

`func (o *ConfigResponseV1) SetSnapshotLimitNil(b bool)`

 SetSnapshotLimitNil sets the value for SnapshotLimit to be an explicit nil

### UnsetSnapshotLimit
`func (o *ConfigResponseV1) UnsetSnapshotLimit()`

UnsetSnapshotLimit ensures that no value is present for SnapshotLimit, not even an explicit nil
### GetMaxKernelSize

`func (o *ConfigResponseV1) GetMaxKernelSize() float32`

GetMaxKernelSize returns the MaxKernelSize field if non-nil, zero value otherwise.

### GetMaxKernelSizeOk

`func (o *ConfigResponseV1) GetMaxKernelSizeOk() (*float32, bool)`

GetMaxKernelSizeOk returns a tuple with the MaxKernelSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxKernelSize

`func (o *ConfigResponseV1) SetMaxKernelSize(v float32)`

SetMaxKernelSize sets MaxKernelSize field to given value.

### HasMaxKernelSize

`func (o *ConfigResponseV1) HasMaxKernelSize() bool`

HasMaxKernelSize returns a boolean if a field has been set.

### SetMaxKernelSizeNil

`func (o *ConfigResponseV1) SetMaxKernelSizeNil(b bool)`

 SetMaxKernelSizeNil sets the value for MaxKernelSize to be an explicit nil

### UnsetMaxKernelSize
`func (o *ConfigResponseV1) UnsetMaxKernelSize()`

UnsetMaxKernelSize ensures that no value is present for MaxKernelSize, not even an explicit nil
### GetMaxRamdiskSize

`func (o *ConfigResponseV1) GetMaxRamdiskSize() float32`

GetMaxRamdiskSize returns the MaxRamdiskSize field if non-nil, zero value otherwise.

### GetMaxRamdiskSizeOk

`func (o *ConfigResponseV1) GetMaxRamdiskSizeOk() (*float32, bool)`

GetMaxRamdiskSizeOk returns a tuple with the MaxRamdiskSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRamdiskSize

`func (o *ConfigResponseV1) SetMaxRamdiskSize(v float32)`

SetMaxRamdiskSize sets MaxRamdiskSize field to given value.

### HasMaxRamdiskSize

`func (o *ConfigResponseV1) HasMaxRamdiskSize() bool`

HasMaxRamdiskSize returns a boolean if a field has been set.

### SetMaxRamdiskSizeNil

`func (o *ConfigResponseV1) SetMaxRamdiskSizeNil(b bool)`

 SetMaxRamdiskSizeNil sets the value for MaxRamdiskSize to be an explicit nil

### UnsetMaxRamdiskSize
`func (o *ConfigResponseV1) UnsetMaxRamdiskSize()`

UnsetMaxRamdiskSize ensures that no value is present for MaxRamdiskSize, not even an explicit nil
### GetCharmSDK

`func (o *ConfigResponseV1) GetCharmSDK() bool`

GetCharmSDK returns the CharmSDK field if non-nil, zero value otherwise.

### GetCharmSDKOk

`func (o *ConfigResponseV1) GetCharmSDKOk() (*bool, bool)`

GetCharmSDKOk returns a tuple with the CharmSDK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmSDK

`func (o *ConfigResponseV1) SetCharmSDK(v bool)`

SetCharmSDK sets CharmSDK field to given value.

### HasCharmSDK

`func (o *ConfigResponseV1) HasCharmSDK() bool`

HasCharmSDK returns a boolean if a field has been set.

### SetCharmSDKNil

`func (o *ConfigResponseV1) SetCharmSDKNil(b bool)`

 SetCharmSDKNil sets the value for CharmSDK to be an explicit nil

### UnsetCharmSDK
`func (o *ConfigResponseV1) UnsetCharmSDK()`

UnsetCharmSDK ensures that no value is present for CharmSDK, not even an explicit nil
### GetTrial

`func (o *ConfigResponseV1) GetTrial() TrialV1`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *ConfigResponseV1) GetTrialOk() (*TrialV1, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *ConfigResponseV1) SetTrial(v TrialV1)`

SetTrial sets Trial field to given value.

### HasTrial

`func (o *ConfigResponseV1) HasTrial() bool`

HasTrial returns a boolean if a field has been set.

### GetSentryUrl

`func (o *ConfigResponseV1) GetSentryUrl() string`

GetSentryUrl returns the SentryUrl field if non-nil, zero value otherwise.

### GetSentryUrlOk

`func (o *ConfigResponseV1) GetSentryUrlOk() (*string, bool)`

GetSentryUrlOk returns a tuple with the SentryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentryUrl

`func (o *ConfigResponseV1) SetSentryUrl(v string)`

SetSentryUrl sets SentryUrl field to given value.

### HasSentryUrl

`func (o *ConfigResponseV1) HasSentryUrl() bool`

HasSentryUrl returns a boolean if a field has been set.

### SetSentryUrlNil

`func (o *ConfigResponseV1) SetSentryUrlNil(b bool)`

 SetSentryUrlNil sets the value for SentryUrl to be an explicit nil

### UnsetSentryUrl
`func (o *ConfigResponseV1) UnsetSentryUrl()`

UnsetSentryUrl ensures that no value is present for SentryUrl, not even an explicit nil
### GetDomainAuthenticationProviders

`func (o *ConfigResponseV1) GetDomainAuthenticationProviders() bool`

GetDomainAuthenticationProviders returns the DomainAuthenticationProviders field if non-nil, zero value otherwise.

### GetDomainAuthenticationProvidersOk

`func (o *ConfigResponseV1) GetDomainAuthenticationProvidersOk() (*bool, bool)`

GetDomainAuthenticationProvidersOk returns a tuple with the DomainAuthenticationProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainAuthenticationProviders

`func (o *ConfigResponseV1) SetDomainAuthenticationProviders(v bool)`

SetDomainAuthenticationProviders sets DomainAuthenticationProviders field to given value.

### HasDomainAuthenticationProviders

`func (o *ConfigResponseV1) HasDomainAuthenticationProviders() bool`

HasDomainAuthenticationProviders returns a boolean if a field has been set.

### SetDomainAuthenticationProvidersNil

`func (o *ConfigResponseV1) SetDomainAuthenticationProvidersNil(b bool)`

 SetDomainAuthenticationProvidersNil sets the value for DomainAuthenticationProviders to be an explicit nil

### UnsetDomainAuthenticationProviders
`func (o *ConfigResponseV1) UnsetDomainAuthenticationProviders()`

UnsetDomainAuthenticationProviders ensures that no value is present for DomainAuthenticationProviders, not even an explicit nil
### GetDefaultSsid

`func (o *ConfigResponseV1) GetDefaultSsid() string`

GetDefaultSsid returns the DefaultSsid field if non-nil, zero value otherwise.

### GetDefaultSsidOk

`func (o *ConfigResponseV1) GetDefaultSsidOk() (*string, bool)`

GetDefaultSsidOk returns a tuple with the DefaultSsid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultSsid

`func (o *ConfigResponseV1) SetDefaultSsid(v string)`

SetDefaultSsid sets DefaultSsid field to given value.

### HasDefaultSsid

`func (o *ConfigResponseV1) HasDefaultSsid() bool`

HasDefaultSsid returns a boolean if a field has been set.

### SetDefaultSsidNil

`func (o *ConfigResponseV1) SetDefaultSsidNil(b bool)`

 SetDefaultSsidNil sets the value for DefaultSsid to be an explicit nil

### UnsetDefaultSsid
`func (o *ConfigResponseV1) UnsetDefaultSsid()`

UnsetDefaultSsid ensures that no value is present for DefaultSsid, not even an explicit nil
### GetCoordinatorConfig

`func (o *ConfigResponseV1) GetCoordinatorConfig() CoordinatorConfigV1`

GetCoordinatorConfig returns the CoordinatorConfig field if non-nil, zero value otherwise.

### GetCoordinatorConfigOk

`func (o *ConfigResponseV1) GetCoordinatorConfigOk() (*CoordinatorConfigV1, bool)`

GetCoordinatorConfigOk returns a tuple with the CoordinatorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorConfig

`func (o *ConfigResponseV1) SetCoordinatorConfig(v CoordinatorConfigV1)`

SetCoordinatorConfig sets CoordinatorConfig field to given value.

### HasCoordinatorConfig

`func (o *ConfigResponseV1) HasCoordinatorConfig() bool`

HasCoordinatorConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


