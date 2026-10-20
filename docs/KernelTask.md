# KernelTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KernelId** | **string** | Kernel task ID (uint64_t). | 
**Name** | **string** | Thread name. | 
**ProcessId** | **float32** | Process ID of task. | 
**Threads** | [**[]KernelThread**](KernelThread.md) | Threads belonging to this task. | 

## Methods

### NewKernelTask

`func NewKernelTask(kernelId string, name string, processId float32, threads []KernelThread, ) *KernelTask`

NewKernelTask instantiates a new KernelTask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKernelTaskWithDefaults

`func NewKernelTaskWithDefaults() *KernelTask`

NewKernelTaskWithDefaults instantiates a new KernelTask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKernelId

`func (o *KernelTask) GetKernelId() string`

GetKernelId returns the KernelId field if non-nil, zero value otherwise.

### GetKernelIdOk

`func (o *KernelTask) GetKernelIdOk() (*string, bool)`

GetKernelIdOk returns a tuple with the KernelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelId

`func (o *KernelTask) SetKernelId(v string)`

SetKernelId sets KernelId field to given value.


### GetName

`func (o *KernelTask) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *KernelTask) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *KernelTask) SetName(v string)`

SetName sets Name field to given value.


### GetProcessId

`func (o *KernelTask) GetProcessId() float32`

GetProcessId returns the ProcessId field if non-nil, zero value otherwise.

### GetProcessIdOk

`func (o *KernelTask) GetProcessIdOk() (*float32, bool)`

GetProcessIdOk returns a tuple with the ProcessId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessId

`func (o *KernelTask) SetProcessId(v float32)`

SetProcessId sets ProcessId field to given value.


### GetThreads

`func (o *KernelTask) GetThreads() []KernelThread`

GetThreads returns the Threads field if non-nil, zero value otherwise.

### GetThreadsOk

`func (o *KernelTask) GetThreadsOk() (*[]KernelThread, bool)`

GetThreadsOk returns a tuple with the Threads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreads

`func (o *KernelTask) SetThreads(v []KernelThread)`

SetThreads sets Threads field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


