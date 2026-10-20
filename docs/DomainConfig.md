# DomainConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Android** | Pointer to **bool** | Whether Android devices are enabled. | [optional] 
**Billing** | Pointer to **bool** | Whether billing is enabled. | [optional] 
**LicenseType** | Pointer to **string** | License type identifier. | [optional] 
**SignupEmail** | Pointer to **string** | Email used for domain signup. | [optional] 
**Trial** | Pointer to [**NullableDomainConfigTrial**](DomainConfigTrial.md) |  | [optional] 
**UsageBased** | Pointer to **bool** | Whether usage-based billing is enabled. | [optional] 
**EnableNetgearDevices** | Pointer to **bool** | Whether Netgear devices are enabled. | [optional] 
**NoIos** | Pointer to **bool** | Whether iOS devices are disabled. | [optional] 
**EnableAmazonDevices** | Pointer to **bool** | Whether Amazon devices are enabled. | [optional] 
**DeviceDhcpServer** | Pointer to **bool** | Whether device DHCP server is enabled. | [optional] 
**EnableArmDevices** | Pointer to **bool** | Whether ARM devices are enabled. | [optional] 
**EnableDevices** | Pointer to **bool** | Whether devices are enabled. | [optional] 
**Webplayer** | Pointer to [**DomainConfigWebplayer**](DomainConfigWebplayer.md) |  | [optional] 
**SnapshotSharingPermissions** | Pointer to [**DomainConfigSnapshotSharingPermissions**](DomainConfigSnapshotSharingPermissions.md) |  | [optional] 

## Methods

### NewDomainConfig

`func NewDomainConfig() *DomainConfig`

NewDomainConfig instantiates a new DomainConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainConfigWithDefaults

`func NewDomainConfigWithDefaults() *DomainConfig`

NewDomainConfigWithDefaults instantiates a new DomainConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAndroid

`func (o *DomainConfig) GetAndroid() bool`

GetAndroid returns the Android field if non-nil, zero value otherwise.

### GetAndroidOk

`func (o *DomainConfig) GetAndroidOk() (*bool, bool)`

GetAndroidOk returns a tuple with the Android field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroid

`func (o *DomainConfig) SetAndroid(v bool)`

SetAndroid sets Android field to given value.

### HasAndroid

`func (o *DomainConfig) HasAndroid() bool`

HasAndroid returns a boolean if a field has been set.

### GetBilling

`func (o *DomainConfig) GetBilling() bool`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *DomainConfig) GetBillingOk() (*bool, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *DomainConfig) SetBilling(v bool)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *DomainConfig) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetLicenseType

`func (o *DomainConfig) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *DomainConfig) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *DomainConfig) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.

### HasLicenseType

`func (o *DomainConfig) HasLicenseType() bool`

HasLicenseType returns a boolean if a field has been set.

### GetSignupEmail

`func (o *DomainConfig) GetSignupEmail() string`

GetSignupEmail returns the SignupEmail field if non-nil, zero value otherwise.

### GetSignupEmailOk

`func (o *DomainConfig) GetSignupEmailOk() (*string, bool)`

GetSignupEmailOk returns a tuple with the SignupEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignupEmail

`func (o *DomainConfig) SetSignupEmail(v string)`

SetSignupEmail sets SignupEmail field to given value.

### HasSignupEmail

`func (o *DomainConfig) HasSignupEmail() bool`

HasSignupEmail returns a boolean if a field has been set.

### GetTrial

`func (o *DomainConfig) GetTrial() DomainConfigTrial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *DomainConfig) GetTrialOk() (*DomainConfigTrial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *DomainConfig) SetTrial(v DomainConfigTrial)`

SetTrial sets Trial field to given value.

### HasTrial

`func (o *DomainConfig) HasTrial() bool`

HasTrial returns a boolean if a field has been set.

### SetTrialNil

`func (o *DomainConfig) SetTrialNil(b bool)`

 SetTrialNil sets the value for Trial to be an explicit nil

### UnsetTrial
`func (o *DomainConfig) UnsetTrial()`

UnsetTrial ensures that no value is present for Trial, not even an explicit nil
### GetUsageBased

`func (o *DomainConfig) GetUsageBased() bool`

GetUsageBased returns the UsageBased field if non-nil, zero value otherwise.

### GetUsageBasedOk

`func (o *DomainConfig) GetUsageBasedOk() (*bool, bool)`

GetUsageBasedOk returns a tuple with the UsageBased field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageBased

`func (o *DomainConfig) SetUsageBased(v bool)`

SetUsageBased sets UsageBased field to given value.

### HasUsageBased

`func (o *DomainConfig) HasUsageBased() bool`

HasUsageBased returns a boolean if a field has been set.

### GetEnableNetgearDevices

`func (o *DomainConfig) GetEnableNetgearDevices() bool`

GetEnableNetgearDevices returns the EnableNetgearDevices field if non-nil, zero value otherwise.

### GetEnableNetgearDevicesOk

`func (o *DomainConfig) GetEnableNetgearDevicesOk() (*bool, bool)`

GetEnableNetgearDevicesOk returns a tuple with the EnableNetgearDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableNetgearDevices

`func (o *DomainConfig) SetEnableNetgearDevices(v bool)`

SetEnableNetgearDevices sets EnableNetgearDevices field to given value.

### HasEnableNetgearDevices

`func (o *DomainConfig) HasEnableNetgearDevices() bool`

HasEnableNetgearDevices returns a boolean if a field has been set.

### GetNoIos

`func (o *DomainConfig) GetNoIos() bool`

GetNoIos returns the NoIos field if non-nil, zero value otherwise.

### GetNoIosOk

`func (o *DomainConfig) GetNoIosOk() (*bool, bool)`

GetNoIosOk returns a tuple with the NoIos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoIos

`func (o *DomainConfig) SetNoIos(v bool)`

SetNoIos sets NoIos field to given value.

### HasNoIos

`func (o *DomainConfig) HasNoIos() bool`

HasNoIos returns a boolean if a field has been set.

### GetEnableAmazonDevices

`func (o *DomainConfig) GetEnableAmazonDevices() bool`

GetEnableAmazonDevices returns the EnableAmazonDevices field if non-nil, zero value otherwise.

### GetEnableAmazonDevicesOk

`func (o *DomainConfig) GetEnableAmazonDevicesOk() (*bool, bool)`

GetEnableAmazonDevicesOk returns a tuple with the EnableAmazonDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAmazonDevices

`func (o *DomainConfig) SetEnableAmazonDevices(v bool)`

SetEnableAmazonDevices sets EnableAmazonDevices field to given value.

### HasEnableAmazonDevices

`func (o *DomainConfig) HasEnableAmazonDevices() bool`

HasEnableAmazonDevices returns a boolean if a field has been set.

### GetDeviceDhcpServer

`func (o *DomainConfig) GetDeviceDhcpServer() bool`

GetDeviceDhcpServer returns the DeviceDhcpServer field if non-nil, zero value otherwise.

### GetDeviceDhcpServerOk

`func (o *DomainConfig) GetDeviceDhcpServerOk() (*bool, bool)`

GetDeviceDhcpServerOk returns a tuple with the DeviceDhcpServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceDhcpServer

`func (o *DomainConfig) SetDeviceDhcpServer(v bool)`

SetDeviceDhcpServer sets DeviceDhcpServer field to given value.

### HasDeviceDhcpServer

`func (o *DomainConfig) HasDeviceDhcpServer() bool`

HasDeviceDhcpServer returns a boolean if a field has been set.

### GetEnableArmDevices

`func (o *DomainConfig) GetEnableArmDevices() bool`

GetEnableArmDevices returns the EnableArmDevices field if non-nil, zero value otherwise.

### GetEnableArmDevicesOk

`func (o *DomainConfig) GetEnableArmDevicesOk() (*bool, bool)`

GetEnableArmDevicesOk returns a tuple with the EnableArmDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableArmDevices

`func (o *DomainConfig) SetEnableArmDevices(v bool)`

SetEnableArmDevices sets EnableArmDevices field to given value.

### HasEnableArmDevices

`func (o *DomainConfig) HasEnableArmDevices() bool`

HasEnableArmDevices returns a boolean if a field has been set.

### GetEnableDevices

`func (o *DomainConfig) GetEnableDevices() bool`

GetEnableDevices returns the EnableDevices field if non-nil, zero value otherwise.

### GetEnableDevicesOk

`func (o *DomainConfig) GetEnableDevicesOk() (*bool, bool)`

GetEnableDevicesOk returns a tuple with the EnableDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableDevices

`func (o *DomainConfig) SetEnableDevices(v bool)`

SetEnableDevices sets EnableDevices field to given value.

### HasEnableDevices

`func (o *DomainConfig) HasEnableDevices() bool`

HasEnableDevices returns a boolean if a field has been set.

### GetWebplayer

`func (o *DomainConfig) GetWebplayer() DomainConfigWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *DomainConfig) GetWebplayerOk() (*DomainConfigWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *DomainConfig) SetWebplayer(v DomainConfigWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *DomainConfig) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetSnapshotSharingPermissions

`func (o *DomainConfig) GetSnapshotSharingPermissions() DomainConfigSnapshotSharingPermissions`

GetSnapshotSharingPermissions returns the SnapshotSharingPermissions field if non-nil, zero value otherwise.

### GetSnapshotSharingPermissionsOk

`func (o *DomainConfig) GetSnapshotSharingPermissionsOk() (*DomainConfigSnapshotSharingPermissions, bool)`

GetSnapshotSharingPermissionsOk returns a tuple with the SnapshotSharingPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotSharingPermissions

`func (o *DomainConfig) SetSnapshotSharingPermissions(v DomainConfigSnapshotSharingPermissions)`

SetSnapshotSharingPermissions sets SnapshotSharingPermissions field to given value.

### HasSnapshotSharingPermissions

`func (o *DomainConfig) HasSnapshotSharingPermissions() bool`

HasSnapshotSharingPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


