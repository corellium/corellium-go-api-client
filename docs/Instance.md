# Instance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Instance identifier. | 
**Name** | **string** | Instance name. | 
**Key** | **string** | Key used to encrypt the instance (hex). | 
**Flavor** | **string** | The flavor identifier of this instance. | 
**FlavorName** | Pointer to **string** | Human-readable flavor name. | [optional] 
**Type** | **string** | Device type. | 
**Project** | **string** | The project ID of the project this instance belongs to. | 
**DomainName** | Pointer to **string** | Domain name associated with this instance&#39;s project. | [optional] 
**State** | [**InstanceState**](InstanceState.md) |  | 
**StateChanged** | **NullableTime** | Time the state of the instance last changed; null before the first transition. | 
**StartedAt** | **NullableTime** | Time the instance was started, NULL if currently SHUTOFF. | 
**UserTask** | Pointer to **NullableString** | Currently executing user task. | [optional] 
**TaskState** | Pointer to **string** | Current task state if any (e.g. &#39;none&#39;, &#39;starting&#39;, &#39;stopping&#39;, &#39;pausing&#39;, &#39;unpausing&#39;, &#39;rebooting&#39;, &#39;building&#39;). | [optional] 
**Error** | Pointer to **NullableString** | Current error state if any. | [optional] 
**RestoreStatus** | Pointer to [**InstanceRestoreStatus**](InstanceRestoreStatus.md) |  | [optional] 
**ReadOnly** | Pointer to [**NullableInstanceReadOnlyStatus**](InstanceReadOnlyStatus.md) |  | [optional] 
**BootOptions** | Pointer to [**InstanceBootOptions**](InstanceBootOptions.md) |  | [optional] 
**ServiceIp** | Pointer to **string** | Services IP address. | [optional] 
**WifiIp** | Pointer to **string** | LAN IP address. | [optional] 
**WifiMac** | Pointer to **string** | WiFi MAC address. | [optional] 
**SecondaryIp** | Pointer to **string** | Secondary interface LAN IP address (if supported). | [optional] 
**PortAdb** | Pointer to **string** | ADB port number. | [optional] 
**PortUsb** | Pointer to **string** | USB port number. | [optional] 
**PortGdb** | Pointer to **string** | GDB port number. | [optional] 
**PortSepGdb** | Pointer to **string** | SEP GDB port number. | [optional] 
**PortCons** | Pointer to **string** | Default console port number. | [optional] 
**PortSepCons** | Pointer to **string** | SEP console port number. | [optional] 
**PortSysCons** | Pointer to **string** | System console port number. | [optional] 
**PortUsbmuxd** | Pointer to **string** | USBMuxD port number. | [optional] 
**PortFrida** | Pointer to **string** | Frida instrumentation port number. | [optional] 
**PortSockcap** | Pointer to **string** | Socket capture port number. | [optional] 
**PortModelGw** | Pointer to **string** | Model gateway port number. | [optional] 
**Consoles** | Pointer to [**[]InstanceConsole**](InstanceConsole.md) | Available console connections. | [optional] 
**Interfaces** | Pointer to [**[]InstanceInterfaceStatus**](InstanceInterfaceStatus.md) | Available configurable interfaces and their attachment status. | [optional] 
**Services** | Pointer to [**InstanceServices**](InstanceServices.md) |  | [optional] 
**Panicked** | Pointer to **bool** | Whether the instance has panicked. | [optional] 
**Created** | **time.Time** | Time instance was created. | 
**Model** | Pointer to **string** | Model of virtual machine device. | [optional] 
**FwPackage** | Pointer to **string** | URL that the package used to create this instance is available at. | [optional] 
**OsVersion** | Pointer to **string** | OS version. | [optional] 
**OsBuild** | Pointer to **string** | OS build. | [optional] 
**Agent** | Pointer to [**NullableInstanceAgentState**](InstanceAgentState.md) |  | [optional] 
**NetMon** | Pointer to [**InstanceNetmonState**](InstanceNetmonState.md) |  | [optional] 
**NetDump** | Pointer to [**InstanceNetdumpState**](InstanceNetdumpState.md) |  | [optional] 
**CoreTrace** | Pointer to [**InstanceTraceState**](InstanceTraceState.md) |  | [optional] 
**HyperTrace** | Pointer to [**InstanceHyperTraceState**](InstanceHyperTraceState.md) |  | [optional] 
**ExposePort** | Pointer to **NullableString** | Currently exposed port, if any. | [optional] 
**Fault** | Pointer to **NullableBool** | Whether the instance is in a fault state. | [optional] 
**Patches** | Pointer to **[]string** | Patches applied to the instance. | [optional] 
**CreatedBy** | Pointer to [**NullableCreatedBy**](CreatedBy.md) |  | [optional] 
**UefiBootloader** | Pointer to [**InstanceUefiBootloader**](InstanceUefiBootloader.md) |  | [optional] 
**Orientation** | Pointer to **float32** | Device orientation. | [optional] 
**Mast** | Pointer to **bool** | Whether MATRIX is enabled. | [optional] 
**WanAccess** | Pointer to **bool** | Whether WAN access is enabled. | [optional] 

## Methods

### NewInstance

`func NewInstance(id string, name string, key string, flavor string, type_ string, project string, state InstanceState, stateChanged NullableTime, startedAt NullableTime, created time.Time, ) *Instance`

NewInstance instantiates a new Instance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceWithDefaults

`func NewInstanceWithDefaults() *Instance`

NewInstanceWithDefaults instantiates a new Instance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Instance) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Instance) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Instance) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Instance) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Instance) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Instance) SetName(v string)`

SetName sets Name field to given value.


### GetKey

`func (o *Instance) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *Instance) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *Instance) SetKey(v string)`

SetKey sets Key field to given value.


### GetFlavor

`func (o *Instance) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *Instance) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *Instance) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.


