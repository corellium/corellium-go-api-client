# ConfigResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OnSite** | **bool** | Denotes whether it&#39;s an on-site install. | 
**NetworkTypes** | **[]string** | Valid network types (e.g. \&quot;nat\&quot;, \&quot;bridged\&quot;, \&quot;routed\&quot;). | 
**NetworkType** | **string** | Current network type setting. | 
**ShowDomainSettings** | **bool** | Denotes whether to show domain settings. | 
**Version** | **string** | Denotes the version. | 
**InvalidBuild** | Pointer to **bool** | Denotes whether the build is invalid. | [optional] 
**SepSim** | **bool** | Denotes whether sepSim is enabled. | 
**InstallerAvailable** | **bool** | Denotes whether installer is available. | 
**StripePublicKey** | Pointer to **string** | Stripe public key. | [optional] 
**IntercomId** | Pointer to **string** | Intercom app ID, also known as workspace ID. | [optional] 
**GtmId** | Pointer to **string** | Google Tag Manager ID. | [optional] 
**BillingBackend** | Pointer to **NullableString** | Default backend billing API name for new subscriptions (e.g. \&quot;stripe\&quot;). | [optional] 
**Maintenance** | Pointer to [**NullableConfigResponseMaintenance**](ConfigResponseMaintenance.md) |  | [optional] 
**Logging** | Pointer to [**Logging**](Logging.md) |  | [optional] 
**CloudAdmin** | **string** | URL for cloud admin login. | 
**FilesAdmin** | **string** | URL for files admin login. | 
**CloudDomain** | Pointer to **string** | Cloud domain name (usually corellium.com or staging.corellium.com). | [optional] 
**BillingDomain** | Pointer to **string** | Billing domain name. | [optional] 
**AppDomain** | Pointer to **string** | App domain name (usually app.corellium.com or app.staging.corellium.com). | [optional] 
**MaxNetworkMonitorFileSize** | **string** | Maximum network monitor file size. | 
**EnableFirmwareImageUpload** | **bool** | Denotes whether users can upload firmware images. | 
**AuthProviders** | [**[]ConfigAuthProvider**](ConfigAuthProvider.md) | Auth providers. | 
**WelcomeMessage** | Pointer to **string** | Domain welcome message, when enabled. | [optional] 
**SnapshotLimit** | **float32** | Maximum number of snapshots to allow. | 
**MaxKernelSize** | **float32** | The maximum size, in bytes, (default: 100 MiB) that an uploaded kernel should be. | 
**MaxRamdiskSize** | **float32** | The maximum size, in bytes, (default: 500 MiB) that an uploaded ramdisk should be. | 
**CharmSdk** | Pointer to **bool** | Denotes whether charmSDK is enabled. | [optional] 
**Trial** | [**Trial**](Trial.md) |  | 
**SentryUrl** | Pointer to **string** | Sentry URL. | [optional] 
**DomainAuthenticationProviders** | Pointer to **bool** | If enabled, adds the default providers in their current configuration. | [optional] 
**RemoteGpu** | Pointer to **bool** | Whether remote GPU is enabled. | [optional] 
**DefaultSsid** | **string** | The configured default SSID from /etc/corellium/setup.json. | 
**AwsMarketplace** | Pointer to **bool** | Whether this is an AWS Marketplace deployment. | [optional] 
**OpenGAppsBinary** | Pointer to **string** | OpenGApps binary location. | [optional] 
**AirGapped** | Pointer to **bool** | Whether the deployment is airgapped. | [optional] 
**CoordinatorConfig** | [**CoordinatorConfig**](CoordinatorConfig.md) | Partial coordinator configuration. | 
**AiToolsConfig** | Pointer to [**ConfigResponseAiToolsConfig**](ConfigResponseAiToolsConfig.md) |  | [optional] 

## Methods

### NewConfigResponse

`func NewConfigResponse(onSite bool, networkTypes []string, networkType string, showDomainSettings bool, version string, sepSim bool, installerAvailable bool, cloudAdmin string, filesAdmin string, maxNetworkMonitorFileSize string, enableFirmwareImageUpload bool, authProviders []ConfigAuthProvider, snapshotLimit float32, maxKernelSize float32, maxRamdiskSize float32, trial Trial, defaultSsid string, coordinatorConfig CoordinatorConfig, ) *ConfigResponse`

NewConfigResponse instantiates a new ConfigResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigResponseWithDefaults

`func NewConfigResponseWithDefaults() *ConfigResponse`

NewConfigResponseWithDefaults instantiates a new ConfigResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOnSite

`func (o *ConfigResponse) GetOnSite() bool`

GetOnSite returns the OnSite field if non-nil, zero value otherwise.

### GetOnSiteOk

`func (o *ConfigResponse) GetOnSiteOk() (*bool, bool)`

GetOnSiteOk returns a tuple with the OnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnSite

`func (o *ConfigResponse) SetOnSite(v bool)`

SetOnSite sets OnSite field to given value.


### GetNetworkTypes

`func (o *ConfigResponse) GetNetworkTypes() []string`

GetNetworkTypes returns the NetworkTypes field if non-nil, zero value otherwise.

### GetNetworkTypesOk

`func (o *ConfigResponse) GetNetworkTypesOk() (*[]string, bool)`

GetNetworkTypesOk returns a tuple with the NetworkTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTypes

`func (o *ConfigResponse) SetNetworkTypes(v []string)`

SetNetworkTypes sets NetworkTypes field to given value.


### SetNetworkTypesNil

`func (o *ConfigResponse) SetNetworkTypesNil(b bool)`

 SetNetworkTypesNil sets the value for NetworkTypes to be an explicit nil

### UnsetNetworkTypes
`func (o *ConfigResponse) UnsetNetworkTypes()`

UnsetNetworkTypes ensures that no value is present for NetworkTypes, not even an explicit nil
### GetNetworkType

`func (o *ConfigResponse) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *ConfigResponse) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *ConfigResponse) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.


### GetShowDomainSettings

`func (o *ConfigResponse) GetShowDomainSettings() bool`

GetShowDomainSettings returns the ShowDomainSettings field if non-nil, zero value otherwise.

### GetShowDomainSettingsOk

`func (o *ConfigResponse) GetShowDomainSettingsOk() (*bool, bool)`

GetShowDomainSettingsOk returns a tuple with the ShowDomainSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDomainSettings

`func (o *ConfigResponse) SetShowDomainSettings(v bool)`

SetShowDomainSettings sets ShowDomainSettings field to given value.


### GetVersion

`func (o *ConfigResponse) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ConfigResponse) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ConfigResponse) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetInvalidBuild

`func (o *ConfigResponse) GetInvalidBuild() bool`

GetInvalidBuild returns the InvalidBuild field if non-nil, zero value otherwise.

### GetInvalidBuildOk

`func (o *ConfigResponse) GetInvalidBuildOk() (*bool, bool)`

GetInvalidBuildOk returns a tuple with the InvalidBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidBuild

`func (o *ConfigResponse) SetInvalidBuild(v bool)`

SetInvalidBuild sets InvalidBuild field to given value.

### HasInvalidBuild

`func (o *ConfigResponse) HasInvalidBuild() bool`

HasInvalidBuild returns a boolean if a field has been set.

### GetSepSim

`func (o *ConfigResponse) GetSepSim() bool`

GetSepSim returns the SepSim field if non-nil, zero value otherwise.

### GetSepSimOk

`func (o *ConfigResponse) GetSepSimOk() (*bool, bool)`

GetSepSimOk returns a tuple with the SepSim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepSim

`func (o *ConfigResponse) SetSepSim(v bool)`

SetSepSim sets SepSim field to given value.


### GetInstallerAvailable

`func (o *ConfigResponse) GetInstallerAvailable() bool`

GetInstallerAvailable returns the InstallerAvailable field if non-nil, zero value otherwise.

### GetInstallerAvailableOk

`func (o *ConfigResponse) GetInstallerAvailableOk() (*bool, bool)`

GetInstallerAvailableOk returns a tuple with the InstallerAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallerAvailable

`func (o *ConfigResponse) SetInstallerAvailable(v bool)`

SetInstallerAvailable sets InstallerAvailable field to given value.


### GetStripePublicKey

`func (o *ConfigResponse) GetStripePublicKey() string`

GetStripePublicKey returns the StripePublicKey field if non-nil, zero value otherwise.

### GetStripePublicKeyOk

`func (o *ConfigResponse) GetStripePublicKeyOk() (*string, bool)`

GetStripePublicKeyOk returns a tuple with the StripePublicKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripePublicKey

`func (o *ConfigResponse) SetStripePublicKey(v string)`

SetStripePublicKey sets StripePublicKey field to given value.

