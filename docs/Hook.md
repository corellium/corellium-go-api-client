# Hook

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** | Hook identifier. | 
**Label** | **string** | Hook label. | 
**Address** | **string** | EL1/kernel virtual address, in hexadecimal, where the hook fires: the patch runs each time the device executes the instruction at this address.  If a slide is applied at runtime, do not include it. | 
**Patch** | **string** | The code to run when the hook fires, in the language given by &#x60;patchType&#x60;. | 
**PatchType** | [**HookPatchType**](HookPatchType.md) |  | 
**Enabled** | **bool** | Whether the hook runs. Disabled hooks are kept but skipped. | 
**InstanceId** | **string** | Owning instance identifier. | 
**CreatedAt** | **time.Time** | Creation timestamp. | 
**UpdatedAt** | **time.Time** | Last update timestamp. | 

## Methods

### NewHook

`func NewHook(identifier string, label string, address string, patch string, patchType HookPatchType, enabled bool, instanceId string, createdAt time.Time, updatedAt time.Time, ) *Hook`

NewHook instantiates a new Hook object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHookWithDefaults

`func NewHookWithDefaults() *Hook`

NewHookWithDefaults instantiates a new Hook object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *Hook) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *Hook) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *Hook) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetLabel

`func (o *Hook) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *Hook) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *Hook) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetAddress

`func (o *Hook) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Hook) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Hook) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetPatch

`func (o *Hook) GetPatch() string`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *Hook) GetPatchOk() (*string, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *Hook) SetPatch(v string)`

SetPatch sets Patch field to given value.


### GetPatchType

`func (o *Hook) GetPatchType() HookPatchType`

GetPatchType returns the PatchType field if non-nil, zero value otherwise.

### GetPatchTypeOk

`func (o *Hook) GetPatchTypeOk() (*HookPatchType, bool)`

GetPatchTypeOk returns a tuple with the PatchType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchType

`func (o *Hook) SetPatchType(v HookPatchType)`

SetPatchType sets PatchType field to given value.


### GetEnabled

`func (o *Hook) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Hook) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Hook) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetInstanceId

`func (o *Hook) GetInstanceId() string`

GetInstanceId returns the InstanceId field if non-nil, zero value otherwise.

### GetInstanceIdOk

`func (o *Hook) GetInstanceIdOk() (*string, bool)`

GetInstanceIdOk returns a tuple with the InstanceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstanceId

`func (o *Hook) SetInstanceId(v string)`

SetInstanceId sets InstanceId field to given value.


### GetCreatedAt

`func (o *Hook) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Hook) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Hook) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Hook) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Hook) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Hook) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


