# PartialUpdateInterconnectRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** | The name of the interconnect (optional) | [optional] 
**Interfaces** | Pointer to **[]map[string]interface{}** | Array of interfaces with deviceId and interfaceId (optional) | [optional] 

## Methods

### NewPartialUpdateInterconnectRequest

`func NewPartialUpdateInterconnectRequest() *PartialUpdateInterconnectRequest`

NewPartialUpdateInterconnectRequest instantiates a new PartialUpdateInterconnectRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartialUpdateInterconnectRequestWithDefaults

`func NewPartialUpdateInterconnectRequestWithDefaults() *PartialUpdateInterconnectRequest`

NewPartialUpdateInterconnectRequestWithDefaults instantiates a new PartialUpdateInterconnectRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PartialUpdateInterconnectRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartialUpdateInterconnectRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartialUpdateInterconnectRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PartialUpdateInterconnectRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *PartialUpdateInterconnectRequest) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PartialUpdateInterconnectRequest) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetInterfaces

`func (o *PartialUpdateInterconnectRequest) GetInterfaces() []map[string]interface{}`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *PartialUpdateInterconnectRequest) GetInterfacesOk() (*[]map[string]interface{}, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *PartialUpdateInterconnectRequest) SetInterfaces(v []map[string]interface{})`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *PartialUpdateInterconnectRequest) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### SetInterfacesNil

`func (o *PartialUpdateInterconnectRequest) SetInterfacesNil(b bool)`

 SetInterfacesNil sets the value for Interfaces to be an explicit nil

### UnsetInterfaces
`func (o *PartialUpdateInterconnectRequest) UnsetInterfaces()`

UnsetInterfaces ensures that no value is present for Interfaces, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


