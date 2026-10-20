# PatchInstanceBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The name of the device. | [optional] 
**BootOptions** | Pointer to [**InstanceBootOptions**](InstanceBootOptions.md) | The desired boot options. | [optional] 
**Proxy** | Pointer to [**[]PatchInstanceBodyProxyInner**](PatchInstanceBodyProxyInner.md) | Port proxy configurations for the instance. | [optional] 
**StraceFilter** | Pointer to [**[]PatchInstanceBodyStraceFilterInner**](PatchInstanceBodyStraceFilterInner.md) | CoreTrace process filter. | [optional] 

## Methods

### NewPatchInstanceBody

`func NewPatchInstanceBody() *PatchInstanceBody`

NewPatchInstanceBody instantiates a new PatchInstanceBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchInstanceBodyWithDefaults

`func NewPatchInstanceBodyWithDefaults() *PatchInstanceBody`

NewPatchInstanceBodyWithDefaults instantiates a new PatchInstanceBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PatchInstanceBody) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PatchInstanceBody) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PatchInstanceBody) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PatchInstanceBody) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBootOptions

`func (o *PatchInstanceBody) GetBootOptions() InstanceBootOptions`

GetBootOptions returns the BootOptions field if non-nil, zero value otherwise.

### GetBootOptionsOk

`func (o *PatchInstanceBody) GetBootOptionsOk() (*InstanceBootOptions, bool)`

GetBootOptionsOk returns a tuple with the BootOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBootOptions

`func (o *PatchInstanceBody) SetBootOptions(v InstanceBootOptions)`

SetBootOptions sets BootOptions field to given value.

### HasBootOptions

`func (o *PatchInstanceBody) HasBootOptions() bool`

HasBootOptions returns a boolean if a field has been set.

### GetProxy

`func (o *PatchInstanceBody) GetProxy() []PatchInstanceBodyProxyInner`

GetProxy returns the Proxy field if non-nil, zero value otherwise.

### GetProxyOk

`func (o *PatchInstanceBody) GetProxyOk() (*[]PatchInstanceBodyProxyInner, bool)`

GetProxyOk returns a tuple with the Proxy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProxy

`func (o *PatchInstanceBody) SetProxy(v []PatchInstanceBodyProxyInner)`

SetProxy sets Proxy field to given value.

### HasProxy

`func (o *PatchInstanceBody) HasProxy() bool`

HasProxy returns a boolean if a field has been set.

### GetStraceFilter

`func (o *PatchInstanceBody) GetStraceFilter() []PatchInstanceBodyStraceFilterInner`

GetStraceFilter returns the StraceFilter field if non-nil, zero value otherwise.

### GetStraceFilterOk

`func (o *PatchInstanceBody) GetStraceFilterOk() (*[]PatchInstanceBodyStraceFilterInner, bool)`

GetStraceFilterOk returns a tuple with the StraceFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStraceFilter

`func (o *PatchInstanceBody) SetStraceFilter(v []PatchInstanceBodyStraceFilterInner)`

SetStraceFilter sets StraceFilter field to given value.

### HasStraceFilter

`func (o *PatchInstanceBody) HasStraceFilter() bool`

HasStraceFilter returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


