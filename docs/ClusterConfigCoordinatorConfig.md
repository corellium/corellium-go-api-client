# ClusterConfigCoordinatorConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BindHost** | **string** |  | 
**BindPort** | **float32** |  | 
**DbDatabase** | **string** |  | 
**DbHost** | **string** |  | 
**DbPort** | **float32** |  | 
**DbPassword** | **string** |  | 
**DbUser** | **string** |  | 
**DbLoggingEnabled** | **bool** |  | 
**ConfigDbHost** | Pointer to **string** |  | [optional] 
**ConfigDbPort** | Pointer to **float32** |  | [optional] 
**ConfigDbUser** | Pointer to **string** |  | [optional] 
**ConfigDbPassword** | Pointer to **string** |  | [optional] 
**ConfigDbName** | Pointer to **string** |  | [optional] 
**IpBlock** | **string** |  | 
**LocalIp** | **string** |  | 
**IpBlockNetmask** | **string** |  | 
**InstanceDNSServers** | Pointer to **[]string** |  | [optional] 
**OnSite** | **bool** |  | 
**PrivateHeaders** | **[]string** |  | 
**Trial** | Pointer to [**ClusterConfigCoordinatorConfigTrial**](ClusterConfigCoordinatorConfigTrial.md) |  | [optional] 
**TrialSurveyId** | **string** |  | 
**AuthProviders** | Pointer to [**[]ClusterConfigCoordinatorConfigAuthProvidersInner**](ClusterConfigCoordinatorConfigAuthProvidersInner.md) |  | [optional] 
**PerProjectStorageQuota** | Pointer to **float32** |  | [optional] 
**ImageDataPath** | Pointer to **string** |  | [optional] 
**EnsureDomain** | Pointer to [**ClusterConfigCoordinatorConfigEnsureDomain**](ClusterConfigCoordinatorConfigEnsureDomain.md) |  | [optional] 
**Hubspot** | Pointer to [**ClusterConfigCoordinatorConfigHubspot**](ClusterConfigCoordinatorConfigHubspot.md) |  | [optional] 
**NexusUrl** | Pointer to **string** |  | [optional] 
**BillingTradeCreditDays** | Pointer to **float32** |  | [optional] 
**JwtTokenExpiration** | Pointer to **float32** |  | [optional] 
**Hypertune** | Pointer to [**ClusterConfigCoordinatorConfigHypertune**](ClusterConfigCoordinatorConfigHypertune.md) |  | [optional] 
**AwsMarketplace** | Pointer to [**ClusterConfigCoordinatorConfigAwsMarketplace**](ClusterConfigCoordinatorConfigAwsMarketplace.md) |  | [optional] 
**Pipedrive** | Pointer to [**ClusterConfigCoordinatorConfigPipedrive**](ClusterConfigCoordinatorConfigPipedrive.md) |  | [optional] 
**Webplayer** | Pointer to [**ClusterConfigCoordinatorConfigWebplayer**](ClusterConfigCoordinatorConfigWebplayer.md) |  | [optional] 
**PostmarkServerToken** | Pointer to **string** |  | [optional] 
**PostmarkEmailFrom** | Pointer to **string** |  | [optional] 
**PostmarkEmailTemplate** | Pointer to **string** |  | [optional] 
**S3** | Pointer to **map[string]string** |  | [optional] 
**OfacApiKey** | Pointer to **string** |  | [optional] 
**UsbMediaQueueDir** | Pointer to **string** |  | [optional] 
**UsbMediaAccessEnabled** | Pointer to **bool** |  | [optional] 
**IntercomIdVerifySecret** | Pointer to **string** |  | [optional] 
**FvpSecret** | Pointer to **string** |  | [optional] 

## Methods

### NewClusterConfigCoordinatorConfig

`func NewClusterConfigCoordinatorConfig(bindHost string, bindPort float32, dbDatabase string, dbHost string, dbPort float32, dbPassword string, dbUser string, dbLoggingEnabled bool, ipBlock string, localIp string, ipBlockNetmask string, onSite bool, privateHeaders []string, trialSurveyId string, ) *ClusterConfigCoordinatorConfig`

NewClusterConfigCoordinatorConfig instantiates a new ClusterConfigCoordinatorConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigCoordinatorConfigWithDefaults

`func NewClusterConfigCoordinatorConfigWithDefaults() *ClusterConfigCoordinatorConfig`

NewClusterConfigCoordinatorConfigWithDefaults instantiates a new ClusterConfigCoordinatorConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBindHost

`func (o *ClusterConfigCoordinatorConfig) GetBindHost() string`

GetBindHost returns the BindHost field if non-nil, zero value otherwise.

### GetBindHostOk

`func (o *ClusterConfigCoordinatorConfig) GetBindHostOk() (*string, bool)`

GetBindHostOk returns a tuple with the BindHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindHost

`func (o *ClusterConfigCoordinatorConfig) SetBindHost(v string)`

SetBindHost sets BindHost field to given value.


### GetBindPort

`func (o *ClusterConfigCoordinatorConfig) GetBindPort() float32`

GetBindPort returns the BindPort field if non-nil, zero value otherwise.

### GetBindPortOk

`func (o *ClusterConfigCoordinatorConfig) GetBindPortOk() (*float32, bool)`

GetBindPortOk returns a tuple with the BindPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindPort

`func (o *ClusterConfigCoordinatorConfig) SetBindPort(v float32)`

SetBindPort sets BindPort field to given value.


### GetDbDatabase

`func (o *ClusterConfigCoordinatorConfig) GetDbDatabase() string`

GetDbDatabase returns the DbDatabase field if non-nil, zero value otherwise.

### GetDbDatabaseOk

`func (o *ClusterConfigCoordinatorConfig) GetDbDatabaseOk() (*string, bool)`

GetDbDatabaseOk returns a tuple with the DbDatabase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbDatabase

`func (o *ClusterConfigCoordinatorConfig) SetDbDatabase(v string)`

SetDbDatabase sets DbDatabase field to given value.


### GetDbHost

`func (o *ClusterConfigCoordinatorConfig) GetDbHost() string`

GetDbHost returns the DbHost field if non-nil, zero value otherwise.

### GetDbHostOk

`func (o *ClusterConfigCoordinatorConfig) GetDbHostOk() (*string, bool)`

GetDbHostOk returns a tuple with the DbHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbHost

`func (o *ClusterConfigCoordinatorConfig) SetDbHost(v string)`

SetDbHost sets DbHost field to given value.


### GetDbPort

`func (o *ClusterConfigCoordinatorConfig) GetDbPort() float32`

GetDbPort returns the DbPort field if non-nil, zero value otherwise.

### GetDbPortOk

`func (o *ClusterConfigCoordinatorConfig) GetDbPortOk() (*float32, bool)`

GetDbPortOk returns a tuple with the DbPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbPort

`func (o *ClusterConfigCoordinatorConfig) SetDbPort(v float32)`

SetDbPort sets DbPort field to given value.


### GetDbPassword

`func (o *ClusterConfigCoordinatorConfig) GetDbPassword() string`

GetDbPassword returns the DbPassword field if non-nil, zero value otherwise.

### GetDbPasswordOk

`func (o *ClusterConfigCoordinatorConfig) GetDbPasswordOk() (*string, bool)`

GetDbPasswordOk returns a tuple with the DbPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbPassword

`func (o *ClusterConfigCoordinatorConfig) SetDbPassword(v string)`

SetDbPassword sets DbPassword field to given value.


### GetDbUser

`func (o *ClusterConfigCoordinatorConfig) GetDbUser() string`

GetDbUser returns the DbUser field if non-nil, zero value otherwise.

### GetDbUserOk

`func (o *ClusterConfigCoordinatorConfig) GetDbUserOk() (*string, bool)`

GetDbUserOk returns a tuple with the DbUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbUser

`func (o *ClusterConfigCoordinatorConfig) SetDbUser(v string)`

SetDbUser sets DbUser field to given value.


### GetDbLoggingEnabled

`func (o *ClusterConfigCoordinatorConfig) GetDbLoggingEnabled() bool`

GetDbLoggingEnabled returns the DbLoggingEnabled field if non-nil, zero value otherwise.

### GetDbLoggingEnabledOk

`func (o *ClusterConfigCoordinatorConfig) GetDbLoggingEnabledOk() (*bool, bool)`

