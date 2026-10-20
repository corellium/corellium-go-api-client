# KernelThreadV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KernelId** | Pointer to **NullableString** | Kernel Thread ID | [optional] 
**Tid** | Pointer to **NullableFloat32** | Task ID | [optional] 
**Stack** | Pointer to **[]string** | Array of stack addresses | [optional] 

## Methods

### NewKernelThreadV1

`func NewKernelThreadV1() *KernelThreadV1`

NewKernelThreadV1 instantiates a new KernelThreadV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKernelThreadV1WithDefaults

`func NewKernelThreadV1WithDefaults() *KernelThreadV1`

NewKernelThreadV1WithDefaults instantiates a new KernelThreadV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKernelId

`func (o *KernelThreadV1) GetKernelId() string`

GetKernelId returns the KernelId field if non-nil, zero value otherwise.

### GetKernelIdOk

`func (o *KernelThreadV1) GetKernelIdOk() (*string, bool)`

GetKernelIdOk returns a tuple with the KernelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelId

`func (o *KernelThreadV1) SetKernelId(v string)`

SetKernelId sets KernelId field to given value.

### HasKernelId

`func (o *KernelThreadV1) HasKernelId() bool`

HasKernelId returns a boolean if a field has been set.

### SetKernelIdNil

`func (o *KernelThreadV1) SetKernelIdNil(b bool)`

 SetKernelIdNil sets the value for KernelId to be an explicit nil

### UnsetKernelId
`func (o *KernelThreadV1) UnsetKernelId()`

UnsetKernelId ensures that no value is present for KernelId, not even an explicit nil
### GetTid

`func (o *KernelThreadV1) GetTid() float32`

GetTid returns the Tid field if non-nil, zero value otherwise.

### GetTidOk

`func (o *KernelThreadV1) GetTidOk() (*float32, bool)`

GetTidOk returns a tuple with the Tid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTid

`func (o *KernelThreadV1) SetTid(v float32)`

SetTid sets Tid field to given value.

### HasTid

`func (o *KernelThreadV1) HasTid() bool`

HasTid returns a boolean if a field has been set.

### SetTidNil

`func (o *KernelThreadV1) SetTidNil(b bool)`

 SetTidNil sets the value for Tid to be an explicit nil

### UnsetTid
`func (o *KernelThreadV1) UnsetTid()`

UnsetTid ensures that no value is present for Tid, not even an explicit nil
### GetStack

`func (o *KernelThreadV1) GetStack() []string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *KernelThreadV1) GetStackOk() (*[]string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *KernelThreadV1) SetStack(v []string)`

SetStack sets Stack field to given value.

### HasStack

`func (o *KernelThreadV1) HasStack() bool`

HasStack returns a boolean if a field has been set.

### SetStackNil

`func (o *KernelThreadV1) SetStackNil(b bool)`

 SetStackNil sets the value for Stack to be an explicit nil

### UnsetStack
`func (o *KernelThreadV1) UnsetStack()`

UnsetStack ensures that no value is present for Stack, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


