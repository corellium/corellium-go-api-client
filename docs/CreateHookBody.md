# CreateHookBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Label** | **string** | Hook label. | 
**Address** | **string** | Memory address to hook. | 
**Patch** | **string** | Patch code to execute. | 
**PatchType** | [**HookPatchType**](HookPatchType.md) |  | 
**Enabled** | Pointer to **bool** | Whether the hook is active. | [optional] [default to true]

## Methods

### NewCreateHookBody

`func NewCreateHookBody(label string, address string, patch string, patchType HookPatchType, ) *CreateHookBody`

NewCreateHookBody instantiates a new CreateHookBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateHookBodyWithDefaults

`func NewCreateHookBodyWithDefaults() *CreateHookBody`

NewCreateHookBodyWithDefaults instantiates a new CreateHookBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabel

`func (o *CreateHookBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateHookBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateHookBody) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetAddress

`func (o *CreateHookBody) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *CreateHookBody) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *CreateHookBody) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetPatch

`func (o *CreateHookBody) GetPatch() string`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *CreateHookBody) GetPatchOk() (*string, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *CreateHookBody) SetPatch(v string)`

SetPatch sets Patch field to given value.


### GetPatchType

`func (o *CreateHookBody) GetPatchType() HookPatchType`

GetPatchType returns the PatchType field if non-nil, zero value otherwise.

### GetPatchTypeOk

`func (o *CreateHookBody) GetPatchTypeOk() (*HookPatchType, bool)`

GetPatchTypeOk returns a tuple with the PatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchType

`func (o *CreateHookBody) SetPatchType(v HookPatchType)`

SetPatchType sets PatchType field to given value.


### GetEnabled

`func (o *CreateHookBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateHookBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateHookBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateHookBody) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


