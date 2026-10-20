# DomainListItemProjectsInnerInstancesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Instance identifier. | 
**Name** | Pointer to **string** | Instance name. | [optional] 
**Status** | **string** | Instance status (ACTIVE, SHUTOFF, etc.). | 
**Error** | **NullableString** | Error message if any. | 
**TaskState** | **string** | Current task state. | 
**UserTask** | **NullableString** | User-initiated task. | 
**OsVersion** | **string** | OS version. | 
**OsBuild** | **string** | OS build identifier. | 
**FlavorId** | **string** | Device flavor identifier. | 
**Flavor** | Pointer to **string** | Friendly device flavor name. | [optional] 
**ComputeNode** | **NullableString** | Compute node address. | 
**ServiceIp** | **NullableString** | Service IP address. | 
**WifiIp** | **NullableString** | WiFi IP address. | 
**Images** | [**[]DomainListItemProjectsInnerInstancesInnerImagesInner**](DomainListItemProjectsInnerInstancesInnerImagesInner.md) | List of images. | 
**Usage** | [**DomainListItemProjectsInnerInstancesInnerUsage**](DomainListItemProjectsInnerInstancesInnerUsage.md) |  | 

## Methods

### NewDomainListItemProjectsInnerInstancesInner

`func NewDomainListItemProjectsInnerInstancesInner(identifier string, status string, error_ NullableString, taskState string, userTask NullableString, osVersion string, osBuild string, flavorId string, computeNode NullableString, serviceIp NullableString, wifiIp NullableString, images []DomainListItemProjectsInnerInstancesInnerImagesInner, usage DomainListItemProjectsInnerInstancesInnerUsage, ) *DomainListItemProjectsInnerInstancesInner`

NewDomainListItemProjectsInnerInstancesInner instantiates a new DomainListItemProjectsInnerInstancesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainListItemProjectsInnerInstancesInnerWithDefaults

`func NewDomainListItemProjectsInnerInstancesInnerWithDefaults() *DomainListItemProjectsInnerInstancesInner`

NewDomainListItemProjectsInnerInstancesInnerWithDefaults instantiates a new DomainListItemProjectsInnerInstancesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DomainListItemProjectsInnerInstancesInner) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DomainListItemProjectsInnerInstancesInner) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetName

`func (o *DomainListItemProjectsInnerInstancesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainListItemProjectsInnerInstancesInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DomainListItemProjectsInnerInstancesInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetStatus

`func (o *DomainListItemProjectsInnerInstancesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DomainListItemProjectsInnerInstancesInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetError

`func (o *DomainListItemProjectsInnerInstancesInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DomainListItemProjectsInnerInstancesInner) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *DomainListItemProjectsInnerInstancesInner) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *DomainListItemProjectsInnerInstancesInner) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetTaskState

`func (o *DomainListItemProjectsInnerInstancesInner) GetTaskState() string`

GetTaskState returns the TaskState field if non-nil, zero value otherwise.

### GetTaskStateOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetTaskStateOk() (*string, bool)`

GetTaskStateOk returns a tuple with the TaskState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskState

`func (o *DomainListItemProjectsInnerInstancesInner) SetTaskState(v string)`

SetTaskState sets TaskState field to given value.


### GetUserTask

`func (o *DomainListItemProjectsInnerInstancesInner) GetUserTask() string`

GetUserTask returns the UserTask field if non-nil, zero value otherwise.

### GetUserTaskOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetUserTaskOk() (*string, bool)`

GetUserTaskOk returns a tuple with the UserTask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserTask

`func (o *DomainListItemProjectsInnerInstancesInner) SetUserTask(v string)`

SetUserTask sets UserTask field to given value.


### SetUserTaskNil

`func (o *DomainListItemProjectsInnerInstancesInner) SetUserTaskNil(b bool)`

 SetUserTaskNil sets the value for UserTask to be an explicit nil

### UnsetUserTask
`func (o *DomainListItemProjectsInnerInstancesInner) UnsetUserTask()`

UnsetUserTask ensures that no value is present for UserTask, not even an explicit nil
### GetOsVersion

`func (o *DomainListItemProjectsInnerInstancesInner) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *DomainListItemProjectsInnerInstancesInner) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.


### GetOsBuild

`func (o *DomainListItemProjectsInnerInstancesInner) GetOsBuild() string`

GetOsBuild returns the OsBuild field if non-nil, zero value otherwise.

### GetOsBuildOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetOsBuildOk() (*string, bool)`

GetOsBuildOk returns a tuple with the OsBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsBuild

`func (o *DomainListItemProjectsInnerInstancesInner) SetOsBuild(v string)`

SetOsBuild sets OsBuild field to given value.


### GetFlavorId

`func (o *DomainListItemProjectsInnerInstancesInner) GetFlavorId() string`

GetFlavorId returns the FlavorId field if non-nil, zero value otherwise.

### GetFlavorIdOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetFlavorIdOk() (*string, bool)`

GetFlavorIdOk returns a tuple with the FlavorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavorId

`func (o *DomainListItemProjectsInnerInstancesInner) SetFlavorId(v string)`

SetFlavorId sets FlavorId field to given value.


### GetFlavor

`func (o *DomainListItemProjectsInnerInstancesInner) GetFlavor() string`

GetFlavor returns the Flavor field if non-nil, zero value otherwise.

### GetFlavorOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetFlavorOk() (*string, bool)`

GetFlavorOk returns a tuple with the Flavor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlavor

`func (o *DomainListItemProjectsInnerInstancesInner) SetFlavor(v string)`

SetFlavor sets Flavor field to given value.

### HasFlavor

`func (o *DomainListItemProjectsInnerInstancesInner) HasFlavor() bool`

HasFlavor returns a boolean if a field has been set.

### GetComputeNode

`func (o *DomainListItemProjectsInnerInstancesInner) GetComputeNode() string`

GetComputeNode returns the ComputeNode field if non-nil, zero value otherwise.

### GetComputeNodeOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetComputeNodeOk() (*string, bool)`

GetComputeNodeOk returns a tuple with the ComputeNode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputeNode

`func (o *DomainListItemProjectsInnerInstancesInner) SetComputeNode(v string)`

SetComputeNode sets ComputeNode field to given value.


### SetComputeNodeNil

`func (o *DomainListItemProjectsInnerInstancesInner) SetComputeNodeNil(b bool)`

 SetComputeNodeNil sets the value for ComputeNode to be an explicit nil

### UnsetComputeNode
`func (o *DomainListItemProjectsInnerInstancesInner) UnsetComputeNode()`

UnsetComputeNode ensures that no value is present for ComputeNode, not even an explicit nil
### GetServiceIp

`func (o *DomainListItemProjectsInnerInstancesInner) GetServiceIp() string`

GetServiceIp returns the ServiceIp field if non-nil, zero value otherwise.

### GetServiceIpOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetServiceIpOk() (*string, bool)`

GetServiceIpOk returns a tuple with the ServiceIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceIp

`func (o *DomainListItemProjectsInnerInstancesInner) SetServiceIp(v string)`

SetServiceIp sets ServiceIp field to given value.


### SetServiceIpNil

`func (o *DomainListItemProjectsInnerInstancesInner) SetServiceIpNil(b bool)`

 SetServiceIpNil sets the value for ServiceIp to be an explicit nil

### UnsetServiceIp
`func (o *DomainListItemProjectsInnerInstancesInner) UnsetServiceIp()`

UnsetServiceIp ensures that no value is present for ServiceIp, not even an explicit nil
### GetWifiIp

`func (o *DomainListItemProjectsInnerInstancesInner) GetWifiIp() string`

GetWifiIp returns the WifiIp field if non-nil, zero value otherwise.

### GetWifiIpOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetWifiIpOk() (*string, bool)`

GetWifiIpOk returns a tuple with the WifiIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWifiIp

`func (o *DomainListItemProjectsInnerInstancesInner) SetWifiIp(v string)`

SetWifiIp sets WifiIp field to given value.


### SetWifiIpNil

`func (o *DomainListItemProjectsInnerInstancesInner) SetWifiIpNil(b bool)`

 SetWifiIpNil sets the value for WifiIp to be an explicit nil

### UnsetWifiIp
`func (o *DomainListItemProjectsInnerInstancesInner) UnsetWifiIp()`

UnsetWifiIp ensures that no value is present for WifiIp, not even an explicit nil
### GetImages

`func (o *DomainListItemProjectsInnerInstancesInner) GetImages() []DomainListItemProjectsInnerInstancesInnerImagesInner`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetImagesOk() (*[]DomainListItemProjectsInnerInstancesInnerImagesInner, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *DomainListItemProjectsInnerInstancesInner) SetImages(v []DomainListItemProjectsInnerInstancesInnerImagesInner)`

SetImages sets Images field to given value.


### GetUsage

`func (o *DomainListItemProjectsInnerInstancesInner) GetUsage() DomainListItemProjectsInnerInstancesInnerUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DomainListItemProjectsInnerInstancesInner) GetUsageOk() (*DomainListItemProjectsInnerInstancesInnerUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DomainListItemProjectsInnerInstancesInner) SetUsage(v DomainListItemProjectsInnerInstancesInnerUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