### GetFlavorName

`func (o *Instance) GetFlavorName() string`

GetFlavorName returns the FlavorName field if non-nil, zero value otherwise.

### GetFlavorNameOk

`func (o *Instance) GetFlavorNameOk() (*string, bool)`

GetFlavorNameOk returns a tuple with the FlavorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavorName

`func (o *Instance) SetFlavorName(v string)`

SetFlavorName sets FlavorName field to given value.

### HasFlavorName

`func (o *Instance) HasFlavorName() bool`

HasFlavorName returns a boolean if a field has been set.

### GetType

`func (o *Instance) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Instance) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Instance) SetType(v string)`

SetType sets Type field to given value.


### GetProject

`func (o *Instance) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *Instance) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *Instance) SetProject(v string)`

SetProject sets Project field to given value.


### GetDomainName

`func (o *Instance) GetDomainName() string`

GetDomainName returns the DomainName field if non-nil, zero value otherwise.

### GetDomainNameOk

`func (o *Instance) GetDomainNameOk() (*string, bool)`

GetDomainNameOk returns a tuple with the DomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainName

`func (o *Instance) SetDomainName(v string)`

SetDomainName sets DomainName field to given value.

### HasDomainName

`func (o *Instance) HasDomainName() bool`

HasDomainName returns a boolean if a field has been set.

### GetState

`func (o *Instance) GetState() InstanceState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Instance) GetStateOk() (*InstanceState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Instance) SetState(v InstanceState)`

SetState sets State field to given value.


### GetStateChanged

`func (o *Instance) GetStateChanged() time.Time`

GetStateChanged returns the StateChanged field if non-nil, zero value otherwise.

### GetStateChangedOk

`func (o *Instance) GetStateChangedOk() (*time.Time, bool)`

GetStateChangedOk returns a tuple with the StateChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStateChanged

`func (o *Instance) SetStateChanged(v time.Time)`

SetStateChanged sets StateChanged field to given value.


### SetStateChangedNil

`func (o *Instance) SetStateChangedNil(b bool)`

 SetStateChangedNil sets the value for StateChanged to be an explicit nil

### UnsetStateChanged
`func (o *Instance) UnsetStateChanged()`

UnsetStateChanged ensures that no value is present for StateChanged, not even an explicit nil
### GetStartedAt

`func (o *Instance) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *Instance) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *Instance) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *Instance) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *Instance) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetUserTask

`func (o *Instance) GetUserTask() string`

GetUserTask returns the UserTask field if non-nil, zero value otherwise.

### GetUserTaskOk

`func (o *Instance) GetUserTaskOk() (*string, bool)`

GetUserTaskOk returns a tuple with the UserTask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTask

`func (o *Instance) SetUserTask(v string)`

SetUserTask sets UserTask field to given value.

### HasUserTask

`func (o *Instance) HasUserTask() bool`

HasUserTask returns a boolean if a field has been set.

### SetUserTaskNil

`func (o *Instance) SetUserTaskNil(b bool)`

 SetUserTaskNil sets the value for UserTask to be an explicit nil

### UnsetUserTask
`func (o *Instance) UnsetUserTask()`

UnsetUserTask ensures that no value is present for UserTask, not even an explicit nil
### GetTaskState

`func (o *Instance) GetTaskState() string`

GetTaskState returns the TaskState field if non-nil, zero value otherwise.

### GetTaskStateOk

`func (o *Instance) GetTaskStateOk() (*string, bool)`

GetTaskStateOk returns a tuple with the TaskState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskState

`func (o *Instance) SetTaskState(v string)`

SetTaskState sets TaskState field to given value.

### HasTaskState

`func (o *Instance) HasTaskState() bool`

HasTaskState returns a boolean if a field has been set.

### GetError

`func (o *Instance) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Instance) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Instance) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *Instance) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *Instance) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *Instance) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetRestoreStatus

`func (o *Instance) GetRestoreStatus() InstanceRestoreStatus`

GetRestoreStatus returns the RestoreStatus field if non-nil, zero value otherwise.

### GetRestoreStatusOk

`func (o *Instance) GetRestoreStatusOk() (*InstanceRestoreStatus, bool)`

GetRestoreStatusOk returns a tuple with the RestoreStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestoreStatus

`func (o *Instance) SetRestoreStatus(v InstanceRestoreStatus)`

SetRestoreStatus sets RestoreStatus field to given value.

### HasRestoreStatus

`func (o *Instance) HasRestoreStatus() bool`

HasRestoreStatus returns a boolean if a field has been set.

### GetReadOnly

`func (o *Instance) GetReadOnly() InstanceReadOnlyStatus`

GetReadOnly returns the ReadOnly field if non-nil, zero value otherwise.

### GetReadOnlyOk

`func (o *Instance) GetReadOnlyOk() (*InstanceReadOnlyStatus, bool)`

GetReadOnlyOk returns a tuple with the ReadOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadOnly

`func (o *Instance) SetReadOnly(v InstanceReadOnlyStatus)`

SetReadOnly sets ReadOnly field to given value.

### HasReadOnly

`func (o *Instance) HasReadOnly() bool`

HasReadOnly returns a boolean if a field has been set.

### SetReadOnlyNil

`func (o *Instance) SetReadOnlyNil(b bool)`

 SetReadOnlyNil sets the value for ReadOnly to be an explicit nil

### UnsetReadOnly
`func (o *Instance) UnsetReadOnly()`

UnsetReadOnly ensures that no value is present for ReadOnly, not even an explicit nil
### GetBootOptions

`func (o *Instance) GetBootOptions() InstanceBootOptions`

GetBootOptions returns the BootOptions field if non-nil, zero value otherwise.

### GetBootOptionsOk

