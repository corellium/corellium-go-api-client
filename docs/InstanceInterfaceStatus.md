# InstanceInterfaceStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterfaceId** | **string** | Interface identifier. | 
**InterconnectId** | Pointer to **string** | Interconnect identifier when the interface is attached. | [optional] 
**Status** | **string** | Current interface attachment status. | 

## Methods

### NewInstanceInterfaceStatus

`func NewInstanceInterfaceStatus(interfaceId string, status string, ) *InstanceInterfaceStatus`

NewInstanceInterfaceStatus instantiates a new InstanceInterfaceStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceInterfaceStatusWithDefaults

`func NewInstanceInterfaceStatusWithDefaults() *InstanceInterfaceStatus`

NewInstanceInterfaceStatusWithDefaults instantiates a new InstanceInterfaceStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterfaceId

`func (o *InstanceInterfaceStatus) GetInterfaceId() string`

GetInterfaceId returns the InterfaceId field if non-nil, zero value otherwise.

### GetInterfaceIdOk

`func (o *InstanceInterfaceStatus) GetInterfaceIdOk() (*string, bool)`

GetInterfaceIdOk returns a tuple with the InterfaceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaceId

`func (o *InstanceInterfaceStatus) SetInterfaceId(v string)`

SetInterfaceId sets InterfaceId field to given value.


### GetInterconnectId

`func (o *InstanceInterfaceStatus) GetInterconnectId() string`

GetInterconnectId returns the InterconnectId field if non-nil, zero value otherwise.

### GetInterconnectIdOk

`func (o *InstanceInterfaceStatus) GetInterconnectIdOk() (*string, bool)`

GetInterconnectIdOk returns a tuple with the InterconnectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterconnectId

`func (o *InstanceInterfaceStatus) SetInterconnectId(v string)`

SetInterconnectId sets InterconnectId field to given value.

### HasInterconnectId

`func (o *InstanceInterfaceStatus) HasInterconnectId() bool`

HasInterconnectId returns a boolean if a field has been set.

### GetStatus

`func (o *InstanceInterfaceStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InstanceInterfaceStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InstanceInterfaceStatus) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


