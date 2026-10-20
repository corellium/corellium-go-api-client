# ClusterConfigSetupConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OnSite** | **bool** |  | 
**ArtifactsVolumeSize** | Pointer to **float32** |  | [optional] 
**NetworkMonitorInterval** | **float32** |  | 
**MaxNetworkMonitorFileSize** | **string** |  | 
**CaCertFileSrc** | **string** |  | 
**LocalIp** | **string** |  | 
**InstanceIpBlockNetmask** | **string** |  | 
**InstanceGateway** | **string** |  | 
**InstanceDNSServers** | Pointer to **[]string** |  | [optional] 
**ReportInterval** | **float32** |  | 
**CertKeyFileData** | Pointer to **string** |  | [optional] 
**DefaultSsid** | Pointer to **string** |  | [optional] 
**EnableExperimentalDevices** | Pointer to **bool** |  | [optional] 
**ControllerNodes** | Pointer to **[]string** |  | [optional] 
**Domain** | Pointer to **string** |  | [optional] 
**Interface** | **string** |  | 
**VirtualDeviceInterface** | Pointer to **string** |  | [optional] 
**AutoApproveTrials** | Pointer to **string** |  | [optional] 
**SnapshotLimit** | Pointer to **float32** |  | [optional] 
**MaxDownloadAgentsPerDevice** | Pointer to **float32** |  | [optional] 
**ClientCertFile** | Pointer to **string** |  | [optional] 
**DockerHostIp** | Pointer to **string** |  | [optional] 
**DomainName** | Pointer to **string** |  | [optional] 
**VpnClientIP** | Pointer to **string** |  | [optional] 

## Methods

### NewClusterConfigSetupConfig

`func NewClusterConfigSetupConfig(onSite bool, networkMonitorInterval float32, maxNetworkMonitorFileSize string, caCertFileSrc string, localIp string, instanceIpBlockNetmask string, instanceGateway string, reportInterval float32, interface_ string, ) *ClusterConfigSetupConfig`

NewClusterConfigSetupConfig instantiates a new ClusterConfigSetupConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClusterConfigSetupConfigWithDefaults

`func NewClusterConfigSetupConfigWithDefaults() *ClusterConfigSetupConfig`

NewClusterConfigSetupConfigWithDefaults instantiates a new ClusterConfigSetupConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOnSite

`func (o *ClusterConfigSetupConfig) GetOnSite() bool`

GetOnSite returns the OnSite field if non-nil, zero value otherwise.

### GetOnSiteOk

`func (o *ClusterConfigSetupConfig) GetOnSiteOk() (*bool, bool)`

GetOnSiteOk returns a tuple with the OnSite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnSite

`func (o *ClusterConfigSetupConfig) SetOnSite(v bool)`

SetOnSite sets OnSite field to given value.


### GetArtifactsVolumeSize

`func (o *ClusterConfigSetupConfig) GetArtifactsVolumeSize() float32`

GetArtifactsVolumeSize returns the ArtifactsVolumeSize field if non-nil, zero value otherwise.

### GetArtifactsVolumeSizeOk

`func (o *ClusterConfigSetupConfig) GetArtifactsVolumeSizeOk() (*float32, bool)`

GetArtifactsVolumeSizeOk returns a tuple with the ArtifactsVolumeSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactsVolumeSize

`func (o *ClusterConfigSetupConfig) SetArtifactsVolumeSize(v float32)`

SetArtifactsVolumeSize sets ArtifactsVolumeSize field to given value.

### HasArtifactsVolumeSize

`func (o *ClusterConfigSetupConfig) HasArtifactsVolumeSize() bool`

HasArtifactsVolumeSize returns a boolean if a field has been set.

### GetNetworkMonitorInterval

`func (o *ClusterConfigSetupConfig) GetNetworkMonitorInterval() float32`

GetNetworkMonitorInterval returns the NetworkMonitorInterval field if non-nil, zero value otherwise.

### GetNetworkMonitorIntervalOk

`func (o *ClusterConfigSetupConfig) GetNetworkMonitorIntervalOk() (*float32, bool)`

GetNetworkMonitorIntervalOk returns a tuple with the NetworkMonitorInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkMonitorInterval

`func (o *ClusterConfigSetupConfig) SetNetworkMonitorInterval(v float32)`

SetNetworkMonitorInterval sets NetworkMonitorInterval field to given value.


### GetMaxNetworkMonitorFileSize

`func (o *ClusterConfigSetupConfig) GetMaxNetworkMonitorFileSize() string`

GetMaxNetworkMonitorFileSize returns the MaxNetworkMonitorFileSize field if non-nil, zero value otherwise.

