# UpdateInterconnectV3Body

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A name to recognise the interconnect by. | 
**Interfaces** | [**[]InterfacesSchemaInner**](InterfacesSchemaInner.md) |  | 
**Type** | Pointer to **string** | How the interconnect behaves: &#x60;hub&#x60; passes every signal to every connected interface; &#x60;switch&#x60; routes traffic between endpoints. | [optional] 
**ProjectId** | Pointer to **string** | Project the interconnect belongs to. Every device listed in &#x60;interfaces&#x60; must be in this project, otherwise the request fails with 400. Cannot be changed later. | [optional] 
**Protocol** | Pointer to [**InterconnectProtocol**](InterconnectProtocol.md) |  | [optional] 

## Methods

### NewUpdateInterconnectV3Body

`func NewUpdateInterconnectV3Body(name string, interfaces []InterfacesSchemaInner, ) *UpdateInterconnectV3Body`

NewUpdateInterconnectV3Body instantiates a new UpdateInterconnectV3Body object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateInterconnectV3BodyWithDefaults

`func NewUpdateInterconnectV3BodyWithDefaults() *UpdateInterconnectV3Body`

NewUpdateInterconnectV3BodyWithDefaults instantiates a new UpdateInterconnectV3Body object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateInterconnectV3Body) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateInterconnectV3Body) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateInterconnectV3Body) SetName(v string)`

SetName sets Name field to given value.


### GetInterfaces

`func (o *UpdateInterconnectV3Body) GetInterfaces() []InterfacesSchemaInner`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *UpdateInterconnectV3Body) GetInterfacesOk() (*[]InterfacesSchemaInner, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *UpdateInterconnectV3Body) SetInterfaces(v []InterfacesSchemaInner)`

SetInterfaces sets Interfaces field to given value.


### GetType

`func (o *UpdateInterconnectV3Body) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *UpdateInterconnectV3Body) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *UpdateInterconnectV3Body) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *UpdateInterconnectV3Body) HasType() bool`

HasType returns a boolean if a field has been set.

### GetProjectId

`func (o *UpdateInterconnectV3Body) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateInterconnectV3Body) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateInterconnectV3Body) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *UpdateInterconnectV3Body) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetProtocol

`func (o *UpdateInterconnectV3Body) GetProtocol() InterconnectProtocol`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *UpdateInterconnectV3Body) GetProtocolOk() (*InterconnectProtocol, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *UpdateInterconnectV3Body) SetProtocol(v InterconnectProtocol)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *UpdateInterconnectV3Body) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