### HasStripePublicKey

`func (o *ConfigResponse) HasStripePublicKey() bool`

HasStripePublicKey returns a boolean if a field has been set.

### GetIntercomId

`func (o *ConfigResponse) GetIntercomId() string`

GetIntercomId returns the IntercomId field if non-nil, zero value otherwise.

### GetIntercomIdOk

`func (o *ConfigResponse) GetIntercomIdOk() (*string, bool)`

GetIntercomIdOk returns a tuple with the IntercomId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercomId

`func (o *ConfigResponse) SetIntercomId(v string)`

SetIntercomId sets IntercomId field to given value.

### HasIntercomId

`func (o *ConfigResponse) HasIntercomId() bool`

HasIntercomId returns a boolean if a field has been set.

### GetGtmId

`func (o *ConfigResponse) GetGtmId() string`

GetGtmId returns the GtmId field if non-nil, zero value otherwise.

### GetGtmIdOk

`func (o *ConfigResponse) GetGtmIdOk() (*string, bool)`

GetGtmIdOk returns a tuple with the GtmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtmId

`func (o *ConfigResponse) SetGtmId(v string)`

SetGtmId sets GtmId field to given value.

### HasGtmId

`func (o *ConfigResponse) HasGtmId() bool`

HasGtmId returns a boolean if a field has been set.

### GetBillingBackend

`func (o *ConfigResponse) GetBillingBackend() string`

GetBillingBackend returns the BillingBackend field if non-nil, zero value otherwise.

### GetBillingBackendOk

`func (o *ConfigResponse) GetBillingBackendOk() (*string, bool)`

GetBillingBackendOk returns a tuple with the BillingBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingBackend

`func (o *ConfigResponse) SetBillingBackend(v string)`

SetBillingBackend sets BillingBackend field to given value.

### HasBillingBackend

`func (o *ConfigResponse) HasBillingBackend() bool`

HasBillingBackend returns a boolean if a field has been set.

### SetBillingBackendNil

`func (o *ConfigResponse) SetBillingBackendNil(b bool)`

 SetBillingBackendNil sets the value for BillingBackend to be an explicit nil

### UnsetBillingBackend
`func (o *ConfigResponse) UnsetBillingBackend()`

UnsetBillingBackend ensures that no value is present for BillingBackend, not even an explicit nil
### GetMaintenance

`func (o *ConfigResponse) GetMaintenance() ConfigResponseMaintenance`

GetMaintenance returns the Maintenance field if non-nil, zero value otherwise.

### GetMaintenanceOk

`func (o *ConfigResponse) GetMaintenanceOk() (*ConfigResponseMaintenance, bool)`

GetMaintenanceOk returns a tuple with the Maintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenance

`func (o *ConfigResponse) SetMaintenance(v ConfigResponseMaintenance)`

SetMaintenance sets Maintenance field to given value.

### HasMaintenance

`func (o *ConfigResponse) HasMaintenance() bool`

HasMaintenance returns a boolean if a field has been set.

### SetMaintenanceNil

`func (o *ConfigResponse) SetMaintenanceNil(b bool)`

 SetMaintenanceNil sets the value for Maintenance to be an explicit nil

### UnsetMaintenance
`func (o *ConfigResponse) UnsetMaintenance()`

UnsetMaintenance ensures that no value is present for Maintenance, not even an explicit nil
### GetLogging