GetDbLoggingEnabledOk returns a tuple with the DbLoggingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDbLoggingEnabled

`func (o *ClusterConfigCoordinatorConfig) SetDbLoggingEnabled(v bool)`

SetDbLoggingEnabled sets DbLoggingEnabled field to given value.


### GetConfigDbHost

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbHost() string`

GetConfigDbHost returns the ConfigDbHost field if non-nil, zero value otherwise.

### GetConfigDbHostOk

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbHostOk() (*string, bool)`

GetConfigDbHostOk returns a tuple with the ConfigDbHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigDbHost

`func (o *ClusterConfigCoordinatorConfig) SetConfigDbHost(v string)`

SetConfigDbHost sets ConfigDbHost field to given value.

### HasConfigDbHost

`func (o *ClusterConfigCoordinatorConfig) HasConfigDbHost() bool`

HasConfigDbHost returns a boolean if a field has been set.

### GetConfigDbPort

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbPort() float32`

GetConfigDbPort returns the ConfigDbPort field if non-nil, zero value otherwise.

### GetConfigDbPortOk

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbPortOk() (*float32, bool)`

GetConfigDbPortOk returns a tuple with the ConfigDbPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigDbPort

`func (o *ClusterConfigCoordinatorConfig) SetConfigDbPort(v float32)`

SetConfigDbPort sets ConfigDbPort field to given value.

### HasConfigDbPort

`func (o *ClusterConfigCoordinatorConfig) HasConfigDbPort() bool`

HasConfigDbPort returns a boolean if a field has been set.

### GetConfigDbUser

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbUser() string`

GetConfigDbUser returns the ConfigDbUser field if non-nil, zero value otherwise.

### GetConfigDbUserOk

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbUserOk() (*string, bool)`

GetConfigDbUserOk returns a tuple with the ConfigDbUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigDbUser

`func (o *ClusterConfigCoordinatorConfig) SetConfigDbUser(v string)`

SetConfigDbUser sets ConfigDbUser field to given value.

### HasConfigDbUser

`func (o *ClusterConfigCoordinatorConfig) HasConfigDbUser() bool`

HasConfigDbUser returns a boolean if a field has been set.

### GetConfigDbPassword

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbPassword() string`

GetConfigDbPassword returns the ConfigDbPassword field if non-nil, zero value otherwise.

### GetConfigDbPasswordOk

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbPasswordOk() (*string, bool)`

GetConfigDbPasswordOk returns a tuple with the ConfigDbPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigDbPassword

`func (o *ClusterConfigCoordinatorConfig) SetConfigDbPassword(v string)`

SetConfigDbPassword sets ConfigDbPassword field to given value.

### HasConfigDbPassword

`func (o *ClusterConfigCoordinatorConfig) HasConfigDbPassword() bool`

HasConfigDbPassword returns a boolean if a field has been set.

