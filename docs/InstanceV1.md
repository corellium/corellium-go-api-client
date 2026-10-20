# InstanceV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** | Instance Identifier | [optional] 
**Name** | Pointer to **NullableString** | Instance Name | [optional] 
**Key** | Pointer to **NullableString** | Key used to encrypt the Instance | [optional] 
**Flavor** | Pointer to **NullableString** | The flavor identifier of this instance | [optional] 
**FlavorName** | Pointer to **NullableString** | Human-readable flavor name | [optional] 
**Type** | Pointer to **NullableString** | Device type | [optional] 
**Project** | Pointer to **NullableString** | The projectId of the project this instance belongs to | [optional] 
**DomainName** | Pointer to **NullableString** | Domain name associated with this instance&#39;s project | [optional] 
**State** | Pointer to [**InstanceStateV1**](InstanceStateV1.md) |  | [optional] 
**StateChanged** | Pointer to **NullableTime** | Time the state of the instance last changed | [optional] 
**StartedAt** | Pointer to **NullableTime** | Time the instance was started, NULL if currently SHUTOFF | [optional] 
**UserTask** | Pointer to **NullableString** | Currently executing User Task | [optional] 
**TaskState** | Pointer to **NullableString** | Current task state if any | [optional] 
**Error** | Pointer to **NullableString** | Current error state if any | [optional] 
**RestoreStatus** | Pointer to [**InstanceRestoreStatusV1**](InstanceRestoreStatusV1.md) |  | [optional] 
**ReadOnly** | Pointer to [**InstanceReadOnlyStatusV1**](InstanceReadOnlyStatusV1.md) |  | [optional] 
**BootOptions** | Pointer to [**InstanceBootOptionsV1**](InstanceBootOptionsV1.md) |  | [optional] 
**ServiceIp** | Pointer to **NullableString** | Services IP Address | [optional] 
**WifiIp** | Pointer to **NullableString** | LAN IP Address | [optional] 
**WifiMac** | Pointer to **NullableString** | WiFi MAC address | [optional] 
**SecondaryIp** | Pointer to **NullableString** | Secondary Interface LAN IP Address (if supported) | [optional] 
**PortAdb** | Pointer to **NullableFloat32** | ADB (Android Debug Bridge) port number | [optional] 
**PortUsb** | Pointer to **NullableFloat32** | USB port number | [optional] 
**PortGdb** | Pointer to **NullableFloat32** | GDB (GNU Debugger) port number | [optional] 
**PortSepGdb** | Pointer to **NullableFloat32** | SEP GDB port number | [optional] 
**PortCons** | Pointer to **NullableFloat32** | Default console port number | [optional] 
**PortSepCons** | Pointer to **NullableFloat32** | SEP console port number | [optional] 
**PortSysCons** | Pointer to **NullableFloat32** | System console port number | [optional] 
**PortUsbmuxd** | Pointer to **NullableFloat32** | USBMuxD port number | [optional] 
**PortFrida** | Pointer to **NullableFloat32** | Frida instrumentation port number | [optional] 
**PortSockcap** | Pointer to **NullableFloat32** | Socket capture port number | [optional] 
**PortModelGw** | Pointer to **NullableFloat32** | Model gateway port number | [optional] 
**Consoles** | Pointer to [**[]InstanceConsoleV1**](InstanceConsoleV1.md) | Available console connections | [optional] 
**Services** | Pointer to [**InstanceServicesV1**](InstanceServicesV1.md) |  | [optional] 
**Panicked** | Pointer to **NullableBool** |  | [optional] 
**Created** | Pointer to **NullableTime** | Time instance was created | [optional] 
**Model** | Pointer to **NullableString** | Model of virtual machine device | [optional] 
**Fwpackage** | Pointer to **NullableString** | URL that package used to create this instance is available at | [optional] 
**Os** | Pointer to **NullableString** |  | [optional] 
**Osbuild** | Pointer to **NullableString** |  | [optional] 
**Agent** | Pointer to [**NullableInstanceAgentStateV1**](InstanceAgentStateV1.md) |  | [optional] 
**Netmon** | Pointer to [**InstanceNetmonStateV1**](InstanceNetmonStateV1.md) |  | [optional] 
**Netdump** | Pointer to [**InstanceNetdumpStateV1**](InstanceNetdumpStateV1.md) |  | [optional] 
**CoreTrace** | Pointer to [**InstanceTraceStateV1**](InstanceTraceStateV1.md) |  | [optional] 
**HyperTrace** | Pointer to [**InstanceHyperTraceStateV1**](InstanceHyperTraceStateV1.md) |  | [optional] 
**ExposePort** | Pointer to **NullableString** |  | [optional] 
**Fault** | Pointer to **NullableBool** |  | [optional] 
**Patches** | Pointer to **[]string** |  | [optional] 
**CreatedBy** | Pointer to [**CreatedBy**](CreatedBy.md) |  | [optional] 
**UefiBootloader** | Pointer to **NullableBool** | Whether UEFI bootloader is in use | [optional] 
**Orientation** | Pointer to **NullableFloat32** | Device orientation | [optional] 
**Mast** | Pointer to **NullableBool** | Whether the device has a mast | [optional] 
**WanAccess** | Pointer to **NullableBool** | Whether WAN access is enabled | [optional] 

## Methods

### NewInstanceV1

`func NewInstanceV1() *InstanceV1`

