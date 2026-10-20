# Interconnect

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A name to recognise the interconnect by. | 
**Type** | **string** | How the interconnect behaves: &#x60;hub&#x60; passes every signal to every connected interface; &#x60;switch&#x60; routes traffic between endpoints. | 
**ProjectId** | **string** | Project the interconnect belongs to. Every device listed in &#x60;interfaces&#x60; must be in this project, otherwise the request fails with 400. Cannot be changed later. | 
**Interfaces** | [**[]InterfacesSchemaInner**](InterfacesSchemaInner.md) |  | 
**Id** | **string** | The interconnect identifier. | 
**Protocol** | **string** | The protocol used by the interconnect. | 
**Status** | **string** | The current status of the interconnect. | 
**InstanceCount** | **float32** | Number of unique instances connected to this interconnect. | 
**CreatedAt** | **time.Time** | Creation timestamp. | 
**UpdatedAt** | **time.Time** | Last update timestamp. | 

## Methods

### NewInterconnect

`func NewInterconnect(name string, type_ string, projectId string, interfaces []InterfacesSchemaInner, id string, protocol string, status string, instanceCount float32, createdAt time.Time, updatedAt time.Time, ) *Interconnect`

NewInterconnect instantiates a new Interconnect object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInterconnectWithDefaults

`func NewInterconnectWithDefaults() *Interconnect`

NewInterconnectWithDefaults instantiates a new Interconnect object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Interconnect) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Interconnect) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Interconnect) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *Interconnect) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Interconnect) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Interconnect) SetType(v string)`

SetType sets Type field to given value.


### GetProjectId

`func (o *Interconnect) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Interconnect) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Interconnect) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetInterfaces

`func (o *Interconnect) GetInterfaces() []InterfacesSchemaInner`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *Interconnect) GetInterfacesOk() (*[]InterfacesSchemaInner, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *Interconnect) SetInterfaces(v []InterfacesSchemaInner)`

SetInterfaces sets Interfaces field to given value.


### GetId

`func (o *Interconnect) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Interconnect) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Interconnect) SetId(v string)`

SetId sets Id field to given value.


### GetProtocol

`func (o *Interconnect) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *Interconnect) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *Interconnect) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.


### GetStatus

`func (o *Interconnect) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Interconnect) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Interconnect) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetInstanceCount

`func (o *Interconnect) GetInstanceCount() float32`

GetInstanceCount returns the InstanceCount field if non-nil, zero value otherwise.

### GetInstanceCountOk

`func (o *Interconnect) GetInstanceCountOk() (*float32, bool)`

GetInstanceCountOk returns a tuple with the InstanceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceCount

`func (o *Interconnect) SetInstanceCount(v float32)`

SetInstanceCount sets InstanceCount field to given value.


### GetCreatedAt

`func (o *Interconnect) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Interconnect) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Interconnect) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Interconnect) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Interconnect) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Interconnect) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


