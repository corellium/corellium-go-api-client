# PatchInstanceBodyProxyInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DevicePort** | **float32** | The device port to use for proxying. | 
**FirstAvailable** | **bool** | Use the first available port if devicePort is unavailable. | 
**Expose** | **bool** | Expose the proxy to the external interface. | 
**RouterPort** | **float32** | The router port to use for proxying. | 

## Methods

### NewPatchInstanceBodyProxyInner

`func NewPatchInstanceBodyProxyInner(devicePort float32, firstAvailable bool, expose bool, routerPort float32, ) *PatchInstanceBodyProxyInner`

NewPatchInstanceBodyProxyInner instantiates a new PatchInstanceBodyProxyInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchInstanceBodyProxyInnerWithDefaults

`func NewPatchInstanceBodyProxyInnerWithDefaults() *PatchInstanceBodyProxyInner`

NewPatchInstanceBodyProxyInnerWithDefaults instantiates a new PatchInstanceBodyProxyInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDevicePort

`func (o *PatchInstanceBodyProxyInner) GetDevicePort() float32`

GetDevicePort returns the DevicePort field if non-nil, zero value otherwise.

### GetDevicePortOk

`func (o *PatchInstanceBodyProxyInner) GetDevicePortOk() (*float32, bool)`

GetDevicePortOk returns a tuple with the DevicePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevicePort

`func (o *PatchInstanceBodyProxyInner) SetDevicePort(v float32)`

SetDevicePort sets DevicePort field to given value.


### GetFirstAvailable

`func (o *PatchInstanceBodyProxyInner) GetFirstAvailable() bool`

GetFirstAvailable returns the FirstAvailable field if non-nil, zero value otherwise.

### GetFirstAvailableOk

`func (o *PatchInstanceBodyProxyInner) GetFirstAvailableOk() (*bool, bool)`

GetFirstAvailableOk returns a tuple with the FirstAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstAvailable

`func (o *PatchInstanceBodyProxyInner) SetFirstAvailable(v bool)`

SetFirstAvailable sets FirstAvailable field to given value.


### GetExpose

`func (o *PatchInstanceBodyProxyInner) GetExpose() bool`

GetExpose returns the Expose field if non-nil, zero value otherwise.

### GetExposeOk

`func (o *PatchInstanceBodyProxyInner) GetExposeOk() (*bool, bool)`

GetExposeOk returns a tuple with the Expose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpose

`func (o *PatchInstanceBodyProxyInner) SetExpose(v bool)`

SetExpose sets Expose field to given value.


### GetRouterPort

`func (o *PatchInstanceBodyProxyInner) GetRouterPort() float32`

GetRouterPort returns the RouterPort field if non-nil, zero value otherwise.

### GetRouterPortOk

`func (o *PatchInstanceBodyProxyInner) GetRouterPortOk() (*float32, bool)`

GetRouterPortOk returns a tuple with the RouterPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouterPort

`func (o *PatchInstanceBodyProxyInner) SetRouterPort(v float32)`

SetRouterPort sets RouterPort field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


