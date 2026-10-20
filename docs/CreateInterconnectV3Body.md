# CreateInterconnectV3Body

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A name to recognise the interconnect by. | 
**Type** | **string** | How the interconnect behaves: &#x60;hub&#x60; passes every signal to every connected interface; &#x60;switch&#x60; routes traffic between endpoints. | 
**Interfaces** | [**[]InterfacesSchemaInner**](InterfacesSchemaInner.md) |  | 
**ProjectId** | **string** | Project the interconnect belongs to. Every device listed in &#x60;interfaces&#x60; must be in this project, otherwise the request fails with 400. Cannot be changed later. | 
**Protocol** | [**InterconnectProtocol**](InterconnectProtocol.md) |  | 

## Methods

### NewCreateInterconnectV3Body

`func NewCreateInterconnectV3Body(name string, type_ string, interfaces []InterfacesSchemaInner, projectId string, protocol InterconnectProtocol, ) *CreateInterconnectV3Body`

NewCreateInterconnectV3Body instantiates a new CreateInterconnectV3Body object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInterconnectV3BodyWithDefaults

`func NewCreateInterconnectV3BodyWithDefaults() *CreateInterconnectV3Body`

NewCreateInterconnectV3BodyWithDefaults instantiates a new CreateInterconnectV3Body object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateInterconnectV3Body) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateInterconnectV3Body) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateInterconnectV3Body) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *CreateInterconnectV3Body) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateInterconnectV3Body) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateInterconnectV3Body) SetType(v string)`

SetType sets Type field to given value.


### GetInterfaces

`func (o *CreateInterconnectV3Body) GetInterfaces() []InterfacesSchemaInner`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *CreateInterconnectV3Body) GetInterfacesOk() (*[]InterfacesSchemaInner, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *CreateInterconnectV3Body) SetInterfaces(v []InterfacesSchemaInner)`

SetInterfaces sets Interfaces field to given value.


### GetProjectId

`func (o *CreateInterconnectV3Body) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateInterconnectV3Body) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateInterconnectV3Body) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProtocol

`func (o *CreateInterconnectV3Body) GetProtocol() InterconnectProtocol`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *CreateInterconnectV3Body) GetProtocolOk() (*InterconnectProtocol, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *CreateInterconnectV3Body) SetProtocol(v InterconnectProtocol)`

SetProtocol sets Protocol field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


