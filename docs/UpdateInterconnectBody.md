# UpdateInterconnectBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the interconnect | 
**Interfaces** | **[]map[string]interface{}** | Array of interfaces with deviceId and interfaceId | 

## Methods

### NewUpdateInterconnectBody

`func NewUpdateInterconnectBody(name string, interfaces []map[string]interface{}, ) *UpdateInterconnectBody`

NewUpdateInterconnectBody instantiates a new UpdateInterconnectBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateInterconnectBodyWithDefaults

`func NewUpdateInterconnectBodyWithDefaults() *UpdateInterconnectBody`

NewUpdateInterconnectBodyWithDefaults instantiates a new UpdateInterconnectBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateInterconnectBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateInterconnectBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateInterconnectBody) SetName(v string)`

SetName sets Name field to given value.


### GetInterfaces

`func (o *UpdateInterconnectBody) GetInterfaces() []map[string]interface{}`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *UpdateInterconnectBody) GetInterfacesOk() (*[]map[string]interface{}, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *UpdateInterconnectBody) SetInterfaces(v []map[string]interface{})`

SetInterfaces sets Interfaces field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