`func (o *ConfigResponse) GetLogging() Logging`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *ConfigResponse) GetLoggingOk() (*Logging, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *ConfigResponse) SetLogging(v Logging)`

SetLogging sets Logging field to given value.

### HasLogging

`func (o *ConfigResponse) HasLogging() bool`

HasLogging returns a boolean if a field has been set.

### GetCloudAdmin

`func (o *ConfigResponse) GetCloudAdmin() string`

GetCloudAdmin returns the CloudAdmin field if non-nil, zero value otherwise.

### GetCloudAdminOk

`func (o *ConfigResponse) GetCloudAdminOk() (*string, bool)`

GetCloudAdminOk returns a tuple with the CloudAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudAdmin

`func (o *ConfigResponse) SetCloudAdmin(v string)`

SetCloudAdmin sets CloudAdmin field to given value.


### GetFilesAdmin

`func (o *ConfigResponse) GetFilesAdmin() string`

GetFilesAdmin returns the FilesAdmin field if non-nil, zero value otherwise.

### GetFilesAdminOk

`func (o *ConfigResponse) GetFilesAdminOk() (*string, bool)`

GetFilesAdminOk returns a tuple with the FilesAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesAdmin

`func (o *ConfigResponse) SetFilesAdmin(v string)`

SetFilesAdmin sets FilesAdmin field to given value.


### GetCloudDomain

`func (o *ConfigResponse) GetCloudDomain() string`

GetCloudDomain returns the CloudDomain field if non-nil, zero value otherwise.

### GetCloudDomainOk

`func (o *ConfigResponse) GetCloudDomainOk() (*string, bool)`

GetCloudDomainOk returns a tuple with the CloudDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudDomain

`func (o *ConfigResponse) SetCloudDomain(v string)`

SetCloudDomain sets CloudDomain field to given value.

### HasCloudDomain

`func (o *ConfigResponse) HasCloudDomain() bool`

HasCloudDomain returns a boolean if a field has been set.

### GetBillingDomain

`func (o *ConfigResponse) GetBillingDomain() string`

GetBillingDomain returns the BillingDomain field if non-nil, zero value otherwise.

### GetBillingDomainOk

`func (o *ConfigResponse) GetBillingDomainOk() (*string, bool)`

GetBillingDomainOk returns a tuple with the BillingDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingDomain

`func (o *ConfigResponse) SetBillingDomain(v string)`

SetBillingDomain sets BillingDomain field to given value.

### HasBillingDomain

`func (o *ConfigResponse) HasBillingDomain() bool`

HasBillingDomain returns a boolean if a field has been set.

### GetAppDomain

`func (o *ConfigResponse) GetAppDomain() string`

GetAppDomain returns the AppDomain field if non-nil, zero value otherwise.

### GetAppDomainOk

`func (o *ConfigResponse) GetAppDomainOk() (*string, bool)`

GetAppDomainOk returns a tuple with the AppDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppDomain

`func (o *ConfigResponse) SetAppDomain(v string)`

SetAppDomain sets AppDomain field to given value.

### HasAppDomain

`func (o *ConfigResponse) HasAppDomain() bool`

HasAppDomain returns a boolean if a field has been set.

### GetMaxNetworkMonitorFileSize

`func (o *ConfigResponse) GetMaxNetworkMonitorFileSize() string`

GetMaxNetworkMonitorFileSize returns the MaxNetworkMonitorFileSize field if non-nil, zero value otherwise.

### GetMaxNetworkMonitorFileSizeOk

`func (o *ConfigResponse) GetMaxNetworkMonitorFileSizeOk() (*string, bool)`

GetMaxNetworkMonitorFileSizeOk returns a tuple with the MaxNetworkMonitorFileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNetworkMonitorFileSize

`func (o *ConfigResponse) SetMaxNetworkMonitorFileSize(v string)`

SetMaxNetworkMonitorFileSize sets MaxNetworkMonitorFileSize field to given value.


### GetEnableFirmwareImageUpload

`func (o *ConfigResponse) GetEnableFirmwareImageUpload() bool`

GetEnableFirmwareImageUpload returns the EnableFirmwareImageUpload field if non-nil, zero value otherwise.

### GetEnableFirmwareImageUploadOk

`func (o *ConfigResponse) GetEnableFirmwareImageUploadOk() (*bool, bool)`

GetEnableFirmwareImageUploadOk returns a tuple with the EnableFirmwareImageUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableFirmwareImageUpload

`func (o *ConfigResponse) SetEnableFirmwareImageUpload(v bool)`

SetEnableFirmwareImageUpload sets EnableFirmwareImageUpload field to given value.


### GetAuthProviders

`func (o *ConfigResponse) GetAuthProviders() []ConfigAuthProvider`

GetAuthProviders returns the AuthProviders field if non-nil, zero value otherwise.

### GetAuthProvidersOk

`func (o *ConfigResponse) GetAuthProvidersOk() (*[]ConfigAuthProvider, bool)`

GetAuthProvidersOk returns a tuple with the AuthProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthProviders

`func (o *ConfigResponse) SetAuthProviders(v []ConfigAuthProvider)`

SetAuthProviders sets AuthProviders field to given value.


### GetWelcomeMessage

`func (o *ConfigResponse) GetWelcomeMessage() string`

GetWelcomeMessage returns the WelcomeMessage field if non-nil, zero value otherwise.

### GetWelcomeMessageOk

`func (o *ConfigResponse) GetWelcomeMessageOk() (*string, bool)`

GetWelcomeMessageOk returns a tuple with the WelcomeMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWelcomeMessage

`func (o *ConfigResponse) SetWelcomeMessage(v string)`

SetWelcomeMessage sets WelcomeMessage field to given value.

### HasWelcomeMessage

`func (o *ConfigResponse) HasWelcomeMessage() bool`

HasWelcomeMessage returns a boolean if a field has been set.

### GetSnapshotLimit

`func (o *ConfigResponse) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *ConfigResponse) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *ConfigResponse) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.


