# DomainConfigInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Android** | Pointer to **bool** | Whether Android devices are enabled. | [optional] 
**Billing** | Pointer to **bool** | Whether billing is enabled. | [optional] 
**OrganizationName** | Pointer to **string** | Organization name. | [optional] 
**LicenseType** | Pointer to **string** | License type identifier. | [optional] 
**SignupEmail** | Pointer to **string** | Email used for domain signup. | [optional] 
**CouponCode** | Pointer to **string** | Coupon code. | [optional] 
**Trial** | Pointer to [**NullableDomainConfigInputTrial**](DomainConfigInputTrial.md) |  | [optional] 
**NoIos** | Pointer to **bool** | Whether iOS devices are disabled. | [optional] 
**DeviceDhcpServer** | Pointer to **bool** | Whether the device DHCP server is enabled. | [optional] 
**Files** | Pointer to **bool** | Whether the files feature is enabled. | [optional] 
**FilesOnly** | Pointer to **bool** | Whether the domain is in files-only mode. | [optional] 
**RemoteGpu** | Pointer to **bool** | Whether remote GPU nodes are used. | [optional] 
**PrioritizedNodes** | Pointer to **[]string** | Node addresses (host:port) to prefer when placing devices. | [optional] 
**EnableNetgearDevices** | Pointer to **bool** | Whether Netgear devices are enabled. | [optional] 
**EnableAmazonDevices** | Pointer to **bool** | Whether Amazon devices are enabled. | [optional] 
**EnableArmDevices** | Pointer to **bool** | Whether ARM devices are enabled. | [optional] 
**EnableDevices** | Pointer to **bool** | Whether devices are enabled. | [optional] 
**Webplayer** | Pointer to [**DomainConfigInputWebplayer**](DomainConfigInputWebplayer.md) |  | [optional] 
**SnapshotSharingPermissions** | Pointer to [**DomainConfigInputSnapshotSharingPermissions**](DomainConfigInputSnapshotSharingPermissions.md) |  | [optional] 

## Methods

### NewDomainConfigInput

`func NewDomainConfigInput() *DomainConfigInput`

NewDomainConfigInput instantiates a new DomainConfigInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainConfigInputWithDefaults

`func NewDomainConfigInputWithDefaults() *DomainConfigInput`

NewDomainConfigInputWithDefaults instantiates a new DomainConfigInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAndroid

`func (o *DomainConfigInput) GetAndroid() bool`

GetAndroid returns the Android field if non-nil, zero value otherwise.

### GetAndroidOk

`func (o *DomainConfigInput) GetAndroidOk() (*bool, bool)`

GetAndroidOk returns a tuple with the Android field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroid

`func (o *DomainConfigInput) SetAndroid(v bool)`

SetAndroid sets Android field to given value.

### HasAndroid

`func (o *DomainConfigInput) HasAndroid() bool`

HasAndroid returns a boolean if a field has been set.

### GetBilling

`func (o *DomainConfigInput) GetBilling() bool`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *DomainConfigInput) GetBillingOk() (*bool, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *DomainConfigInput) SetBilling(v bool)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *DomainConfigInput) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetOrganizationName

`func (o *DomainConfigInput) GetOrganizationName() string`

GetOrganizationName returns the OrganizationName field if non-nil, zero value otherwise.

### GetOrganizationNameOk

`func (o *DomainConfigInput) GetOrganizationNameOk() (*string, bool)`

GetOrganizationNameOk returns a tuple with the OrganizationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationName

`func (o *DomainConfigInput) SetOrganizationName(v string)`

SetOrganizationName sets OrganizationName field to given value.

### HasOrganizationName

`func (o *DomainConfigInput) HasOrganizationName() bool`

HasOrganizationName returns a boolean if a field has been set.

### GetLicenseType

