# ClusterConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LastConfigKeys** | **[]string** |  | 
**LocalIp** | **string** |  | 
**IpBlockNetmask** | **string** |  | 
**InstanceGateway** | **string** |  | 
**InstanceDNSServers** | Pointer to **[]string** |  | [optional] 
**Coordinator** | Pointer to **string** |  | [optional] 
**OnSite** | Pointer to **bool** |  | [optional] 
**CloudProvider** | **NullableString** |  | 
**NetworkTypes** | **[]string** |  | 
**NetworkType** | Pointer to **string** |  | [optional] 
**ShowDomainSettings** | Pointer to **bool** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 
**IpswUrl** | Pointer to **string** |  | [optional] 
**CoreimgUrl** | Pointer to **string** |  | [optional] 
**FwServiceUrl** | Pointer to **string** |  | [optional] 
**ServicePassword** | Pointer to **string** |  | [optional] 
**InvalidBuild** | Pointer to **bool** |  | [optional] 
**SepSim** | Pointer to **bool** |  | [optional] 
**InstallerAvailable** | Pointer to **bool** |  | [optional] 
**Stripe** | Pointer to [**ClusterConfigStripe**](ClusterConfigStripe.md) |  | [optional] 
**IntercomId** | Pointer to **string** |  | [optional] 
**AuxWebhook** | Pointer to **string** |  | [optional] 
**GtmId** | Pointer to **string** |  | [optional] 
**ZapierFeedbackWebhook** | Pointer to **string** |  | [optional] 
**ZapierBugsWebhook** | Pointer to **string** |  | [optional] 
**BillingBackend** | Pointer to **string** |  | [optional] 
**Maintenance** | Pointer to [**ClusterConfigMaintenance**](ClusterConfigMaintenance.md) |  | [optional] 
**CloudDomain** | Pointer to **string** |  | [optional] 
**Development** | Pointer to **bool** |  | [optional] 
**BillingDomain** | Pointer to **string** |  | [optional] 
**AppDomain** | Pointer to **string** |  | [optional] 
**EnableFirmwareImageUpload** | Pointer to **bool** |  | [optional] 
**NetMonCA** | Pointer to [**ClusterConfigNetMonCA**](ClusterConfigNetMonCA.md) |  | [optional] 
**SnapshotLimit** | Pointer to **float32** |  | [optional] 
**MaxKernelSize** | **float32** |  | 
**MaxRamdiskSize** | **float32** |  | 
**CharmSDK** | Pointer to **bool** |  | [optional] 
**SentryUrl** | Pointer to **string** |  | [optional] 
**RemoteGpu** | Pointer to **bool** |  | [optional] 
**RateLimit** | Pointer to **bool** |  | [optional] 
**CertFileData** | Pointer to **string** |  | [optional] 
**CaCertFileSrc** | **string** |  | 
**VstrmOnComputeNodes** | Pointer to **bool** |  | [optional] 
**Charm** | Pointer to **map[string]interface{}** |  | [optional] 
**C3poPathPrefix** | Pointer to **string** |  | [optional] 
**Branding** | **string** |  | 
**OpenGAppsBinary** | **string** |  | 
**Airgapped** | **bool** |  | 
**NodeStaleTimeout** | Pointer to **float32** |  | [optional] 
**ReportInterval** | Pointer to **float32** |  | [optional] 
**CoordinatorConfig** | Pointer to [**ClusterConfigCoordinatorConfig**](ClusterConfigCoordinatorConfig.md) |  | [optional] 
**SetupConfig** | Pointer to [**ClusterConfigSetupConfig**](ClusterConfigSetupConfig.md) |  | [optional] 
**NodeSpecificConfig** | Pointer to [**ClusterConfigNodeSpecificConfig**](ClusterConfigNodeSpecificConfig.md) |  | [optional] 
**PackageConfig** | Pointer to [**ClusterConfigPackageConfig**](ClusterConfigPackageConfig.md) |  | [optional] 
**MonitorInterval** | Pointer to **float32** |  | [optional] 
**Csp** | Pointer to **bool** |  | [optional] 
**Cdk** | Pointer to **bool** |  | [optional] 
**CharmExtensionPaths** | Pointer to **[]string** |  | [optional] 
**FirmwareCache** | Pointer to **string** |  | [optional] 
**Vstrm** | Pointer to **string** |  | [optional] 
**Console** | Pointer to **string** |  | [optional] 
**FetchFirmwareAssets** | Pointer to **bool** |  | [optional] 
**ClusterFirmwareAssets** | Pointer to **bool** |  | [optional] 
**AuthProviders** | Pointer to [**[]ClusterConfigCoordinatorConfigAuthProvidersInner**](ClusterConfigCoordinatorConfigAuthProvidersInner.md) |  | [optional] 
**Domain** | Pointer to **string** |  | [optional] 
**ServiceDomain** | Pointer to **string** |  | [optional] 
**ServiceUser** | Pointer to **string** |  | [optional] 
**DomainImageUploadQuota** | Pointer to **float32** |  | [optional] 
**IpswFilters** | Pointer to [**[]ClusterConfigIpswFiltersInner**](ClusterConfigIpswFiltersInner.md) |  | [optional] 
**FirmwareServiceConfig** | Pointer to [**ClusterConfigFirmwareServiceConfig**](ClusterConfigFirmwareServiceConfig.md) |  | [optional] 
**AiToolsConfig** | [**AiToolsConfig**](AiToolsConfig.md) |  | 

## Methods

### NewClusterConfig

`func NewClusterConfig(lastConfigKeys []string, localIp string, ipBlockNetmask string, instanceGateway string, cloudProvider NullableString, networkTypes []string, maxKernelSize float32, maxRamdiskSize float32, caCertFileSrc string, branding string, openGAppsBinary string, airgapped bool, aiToolsConfig AiToolsConfig, ) *ClusterConfig`

NewClusterConfig instantiates a new ClusterConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigWithDefaults

`func NewClusterConfigWithDefaults() *ClusterConfig`

NewClusterConfigWithDefaults instantiates a new ClusterConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLastConfigKeys

`func (o *ClusterConfig) GetLastConfigKeys() []string`

GetLastConfigKeys returns the LastConfigKeys field if non-nil, zero value otherwise.

### GetLastConfigKeysOk

`func (o *ClusterConfig) GetLastConfigKeysOk() (*[]string, bool)`