### GetMaxKernelSize

`func (o *ConfigResponse) GetMaxKernelSize() float32`

GetMaxKernelSize returns the MaxKernelSize field if non-nil, zero value otherwise.

### GetMaxKernelSizeOk

`func (o *ConfigResponse) GetMaxKernelSizeOk() (*float32, bool)`

GetMaxKernelSizeOk returns a tuple with the MaxKernelSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxKernelSize

`func (o *ConfigResponse) SetMaxKernelSize(v float32)`

SetMaxKernelSize sets MaxKernelSize field to given value.


### GetMaxRamdiskSize

`func (o *ConfigResponse) GetMaxRamdiskSize() float32`

GetMaxRamdiskSize returns the MaxRamdiskSize field if non-nil, zero value otherwise.

### GetMaxRamdiskSizeOk

`func (o *ConfigResponse) GetMaxRamdiskSizeOk() (*float32, bool)`

GetMaxRamdiskSizeOk returns a tuple with the MaxRamdiskSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRamdiskSize

`func (o *ConfigResponse) SetMaxRamdiskSize(v float32)`

SetMaxRamdiskSize sets MaxRamdiskSize field to given value.


### GetCharmSdk

`func (o *ConfigResponse) GetCharmSdk() bool`

GetCharmSdk returns the CharmSdk field if non-nil, zero value otherwise.

### GetCharmSdkOk

`func (o *ConfigResponse) GetCharmSdkOk() (*bool, bool)`

GetCharmSdkOk returns a tuple with the CharmSdk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmSdk

`func (o *ConfigResponse) SetCharmSdk(v bool)`

SetCharmSdk sets CharmSdk field to given value.

### HasCharmSdk

`func (o *ConfigResponse) HasCharmSdk() bool`

HasCharmSdk returns a boolean if a field has been set.

### GetTrial

`func (o *ConfigResponse) GetTrial() Trial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *ConfigResponse) GetTrialOk() (*Trial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *ConfigResponse) SetTrial(v Trial)`

SetTrial sets Trial field to given value.


### GetSentryUrl

`func (o *ConfigResponse) GetSentryUrl() string`

GetSentryUrl returns the SentryUrl field if non-nil, zero value otherwise.

### GetSentryUrlOk

`func (o *ConfigResponse) GetSentryUrlOk() (*string, bool)`

GetSentryUrlOk returns a tuple with the SentryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentryUrl

`func (o *ConfigResponse) SetSentryUrl(v string)`

SetSentryUrl sets SentryUrl field to given value.

### HasSentryUrl

`func (o *ConfigResponse) HasSentryUrl() bool`

HasSentryUrl returns a boolean if a field has been set.

### GetDomainAuthenticationProviders

`func (o *ConfigResponse) GetDomainAuthenticationProviders() bool`

GetDomainAuthenticationProviders returns the DomainAuthenticationProviders field if non-nil, zero value otherwise.

### GetDomainAuthenticationProvidersOk

`func (o *ConfigResponse) GetDomainAuthenticationProvidersOk() (*bool, bool)`

GetDomainAuthenticationProvidersOk returns a tuple with the DomainAuthenticationProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainAuthenticationProviders

`func (o *ConfigResponse) SetDomainAuthenticationProviders(v bool)`

SetDomainAuthenticationProviders sets DomainAuthenticationProviders field to given value.

### HasDomainAuthenticationProviders

`func (o *ConfigResponse) HasDomainAuthenticationProviders() bool`

HasDomainAuthenticationProviders returns a boolean if a field has been set.

### GetRemoteGpu

`func (o *ConfigResponse) GetRemoteGpu() bool`

GetRemoteGpu returns the RemoteGpu field if non-nil, zero value otherwise.

### GetRemoteGpuOk

`func (o *ConfigResponse) GetRemoteGpuOk() (*bool, bool)`