`func (o *DomainConfigInput) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *DomainConfigInput) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *DomainConfigInput) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.

### HasLicenseType

`func (o *DomainConfigInput) HasLicenseType() bool`

HasLicenseType returns a boolean if a field has been set.

### GetSignupEmail

`func (o *DomainConfigInput) GetSignupEmail() string`

GetSignupEmail returns the SignupEmail field if non-nil, zero value otherwise.

### GetSignupEmailOk

`func (o *DomainConfigInput) GetSignupEmailOk() (*string, bool)`

GetSignupEmailOk returns a tuple with the SignupEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignupEmail

`func (o *DomainConfigInput) SetSignupEmail(v string)`

SetSignupEmail sets SignupEmail field to given value.

### HasSignupEmail

`func (o *DomainConfigInput) HasSignupEmail() bool`

HasSignupEmail returns a boolean if a field has been set.

### GetCouponCode

`func (o *DomainConfigInput) GetCouponCode() string`

GetCouponCode returns the CouponCode field if non-nil, zero value otherwise.

### GetCouponCodeOk

`func (o *DomainConfigInput) GetCouponCodeOk() (*string, bool)`

GetCouponCodeOk returns a tuple with the CouponCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCouponCode

`func (o *DomainConfigInput) SetCouponCode(v string)`

SetCouponCode sets CouponCode field to given value.

### HasCouponCode

`func (o *DomainConfigInput) HasCouponCode() bool`

HasCouponCode returns a boolean if a field has been set.

### GetTrial

`func (o *DomainConfigInput) GetTrial() DomainConfigInputTrial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *DomainConfigInput) GetTrialOk() (*DomainConfigInputTrial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *DomainConfigInput) SetTrial(v DomainConfigInputTrial)`

SetTrial sets Trial field to given value.

### HasTrial

`func (o *DomainConfigInput) HasTrial() bool`

HasTrial returns a boolean if a field has been set.

### SetTrialNil

`func (o *DomainConfigInput) SetTrialNil(b bool)`

 SetTrialNil sets the value for Trial to be an explicit nil

### UnsetTrial
`func (o *DomainConfigInput) UnsetTrial()`

UnsetTrial ensures that no value is present for Trial, not even an explicit nil
### GetNoIos

`func (o *DomainConfigInput) GetNoIos() bool`

GetNoIos returns the NoIos field if non-nil, zero value otherwise.

### GetNoIosOk

`func (o *DomainConfigInput) GetNoIosOk() (*bool, bool)`

GetNoIosOk returns a tuple with the NoIos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoIos

`func (o *DomainConfigInput) SetNoIos(v bool)`

SetNoIos sets NoIos field to given value.

### HasNoIos

`func (o *DomainConfigInput) HasNoIos() bool`

HasNoIos returns a boolean if a field has been set.

### GetDeviceDhcpServer

`func (o *DomainConfigInput) GetDeviceDhcpServer() bool`

GetDeviceDhcpServer returns the DeviceDhcpServer field if non-nil, zero value otherwise.

### GetDeviceDhcpServerOk

`func (o *DomainConfigInput) GetDeviceDhcpServerOk() (*bool, bool)`

GetDeviceDhcpServerOk returns a tuple with the DeviceDhcpServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceDhcpServer

`func (o *DomainConfigInput) SetDeviceDhcpServer(v bool)`

SetDeviceDhcpServer sets DeviceDhcpServer field to given value.

### HasDeviceDhcpServer

`func (o *DomainConfigInput) HasDeviceDhcpServer() bool`

HasDeviceDhcpServer returns a boolean if a field has been set.

### GetFiles

`func (o *DomainConfigInput) GetFiles() bool`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *DomainConfigInput) GetFilesOk() (*bool, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *DomainConfigInput) SetFiles(v bool)`

SetFiles sets Files field to given value.

### HasFiles