NewInstanceV1 instantiates a new InstanceV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceV1WithDefaults

`func NewInstanceV1WithDefaults() *InstanceV1`

NewInstanceV1WithDefaults instantiates a new InstanceV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InstanceV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InstanceV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InstanceV1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InstanceV1) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *InstanceV1) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *InstanceV1) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetName

`func (o *InstanceV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InstanceV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InstanceV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InstanceV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *InstanceV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *InstanceV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetKey

`func (o *InstanceV1) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *InstanceV1) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *InstanceV1) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *InstanceV1) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *InstanceV1) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *InstanceV1) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetFlavor

`func (o *InstanceV1) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *InstanceV1) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *InstanceV1) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *InstanceV1) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### SetFlavorNil

`func (o *InstanceV1) SetFlavorNil(b bool)`

 SetFlavorNil sets the value for Flavor to be an explicit nil

### UnsetFlavor
`func (o *InstanceV1) UnsetFlavor()`

UnsetFlavor ensures that no value is present for Flavor, not even an explicit nil
### GetFlavorName

`func (o *InstanceV1) GetFlavorName() string`

GetFlavorName returns the FlavorName field if non-nil, zero value otherwise.

### GetFlavorNameOk

`func (o *InstanceV1) GetFlavorNameOk() (*string, bool)`

GetFlavorNameOk returns a tuple with the FlavorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavorName

`func (o *InstanceV1) SetFlavorName(v string)`

SetFlavorName sets FlavorName field to given value.

### HasFlavorName

`func (o *InstanceV1) HasFlavorName() bool`

HasFlavorName returns a boolean if a field has been set.

### SetFlavorNameNil

`func (o *InstanceV1) SetFlavorNameNil(b bool)`

 SetFlavorNameNil sets the value for FlavorName to be an explicit nil

### UnsetFlavorName
`func (o *InstanceV1) UnsetFlavorName()`

UnsetFlavorName ensures that no value is present for FlavorName, not even an explicit nil
### GetType

`func (o *InstanceV1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InstanceV1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InstanceV1) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InstanceV1) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *InstanceV1) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *InstanceV1) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetProject

`func (o *InstanceV1) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *InstanceV1) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *InstanceV1) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *InstanceV1) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *InstanceV1) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *InstanceV1) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetDomainName

`func (o *InstanceV1) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *InstanceV1) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *InstanceV1) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *InstanceV1) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### SetDomainNameNil

`func (o *InstanceV1) SetDomainNameNil(b bool)`

 SetDomainNameNil sets the value for DomainName to be an explicit nil

### UnsetDomainName
`func (o *InstanceV1) UnsetDomainName()`

UnsetDomainName ensures that no value is present for DomainName, not even an explicit nil
### GetState

`func (o *InstanceV1) GetState() InstanceStateV1`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *InstanceV1) GetStateOk() (*InstanceStateV1, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *InstanceV1) SetState(v InstanceStateV1)`

SetState sets State field to given value.

### HasState

`func (o *InstanceV1) HasState() bool`

HasState returns a boolean if a field has been set.

### GetStateChanged

`func (o *InstanceV1) GetStateChanged() time.Time`

GetStateChanged returns the StateChanged field if non-nil, zero value otherwise.

### GetStateChangedOk

`func (o *InstanceV1) GetStateChangedOk() (*time.Time, bool)`

GetStateChangedOk returns a tuple with the StateChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateChanged

`func (o *InstanceV1) SetStateChanged(v time.Time)`

SetStateChanged sets StateChanged field to given value.

### HasStateChanged

`func (o *InstanceV1) HasStateChanged() bool`

HasStateChanged returns a boolean if a field has been set.

### SetStateChangedNil

`func (o *InstanceV1) SetStateChangedNil(b bool)`

 SetStateChangedNil sets the value for StateChanged to be an explicit nil

### UnsetStateChanged
`func (o *InstanceV1) UnsetStateChanged()`

UnsetStateChanged ensures that no value is present for StateChanged, not even an explicit nil
### GetStartedAt

`func (o *InstanceV1) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *InstanceV1) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *InstanceV1) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *InstanceV1) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *InstanceV1) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *InstanceV1) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetUserTask

`func (o *InstanceV1) GetUserTask() string`

GetUserTask returns the UserTask field if non-nil, zero value otherwise.

### GetUserTaskOk

`func (o *InstanceV1) GetUserTaskOk() (*string, bool)`

GetUserTaskOk returns a tuple with the UserTask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTask

`func (o *InstanceV1) SetUserTask(v string)`

SetUserTask sets UserTask field to given value.

### HasUserTask

`func (o *InstanceV1) HasUserTask() bool`

HasUserTask returns a boolean if a field has been set.

### SetUserTaskNil

`func (o *InstanceV1) SetUserTaskNil(b bool)`

 SetUserTaskNil sets the value for UserTask to be an explicit nil

### UnsetUserTask
`func (o *InstanceV1) UnsetUserTask()`

UnsetUserTask ensures that no value is present for UserTask, not even an explicit nil
### GetTaskState

`func (o *InstanceV1) GetTaskState() string`

GetTaskState returns the TaskState field if non-nil, zero value otherwise.

### GetTaskStateOk

`func (o *InstanceV1) GetTaskStateOk() (*string, bool)`

GetTaskStateOk returns a tuple with the TaskState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskState

`func (o *InstanceV1) SetTaskState(v string)`

SetTaskState sets TaskState field to given value.

### HasTaskState

`func (o *InstanceV1) HasTaskState() bool`

HasTaskState returns a boolean if a field has been set.

### SetTaskStateNil

`func (o *InstanceV1) SetTaskStateNil(b bool)`

 SetTaskStateNil sets the value for TaskState to be an explicit nil

### UnsetTaskState
`func (o *InstanceV1) UnsetTaskState()`

UnsetTaskState ensures that no value is present for TaskState, not even an explicit nil
### GetError

`func (o *InstanceV1) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InstanceV1) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InstanceV1) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *InstanceV1) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *InstanceV1) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *InstanceV1) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetRestoreStatus

`func (o *InstanceV1) GetRestoreStatus() InstanceRestoreStatusV1`

GetRestoreStatus returns the RestoreStatus field if non-nil, zero value otherwise.

### GetRestoreStatusOk

`func (o *InstanceV1) GetRestoreStatusOk() (*InstanceRestoreStatusV1, bool)`

GetRestoreStatusOk returns a tuple with the RestoreStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestoreStatus

`func (o *InstanceV1) SetRestoreStatus(v InstanceRestoreStatusV1)`

SetRestoreStatus sets RestoreStatus field to given value.

### HasRestoreStatus

`func (o *InstanceV1) HasRestoreStatus() bool`

HasRestoreStatus returns a boolean if a field has been set.

### GetReadOnly

`func (o *InstanceV1) GetReadOnly() InstanceReadOnlyStatusV1`

GetReadOnly returns the ReadOnly field if non-nil, zero value otherwise.

### GetReadOnlyOk

`func (o *InstanceV1) GetReadOnlyOk() (*InstanceReadOnlyStatusV1, bool)`

GetReadOnlyOk returns a tuple with the ReadOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadOnly

`func (o *InstanceV1) SetReadOnly(v InstanceReadOnlyStatusV1)`

SetReadOnly sets ReadOnly field to given value.

### HasReadOnly

`func (o *InstanceV1) HasReadOnly() bool`

HasReadOnly returns a boolean if a field has been set.

### GetBootOptions

`func (o *InstanceV1) GetBootOptions() InstanceBootOptionsV1`

GetBootOptions returns the BootOptions field if non-nil, zero value otherwise.

### GetBootOptionsOk

`func (o *InstanceV1) GetBootOptionsOk() (*InstanceBootOptionsV1, bool)`

GetBootOptionsOk returns a tuple with the BootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootOptions

`func (o *InstanceV1) SetBootOptions(v InstanceBootOptionsV1)`

SetBootOptions sets BootOptions field to given value.

### HasBootOptions

`func (o *InstanceV1) HasBootOptions() bool`

HasBootOptions returns a boolean if a field has been set.

### GetServiceIp

`func (o *InstanceV1) GetServiceIp() string`

GetServiceIp returns the ServiceIp field if non-nil, zero value otherwise.

### GetServiceIpOk

`func (o *InstanceV1) GetServiceIpOk() (*string, bool)`

GetServiceIpOk returns a tuple with the ServiceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceIp

`func (o *InstanceV1) SetServiceIp(v string)`

SetServiceIp sets ServiceIp field to given value.

### HasServiceIp

`func (o *InstanceV1) HasServiceIp() bool`

HasServiceIp returns a boolean if a field has been set.

### SetServiceIpNil

`func (o *InstanceV1) SetServiceIpNil(b bool)`

 SetServiceIpNil sets the value for ServiceIp to be an explicit nil

### UnsetServiceIp
`func (o *InstanceV1) UnsetServiceIp()`

UnsetServiceIp ensures that no value is present for ServiceIp, not even an explicit nil
### GetWifiIp

`func (o *InstanceV1) GetWifiIp() string`

GetWifiIp returns the WifiIp field if non-nil, zero value otherwise.

### GetWifiIpOk

`func (o *InstanceV1) GetWifiIpOk() (*string, bool)`

GetWifiIpOk returns a tuple with the WifiIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiIp

`func (o *InstanceV1) SetWifiIp(v string)`

SetWifiIp sets WifiIp field to given value.

### HasWifiIp

`func (o *InstanceV1) HasWifiIp() bool`

HasWifiIp returns a boolean if a field has been set.

### SetWifiIpNil

`func (o *InstanceV1) SetWifiIpNil(b bool)`

 SetWifiIpNil sets the value for WifiIp to be an explicit nil

### UnsetWifiIp
`func (o *InstanceV1) UnsetWifiIp()`

UnsetWifiIp ensures that no value is present for WifiIp, not even an explicit nil
### GetWifiMac

`func (o *InstanceV1) GetWifiMac() string`

GetWifiMac returns the WifiMac field if non-nil, zero value otherwise.

### GetWifiMacOk

`func (o *InstanceV1) GetWifiMacOk() (*string, bool)`

GetWifiMacOk returns a tuple with the WifiMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiMac

`func (o *InstanceV1) SetWifiMac(v string)`

SetWifiMac sets WifiMac field to given value.

### HasWifiMac

`func (o *InstanceV1) HasWifiMac() bool`

HasWifiMac returns a boolean if a field has been set.

### SetWifiMacNil

`func (o *InstanceV1) SetWifiMacNil(b bool)`

 SetWifiMacNil sets the value for WifiMac to be an explicit nil

### UnsetWifiMac
`func (o *InstanceV1) UnsetWifiMac()`

UnsetWifiMac ensures that no value is present for WifiMac, not even an explicit nil
### GetSecondaryIp

`func (o *InstanceV1) GetSecondaryIp() string`

GetSecondaryIp returns the SecondaryIp field if non-nil, zero value otherwise.

### GetSecondaryIpOk

`func (o *InstanceV1) GetSecondaryIpOk() (*string, bool)`

GetSecondaryIpOk returns a tuple with the SecondaryIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryIp

`func (o *InstanceV1) SetSecondaryIp(v string)`

SetSecondaryIp sets SecondaryIp field to given value.

### HasSecondaryIp

`func (o *InstanceV1) HasSecondaryIp() bool`

HasSecondaryIp returns a boolean if a field has been set.

### SetSecondaryIpNil

`func (o *InstanceV1) SetSecondaryIpNil(b bool)`

 SetSecondaryIpNil sets the value for SecondaryIp to be an explicit nil

### UnsetSecondaryIp
`func (o *InstanceV1) UnsetSecondaryIp()`

UnsetSecondaryIp ensures that no value is present for SecondaryIp, not even an explicit nil
### GetPortAdb

`func (o *InstanceV1) GetPortAdb() float32`

GetPortAdb returns the PortAdb field if non-nil, zero value otherwise.

### GetPortAdbOk

`func (o *InstanceV1) GetPortAdbOk() (*float32, bool)`

GetPortAdbOk returns a tuple with the PortAdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortAdb

`func (o *InstanceV1) SetPortAdb(v float32)`

SetPortAdb sets PortAdb field to given value.

### HasPortAdb

`func (o *InstanceV1) HasPortAdb() bool`

HasPortAdb returns a boolean if a field has been set.

### SetPortAdbNil

`func (o *InstanceV1) SetPortAdbNil(b bool)`

 SetPortAdbNil sets the value for PortAdb to be an explicit nil

### UnsetPortAdb
`func (o *InstanceV1) UnsetPortAdb()`

UnsetPortAdb ensures that no value is present for PortAdb, not even an explicit nil
### GetPortUsb

`func (o *InstanceV1) GetPortUsb() float32`

GetPortUsb returns the PortUsb field if non-nil, zero value otherwise.

### GetPortUsbOk

`func (o *InstanceV1) GetPortUsbOk() (*float32, bool)`

GetPortUsbOk returns a tuple with the PortUsb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortUsb

`func (o *InstanceV1) SetPortUsb(v float32)`

SetPortUsb sets PortUsb field to given value.

### HasPortUsb

`func (o *InstanceV1) HasPortUsb() bool`

HasPortUsb returns a boolean if a field has been set.

### SetPortUsbNil

`func (o *InstanceV1) SetPortUsbNil(b bool)`

 SetPortUsbNil sets the value for PortUsb to be an explicit nil

### UnsetPortUsb
`func (o *InstanceV1) UnsetPortUsb()`

UnsetPortUsb ensures that no value is present for PortUsb, not even an explicit nil
### GetPortGdb

`func (o *InstanceV1) GetPortGdb() float32`

GetPortGdb returns the PortGdb field if non-nil, zero value otherwise.

### GetPortGdbOk

`func (o *InstanceV1) GetPortGdbOk() (*float32, bool)`

GetPortGdbOk returns a tuple with the PortGdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortGdb

`func (o *InstanceV1) SetPortGdb(v float32)`

SetPortGdb sets PortGdb field to given value.

### HasPortGdb

`func (o *InstanceV1) HasPortGdb() bool`

HasPortGdb returns a boolean if a field has been set.

### SetPortGdbNil

`func (o *InstanceV1) SetPortGdbNil(b bool)`

 SetPortGdbNil sets the value for PortGdb to be an explicit nil

### UnsetPortGdb
`func (o *InstanceV1) UnsetPortGdb()`

UnsetPortGdb ensures that no value is present for PortGdb, not even an explicit nil
### GetPortSepGdb

`func (o *InstanceV1) GetPortSepGdb() float32`

GetPortSepGdb returns the PortSepGdb field if non-nil, zero value otherwise.

### GetPortSepGdbOk

`func (o *InstanceV1) GetPortSepGdbOk() (*float32, bool)`

GetPortSepGdbOk returns a tuple with the PortSepGdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSepGdb

`func (o *InstanceV1) SetPortSepGdb(v float32)`

SetPortSepGdb sets PortSepGdb field to given value.

### HasPortSepGdb

`func (o *InstanceV1) HasPortSepGdb() bool`

HasPortSepGdb returns a boolean if a field has been set.

### SetPortSepGdbNil

`func (o *InstanceV1) SetPortSepGdbNil(b bool)`

 SetPortSepGdbNil sets the value for PortSepGdb to be an explicit nil

### UnsetPortSepGdb
`func (o *InstanceV1) UnsetPortSepGdb()`

UnsetPortSepGdb ensures that no value is present for PortSepGdb, not even an explicit nil
### GetPortCons

`func (o *InstanceV1) GetPortCons() float32`

GetPortCons returns the PortCons field if non-nil, zero value otherwise.

### GetPortConsOk

`func (o *InstanceV1) GetPortConsOk() (*float32, bool)`

GetPortConsOk returns a tuple with the PortCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortCons

`func (o *InstanceV1) SetPortCons(v float32)`

SetPortCons sets PortCons field to given value.

### HasPortCons

`func (o *InstanceV1) HasPortCons() bool`

HasPortCons returns a boolean if a field has been set.

### SetPortConsNil

`func (o *InstanceV1) SetPortConsNil(b bool)`

 SetPortConsNil sets the value for PortCons to be an explicit nil

### UnsetPortCons
`func (o *InstanceV1) UnsetPortCons()`

UnsetPortCons ensures that no value is present for PortCons, not even an explicit nil
### GetPortSepCons

`func (o *InstanceV1) GetPortSepCons() float32`

GetPortSepCons returns the PortSepCons field if non-nil, zero value otherwise.

### GetPortSepConsOk

`func (o *InstanceV1) GetPortSepConsOk() (*float32, bool)`

GetPortSepConsOk returns a tuple with the PortSepCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSepCons

`func (o *InstanceV1) SetPortSepCons(v float32)`

SetPortSepCons sets PortSepCons field to given value.

### HasPortSepCons

`func (o *InstanceV1) HasPortSepCons() bool`

HasPortSepCons returns a boolean if a field has been set.

### SetPortSepConsNil

`func (o *InstanceV1) SetPortSepConsNil(b bool)`

 SetPortSepConsNil sets the value for PortSepCons to be an explicit nil

### UnsetPortSepCons
`func (o *InstanceV1) UnsetPortSepCons()`

UnsetPortSepCons ensures that no value is present for PortSepCons, not even an explicit nil
### GetPortSysCons

`func (o *InstanceV1) GetPortSysCons() float32`

GetPortSysCons returns the PortSysCons field if non-nil, zero value otherwise.

### GetPortSysConsOk

`func (o *InstanceV1) GetPortSysConsOk() (*float32, bool)`

GetPortSysConsOk returns a tuple with the PortSysCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSysCons

`func (o *InstanceV1) SetPortSysCons(v float32)`

SetPortSysCons sets PortSysCons field to given value.

### HasPortSysCons

`func (o *InstanceV1) HasPortSysCons() bool`

HasPortSysCons returns a boolean if a field has been set.

### SetPortSysConsNil

`func (o *InstanceV1) SetPortSysConsNil(b bool)`

 SetPortSysConsNil sets the value for PortSysCons to be an explicit nil

### UnsetPortSysCons
`func (o *InstanceV1) UnsetPortSysCons()`

UnsetPortSysCons ensures that no value is present for PortSysCons, not even an explicit nil
### GetPortUsbmuxd

`func (o *InstanceV1) GetPortUsbmuxd() float32`

GetPortUsbmuxd returns the PortUsbmuxd field if non-nil, zero value otherwise.

### GetPortUsbmuxdOk

`func (o *InstanceV1) GetPortUsbmuxdOk() (*float32, bool)`

GetPortUsbmuxdOk returns a tuple with the PortUsbmuxd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortUsbmuxd

`func (o *InstanceV1) SetPortUsbmuxd(v float32)`

SetPortUsbmuxd sets PortUsbmuxd field to given value.

### HasPortUsbmuxd

`func (o *InstanceV1) HasPortUsbmuxd() bool`

HasPortUsbmuxd returns a boolean if a field has been set.

### SetPortUsbmuxdNil

`func (o *InstanceV1) SetPortUsbmuxdNil(b bool)`

 SetPortUsbmuxdNil sets the value for PortUsbmuxd to be an explicit nil

### UnsetPortUsbmuxd
`func (o *InstanceV1) UnsetPortUsbmuxd()`

UnsetPortUsbmuxd ensures that no value is present for PortUsbmuxd, not even an explicit nil
### GetPortFrida

`func (o *InstanceV1) GetPortFrida() float32`

GetPortFrida returns the PortFrida field if non-nil, zero value otherwise.

### GetPortFridaOk

`func (o *InstanceV1) GetPortFridaOk() (*float32, bool)`

GetPortFridaOk returns a tuple with the PortFrida field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortFrida

`func (o *InstanceV1) SetPortFrida(v float32)`

SetPortFrida sets PortFrida field to given value.

### HasPortFrida

`func (o *InstanceV1) HasPortFrida() bool`

HasPortFrida returns a boolean if a field has been set.

### SetPortFridaNil

`func (o *InstanceV1) SetPortFridaNil(b bool)`

 SetPortFridaNil sets the value for PortFrida to be an explicit nil

### UnsetPortFrida
`func (o *InstanceV1) UnsetPortFrida()`

UnsetPortFrida ensures that no value is present for PortFrida, not even an explicit nil
### GetPortSockcap

`func (o *InstanceV1) GetPortSockcap() float32`

GetPortSockcap returns the PortSockcap field if non-nil, zero value otherwise.

### GetPortSockcapOk

`func (o *InstanceV1) GetPortSockcapOk() (*float32, bool)`

GetPortSockcapOk returns a tuple with the PortSockcap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSockcap

`func (o *InstanceV1) SetPortSockcap(v float32)`

SetPortSockcap sets PortSockcap field to given value.

### HasPortSockcap

`func (o *InstanceV1) HasPortSockcap() bool`

HasPortSockcap returns a boolean if a field has been set.

### SetPortSockcapNil

`func (o *InstanceV1) SetPortSockcapNil(b bool)`

 SetPortSockcapNil sets the value for PortSockcap to be an explicit nil

### UnsetPortSockcap
`func (o *InstanceV1) UnsetPortSockcap()`

UnsetPortSockcap ensures that no value is present for PortSockcap, not even an explicit nil
### GetPortModelGw

`func (o *InstanceV1) GetPortModelGw() float32`

GetPortModelGw returns the PortModelGw field if non-nil, zero value otherwise.

### GetPortModelGwOk

`func (o *InstanceV1) GetPortModelGwOk() (*float32, bool)`

GetPortModelGwOk returns a tuple with the PortModelGw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortModelGw

`func (o *InstanceV1) SetPortModelGw(v float32)`

SetPortModelGw sets PortModelGw field to given value.

### HasPortModelGw

`func (o *InstanceV1) HasPortModelGw() bool`

HasPortModelGw returns a boolean if a field has been set.

### SetPortModelGwNil

`func (o *InstanceV1) SetPortModelGwNil(b bool)`

 SetPortModelGwNil sets the value for PortModelGw to be an explicit nil

### UnsetPortModelGw
`func (o *InstanceV1) UnsetPortModelGw()`

UnsetPortModelGw ensures that no value is present for PortModelGw, not even an explicit nil
### GetConsoles

`func (o *InstanceV1) GetConsoles() []InstanceConsoleV1`

GetConsoles returns the Consoles field if non-nil, zero value otherwise.

### GetConsolesOk

`func (o *InstanceV1) GetConsolesOk() (*[]InstanceConsoleV1, bool)`

GetConsolesOk returns a tuple with the Consoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsoles

`func (o *InstanceV1) SetConsoles(v []InstanceConsoleV1)`

SetConsoles sets Consoles field to given value.

### HasConsoles

`func (o *InstanceV1) HasConsoles() bool`

HasConsoles returns a boolean if a field has been set.

### SetConsolesNil

`func (o *InstanceV1) SetConsolesNil(b bool)`

 SetConsolesNil sets the value for Consoles to be an explicit nil

### UnsetConsoles
`func (o *InstanceV1) UnsetConsoles()`

UnsetConsoles ensures that no value is present for Consoles, not even an explicit nil
### GetServices

`func (o *InstanceV1) GetServices() InstanceServicesV1`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *InstanceV1) GetServicesOk() (*InstanceServicesV1, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *InstanceV1) SetServices(v InstanceServicesV1)`