GetRemoteGpuOk returns a tuple with the RemoteGpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteGpu

`func (o *ConfigResponse) SetRemoteGpu(v bool)`

SetRemoteGpu sets RemoteGpu field to given value.

### HasRemoteGpu

`func (o *ConfigResponse) HasRemoteGpu() bool`

HasRemoteGpu returns a boolean if a field has been set.

### GetDefaultSsid

`func (o *ConfigResponse) GetDefaultSsid() string`

GetDefaultSsid returns the DefaultSsid field if non-nil, zero value otherwise.

### GetDefaultSsidOk

`func (o *ConfigResponse) GetDefaultSsidOk() (*string, bool)`

GetDefaultSsidOk returns a tuple with the DefaultSsid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultSsid

`func (o *ConfigResponse) SetDefaultSsid(v string)`

SetDefaultSsid sets DefaultSsid field to given value.


### GetAwsMarketplace

`func (o *ConfigResponse) GetAwsMarketplace() bool`

GetAwsMarketplace returns the AwsMarketplace field if non-nil, zero value otherwise.

### GetAwsMarketplaceOk

`func (o *ConfigResponse) GetAwsMarketplaceOk() (*bool, bool)`

GetAwsMarketplaceOk returns a tuple with the AwsMarketplace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwsMarketplace

`func (o *ConfigResponse) SetAwsMarketplace(v bool)`

SetAwsMarketplace sets AwsMarketplace field to given value.

### HasAwsMarketplace

`func (o *ConfigResponse) HasAwsMarketplace() bool`

HasAwsMarketplace returns a boolean if a field has been set.

### GetOpenGAppsBinary

`func (o *ConfigResponse) GetOpenGAppsBinary() string`

GetOpenGAppsBinary returns the OpenGAppsBinary field if non-nil, zero value otherwise.

### GetOpenGAppsBinaryOk

`func (o *ConfigResponse) GetOpenGAppsBinaryOk() (*string, bool)`

GetOpenGAppsBinaryOk returns a tuple with the OpenGAppsBinary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenGAppsBinary

`func (o *ConfigResponse) SetOpenGAppsBinary(v string)`

SetOpenGAppsBinary sets OpenGAppsBinary field to given value.

### HasOpenGAppsBinary

`func (o *ConfigResponse) HasOpenGAppsBinary() bool`

HasOpenGAppsBinary returns a boolean if a field has been set.

### GetAirGapped

`func (o *ConfigResponse) GetAirGapped() bool`

GetAirGapped returns the AirGapped field if non-nil, zero value otherwise.

### GetAirGappedOk

`func (o *ConfigResponse) GetAirGappedOk() (*bool, bool)`

GetAirGappedOk returns a tuple with the AirGapped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAirGapped

`func (o *ConfigResponse) SetAirGapped(v bool)`

SetAirGapped sets AirGapped field to given value.

### HasAirGapped

`func (o *ConfigResponse) HasAirGapped() bool`

HasAirGapped returns a boolean if a field has been set.

### GetCoordinatorConfig

`func (o *ConfigResponse) GetCoordinatorConfig() CoordinatorConfig`

GetCoordinatorConfig returns the CoordinatorConfig field if non-nil, zero value otherwise.

### GetCoordinatorConfigOk

`func (o *ConfigResponse) GetCoordinatorConfigOk() (*CoordinatorConfig, bool)`

GetCoordinatorConfigOk returns a tuple with the CoordinatorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorConfig

`func (o *ConfigResponse) SetCoordinatorConfig(v CoordinatorConfig)`

SetCoordinatorConfig sets CoordinatorConfig field to given value.


### GetAiToolsConfig

`func (o *ConfigResponse) GetAiToolsConfig() ConfigResponseAiToolsConfig`

GetAiToolsConfig returns the AiToolsConfig field if non-nil, zero value otherwise.

### GetAiToolsConfigOk

`func (o *ConfigResponse) GetAiToolsConfigOk() (*ConfigResponseAiToolsConfig, bool)`

GetAiToolsConfigOk returns a tuple with the AiToolsConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiToolsConfig

`func (o *ConfigResponse) SetAiToolsConfig(v ConfigResponseAiToolsConfig)`

SetAiToolsConfig sets AiToolsConfig field to given value.

### HasAiToolsConfig

`func (o *ConfigResponse) HasAiToolsConfig() bool`

HasAiToolsConfig returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