`func (o *Instance) GetBootOptionsOk() (*InstanceBootOptions, bool)`

GetBootOptionsOk returns a tuple with the BootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootOptions

`func (o *Instance) SetBootOptions(v InstanceBootOptions)`

SetBootOptions sets BootOptions field to given value.

### HasBootOptions

`func (o *Instance) HasBootOptions() bool`

HasBootOptions returns a boolean if a field has been set.

### GetServiceIp

`func (o *Instance) GetServiceIp() string`

GetServiceIp returns the ServiceIp field if non-nil, zero value otherwise.

### GetServiceIpOk

`func (o *Instance) GetServiceIpOk() (*string, bool)`

GetServiceIpOk returns a tuple with the ServiceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceIp

`func (o *Instance) SetServiceIp(v string)`

SetServiceIp sets ServiceIp field to given value.

### HasServiceIp

`func (o *Instance) HasServiceIp() bool`

HasServiceIp returns a boolean if a field has been set.

### GetWifiIp

`func (o *Instance) GetWifiIp() string`

GetWifiIp returns the WifiIp field if non-nil, zero value otherwise.

### GetWifiIpOk

`func (o *Instance) GetWifiIpOk() (*string, bool)`

GetWifiIpOk returns a tuple with the WifiIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiIp

`func (o *Instance) SetWifiIp(v string)`

SetWifiIp sets WifiIp field to given value.

### HasWifiIp

`func (o *Instance) HasWifiIp() bool`

HasWifiIp returns a boolean if a field has been set.

### GetWifiMac

`func (o *Instance) GetWifiMac() string`

GetWifiMac returns the WifiMac field if non-nil, zero value otherwise.

### GetWifiMacOk

`func (o *Instance) GetWifiMacOk() (*string, bool)`

GetWifiMacOk returns a tuple with the WifiMac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiMac

`func (o *Instance) SetWifiMac(v string)`

SetWifiMac sets WifiMac field to given value.

### HasWifiMac

`func (o *Instance) HasWifiMac() bool`

HasWifiMac returns a boolean if a field has been set.

### GetSecondaryIp

`func (o *Instance) GetSecondaryIp() string`

GetSecondaryIp returns the SecondaryIp field if non-nil, zero value otherwise.

### GetSecondaryIpOk

`func (o *Instance) GetSecondaryIpOk() (*string, bool)`

GetSecondaryIpOk returns a tuple with the SecondaryIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecondaryIp

`func (o *Instance) SetSecondaryIp(v string)`

SetSecondaryIp sets SecondaryIp field to given value.

### HasSecondaryIp

`func (o *Instance) HasSecondaryIp() bool`

HasSecondaryIp returns a boolean if a field has been set.

### GetPortAdb

`func (o *Instance) GetPortAdb() string`

GetPortAdb returns the PortAdb field if non-nil, zero value otherwise.

### GetPortAdbOk

`func (o *Instance) GetPortAdbOk() (*string, bool)`

GetPortAdbOk returns a tuple with the PortAdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortAdb

`func (o *Instance) SetPortAdb(v string)`

SetPortAdb sets PortAdb field to given value.

### HasPortAdb

`func (o *Instance) HasPortAdb() bool`

HasPortAdb returns a boolean if a field has been set.

### GetPortUsb

`func (o *Instance) GetPortUsb() string`

GetPortUsb returns the PortUsb field if non-nil, zero value otherwise.

### GetPortUsbOk

`func (o *Instance) GetPortUsbOk() (*string, bool)`

GetPortUsbOk returns a tuple with the PortUsb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortUsb

`func (o *Instance) SetPortUsb(v string)`

SetPortUsb sets PortUsb field to given value.

### HasPortUsb

`func (o *Instance) HasPortUsb() bool`

HasPortUsb returns a boolean if a field has been set.

### GetPortGdb

`func (o *Instance) GetPortGdb() string`