GetLastConfigKeysOk returns a tuple with the LastConfigKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastConfigKeys

`func (o *ClusterConfig) SetLastConfigKeys(v []string)`

SetLastConfigKeys sets LastConfigKeys field to given value.


### GetLocalIp

`func (o *ClusterConfig) GetLocalIp() string`

GetLocalIp returns the LocalIp field if non-nil, zero value otherwise.

### GetLocalIpOk

`func (o *ClusterConfig) GetLocalIpOk() (*string, bool)`

GetLocalIpOk returns a tuple with the LocalIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIp

`func (o *ClusterConfig) SetLocalIp(v string)`

SetLocalIp sets LocalIp field to given value.


### GetIpBlockNetmask

`func (o *ClusterConfig) GetIpBlockNetmask() string`

GetIpBlockNetmask returns the IpBlockNetmask field if non-nil, zero value otherwise.

### GetIpBlockNetmaskOk

`func (o *ClusterConfig) GetIpBlockNetmaskOk() (*string, bool)`

GetIpBlockNetmaskOk returns a tuple with the IpBlockNetmask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlockNetmask

`func (o *ClusterConfig) SetIpBlockNetmask(v string)`

SetIpBlockNetmask sets IpBlockNetmask field to given value.


### GetInstanceGateway

`func (o *ClusterConfig) GetInstanceGateway() string`

GetInstanceGateway returns the InstanceGateway field if non-nil, zero value otherwise.

### GetInstanceGatewayOk

`func (o *ClusterConfig) GetInstanceGatewayOk() (*string, bool)`

GetInstanceGatewayOk returns a tuple with the InstanceGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceGateway

`func (o *ClusterConfig) SetInstanceGateway(v string)`

SetInstanceGateway sets InstanceGateway field to given value.


### GetInstanceDNSServers

`func (o *ClusterConfig) GetInstanceDNSServers() []string`

GetInstanceDNSServers returns the InstanceDNSServers field if non-nil, zero value otherwise.

### GetInstanceDNSServersOk

`func (o *ClusterConfig) GetInstanceDNSServersOk() (*[]string, bool)`

GetInstanceDNSServersOk returns a tuple with the InstanceDNSServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceDNSServers

`func (o *ClusterConfig) SetInstanceDNSServers(v []string)`

SetInstanceDNSServers sets InstanceDNSServers field to given value.

### HasInstanceDNSServers

`func (o *ClusterConfig) HasInstanceDNSServers() bool`

HasInstanceDNSServers returns a boolean if a field has been set.

### GetCoordinator

`func (o *ClusterConfig) GetCoordinator() string`

GetCoordinator returns the Coordinator field if non-nil, zero value otherwise.

### GetCoordinatorOk

`func (o *ClusterConfig) GetCoordinatorOk() (*string, bool)`

GetCoordinatorOk returns a tuple with the Coordinator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinator

`func (o *ClusterConfig) SetCoordinator(v string)`

SetCoordinator sets Coordinator field to given value.

### HasCoordinator

`func (o *ClusterConfig) HasCoordinator() bool`

HasCoordinator returns a boolean if a field has been set.

### GetOnSite

`func (o *ClusterConfig) GetOnSite() bool`

GetOnSite returns the OnSite field if non-nil, zero value otherwise.

### GetOnSiteOk

`func (o *ClusterConfig) GetOnSiteOk() (*bool, bool)`

GetOnSiteOk returns a tuple with the OnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnSite

`func (o *ClusterConfig) SetOnSite(v bool)`

SetOnSite sets OnSite field to given value.

### HasOnSite

`func (o *ClusterConfig) HasOnSite() bool`

HasOnSite returns a boolean if a field has been set.

### GetCloudProvider

`func (o *ClusterConfig) GetCloudProvider() string`

GetCloudProvider returns the CloudProvider field if non-nil, zero value otherwise.

### GetCloudProviderOk

`func (o *ClusterConfig) GetCloudProviderOk() (*string, bool)`

GetCloudProviderOk returns a tuple with the CloudProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudProvider

`func (o *ClusterConfig) SetCloudProvider(v string)`

SetCloudProvider sets CloudProvider field to given value.


### SetCloudProviderNil

`func (o *ClusterConfig) SetCloudProviderNil(b bool)`

 SetCloudProviderNil sets the value for CloudProvider to be an explicit nil

### UnsetCloudProvider
`func (o *ClusterConfig) UnsetCloudProvider()`

UnsetCloudProvider ensures that no value is present for CloudProvider, not even an explicit nil
### GetNetworkTypes

`func (o *ClusterConfig) GetNetworkTypes() []string`

GetNetworkTypes returns the NetworkTypes field if non-nil, zero value otherwise.

### GetNetworkTypesOk

`func (o *ClusterConfig) GetNetworkTypesOk() (*[]string, bool)`

GetNetworkTypesOk returns a tuple with the NetworkTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkTypes

`func (o *ClusterConfig) SetNetworkTypes(v []string)`

SetNetworkTypes sets NetworkTypes field to given value.


### GetNetworkType

`func (o *ClusterConfig) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *ClusterConfig) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *ClusterConfig) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.

### HasNetworkType

`func (o *ClusterConfig) HasNetworkType() bool`

HasNetworkType returns a boolean if a field has been set.

### GetShowDomainSettings

`func (o *ClusterConfig) GetShowDomainSettings() bool`

GetShowDomainSettings returns the ShowDomainSettings field if non-nil, zero value otherwise.

### GetShowDomainSettingsOk

`func (o *ClusterConfig) GetShowDomainSettingsOk() (*bool, bool)`

GetShowDomainSettingsOk returns a tuple with the ShowDomainSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowDomainSettings

`func (o *ClusterConfig) SetShowDomainSettings(v bool)`

SetShowDomainSettings sets ShowDomainSettings field to given value.

### HasShowDomainSettings

`func (o *ClusterConfig) HasShowDomainSettings() bool`

HasShowDomainSettings returns a boolean if a field has been set.

### GetVersion

`func (o *ClusterConfig) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ClusterConfig) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ClusterConfig) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ClusterConfig) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetIpswUrl

`func (o *ClusterConfig) GetIpswUrl() string`

GetIpswUrl returns the IpswUrl field if non-nil, zero value otherwise.

### GetIpswUrlOk

`func (o *ClusterConfig) GetIpswUrlOk() (*string, bool)`

