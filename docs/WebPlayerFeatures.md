# WebPlayerFeatures

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Apps** | Pointer to **bool** | Whether the viewer may use the apps part of the device interface. Features left out are off. | [optional] 
**Connect** | Pointer to **bool** | Whether the viewer may use the connect part of the device interface. Features left out are off. | [optional] 
**Console** | Pointer to **bool** | Whether the viewer may use the console part of the device interface. Features left out are off. | [optional] 
**Coretrace** | Pointer to **bool** | Whether the viewer may use the coretrace part of the device interface. Features left out are off. | [optional] 
**DeviceControl** | Pointer to **bool** | Whether the viewer may use the deviceControl part of the device interface. Features left out are off. | [optional] 
**DeviceDelete** | Pointer to **bool** | Whether the viewer may use the deviceDelete part of the device interface. Features left out are off. | [optional] 
**Files** | Pointer to **bool** | Whether the viewer may use the files part of the device interface. Features left out are off. | [optional] 
**Frida** | Pointer to **bool** | Whether the viewer may use the frida part of the device interface. Features left out are off. | [optional] 
**Images** | Pointer to **bool** | Whether the viewer may use the images part of the device interface. Features left out are off. | [optional] 
**Messaging** | Pointer to **bool** | Whether the viewer may use the messaging part of the device interface. Features left out are off. | [optional] 
**Netmon** | Pointer to **bool** | Whether the viewer may use the netmon part of the device interface. Features left out are off. | [optional] 
**Network** | Pointer to **bool** | Whether the viewer may use the network part of the device interface. Features left out are off. | [optional] 
**PortForwarding** | Pointer to **bool** | Whether the viewer may use the portForwarding part of the device interface. Features left out are off. | [optional] 
**PowerManagement** | Pointer to **bool** | Whether the viewer may use the powerManagement part of the device interface. Features left out are off. | [optional] 
**Profile** | Pointer to **bool** | Whether the viewer may use the profile part of the device interface. Features left out are off. | [optional] 
**Sensors** | Pointer to **bool** | Whether the viewer may use the sensors part of the device interface. Features left out are off. | [optional] 
**Settings** | Pointer to **bool** | Whether the viewer may use the settings part of the device interface. Features left out are off. | [optional] 
**Snapshots** | Pointer to **bool** | Whether the viewer may use the snapshots part of the device interface. Features left out are off. | [optional] 
**Strace** | Pointer to **bool** | Whether the viewer may use the strace part of the device interface. Features left out are off. | [optional] 
**System** | Pointer to **bool** | Whether the viewer may use the system part of the device interface. Features left out are off. | [optional] 

## Methods

### NewWebPlayerFeatures

`func NewWebPlayerFeatures() *WebPlayerFeatures`

NewWebPlayerFeatures instantiates a new WebPlayerFeatures object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebPlayerFeaturesWithDefaults

`func NewWebPlayerFeaturesWithDefaults() *WebPlayerFeatures`

NewWebPlayerFeaturesWithDefaults instantiates a new WebPlayerFeatures object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApps

`func (o *WebPlayerFeatures) GetApps() bool`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *WebPlayerFeatures) GetAppsOk() (*bool, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *WebPlayerFeatures) SetApps(v bool)`

SetApps sets Apps field to given value.

### HasApps

`func (o *WebPlayerFeatures) HasApps() bool`

HasApps returns a boolean if a field has been set.

### GetConnect

`func (o *WebPlayerFeatures) GetConnect() bool`

GetConnect returns the Connect field if non-nil, zero value otherwise.

### GetConnectOk

`func (o *WebPlayerFeatures) GetConnectOk() (*bool, bool)`

GetConnectOk returns a tuple with the Connect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnect

`func (o *WebPlayerFeatures) SetConnect(v bool)`

SetConnect sets Connect field to given value.

### HasConnect

`func (o *WebPlayerFeatures) HasConnect() bool`

HasConnect returns a boolean if a field has been set.

### GetConsole

`func (o *WebPlayerFeatures) GetConsole() bool`

GetConsole returns the Console field if non-nil, zero value otherwise.

### GetConsoleOk

`func (o *WebPlayerFeatures) GetConsoleOk() (*bool, bool)`

GetConsoleOk returns a tuple with the Console field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsole

`func (o *WebPlayerFeatures) SetConsole(v bool)`

SetConsole sets Console field to given value.

### HasConsole

`func (o *WebPlayerFeatures) HasConsole() bool`

HasConsole returns a boolean if a field has been set.

### GetCoretrace

`func (o *WebPlayerFeatures) GetCoretrace() bool`

GetCoretrace returns the Coretrace field if non-nil, zero value otherwise.

### GetCoretraceOk

`func (o *WebPlayerFeatures) GetCoretraceOk() (*bool, bool)`

GetCoretraceOk returns a tuple with the Coretrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoretrace

`func (o *WebPlayerFeatures) SetCoretrace(v bool)`

SetCoretrace sets Coretrace field to given value.

### HasCoretrace

`func (o *WebPlayerFeatures) HasCoretrace() bool`

HasCoretrace returns a boolean if a field has been set.

### GetDeviceControl

`func (o *WebPlayerFeatures) GetDeviceControl() bool`

GetDeviceControl returns the DeviceControl field if non-nil, zero value otherwise.

### GetDeviceControlOk

`func (o *WebPlayerFeatures) GetDeviceControlOk() (*bool, bool)`

GetDeviceControlOk returns a tuple with the DeviceControl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceControl

`func (o *WebPlayerFeatures) SetDeviceControl(v bool)`

SetDeviceControl sets DeviceControl field to given value.

### HasDeviceControl

`func (o *WebPlayerFeatures) HasDeviceControl() bool`

HasDeviceControl returns a boolean if a field has been set.

### GetDeviceDelete

`func (o *WebPlayerFeatures) GetDeviceDelete() bool`

GetDeviceDelete returns the DeviceDelete field if non-nil, zero value otherwise.

### GetDeviceDeleteOk

`func (o *WebPlayerFeatures) GetDeviceDeleteOk() (*bool, bool)`

GetDeviceDeleteOk returns a tuple with the DeviceDelete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceDelete

`func (o *WebPlayerFeatures) SetDeviceDelete(v bool)`

SetDeviceDelete sets DeviceDelete field to given value.

### HasDeviceDelete

`func (o *WebPlayerFeatures) HasDeviceDelete() bool`

HasDeviceDelete returns a boolean if a field has been set.

### GetFiles

`func (o *WebPlayerFeatures) GetFiles() bool`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *WebPlayerFeatures) GetFilesOk() (*bool, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *WebPlayerFeatures) SetFiles(v bool)`

SetFiles sets Files field to given value.

### HasFiles

`func (o *WebPlayerFeatures) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### GetFrida

`func (o *WebPlayerFeatures) GetFrida() bool`

GetFrida returns the Frida field if non-nil, zero value otherwise.

### GetFridaOk

`func (o *WebPlayerFeatures) GetFridaOk() (*bool, bool)`

GetFridaOk returns a tuple with the Frida field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrida

`func (o *WebPlayerFeatures) SetFrida(v bool)`

SetFrida sets Frida field to given value.

### HasFrida

`func (o *WebPlayerFeatures) HasFrida() bool`

HasFrida returns a boolean if a field has been set.

### GetImages

`func (o *WebPlayerFeatures) GetImages() bool`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *WebPlayerFeatures) GetImagesOk() (*bool, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *WebPlayerFeatures) SetImages(v bool)`

SetImages sets Images field to given value.

### HasImages

`func (o *WebPlayerFeatures) HasImages() bool`

HasImages returns a boolean if a field has been set.

### GetMessaging

`func (o *WebPlayerFeatures) GetMessaging() bool`

GetMessaging returns the Messaging field if non-nil, zero value otherwise.

### GetMessagingOk

`func (o *WebPlayerFeatures) GetMessagingOk() (*bool, bool)`

GetMessagingOk returns a tuple with the Messaging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessaging

`func (o *WebPlayerFeatures) SetMessaging(v bool)`

SetMessaging sets Messaging field to given value.

### HasMessaging

`func (o *WebPlayerFeatures) HasMessaging() bool`

HasMessaging returns a boolean if a field has been set.

### GetNetmon

`func (o *WebPlayerFeatures) GetNetmon() bool`

GetNetmon returns the Netmon field if non-nil, zero value otherwise.

### GetNetmonOk

`func (o *WebPlayerFeatures) GetNetmonOk() (*bool, bool)`

GetNetmonOk returns a tuple with the Netmon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetmon

`func (o *WebPlayerFeatures) SetNetmon(v bool)`

SetNetmon sets Netmon field to given value.

### HasNetmon

`func (o *WebPlayerFeatures) HasNetmon() bool`