GetPortGdb returns the PortGdb field if non-nil, zero value otherwise.

### GetPortGdbOk

`func (o *Instance) GetPortGdbOk() (*string, bool)`

GetPortGdbOk returns a tuple with the PortGdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortGdb

`func (o *Instance) SetPortGdb(v string)`

SetPortGdb sets PortGdb field to given value.

### HasPortGdb

`func (o *Instance) HasPortGdb() bool`

HasPortGdb returns a boolean if a field has been set.

### GetPortSepGdb

`func (o *Instance) GetPortSepGdb() string`

GetPortSepGdb returns the PortSepGdb field if non-nil, zero value otherwise.

### GetPortSepGdbOk

`func (o *Instance) GetPortSepGdbOk() (*string, bool)`

GetPortSepGdbOk returns a tuple with the PortSepGdb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSepGdb

`func (o *Instance) SetPortSepGdb(v string)`

SetPortSepGdb sets PortSepGdb field to given value.

### HasPortSepGdb

`func (o *Instance) HasPortSepGdb() bool`

HasPortSepGdb returns a boolean if a field has been set.

### GetPortCons

`func (o *Instance) GetPortCons() string`

GetPortCons returns the PortCons field if non-nil, zero value otherwise.

### GetPortConsOk

`func (o *Instance) GetPortConsOk() (*string, bool)`

GetPortConsOk returns a tuple with the PortCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortCons

`func (o *Instance) SetPortCons(v string)`

SetPortCons sets PortCons field to given value.

### HasPortCons

`func (o *Instance) HasPortCons() bool`

HasPortCons returns a boolean if a field has been set.

### GetPortSepCons

`func (o *Instance) GetPortSepCons() string`

GetPortSepCons returns the PortSepCons field if non-nil, zero value otherwise.

### GetPortSepConsOk

`func (o *Instance) GetPortSepConsOk() (*string, bool)`

GetPortSepConsOk returns a tuple with the PortSepCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSepCons

`func (o *Instance) SetPortSepCons(v string)`

SetPortSepCons sets PortSepCons field to given value.

### HasPortSepCons

`func (o *Instance) HasPortSepCons() bool`

HasPortSepCons returns a boolean if a field has been set.

### GetPortSysCons

`func (o *Instance) GetPortSysCons() string`

GetPortSysCons returns the PortSysCons field if non-nil, zero value otherwise.

### GetPortSysConsOk

`func (o *Instance) GetPortSysConsOk() (*string, bool)`

GetPortSysConsOk returns a tuple with the PortSysCons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSysCons

`func (o *Instance) SetPortSysCons(v string)`

SetPortSysCons sets PortSysCons field to given value.

### HasPortSysCons

`func (o *Instance) HasPortSysCons() bool`

HasPortSysCons returns a boolean if a field has been set.

### GetPortUsbmuxd

`func (o *Instance) GetPortUsbmuxd() string`

GetPortUsbmuxd returns the PortUsbmuxd field if non-nil, zero value otherwise.

### GetPortUsbmuxdOk

`func (o *Instance) GetPortUsbmuxdOk() (*string, bool)`

GetPortUsbmuxdOk returns a tuple with the PortUsbmuxd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortUsbmuxd

`func (o *Instance) SetPortUsbmuxd(v string)`

SetPortUsbmuxd sets PortUsbmuxd field to given value.

### HasPortUsbmuxd

`func (o *Instance) HasPortUsbmuxd() bool`

HasPortUsbmuxd returns a boolean if a field has been set.

### GetPortFrida

`func (o *Instance) GetPortFrida() string`

GetPortFrida returns the PortFrida field if non-nil, zero value otherwise.

### GetPortFridaOk

`func (o *Instance) GetPortFridaOk() (*string, bool)`

GetPortFridaOk returns a tuple with the PortFrida field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortFrida

`func (o *Instance) SetPortFrida(v string)`