### GetMaxNetworkMonitorFileSizeOk

`func (o *ClusterConfigSetupConfig) GetMaxNetworkMonitorFileSizeOk() (*string, bool)`

GetMaxNetworkMonitorFileSizeOk returns a tuple with the MaxNetworkMonitorFileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNetworkMonitorFileSize

`func (o *ClusterConfigSetupConfig) SetMaxNetworkMonitorFileSize(v string)`

SetMaxNetworkMonitorFileSize sets MaxNetworkMonitorFileSize field to given value.


### GetCaCertFileSrc

`func (o *ClusterConfigSetupConfig) GetCaCertFileSrc() string`

GetCaCertFileSrc returns the CaCertFileSrc field if non-nil, zero value otherwise.

### GetCaCertFileSrcOk

`func (o *ClusterConfigSetupConfig) GetCaCertFileSrcOk() (*string, bool)`

GetCaCertFileSrcOk returns a tuple with the CaCertFileSrc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaCertFileSrc

`func (o *ClusterConfigSetupConfig) SetCaCertFileSrc(v string)`

SetCaCertFileSrc sets CaCertFileSrc field to given value.


### GetLocalIp

`func (o *ClusterConfigSetupConfig) GetLocalIp() string`

GetLocalIp returns the LocalIp field if non-nil, zero value otherwise.

### GetLocalIpOk

`func (o *ClusterConfigSetupConfig) GetLocalIpOk() (*string, bool)`

GetLocalIpOk returns a tuple with the LocalIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalIp

`func (o *ClusterConfigSetupConfig) SetLocalIp(v string)`

SetLocalIp sets LocalIp field to given value.


### GetInstanceIpBlockNetmask

`func (o *ClusterConfigSetupConfig) GetInstanceIpBlockNetmask() string`

GetInstanceIpBlockNetmask returns the InstanceIpBlockNetmask field if non-nil, zero value otherwise.

### GetInstanceIpBlockNetmaskOk

`func (o *ClusterConfigSetupConfig) GetInstanceIpBlockNetmaskOk() (*string, bool)`

GetInstanceIpBlockNetmaskOk returns a tuple with the InstanceIpBlockNetmask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceIpBlockNetmask

`func (o *ClusterConfigSetupConfig) SetInstanceIpBlockNetmask(v string)`

SetInstanceIpBlockNetmask sets InstanceIpBlockNetmask field to given value.


### GetInstanceGateway

`func (o *ClusterConfigSetupConfig) GetInstanceGateway() string`

GetInstanceGateway returns the InstanceGateway field if non-nil, zero value otherwise.

### GetInstanceGatewayOk

`func (o *ClusterConfigSetupConfig) GetInstanceGatewayOk() (*string, bool)`

GetInstanceGatewayOk returns a tuple with the InstanceGateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceGateway

`func (o *ClusterConfigSetupConfig) SetInstanceGateway(v string)`

SetInstanceGateway sets InstanceGateway field to given value.


### GetInstanceDNSServers

`func (o *ClusterConfigSetupConfig) GetInstanceDNSServers() []string`

GetInstanceDNSServers returns the InstanceDNSServers field if non-nil, zero value otherwise.

### GetInstanceDNSServersOk

`func (o *ClusterConfigSetupConfig) GetInstanceDNSServersOk() (*[]string, bool)`

GetInstanceDNSServersOk returns a tuple with the InstanceDNSServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceDNSServers

`func (o *ClusterConfigSetupConfig) SetInstanceDNSServers(v []string)`

SetInstanceDNSServers sets InstanceDNSServers field to given value.

### HasInstanceDNSServers

`func (o *ClusterConfigSetupConfig) HasInstanceDNSServers() bool`

HasInstanceDNSServers returns a boolean if a field has been set.

### GetReportInterval

`func (o *ClusterConfigSetupConfig) GetReportInterval() float32`

GetReportInterval returns the ReportInterval field if non-nil, zero value otherwise.

### GetReportIntervalOk

`func (o *ClusterConfigSetupConfig) GetReportIntervalOk() (*float32, bool)`

GetReportIntervalOk returns a tuple with the ReportInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportInterval

`func (o *ClusterConfigSetupConfig) SetReportInterval(v float32)`

SetReportInterval sets ReportInterval field to given value.


### GetCertKeyFileData

`func (o *ClusterConfigSetupConfig) GetCertKeyFileData() string`

GetCertKeyFileData returns the CertKeyFileData field if non-nil, zero value otherwise.

### GetCertKeyFileDataOk

`func (o *ClusterConfigSetupConfig) GetCertKeyFileDataOk() (*string, bool)`

