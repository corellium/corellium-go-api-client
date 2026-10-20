# CreateInterconnectBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the interconnect | 
**Protocol** | **string** | The protocol used by the interconnect | 
**Type** | **string** | The type of interconnect | 
**Project** | **string** | The UUID of the project | 
**Interfaces** | **[]string** | Array of instance identifiers | 

## Methods

### NewCreateInterconnectBody

`func NewCreateInterconnectBody(name string, protocol string, type_ string, project string, interfaces []string, ) *CreateInterconnectBody`

NewCreateInterconnectBody instantiates a new CreateInterconnectBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInterconnectBodyWithDefaults

`func NewCreateInterconnectBodyWithDefaults() *CreateInterconnectBody`

NewCreateInterconnectBodyWithDefaults instantiates a new CreateInterconnectBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateInterconnectBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateInterconnectBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateInterconnectBody) SetName(v string)`

SetName sets Name field to given value.


### GetProtocol

`func (o *CreateInterconnectBody) GetProtocol() string`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *CreateInterconnectBody) GetProtocolOk() (*string, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *CreateInterconnectBody) SetProtocol(v string)`

SetProtocol sets Protocol field to given value.


### GetType

`func (o *CreateInterconnectBody) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateInterconnectBody) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateInterconnectBody) SetType(v string)`

SetType sets Type field to given value.


### GetProject

`func (o *CreateInterconnectBody) GetProject() string`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *CreateInterconnectBody) GetProjectOk() (*string, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *CreateInterconnectBody) SetProject(v string)`

SetProject sets Project field to given value.


### GetInterfaces

`func (o *CreateInterconnectBody) GetInterfaces() []string`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *CreateInterconnectBody) GetInterfacesOk() (*[]string, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *CreateInterconnectBody) SetInterfaces(v []string)`

SetInterfaces sets Interfaces field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


