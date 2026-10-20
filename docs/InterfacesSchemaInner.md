# InterfacesSchemaInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **string** | ID of the device (instance) whose interface to connect. | 
**InterfaceId** | **string** | Which interface on that device, written &#x60;&lt;name&gt;/&lt;number&gt;&#x60; (for example &#x60;eth0:1/2&#x60; or &#x60;gpio/0&#x60;). The device model decides which interfaces exist. | 

## Methods

### NewInterfacesSchemaInner

`func NewInterfacesSchemaInner(deviceId string, interfaceId string, ) *InterfacesSchemaInner`

NewInterfacesSchemaInner instantiates a new InterfacesSchemaInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInterfacesSchemaInnerWithDefaults

`func NewInterfacesSchemaInnerWithDefaults() *InterfacesSchemaInner`

NewInterfacesSchemaInnerWithDefaults instantiates a new InterfacesSchemaInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *InterfacesSchemaInner) GetDeviceId() string`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *InterfacesSchemaInner) GetDeviceIdOk() (*string, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *InterfacesSchemaInner) SetDeviceId(v string)`

SetDeviceId sets DeviceId field to given value.


### GetInterfaceId

`func (o *InterfacesSchemaInner) GetInterfaceId() string`

GetInterfaceId returns the InterfaceId field if non-nil, zero value otherwise.

### GetInterfaceIdOk

`func (o *InterfacesSchemaInner) GetInterfaceIdOk() (*string, bool)`

GetInterfaceIdOk returns a tuple with the InterfaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceId

`func (o *InterfacesSchemaInner) SetInterfaceId(v string)`

SetInterfaceId sets InterfaceId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