### GetConfigDbName

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbName() string`

GetConfigDbName returns the ConfigDbName field if non-nil, zero value otherwise.

### GetConfigDbNameOk

`func (o *ClusterConfigCoordinatorConfig) GetConfigDbNameOk() (*string, bool)`

GetConfigDbNameOk returns a tuple with the ConfigDbName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigDbName

`func (o *ClusterConfigCoordinatorConfig) SetConfigDbName(v string)`

SetConfigDbName sets ConfigDbName field to given value.

### HasConfigDbName

`func (o *ClusterConfigCoordinatorConfig) HasConfigDbName() bool`

HasConfigDbName returns a boolean if a field has been set.

### GetIpBlock

`func (o *ClusterConfigCoordinatorConfig) GetIpBlock() string`

GetIpBlock returns the IpBlock field if non-nil, zero value otherwise.

### GetIpBlockOk

`func (o *ClusterConfigCoordinatorConfig) GetIpBlockOk() (*string, bool)`

GetIpBlockOk returns a tuple with the IpBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlock

`func (o *ClusterConfigCoordinatorConfig) SetIpBlock(v string)`

SetIpBlock sets IpBlock field to given value.


### GetLocalIp

`func (o *ClusterConfigCoordinatorConfig) GetLocalIp() string`

GetLocalIp returns the LocalIp field if non-nil, zero value otherwise.

### GetLocalIpOk

`func (o *ClusterConfigCoordinatorConfig) GetLocalIpOk() (*string, bool)`

GetLocalIpOk returns a tuple with the LocalIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIp

`func (o *ClusterConfigCoordinatorConfig) SetLocalIp(v string)`

SetLocalIp sets LocalIp field to given value.


### GetIpBlockNetmask

`func (o *ClusterConfigCoordinatorConfig) GetIpBlockNetmask() string`

GetIpBlockNetmask returns the IpBlockNetmask field if non-nil, zero value otherwise.

### GetIpBlockNetmaskOk

`func (o *ClusterConfigCoordinatorConfig) GetIpBlockNetmaskOk() (*string, bool)`

GetIpBlockNetmaskOk returns a tuple with the IpBlockNetmask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpBlockNetmask

`func (o *ClusterConfigCoordinatorConfig) SetIpBlockNetmask(v string)`

SetIpBlockNetmask sets IpBlockNetmask field to given value.


### GetInstanceDNSServers

`func (o *ClusterConfigCoordinatorConfig) GetInstanceDNSServers() []string`

GetInstanceDNSServers returns the InstanceDNSServers field if non-nil, zero value otherwise.

### GetInstanceDNSServersOk

`func (o *ClusterConfigCoordinatorConfig) GetInstanceDNSServersOk() (*[]string, bool)`

GetInstanceDNSServersOk returns a tuple with the InstanceDNSServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceDNSServers

`func (o *ClusterConfigCoordinatorConfig) SetInstanceDNSServers(v []string)`

SetInstanceDNSServers sets InstanceDNSServers field to given value.

### HasInstanceDNSServers

`func (o *ClusterConfigCoordinatorConfig) HasInstanceDNSServers() bool`

HasInstanceDNSServers returns a boolean if a field has been set.

### GetOnSite

`func (o *ClusterConfigCoordinatorConfig) GetOnSite() bool`

GetOnSite returns the OnSite field if non-nil, zero value otherwise.

### GetOnSiteOk

`func (o *ClusterConfigCoordinatorConfig) GetOnSiteOk() (*bool, bool)`

GetOnSiteOk returns a tuple with the OnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnSite

`func (o *ClusterConfigCoordinatorConfig) SetOnSite(v bool)`

SetOnSite sets OnSite field to given value.


### GetPrivateHeaders

`func (o *ClusterConfigCoordinatorConfig) GetPrivateHeaders() []string`

GetPrivateHeaders returns the PrivateHeaders field if non-nil, zero value otherwise.

### GetPrivateHeadersOk

`func (o *ClusterConfigCoordinatorConfig) GetPrivateHeadersOk() (*[]string, bool)`

GetPrivateHeadersOk returns a tuple with the PrivateHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateHeaders

`func (o *ClusterConfigCoordinatorConfig) SetPrivateHeaders(v []string)`

SetPrivateHeaders sets PrivateHeaders field to given value.


### GetTrial

`func (o *ClusterConfigCoordinatorConfig) GetTrial() ClusterConfigCoordinatorConfigTrial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *ClusterConfigCoordinatorConfig) GetTrialOk() (*ClusterConfigCoordinatorConfigTrial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *ClusterConfigCoordinatorConfig) SetTrial(v ClusterConfigCoordinatorConfigTrial)`

SetTrial sets Trial field to given value.

### HasTrial

`func (o *ClusterConfigCoordinatorConfig) HasTrial() bool`

HasTrial returns a boolean if a field has been set.

### GetTrialSurveyId

`func (o *ClusterConfigCoordinatorConfig) GetTrialSurveyId() string`

GetTrialSurveyId returns the TrialSurveyId field if non-nil, zero value otherwise.

### GetTrialSurveyIdOk

`func (o *ClusterConfigCoordinatorConfig) GetTrialSurveyIdOk() (*string, bool)`

GetTrialSurveyIdOk returns a tuple with the TrialSurveyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialSurveyId

`func (o *ClusterConfigCoordinatorConfig) SetTrialSurveyId(v string)`

SetTrialSurveyId sets TrialSurveyId field to given value.


### GetAuthProviders

`func (o *ClusterConfigCoordinatorConfig) GetAuthProviders() []ClusterConfigCoordinatorConfigAuthProvidersInner`

GetAuthProviders returns the AuthProviders field if non-nil, zero value otherwise.

### GetAuthProvidersOk

`func (o *ClusterConfigCoordinatorConfig) GetAuthProvidersOk() (*[]ClusterConfigCoordinatorConfigAuthProvidersInner, bool)`

GetAuthProvidersOk returns a tuple with the AuthProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthProviders

`func (o *ClusterConfigCoordinatorConfig) SetAuthProviders(v []ClusterConfigCoordinatorConfigAuthProvidersInner)`

SetAuthProviders sets AuthProviders field to given value.

### HasAuthProviders

`func (o *ClusterConfigCoordinatorConfig) HasAuthProviders() bool`

HasAuthProviders returns a boolean if a field has been set.

### GetPerProjectStorageQuota

`func (o *ClusterConfigCoordinatorConfig) GetPerProjectStorageQuota() float32`

GetPerProjectStorageQuota returns the PerProjectStorageQuota field if non-nil, zero value otherwise.

### GetPerProjectStorageQuotaOk

`func (o *ClusterConfigCoordinatorConfig) GetPerProjectStorageQuotaOk() (*float32, bool)`

GetPerProjectStorageQuotaOk returns a tuple with the PerProjectStorageQuota field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerProjectStorageQuota

`func (o *ClusterConfigCoordinatorConfig) SetPerProjectStorageQuota(v float32)`

SetPerProjectStorageQuota sets PerProjectStorageQuota field to given value.

### HasPerProjectStorageQuota

`func (o *ClusterConfigCoordinatorConfig) HasPerProjectStorageQuota() bool`

HasPerProjectStorageQuota returns a boolean if a field has been set.

### GetImageDataPath

`func (o *ClusterConfigCoordinatorConfig) GetImageDataPath() string`

GetImageDataPath returns the ImageDataPath field if non-nil, zero value otherwise.

### GetImageDataPathOk

`func (o *ClusterConfigCoordinatorConfig) GetImageDataPathOk() (*string, bool)`

GetImageDataPathOk returns a tuple with the ImageDataPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageDataPath

`func (o *ClusterConfigCoordinatorConfig) SetImageDataPath(v string)`

SetImageDataPath sets ImageDataPath field to given value.

### HasImageDataPath

`func (o *ClusterConfigCoordinatorConfig) HasImageDataPath() bool`

HasImageDataPath returns a boolean if a field has been set.

### GetEnsureDomain

`func (o *ClusterConfigCoordinatorConfig) GetEnsureDomain() ClusterConfigCoordinatorConfigEnsureDomain`

GetEnsureDomain returns the EnsureDomain field if non-nil, zero value otherwise.

### GetEnsureDomainOk

`func (o *ClusterConfigCoordinatorConfig) GetEnsureDomainOk() (*ClusterConfigCoordinatorConfigEnsureDomain, bool)`

GetEnsureDomainOk returns a tuple with the EnsureDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnsureDomain

`func (o *ClusterConfigCoordinatorConfig) SetEnsureDomain(v ClusterConfigCoordinatorConfigEnsureDomain)`

SetEnsureDomain sets EnsureDomain field to given value.

### HasEnsureDomain

`func (o *ClusterConfigCoordinatorConfig) HasEnsureDomain() bool`

HasEnsureDomain returns a boolean if a field has been set.

### GetHubspot

`func (o *ClusterConfigCoordinatorConfig) GetHubspot() ClusterConfigCoordinatorConfigHubspot`

GetHubspot returns the Hubspot field if non-nil, zero value otherwise.

### GetHubspotOk

`func (o *ClusterConfigCoordinatorConfig) GetHubspotOk() (*ClusterConfigCoordinatorConfigHubspot, bool)`

GetHubspotOk returns a tuple with the Hubspot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHubspot

`func (o *ClusterConfigCoordinatorConfig) SetHubspot(v ClusterConfigCoordinatorConfigHubspot)`

SetHubspot sets Hubspot field to given value.

### HasHubspot

`func (o *ClusterConfigCoordinatorConfig) HasHubspot() bool`

HasHubspot returns a boolean if a field has been set.

### GetNexusUrl

`func (o *ClusterConfigCoordinatorConfig) GetNexusUrl() string`

GetNexusUrl returns the NexusUrl field if non-nil, zero value otherwise.

### GetNexusUrlOk

`func (o *ClusterConfigCoordinatorConfig) GetNexusUrlOk() (*string, bool)`

GetNexusUrlOk returns a tuple with the NexusUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNexusUrl

`func (o *ClusterConfigCoordinatorConfig) SetNexusUrl(v string)`

SetNexusUrl sets NexusUrl field to given value.

### HasNexusUrl

`func (o *ClusterConfigCoordinatorConfig) HasNexusUrl() bool`

HasNexusUrl returns a boolean if a field has been set.

### GetBillingTradeCreditDays

`func (o *ClusterConfigCoordinatorConfig) GetBillingTradeCreditDays() float32`

GetBillingTradeCreditDays returns the BillingTradeCreditDays field if non-nil, zero value otherwise.

### GetBillingTradeCreditDaysOk

`func (o *ClusterConfigCoordinatorConfig) GetBillingTradeCreditDaysOk() (*float32, bool)`

GetBillingTradeCreditDaysOk returns a tuple with the BillingTradeCreditDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingTradeCreditDays

`func (o *ClusterConfigCoordinatorConfig) SetBillingTradeCreditDays(v float32)`

SetBillingTradeCreditDays sets BillingTradeCreditDays field to given value.

### HasBillingTradeCreditDays

`func (o *ClusterConfigCoordinatorConfig) HasBillingTradeCreditDays() bool`

HasBillingTradeCreditDays returns a boolean if a field has been set.

### GetJwtTokenExpiration

`func (o *ClusterConfigCoordinatorConfig) GetJwtTokenExpiration() float32`

GetJwtTokenExpiration returns the JwtTokenExpiration field if non-nil, zero value otherwise.

### GetJwtTokenExpirationOk

`func (o *ClusterConfigCoordinatorConfig) GetJwtTokenExpirationOk() (*float32, bool)`

GetJwtTokenExpirationOk returns a tuple with the JwtTokenExpiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJwtTokenExpiration

`func (o *ClusterConfigCoordinatorConfig) SetJwtTokenExpiration(v float32)`

SetJwtTokenExpiration sets JwtTokenExpiration field to given value.

### HasJwtTokenExpiration

`func (o *ClusterConfigCoordinatorConfig) HasJwtTokenExpiration() bool`

HasJwtTokenExpiration returns a boolean if a field has been set.

### GetHypertune

`func (o *ClusterConfigCoordinatorConfig) GetHypertune() ClusterConfigCoordinatorConfigHypertune`

GetHypertune returns the Hypertune field if non-nil, zero value otherwise.

### GetHypertuneOk

`func (o *ClusterConfigCoordinatorConfig) GetHypertuneOk() (*ClusterConfigCoordinatorConfigHypertune, bool)`

GetHypertuneOk returns a tuple with the Hypertune field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHypertune

`func (o *ClusterConfigCoordinatorConfig) SetHypertune(v ClusterConfigCoordinatorConfigHypertune)`

SetHypertune sets Hypertune field to given value.

### HasHypertune

`func (o *ClusterConfigCoordinatorConfig) HasHypertune() bool`

HasHypertune returns a boolean if a field has been set.

### GetAwsMarketplace

`func (o *ClusterConfigCoordinatorConfig) GetAwsMarketplace() ClusterConfigCoordinatorConfigAwsMarketplace`

GetAwsMarketplace returns the AwsMarketplace field if non-nil, zero value otherwise.

### GetAwsMarketplaceOk

`func (o *ClusterConfigCoordinatorConfig) GetAwsMarketplaceOk() (*ClusterConfigCoordinatorConfigAwsMarketplace, bool)`

GetAwsMarketplaceOk returns a tuple with the AwsMarketplace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwsMarketplace

`func (o *ClusterConfigCoordinatorConfig) SetAwsMarketplace(v ClusterConfigCoordinatorConfigAwsMarketplace)`

SetAwsMarketplace sets AwsMarketplace field to given value.

### HasAwsMarketplace

`func (o *ClusterConfigCoordinatorConfig) HasAwsMarketplace() bool`

HasAwsMarketplace returns a boolean if a field has been set.

### GetPipedrive

`func (o *ClusterConfigCoordinatorConfig) GetPipedrive() ClusterConfigCoordinatorConfigPipedrive`

GetPipedrive returns the Pipedrive field if non-nil, zero value otherwise.

### GetPipedriveOk

`func (o *ClusterConfigCoordinatorConfig) GetPipedriveOk() (*ClusterConfigCoordinatorConfigPipedrive, bool)`

GetPipedriveOk returns a tuple with the Pipedrive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipedrive

`func (o *ClusterConfigCoordinatorConfig) SetPipedrive(v ClusterConfigCoordinatorConfigPipedrive)`

SetPipedrive sets Pipedrive field to given value.

### HasPipedrive

`func (o *ClusterConfigCoordinatorConfig) HasPipedrive() bool`

HasPipedrive returns a boolean if a field has been set.

### GetWebplayer

`func (o *ClusterConfigCoordinatorConfig) GetWebplayer() ClusterConfigCoordinatorConfigWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *ClusterConfigCoordinatorConfig) GetWebplayerOk() (*ClusterConfigCoordinatorConfigWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *ClusterConfigCoordinatorConfig) SetWebplayer(v ClusterConfigCoordinatorConfigWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *ClusterConfigCoordinatorConfig) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetPostmarkServerToken

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkServerToken() string`

GetPostmarkServerToken returns the PostmarkServerToken field if non-nil, zero value otherwise.

### GetPostmarkServerTokenOk

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkServerTokenOk() (*string, bool)`