GetIpswUrlOk returns a tuple with the IpswUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpswUrl

`func (o *ClusterConfig) SetIpswUrl(v string)`

SetIpswUrl sets IpswUrl field to given value.

### HasIpswUrl

`func (o *ClusterConfig) HasIpswUrl() bool`

HasIpswUrl returns a boolean if a field has been set.

### GetCoreimgUrl

`func (o *ClusterConfig) GetCoreimgUrl() string`

GetCoreimgUrl returns the CoreimgUrl field if non-nil, zero value otherwise.

### GetCoreimgUrlOk

`func (o *ClusterConfig) GetCoreimgUrlOk() (*string, bool)`

GetCoreimgUrlOk returns a tuple with the CoreimgUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreimgUrl

`func (o *ClusterConfig) SetCoreimgUrl(v string)`

SetCoreimgUrl sets CoreimgUrl field to given value.

### HasCoreimgUrl

`func (o *ClusterConfig) HasCoreimgUrl() bool`

HasCoreimgUrl returns a boolean if a field has been set.

### GetFwServiceUrl

`func (o *ClusterConfig) GetFwServiceUrl() string`

GetFwServiceUrl returns the FwServiceUrl field if non-nil, zero value otherwise.

### GetFwServiceUrlOk

`func (o *ClusterConfig) GetFwServiceUrlOk() (*string, bool)`

GetFwServiceUrlOk returns a tuple with the FwServiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFwServiceUrl

`func (o *ClusterConfig) SetFwServiceUrl(v string)`

SetFwServiceUrl sets FwServiceUrl field to given value.

### HasFwServiceUrl

`func (o *ClusterConfig) HasFwServiceUrl() bool`

HasFwServiceUrl returns a boolean if a field has been set.

### GetServicePassword

`func (o *ClusterConfig) GetServicePassword() string`

GetServicePassword returns the ServicePassword field if non-nil, zero value otherwise.

### GetServicePasswordOk

`func (o *ClusterConfig) GetServicePasswordOk() (*string, bool)`

GetServicePasswordOk returns a tuple with the ServicePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServicePassword

`func (o *ClusterConfig) SetServicePassword(v string)`

SetServicePassword sets ServicePassword field to given value.

### HasServicePassword

`func (o *ClusterConfig) HasServicePassword() bool`

HasServicePassword returns a boolean if a field has been set.

### GetInvalidBuild

`func (o *ClusterConfig) GetInvalidBuild() bool`

GetInvalidBuild returns the InvalidBuild field if non-nil, zero value otherwise.

### GetInvalidBuildOk

`func (o *ClusterConfig) GetInvalidBuildOk() (*bool, bool)`

GetInvalidBuildOk returns a tuple with the InvalidBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidBuild

`func (o *ClusterConfig) SetInvalidBuild(v bool)`

SetInvalidBuild sets InvalidBuild field to given value.

### HasInvalidBuild

`func (o *ClusterConfig) HasInvalidBuild() bool`

HasInvalidBuild returns a boolean if a field has been set.

### GetSepSim

`func (o *ClusterConfig) GetSepSim() bool`

GetSepSim returns the SepSim field if non-nil, zero value otherwise.

### GetSepSimOk

`func (o *ClusterConfig) GetSepSimOk() (*bool, bool)`

GetSepSimOk returns a tuple with the SepSim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepSim

`func (o *ClusterConfig) SetSepSim(v bool)`

SetSepSim sets SepSim field to given value.

### HasSepSim

`func (o *ClusterConfig) HasSepSim() bool`

HasSepSim returns a boolean if a field has been set.

### GetInstallerAvailable

`func (o *ClusterConfig) GetInstallerAvailable() bool`

GetInstallerAvailable returns the InstallerAvailable field if non-nil, zero value otherwise.

### GetInstallerAvailableOk

`func (o *ClusterConfig) GetInstallerAvailableOk() (*bool, bool)`

GetInstallerAvailableOk returns a tuple with the InstallerAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallerAvailable

`func (o *ClusterConfig) SetInstallerAvailable(v bool)`

SetInstallerAvailable sets InstallerAvailable field to given value.

### HasInstallerAvailable

`func (o *ClusterConfig) HasInstallerAvailable() bool`

HasInstallerAvailable returns a boolean if a field has been set.

### GetStripe

`func (o *ClusterConfig) GetStripe() ClusterConfigStripe`

GetStripe returns the Stripe field if non-nil, zero value otherwise.

### GetStripeOk

`func (o *ClusterConfig) GetStripeOk() (*ClusterConfigStripe, bool)`

GetStripeOk returns a tuple with the Stripe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripe

`func (o *ClusterConfig) SetStripe(v ClusterConfigStripe)`

SetStripe sets Stripe field to given value.

### HasStripe

`func (o *ClusterConfig) HasStripe() bool`

HasStripe returns a boolean if a field has been set.

### GetIntercomId

`func (o *ClusterConfig) GetIntercomId() string`

GetIntercomId returns the IntercomId field if non-nil, zero value otherwise.

### GetIntercomIdOk

`func (o *ClusterConfig) GetIntercomIdOk() (*string, bool)`

GetIntercomIdOk returns a tuple with the IntercomId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercomId

`func (o *ClusterConfig) SetIntercomId(v string)`

SetIntercomId sets IntercomId field to given value.

### HasIntercomId

`func (o *ClusterConfig) HasIntercomId() bool`

HasIntercomId returns a boolean if a field has been set.

### GetAuxWebhook

`func (o *ClusterConfig) GetAuxWebhook() string`

GetAuxWebhook returns the AuxWebhook field if non-nil, zero value otherwise.

### GetAuxWebhookOk

`func (o *ClusterConfig) GetAuxWebhookOk() (*string, bool)`

GetAuxWebhookOk returns a tuple with the AuxWebhook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuxWebhook

`func (o *ClusterConfig) SetAuxWebhook(v string)`

SetAuxWebhook sets AuxWebhook field to given value.

### HasAuxWebhook

`func (o *ClusterConfig) HasAuxWebhook() bool`

HasAuxWebhook returns a boolean if a field has been set.

### GetGtmId

`func (o *ClusterConfig) GetGtmId() string`

GetGtmId returns the GtmId field if non-nil, zero value otherwise.

### GetGtmIdOk

`func (o *ClusterConfig) GetGtmIdOk() (*string, bool)`

