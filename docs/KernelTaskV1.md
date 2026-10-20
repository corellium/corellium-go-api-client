# KernelTaskV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KernelId** | Pointer to **NullableString** | Kernel Task ID | [optional] 
**Name** | Pointer to **NullableString** | Thread name | [optional] 
**Pid** | Pointer to **NullableFloat32** | Process ID of task | [optional] 
**Threads** | Pointer to [**[]KernelThreadV1**](KernelThreadV1.md) |  | [optional] 

## Methods

### NewKernelTaskV1

`func NewKernelTaskV1() *KernelTaskV1`

NewKernelTaskV1 instantiates a new KernelTaskV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKernelTaskV1WithDefaults

`func NewKernelTaskV1WithDefaults() *KernelTaskV1`

NewKernelTaskV1WithDefaults instantiates a new KernelTaskV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKernelId

`func (o *KernelTaskV1) GetKernelId() string`

GetKernelId returns the KernelId field if non-nil, zero value otherwise.

### GetKernelIdOk

`func (o *KernelTaskV1) GetKernelIdOk() (*string, bool)`

GetKernelIdOk returns a tuple with the KernelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelId

`func (o *KernelTaskV1) SetKernelId(v string)`

SetKernelId sets KernelId field to given value.

### HasKernelId

`func (o *KernelTaskV1) HasKernelId() bool`

HasKernelId returns a boolean if a field has been set.

### SetKernelIdNil

`func (o *KernelTaskV1) SetKernelIdNil(b bool)`

 SetKernelIdNil sets the value for KernelId to be an explicit nil

### UnsetKernelId
`func (o *KernelTaskV1) UnsetKernelId()`

UnsetKernelId ensures that no value is present for KernelId, not even an explicit nil
### GetName

`func (o *KernelTaskV1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *KernelTaskV1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *KernelTaskV1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *KernelTaskV1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *KernelTaskV1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *KernelTaskV1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPid

`func (o *KernelTaskV1) GetPid() float32`

GetPid returns the Pid field if non-nil, zero value otherwise.

### GetPidOk

`func (o *KernelTaskV1) GetPidOk() (*float32, bool)`

GetPidOk returns a tuple with the Pid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPid

`func (o *KernelTaskV1) SetPid(v float32)`

SetPid sets Pid field to given value.

### HasPid

`func (o *KernelTaskV1) HasPid() bool`

HasPid returns a boolean if a field has been set.

### SetPidNil

`func (o *KernelTaskV1) SetPidNil(b bool)`

 SetPidNil sets the value for Pid to be an explicit nil

### UnsetPid
`func (o *KernelTaskV1) UnsetPid()`

UnsetPid ensures that no value is present for Pid, not even an explicit nil
### GetThreads

`func (o *KernelTaskV1) GetThreads() []KernelThreadV1`

GetThreads returns the Threads field if non-nil, zero value otherwise.

### GetThreadsOk

`func (o *KernelTaskV1) GetThreadsOk() (*[]KernelThreadV1, bool)`

GetThreadsOk returns a tuple with the Threads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreads

`func (o *KernelTaskV1) SetThreads(v []KernelThreadV1)`

SetThreads sets Threads field to given value.

### HasThreads

`func (o *KernelTaskV1) HasThreads() bool`

HasThreads returns a boolean if a field has been set.

### SetThreadsNil

`func (o *KernelTaskV1) SetThreadsNil(b bool)`

 SetThreadsNil sets the value for Threads to be an explicit nil

### UnsetThreads
`func (o *KernelTaskV1) UnsetThreads()`

UnsetThreads ensures that no value is present for Threads, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