HasNetmon returns a boolean if a field has been set.

### GetNetwork

`func (o *WebPlayerFeatures) GetNetwork() bool`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *WebPlayerFeatures) GetNetworkOk() (*bool, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *WebPlayerFeatures) SetNetwork(v bool)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *WebPlayerFeatures) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetPortForwarding

`func (o *WebPlayerFeatures) GetPortForwarding() bool`

GetPortForwarding returns the PortForwarding field if non-nil, zero value otherwise.

### GetPortForwardingOk

`func (o *WebPlayerFeatures) GetPortForwardingOk() (*bool, bool)`

GetPortForwardingOk returns a tuple with the PortForwarding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortForwarding

`func (o *WebPlayerFeatures) SetPortForwarding(v bool)`

SetPortForwarding sets PortForwarding field to given value.

### HasPortForwarding

`func (o *WebPlayerFeatures) HasPortForwarding() bool`

HasPortForwarding returns a boolean if a field has been set.

### GetPowerManagement

`func (o *WebPlayerFeatures) GetPowerManagement() bool`

GetPowerManagement returns the PowerManagement field if non-nil, zero value otherwise.

### GetPowerManagementOk

`func (o *WebPlayerFeatures) GetPowerManagementOk() (*bool, bool)`

GetPowerManagementOk returns a tuple with the PowerManagement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPowerManagement

`func (o *WebPlayerFeatures) SetPowerManagement(v bool)`

SetPowerManagement sets PowerManagement field to given value.

### HasPowerManagement

`func (o *WebPlayerFeatures) HasPowerManagement() bool`

HasPowerManagement returns a boolean if a field has been set.

### GetProfile

`func (o *WebPlayerFeatures) GetProfile() bool`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *WebPlayerFeatures) GetProfileOk() (*bool, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *WebPlayerFeatures) SetProfile(v bool)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *WebPlayerFeatures) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### GetSensors

`func (o *WebPlayerFeatures) GetSensors() bool`

GetSensors returns the Sensors field if non-nil, zero value otherwise.

### GetSensorsOk

`func (o *WebPlayerFeatures) GetSensorsOk() (*bool, bool)`

GetSensorsOk returns a tuple with the Sensors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSensors

`func (o *WebPlayerFeatures) SetSensors(v bool)`

SetSensors sets Sensors field to given value.

### HasSensors

`func (o *WebPlayerFeatures) HasSensors() bool`

HasSensors returns a boolean if a field has been set.

### GetSettings

`func (o *WebPlayerFeatures) GetSettings() bool`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *WebPlayerFeatures) GetSettingsOk() (*bool, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *WebPlayerFeatures) SetSettings(v bool)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *WebPlayerFeatures) HasSettings() bool`

HasSettings returns a boolean if a field has been set.

### GetSnapshots

`func (o *WebPlayerFeatures) GetSnapshots() bool`

GetSnapshots returns the Snapshots field if non-nil, zero value otherwise.

### GetSnapshotsOk

`func (o *WebPlayerFeatures) GetSnapshotsOk() (*bool, bool)`

GetSnapshotsOk returns a tuple with the Snapshots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshots

`func (o *WebPlayerFeatures) SetSnapshots(v bool)`

SetSnapshots sets Snapshots field to given value.

### HasSnapshots

`func (o *WebPlayerFeatures) HasSnapshots() bool`

HasSnapshots returns a boolean if a field has been set.

### GetStrace

`func (o *WebPlayerFeatures) GetStrace() bool`

GetStrace returns the Strace field if non-nil, zero value otherwise.

### GetStraceOk

`func (o *WebPlayerFeatures) GetStraceOk() (*bool, bool)`

GetStraceOk returns a tuple with the Strace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrace

`func (o *WebPlayerFeatures) SetStrace(v bool)`

SetStrace sets Strace field to given value.

### HasStrace

`func (o *WebPlayerFeatures) HasStrace() bool`

HasStrace returns a boolean if a field has been set.

### GetSystem

`func (o *WebPlayerFeatures) GetSystem() bool`

GetSystem returns the System field if non-nil, zero value otherwise.

### GetSystemOk

`func (o *WebPlayerFeatures) GetSystemOk() (*bool, bool)`

GetSystemOk returns a tuple with the System field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystem

`func (o *WebPlayerFeatures) SetSystem(v bool)`

SetSystem sets System field to given value.

### HasSystem

`func (o *WebPlayerFeatures) HasSystem() bool`

HasSystem returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


