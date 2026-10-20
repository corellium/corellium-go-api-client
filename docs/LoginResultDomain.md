# LoginResultDomain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **NullableString** | Domain name. | 
**Label** | **NullableString** | Domain description. | 
**TermsPolicy** | Pointer to **NullableString** | Terms-of-service policy for the domain. | [optional] 
**Cores** | **float32** | Licensed core quota. | 
**Individual** | **bool** | Whether this is an individual (aggregate member) domain. | 
**TotpRequired** | Pointer to **bool** | Present when the domain mandates TOTP. | [optional] 
**Subscription** | Pointer to **map[string]interface{}** | Billing summary for the domain, present when it has a billing record. Carries the billing wire fields renew_action, next_bill, billing_type and billing_backend. | [optional] 
**LicenseType** | Pointer to **string** | License type identifier. | [optional] 
**Android** | Pointer to **bool** | Whether Android devices are enabled. | [optional] 
**NoIOS** | Pointer to **bool** | Whether iOS devices are disabled. | [optional] 
**FilesOnly** | Pointer to **bool** | Whether the domain is in files-only mode. | [optional] 
**DeviceDHCPServer** | Pointer to **bool** | Whether the device DHCP server is enabled. | [optional] 
**EnableArmDevices** | Pointer to **bool** | Whether ARM devices are enabled. | [optional] 
**UseDeviceAccounting** | Pointer to **bool** | Whether the domain is billed by device hours instead of core hours. | [optional] 
**SingleProject** | Pointer to **bool** | Whether the domain is limited to a single project. | [optional] 
**TermsUpdated** | Pointer to **string** | When the domain terms were last updated; compared against the user agreement. | [optional] 
**Trial** | Pointer to [**NullableLoginResultDomainTrial**](LoginResultDomainTrial.md) |  | [optional] 
**Webplayer** | Pointer to [**LoginResultDomainWebplayer**](LoginResultDomainWebplayer.md) |  | [optional] 
**SnapshotSharingPermissions** | Pointer to [**LoginResultDomainSnapshotSharingPermissions**](LoginResultDomainSnapshotSharingPermissions.md) |  | [optional] 
**DeviceAutoShutdown** | Pointer to [**LoginResultDomainDeviceAutoShutdown**](LoginResultDomainDeviceAutoShutdown.md) |  | [optional] 
**Disabled** | Pointer to [**LoginResultDomainDisabled**](LoginResultDomainDisabled.md) |  | [optional] 

## Methods

### NewLoginResultDomain

`func NewLoginResultDomain(name NullableString, label NullableString, cores float32, individual bool, ) *LoginResultDomain`

NewLoginResultDomain instantiates a new LoginResultDomain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResultDomainWithDefaults

`func NewLoginResultDomainWithDefaults() *LoginResultDomain`

NewLoginResultDomainWithDefaults instantiates a new LoginResultDomain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *LoginResultDomain) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LoginResultDomain) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LoginResultDomain) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *LoginResultDomain) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *LoginResultDomain) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetLabel

`func (o *LoginResultDomain) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *LoginResultDomain) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *LoginResultDomain) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *LoginResultDomain) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *LoginResultDomain) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetTermsPolicy

`func (o *LoginResultDomain) GetTermsPolicy() string`

GetTermsPolicy returns the TermsPolicy field if non-nil, zero value otherwise.

### GetTermsPolicyOk

`func (o *LoginResultDomain) GetTermsPolicyOk() (*string, bool)`

GetTermsPolicyOk returns a tuple with the TermsPolicy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsPolicy

`func (o *LoginResultDomain) SetTermsPolicy(v string)`

SetTermsPolicy sets TermsPolicy field to given value.

### HasTermsPolicy

`func (o *LoginResultDomain) HasTermsPolicy() bool`

HasTermsPolicy returns a boolean if a field has been set.

### SetTermsPolicyNil

`func (o *LoginResultDomain) SetTermsPolicyNil(b bool)`

 SetTermsPolicyNil sets the value for TermsPolicy to be an explicit nil

### UnsetTermsPolicy
`func (o *LoginResultDomain) UnsetTermsPolicy()`

UnsetTermsPolicy ensures that no value is present for TermsPolicy, not even an explicit nil
### GetCores

`func (o *LoginResultDomain) GetCores() float32`

GetCores returns the Cores field if non-nil, zero value otherwise.

### GetCoresOk

`func (o *LoginResultDomain) GetCoresOk() (*float32, bool)`

GetCoresOk returns a tuple with the Cores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCores

`func (o *LoginResultDomain) SetCores(v float32)`

SetCores sets Cores field to given value.


### GetIndividual

`func (o *LoginResultDomain) GetIndividual() bool`

GetIndividual returns the Individual field if non-nil, zero value otherwise.

### GetIndividualOk

`func (o *LoginResultDomain) GetIndividualOk() (*bool, bool)`

GetIndividualOk returns a tuple with the Individual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndividual

`func (o *LoginResultDomain) SetIndividual(v bool)`

SetIndividual sets Individual field to given value.


### GetTotpRequired

`func (o *LoginResultDomain) GetTotpRequired() bool`

GetTotpRequired returns the TotpRequired field if non-nil, zero value otherwise.

### GetTotpRequiredOk

`func (o *LoginResultDomain) GetTotpRequiredOk() (*bool, bool)`

GetTotpRequiredOk returns a tuple with the TotpRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotpRequired

`func (o *LoginResultDomain) SetTotpRequired(v bool)`

SetTotpRequired sets TotpRequired field to given value.

### HasTotpRequired

`func (o *LoginResultDomain) HasTotpRequired() bool`

HasTotpRequired returns a boolean if a field has been set.

### GetSubscription

`func (o *LoginResultDomain) GetSubscription() map[string]interface{}`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *LoginResultDomain) GetSubscriptionOk() (*map[string]interface{}, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *LoginResultDomain) SetSubscription(v map[string]interface{})`

SetSubscription sets Subscription field to given value.

### HasSubscription

`func (o *LoginResultDomain) HasSubscription() bool`

HasSubscription returns a boolean if a field has been set.

### GetLicenseType

