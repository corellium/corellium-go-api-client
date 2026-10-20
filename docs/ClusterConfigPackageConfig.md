# ClusterConfigPackageConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LicenseType** | Pointer to **string** |  | [optional] 
**ClusterId** | Pointer to **string** |  | [optional] 
**NetworkType** | Pointer to **string** |  | [optional] 
**PhysicalInterfaces** | Pointer to **map[string]string** |  | [optional] 
**Features** | Pointer to [**ClusterConfigPackageConfigFeatures**](ClusterConfigPackageConfigFeatures.md) |  | [optional] 
**Components** | Pointer to [**ClusterConfigPackageConfigComponents**](ClusterConfigPackageConfigComponents.md) |  | [optional] 
**TermsOfService** | Pointer to **string** |  | [optional] 
**DomainAuthenticationProviders** | Pointer to **bool** |  | [optional] 
**MaxNetworkMonitorFileSize** | Pointer to **string** |  | [optional] 
**Combined** | Pointer to **bool** |  | [optional] 
**FlavorFilters** | [**[]ClusterConfigPackageConfigFlavorFiltersInner**](ClusterConfigPackageConfigFlavorFiltersInner.md) |  | 
**CharmSDK** | Pointer to **bool** |  | [optional] 
**HighlyAvailable** | Pointer to **bool** |  | [optional] 
**NodeVersion** | Pointer to **string** |  | [optional] 
**InvalidBuild** | Pointer to **bool** |  | [optional] 
**SepSim** | Pointer to **bool** |  | [optional] 
**KernelGDB** | Pointer to **bool** |  | [optional] 
**Android** | Pointer to **bool** |  | [optional] 
**NoIOS** | Pointer to **bool** |  | [optional] 
**IosBetas** | Pointer to **bool** |  | [optional] 
**CharmModules** | Pointer to **bool** |  | [optional] 
**Btrace** | Pointer to **bool** |  | [optional] 
**Strace** | Pointer to **bool** |  | [optional] 
**GameStreaming** | Pointer to **bool** |  | [optional] 
**ContainerTemplateGeneration** | Pointer to **string** |  | [optional] 
**S3Supported** | Pointer to **bool** |  | [optional] 

## Methods

### NewClusterConfigPackageConfig

`func NewClusterConfigPackageConfig(flavorFilters []ClusterConfigPackageConfigFlavorFiltersInner, ) *ClusterConfigPackageConfig`

NewClusterConfigPackageConfig instantiates a new ClusterConfigPackageConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigPackageConfigWithDefaults

`func NewClusterConfigPackageConfigWithDefaults() *ClusterConfigPackageConfig`

NewClusterConfigPackageConfigWithDefaults instantiates a new ClusterConfigPackageConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLicenseType

`func (o *ClusterConfigPackageConfig) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *ClusterConfigPackageConfig) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *ClusterConfigPackageConfig) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.

### HasLicenseType

`func (o *ClusterConfigPackageConfig) HasLicenseType() bool`

HasLicenseType returns a boolean if a field has been set.

### GetClusterId

`func (o *ClusterConfigPackageConfig) GetClusterId() string`

GetClusterId returns the ClusterId field if non-nil, zero value otherwise.

### GetClusterIdOk

`func (o *ClusterConfigPackageConfig) GetClusterIdOk() (*string, bool)`

GetClusterIdOk returns a tuple with the ClusterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterId

`func (o *ClusterConfigPackageConfig) SetClusterId(v string)`

SetClusterId sets ClusterId field to given value.

### HasClusterId

`func (o *ClusterConfigPackageConfig) HasClusterId() bool`

HasClusterId returns a boolean if a field has been set.

### GetNetworkType

`func (o *ClusterConfigPackageConfig) GetNetworkType() string`

GetNetworkType returns the NetworkType field if non-nil, zero value otherwise.

### GetNetworkTypeOk

`func (o *ClusterConfigPackageConfig) GetNetworkTypeOk() (*string, bool)`

GetNetworkTypeOk returns a tuple with the NetworkType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkType

`func (o *ClusterConfigPackageConfig) SetNetworkType(v string)`

SetNetworkType sets NetworkType field to given value.

### HasNetworkType

`func (o *ClusterConfigPackageConfig) HasNetworkType() bool`

HasNetworkType returns a boolean if a field has been set.

### GetPhysicalInterfaces

`func (o *ClusterConfigPackageConfig) GetPhysicalInterfaces() map[string]string`

GetPhysicalInterfaces returns the PhysicalInterfaces field if non-nil, zero value otherwise.

### GetPhysicalInterfacesOk

`func (o *ClusterConfigPackageConfig) GetPhysicalInterfacesOk() (*map[string]string, bool)`

GetPhysicalInterfacesOk returns a tuple with the PhysicalInterfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhysicalInterfaces

`func (o *ClusterConfigPackageConfig) SetPhysicalInterfaces(v map[string]string)`

SetPhysicalInterfaces sets PhysicalInterfaces field to given value.

### HasPhysicalInterfaces

`func (o *ClusterConfigPackageConfig) HasPhysicalInterfaces() bool`

HasPhysicalInterfaces returns a boolean if a field has been set.

### GetFeatures

`func (o *ClusterConfigPackageConfig) GetFeatures() ClusterConfigPackageConfigFeatures`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *ClusterConfigPackageConfig) GetFeaturesOk() (*ClusterConfigPackageConfigFeatures, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *ClusterConfigPackageConfig) SetFeatures(v ClusterConfigPackageConfigFeatures)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *ClusterConfigPackageConfig) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### GetComponents

`func (o *ClusterConfigPackageConfig) GetComponents() ClusterConfigPackageConfigComponents`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *ClusterConfigPackageConfig) GetComponentsOk() (*ClusterConfigPackageConfigComponents, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *ClusterConfigPackageConfig) SetComponents(v ClusterConfigPackageConfigComponents)`

SetComponents sets Components field to given value.

### HasComponents

