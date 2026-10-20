# InterconnectResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** | The interconnect identifier | [optional] 
**Name** | Pointer to **NullableString** | The name of the interconnect | [optional] 
**Protocol** | Pointer to **NullableString** | The protocol used by the interconnect | [optional] 
**Type** | Pointer to **NullableString** | The type of interconnect | [optional] 
**Project** | Pointer to **NullableString** | The UUID of the project | [optional] 
**Status** | Pointer to **NullableString** | The current status of the interconnect | [optional] 
**Interfaces** | Pointer to [**[]InstanceInterface**](InstanceInterface.md) | Array of instance interfaces | [optional] 
**CreatedAt** | Pointer to **NullableString** | Creation timestamp | [optional] 
**UpdatedAt** | Pointer to **NullableString** | Last update timestamp | [optional] 

## Methods

### NewInterconnectResponse

`func NewInterconnectResponse() *InterconnectResponse`

NewInterconnectResponse instantiates a new InterconnectResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInterconnectResponseWithDefaults

`func NewInterconnectResponseWithDefaults() *InterconnectResponse`

NewInterconnectResponseWithDefaults instantiates a new InterconnectResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InterconnectResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InterconnectResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InterconnectResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *InterconnectResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *InterconnectResponse) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *InterconnectResponse) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetName

`func (o *InterconnectResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InterconnectResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InterconnectResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InterconnectResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *InterconnectResponse) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *InterconnectResponse) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetProtocol

`func (o *InterconnectResponse) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *InterconnectResponse) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *InterconnectResponse) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *InterconnectResponse) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.

### SetProtocolNil

`func (o *InterconnectResponse) SetProtocolNil(b bool)`

 SetProtocolNil sets the value for Protocol to be an explicit nil

### UnsetProtocol
`func (o *InterconnectResponse) UnsetProtocol()`

UnsetProtocol ensures that no value is present for Protocol, not even an explicit nil
### GetType

`func (o *InterconnectResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InterconnectResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InterconnectResponse) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InterconnectResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *InterconnectResponse) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *InterconnectResponse) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetProject

`func (o *InterconnectResponse) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *InterconnectResponse) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *InterconnectResponse) SetProject(v string)`

SetProject sets Project field to given value.

### HasProject

`func (o *InterconnectResponse) HasProject() bool`

HasProject returns a boolean if a field has been set.

### SetProjectNil

`func (o *InterconnectResponse) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *InterconnectResponse) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetStatus

`func (o *InterconnectResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InterconnectResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InterconnectResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InterconnectResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *InterconnectResponse) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *InterconnectResponse) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetInterfaces

`func (o *InterconnectResponse) GetInterfaces() []InstanceInterface`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *InterconnectResponse) GetInterfacesOk() (*[]InstanceInterface, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *InterconnectResponse) SetInterfaces(v []InstanceInterface)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *InterconnectResponse) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.

### SetInterfacesNil

`func (o *InterconnectResponse) SetInterfacesNil(b bool)`

 SetInterfacesNil sets the value for Interfaces to be an explicit nil

### UnsetInterfaces
`func (o *InterconnectResponse) UnsetInterfaces()`

UnsetInterfaces ensures that no value is present for Interfaces, not even an explicit nil
### GetCreatedAt

`func (o *InterconnectResponse) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InterconnectResponse) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InterconnectResponse) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *InterconnectResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *InterconnectResponse) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *InterconnectResponse) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *InterconnectResponse) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *InterconnectResponse) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *InterconnectResponse) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *InterconnectResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *InterconnectResponse) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *InterconnectResponse) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