SetServices sets Services field to given value.

### HasServices

`func (o *InstanceV1) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetPanicked

`func (o *InstanceV1) GetPanicked() bool`

GetPanicked returns the Panicked field if non-nil, zero value otherwise.

### GetPanickedOk

`func (o *InstanceV1) GetPanickedOk() (*bool, bool)`

GetPanickedOk returns a tuple with the Panicked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPanicked

`func (o *InstanceV1) SetPanicked(v bool)`

SetPanicked sets Panicked field to given value.

### HasPanicked

`func (o *InstanceV1) HasPanicked() bool`

HasPanicked returns a boolean if a field has been set.

### SetPanickedNil

`func (o *InstanceV1) SetPanickedNil(b bool)`

 SetPanickedNil sets the value for Panicked to be an explicit nil

### UnsetPanicked
`func (o *InstanceV1) UnsetPanicked()`

UnsetPanicked ensures that no value is present for Panicked, not even an explicit nil
### GetCreated

`func (o *InstanceV1) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *InstanceV1) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *InstanceV1) SetCreated(v time.Time)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *InstanceV1) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### SetCreatedNil

`func (o *InstanceV1) SetCreatedNil(b bool)`

 SetCreatedNil sets the value for Created to be an explicit nil

### UnsetCreated
`func (o *InstanceV1) UnsetCreated()`