GetCertKeyFileDataOk returns a tuple with the CertKeyFileData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertKeyFileData

`func (o *ClusterConfigSetupConfig) SetCertKeyFileData(v string)`

SetCertKeyFileData sets CertKeyFileData field to given value.

### HasCertKeyFileData

`func (o *ClusterConfigSetupConfig) HasCertKeyFileData() bool`

HasCertKeyFileData returns a boolean if a field has been set.

### GetDefaultSsid

`func (o *ClusterConfigSetupConfig) GetDefaultSsid() string`

GetDefaultSsid returns the DefaultSsid field if non-nil, zero value otherwise.

### GetDefaultSsidOk

`func (o *ClusterConfigSetupConfig) GetDefaultSsidOk() (*string, bool)`

GetDefaultSsidOk returns a tuple with the DefaultSsid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultSsid

`func (o *ClusterConfigSetupConfig) SetDefaultSsid(v string)`

SetDefaultSsid sets DefaultSsid field to given value.

### HasDefaultSsid

`func (o *ClusterConfigSetupConfig) HasDefaultSsid() bool`

HasDefaultSsid returns a boolean if a field has been set.

### GetEnableExperimentalDevices

`func (o *ClusterConfigSetupConfig) GetEnableExperimentalDevices() bool`

GetEnableExperimentalDevices returns the EnableExperimentalDevices field if non-nil, zero value otherwise.

### GetEnableExperimentalDevicesOk

`func (o *ClusterConfigSetupConfig) GetEnableExperimentalDevicesOk() (*bool, bool)`

GetEnableExperimentalDevicesOk returns a tuple with the EnableExperimentalDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableExperimentalDevices

`func (o *ClusterConfigSetupConfig) SetEnableExperimentalDevices(v bool)`

SetEnableExperimentalDevices sets EnableExperimentalDevices field to given value.

### HasEnableExperimentalDevices

`func (o *ClusterConfigSetupConfig) HasEnableExperimentalDevices() bool`

HasEnableExperimentalDevices returns a boolean if a field has been set.

### GetControllerNodes

`func (o *ClusterConfigSetupConfig) GetControllerNodes() []string`

GetControllerNodes returns the ControllerNodes field if non-nil, zero value otherwise.

### GetControllerNodesOk

`func (o *ClusterConfigSetupConfig) GetControllerNodesOk() (*[]string, bool)`

GetControllerNodesOk returns a tuple with the ControllerNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllerNodes

`func (o *ClusterConfigSetupConfig) SetControllerNodes(v []string)`

SetControllerNodes sets ControllerNodes field to given value.

### HasControllerNodes

`func (o *ClusterConfigSetupConfig) HasControllerNodes() bool`

HasControllerNodes returns a boolean if a field has been set.

### GetDomain