SetPortFrida sets PortFrida field to given value.

### HasPortFrida

`func (o *Instance) HasPortFrida() bool`

HasPortFrida returns a boolean if a field has been set.

### GetPortSockcap

`func (o *Instance) GetPortSockcap() string`

GetPortSockcap returns the PortSockcap field if non-nil, zero value otherwise.

### GetPortSockcapOk

`func (o *Instance) GetPortSockcapOk() (*string, bool)`

GetPortSockcapOk returns a tuple with the PortSockcap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortSockcap

`func (o *Instance) SetPortSockcap(v string)`

SetPortSockcap sets PortSockcap field to given value.

### HasPortSockcap

`func (o *Instance) HasPortSockcap() bool`

HasPortSockcap returns a boolean if a field has been set.

### GetPortModelGw

`func (o *Instance) GetPortModelGw() string`

GetPortModelGw returns the PortModelGw field if non-nil, zero value otherwise.

### GetPortModelGwOk

`func (o *Instance) GetPortModelGwOk() (*string, bool)`

GetPortModelGwOk returns a tuple with the PortModelGw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortModelGw

`func (o *Instance) SetPortModelGw(v string)`

SetPortModelGw sets PortModelGw field to given value.

### HasPortModelGw

`func (o *Instance) HasPortModelGw() bool`

HasPortModelGw returns a boolean if a field has been set.

### GetConsoles

`func (o *Instance) GetConsoles() []InstanceConsole`

GetConsoles returns the Consoles field if non-nil, zero value otherwise.

### GetConsolesOk

`func (o *Instance) GetConsolesOk() (*[]InstanceConsole, bool)`

GetConsolesOk returns a tuple with the Consoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsoles

`func (o *Instance) SetConsoles(v []InstanceConsole)`

SetConsoles sets Consoles field to given value.

### HasConsoles

`func (o *Instance) HasConsoles() bool`

HasConsoles returns a boolean if a field has been set.

### GetInterfaces

`func (o *Instance) GetInterfaces() []InstanceInterfaceStatus`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *Instance) GetInterfacesOk() (*[]InstanceInterfaceStatus, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *Instance) SetInterfaces(v []InstanceInterfaceStatus)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *Instance) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### GetServices

`func (o *Instance) GetServices() InstanceServices`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *Instance) GetServicesOk() (*InstanceServices, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *Instance) SetServices(v InstanceServices)`

SetServices sets Services field to given value.

### HasServices

`func (o *Instance) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetPanicked

`func (o *Instance) GetPanicked() bool`

GetPanicked returns the Panicked field if non-nil, zero value otherwise.

### GetPanickedOk

`func (o *Instance) GetPanickedOk() (*bool, bool)`

GetPanickedOk returns a tuple with the Panicked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPanicked

`func (o *Instance) SetPanicked(v bool)`

SetPanicked sets Panicked field to given value.

### HasPanicked

`func (o *Instance) HasPanicked() bool`

HasPanicked returns a boolean if a field has been set.

### GetCreated

`func (o *Instance) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *Instance) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *Instance) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetModel

`func (o *Instance) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Instance) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Instance) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *Instance) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetFwPackage

`func (o *Instance) GetFwPackage() string`

GetFwPackage returns the FwPackage field if non-nil, zero value otherwise.

### GetFwPackageOk

`func (o *Instance) GetFwPackageOk() (*string, bool)`

GetFwPackageOk returns a tuple with the FwPackage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFwPackage

`func (o *Instance) SetFwPackage(v string)`

SetFwPackage sets FwPackage field to given value.

### HasFwPackage

`func (o *Instance) HasFwPackage() bool`

HasFwPackage returns a boolean if a field has been set.

### GetOsVersion

`func (o *Instance) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *Instance) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *Instance) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.

### HasOsVersion

`func (o *Instance) HasOsVersion() bool`

HasOsVersion returns a boolean if a field has been set.

### GetOsBuild

`func (o *Instance) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *Instance) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *Instance) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.

