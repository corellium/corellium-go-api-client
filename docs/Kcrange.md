# Kcrange

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KernelExtension** | **string** | Kernel extension. | 
**Range** | **[]string** | Start and end address of the kernel extension range. | 

## Methods

### NewKcrange

`func NewKcrange(kernelExtension string, range_ []string, ) *Kcrange`

NewKcrange instantiates a new Kcrange object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKcrangeWithDefaults

`func NewKcrangeWithDefaults() *Kcrange`

NewKcrangeWithDefaults instantiates a new Kcrange object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKernelExtension

`func (o *Kcrange) GetKernelExtension() string`

GetKernelExtension returns the KernelExtension field if non-nil, zero value otherwise.

### GetKernelExtensionOk

`func (o *Kcrange) GetKernelExtensionOk() (*string, bool)`

GetKernelExtensionOk returns a tuple with the KernelExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKernelExtension

`func (o *Kcrange) SetKernelExtension(v string)`

SetKernelExtension sets KernelExtension field to given value.


### GetRange

`func (o *Kcrange) GetRange() []string`

GetRange returns the Range field if non-nil, zero value otherwise.

### GetRangeOk

`func (o *Kcrange) GetRangeOk() (*[]string, bool)`

GetRangeOk returns a tuple with the Range field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRange

`func (o *Kcrange) SetRange(v []string)`

SetRange sets Range field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