`func (o *ClusterConfigSetupConfig) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ClusterConfigSetupConfig) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ClusterConfigSetupConfig) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *ClusterConfigSetupConfig) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetInterface

`func (o *ClusterConfigSetupConfig) GetInterface() string`

GetInterface returns the Interface field if non-nil, zero value otherwise.

### GetInterfaceOk

`func (o *ClusterConfigSetupConfig) GetInterfaceOk() (*string, bool)`

GetInterfaceOk returns a tuple with the Interface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterface

`func (o *ClusterConfigSetupConfig) SetInterface(v string)`

SetInterface sets Interface field to given value.


### GetVirtualDeviceInterface

`func (o *ClusterConfigSetupConfig) GetVirtualDeviceInterface() string`

GetVirtualDeviceInterface returns the VirtualDeviceInterface field if non-nil, zero value otherwise.

### GetVirtualDeviceInterfaceOk

`func (o *ClusterConfigSetupConfig) GetVirtualDeviceInterfaceOk() (*string, bool)`

GetVirtualDeviceInterfaceOk returns a tuple with the VirtualDeviceInterface field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVirtualDeviceInterface

`func (o *ClusterConfigSetupConfig) SetVirtualDeviceInterface(v string)`

SetVirtualDeviceInterface sets VirtualDeviceInterface field to given value.

### HasVirtualDeviceInterface

`func (o *ClusterConfigSetupConfig) HasVirtualDeviceInterface() bool`

HasVirtualDeviceInterface returns a boolean if a field has been set.

### GetAutoApproveTrials

`func (o *ClusterConfigSetupConfig) GetAutoApproveTrials() string`

GetAutoApproveTrials returns the AutoApproveTrials field if non-nil, zero value otherwise.

### GetAutoApproveTrialsOk

`func (o *ClusterConfigSetupConfig) GetAutoApproveTrialsOk() (*string, bool)`

GetAutoApproveTrialsOk returns a tuple with the AutoApproveTrials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoApproveTrials

`func (o *ClusterConfigSetupConfig) SetAutoApproveTrials(v string)`

SetAutoApproveTrials sets AutoApproveTrials field to given value.

### HasAutoApproveTrials

`func (o *ClusterConfigSetupConfig) HasAutoApproveTrials() bool`

HasAutoApproveTrials returns a boolean if a field has been set.

### GetSnapshotLimit

`func (o *ClusterConfigSetupConfig) GetSnapshotLimit() float32`

GetSnapshotLimit returns the SnapshotLimit field if non-nil, zero value otherwise.

### GetSnapshotLimitOk

`func (o *ClusterConfigSetupConfig) GetSnapshotLimitOk() (*float32, bool)`

GetSnapshotLimitOk returns a tuple with the SnapshotLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotLimit

`func (o *ClusterConfigSetupConfig) SetSnapshotLimit(v float32)`

SetSnapshotLimit sets SnapshotLimit field to given value.

### HasSnapshotLimit

`func (o *ClusterConfigSetupConfig) HasSnapshotLimit() bool`

HasSnapshotLimit returns a boolean if a field has been set.

### GetMaxDownloadAgentsPerDevice

`func (o *ClusterConfigSetupConfig) GetMaxDownloadAgentsPerDevice() float32`

GetMaxDownloadAgentsPerDevice returns the MaxDownloadAgentsPerDevice field if non-nil, zero value otherwise.

### GetMaxDownloadAgentsPerDeviceOk

`func (o *ClusterConfigSetupConfig) GetMaxDownloadAgentsPerDeviceOk() (*float32, bool)`

GetMaxDownloadAgentsPerDeviceOk returns a tuple with the MaxDownloadAgentsPerDevice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDownloadAgentsPerDevice

`func (o *ClusterConfigSetupConfig) SetMaxDownloadAgentsPerDevice(v float32)`

SetMaxDownloadAgentsPerDevice sets MaxDownloadAgentsPerDevice field to given value.

### HasMaxDownloadAgentsPerDevice

`func (o *ClusterConfigSetupConfig) HasMaxDownloadAgentsPerDevice() bool`

HasMaxDownloadAgentsPerDevice returns a boolean if a field has been set.

### GetClientCertFile

`func (o *ClusterConfigSetupConfig) GetClientCertFile() string`

GetClientCertFile returns the ClientCertFile field if non-nil, zero value otherwise.

### GetClientCertFileOk

`func (o *ClusterConfigSetupConfig) GetClientCertFileOk() (*string, bool)`

GetClientCertFileOk returns a tuple with the ClientCertFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientCertFile

`func (o *ClusterConfigSetupConfig) SetClientCertFile(v string)`

SetClientCertFile sets ClientCertFile field to given value.

### HasClientCertFile

`func (o *ClusterConfigSetupConfig) HasClientCertFile() bool`

HasClientCertFile returns a boolean if a field has been set.

### GetDockerHostIp

`func (o *ClusterConfigSetupConfig) GetDockerHostIp() string`

GetDockerHostIp returns the DockerHostIp field if non-nil, zero value otherwise.

### GetDockerHostIpOk

`func (o *ClusterConfigSetupConfig) GetDockerHostIpOk() (*string, bool)`

GetDockerHostIpOk returns a tuple with the DockerHostIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDockerHostIp

`func (o *ClusterConfigSetupConfig) SetDockerHostIp(v string)`

SetDockerHostIp sets DockerHostIp field to given value.

### HasDockerHostIp

`func (o *ClusterConfigSetupConfig) HasDockerHostIp() bool`

HasDockerHostIp returns a boolean if a field has been set.

### GetDomainName

`func (o *ClusterConfigSetupConfig) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *ClusterConfigSetupConfig) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *ClusterConfigSetupConfig) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *ClusterConfigSetupConfig) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### GetVpnClientIP

`func (o *ClusterConfigSetupConfig) GetVpnClientIP() string`

GetVpnClientIP returns the VpnClientIP field if non-nil, zero value otherwise.

### GetVpnClientIPOk

`func (o *ClusterConfigSetupConfig) GetVpnClientIPOk() (*string, bool)`

GetVpnClientIPOk returns a tuple with the VpnClientIP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVpnClientIP

`func (o *ClusterConfigSetupConfig) SetVpnClientIP(v string)`

SetVpnClientIP sets VpnClientIP field to given value.

### HasVpnClientIP

`func (o *ClusterConfigSetupConfig) HasVpnClientIP() bool`

HasVpnClientIP returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