UnsetCreated ensures that no value is present for Created, not even an explicit nil
### GetModel

`func (o *InstanceV1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *InstanceV1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *InstanceV1) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *InstanceV1) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *InstanceV1) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *InstanceV1) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetFwpackage

`func (o *InstanceV1) GetFwpackage() string`

GetFwpackage returns the Fwpackage field if non-nil, zero value otherwise.

### GetFwpackageOk

`func (o *InstanceV1) GetFwpackageOk() (*string, bool)`

GetFwpackageOk returns a tuple with the Fwpackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFwpackage

`func (o *InstanceV1) SetFwpackage(v string)`

SetFwpackage sets Fwpackage field to given value.

### HasFwpackage

`func (o *InstanceV1) HasFwpackage() bool`

HasFwpackage returns a boolean if a field has been set.

### SetFwpackageNil

`func (o *InstanceV1) SetFwpackageNil(b bool)`

 SetFwpackageNil sets the value for Fwpackage to be an explicit nil

### UnsetFwpackage
`func (o *InstanceV1) UnsetFwpackage()`

UnsetFwpackage ensures that no value is present for Fwpackage, not even an explicit nil
### GetOs

`func (o *InstanceV1) GetOs() string`

GetOs returns the Os field if non-nil, zero value otherwise.

### GetOsOk

`func (o *InstanceV1) GetOsOk() (*string, bool)`

GetOsOk returns a tuple with the Os field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOs

`func (o *InstanceV1) SetOs(v string)`

SetOs sets Os field to given value.

### HasOs

`func (o *InstanceV1) HasOs() bool`

HasOs returns a boolean if a field has been set.

### SetOsNil

`func (o *InstanceV1) SetOsNil(b bool)`

 SetOsNil sets the value for Os to be an explicit nil

### UnsetOs
`func (o *InstanceV1) UnsetOs()`

UnsetOs ensures that no value is present for Os, not even an explicit nil
### GetOsbuild

`func (o *InstanceV1) GetOsbuild() string`

GetOsbuild returns the Osbuild field if non-nil, zero value otherwise.

### GetOsbuildOk

`func (o *InstanceV1) GetOsbuildOk() (*string, bool)`

GetOsbuildOk returns a tuple with the Osbuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsbuild

`func (o *InstanceV1) SetOsbuild(v string)`

SetOsbuild sets Osbuild field to given value.

### HasOsbuild

`func (o *InstanceV1) HasOsbuild() bool`

HasOsbuild returns a boolean if a field has been set.

### SetOsbuildNil

`func (o *InstanceV1) SetOsbuildNil(b bool)`

 SetOsbuildNil sets the value for Osbuild to be an explicit nil

### UnsetOsbuild
`func (o *InstanceV1) UnsetOsbuild()`

UnsetOsbuild ensures that no value is present for Osbuild, not even an explicit nil
### GetAgent

`func (o *InstanceV1) GetAgent() InstanceAgentStateV1`

GetAgent returns the Agent field if non-nil, zero value otherwise.

### GetAgentOk

`func (o *InstanceV1) GetAgentOk() (*InstanceAgentStateV1, bool)`

GetAgentOk returns a tuple with the Agent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgent

`func (o *InstanceV1) SetAgent(v InstanceAgentStateV1)`

SetAgent sets Agent field to given value.

### HasAgent

`func (o *InstanceV1) HasAgent() bool`

HasAgent returns a boolean if a field has been set.

### SetAgentNil

`func (o *InstanceV1) SetAgentNil(b bool)`

 SetAgentNil sets the value for Agent to be an explicit nil

### UnsetAgent
`func (o *InstanceV1) UnsetAgent()`

UnsetAgent ensures that no value is present for Agent, not even an explicit nil
### GetNetmon

`func (o *InstanceV1) GetNetmon() InstanceNetmonStateV1`

GetNetmon returns the Netmon field if non-nil, zero value otherwise.

### GetNetmonOk

`func (o *InstanceV1) GetNetmonOk() (*InstanceNetmonStateV1, bool)`

GetNetmonOk returns a tuple with the Netmon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetmon

`func (o *InstanceV1) SetNetmon(v InstanceNetmonStateV1)`

SetNetmon sets Netmon field to given value.

### HasNetmon

`func (o *InstanceV1) HasNetmon() bool`

HasNetmon returns a boolean if a field has been set.

### GetNetdump

`func (o *InstanceV1) GetNetdump() InstanceNetdumpStateV1`

GetNetdump returns the Netdump field if non-nil, zero value otherwise.

### GetNetdumpOk

`func (o *InstanceV1) GetNetdumpOk() (*InstanceNetdumpStateV1, bool)`

GetNetdumpOk returns a tuple with the Netdump field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetdump

`func (o *InstanceV1) SetNetdump(v InstanceNetdumpStateV1)`

SetNetdump sets Netdump field to given value.

### HasNetdump

`func (o *InstanceV1) HasNetdump() bool`

HasNetdump returns a boolean if a field has been set.

### GetCoreTrace

`func (o *InstanceV1) GetCoreTrace() InstanceTraceStateV1`

GetCoreTrace returns the CoreTrace field if non-nil, zero value otherwise.

### GetCoreTraceOk

`func (o *InstanceV1) GetCoreTraceOk() (*InstanceTraceStateV1, bool)`

GetCoreTraceOk returns a tuple with the CoreTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreTrace

`func (o *InstanceV1) SetCoreTrace(v InstanceTraceStateV1)`

SetCoreTrace sets CoreTrace field to given value.

### HasCoreTrace

`func (o *InstanceV1) HasCoreTrace() bool`

HasCoreTrace returns a boolean if a field has been set.

### GetHyperTrace

`func (o *InstanceV1) GetHyperTrace() InstanceHyperTraceStateV1`

GetHyperTrace returns the HyperTrace field if non-nil, zero value otherwise.

### GetHyperTraceOk

`func (o *InstanceV1) GetHyperTraceOk() (*InstanceHyperTraceStateV1, bool)`

GetHyperTraceOk returns a tuple with the HyperTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHyperTrace

`func (o *InstanceV1) SetHyperTrace(v InstanceHyperTraceStateV1)`

SetHyperTrace sets HyperTrace field to given value.

### HasHyperTrace

`func (o *InstanceV1) HasHyperTrace() bool`

HasHyperTrace returns a boolean if a field has been set.

### GetExposePort

`func (o *InstanceV1) GetExposePort() string`

GetExposePort returns the ExposePort field if non-nil, zero value otherwise.

### GetExposePortOk

`func (o *InstanceV1) GetExposePortOk() (*string, bool)`

GetExposePortOk returns a tuple with the ExposePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExposePort

`func (o *InstanceV1) SetExposePort(v string)`

SetExposePort sets ExposePort field to given value.

### HasExposePort

`func (o *InstanceV1) HasExposePort() bool`

HasExposePort returns a boolean if a field has been set.

### SetExposePortNil

`func (o *InstanceV1) SetExposePortNil(b bool)`

 SetExposePortNil sets the value for ExposePort to be an explicit nil

### UnsetExposePort
`func (o *InstanceV1) UnsetExposePort()`

UnsetExposePort ensures that no value is present for ExposePort, not even an explicit nil
### GetFault

`func (o *InstanceV1) GetFault() bool`

GetFault returns the Fault field if non-nil, zero value otherwise.

### GetFaultOk

`func (o *InstanceV1) GetFaultOk() (*bool, bool)`

GetFaultOk returns a tuple with the Fault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFault

`func (o *InstanceV1) SetFault(v bool)`

SetFault sets Fault field to given value.

### HasFault

`func (o *InstanceV1) HasFault() bool`

HasFault returns a boolean if a field has been set.

### SetFaultNil

`func (o *InstanceV1) SetFaultNil(b bool)`

 SetFaultNil sets the value for Fault to be an explicit nil

### UnsetFault
`func (o *InstanceV1) UnsetFault()`

UnsetFault ensures that no value is present for Fault, not even an explicit nil
### GetPatches

`func (o *InstanceV1) GetPatches() []string`

GetPatches returns the Patches field if non-nil, zero value otherwise.

### GetPatchesOk

`func (o *InstanceV1) GetPatchesOk() (*[]string, bool)`

GetPatchesOk returns a tuple with the Patches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatches

`func (o *InstanceV1) SetPatches(v []string)`

SetPatches sets Patches field to given value.

### HasPatches

`func (o *InstanceV1) HasPatches() bool`

HasPatches returns a boolean if a field has been set.

### SetPatchesNil

`func (o *InstanceV1) SetPatchesNil(b bool)`

 SetPatchesNil sets the value for Patches to be an explicit nil

### UnsetPatches
`func (o *InstanceV1) UnsetPatches()`

UnsetPatches ensures that no value is present for Patches, not even an explicit nil
### GetCreatedBy

`func (o *InstanceV1) GetCreatedBy() CreatedBy`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *InstanceV1) GetCreatedByOk() (*CreatedBy, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *InstanceV1) SetCreatedBy(v CreatedBy)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *InstanceV1) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetUefiBootloader

`func (o *InstanceV1) GetUefiBootloader() bool`

GetUefiBootloader returns the UefiBootloader field if non-nil, zero value otherwise.

### GetUefiBootloaderOk

`func (o *InstanceV1) GetUefiBootloaderOk() (*bool, bool)`

GetUefiBootloaderOk returns a tuple with the UefiBootloader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUefiBootloader

`func (o *InstanceV1) SetUefiBootloader(v bool)`

SetUefiBootloader sets UefiBootloader field to given value.

### HasUefiBootloader

`func (o *InstanceV1) HasUefiBootloader() bool`

HasUefiBootloader returns a boolean if a field has been set.

### SetUefiBootloaderNil

`func (o *InstanceV1) SetUefiBootloaderNil(b bool)`

 SetUefiBootloaderNil sets the value for UefiBootloader to be an explicit nil

### UnsetUefiBootloader
`func (o *InstanceV1) UnsetUefiBootloader()`

UnsetUefiBootloader ensures that no value is present for UefiBootloader, not even an explicit nil
### GetOrientation

`func (o *InstanceV1) GetOrientation() float32`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *InstanceV1) GetOrientationOk() (*float32, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *InstanceV1) SetOrientation(v float32)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *InstanceV1) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### SetOrientationNil

`func (o *InstanceV1) SetOrientationNil(b bool)`

 SetOrientationNil sets the value for Orientation to be an explicit nil

### UnsetOrientation
`func (o *InstanceV1) UnsetOrientation()`

UnsetOrientation ensures that no value is present for Orientation, not even an explicit nil
### GetMast

`func (o *InstanceV1) GetMast() bool`

GetMast returns the Mast field if non-nil, zero value otherwise.

### GetMastOk

`func (o *InstanceV1) GetMastOk() (*bool, bool)`

GetMastOk returns a tuple with the Mast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMast

`func (o *InstanceV1) SetMast(v bool)`

SetMast sets Mast field to given value.

### HasMast

`func (o *InstanceV1) HasMast() bool`

HasMast returns a boolean if a field has been set.

### SetMastNil

`func (o *InstanceV1) SetMastNil(b bool)`

 SetMastNil sets the value for Mast to be an explicit nil

### UnsetMast
`func (o *InstanceV1) UnsetMast()`

UnsetMast ensures that no value is present for Mast, not even an explicit nil
### GetWanAccess

`func (o *InstanceV1) GetWanAccess() bool`

GetWanAccess returns the WanAccess field if non-nil, zero value otherwise.

### GetWanAccessOk

`func (o *InstanceV1) GetWanAccessOk() (*bool, bool)`

GetWanAccessOk returns a tuple with the WanAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanAccess

`func (o *InstanceV1) SetWanAccess(v bool)`

SetWanAccess sets WanAccess field to given value.

### HasWanAccess

`func (o *InstanceV1) HasWanAccess() bool`

HasWanAccess returns a boolean if a field has been set.

### SetWanAccessNil

`func (o *InstanceV1) SetWanAccessNil(b bool)`

 SetWanAccessNil sets the value for WanAccess to be an explicit nil

### UnsetWanAccess
`func (o *InstanceV1) UnsetWanAccess()`

UnsetWanAccess ensures that no value is present for WanAccess, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