GetGtmIdOk returns a tuple with the GtmId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtmId

`func (o *ClusterConfig) SetGtmId(v string)`

SetGtmId sets GtmId field to given value.

### HasGtmId

`func (o *ClusterConfig) HasGtmId() bool`

HasGtmId returns a boolean if a field has been set.

### GetZapierFeedbackWebhook

`func (o *ClusterConfig) GetZapierFeedbackWebhook() string`

GetZapierFeedbackWebhook returns the ZapierFeedbackWebhook field if non-nil, zero value otherwise.

### GetZapierFeedbackWebhookOk

`func (o *ClusterConfig) GetZapierFeedbackWebhookOk() (*string, bool)`

GetZapierFeedbackWebhookOk returns a tuple with the ZapierFeedbackWebhook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZapierFeedbackWebhook

`func (o *ClusterConfig) SetZapierFeedbackWebhook(v string)`

SetZapierFeedbackWebhook sets ZapierFeedbackWebhook field to given value.

### HasZapierFeedbackWebhook

`func (o *ClusterConfig) HasZapierFeedbackWebhook() bool`

HasZapierFeedbackWebhook returns a boolean if a field has been set.

### GetZapierBugsWebhook

`func (o *ClusterConfig) GetZapierBugsWebhook() string`

GetZapierBugsWebhook returns the ZapierBugsWebhook field if non-nil, zero value otherwise.

### GetZapierBugsWebhookOk

`func (o *ClusterConfig) GetZapierBugsWebhookOk() (*string, bool)`

GetZapierBugsWebhookOk returns a tuple with the ZapierBugsWebhook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZapierBugsWebhook

`func (o *ClusterConfig) SetZapierBugsWebhook(v string)`

SetZapierBugsWebhook sets ZapierBugsWebhook field to given value.

### HasZapierBugsWebhook

`func (o *ClusterConfig) HasZapierBugsWebhook() bool`

HasZapierBugsWebhook returns a boolean if a field has been set.

### GetBillingBackend

`func (o *ClusterConfig) GetBillingBackend() string`

GetBillingBackend returns the BillingBackend field if non-nil, zero value otherwise.

### GetBillingBackendOk

`func (o *ClusterConfig) GetBillingBackendOk() (*string, bool)`

GetBillingBackendOk returns a tuple with the BillingBackend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingBackend

`func (o *ClusterConfig) SetBillingBackend(v string)`

SetBillingBackend sets BillingBackend field to given value.

### HasBillingBackend

`func (o *ClusterConfig) HasBillingBackend() bool`

HasBillingBackend returns a boolean if a field has been set.

### GetMaintenance

`func (o *ClusterConfig) GetMaintenance() ClusterConfigMaintenance`

GetMaintenance returns the Maintenance field if non-nil, zero value otherwise.

### GetMaintenanceOk

`func (o *ClusterConfig) GetMaintenanceOk() (*ClusterConfigMaintenance, bool)`

GetMaintenanceOk returns a tuple with the Maintenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaintenance

`func (o *ClusterConfig) SetMaintenance(v ClusterConfigMaintenance)`

SetMaintenance sets Maintenance field to given value.

### HasMaintenance

`func (o *ClusterConfig) HasMaintenance() bool`

HasMaintenance returns a boolean if a field has been set.

### GetCloudDomain

`func (o *ClusterConfig) GetCloudDomain() string`

GetCloudDomain returns the CloudDomain field if non-nil, zero value otherwise.

### GetCloudDomainOk

`func (o *ClusterConfig) GetCloudDomainOk() (*string, bool)`

GetCloudDomainOk returns a tuple with the CloudDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudDomain

`func (o *ClusterConfig) SetCloudDomain(v string)`

SetCloudDomain sets CloudDomain field to given value.

### HasCloudDomain

`func (o *ClusterConfig) HasCloudDomain() bool`

HasCloudDomain returns a boolean if a field has been set.

### GetDevelopment

`func (o *ClusterConfig) GetDevelopment() bool`

GetDevelopment returns the Development field if non-nil, zero value otherwise.

### GetDevelopmentOk

`func (o *ClusterConfig) GetDevelopmentOk() (*bool, bool)`

GetDevelopmentOk returns a tuple with the Development field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevelopment

`func (o *ClusterConfig) SetDevelopment(v bool)`

SetDevelopment sets Development field to given value.

### HasDevelopment

`func (o *ClusterConfig) HasDevelopment() bool`

HasDevelopment returns a boolean if a field has been set.

### GetBillingDomain

`func (o *ClusterConfig) GetBillingDomain() string`

GetBillingDomain returns the BillingDomain field if non-nil, zero value otherwise.

### GetBillingDomainOk

`func (o *ClusterConfig) GetBillingDomainOk() (*string, bool)`

GetBillingDomainOk returns a tuple with the BillingDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingDomain

`func (o *ClusterConfig) SetBillingDomain(v string)`

SetBillingDomain sets BillingDomain field to given value.

### HasBillingDomain

`func (o *ClusterConfig) HasBillingDomain() bool`

HasBillingDomain returns a boolean if a field has been set.

### GetAppDomain

`func (o *ClusterConfig) GetAppDomain() string`

GetAppDomain returns the AppDomain field if non-nil, zero value otherwise.

### GetAppDomainOk

`func (o *ClusterConfig) GetAppDomainOk() (*string, bool)`

GetAppDomainOk returns a tuple with the AppDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppDomain

`func (o *ClusterConfig) SetAppDomain(v string)`

SetAppDomain sets AppDomain field to given value.

### HasAppDomain

`func (o *ClusterConfig) HasAppDomain() bool`

HasAppDomain returns a boolean if a field has been set.

### GetEnableFirmwareImageUpload

`func (o *ClusterConfig) GetEnableFirmwareImageUpload() bool`

GetEnableFirmwareImageUpload returns the EnableFirmwareImageUpload field if non-nil, zero value otherwise.

### GetEnableFirmwareImageUploadOk

`func (o *ClusterConfig) GetEnableFirmwareImageUploadOk() (*bool, bool)`

GetEnableFirmwareImageUploadOk returns a tuple with the EnableFirmwareImageUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableFirmwareImageUpload

`func (o *ClusterConfig) SetEnableFirmwareImageUpload(v bool)`