`func (o *LoginResultDomain) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *LoginResultDomain) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *LoginResultDomain) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.

### HasLicenseType

`func (o *LoginResultDomain) HasLicenseType() bool`

HasLicenseType returns a boolean if a field has been set.

### GetAndroid

`func (o *LoginResultDomain) GetAndroid() bool`

GetAndroid returns the Android field if non-nil, zero value otherwise.

### GetAndroidOk

`func (o *LoginResultDomain) GetAndroidOk() (*bool, bool)`

GetAndroidOk returns a tuple with the Android field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAndroid

`func (o *LoginResultDomain) SetAndroid(v bool)`

SetAndroid sets Android field to given value.

### HasAndroid

`func (o *LoginResultDomain) HasAndroid() bool`

HasAndroid returns a boolean if a field has been set.

### GetNoIOS

`func (o *LoginResultDomain) GetNoIOS() bool`

GetNoIOS returns the NoIOS field if non-nil, zero value otherwise.

### GetNoIOSOk

`func (o *LoginResultDomain) GetNoIOSOk() (*bool, bool)`

GetNoIOSOk returns a tuple with the NoIOS field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNoIOS

`func (o *LoginResultDomain) SetNoIOS(v bool)`

SetNoIOS sets NoIOS field to given value.

### HasNoIOS

`func (o *LoginResultDomain) HasNoIOS() bool`

HasNoIOS returns a boolean if a field has been set.

### GetFilesOnly

`func (o *LoginResultDomain) GetFilesOnly() bool`

GetFilesOnly returns the FilesOnly field if non-nil, zero value otherwise.

### GetFilesOnlyOk

`func (o *LoginResultDomain) GetFilesOnlyOk() (*bool, bool)`

GetFilesOnlyOk returns a tuple with the FilesOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesOnly

`func (o *LoginResultDomain) SetFilesOnly(v bool)`

SetFilesOnly sets FilesOnly field to given value.

### HasFilesOnly

`func (o *LoginResultDomain) HasFilesOnly() bool`

HasFilesOnly returns a boolean if a field has been set.

### GetDeviceDHCPServer

`func (o *LoginResultDomain) GetDeviceDHCPServer() bool`

GetDeviceDHCPServer returns the DeviceDHCPServer field if non-nil, zero value otherwise.

### GetDeviceDHCPServerOk

`func (o *LoginResultDomain) GetDeviceDHCPServerOk() (*bool, bool)`

GetDeviceDHCPServerOk returns a tuple with the DeviceDHCPServer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceDHCPServer

`func (o *LoginResultDomain) SetDeviceDHCPServer(v bool)`

SetDeviceDHCPServer sets DeviceDHCPServer field to given value.

### HasDeviceDHCPServer

`func (o *LoginResultDomain) HasDeviceDHCPServer() bool`

HasDeviceDHCPServer returns a boolean if a field has been set.

### GetEnableArmDevices

`func (o *LoginResultDomain) GetEnableArmDevices() bool`

GetEnableArmDevices returns the EnableArmDevices field if non-nil, zero value otherwise.

### GetEnableArmDevicesOk

`func (o *LoginResultDomain) GetEnableArmDevicesOk() (*bool, bool)`

GetEnableArmDevicesOk returns a tuple with the EnableArmDevices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableArmDevices

`func (o *LoginResultDomain) SetEnableArmDevices(v bool)`

SetEnableArmDevices sets EnableArmDevices field to given value.

### HasEnableArmDevices

`func (o *LoginResultDomain) HasEnableArmDevices() bool`

HasEnableArmDevices returns a boolean if a field has been set.

### GetUseDeviceAccounting

`func (o *LoginResultDomain) GetUseDeviceAccounting() bool`

GetUseDeviceAccounting returns the UseDeviceAccounting field if non-nil, zero value otherwise.

### GetUseDeviceAccountingOk

`func (o *LoginResultDomain) GetUseDeviceAccountingOk() (*bool, bool)`

GetUseDeviceAccountingOk returns a tuple with the UseDeviceAccounting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseDeviceAccounting

`func (o *LoginResultDomain) SetUseDeviceAccounting(v bool)`

SetUseDeviceAccounting sets UseDeviceAccounting field to given value.

### HasUseDeviceAccounting

`func (o *LoginResultDomain) HasUseDeviceAccounting() bool`

HasUseDeviceAccounting returns a boolean if a field has been set.

### GetSingleProject

`func (o *LoginResultDomain) GetSingleProject() bool`

GetSingleProject returns the SingleProject field if non-nil, zero value otherwise.

### GetSingleProjectOk

`func (o *LoginResultDomain) GetSingleProjectOk() (*bool, bool)`

GetSingleProjectOk returns a tuple with the SingleProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSingleProject

`func (o *LoginResultDomain) SetSingleProject(v bool)`

SetSingleProject sets SingleProject field to given value.

### HasSingleProject

`func (o *LoginResultDomain) HasSingleProject() bool`

HasSingleProject returns a boolean if a field has been set.

### GetTermsUpdated

`func (o *LoginResultDomain) GetTermsUpdated() string`

GetTermsUpdated returns the TermsUpdated field if non-nil, zero value otherwise.

### GetTermsUpdatedOk

`func (o *LoginResultDomain) GetTermsUpdatedOk() (*string, bool)`

GetTermsUpdatedOk returns a tuple with the TermsUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTermsUpdated

`func (o *LoginResultDomain) SetTermsUpdated(v string)`

SetTermsUpdated sets TermsUpdated field to given value.

### HasTermsUpdated

`func (o *LoginResultDomain) HasTermsUpdated() bool`

HasTermsUpdated returns a boolean if a field has been set.

### GetTrial

`func (o *LoginResultDomain) GetTrial() LoginResultDomainTrial`

GetTrial returns the Trial field if non-nil, zero value otherwise.

### GetTrialOk

`func (o *LoginResultDomain) GetTrialOk() (*LoginResultDomainTrial, bool)`

GetTrialOk returns a tuple with the Trial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrial

`func (o *LoginResultDomain) SetTrial(v LoginResultDomainTrial)`

SetTrial sets Trial field to given value.

### HasTrial

`func (o *LoginResultDomain) HasTrial() bool`

HasTrial returns a boolean if a field has been set.

### SetTrialNil

`func (o *LoginResultDomain) SetTrialNil(b bool)`

 SetTrialNil sets the value for Trial to be an explicit nil

### UnsetTrial
`func (o *LoginResultDomain) UnsetTrial()`

UnsetTrial ensures that no value is present for Trial, not even an explicit nil
### GetWebplayer

`func (o *LoginResultDomain) GetWebplayer() LoginResultDomainWebplayer`

GetWebplayer returns the Webplayer field if non-nil, zero value otherwise.

### GetWebplayerOk

`func (o *LoginResultDomain) GetWebplayerOk() (*LoginResultDomainWebplayer, bool)`

GetWebplayerOk returns a tuple with the Webplayer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebplayer

`func (o *LoginResultDomain) SetWebplayer(v LoginResultDomainWebplayer)`

SetWebplayer sets Webplayer field to given value.

### HasWebplayer

`func (o *LoginResultDomain) HasWebplayer() bool`

HasWebplayer returns a boolean if a field has been set.

### GetSnapshotSharingPermissions

`func (o *LoginResultDomain) GetSnapshotSharingPermissions() LoginResultDomainSnapshotSharingPermissions`

GetSnapshotSharingPermissions returns the SnapshotSharingPermissions field if non-nil, zero value otherwise.

### GetSnapshotSharingPermissionsOk

`func (o *LoginResultDomain) GetSnapshotSharingPermissionsOk() (*LoginResultDomainSnapshotSharingPermissions, bool)`

GetSnapshotSharingPermissionsOk returns a tuple with the SnapshotSharingPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshotSharingPermissions

`func (o *LoginResultDomain) SetSnapshotSharingPermissions(v LoginResultDomainSnapshotSharingPermissions)`

SetSnapshotSharingPermissions sets SnapshotSharingPermissions field to given value.

### HasSnapshotSharingPermissions

`func (o *LoginResultDomain) HasSnapshotSharingPermissions() bool`

HasSnapshotSharingPermissions returns a boolean if a field has been set.

### GetDeviceAutoShutdown

`func (o *LoginResultDomain) GetDeviceAutoShutdown() LoginResultDomainDeviceAutoShutdown`

GetDeviceAutoShutdown returns the DeviceAutoShutdown field if non-nil, zero value otherwise.

### GetDeviceAutoShutdownOk

`func (o *LoginResultDomain) GetDeviceAutoShutdownOk() (*LoginResultDomainDeviceAutoShutdown, bool)`

GetDeviceAutoShutdownOk returns a tuple with the DeviceAutoShutdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceAutoShutdown

`func (o *LoginResultDomain) SetDeviceAutoShutdown(v LoginResultDomainDeviceAutoShutdown)`

SetDeviceAutoShutdown sets DeviceAutoShutdown field to given value.

### HasDeviceAutoShutdown

`func (o *LoginResultDomain) HasDeviceAutoShutdown() bool`

HasDeviceAutoShutdown returns a boolean if a field has been set.

### GetDisabled

`func (o *LoginResultDomain) GetDisabled() LoginResultDomainDisabled`

GetDisabled returns the Disabled field if non-nil, zero value otherwise.

### GetDisabledOk

`func (o *LoginResultDomain) GetDisabledOk() (*LoginResultDomainDisabled, bool)`

GetDisabledOk returns a tuple with the Disabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisabled

`func (o *LoginResultDomain) SetDisabled(v LoginResultDomainDisabled)`

SetDisabled sets Disabled field to given value.

### HasDisabled

`func (o *LoginResultDomain) HasDisabled() bool`

HasDisabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