### HasOsBuild

`func (o *Instance) HasOsBuild() bool`

HasOsBuild returns a boolean if a field has been set.

### GetAgent

`func (o *Instance) GetAgent() InstanceAgentState`

GetAgent returns the Agent field if non-nil, zero value otherwise.

### GetAgentOk

`func (o *Instance) GetAgentOk() (*InstanceAgentState, bool)`

GetAgentOk returns a tuple with the Agent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgent

`func (o *Instance) SetAgent(v InstanceAgentState)`

SetAgent sets Agent field to given value.

### HasAgent

`func (o *Instance) HasAgent() bool`

HasAgent returns a boolean if a field has been set.

### SetAgentNil

`func (o *Instance) SetAgentNil(b bool)`

 SetAgentNil sets the value for Agent to be an explicit nil

### UnsetAgent
`func (o *Instance) UnsetAgent()`

UnsetAgent ensures that no value is present for Agent, not even an explicit nil
### GetNetMon

`func (o *Instance) GetNetMon() InstanceNetmonState`

GetNetMon returns the NetMon field if non-nil, zero value otherwise.

### GetNetMonOk

`func (o *Instance) GetNetMonOk() (*InstanceNetmonState, bool)`

GetNetMonOk returns a tuple with the NetMon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetMon

`func (o *Instance) SetNetMon(v InstanceNetmonState)`

SetNetMon sets NetMon field to given value.

### HasNetMon

`func (o *Instance) HasNetMon() bool`

HasNetMon returns a boolean if a field has been set.

### GetNetDump

`func (o *Instance) GetNetDump() InstanceNetdumpState`

GetNetDump returns the NetDump field if non-nil, zero value otherwise.

### GetNetDumpOk

`func (o *Instance) GetNetDumpOk() (*InstanceNetdumpState, bool)`

GetNetDumpOk returns a tuple with the NetDump field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetDump

`func (o *Instance) SetNetDump(v InstanceNetdumpState)`

SetNetDump sets NetDump field to given value.

### HasNetDump

`func (o *Instance) HasNetDump() bool`

HasNetDump returns a boolean if a field has been set.

### GetCoreTrace

`func (o *Instance) GetCoreTrace() InstanceTraceState`

GetCoreTrace returns the CoreTrace field if non-nil, zero value otherwise.

### GetCoreTraceOk

`func (o *Instance) GetCoreTraceOk() (*InstanceTraceState, bool)`

GetCoreTraceOk returns a tuple with the CoreTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoreTrace

`func (o *Instance) SetCoreTrace(v InstanceTraceState)`

SetCoreTrace sets CoreTrace field to given value.

### HasCoreTrace

`func (o *Instance) HasCoreTrace() bool`

HasCoreTrace returns a boolean if a field has been set.

### GetHyperTrace

`func (o *Instance) GetHyperTrace() InstanceHyperTraceState`

GetHyperTrace returns the HyperTrace field if non-nil, zero value otherwise.

### GetHyperTraceOk

`func (o *Instance) GetHyperTraceOk() (*InstanceHyperTraceState, bool)`

GetHyperTraceOk returns a tuple with the HyperTrace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHyperTrace

`func (o *Instance) SetHyperTrace(v InstanceHyperTraceState)`

SetHyperTrace sets HyperTrace field to given value.

### HasHyperTrace

`func (o *Instance) HasHyperTrace() bool`

HasHyperTrace returns a boolean if a field has been set.

### GetExposePort

`func (o *Instance) GetExposePort() string`

GetExposePort returns the ExposePort field if non-nil, zero value otherwise.

### GetExposePortOk

`func (o *Instance) GetExposePortOk() (*string, bool)`

GetExposePortOk returns a tuple with the ExposePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExposePort

`func (o *Instance) SetExposePort(v string)`