GetPostmarkServerTokenOk returns a tuple with the PostmarkServerToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostmarkServerToken

`func (o *ClusterConfigCoordinatorConfig) SetPostmarkServerToken(v string)`

SetPostmarkServerToken sets PostmarkServerToken field to given value.

### HasPostmarkServerToken

`func (o *ClusterConfigCoordinatorConfig) HasPostmarkServerToken() bool`

HasPostmarkServerToken returns a boolean if a field has been set.

### GetPostmarkEmailFrom

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkEmailFrom() string`

GetPostmarkEmailFrom returns the PostmarkEmailFrom field if non-nil, zero value otherwise.

### GetPostmarkEmailFromOk

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkEmailFromOk() (*string, bool)`

GetPostmarkEmailFromOk returns a tuple with the PostmarkEmailFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostmarkEmailFrom

`func (o *ClusterConfigCoordinatorConfig) SetPostmarkEmailFrom(v string)`

SetPostmarkEmailFrom sets PostmarkEmailFrom field to given value.

### HasPostmarkEmailFrom

`func (o *ClusterConfigCoordinatorConfig) HasPostmarkEmailFrom() bool`

HasPostmarkEmailFrom returns a boolean if a field has been set.

### GetPostmarkEmailTemplate

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkEmailTemplate() string`

GetPostmarkEmailTemplate returns the PostmarkEmailTemplate field if non-nil, zero value otherwise.

### GetPostmarkEmailTemplateOk

`func (o *ClusterConfigCoordinatorConfig) GetPostmarkEmailTemplateOk() (*string, bool)`

GetPostmarkEmailTemplateOk returns a tuple with the PostmarkEmailTemplate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostmarkEmailTemplate

`func (o *ClusterConfigCoordinatorConfig) SetPostmarkEmailTemplate(v string)`

SetPostmarkEmailTemplate sets PostmarkEmailTemplate field to given value.

### HasPostmarkEmailTemplate

`func (o *ClusterConfigCoordinatorConfig) HasPostmarkEmailTemplate() bool`

HasPostmarkEmailTemplate returns a boolean if a field has been set.

### GetS3

`func (o *ClusterConfigCoordinatorConfig) GetS3() map[string]string`

GetS3 returns the S3 field if non-nil, zero value otherwise.

### GetS3Ok

`func (o *ClusterConfigCoordinatorConfig) GetS3Ok() (*map[string]string, bool)`

GetS3Ok returns a tuple with the S3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetS3

`func (o *ClusterConfigCoordinatorConfig) SetS3(v map[string]string)`

SetS3 sets S3 field to given value.

### HasS3

`func (o *ClusterConfigCoordinatorConfig) HasS3() bool`

HasS3 returns a boolean if a field has been set.

### GetOfacApiKey

`func (o *ClusterConfigCoordinatorConfig) GetOfacApiKey() string`

GetOfacApiKey returns the OfacApiKey field if non-nil, zero value otherwise.

### GetOfacApiKeyOk

`func (o *ClusterConfigCoordinatorConfig) GetOfacApiKeyOk() (*string, bool)`

GetOfacApiKeyOk returns a tuple with the OfacApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOfacApiKey

`func (o *ClusterConfigCoordinatorConfig) SetOfacApiKey(v string)`

SetOfacApiKey sets OfacApiKey field to given value.

### HasOfacApiKey

`func (o *ClusterConfigCoordinatorConfig) HasOfacApiKey() bool`

HasOfacApiKey returns a boolean if a field has been set.

### GetUsbMediaQueueDir

`func (o *ClusterConfigCoordinatorConfig) GetUsbMediaQueueDir() string`

GetUsbMediaQueueDir returns the UsbMediaQueueDir field if non-nil, zero value otherwise.

### GetUsbMediaQueueDirOk

`func (o *ClusterConfigCoordinatorConfig) GetUsbMediaQueueDirOk() (*string, bool)`

GetUsbMediaQueueDirOk returns a tuple with the UsbMediaQueueDir field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsbMediaQueueDir

`func (o *ClusterConfigCoordinatorConfig) SetUsbMediaQueueDir(v string)`

SetUsbMediaQueueDir sets UsbMediaQueueDir field to given value.

### HasUsbMediaQueueDir

`func (o *ClusterConfigCoordinatorConfig) HasUsbMediaQueueDir() bool`

HasUsbMediaQueueDir returns a boolean if a field has been set.

### GetUsbMediaAccessEnabled

`func (o *ClusterConfigCoordinatorConfig) GetUsbMediaAccessEnabled() bool`

GetUsbMediaAccessEnabled returns the UsbMediaAccessEnabled field if non-nil, zero value otherwise.

### GetUsbMediaAccessEnabledOk

`func (o *ClusterConfigCoordinatorConfig) GetUsbMediaAccessEnabledOk() (*bool, bool)`

GetUsbMediaAccessEnabledOk returns a tuple with the UsbMediaAccessEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsbMediaAccessEnabled

`func (o *ClusterConfigCoordinatorConfig) SetUsbMediaAccessEnabled(v bool)`

SetUsbMediaAccessEnabled sets UsbMediaAccessEnabled field to given value.

### HasUsbMediaAccessEnabled

`func (o *ClusterConfigCoordinatorConfig) HasUsbMediaAccessEnabled() bool`

HasUsbMediaAccessEnabled returns a boolean if a field has been set.

### GetIntercomIdVerifySecret

`func (o *ClusterConfigCoordinatorConfig) GetIntercomIdVerifySecret() string`

GetIntercomIdVerifySecret returns the IntercomIdVerifySecret field if non-nil, zero value otherwise.

### GetIntercomIdVerifySecretOk

`func (o *ClusterConfigCoordinatorConfig) GetIntercomIdVerifySecretOk() (*string, bool)`

GetIntercomIdVerifySecretOk returns a tuple with the IntercomIdVerifySecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntercomIdVerifySecret

`func (o *ClusterConfigCoordinatorConfig) SetIntercomIdVerifySecret(v string)`

SetIntercomIdVerifySecret sets IntercomIdVerifySecret field to given value.

### HasIntercomIdVerifySecret

`func (o *ClusterConfigCoordinatorConfig) HasIntercomIdVerifySecret() bool`

HasIntercomIdVerifySecret returns a boolean if a field has been set.

### GetFvpSecret

`func (o *ClusterConfigCoordinatorConfig) GetFvpSecret() string`

GetFvpSecret returns the FvpSecret field if non-nil, zero value otherwise.

### GetFvpSecretOk

`func (o *ClusterConfigCoordinatorConfig) GetFvpSecretOk() (*string, bool)`

GetFvpSecretOk returns a tuple with the FvpSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFvpSecret

`func (o *ClusterConfigCoordinatorConfig) SetFvpSecret(v string)`

SetFvpSecret sets FvpSecret field to given value.

### HasFvpSecret

`func (o *ClusterConfigCoordinatorConfig) HasFvpSecret() bool`

HasFvpSecret returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