`func (o *DomainConfigInput) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### GetFilesOnly

`func (o *DomainConfigInput) GetFilesOnly() bool`

GetFilesOnly returns the FilesOnly field if non-nil, zero value otherwise.

### GetFilesOnlyOk

`func (o *DomainConfigInput) GetFilesOnlyOk() (*bool, bool)`

GetFilesOnlyOk returns a tuple with the FilesOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesOnly

`func (o *DomainConfigInput) SetFilesOnly(v bool)`

SetFilesOnly sets FilesOnly field to given value.

### HasFilesOnly

`func (o *DomainConfigInput) HasFilesOnly() bool`

HasFilesOnly returns a boolean if a field has been set.

### GetRemoteGpu

`func (o *DomainConfigInput) GetRemoteGpu() bool`

GetRemoteGpu returns the RemoteGpu field if non-nil, zero value otherwise.

### GetRemoteGpuOk

`func (o *DomainConfigInput) GetRemoteGpuOk() (*bool, bool)`

GetRemoteGpuOk returns a tuple with the RemoteGpu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteGpu

`func (o *DomainConfigInput) SetRemoteGpu(v bool)`

SetRemoteGpu sets RemoteGpu field to given value.

### HasRemoteGpu

`func (o *DomainConfigInput) HasRemoteGpu() bool`

HasRemoteGpu returns a boolean if a field has been set.

### GetPrioritizedNodes

`func (o *DomainConfigInput) GetPrioritizedNodes() []string`

GetPrioritizedNodes returns the PrioritizedNodes field if non-nil, zero value otherwise.

### GetPrioritizedNodesOk

`func (o *DomainConfigInput) GetPrioritizedNodesOk() (*[]string, bool)`

GetPrioritizedNodesOk returns a tuple with the PrioritizedNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrioritizedNodes

`func (o *DomainConfigInput) SetPrioritizedNodes(v []string)`

SetPrioritizedNodes sets PrioritizedNodes field to given value.

### HasPrioritizedNodes

`func (o *DomainConfigInput) HasPrioritizedNodes() bool`

HasPrioritizedNodes returns a boolean if a field has been set.

### GetEnableNetgearDevices

`func (o *DomainConfigInput) GetEnableNetgearDevices() bool`

GetEnableNetgearDevices returns the EnableNetgearDevices field if non-nil, zero value otherwise.

### GetEnableNetgearDevicesOk

`func (o *DomainConfigInput) GetEnableNetgearDevicesOk() (*bool, bool)`

GetEnableNetgearDevicesOk returns a tuple with the EnableNetgearDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableNetgearDevices

`func (o *DomainConfigInput) SetEnableNetgearDevices(v bool)`

SetEnableNetgearDevices sets EnableNetgearDevices field to given value.

### HasEnableNetgearDevices

`func (o *DomainConfigInput) HasEnableNetgearDevices() bool`

HasEnableNetgearDevices returns a boolean if a field has been set.

### GetEnableAmazonDevices

`func (o *DomainConfigInput) GetEnableAmazonDevices() bool`

GetEnableAmazonDevices returns the EnableAmazonDevices field if non-nil, zero value otherwise.

### GetEnableAmazonDevicesOk

`func (o *DomainConfigInput) GetEnableAmazonDevicesOk() (*bool, bool)`

GetEnableAmazonDevicesOk returns a tuple with the EnableAmazonDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableAmazonDevices

`func (o *DomainConfigInput) SetEnableAmazonDevices(v bool)`

SetEnableAmazonDevices sets EnableAmazonDevices field to given value.

### HasEnableAmazonDevices

`func (o *DomainConfigInput) HasEnableAmazonDevices() bool`

HasEnableAmazonDevices returns a boolean if a field has been set.

### GetEnableArmDevices

`func (o *DomainConfigInput) GetEnableArmDevices() bool`

GetEnableArmDevices returns the EnableArmDevices field if non-nil, zero value otherwise.

### GetEnableArmDevicesOk

`func (o *DomainConfigInput) GetEnableArmDevicesOk() (*bool, bool)`

GetEnableArmDevicesOk returns a tuple with the EnableArmDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableArmDevices

`func (o *DomainConfigInput) SetEnableArmDevices(v bool)`

SetEnableArmDevices sets EnableArmDevices field to given value.

### HasEnableArmDevices

`func (o *DomainConfigInput) HasEnableArmDevices() bool`

HasEnableArmDevices returns a boolean if a field has been set.

### GetEnableDevices

`func (o *DomainConfigInput) GetEnableDevices() bool`

GetEnableDevices returns the EnableDevices field if non-nil, zero value otherwise.

### GetEnableDevicesOk

`func (o *DomainConfigInput) GetEnableDevicesOk() (*bool, bool)`

GetEnableDevicesOk returns a tuple with the EnableDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableDevices

`func (o *DomainConfigInput) SetEnableDevices(v bool)`

SetEnableDevices sets EnableDevices field to given value.

### HasEnableDevices

`func (o *DomainConfigInput) HasEnableDevices() bool`

HasEnableDevices returns a boolean if a field has been set.

### GetWebplayer

`func (o *DomainConfigInput) GetWebplayer() DomainConfigInputWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *DomainConfigInput) GetWebplayerOk() (*DomainConfigInputWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *DomainConfigInput) SetWebplayer(v DomainConfigInputWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *DomainConfigInput) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetSnapshotSharingPermissions

`func (o *DomainConfigInput) GetSnapshotSharingPermissions() DomainConfigInputSnapshotSharingPermissions`

GetSnapshotSharingPermissions returns the SnapshotSharingPermissions field if non-nil, zero value otherwise.

### GetSnapshotSharingPermissionsOk

`func (o *DomainConfigInput) GetSnapshotSharingPermissionsOk() (*DomainConfigInputSnapshotSharingPermissions, bool)`

GetSnapshotSharingPermissionsOk returns a tuple with the SnapshotSharingPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotSharingPermissions

`func (o *DomainConfigInput) SetSnapshotSharingPermissions(v DomainConfigInputSnapshotSharingPermissions)`

SetSnapshotSharingPermissions sets SnapshotSharingPermissions field to given value.

### HasSnapshotSharingPermissions

`func (o *DomainConfigInput) HasSnapshotSharingPermissions() bool`

HasSnapshotSharingPermissions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


