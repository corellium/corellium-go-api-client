# AttachInterfaceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterfaceId** | **string** | Which of the device&#39;s I/O interfaces to connect, for example &#x60;gpio/0&#x60;. | 
**InterconnectId** | **string** | Interconnect identifier. | 

## Methods

### NewAttachInterfaceBody

`func NewAttachInterfaceBody(interfaceId string, interconnectId string, ) *AttachInterfaceBody`

NewAttachInterfaceBody instantiates a new AttachInterfaceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachInterfaceBodyWithDefaults

`func NewAttachInterfaceBodyWithDefaults() *AttachInterfaceBody`

NewAttachInterfaceBodyWithDefaults instantiates a new AttachInterfaceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaceId

`func (o *AttachInterfaceBody) GetInterfaceId() string`

GetInterfaceId returns the InterfaceId field if non-nil, zero value otherwise.

### GetInterfaceIdOk

`func (o *AttachInterfaceBody) GetInterfaceIdOk() (*string, bool)`

GetInterfaceIdOk returns a tuple with the InterfaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceId

`func (o *AttachInterfaceBody) SetInterfaceId(v string)`

SetInterfaceId sets InterfaceId field to given value.


### GetInterconnectId

`func (o *AttachInterfaceBody) GetInterconnectId() string`

GetInterconnectId returns the InterconnectId field if non-nil, zero value otherwise.

### GetInterconnectIdOk

`func (o *AttachInterfaceBody) GetInterconnectIdOk() (*string, bool)`

GetInterconnectIdOk returns a tuple with the InterconnectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterconnectId

`func (o *AttachInterfaceBody) SetInterconnectId(v string)`

SetInterconnectId sets InterconnectId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


