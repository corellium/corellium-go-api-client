# KernelThread

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KernelId** | **string** | Kernel thread ID (uint64_t). | 
**TaskId** | **float32** | Task ID. | 
**Stack** | **[]string** | Array of stack addresses. | 

## Methods

### NewKernelThread

`func NewKernelThread(kernelId string, taskId float32, stack []string, ) *KernelThread`

NewKernelThread instantiates a new KernelThread object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKernelThreadWithDefaults

`func NewKernelThreadWithDefaults() *KernelThread`

NewKernelThreadWithDefaults instantiates a new KernelThread object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKernelId

`func (o *KernelThread) GetKernelId() string`

GetKernelId returns the KernelId field if non-nil, zero value otherwise.

### GetKernelIdOk

`func (o *KernelThread) GetKernelIdOk() (*string, bool)`

GetKernelIdOk returns a tuple with the KernelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelId

`func (o *KernelThread) SetKernelId(v string)`

SetKernelId sets KernelId field to given value.


### GetTaskId

`func (o *KernelThread) GetTaskId() float32`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *KernelThread) GetTaskIdOk() (*float32, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *KernelThread) SetTaskId(v float32)`

SetTaskId sets TaskId field to given value.


### GetStack

`func (o *KernelThread) GetStack() []string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *KernelThread) GetStackOk() (*[]string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *KernelThread) SetStack(v []string)`

SetStack sets Stack field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