SetEnableFirmwareImageUpload sets EnableFirmwareImageUpload field to given value.

### HasEnableFirmwareImageUpload

`func (o *ClusterConfig) HasEnableFirmwareImageUpload() bool`

HasEnableFirmwareImageUpload returns a boolean if a field has been set.

### GetNetMonCA

`func (o *ClusterConfig) GetNetMonCA() ClusterConfigNetMonCA`

GetNetMonCA returns the NetMonCA field if non-nil, zero value otherwise.

### GetNetMonCAOk

`func (o *ClusterConfig) GetNetMonCAOk() (*ClusterConfigNetMonCA, bool)`

GetNetMonCAOk returns a tuple with the NetMonCA field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetMonCA

`func (o *ClusterConfig) SetNetMonCA(v ClusterConfigNetMonCA)`

SetNetMonCA sets NetMonCA field to given value.

### HasNetMonCA

`func (o *ClusterConfig) HasNetMonCA() bool`

HasNetMonCA returns a boolean if a field has been set.

### GetSnapshotLimit

`func (o *ClusterConfig) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *ClusterConfig) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *ClusterConfig) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.

### HasSnapshotLimit

`func (o *ClusterConfig) HasSnapshotLimit() bool`

HasSnapshotLimit returns a boolean if a field has been set.

### GetMaxKernelSize

`func (o *ClusterConfig) GetMaxKernelSize() float32`

GetMaxKernelSize returns the MaxKernelSize field if non-nil, zero value otherwise.

### GetMaxKernelSizeOk

`func (o *ClusterConfig) GetMaxKernelSizeOk() (*float32, bool)`

GetMaxKernelSizeOk returns a tuple with the MaxKernelSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxKernelSize

`func (o *ClusterConfig) SetMaxKernelSize(v float32)`

SetMaxKernelSize sets MaxKernelSize field to given value.


### GetMaxRamdiskSize

`func (o *ClusterConfig) GetMaxRamdiskSize() float32`

GetMaxRamdiskSize returns the MaxRamdiskSize field if non-nil, zero value otherwise.

### GetMaxRamdiskSizeOk

`func (o *ClusterConfig) GetMaxRamdiskSizeOk() (*float32, bool)`

GetMaxRamdiskSizeOk returns a tuple with the MaxRamdiskSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRamdiskSize

`func (o *ClusterConfig) SetMaxRamdiskSize(v float32)`

SetMaxRamdiskSize sets MaxRamdiskSize field to given value.


### GetCharmSDK

`func (o *ClusterConfig) GetCharmSDK() bool`

GetCharmSDK returns the CharmSDK field if non-nil, zero value otherwise.

### GetCharmSDKOk

`func (o *ClusterConfig) GetCharmSDKOk() (*bool, bool)`

GetCharmSDKOk returns a tuple with the CharmSDK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmSDK

`func (o *ClusterConfig) SetCharmSDK(v bool)`

SetCharmSDK sets CharmSDK field to given value.

### HasCharmSDK

`func (o *ClusterConfig) HasCharmSDK() bool`

HasCharmSDK returns a boolean if a field has been set.

### GetSentryUrl

`func (o *ClusterConfig) GetSentryUrl() string`

GetSentryUrl returns the SentryUrl field if non-nil, zero value otherwise.

### GetSentryUrlOk

`func (o *ClusterConfig) GetSentryUrlOk() (*string, bool)`

GetSentryUrlOk returns a tuple with the SentryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentryUrl

`func (o *ClusterConfig) SetSentryUrl(v string)`

SetSentryUrl sets SentryUrl field to given value.

### HasSentryUrl

`func (o *ClusterConfig) HasSentryUrl() bool`

HasSentryUrl returns a boolean if a field has been set.

### GetRemoteGpu

`func (o *ClusterConfig) GetRemoteGpu() bool`

GetRemoteGpu returns the RemoteGpu field if non-nil, zero value otherwise.

### GetRemoteGpuOk

`func (o *ClusterConfig) GetRemoteGpuOk() (*bool, bool)`

GetRemoteGpuOk returns a tuple with the RemoteGpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteGpu

`func (o *ClusterConfig) SetRemoteGpu(v bool)`

SetRemoteGpu sets RemoteGpu field to given value.

### HasRemoteGpu

`func (o *ClusterConfig) HasRemoteGpu() bool`

HasRemoteGpu returns a boolean if a field has been set.

### GetRateLimit

`func (o *ClusterConfig) GetRateLimit() bool`

GetRateLimit returns the RateLimit field if non-nil, zero value otherwise.

### GetRateLimitOk

`func (o *ClusterConfig) GetRateLimitOk() (*bool, bool)`

GetRateLimitOk returns a tuple with the RateLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRateLimit

`func (o *ClusterConfig) SetRateLimit(v bool)`

SetRateLimit sets RateLimit field to given value.

### HasRateLimit

`func (o *ClusterConfig) HasRateLimit() bool`

HasRateLimit returns a boolean if a field has been set.

### GetCertFileData

`func (o *ClusterConfig) GetCertFileData() string`

GetCertFileData returns the CertFileData field if non-nil, zero value otherwise.

### GetCertFileDataOk

`func (o *ClusterConfig) GetCertFileDataOk() (*string, bool)`

GetCertFileDataOk returns a tuple with the CertFileData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertFileData

`func (o *ClusterConfig) SetCertFileData(v string)`

SetCertFileData sets CertFileData field to given value.

### HasCertFileData

`func (o *ClusterConfig) HasCertFileData() bool`

HasCertFileData returns a boolean if a field has been set.

### GetCaCertFileSrc

`func (o *ClusterConfig) GetCaCertFileSrc() string`

GetCaCertFileSrc returns the CaCertFileSrc field if non-nil, zero value otherwise.

### GetCaCertFileSrcOk

`func (o *ClusterConfig) GetCaCertFileSrcOk() (*string, bool)`

GetCaCertFileSrcOk returns a tuple with the CaCertFileSrc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaCertFileSrc

`func (o *ClusterConfig) SetCaCertFileSrc(v string)`

SetCaCertFileSrc sets CaCertFileSrc field to given value.


### GetVstrmOnComputeNodes

`func (o *ClusterConfig) GetVstrmOnComputeNodes() bool`

GetVstrmOnComputeNodes returns the VstrmOnComputeNodes field if non-nil, zero value otherwise.

### GetVstrmOnComputeNodesOk

`func (o *ClusterConfig) GetVstrmOnComputeNodesOk() (*bool, bool)`

GetVstrmOnComputeNodesOk returns a tuple with the VstrmOnComputeNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVstrmOnComputeNodes

`func (o *ClusterConfig) SetVstrmOnComputeNodes(v bool)`

SetVstrmOnComputeNodes sets VstrmOnComputeNodes field to given value.

### HasVstrmOnComputeNodes

`func (o *ClusterConfig) HasVstrmOnComputeNodes() bool`

HasVstrmOnComputeNodes returns a boolean if a field has been set.

### GetCharm

`func (o *ClusterConfig) GetCharm() map[string]interface{}`

GetCharm returns the Charm field if non-nil, zero value otherwise.

### GetCharmOk

`func (o *ClusterConfig) GetCharmOk() (*map[string]interface{}, bool)`

GetCharmOk returns a tuple with the Charm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharm

`func (o *ClusterConfig) SetCharm(v map[string]interface{})`

SetCharm sets Charm field to given value.

### HasCharm

`func (o *ClusterConfig) HasCharm() bool`

HasCharm returns a boolean if a field has been set.

### GetC3poPathPrefix

`func (o *ClusterConfig) GetC3poPathPrefix() string`

GetC3poPathPrefix returns the C3poPathPrefix field if non-nil, zero value otherwise.

### GetC3poPathPrefixOk

`func (o *ClusterConfig) GetC3poPathPrefixOk() (*string, bool)`

GetC3poPathPrefixOk returns a tuple with the C3poPathPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetC3poPathPrefix

`func (o *ClusterConfig) SetC3poPathPrefix(v string)`

SetC3poPathPrefix sets C3poPathPrefix field to given value.

### HasC3poPathPrefix

`func (o *ClusterConfig) HasC3poPathPrefix() bool`

HasC3poPathPrefix returns a boolean if a field has been set.

### GetBranding

`func (o *ClusterConfig) GetBranding() string`

GetBranding returns the Branding field if non-nil, zero value otherwise.

### GetBrandingOk

`func (o *ClusterConfig) GetBrandingOk() (*string, bool)`

GetBrandingOk returns a tuple with the Branding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranding

`func (o *ClusterConfig) SetBranding(v string)`

SetBranding sets Branding field to given value.


### GetOpenGAppsBinary

`func (o *ClusterConfig) GetOpenGAppsBinary() string`

GetOpenGAppsBinary returns the OpenGAppsBinary field if non-nil, zero value otherwise.

### GetOpenGAppsBinaryOk

`func (o *ClusterConfig) GetOpenGAppsBinaryOk() (*string, bool)`

GetOpenGAppsBinaryOk returns a tuple with the OpenGAppsBinary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenGAppsBinary

`func (o *ClusterConfig) SetOpenGAppsBinary(v string)`

SetOpenGAppsBinary sets OpenGAppsBinary field to given value.


### GetAirgapped

`func (o *ClusterConfig) GetAirgapped() bool`

GetAirgapped returns the Airgapped field if non-nil, zero value otherwise.

### GetAirgappedOk

`func (o *ClusterConfig) GetAirgappedOk() (*bool, bool)`

GetAirgappedOk returns a tuple with the Airgapped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAirgapped

`func (o *ClusterConfig) SetAirgapped(v bool)`

SetAirgapped sets Airgapped field to given value.


### GetNodeStaleTimeout

`func (o *ClusterConfig) GetNodeStaleTimeout() float32`

GetNodeStaleTimeout returns the NodeStaleTimeout field if non-nil, zero value otherwise.

### GetNodeStaleTimeoutOk

`func (o *ClusterConfig) GetNodeStaleTimeoutOk() (*float32, bool)`

GetNodeStaleTimeoutOk returns a tuple with the NodeStaleTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeStaleTimeout

`func (o *ClusterConfig) SetNodeStaleTimeout(v float32)`

SetNodeStaleTimeout sets NodeStaleTimeout field to given value.

### HasNodeStaleTimeout

`func (o *ClusterConfig) HasNodeStaleTimeout() bool`

HasNodeStaleTimeout returns a boolean if a field has been set.

### GetReportInterval

`func (o *ClusterConfig) GetReportInterval() float32`

GetReportInterval returns the ReportInterval field if non-nil, zero value otherwise.

### GetReportIntervalOk

`func (o *ClusterConfig) GetReportIntervalOk() (*float32, bool)`

GetReportIntervalOk returns a tuple with the ReportInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportInterval

`func (o *ClusterConfig) SetReportInterval(v float32)`

SetReportInterval sets ReportInterval field to given value.

### HasReportInterval

`func (o *ClusterConfig) HasReportInterval() bool`

HasReportInterval returns a boolean if a field has been set.

### GetCoordinatorConfig

`func (o *ClusterConfig) GetCoordinatorConfig() ClusterConfigCoordinatorConfig`

GetCoordinatorConfig returns the CoordinatorConfig field if non-nil, zero value otherwise.

### GetCoordinatorConfigOk

`func (o *ClusterConfig) GetCoordinatorConfigOk() (*ClusterConfigCoordinatorConfig, bool)`

GetCoordinatorConfigOk returns a tuple with the CoordinatorConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinatorConfig

`func (o *ClusterConfig) SetCoordinatorConfig(v ClusterConfigCoordinatorConfig)`

SetCoordinatorConfig sets CoordinatorConfig field to given value.

### HasCoordinatorConfig

`func (o *ClusterConfig) HasCoordinatorConfig() bool`

HasCoordinatorConfig returns a boolean if a field has been set.

### GetSetupConfig

`func (o *ClusterConfig) GetSetupConfig() ClusterConfigSetupConfig`

GetSetupConfig returns the SetupConfig field if non-nil, zero value otherwise.

### GetSetupConfigOk

`func (o *ClusterConfig) GetSetupConfigOk() (*ClusterConfigSetupConfig, bool)`

GetSetupConfigOk returns a tuple with the SetupConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupConfig

`func (o *ClusterConfig) SetSetupConfig(v ClusterConfigSetupConfig)`

SetSetupConfig sets SetupConfig field to given value.

### HasSetupConfig

`func (o *ClusterConfig) HasSetupConfig() bool`

HasSetupConfig returns a boolean if a field has been set.

### GetNodeSpecificConfig

`func (o *ClusterConfig) GetNodeSpecificConfig() ClusterConfigNodeSpecificConfig`

GetNodeSpecificConfig returns the NodeSpecificConfig field if non-nil, zero value otherwise.

### GetNodeSpecificConfigOk

`func (o *ClusterConfig) GetNodeSpecificConfigOk() (*ClusterConfigNodeSpecificConfig, bool)`

GetNodeSpecificConfigOk returns a tuple with the NodeSpecificConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeSpecificConfig

`func (o *ClusterConfig) SetNodeSpecificConfig(v ClusterConfigNodeSpecificConfig)`

SetNodeSpecificConfig sets NodeSpecificConfig field to given value.

### HasNodeSpecificConfig

`func (o *ClusterConfig) HasNodeSpecificConfig() bool`

HasNodeSpecificConfig returns a boolean if a field has been set.

### GetPackageConfig

`func (o *ClusterConfig) GetPackageConfig() ClusterConfigPackageConfig`

GetPackageConfig returns the PackageConfig field if non-nil, zero value otherwise.

### GetPackageConfigOk

`func (o *ClusterConfig) GetPackageConfigOk() (*ClusterConfigPackageConfig, bool)`

GetPackageConfigOk returns a tuple with the PackageConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageConfig

`func (o *ClusterConfig) SetPackageConfig(v ClusterConfigPackageConfig)`

SetPackageConfig sets PackageConfig field to given value.

### HasPackageConfig

`func (o *ClusterConfig) HasPackageConfig() bool`

HasPackageConfig returns a boolean if a field has been set.

### GetMonitorInterval

`func (o *ClusterConfig) GetMonitorInterval() float32`

GetMonitorInterval returns the MonitorInterval field if non-nil, zero value otherwise.

### GetMonitorIntervalOk

`func (o *ClusterConfig) GetMonitorIntervalOk() (*float32, bool)`

GetMonitorIntervalOk returns a tuple with the MonitorInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitorInterval

`func (o *ClusterConfig) SetMonitorInterval(v float32)`

SetMonitorInterval sets MonitorInterval field to given value.

### HasMonitorInterval

`func (o *ClusterConfig) HasMonitorInterval() bool`

HasMonitorInterval returns a boolean if a field has been set.

### GetCsp

`func (o *ClusterConfig) GetCsp() bool`

GetCsp returns the Csp field if non-nil, zero value otherwise.

### GetCspOk

`func (o *ClusterConfig) GetCspOk() (*bool, bool)`

GetCspOk returns a tuple with the Csp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsp

`func (o *ClusterConfig) SetCsp(v bool)`

SetCsp sets Csp field to given value.

### HasCsp

`func (o *ClusterConfig) HasCsp() bool`

HasCsp returns a boolean if a field has been set.

### GetCdk

`func (o *ClusterConfig) GetCdk() bool`

GetCdk returns the Cdk field if non-nil, zero value otherwise.

### GetCdkOk

`func (o *ClusterConfig) GetCdkOk() (*bool, bool)`

GetCdkOk returns a tuple with the Cdk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCdk

`func (o *ClusterConfig) SetCdk(v bool)`

SetCdk sets Cdk field to given value.

### HasCdk

`func (o *ClusterConfig) HasCdk() bool`

HasCdk returns a boolean if a field has been set.

### GetCharmExtensionPaths

`func (o *ClusterConfig) GetCharmExtensionPaths() []string`

GetCharmExtensionPaths returns the CharmExtensionPaths field if non-nil, zero value otherwise.

### GetCharmExtensionPathsOk

`func (o *ClusterConfig) GetCharmExtensionPathsOk() (*[]string, bool)`

GetCharmExtensionPathsOk returns a tuple with the CharmExtensionPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmExtensionPaths

`func (o *ClusterConfig) SetCharmExtensionPaths(v []string)`

SetCharmExtensionPaths sets CharmExtensionPaths field to given value.

### HasCharmExtensionPaths

`func (o *ClusterConfig) HasCharmExtensionPaths() bool`

HasCharmExtensionPaths returns a boolean if a field has been set.

### GetFirmwareCache

`func (o *ClusterConfig) GetFirmwareCache() string`

GetFirmwareCache returns the FirmwareCache field if non-nil, zero value otherwise.

### GetFirmwareCacheOk

`func (o *ClusterConfig) GetFirmwareCacheOk() (*string, bool)`

GetFirmwareCacheOk returns a tuple with the FirmwareCache field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwareCache

`func (o *ClusterConfig) SetFirmwareCache(v string)`

SetFirmwareCache sets FirmwareCache field to given value.

### HasFirmwareCache

`func (o *ClusterConfig) HasFirmwareCache() bool`

HasFirmwareCache returns a boolean if a field has been set.

### GetVstrm

`func (o *ClusterConfig) GetVstrm() string`

GetVstrm returns the Vstrm field if non-nil, zero value otherwise.

### GetVstrmOk

`func (o *ClusterConfig) GetVstrmOk() (*string, bool)`

GetVstrmOk returns a tuple with the Vstrm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVstrm

`func (o *ClusterConfig) SetVstrm(v string)`

SetVstrm sets Vstrm field to given value.

### HasVstrm

`func (o *ClusterConfig) HasVstrm() bool`

HasVstrm returns a boolean if a field has been set.

### GetConsole

`func (o *ClusterConfig) GetConsole() string`

GetConsole returns the Console field if non-nil, zero value otherwise.

### GetConsoleOk

`func (o *ClusterConfig) GetConsoleOk() (*string, bool)`

GetConsoleOk returns a tuple with the Console field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsole

`func (o *ClusterConfig) SetConsole(v string)`

SetConsole sets Console field to given value.

### HasConsole

`func (o *ClusterConfig) HasConsole() bool`

HasConsole returns a boolean if a field has been set.

### GetFetchFirmwareAssets

`func (o *ClusterConfig) GetFetchFirmwareAssets() bool`

GetFetchFirmwareAssets returns the FetchFirmwareAssets field if non-nil, zero value otherwise.

### GetFetchFirmwareAssetsOk

`func (o *ClusterConfig) GetFetchFirmwareAssetsOk() (*bool, bool)`

GetFetchFirmwareAssetsOk returns a tuple with the FetchFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFetchFirmwareAssets

`func (o *ClusterConfig) SetFetchFirmwareAssets(v bool)`

SetFetchFirmwareAssets sets FetchFirmwareAssets field to given value.

### HasFetchFirmwareAssets

`func (o *ClusterConfig) HasFetchFirmwareAssets() bool`

HasFetchFirmwareAssets returns a boolean if a field has been set.

### GetClusterFirmwareAssets

`func (o *ClusterConfig) GetClusterFirmwareAssets() bool`

GetClusterFirmwareAssets returns the ClusterFirmwareAssets field if non-nil, zero value otherwise.

### GetClusterFirmwareAssetsOk

`func (o *ClusterConfig) GetClusterFirmwareAssetsOk() (*bool, bool)`

GetClusterFirmwareAssetsOk returns a tuple with the ClusterFirmwareAssets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterFirmwareAssets

`func (o *ClusterConfig) SetClusterFirmwareAssets(v bool)`

SetClusterFirmwareAssets sets ClusterFirmwareAssets field to given value.

### HasClusterFirmwareAssets

`func (o *ClusterConfig) HasClusterFirmwareAssets() bool`

HasClusterFirmwareAssets returns a boolean if a field has been set.

### GetAuthProviders

`func (o *ClusterConfig) GetAuthProviders() []ClusterConfigCoordinatorConfigAuthProvidersInner`

GetAuthProviders returns the AuthProviders field if non-nil, zero value otherwise.

### GetAuthProvidersOk

`func (o *ClusterConfig) GetAuthProvidersOk() (*[]ClusterConfigCoordinatorConfigAuthProvidersInner, bool)`

GetAuthProvidersOk returns a tuple with the AuthProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthProviders

`func (o *ClusterConfig) SetAuthProviders(v []ClusterConfigCoordinatorConfigAuthProvidersInner)`

SetAuthProviders sets AuthProviders field to given value.

### HasAuthProviders

`func (o *ClusterConfig) HasAuthProviders() bool`

HasAuthProviders returns a boolean if a field has been set.

### GetDomain

`func (o *ClusterConfig) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ClusterConfig) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ClusterConfig) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *ClusterConfig) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetServiceDomain

`func (o *ClusterConfig) GetServiceDomain() string`

GetServiceDomain returns the ServiceDomain field if non-nil, zero value otherwise.

### GetServiceDomainOk

`func (o *ClusterConfig) GetServiceDomainOk() (*string, bool)`

GetServiceDomainOk returns a tuple with the ServiceDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceDomain

`func (o *ClusterConfig) SetServiceDomain(v string)`

SetServiceDomain sets ServiceDomain field to given value.

### HasServiceDomain

`func (o *ClusterConfig) HasServiceDomain() bool`

HasServiceDomain returns a boolean if a field has been set.

### GetServiceUser

`func (o *ClusterConfig) GetServiceUser() string`

GetServiceUser returns the ServiceUser field if non-nil, zero value otherwise.

### GetServiceUserOk

`func (o *ClusterConfig) GetServiceUserOk() (*string, bool)`

GetServiceUserOk returns a tuple with the ServiceUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceUser

`func (o *ClusterConfig) SetServiceUser(v string)`

SetServiceUser sets ServiceUser field to given value.

### HasServiceUser

`func (o *ClusterConfig) HasServiceUser() bool`

HasServiceUser returns a boolean if a field has been set.

### GetDomainImageUploadQuota

`func (o *ClusterConfig) GetDomainImageUploadQuota() float32`

