# UpdateHookBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Label** | Pointer to **string** | Hook label. | [optional] 
**Address** | Pointer to **string** | Memory address to hook. | [optional] 
**Patch** | Pointer to **string** | Patch code to execute. | [optional] 
**PatchType** | Pointer to [**HookPatchType**](HookPatchType.md) |  | [optional] 
**Enabled** | Pointer to **bool** | Whether the hook is active. | [optional] 

## Methods

### NewUpdateHookBody

`func NewUpdateHookBody() *UpdateHookBody`

NewUpdateHookBody instantiates a new UpdateHookBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateHookBodyWithDefaults

`func NewUpdateHookBodyWithDefaults() *UpdateHookBody`

NewUpdateHookBodyWithDefaults instantiates a new UpdateHookBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabel

`func (o *UpdateHookBody) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *UpdateHookBody) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *UpdateHookBody) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *UpdateHookBody) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetAddress

`func (o *UpdateHookBody) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *UpdateHookBody) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *UpdateHookBody) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *UpdateHookBody) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetPatch

`func (o *UpdateHookBody) GetPatch() string`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *UpdateHookBody) GetPatchOk() (*string, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *UpdateHookBody) SetPatch(v string)`

SetPatch sets Patch field to given value.

### HasPatch

`func (o *UpdateHookBody) HasPatch() bool`

HasPatch returns a boolean if a field has been set.

### GetPatchType

`func (o *UpdateHookBody) GetPatchType() HookPatchType`

GetPatchType returns the PatchType field if non-nil, zero value otherwise.

### GetPatchTypeOk

`func (o *UpdateHookBody) GetPatchTypeOk() (*HookPatchType, bool)`

GetPatchTypeOk returns a tuple with the PatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchType

`func (o *UpdateHookBody) SetPatchType(v HookPatchType)`

SetPatchType sets PatchType field to given value.

### HasPatchType

`func (o *UpdateHookBody) HasPatchType() bool`

HasPatchType returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateHookBody) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateHookBody) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateHookBody) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateHookBody) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


