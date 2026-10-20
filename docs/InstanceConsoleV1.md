# InstanceConsoleV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** | Console display name | [optional] 
**Id** | Pointer to **NullableString** | Console port identifier (e.g. port-cons) | [optional] 
**Port** | Pointer to **NullableFloat32** | TCP port number | [optional] 
**Hash** | Pointer to **NullableString** | Hash for console authentication | [optional] 
**Info** | Pointer to **NullableString** | Encrypted info for console authentication | [optional] 

## Methods

### NewInstanceConsoleV1

`func NewInstanceConsoleV1() *InstanceConsoleV1`

NewInstanceConsoleV1 instantiates a new InstanceConsoleV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstanceConsoleV1WithDefaults

`func NewInstanceConsoleV1WithDefaults() *InstanceConsoleV1`

NewInstanceConsoleV1WithDefaults instantiates a new InstanceConsoleV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *InstanceConsoleV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InstanceConsoleV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InstanceConsoleV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InstanceConsoleV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *InstanceConsoleV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *InstanceConsoleV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetId

`func (o *InstanceConsoleV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InstanceConsoleV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InstanceConsoleV1) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InstanceConsoleV1) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *InstanceConsoleV1) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *InstanceConsoleV1) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetPort

`func (o *InstanceConsoleV1) GetPort() float32`

GetPort returns the Port field if non-nil, zero value otherwise.

### GetPortOk

`func (o *InstanceConsoleV1) GetPortOk() (*float32, bool)`

GetPortOk returns a tuple with the Port field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPort

`func (o *InstanceConsoleV1) SetPort(v float32)`

SetPort sets Port field to given value.

### HasPort

`func (o *InstanceConsoleV1) HasPort() bool`

HasPort returns a boolean if a field has been set.

### SetPortNil

`func (o *InstanceConsoleV1) SetPortNil(b bool)`

 SetPortNil sets the value for Port to be an explicit nil

### UnsetPort
`func (o *InstanceConsoleV1) UnsetPort()`

UnsetPort ensures that no value is present for Port, not even an explicit nil
### GetHash

`func (o *InstanceConsoleV1) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *InstanceConsoleV1) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *InstanceConsoleV1) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *InstanceConsoleV1) HasHash() bool`

HasHash returns a boolean if a field has been set.

### SetHashNil

`func (o *InstanceConsoleV1) SetHashNil(b bool)`

 SetHashNil sets the value for Hash to be an explicit nil

### UnsetHash
`func (o *InstanceConsoleV1) UnsetHash()`

UnsetHash ensures that no value is present for Hash, not even an explicit nil
### GetInfo

`func (o *InstanceConsoleV1) GetInfo() string`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *InstanceConsoleV1) GetInfoOk() (*string, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *InstanceConsoleV1) SetInfo(v string)`

SetInfo sets Info field to given value.

### HasInfo

`func (o *InstanceConsoleV1) HasInfo() bool`

HasInfo returns a boolean if a field has been set.

### SetInfoNil

`func (o *InstanceConsoleV1) SetInfoNil(b bool)`

 SetInfoNil sets the value for Info to be an explicit nil

### UnsetInfo
`func (o *InstanceConsoleV1) UnsetInfo()`

UnsetInfo ensures that no value is present for Info, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