SetExposePort sets ExposePort field to given value.

### HasExposePort

`func (o *Instance) HasExposePort() bool`

HasExposePort returns a boolean if a field has been set.

### SetExposePortNil

`func (o *Instance) SetExposePortNil(b bool)`

 SetExposePortNil sets the value for ExposePort to be an explicit nil

### UnsetExposePort
`func (o *Instance) UnsetExposePort()`

UnsetExposePort ensures that no value is present for ExposePort, not even an explicit nil
### GetFault

`func (o *Instance) GetFault() bool`

GetFault returns the Fault field if non-nil, zero value otherwise.

### GetFaultOk

`func (o *Instance) GetFaultOk() (*bool, bool)`

GetFaultOk returns a tuple with the Fault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFault

`func (o *Instance) SetFault(v bool)`

SetFault sets Fault field to given value.

### HasFault

`func (o *Instance) HasFault() bool`

HasFault returns a boolean if a field has been set.

### SetFaultNil

`func (o *Instance) SetFaultNil(b bool)`

 SetFaultNil sets the value for Fault to be an explicit nil

### UnsetFault
`func (o *Instance) UnsetFault()`

UnsetFault ensures that no value is present for Fault, not even an explicit nil
### GetPatches

`func (o *Instance) GetPatches() []string`

GetPatches returns the Patches field if non-nil, zero value otherwise.

### GetPatchesOk

`func (o *Instance) GetPatchesOk() (*[]string, bool)`

GetPatchesOk returns a tuple with the Patches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatches

`func (o *Instance) SetPatches(v []string)`

SetPatches sets Patches field to given value.

### HasPatches

`func (o *Instance) HasPatches() bool`

HasPatches returns a boolean if a field has been set.

### GetCreatedBy

`func (o *Instance) GetCreatedBy() CreatedBy`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *Instance) GetCreatedByOk() (*CreatedBy, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *Instance) SetCreatedBy(v CreatedBy)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *Instance) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *Instance) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *Instance) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetUefiBootloader

`func (o *Instance) GetUefiBootloader() InstanceUefiBootloader`

GetUefiBootloader returns the UefiBootloader field if non-nil, zero value otherwise.

### GetUefiBootloaderOk

`func (o *Instance) GetUefiBootloaderOk() (*InstanceUefiBootloader, bool)`

GetUefiBootloaderOk returns a tuple with the UefiBootloader field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUefiBootloader

`func (o *Instance) SetUefiBootloader(v InstanceUefiBootloader)`

SetUefiBootloader sets UefiBootloader field to given value.

### HasUefiBootloader

`func (o *Instance) HasUefiBootloader() bool`

HasUefiBootloader returns a boolean if a field has been set.

### GetOrientation

`func (o *Instance) GetOrientation() float32`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *Instance) GetOrientationOk() (*float32, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *Instance) SetOrientation(v float32)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *Instance) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### GetMast

`func (o *Instance) GetMast() bool`

GetMast returns the Mast field if non-nil, zero value otherwise.

### GetMastOk

`func (o *Instance) GetMastOk() (*bool, bool)`

GetMastOk returns a tuple with the Mast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMast

`func (o *Instance) SetMast(v bool)`

SetMast sets Mast field to given value.

### HasMast

`func (o *Instance) HasMast() bool`

HasMast returns a boolean if a field has been set.

### GetWanAccess

`func (o *Instance) GetWanAccess() bool`

GetWanAccess returns the WanAccess field if non-nil, zero value otherwise.

### GetWanAccessOk

`func (o *Instance) GetWanAccessOk() (*bool, bool)`

GetWanAccessOk returns a tuple with the WanAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWanAccess

`func (o *Instance) SetWanAccess(v bool)`

SetWanAccess sets WanAccess field to given value.

### HasWanAccess

`func (o *Instance) HasWanAccess() bool`

HasWanAccess returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