GetDomainImageUploadQuota returns the DomainImageUploadQuota field if non-nil, zero value otherwise.

### GetDomainImageUploadQuotaOk

`func (o *ClusterConfig) GetDomainImageUploadQuotaOk() (*float32, bool)`

GetDomainImageUploadQuotaOk returns a tuple with the DomainImageUploadQuota field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainImageUploadQuota

`func (o *ClusterConfig) SetDomainImageUploadQuota(v float32)`

SetDomainImageUploadQuota sets DomainImageUploadQuota field to given value.

### HasDomainImageUploadQuota

`func (o *ClusterConfig) HasDomainImageUploadQuota() bool`

HasDomainImageUploadQuota returns a boolean if a field has been set.

### GetIpswFilters

`func (o *ClusterConfig) GetIpswFilters() []ClusterConfigIpswFiltersInner`

GetIpswFilters returns the IpswFilters field if non-nil, zero value otherwise.

### GetIpswFiltersOk

`func (o *ClusterConfig) GetIpswFiltersOk() (*[]ClusterConfigIpswFiltersInner, bool)`

GetIpswFiltersOk returns a tuple with the IpswFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpswFilters

`func (o *ClusterConfig) SetIpswFilters(v []ClusterConfigIpswFiltersInner)`

SetIpswFilters sets IpswFilters field to given value.

