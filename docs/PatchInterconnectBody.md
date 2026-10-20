# PatchInterconnectBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | A name to recognise the interconnect by. | [optional] 
**Interfaces** | Pointer to [**[]InterfacesSchemaInner**](InterfacesSchemaInner.md) |  | [optional] 

## Methods

### NewPatchInterconnectBody

`func NewPatchInterconnectBody() *PatchInterconnectBody`

NewPatchInterconnectBody instantiates a new PatchInterconnectBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchInterconnectBodyWithDefaults

`func NewPatchInterconnectBodyWithDefaults() *PatchInterconnectBody`

NewPatchInterconnectBodyWithDefaults instantiates a new PatchInterconnectBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchInterconnectBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchInterconnectBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchInterconnectBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchInterconnectBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetInterfaces

`func (o *PatchInterconnectBody) GetInterfaces() []InterfacesSchemaInner`

GetInterfaces returns the Interfaces field if non-nil, zero value otherwise.

### GetInterfacesOk

`func (o *PatchInterconnectBody) GetInterfacesOk() (*[]InterfacesSchemaInner, bool)`

GetInterfacesOk returns a tuple with the Interfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterfaces

`func (o *PatchInterconnectBody) SetInterfaces(v []InterfacesSchemaInner)`

SetInterfaces sets Interfaces field to given value.

### HasInterfaces

`func (o *PatchInterconnectBody) HasInterfaces() bool`

HasInterfaces returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