`func (o *ClusterConfigPackageConfig) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### GetTermsOfService

`func (o *ClusterConfigPackageConfig) GetTermsOfService() string`

GetTermsOfService returns the TermsOfService field if non-nil, zero value otherwise.

### GetTermsOfServiceOk

`func (o *ClusterConfigPackageConfig) GetTermsOfServiceOk() (*string, bool)`

GetTermsOfServiceOk returns a tuple with the TermsOfService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsOfService

`func (o *ClusterConfigPackageConfig) SetTermsOfService(v string)`

SetTermsOfService sets TermsOfService field to given value.

### HasTermsOfService

`func (o *ClusterConfigPackageConfig) HasTermsOfService() bool`

HasTermsOfService returns a boolean if a field has been set.

### GetDomainAuthenticationProviders

`func (o *ClusterConfigPackageConfig) GetDomainAuthenticationProviders() bool`

GetDomainAuthenticationProviders returns the DomainAuthenticationProviders field if non-nil, zero value otherwise.

### GetDomainAuthenticationProvidersOk

`func (o *ClusterConfigPackageConfig) GetDomainAuthenticationProvidersOk() (*bool, bool)`

GetDomainAuthenticationProvidersOk returns a tuple with the DomainAuthenticationProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainAuthenticationProviders

`func (o *ClusterConfigPackageConfig) SetDomainAuthenticationProviders(v bool)`

SetDomainAuthenticationProviders sets DomainAuthenticationProviders field to given value.

### HasDomainAuthenticationProviders

`func (o *ClusterConfigPackageConfig) HasDomainAuthenticationProviders() bool`

HasDomainAuthenticationProviders returns a boolean if a field has been set.

### GetMaxNetworkMonitorFileSize

`func (o *ClusterConfigPackageConfig) GetMaxNetworkMonitorFileSize() string`

GetMaxNetworkMonitorFileSize returns the MaxNetworkMonitorFileSize field if non-nil, zero value otherwise.

### GetMaxNetworkMonitorFileSizeOk

`func (o *ClusterConfigPackageConfig) GetMaxNetworkMonitorFileSizeOk() (*string, bool)`

GetMaxNetworkMonitorFileSizeOk returns a tuple with the MaxNetworkMonitorFileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNetworkMonitorFileSize

`func (o *ClusterConfigPackageConfig) SetMaxNetworkMonitorFileSize(v string)`

SetMaxNetworkMonitorFileSize sets MaxNetworkMonitorFileSize field to given value.

### HasMaxNetworkMonitorFileSize

`func (o *ClusterConfigPackageConfig) HasMaxNetworkMonitorFileSize() bool`

HasMaxNetworkMonitorFileSize returns a boolean if a field has been set.

### GetCombined

`func (o *ClusterConfigPackageConfig) GetCombined() bool`

GetCombined returns the Combined field if non-nil, zero value otherwise.

### GetCombinedOk

`func (o *ClusterConfigPackageConfig) GetCombinedOk() (*bool, bool)`

GetCombinedOk returns a tuple with the Combined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCombined

`func (o *ClusterConfigPackageConfig) SetCombined(v bool)`

SetCombined sets Combined field to given value.

### HasCombined

`func (o *ClusterConfigPackageConfig) HasCombined() bool`

HasCombined returns a boolean if a field has been set.

### GetFlavorFilters

`func (o *ClusterConfigPackageConfig) GetFlavorFilters() []ClusterConfigPackageConfigFlavorFiltersInner`

GetFlavorFilters returns the FlavorFilters field if non-nil, zero value otherwise.

### GetFlavorFiltersOk

`func (o *ClusterConfigPackageConfig) GetFlavorFiltersOk() (*[]ClusterConfigPackageConfigFlavorFiltersInner, bool)`

GetFlavorFiltersOk returns a tuple with the FlavorFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavorFilters

`func (o *ClusterConfigPackageConfig) SetFlavorFilters(v []ClusterConfigPackageConfigFlavorFiltersInner)`

SetFlavorFilters sets FlavorFilters field to given value.


### GetCharmSDK

`func (o *ClusterConfigPackageConfig) GetCharmSDK() bool`

GetCharmSDK returns the CharmSDK field if non-nil, zero value otherwise.

### GetCharmSDKOk

`func (o *ClusterConfigPackageConfig) GetCharmSDKOk() (*bool, bool)`

GetCharmSDKOk returns a tuple with the CharmSDK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmSDK

`func (o *ClusterConfigPackageConfig) SetCharmSDK(v bool)`

SetCharmSDK sets CharmSDK field to given value.

### HasCharmSDK

`func (o *ClusterConfigPackageConfig) HasCharmSDK() bool`

HasCharmSDK returns a boolean if a field has been set.

### GetHighlyAvailable

`func (o *ClusterConfigPackageConfig) GetHighlyAvailable() bool`

GetHighlyAvailable returns the HighlyAvailable field if non-nil, zero value otherwise.

### GetHighlyAvailableOk

`func (o *ClusterConfigPackageConfig) GetHighlyAvailableOk() (*bool, bool)`

GetHighlyAvailableOk returns a tuple with the HighlyAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHighlyAvailable

`func (o *ClusterConfigPackageConfig) SetHighlyAvailable(v bool)`

SetHighlyAvailable sets HighlyAvailable field to given value.

### HasHighlyAvailable

`func (o *ClusterConfigPackageConfig) HasHighlyAvailable() bool`

HasHighlyAvailable returns a boolean if a field has been set.

### GetNodeVersion

`func (o *ClusterConfigPackageConfig) GetNodeVersion() string`

GetNodeVersion returns the NodeVersion field if non-nil, zero value otherwise.

### GetNodeVersionOk

`func (o *ClusterConfigPackageConfig) GetNodeVersionOk() (*string, bool)`

GetNodeVersionOk returns a tuple with the NodeVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeVersion

`func (o *ClusterConfigPackageConfig) SetNodeVersion(v string)`

SetNodeVersion sets NodeVersion field to given value.

### HasNodeVersion

`func (o *ClusterConfigPackageConfig) HasNodeVersion() bool`

HasNodeVersion returns a boolean if a field has been set.

### GetInvalidBuild

`func (o *ClusterConfigPackageConfig) GetInvalidBuild() bool`

GetInvalidBuild returns the InvalidBuild field if non-nil, zero value otherwise.

### GetInvalidBuildOk

`func (o *ClusterConfigPackageConfig) GetInvalidBuildOk() (*bool, bool)`

GetInvalidBuildOk returns a tuple with the InvalidBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvalidBuild

`func (o *ClusterConfigPackageConfig) SetInvalidBuild(v bool)`

SetInvalidBuild sets InvalidBuild field to given value.

### HasInvalidBuild

`func (o *ClusterConfigPackageConfig) HasInvalidBuild() bool`

HasInvalidBuild returns a boolean if a field has been set.

### GetSepSim

`func (o *ClusterConfigPackageConfig) GetSepSim() bool`

GetSepSim returns the SepSim field if non-nil, zero value otherwise.

### GetSepSimOk

`func (o *ClusterConfigPackageConfig) GetSepSimOk() (*bool, bool)`

GetSepSimOk returns a tuple with the SepSim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepSim

`func (o *ClusterConfigPackageConfig) SetSepSim(v bool)`

SetSepSim sets SepSim field to given value.

### HasSepSim

`func (o *ClusterConfigPackageConfig) HasSepSim() bool`

HasSepSim returns a boolean if a field has been set.

### GetKernelGDB

`func (o *ClusterConfigPackageConfig) GetKernelGDB() bool`

GetKernelGDB returns the KernelGDB field if non-nil, zero value otherwise.

### GetKernelGDBOk

`func (o *ClusterConfigPackageConfig) GetKernelGDBOk() (*bool, bool)`

GetKernelGDBOk returns a tuple with the KernelGDB field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelGDB

`func (o *ClusterConfigPackageConfig) SetKernelGDB(v bool)`

SetKernelGDB sets KernelGDB field to given value.

### HasKernelGDB

`func (o *ClusterConfigPackageConfig) HasKernelGDB() bool`

HasKernelGDB returns a boolean if a field has been set.

### GetAndroid

`func (o *ClusterConfigPackageConfig) GetAndroid() bool`

GetAndroid returns the Android field if non-nil, zero value otherwise.

### GetAndroidOk

`func (o *ClusterConfigPackageConfig) GetAndroidOk() (*bool, bool)`

GetAndroidOk returns a tuple with the Android field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroid

`func (o *ClusterConfigPackageConfig) SetAndroid(v bool)`

SetAndroid sets Android field to given value.

### HasAndroid

`func (o *ClusterConfigPackageConfig) HasAndroid() bool`

HasAndroid returns a boolean if a field has been set.

### GetNoIOS

`func (o *ClusterConfigPackageConfig) GetNoIOS() bool`

GetNoIOS returns the NoIOS field if non-nil, zero value otherwise.

### GetNoIOSOk

`func (o *ClusterConfigPackageConfig) GetNoIOSOk() (*bool, bool)`

GetNoIOSOk returns a tuple with the NoIOS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoIOS

`func (o *ClusterConfigPackageConfig) SetNoIOS(v bool)`

SetNoIOS sets NoIOS field to given value.

### HasNoIOS

`func (o *ClusterConfigPackageConfig) HasNoIOS() bool`

HasNoIOS returns a boolean if a field has been set.

### GetIosBetas

`func (o *ClusterConfigPackageConfig) GetIosBetas() bool`

GetIosBetas returns the IosBetas field if non-nil, zero value otherwise.

### GetIosBetasOk

`func (o *ClusterConfigPackageConfig) GetIosBetasOk() (*bool, bool)`

GetIosBetasOk returns a tuple with the IosBetas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIosBetas

`func (o *ClusterConfigPackageConfig) SetIosBetas(v bool)`

SetIosBetas sets IosBetas field to given value.

### HasIosBetas

`func (o *ClusterConfigPackageConfig) HasIosBetas() bool`

HasIosBetas returns a boolean if a field has been set.

### GetCharmModules

`func (o *ClusterConfigPackageConfig) GetCharmModules() bool`

GetCharmModules returns the CharmModules field if non-nil, zero value otherwise.

### GetCharmModulesOk

`func (o *ClusterConfigPackageConfig) GetCharmModulesOk() (*bool, bool)`

GetCharmModulesOk returns a tuple with the CharmModules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharmModules

`func (o *ClusterConfigPackageConfig) SetCharmModules(v bool)`

SetCharmModules sets CharmModules field to given value.

### HasCharmModules

`func (o *ClusterConfigPackageConfig) HasCharmModules() bool`

HasCharmModules returns a boolean if a field has been set.

### GetBtrace

`func (o *ClusterConfigPackageConfig) GetBtrace() bool`

GetBtrace returns the Btrace field if non-nil, zero value otherwise.

### GetBtraceOk

`func (o *ClusterConfigPackageConfig) GetBtraceOk() (*bool, bool)`

GetBtraceOk returns a tuple with the Btrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBtrace

`func (o *ClusterConfigPackageConfig) SetBtrace(v bool)`

SetBtrace sets Btrace field to given value.

### HasBtrace

`func (o *ClusterConfigPackageConfig) HasBtrace() bool`

HasBtrace returns a boolean if a field has been set.

### GetStrace

`func (o *ClusterConfigPackageConfig) GetStrace() bool`

GetStrace returns the Strace field if non-nil, zero value otherwise.

### GetStraceOk

`func (o *ClusterConfigPackageConfig) GetStraceOk() (*bool, bool)`

GetStraceOk returns a tuple with the Strace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrace

`func (o *ClusterConfigPackageConfig) SetStrace(v bool)`

SetStrace sets Strace field to given value.

### HasStrace

`func (o *ClusterConfigPackageConfig) HasStrace() bool`

HasStrace returns a boolean if a field has been set.

### GetGameStreaming

`func (o *ClusterConfigPackageConfig) GetGameStreaming() bool`

GetGameStreaming returns the GameStreaming field if non-nil, zero value otherwise.

### GetGameStreamingOk

`func (o *ClusterConfigPackageConfig) GetGameStreamingOk() (*bool, bool)`

GetGameStreamingOk returns a tuple with the GameStreaming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGameStreaming

`func (o *ClusterConfigPackageConfig) SetGameStreaming(v bool)`

SetGameStreaming sets GameStreaming field to given value.

### HasGameStreaming

`func (o *ClusterConfigPackageConfig) HasGameStreaming() bool`

HasGameStreaming returns a boolean if a field has been set.

### GetContainerTemplateGeneration

`func (o *ClusterConfigPackageConfig) GetContainerTemplateGeneration() string`

GetContainerTemplateGeneration returns the ContainerTemplateGeneration field if non-nil, zero value otherwise.

### GetContainerTemplateGenerationOk

`func (o *ClusterConfigPackageConfig) GetContainerTemplateGenerationOk() (*string, bool)`

GetContainerTemplateGenerationOk returns a tuple with the ContainerTemplateGeneration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainerTemplateGeneration

`func (o *ClusterConfigPackageConfig) SetContainerTemplateGeneration(v string)`

SetContainerTemplateGeneration sets ContainerTemplateGeneration field to given value.

### HasContainerTemplateGeneration

`func (o *ClusterConfigPackageConfig) HasContainerTemplateGeneration() bool`

HasContainerTemplateGeneration returns a boolean if a field has been set.

### GetS3Supported

`func (o *ClusterConfigPackageConfig) GetS3Supported() bool`

GetS3Supported returns the S3Supported field if non-nil, zero value otherwise.

### GetS3SupportedOk

`func (o *ClusterConfigPackageConfig) GetS3SupportedOk() (*bool, bool)`

GetS3SupportedOk returns a tuple with the S3Supported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetS3Supported

`func (o *ClusterConfigPackageConfig) SetS3Supported(v bool)`

SetS3Supported sets S3Supported field to given value.

### HasS3Supported

`func (o *ClusterConfigPackageConfig) HasS3Supported() bool`

HasS3Supported returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