### HasIpswFilters

`func (o *ClusterConfig) HasIpswFilters() bool`

HasIpswFilters returns a boolean if a field has been set.

### GetFirmwareServiceConfig

`func (o *ClusterConfig) GetFirmwareServiceConfig() ClusterConfigFirmwareServiceConfig`

GetFirmwareServiceConfig returns the FirmwareServiceConfig field if non-nil, zero value otherwise.

### GetFirmwareServiceConfigOk

`func (o *ClusterConfig) GetFirmwareServiceConfigOk() (*ClusterConfigFirmwareServiceConfig, bool)`

GetFirmwareServiceConfigOk returns a tuple with the FirmwareServiceConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirmwareServiceConfig

`func (o *ClusterConfig) SetFirmwareServiceConfig(v ClusterConfigFirmwareServiceConfig)`

SetFirmwareServiceConfig sets FirmwareServiceConfig field to given value.

### HasFirmwareServiceConfig

`func (o *ClusterConfig) HasFirmwareServiceConfig() bool`

HasFirmwareServiceConfig returns a boolean if a field has been set.

### GetAiToolsConfig

`func (o *ClusterConfig) GetAiToolsConfig() AiToolsConfig`

GetAiToolsConfig returns the AiToolsConfig field if non-nil, zero value otherwise.

### GetAiToolsConfigOk

`func (o *ClusterConfig) GetAiToolsConfigOk() (*AiToolsConfig, bool)`

GetAiToolsConfigOk returns a tuple with the AiToolsConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiToolsConfig

`func (o *ClusterConfig) SetAiToolsConfig(v AiToolsConfig)`

SetAiToolsConfig sets AiToolsConfig field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


